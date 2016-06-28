CSS Centering
===========

Purpose
------

The purpose of this lecture is to teach students how to center elements, block level and inline-block, vertically and horizontally. Many students may become frustrated when trying to center elements, especially vertically, because they expect it to be simple, like in MS Word or Photoshop. This lecture should clarify that while centering elements in CSS is more complicated than you might expect, there are some reliable patterns you can use for centering elements. 

horizontal
-------
- block elements (width required)
    - `margin: 0 auto; width: 400px;`
- inline elements (on parent)
    - `text-align: center;`

vertical
---------
- line-height (only with one line of text)
    - set fixed height on parent, and same line-height on child
    - `vertical-align:middle` on child
- table
    - `.outer { display: table; }` 
    - `.inner { display: table-cell; vertical-align: middle; }`
- css3 transform        
    - `top: 50%;`
    - `transform: translateY(-50%);`