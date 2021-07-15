---
title: 'What is Length?'
date: 2199-01-01
permalink: /posts/2012/08/blog-post-4/
tags:
   - length
   - GMT
   - beta numbers
---

Everyone knows how to measure the length of a straight line segment

(pic of line segment)

Put the end of your ruler at the point $x$, line it up along the segment, and read off the marking that the point y sits above. Instead of carrying ruelrs around with us, we mathematicians build rulers into our pictures in the form of coordinates

(pic of line segment on coordinate plane)

The picture itself tells us the segment is 1 unit long! (the unit can be inches, feet, micrometers, whatever you want). But how would we measure the length of curves that aren't straight?

(pic of curves with same endpoints that are bendy)

If you think of the curves as strings, one option makes sense: pull the string taut so that it's straight and use the ruler! If we restrict ourselves to thinking about strings with endpoints $x$ and $y$, then the longer the string is, the further you have to pull on $x$ and $y$ to make it straight. In some sense, the string gets further and further from being a straight segment. Length can be quantified by how bendy the curve is!

(pic of bendy curves with the bends identified)

This is a fundamental connection: Length is a measure of bendiness (and bendiness is a measure of length)! As mathematicians, we would like to quantify this; we want to find numbers which help us describe this perspective on length, and we want some kind of equation that connects these numbers to length.

(bendiness on one side of equality and length on the other)

The number we use most often to quantify bendiness is called the Jones beta number (named after Peter Jones) denoted by the greek letter $\beta$. Let $z$ be some point on our string and let $r>0$ be any number greater than zero ($r$ is for radius). The symbol $\beta(z,r)$ is a number associated to our curve that we can compute as follows:

(pic of curve with $z$, circle of radius $r$ around $z$)

We draw a circle around $z$ of radius $r$ and look at the part of the curve contained inside of this circle.

(pics of snapshots of balls?)

Next, we draw a line which is as close to the piece of the curve inside of the ball as possible, minimizing the largest distance between any point on the curve and the line.

(pics of lines and distances)

We then divide this length by the radius of the ball. 
