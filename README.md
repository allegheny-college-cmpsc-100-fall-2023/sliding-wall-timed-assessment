# Timed Assessment | Sliding Wall 

This is a timed assessment. It is "open book" and you may look things up online and reference course materials in completing the assessment. However, you may not copy and paste code from outside sources (it is okay to copy and paste your own code), and you should be aware that a complete answer to the prompts is not readily available online. You must use coding concepts in a unique way in order to complete the stated objectives. Given that you have limited time, be strategic about spending it looking things up when in fact you may have the answer in your memory. 

This test is due at 8PM tongiht. Late submissions might not receive credit. It is STRONGLY recommended that you begin the class during our normal lecture period, as the professor might not be available to answer questions about the test after that time frame. 

This timed assessment is regulated by the school's honor code. You can't help or receive help from other people during the exam period. Please refrain from discussing the test with other students for two weeks, in case a classmate takes the test at a later date. (You also cannot discuss the tests with students in future sections of this class who haven't taken it.)

Github will scrape your Trinket immediately after your last submission during the exam period. Changes made to your Trinket after the exam will not be graded. **There is no Gatorgrader in this repo, so don't look for checks!**

## Instructions 

1. Open links below in a separate tab so you can easily reference these instructions. 
2. Sign in to your [trinket.io](https://trinket.io/) account.
3. Find the starter code at [this link](https://trinket.io/library/trinkets/523fdaee8b). Hit the "Remix" button on the upper right ot make your own copy. You can toggle "remix" if you want to reference the original code. 
4. Remember, you will have more chances to get points for each of these categories. 
5. **For your code to receive credit, it must be documented with comments. You must also document the starter code. Complete the comments for one objective before moving on the next.**
6. When you are done, hit Save (to the left of the remix button).
7. Click the share-tree button near the top-left, then click "Link" and copy your link.
8. Paste the link from the last step into LINK.md file in this repo by clicking the filename (above), clicking the pencil to edit, and commiting your changes with the green "Commit" button on the upper right 

## Objectives

### First steps

<img width = "468" src = 
"complete.gif" />

&uarr; If you complete all four objectives, your canvas will look something like this. Each step has a screenshot of what it might look like in isolation beneath the heading (although certain properties, like speed or color, may vary). 

Start by documenting the starter code (starting on line 11) with code comments. This will help you get to know the code so you can edit it successfully. **It is also required to document all code (including the starter code) to receive credit for objectives.**

Be specific in your comments. For example, in lines 11-12, say what each variable is going to do in the code that follows. 

Each objective below will get you points for one or more coding objectives. You can get multiple points for some code categories within this one test. It is recommended that you complete step 2 before step 3. Otherwise, you can go in whatever order you like. 

### ONE: Color one brick

<img width="468" alt="image" src="color1.png">

Create a variable and store a color value (other than black or white) inside it. Use this variable AFTER the nested for-loop to color JUST ONE brick that you've selected from the list. You should choose a brick that is visible in the canvas. Save your work and document it with comments.  

If you achieve this objective, you will get a point for **variables** and **lists**. Your choice of color and brick can be different than those in the screenshot, as long as the colored brick is visible on the canvas. 

### TWO: Animate the Wall 

<img width = "468" src = 
"animate-one.gif" />

Below the nested for-loop, animate the brick wall inside of a `while True:` loop. Be sure to set the framerate with a `rate()` function.

Using a `for-loop`, iterate through each brick in the list `bricks` and apply the same change to the `x` position of each brick, so that the whole wall moves either to the left or to the right. (DO NOT use compound shapes or custom functions here, as they are beyond the scope of this test.)

If you achieve this objective, you will get points for **for-loops**, **lists**, and **while-loops**. 

Note that at some point the wall will leave the canvas entirely, and that's okay for the purposes of this test. 

Document your code with comments and save. 

### THREE: Split the wall in half

<img width = "468" src = 
"split.gif" />

**You should complete step two before completing this step.** Inside the for-loop you created in step two, add an if-else statement so that bricks on one side of the orign move to the left, and the other move to the right. In the resulting image, the wall splits in half like sliding double doors. 

If you achieve this objective, you will get points for **math-logic** and **if-else**. 

Document your code with comments and save. 

### FOUR: Fortify the wall

<img width = "468" src = "fortify.png">

Right now, the wall's dimensions are 10 X 10 X 1 bricks. Add a third nested loop to increase the wall's z-dimension, so that the dimensions become 10 X 10 X 4. 

Document your code with comments and save. 

If you achieve this objective, you will get points for **for-loops**. 

### When finished

When you have completed as many objectives as you can in the allotted time and documented all your code with comments, add your trinket link to LINK.md (steps 7-9) of instructions. Again, there is no Gatorgrader in this repo, so don't waste time looking for checks. 

MAKE SURE the lastest version of your Trinket is saved, and you link you have shared is NOT the same as the starter-code link. 
