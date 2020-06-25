---
layout: page
title: FAQ
---

## Who are you?

I'm a software engineer who enjoys puzzles of all sorts. I love speed solving
and competing in crossword tournaments and puzzle events. I've tried my hand
at constructing puzzles over the years, and while it doesn't come as naturally
for me as solving them, I hope I can make some enjoyable puzzles for others to
solve. At the very least, I hope to write useful software and improve the
software that's out there for other solvers and constructors.

## How do you construct these puzzles?

For variety crosswords, I use [Qxw](https://www.quinapalus.com/qxw.html), which
supports defining custom word paths for each variety puzzle type. It's not
perfect - it doesn't support scoring words, and it doesn't have a great way to
enter two or more words in a defined sequence (e.g. a band in a Marching Bands
puzzle), but it's still quite helpful. I also write scripts to tweak my wordlist
to make certain variety puzzles easier. For example, I have a script to generate
all valid permutations of nine-letter words for the Turns in Twists and Turns
puzzles.

My word list is built on top of
[Peter Broda's](https://peterbroda.me/crosswords/wordlist/) and
[Mark Diehl's](https://www.facebook.com/groups/1515117638602016/files) (requires
Facebook account and membership in the "Crossword Puzzle Collaboration
Directory" group). Thank you to Peter and Mark for sharing these resources and
to the administrators and moderators of the Facebook group for putting together
such a great resource for new constructors!

I'm still a far more experienced solver than constructor, but if you have any
questions about constructing, please don't hesitate to
[reach out](https://twitter.com/jpdavidson).

## How do you create JPZ files for these puzzles?

JPZ is a flexible file format that can be used to represent many different types
of variety crosswords. I've written web-based tools to generate JPZ files for
each type of puzzle posted on this site which can be accessed
[here](https://jpd236.github.io/kotwords/). The source code for these tools is
available on [GitHub](http://github.com/jpd236/kotwords).

If you have any suggestions for how to make these tools more useful or if you
run into any bugs, please report them
[here](https://github.com/jpd236/kotwords/issues)!

## What apps can you use to solve these puzzles?

I use [XWord](https://mrichards42.github.io/xword/), an open-source
cross-platform crossword app which supports JPZ files. It's very customizable,
supports all kinds of puzzles, looks sharp on high-density displays, and since
it's open-source, I've been able to contribute bug fixes and new features over
the years to (hopefully) make it even better.

You can also try the [Crossword Nexus](https://www.crosswordnexus.com/solve/)
solver if you don't want to use an app - this is what I use to embed puzzles
on this site, and the source is available
[here](https://github.com/crosswordnexus/html5-crossword-solver).

The original app for JPZ solving is
[Crossword Solver](https://www.crosswordsolver.info/), which should be mostly
functional, but is a bit antiquated and has some bugs.

## How did you create this blog?

This blog is hosted on [GitHub Pages](https://pages.github.com/) and uses the
[Lanyon](https://github.com/poole/lanyon) theme. You can view the source
repository [here](https://github.com/jpd236/puzzles) - feel free to fork it to
start your own puzzle blog!
