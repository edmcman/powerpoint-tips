The purpose of this repository is to document powerpoint tips for researchers like myself (but hopefully useful to others too!).

An important part of being a researcher is communicating your work to others.  As a result, a necessary evil is spending a lot of time making powerpoint presentations.  My motivation for creating this repository is to encourage myself to spend time to find the right way to accomplish many of the tasks that I perform.  I expect that, eventually, this repository will include Macros and scripts.  I'm a bit embarassed to say that while I spend a lot of time programming *and* creating powerpoint presentations, I almost never combine the two, which feels like a missed opportunity.

# How to contribute?

Open a pull request.  Give preference to scripts or videos using [gifcap](https://gifcap.dev/) where possible over text instructions.

# Tips

## How to emphasize part of an image?

The traditional solution is to draw a box around the emphasized portion of the image, but it's possible to do better.

The general idea is to use the "Fragment" merge shapes options in order to split the image into emphasized and non-emphasized pieces.  **You must select the picture before the emphasis shapes.** The non-emphasized pieces can be desatured in color, blurred, or something else.

### Desaturation example
<details>

![Fragment example](videos/image-emphasis/emph1.gif)

</details>

### Blur example
This builds on the previous example.
<details>

![Blur example](videos/image-emphasis/emph2.gif)

</details>

## How to zoom in on part of an image?

The morph transition allows you to make some really great zoom effects.  Enable the morph transition, duplicate the slide, and crop and expand the element you want to zoom in on.

### Example
<details>

![How to create zoom effect](videos/zoom/zoom1.gif)

![Preview of advancing and backing slide](videos/zoom/zoom2.gif)

</details>

## How to draw a squiggly arrow/line connector?

Powerpoint doesn't allow the sketched style options for straight connectors, but if you use the curve connector and draw a straight line by double clicking on the terminal point, you can set the sketched options, including squiggly lines.  [See also the reply by Bob Jones.](https://answers.microsoft.com/en-us/msoffice/forum/all/why-is-sketched-line-grayed-out-in-word-and/a4e56375-d78c-46c1-905c-96e590e07929#:~:text=Sorry%20if%20this,Regards%2C%0ABob%20J.)

### Example
<details>

![How to create squiggly line arrow](videos/squiggly-line/squiggle.gif)

</details>

# Wanted

## How can you use "quick styles" for non-theme colors?

For example, how can you use these effects with a different color?  The gradients are complicated, so manually replicating it is not easy.

![image](https://github.com/edmcman/powerpoint-tips/assets/1017189/2fbd1fb3-8096-45c8-be33-85dd69a21ada)

# Other resources

* [Mac keyboard shortcuts](https://support.microsoft.com/en-us/office/use-keyboard-shortcuts-to-create-powerpoint-presentations-ebb3d20e-dcd4-444f-a38e-bb5c5ed180f4#PickTab=macOS)
* [Windows keyboard shortcuts](https://support.microsoft.com/en-us/office/use-keyboard-shortcuts-to-create-powerpoint-presentations-ebb3d20e-dcd4-444f-a38e-bb5c5ed180f4#PickTab=Windows)
* [PowerPoint hacks you've never heard of](https://www.mauriziolacava.com/en/10-powerpoint-hacks-you-never-heard-of/#1_make_multiple_images_the_same_size)
* [/r/powerpoint](https://www.reddit.com/r/powerpoint)
