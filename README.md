# ruby-style-guide

## What a styleguide is all about

Styleguides are rulesets that developers recognize and most of the time adhere to, that aim at making their lifes easier. I have tried to come up with these categories of rules I have seen in the wild:

<dl>

<dt>Traffic lights</dt>
<dd>Rules that are completely arbitrary ("Red means stop", "indent with spaces") that make everyone's life easier
</dd>

<dt>General legibility<dt>
<dd>Rules that make human parsing of the code easier -- like special indentation rules for breaking up long lines</dd>

<dt>Yellow snow</dt>
<dd>Rules that disallow dangerous techniques (or ask the developer to highlight the use in a way it is immediately apparent)</dd>

<dt>Save time later</dt>
<dd>Rules that allow frequent types of changes to the code to happen more easily</dd>

<dt>Additional semantics</dt>
<dd>Rules that, when followed by the whole team, transport semantics that are not immediately obvious from the code itself</dd>

</dl>

A styleguide obviously targets different aims, and it is difficult to come up with one that satisfies different people even of the same language community.

## One rule to rule them all

This is the only rule in this styleguide. Stick to it slavishly, unless you are spiking code that you don't intend to share (even with your future self).

> __Write code that is as obvious as possible and easy to read as you possibly can.__

This is the prime directive. Everything else either follows or is team-specific.

Even if you are happy with the code you just banged out, consider that you did it at a time your head was right in the problem space, and a future reader's mind (this includes your future self) will not be. So to be easy to follow for that person, the code has to be _really really obvious and boring_ to you in this moment!

The quality your code needs for being easily consumable by another person is being obnoxiously lame and boring _to you_ the moment you have written it. Don't underestimate the shifting your mind needs to undergo between problems. What is apparent to you right now, as you have just solved the problem, is not obvious only two weeks from now.

## Guidelines

At some future time, I might collect interesting guidelines (I'm conciously avoiding the word rules) here to share. I will link to other guides for the obvious and undebated stuff and point out here what I think is missing.
