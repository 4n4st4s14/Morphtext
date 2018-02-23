Morphext
========

[![Dev Dependency Status](https://david-dm.org/MrSaints/Morphext/dev-status.svg?style=flat)](https://david-dm.org/MrSaints/Morphext#info=devDependencies)

A simple, high-performance and cross-browser [jQuery][jquery] rotating / carousel plugin for text phrases powered by [Animate.css][animatecss]. It is more succinctly described by [Softpedia](http://webscripts.softpedia.com/script/Text-Management/Text-Tools/Morphext-82875.html) as:

> A [jQuery][jquery] plugin for creating text-based carousels, rotating small or large pieces of text one after the other, just like a slider does with images... This can be a great tool for displaying catch phrases, mission statements, tag lines, and so on.

If you would like to achieve a similar effect with more flexibility (e.g. out animation) and with HTML objects rather than text phrases (e.g. unordered list items), please check out [Morphist][morphist].

[Website][website] / [Demo][demo]


Install
-------

Download from the [project page][downloads].

Install with [Bower][bower]: `bower install --save Morphext`


Usage
-----

1. Import the latest [Animate.css][animatecss] and [jQuery][jquery] library into your HTML.

2. Import `morphext.css` and include `morphext.min.js` in your HTML document.

3. Encapsulate your rotating phrases in an element and separate each phrase with a comma or a separator of your choice:

    ```html
    I am a <span id="js-rotating">So Simple, Very Doge, Much Wow, Such Cool</span> Text Rotator
    ```

4. Trigger the plugin by calling Morphext() on the element containing the rotating phrases:

    ```js
    $("#js-rotating").Morphext();
    ```

A demo titled `index.html` is included in this repository. Open it to see the end-result.


