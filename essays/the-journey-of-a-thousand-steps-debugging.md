---
layout: essay
type: essay
published: false
title: "The Journey of a Thousand Steps: Debugging"
date: 2025-09-10
labels:
  - Problem Solving
  - Debugging
  - Questions
  
---

<h1> Debugging in the Ideal Case </h1>
Through around 80% of the code I'm flying through any issues I run into, which takes up about 20% of my total time programming. 
I go through three main steps in solving a problem:

<ol>
      <li>Defining the End Goal</li>
      <li>Identifying the Problem</li>
      <li>Figuring Out a Solution</li>
</ol>

<h2> So, where are we trying to go from here? </h2>

The first step in the journey of solving a problem starts at the end; what is the goal?
Not just looking at the path planned to get there, but the destination. 
There are many different ways to achieve the same goal, so the main focus should be kept on trying to find a path that leads there. 

<h2> What is happening? </h2>

Keeping in mind the end goal, the next part is figuring out why the current path isn't working.
It could be as clear cut as:
<ul>
      <li>A missing semi-colon</li>
      <li>An extra curly brace</li>
      <li>An undeclared variable</li>
</ul>

or as complicated as a functional but unexpected return.

<h2> What do we do? </h2>

Once the problem has been clarified, the next step is to start solving the problem. 
Which is generally easier said than done. 
But assuming it gets done, 
that's all there is to it, <em>simple</em> and <strong>easy</strong>.

<h1> Debugging in Reality </h1>
In the other 20% of the code I slam face first into a brick wall spending 80% of the time debugging. 
Sometimes, the answer just won't magically appear no matter how much I rattle my brain. 
So instead of asking questions just to myself, I ask questions to others. 

<h2> The Art of Asking a Question </h2>

The ideal process still applies, 
but instead of me being able to run through to the end 
I'll need to give the context to someone else so they can. 

<h2> Context Situated Question </h2>
A great example of asking a question with context from stack overflow is

<a href="https://stackoverflow.com/questions/596351/how-can-i-know-which-radio-button-is-selected-via-jquery">
"How can I know which radio button is selected via jQuery?"
</a>
They started by asking
```
I have two radio buttons and want to post the value of the selected one. How can I get the value with jQuery?
```
Then showed their current code of 

```
I can get all of them like this:

$("form :radio")
```

After which they followed up with

```
How do I know which one is selected?
```

Where they layout what they are trying to do, (know which radio button is selected), how they are trying to, (via jQuery), and solutions they have tried ($("form :radio"))

<h2> Unclear Goal Question </h2>
In contrast this other question from stack overflow doesn't explain what they want to do

<a href="https://stackoverflow.com/questions/43966386/what-does-this-array-mean">
"What does this array mean?"
</a>

```
unsigned int PointSet[] = { (10<<16) | 3, (4<<16) | 2, 0xFFFF0002 };
```
After which they proceeded to ask
```
What does this mean ?

| 3 what operation is it?
```

There isn't any understanding shown of the code they've shown, 
which is concerning since going down this pathway may not even lead towards their goal in the first place.





