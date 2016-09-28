# Learning Journal Code 201 - Day 7

### Code Example from Yesterday's Lab
Going over the code from yesterday today and watching it being built again was extremely helpful. The repetition is good. I had pretty much the same code he had except for I had my document.getElementById's all at the top of my code and I used my location property to add the name to the DOM. No biggies, just extra's.

<b>Helpful tips from code review:</b>
1. always check if all files are wired to the HTML <br>
2. this. this. this. don't forget the this. <br>
3. think of when it's practical in the real world to use Math.floor or Math.ceil

### Object Constructors
One of the first goals it to find out what properties are going to be shared and which ones are not. Then you can start writing your function. The shared properties look like: this.course = '201d15'. You assign course the value that will be the same for each student. And the unshared properties look like: this.firstName = firstName; which corresponds with the firstName parameter. Once you finish your function, you add new instances by writing: var rachel = new Student('Rachel');. Object constructors allow you to write a function once and easily add new instances.

### Tables with JavaScript
This part of the lab used a lot of brain power to think if I should append things inside of outside of my constructor function. It's definitely going to be a work in progress. The steps of appending were pretty similar to when we did the lists on Monday, just two dimensional instead of one.

Today was tough, but I made it through!
