### Learning Journal Code 201 - Day 8

Today we learned about forms which ended up being easier than I anticipated. I had a few hiccups with a few small bugs, but other than that, most of it was a breeze.

My totals were not refreshing when I made a new store. The solution was to add the following code right below my cookieTable.innerHTML = '';

for (var i = 0; i < allStores.length; i++) {<br>
  allStores[i].totalPerDay = 0;<br>
}<br>

and the problem was solved.<br>
I actually ended up learning the most from my mistakes today. As per usual.

### Conclusion 
I am so exited to be be skimming the surface of forms and events. There is so much power behind them and I'm also ecstatic to be past week 2 days 2-3 of code 201. So ready to move on and take my new skills with me.
