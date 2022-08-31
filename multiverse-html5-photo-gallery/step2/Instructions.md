In this step the main goal is to build the HTML structure for the gallery project, the structure is a simple nested structure of `article > img + span` tags. It is okay if you are not able to understand the represent notation. 

Here the `>` means the child of the parent, the `+` means the sibling of the previous element.

1. Creating the `<article>` tag inside the `div#gallery-container` element.
   ```html
    <article>
    </article>
    ```

2. Adding `<image>` and `<span>` tag to `<article>` element
    ```html
     <article class="img-container">
        <img class="galley-image"src="">
        <span class="title"></span>
     </article>
     ```

     Now that the basic HTML structure is done, you can create 8 other copies of this for all the images. 

3. Setting the `src` attribute of each Individual `<img>` tag
making use of emmet to create the article>image>p tag structure along with class names 

    ```html
    <img src="assets/01.jpg">
    ```

    Make sure to set the `src` attributes for all the images in the assets folder.

4. Adding lorem text to the span tag. 

    The text we are adding to the span tag represents the title of the image. So we'll restrict the word length to three. 

    Emmet is available on Codedamn Playgrounds, you can directly write `lorem3` and hit space to generate three words inside the `<span>` tag. Or you can choose to write any three words of your choice for all the span tags.

    ```html
    <span class="caption">
    ```


Now that we are done with the HTML Structure for the project, we can move on to the next step to add styles the project.

#### For Geeks

It can seem daunting to write the HTML structure for the gallery project, well it is not. You can always make use of emmet to create a complex HTML structure with a single line of code. 
```
article.img-container*9>img.gallery-image[src=assets/0$.jpg]+span.title>lorem3
```

You can use this structure to create the same HTML Structure that we have written manually. You can learn more about emmet [here](https://docs.emmet.io/abbreviations/syntax/).