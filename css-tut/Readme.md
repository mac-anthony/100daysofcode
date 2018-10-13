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

> is called the child selector or combinator,it just saying that you should give this style to all direct children that are p tags 


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


FontSize: when we think of fontsize we do it in two ways ... Absolute(px) or Relative(em,%)


fontfamily: are the style font style u give to  certain elements..

TextDecoration: 3 main text decoration are line-through,overline and underline ,if u want an elemet to inherit the style of the parent element then we can use the inherit keyword

Font-weight:this controls how dark or light the text displays on our web page


Transform: changing the letter casing ...e.g hello=> Hello (Capitalised)


Text-color: 2 types=> text/foreground colour
and background colour .

The Box Model:this is a way that elements represent themselves on a page in terms of space


CSS ANIMATIONS: makes animating web elements much easier,it eliminates the need for javascript/jquery for a lof of abimation effects.


Transform: we can use transform to add stretch an element or change the co-ordinates of an element

Scale:we have the scale which we use to scale or grow an element

Translate: means move the element from one place to anothe in a web page


Transition: takes an element from one state to another and how the element transitions between the two


Keyframes:are basically the power houz of the css animations  

Animation fill mode: decides what to do with the element outside the animation window   


Repeating Animations: animation-iteration-count enables the animation to occur for the specified amount of time..
Note: we either pass in the number of times we want the animation to occur or pass in the infinite property will we make the animation to run non-stop



Animation Direction: Animation Direction properties


Animation ShortHand:is a way we can do all our animations in just one property which is the animation property


Animation Timing Functions: this determines the rate at which the element thats been animated kind of goes from point a to b.


Chaining Animations:we chain an animation or 2 or more animation together by just using the comma at the end of each animation before starting a new one


Animating a Pop-up: 


Animating a Shopping Cart:




FLEX-BOX: normally we use different positional properties such as absolute,relative etc to move element around in our page or position them where we want  and we also use something like floats to create grid layouts or navigation system you knw that kind of jazz,we also come up with fixed heights for columns that we want to be equal in height. now alot tme we wrote css for this it seemed like a lot of work for what it achieved on the page so this is where css flexbox comes in and just blows all that out of the water.

flexbox is just a new css display type designed to help us craft css layout much easier. so basically it lets us control the position,the size and spacing of elements relative to their parent elements and each other  and also its very responsive.

BENEFITS OF USING FLEXBOX: 
1. we can create navigation bars and menus really easily without having to use floats or worrying about collapsing  of elements

2. its easier to create great layouts / grid layouts

3. its a good way to create bar charts

4. its a very easier way to create equal height and columns