# WebGL Introduction using JavaScript

This is a simple example of how to use WebGL to generate interactive images for the web or for applications.

WebGL is very similar to [OpenGL](https://www.opengl.org/documentation/).  Both are used frequently in visualization software and game development, as well as in many GUI libraries.

## Viewing this example

Open [index.html](./html/index.html) in the src folder with your browser.

## Following the source code

The slides can be found [here](https://docs.google.com/presentation/d/1DZ6c2s6tmMSXbPbZ1ciqVutgf5GtLpF4VDYHkAstsQs/edit?usp=sharing).
They explain the flow of the code in the examples.

Start by looking at the comments in the HTML.  Each HTML document invokes an exampleXX.js script which is where the logic for setting up and running WebGL is.
Go through the code in these scripts and see if you can complete the tasks.

There is also a script with helper functions called [commonFunctions.js](commonFunctions.js).

## Note on supporting libraries

This example uses an additional JavaScript library called [glMatrix](http://glmatrix.net/) to help with creating structures for matrices and vectors and performing mathematical operations on them.
It is worth noting that there are many other libraries out there that can aid in using WebGL, and libraries that use WebGL behind the scenes.

Consider using a package manager like [npm](https://www.npmjs.com/) to organize your dependencies in a larger project.

The Bootstrap file is a style sheet obtained from [Bootswatch](https://bootswatch.com/). It allows the elements in the HTML to be styled according to a theme.

## Note on compatibility

This example uses WebGL 2, which is not fully supported by all browsers.  [This table](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API#WebGL_2_2) shows which browsers support this functionality.

## Addtional resources

* [MDN Web Docs on WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API)
* [Khronos Group Specification](https://www.khronos.org/webgl/)
* [WebGL2 Fundamentals](https://webgl2fundamentals.org/)