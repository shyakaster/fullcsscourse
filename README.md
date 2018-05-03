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

``html
    h2 + p
    {
      color:red;
    }

..For this to work

  * Elements share the same parent
  * Second element comes immediately after first element

  **General sibling**

  ``html
    h2 ~ p
    {
      color: red;
    }


..For this to work

  * Elements share the same parent
  * Second element comes after the first element. It does not have to be immediately after

  **Child sibling**

  ``html
    div > p
    {
      color: red;
    }

..For this to work

  * Second element is a direct child of first element

**Descedant sibling**

``html
  div p
  {
    color: red;
  }


..For this to work

  * Second element is a descedant of the first element and not a direct child

**Resources**
  ..We have covered selectors, properties and values
  .. No need to memorize the entire list
  https://developer.mozilla.org/en-US/docs/Web/CSS/Reference

**Summary**
 ..CSS works with rules
 ..Different types of selectors and these are:
    *Element selectors like h1
    *Class selectors
    *Attribute selectors like [disabled]
    *ID selectos
    *Universal selectors
 ..Properties and values
 ..Inheritance and Specifity
    *Parent styles are generally inherited
    *Multiple rules can apply to one element
    *Specifity resolves multiple rules conflicts
    *Inheritance defaults can be changed
