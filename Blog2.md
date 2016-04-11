<h1>My Failed Attempt at Contributing</h1>

As per my last blog post, I had decided to work on the issue with min/max (see Blog1.md if you haven't already).
The communitiy gave me a quick fix way to get it working for now till it could be dealt with at a later date. Initially, I decided to
play around with the command line interface a bit to duplicate the errors. I was never able to. 

The command line interface is not multi line compatable so I was not able to type things like.. <br>
<code>p = {'p': [4,5]}</code> <br>
<code>math.min(1,2], p['p'])</code>

![CommandLine](http://i.imgur.com/Pj7zydD.png)

I also attempted to play around with it in jfiddle, also unsuccessfully. 

I decided to look into the code (https://github.com/MeganBaluch/mathjs/blob/master/lib/function/statistics/min.js) and it was a quick realization
that I had <b>no idea what I was doing</b>. My biggest issue was the fact that I didn't understand the math functions, the javascript
I could figure out but I didn't understand what the correct output of the above code was even supposed to be?

I started reading through the documents trying to understand the math.min function and how it was SUPPOSED to behave but I still
didn't understand it. I also had a classmate look at it with me (the one who showed me this issue) and upon looking deeper into
the code, he also agreed that he had no idea what was going on. 

I decided to attempt some code, just to check if it was a scalar or not, and if it was not a scalar, throw an exception.
By the time I went to implement this, I had seen the owner had already done so. He tested that if the arguments returned True from a method 
called containsColection(), to throw a type error indicating that 'Scalar values expected in function min.'

It was unfortunately easier than I thought it was going to be and I wish I would have had more of a chance to play around with it before the 
owner just fixed it himself. Next time I guess!!


