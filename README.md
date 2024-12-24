# rock-paper-scissors

<p>Rules of Rock Paper Scissors

✊ beats ✌️

🖐 beats ✊

✌️ beats 🖐

or

Rock beats Scissors

Paper beats Rock

Scissors beats Paper<p>

<p><ins>Strategy for JavaScript</ins>

1. Think about what steps we need

2. Convert those steps into code</p>

<p><ins>Steps or Algorithm</ins>

When we click a button:

1. Computer randomly selects a move

2. Compare the moves to get the result

3. Display the result in a popup</p>

<p>To randomly select a move for the computer we need to use a new piece of JavaScript code. So, here we're gonna use <code>Math.random()</code>
  
<code>Math.random()</code> generates a random number between 0 and 1

To be more precise it actually generates a number greater than equal to 0 and less than 1 or 0 <= number < 1

We need a way to convert this random number into a move like rock, paper or scissors. To do this let's imagine this space between 0 and 1. And then divide this space into 3 equal parts. Each part represents a move.

![move](https://github.com/user-attachments/assets/ac1acbba-36ce-4f69-b49e-d9476833e245)

If we generate a random number:

If between 0 and 1/3 => rock

If between 1/3 and 2/3 => paper

If between 2/3 and 1 => scissors

This is how we can convert the random number into a move and this will give the computer an equal chance of picking rock, paper or scissors.</p>

<code>website</code>: https://golla-udaykiran.github.io/rock-paper-scissors