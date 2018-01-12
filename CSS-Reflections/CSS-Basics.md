### What is the difference between inline, internal, and external styling? Which will you most commonly use?

* Inline styling refers to using the style attribute within an HTML tag on the page. This is considered a bad practice with modern standards.

* Internal styling is creating a style tag within the head tag for an HTML document. This styling is used for if a document will have a unique style other than that you have defined in an external stylesheet.

* **External styling** This is the most common styling of an HTML document. An external style sheet is created (style.css) and usually saved within the same directory as the HTML document. A link to the css document must be placed in the head section of the HTML doc.

### Why are id selectors inhibiting?

* An ID selectors can only be used once in an HTML ,
this is done in practice when an element will never change styles throughout it's life. This is an inflexible method of selecting an element for styling.

### Look at the HTML code below,

```
<div class = "foo">
 <!-- 1 -->
 <p></p>
  <!-- 2 -->
 <p></p>
 <div class = "altfoo">
   <!-- 3 -->
   <p></p>
 </div>
</div>

```
### Is the <div> with class altfoo an immediate child of the <div>
 with foo? Why or why not?

* Altfoo is an imediate child of foo because it is directly nested within the div class foo.

### Referring to the HTML code from above, which element(s) will the following selector select? .foo p {}

* This will select all p that reside within the .foo class.
p1, p2 and p3

### Referring to the HTML code from above, Which element(s) will the following selector select? .foo > p{}

* This will select the immediate p children of the .foo class.
p1, p2

### Look at the HTML code below, what psuedo-selector would you write to select the first <p> element (Only the first one!).

* div:first-child will select only the first p element. This div should have a class. Does not seem like a good practice to group 4 p elements all with different classes inside a div tag.

```
<div>
 <p class = "text">One</p>
 <p class = "text">Two</p>
 <p class = "text">Three</p>
 <p class = "text">Four</p>
</div>

```


#### CSS


```
h2
{
  color:fuchsia;
}

#idselector
{
  background-color:turquoise;
}

.selectorclass
{
  opacity:.5;
}

div.selectorclass
{
  border-style:solid;
}

```
