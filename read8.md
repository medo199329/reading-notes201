# From the Duckett HTML book:

CSS  layout techniques allow positioning elements in a webpage in normal layout flow, with the help of the parent container.

*example of basic layout*

![](https://media.geeksforgeeks.org/wp-content/uploads/website_layout-300x268.png)

**Positioning Elements types**

(position:static ,
position:relative, 
position:absolute ,)


every one of them has its own features we well be discussing further in this course.

# Floats

The float CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it,Meaning it move the text left or right.

float: none;
float: left;
float: right;


# clearing float

Sometimes you may want to force an item to move below any floated elements. For instance, you may want paragraphs to remain adjacent to floats, but force headings to be on their own line.
clear property can be none, left, right, both, inherit, inline-start, and inline-end.


# Positioning

sets how an element is positioned in a document. The top , right , bottom , and left.

h2 {
  position: absolute;
  left: 100px;
  top: 150px;
}


# flex 

The main idea behind the flex layout is to give the container the ability to alter its items’ width/height (and order) to best fill the available space.


