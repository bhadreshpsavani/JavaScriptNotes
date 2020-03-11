Faster Online Compiler: [JsBin](https://jsbin.com/tediqajefo/edit?js,console,output)

Articles: [reference-and-copying-objetcs--arrays-in-javascript](https://dev.to/simo_benhida/reference-and-copying-objetcs--arrays-in-javascript-2h23)

### WebPacks: 
Webpack loaders let you load them directly in Javascript from files in the 'src' directory.

Webpack enables this by parsing the contents of the CSS, image, and font files you want to import and making those contents available as values stored in a JavaScript module.

### React:
This makes it simple to integrate these assets into your app build and handle all your frontend dependencies with one tool.

In a Javascript file, it would be safe to delete an unused imported library like this. But in JSX, we have to include React because the JSX tags will be compiled into calls to  `React.createElement` , and the code would crash if the  `React`  object wasn't present to reference.

### Q/A:

1. Which of these problems is React least suited to address?
-Slow initial page loads leading to a high bounce rate.

2. statements is true about React?
- Components are similar to functions in Javascript, and can be written as functions.
- Components are modular UI elements.
- It's OK to nest components. This is called composition.
- EmberJS and Angular both separate template files from Javascript, whereas in React you just build elements directly in Javascript.
- keeps the DOM in sync with your data.
- React isn't a full-fledged application framework. It's job is to update the DOM to reflect changes in your data.

3. How does React handle non-javascript assets like CSS and web fonts?
- CSS, web fonts, images, and svg can be used as normally in HTML, but can also be loaded through the module system if they are included in the app's `src` directory.

4. On the initial page load, how does the browser get the initial HTML for the react app's web page?
- Via HTTP like every other website.

5. JSX is
- a templating language that compiles to Javascript.
- a superset of Javascript.
- mostly a syntactic convenience for building up javascript objects that describe DOM elements.
