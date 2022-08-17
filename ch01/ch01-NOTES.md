# CHAPTER 01 

## Two ways to declare React Components

1)  ES6 Classes
   
   class HelloWorld extends React.Component {
    render(){ return <p>Hello, world!</p> }
   }

2)  Function Components ( ALTERNATE)

    function HelloWorld(){
        return <p>Hello, world!</p>;
    }

### KEYWORDS
* JSX - JavaScript eXtension Syntax - (HTML + JavaScript) 
* render() - needs to describe how the view should be represented in HTML 
* React Virtual DOM - fake representation of the Document Object Model (DOM)
* Document Object Model (DOM) - browser's HTML tree of a web page.
* Babel - ES6 JavaScript transpiler - transpiles es6 code to es5 that a browser can interpret and execute.
* ReactDOM - react library - pass 2 arguments
  * What we'd like to render
  * Where to render