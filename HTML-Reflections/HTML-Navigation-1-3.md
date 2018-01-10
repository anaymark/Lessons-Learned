### What are other words for anchor tags?
* Links
* Hyperlinks
### What is the blank attribute on anchor tags used for?
The blank attribute allows for a hyperlink to open a new tab in the browser when clicked.
### What are the two different types of lists?
* ul or unordered lists
* ol or ordered lists
### Why do we use the <nav> tag?
nav tag allows for easy navigation of a website, primarily with links at the top to page content. Allows for faster and efficient navigation.
### Is the following tag a link to something on the same page or a different page? <a href='#foo'>
This is a link to an id, which is a link to something on the page. If it was to external content it would have a URL or URI.

```
<!DOCTYPE html>
<html>
<head>
  <title>
    Invisible
  </title>
  </head>

  <body>  
    <header>
      <h1>HTML</h1>
      <nav>
        <ul>
          <li>
            <a href="index.html">Home			</a>
          </li>
          <li>
            <a href ="about.html">About
            </a>
          </li>
          <li>
            <a href="contact.html">Contact Us    </a>
          </li>
          <li>
            <a href="/prices.html">Best Prices in Town.
            </a>
          </li>
        </ul>
      </nav>
    </header>
    <aside>
    </aside>
    <section>
      <p style=color:blue>
    Lorem Ipsum</p>
  	  <img src="https://i.pinimg.com/736x/ea/3d/cf/ea3dcff8ed8e8939d98c96b81f747623--happy-faces-smiley-faces.jpg"  height="100"
    width="100">
    </section>
	<footer>
      <p>Copyright Notice
      </p>
    </footer>
  </body>
</html>

```
