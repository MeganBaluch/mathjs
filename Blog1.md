<h1>My First Experience with MathJS</h1>

Upon looking through the repository a little bit, I thought mathjs seemed like a super useful library for being able to evaluate math equations in javascript code.

I first forked the repo from Josdejong and then cloned it into my local repository, I'm currently working on a branch called Blog

Following along with the install instructions was a breeze and I didn't run into any errors. 
After changing into the mathjs folder, I ran... 

<b>npm install</b>

followed by 

<b>npm run build</b>
![ScreenShot](https://raw.github.com/MeganBaluch/mathjs/master/"Run Build.png")

![Build screenshot](/mathjs/Run Build.png?raw=true)

Although it took a bit to build, but that could just have been my internet, it seemed to build correctly.

I then ran throug the test for the library, with first using the command...

<b>npm test</b> and <b>npm run coverage</b>

After running what seemed like thousands of tests, one of them actually failed, it failed since it took longer than 200ms when testing <i>pow should compute large size of square matrix</i>.

My next step was to go through using jsfiddle and play around with the commands a bit. It took a little bit to get used to the syntax, but by following along with examples on their website, https://jsfiddle.net, I picked up on it pretty quickly.

[photo]

My next step is to hopefully be able to contribute to the code! Fortunately, a fellow classmate stumbled upon an issue with mathjs and asked for suggestions from the community on how he would go about fixing it.
With his permission, I'm going to attempt to fix the bug. 

[photo]

I plan on fixing this by checking the parameters to make sure the numbers are scalars, and if they're not, throw an exception



