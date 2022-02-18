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

To display multiple shapes, we need to define a 
[shape replacement](https://github.com/MtnViewJohn/context-free/wiki/Shape-Replacements) 
that contains the combination of shapes we wish to display.
Here is a program that draws a house:

```
startshape house

shape house {
  SQUARE []
  TRIANGLE [y .75 size 1.5 1]
}
```

The `SQUARE` is modified by the `b` argument, which adjusts the brightness level.

The `TRIANGLE` is modified by a couple of arguments:
* `y .75` instructs it to place the `TRIANGLE` `.75` `y` units away from the `SQUARE`.
* `size 1.5 1` instructs it to make the `TRIANGLE` 1.5 units wide and 1 unit tall.

Colors are specified using `hue`, `saturation`, and `brightness` values. Hues 
range from 0 to 360; the saturation and brightness values range from -1 to 1.

The code below is the same shape but with coloration:

```
startshape house

shape house {
  SQUARE [hue 30 saturation .5 brightness .5]
  TRIANGLE [y .75 size 1.5 1 h 120 sat .8 b .9]
}
```

Note that `hue`, `saturation`, and `brightness` can be abbreviated.

Write a program with the following features:
* It creates a [shape replacement](https://github.com/MtnViewJohn/context-free/wiki/Shape-Replacements) consisting of five primitive shapes.
* It uses all three primitive shapes.
* Each shape should be in a distinct location. Overlapping is okay.
* Each shape should be a different color.
* Each shape is altered in one or more of the following ways:
  * Rotated
  * Resized
  * Skewed

## Step 2: Repetition

Shapes can be repeated inside of a loop. Here are two examples:

```
startshape pattern1

shape pattern1 {
  loop 6 [r 60] TRIANGLE [y .2 h 60 sat 1.0 b 1.0]
}
```

```
startshape pattern2

shape pattern2 {
  loop 6 [r 60 h 30 sat 1 b 1] TRIANGLE [y .2]
}
```

Run each of these programs. Then answer the following questions:
1. What are the similarities and differences of the drawings these programs
produce?

2. What syntactic differences produce these differences?

Shapes can also be repeated using recursion:

```
startshape test

shape spike {
    SQUARE [b 0.5]
    spike [x 0.5 size 0.95]
}
```

Try out `spike`. Then answer the following questions:

3. Why do you think the recursion terminates, even though it does not have a base case?

4. Add `y 0.5` to the recursive call. How does it change its behavior?

5. Change the `size` parameter to `1.05`. How does it change its behavior?

## Step 3: Research

Browse the [Gallery](https://www.contextfreeart.org/gallery/). Select three
pieces of art that you find appealing. For each one:
6. Why do you find it appealing?
7. How does it work? Peruse the [documentation](https://github.com/MtnViewJohn/context-free/wiki) to decode the various language constructs each example utilizes. Explain each novel language construct you encounter.

**Note**: There were significant changes to the language syntax going to Version 3, which is the current version.
Some of the gallery art uses Version 2. Read over the 
[Version 2 syntax guide](https://github.com/MtnViewJohn/context-free/wiki/Version-2-Syntax) to understand the syntax
differences. 

## Step 4: Creation

Write a Context-Free Art program to generate an aesthetically appealing
artwork. You are welcome to create anything you like, subject to the following
constraints:
* Incorporate at least one concept from each of the three examples you selected in Step 3.
* The work you create should also take inspiration from the image you 
contributed in [Lab 1](https://hendrix-cs.github.io/csci270/labs/corpus.html). 
This inspiration is broadly conceived - you may seek to imitate a selection
of shapes and/or colors from your contributed artwork. 

Answer the following questions:
8. How did you utilize each concept you utilized from the three examples you selected?
9. In what way did you take inspiration from your contributed artwork?

## To Submit via Teams

* The `cfdg` files for your programs.
* A PDF document containing:
  * Answers to all of the above questions.
  * Source code for your programs.
  * Images generated by your programs.

