Manual
================
Jonas Course Assignment Package 3.2.2
1/28/2022

## Purpose

This package creates random art, using ggplot2 and the
ggforce::geom_circle functions. A specified amount of randomly sized,
positioned and colored circles is created. Then, a specified amount of
randomly selected, sized and positioned words is added to the canvas.

## Functions

### make_art()

#### Description

The main art generating function.

#### Usage

make_art()

#### Arguments

seedset     the seed to recreate artworks later on.

circles     specificy the number of circles.

words     specify the number of words.

#### Examples

make_art(seed = 1234, circles = 50, words = 10)
