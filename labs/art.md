---
layout: work
type: Lab
num: 6
worktitle: Computational Art
---

## Materials

* For this week's lab, download and install the latest version of [Context-Free Art](https://www.contextfreeart.org/).

## Overview

Our goal in this lab is to learn how to algorithmically create aesthetically pleasing visual art. By using 
[Context-Free Art](https://www.contextfreeart.org/), we can write programs that generate artwork.

## Step 1: Primitive Shapes

A Context-Free Art program consists of a description of a shape in terms of other shapes, ultimately reduced 
to several [primitive shapes](https://github.com/MtnViewJohn/context-free/wiki/Primitive-Shapes). 
(The primitive shapes are `SQUARE`, `TRIANGLE`, and `CIRCLE`.)

Below is a minimal program for drawing a square:

```
startshape SQUARE
```

Enter this program and click the `Render` button, and you should see a large square appear. There are many ways 
to [customize its appearance](https://github.com/MtnViewJohn/context-free/wiki/Shape-Adjustments). For example, the 
following program will rotate the square by 45 degrees:

```
startshape SQUARE [rotate 45]
```

To display multiple shapes, we need to define a new shape that contains the combination of shapes we wish to display.
Here is a program that draws a house:

```
startshape house

shape house {

SQUARE []
TRIANGLE [y .75]
}
```