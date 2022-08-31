
In this step our goal is to set up the basic boilerplate code and link the `style.css` file with the `index.html` file. 

Before jumping into the code of the project, make sure that you understand the basic structure of the HTML5 document, what the boilerplate code does. 

Make sure that you understand 

* `<!DOCTYPE html>` tag. (We use it to tell the browser that we are using HTML5 and not any previous versions of HTML)
  
* `<html>` tag. (We use it to tell the browser that the content inside the `<html>` tag is HTML)
  
* `<head>` tag. (We use it to tell the browser that the content inside the `<head>` tag is metadata about the HTML document)
  
* `<body>` tag. (We use it to tell the browser that the content inside the `<body>` tag is the content of the HTML document)
  
* `<link>` tag. (We use it to tell the browser that we want to link an external file with the HTML document)

It is advised that you go though the [HTML & CSS Fundamentals course](https://codedamn.com/learn/html-css) for a better understanding of the HTML and CSS fundamentals.

In this step you are tasked to create a new `style.css` file and link it with the existing `index.html` document, by implementing this the styles we write in the `style.css` file will be applied to the HTML document.You'll also be applied few CSS Properties to the HTML document. 

1. Add a new `<div> </div>` tag inside the `<body>` element. Give the `<div>` element an id `gallery-container`, this element will act as a container and will have all the gallery images inside this element. 
   
2. Create a new file named `style.css` in the same directory as the `index.html` file.

3. Link the `style.css` file with the `index.html` file by adding the following line of code inside the `<head>` tag of the `index.html` file, using the `<link>` tag. 

    ```html
    <link rel="stylesheet" href="style.css">
    ```
    Here the `rel` attribute specifies the relationship between the HTML document and the linked file. The `href` attribute specifies the path to the linked file.

    Now that we have linked the CSS file it's time to add basic styling to the HTML Document

4. Set `margin`, `padding` to `0` and `box-sizing` to `border-box` to all the elements of the HTML Document. 

    ```css
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    ```

    `margin`, `padding` and `box-sizing` are the CSS properties that are used to set the spacing between the elements of the HTML document.

    By settings this values globally to all the elements this removes the different pre-defined (which are set by browsers) margins and paddings of the elements and makes the styling of the elements easier.

5. Set the `background-color` of the `body` element to `#242629`.

    ```css
    body {
        background-color: #242629;
    }
    ```
    The six digit value is written in hexadecimal (base 16) and here 

   * the first two digits `24` represent the intensity of red
   * the next two digits `26` represent the intensity of Green 
   * the last two digits `29` represent the intensity of Blue

Now that we setup the basic boilerplate code and linked the `style.css` file with the `index.html` file, let's move on to the next step and create the HTML 