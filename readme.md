Faster Online Compiler: [JsBin](https://jsbin.com/tediqajefo/edit?js,console,output)

Articles: [reference-and-copying-objetcs--arrays-in-javascript](https://dev.to/simo_benhida/reference-and-copying-objetcs--arrays-in-javascript-2h23)

WebPacks: Webpack loaders let you load them directly in Javascript from files in the 'src' directory.

Webpack enables this by parsing the contents of the CSS, image, and font files you want to import and making those contents available as values stored in a JavaScript module.

This makes it simple to integrate these assets into your app build and handle all your frontend dependencies with one tool.

In a Javascript file, it would be safe to delete an unused imported library like this. But in JSX, we have to include React because the JSX tags will be compiled into calls to  `React.createElement` , and the code would crash if the  `React`  object wasn't present to reference.
