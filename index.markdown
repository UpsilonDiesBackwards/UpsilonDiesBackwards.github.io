---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title:
---
<body>
    <h1>Upsilon Dies Backwards</h1>
    <div class="slider">
        <div class="images">
            <img src="./assets/images/slide1.png" class="m1" alt="slideshowImage1" id="slideshowImage" width="600" height="600">
        </div>
        <div class="dots">
            <label for="slideshowImage1" onclick="changeIcon1();"></label>
            <label for="slideshowImage2" onclick="changeIcon2();"></label>
            <label for="slideshowImage3" onclick="changeIcon3();"></label>
        </div>
    </div>
    <script src="/assets/javascript/slideshow.js">
</body>