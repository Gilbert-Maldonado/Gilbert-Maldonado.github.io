---
layout: post
title: Week Eleven
---

**What did I do this week?**

Downing reiterated the difference between stack and the heap. He then talked about the move constructor and the move assignment. If you put something inside move() then it convinces the compiler that it's an r-value. The move assignment is nice when you want to transfer the contents over and delete the thing you're stealing from. This takes away the inefficiency of copy over the contents. If there is no move constructor or move assignment then it will just call the copy constructor or copy assignment. Then Downing talked about scope.

In C++ we have:
local
local static
global
global static
class
class static

In Java we have:
local
class (instance)
class static


The main questions he asked to figure out how C++ worked is as follows:

1. How many are there?

2. When are they allocated?

3. When are they initialized

4. What is their scope?

5. What is their lifetime?


These questions help us understand what is really going on in the background.

**What's in your way?**

I have a Number Theory test next week. So that'll be in the way a little bit.


**What will you do next week?**

The next project is coming out so I plan to start out on that early. The project is called game of life I think and I'm sure it'll be more extensive than this past project.

**Quick Tip**

From a podcast called _Coding Blocks_ three people talk about JavaScript Promises and provide insight on how Promises differ from callback functions. It's a great listen. I don't think they start talking about Promises until around the thirty minute mark.
[JavaScript Promises](https://play.google.com/music/m/Drgmmz2zonwf7akg5nlgotqxifa?t=Episode_31__Javascript_Promises_and_Beyond-Coding_Blocks__Software_and_Web_Programming__Security__Be)