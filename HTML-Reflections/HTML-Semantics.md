### Why is accessibility so important?

* Ensures all users have a good experience on a website are able to access the intended information in the intended manner.

* Search Engine ranking is influenced by accessibility.

* Allows screen readers to access the material in a similar manner as intended for the information.

### What are some forms of accessibility as it relates to web development?

* Semantic HTML - important for screen readers
* Logical website flow
* Contrast between text and background
* Img tags that have an alt attribute
* Controls for videos and audio
* No auto-play of videos, audio or media
* UI that clean, light and interpretable

### In your own words, what does semantic mean?

Descriptive term of something that has a logical flow and is interpretable.

### What is semantic HTML?

Semantic HTML is one that has a logical backbone and flow. HTML tags are used in a way that meaning is holistically presented through flow of content.

### What are some common accessibility issues your end users might have?

* Websites with heavy table skeleton.

* Websites that use cpu for loading.

* Not having a text alternative for images. (alt)

* Failure to use Semantic HTML or descriptive tags.

* Not having labels for input fields. (label)

* UI Issues: Contrast issues, text size issues, text font issues, notification placement issues.

* Auto-play content

* Extensive advertisement placement.

a. What are some steps you would take to make their experience on your site better?

* Use logical flow and Semantic HTML with id's for tags and labeled input.

* Try to avoid creating informational websites with a heavy processor intensive tasks.

* Always utilize an alt attribute for images.

* Use material design or a design framework, and test UI for usability.


### What do we use the <label> tag for?

* The label tag gives relative meaning/definition to corresponding inputs.

### Initial code

```
<html>
  <head>
    <meta charset="utf-8">
    <title>Cats are the best!</title>
  </head>
  <body>
    <table>
      <tr>
        <td>Sidebar will go here</td>
        <td id='main'>
          <h2>My awesome site</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
          <p>
            Check out this cat:
            <img src="https://upload.wikimedia.org/wikipedia/commons/4/4d/Cat_November_2010-1a.jpg">
            <br>
            <br>
            <br>
          </p>
          <h1>Isn't it a great cat?!?</h1>
        </td>
      </tr>
    </table>
  </body>
</html>

```

## Cleaned up code
```

<html>
  <head>
    <meta charset="utf-8">
    <title>Cats are the best!</title>
  </head>
  <body>
    <!--Move the h1 header to the header tag -->
    <header>
      <h1>My awesome site</h1>
    </header>
      <!--Remove Table tags, not required in this example -->
    <aside>
       <!-- Comment out the placeholder text, Sidebar will go here-->
    </aside>
    <!--Remove td row with id main, use main tag -->
    <main>
       <!-- change all the headers in main to paragraphs for later styling-->
       <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
       <!--change the p tag into a smaller header for the into text-->
       <p>
         Check out this cat:
       </p>
       <!--Add a alt for img accessibility, and changed image size-->
       <img src="https://upload.wikimedia.org/wikipedia/commons/4/4d/Cat_November_2010-1a.jpg" alt ="Cat" height = "400px" width = "300px">
       <!--remove all the br tags-->
      <!--Replaced static question with form-->
      <form action="cat_survery.php" method ="post" >
        <fieldset>
       <label for = "inputText">Isn't it a great cat?
         <input type = "text", name = "inputText">  
       </label>
      <input type = "submit" value = "Submit">
       </fieldset>
     </form>
    </main>
    <footer>
      <!--created footer-->
    </footer>
  </body>
</html>



```
