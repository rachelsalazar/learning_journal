# Learning Journal Code 201 - Day 3

### During Code Review

This morning during code review I realized a few things that could be fixed in my code from yesterday. I forgot about the figure tag that can be used for images as well as figure caption. I could have used that yesterday. And second, in my JavaScript code, I had, for example:
var answerOne = prompt('String');
var answerOneUpper = answerOne.toUpperCase();

But I now realized that I don't need a new variable I can use the same one and assign the new property to it. And to take it one further and make it as simple as possible, my code can be:
var answerOne = prompt('String').toUpperCase();

BOOM, Done!!

### Arrays

During lecture today, I learned about <b>.push</b>.

When adding a new value to an existing array you can use the .push method.
It looks like this.

rachelsDogs = ['Melvin', 'Wallace'];
rachelsDogs[2] = 'Scout'  |OR|  rachelsDogs.push = ('Scout')
    they both === rachelsDogs = ['Melvin', 'Wallace', 'Scout'];

### if / else / while

if statement can stand alone, they don't need an else.
I DID NOT KNOW THIS. And it's been super helpful!!

### Day 3 Lab

I really enjoyed today's lab! It made me think so hard, and I was actually able to figure everything out. I also learned a TON about while and for loops. It's crazy that when you actually use them in a real situation, they actually start to make sense. Loved today's lab.
