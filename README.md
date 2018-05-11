**FullCssCourse**

Academind CSS course adopted for therailsshop

Through this course we shall build a project and be able to put into practice all the knowledge that we acquire here.

**Lets get started**

The course is divided into three parts.

**The basic track**

  Here we shall cover

  * Getting started
  * The basics
  * Dive deeper into some concepts
  * More on selectors and CSS modules
  * Practicing the basics
  * Positioning

**The advanced track**

  Here we shall cover

  * Background images
  * Dimensions units and sizes
  * Javascript and CSS
  * Responsive design
  * Forms and styling forms
  * Advanced fonts

**The expert track**

  Here we shall cover

  * FlexBox
  * CSS grid
  * Transformations
  * Transitions and animations
  * Writing future proof CSS
  * Saas

**Course prerequisites**

  * Basic Web development and HTML Knowledge
  * Advanced Web Development Knowledge
  * CSS Knowledge

**How to get the best out of the course**

  * Code along and watch the videos(Contact me for these)
  * Do the exercises because practicing is everything
  * Debug your own errors
  * Ask me any questions you might have(alexshyaka@therailsshop.club)

**Which tools shall we use**

  * Code editors--you are free to use sublime text or visual studio code.
  * Use chrome because of its strong developer tools.

**Diving into the basics**

**What we shall cover in this course unit**

  * How to add CSS to HTML
  * Setting up CSS rules
  * Selectors, Properties and Values
  * Conflicting styles

**A note about combinators that is very important**

**Adjacent sibling**

    h2 + p
    {
      color:red;
    }

For this to work

* Elements share the same parent
* Second element comes immediately after first element

  **General sibling**

    h2 ~ p
    {
      color: red;
    }


For this to work

* Elements share the same parent
* Second element comes after the first element. It does not have to be immediately after

  **Child sibling**

    div > p
    {
      color: red;
    }

For this to work

* Second element is a direct child of first element

**Descedant sibling**

  div p
  {
    color: red;
  }


For this to work

* Second element is a descedant of the first element and not a direct child

**Resources**
  ..We have covered selectors, properties and values
  .. No need to memorize the entire list
  https://developer.mozilla.org/en-US/docs/Web/CSS/Reference

**Summary**

 CSS works with rules

Different types of selectors and these are:

* Element selectors like h1
* Class selectors
* Attribute selectors like [disabled]
* ID selectos
* Universal selectors

Properties and values

Inheritance and Specifity

* Parent styles are generally inherited
* Multiple rules can apply to one element
* Specifity resolves multiple rules conflicts
* Inheritance defaults can be changed

**Diving Deeper- Section 3**

* The BoxModel
* Height and Width
* The Display property
* Properties worth to remember
* Pseudo classes and elements

**Note**

  * Margin collapsing- This means two elements on top of each other both have margins
  and the larger margin always wins. This is inforced by the box model. So it is advised to use margin-top or margin-bottom if you want to enforce one
  * All block elements like sections all have a width of 100 percent. They take the full length of the containing element.
  * The height behaves a bit different though. The parent elements have to cascade the property down to the target element if you use height percentange
  * Box-sizing is by default set to content-box which is the height and width of the content only without including the padding and the border but if you set it to border-box then it will include them and it is considered good practice.
  * Always better to set it using the universal element if you prefer your height and width to include the padding and border of the content


      * {

        box-sizing: border-box;

        }

  * The prefered way of setting the box-sizing property


      box-sizing: border-box;


  * The default way

      box-sizing: content-box;
**Pseudo Classes and Pseudo elements**

  * Pseudo class: defines a style of a special state of an element like the hover or active state

  Syntax: :class name
  * Pseudo element: defines the style of a special part of an element

  Syntax: : : element name

  * More on Pseudo classes and elements [here](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)

  * The Box Model is very important to understand how it works especially when it comes to how it works with box-sizing with the width and height.

  **More on selectors and CSS features**

   * Use classes if you want to style your pages and not id unless they symantically make sense but your first choice should be to use classes
   * You can use IDs to link to different places on the same page and this functionality is baked into HTML and thats one of the ways in which they can be useful but not to use necessarily for styling pages

   Note
   * :not() Read abt it [here]("https://developer.mozilla.org/en-US/docs/Web/CSS/:not")





