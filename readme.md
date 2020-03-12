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
- Slow initial page loads leading to a high bounce rate.

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

### Concepts:
- Progressive Enhancement: First build the static html page, then add java script element 


## Practice Error Handling:
- Add a value to the component's state that represents whether the error is present.

- Add a validation function checks for the missing field, sets the error state, and returns a boolean expressing whether the form is valid.

- Run the validation function when the user submits the form, and don't allow the save to occur if the form is not valid.

- Add an error message in the view that will only appear if the error is present.

## Extend The Form Functionality:
- Add "edit" buttons next to the "delete" buttons in  ProductRow.js .

- When clicked, an edit button should set a value of state on the  <Products>  component, e.g.  this.state.formProduct , that indicates which product should populate the form  Since clicking different edit buttons should repurpose the form, you will need a way to update the form's state when the  formProduct  prop is changed. This doesn't happen automatically, but React provides a lifecycle hook that will allow you to call  setState  whenever a prop is changed. It's called componentWillReceiveProps.

- Hitting save on the form should update the products model on the  <Products>  component, and then reset the form to blank values and allow it to create new products. You can use the product's id to keep track of which product to change in the data model, and you can use the absence of an id to indicate when a new product (with a new unique id!) should be created.

- The point of this exercise is to make the form behave differently without adding components or changing the element markup in  <ProductForm> .
