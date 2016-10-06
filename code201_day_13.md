# Learning Journal Code 201 - Day 13

### Lecture
Today in lecture we learned about Local Storage and Persistence. Local storage saves the information you tell it to save to the users browser, so that the data can live through a page reload. It stores the information when the data changes and then retrieves the data at reload.

The basic flow of persistence looks like this:<br>
1. data<br>
2. convert data into a string using JSON.strigify<br>
3. store in local storage with localStorage.<b>getItem</b>('keyname', varStringified);<br>
4. then on reload use localStorage.<b>setItem</b>('keyname'); to retrieve the data<br>
5. convert back to data structure using JSON.parse<br>
6. and there's the same ol' data from before

### Lab
During lab today, I felt like my learning was compromised a little. My pair programming parter failed to follow instructions and did all the coding I was supposed to do on his code while I was taking a short lunch. It was kind of a bummer, thankfully I paid really good attention during lecture and took really good notes. And the TA's took great care of me, Maelle sat down with me and walked me through his code and my code to make sure I was understanding all of the code that was done today. So I do feel like I have good head knowledge now of the code.
