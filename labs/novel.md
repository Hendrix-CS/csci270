---
layout: work
type: Lab
num: 11
worktitle: Visual Novel
---

## Materials

For this week's lab, download and install the latest version of 
[Ren'Py](https://www.renpy.org/).

## Overview

Our goal in this lab is to create a 
[visual novel](https://en.wikipedia.org/wiki/Visual_novel), 
a creative work that integrates text, music, and images. 

As the term "novel" suggests, a visual novel tells a story primarily by means 
of text, with images and music as supplemental story elements.  The reader of 
the visual novel typically has opportunities to make choices that affect the 
story outcome.

You may develop your visual novel on your own, or you are welcome to work as 
part of a team of up to three people producing a single visual novel.

The content of the visual novel should be "family-friendly".

## Design Document

Before you begin programming, write a design document consisting of the 
following:
* A one-paragraph overview of the novel, describing the protagonist, the 
  protagonist's goals, and the general themes of the novel.
* A description of every possible ending of the novel. There should be at 
  least one ending where the protagonist succeeds and a different ending 
  where the protagonist fails.
* A description of a challenge the protagonist must overcome.
* A listing and brief description of each character in the novel. There 
  should be at least two distinct characters in addition to the protagonist.
* A description of each anticipated decision point in the novel. It should 
  have at least four distinct decision points, and there should be at least 
  one ending which is reached by making at least two distinct decisions.
  
## The Visual Novel

Create your visual novel using [Ren'Py](https://www.renpy.org/). It should
match the story requirements given in the design document above. As you work
on it, you are welcome to diverge from the original ideas expressed in the 
design document, as long as it still meets the given requirements.

To get familiar with how Ren'Py works, I highly recommend reading carefully 
through the included example **The Question**. There is also a lot of 
valuable material in the included **Tutorial**. 

I have also created a 
[short visual novel](https://github.com/gjf2a/help_visitor) as a 
demonstration.

## Images and Music

The story should be enhanced with images and music as follows:
* Each character should have at least one image.
  * You may have more than one image per character if you wish to reflect 
    different moods.
* The story should have at least two background images reflecting different 
  scenes.
* There should be at least two musical loops to accompany scenes from the 
  novel. Each musical loop should somehow enhance or reinforce the general 
  mood of the scenes it accompanies.
* It is perfectly fine for images and musical loops to be used in more than 
  one scene.
* Images and music must be original creations.
  * Images may be photographs, original drawings/paintings that are scanned,
    Context Free Art creations, sketches from a drawing program, or anything
    else workable.
  * Music may be composed and exported from Sonic Pi, or performed,
    recorded, and included from any other suitable source.

If you use the **Record** function in Sonic Pi, it generates a `.wav` file, 
which is a format that Ren'Py doesn't support. The following code (using
the [`pydub`](http://pydub.com/) library, preinstalled in Kaggle) will 
convert a file named `scene1.wav` file to an `.mp3` file named `scene1.mp3`:

```
from pydub import AudioSegment 
song = AudioSegment.from_wav("../input/wav-files-to-convert/scene1.wav")
song.export("scene1.mp3", format="mp3")
```

## To Submit via Teams

* By Wednesday, April 3, at 10:10 am:
  * A PDF of your design document
  * Bring a printed copy to class that day
* By Wednesday, April 10, at 10:10 am:
  * A Zip file of your completed visual novel

