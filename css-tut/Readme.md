Targeting Elements with css

Targeting Css tags are very simple,it is one of the ways in which we can target and style our html elements.


TARGETING CLASSES AND IDS.

a class can be used to target multiple elements on a page while Ids can be uses to target only one particular element on a page.

CASCADE AND CSS CONFLICTS.
its wen u have two selectors or two rules of same selector given after the same tags in your document and you have got properties withing those rules that are different from each other.

INHERITANCE Tree
```html
<body>
  <div>
    <p>Text<p>
  </div>
  <h1>Text</h1>
</body> 


THE IMPORTANT DECLARATION : this is a css rule that is used to make a property important and by that i mean that nothing else can overide it






TARGETING MULTIPLE ELEMENTS: all you need to do is write one rule with all the tags or element you want to target in it and you can write multiple selectors on one line.



DESCENDANT SELECTORS:
```html
<body>
  <div>
    <h1>Text</h1>
  </div>
  <h1>Text</h1>
</body>


CHILDREN: 

```css
#main-content > p{

}

> is called the child combinator,it just saying that you should give this style to all direct children that are p tags 


ADJACENT SELECTORS: adjacent selector is a selector that selects an element which comes directly after another element...we do this by using the adjacent combinator which is the plus sign(+)



ATTRIBUTE SELECTORS:

```css
a[href$='pdf']{
  color: green; //what the $ there means is that is should pick all the href links that ends with pdf 
}

a[href^='http]{
  color: pink; //the carrot symbol (^) there means that is should go into the a tags and pick all href that starts with http and style it.
}



PSEUDO-CLASSES:pseudo classes are special keywords that go after selectors, they are like extension of selectors..they help us target things that we could not be able to target with normally with css,things like special behavioural states,advanced structural elements.

two groups: we have dynamic and structural pseduo classes

Dynamic pseudo classes: allow us to style an element in relation to user actions such as... whether a link is being hovered over .whether a button is being pressed etc.

Structural pseudo classes: allow us to style elements based on an advanced structural techniques not possible from oridinary Css selectors.
