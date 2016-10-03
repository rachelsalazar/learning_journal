# Learning Journal Code 201 - Day 10

### Scope
Today we learned about scope. We learned that code blocks should not be 40 or 60 lines long but should be broken up into smaller sections because it makes them easier to read and manage.<br>
Where you declare your variable depicts what the scope of that variable will be. <br>
Example:<br>
var one = 1;<br>
function scope () {<br>
  var rad = rachel;<br>
  console.log(one);  <-------- OK<br>
}<br>
console.log(rad);  <-------- will throw an ERROR

When a variable is declared inside a function it can only be used within that function, it is a local variable. When it's called outside of functions, it is a global variable and can be used anywhere in the code.

### CSS Wireframing
Today we also learned about and worked on wireframing. I really enjoyed this a lot and enjoyed our lab for the day. CSS is a difficult language, but it's a language I really enjoy. We also learned about using 960px as a general layout size because it's very versatile. 960 can be divided by 1, 2, 3, 4, 5, 6, 8, and 10 which makes it desirable to use. One of the most helpful things I learned in lecture today was to build all of your HTML first before you even start the CSS styling. This helped me so much on my lab today.
