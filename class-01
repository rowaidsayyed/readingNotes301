# Welcome 301d4
## Responsive Web Design (RWD)
Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.

## Responsive vs. Adaptive vs. Mobile
Responsive and adaptive web design are closely related, and often transposed as one in the same.
* Responsive means to react quickly and positively to any change
* Adaptive means to be easily modified for a new purpose or situation

 A combination of the two is **ideal**, providing the perfect formula for functional websites

* Mobile means to build a separate website commonly on a new domain solely for mobile users.

## Flexible Layouts
Responsive web design is broken down into three main components
1. flexible layouts : the practice of building the layout of a website with a flexible grid
2. media queries :  provide the ability to specify different styles for individual browser and device circumstances
3. flexible media.

### flexible layouts
The formula is based around taking the target width of an element and dividing it by the width of it’s parent element. 
The result is the relative width of the target element.

> target ÷ context = result 

### media queries
There are different ways to use media queries
* @media rule inside of an existing style sheet
* @import importing a new style sheet 

The media query expression that follows the media type may include different media features and values

#### Logical Operators in Media Queries
There are three different logical operators available for use within media queries, 
* 'and'
* 'not'
* 'only'

#### Media Features
Here are some Media Features
* Height 
* Width
* Orientation
* Aspect Ratio	
* Resolution

#### mobile first
One popular technique with using media queries is called 'mobile first'
which use styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.

### Flexible Media
As viewports begin to change size media doesn’t always follow suit. Images, videos, and other media types need to be scalable, changing their size as the size of the viewport changes.
One quick way to make media scalable is by using the max-width property with a value of 100%. Doing so ensures that as the viewport gets smaller any media will scale down according to its containers width.


### float
The float property allows us to take an element in normal flow and place it as far to the left or right of the containing
element as possible.
When we use the float property, we should also use the **width property** to indicate how wide the floated element should
be.

#### Clearing Floats
The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. 


### grid systems
#### Context
A block level element is as wide as the parent it's inside
#### Columns
To make them next to each other, we just need to float them and apply widths
#### Clearing Context
The parent element will collapse to zero height since it has only floated children. so fix that by clearing it.
#### Gutters
The hardest part about grids is gutters
The steps toward this are
1. use 'box-sizing: border-box'
2. applying a fixed padding to the right side of all columns except the last one.

## Scalable and Modular Architecture for CSS (SMACSS)
SMACSS more style guide than rigid framework. 
SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process.

### There are five types of categories:
1. Base
2. Layout
3. Module
4. State
5. Theme

**Base rules** are the defaults. They are almost exclusively single element selectors but it could include attribute selectors, pseudo-class selectors, child selectors or sibling selectors. Essentially, a base style says that wherever this element is on the page

**Layout rules** divide the page into sections. Layouts hold one or more modules together.

**Modules** are the reusable, modular parts of our design. They are the callouts, the sidebar sections, the product lists and so on.

**State rules** are ways to describe how our modules or layouts will look when in a particular state. 

**Theme rules** are similar to state rules in that they describe how modules or layouts might look

### Naming Rules
naming convention also makes it easier to find which file a style belongs to.
