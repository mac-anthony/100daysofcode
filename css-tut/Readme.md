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