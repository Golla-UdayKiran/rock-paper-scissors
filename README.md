<h2>Rock Paper Scissors</h2>

<p>Rules of Rock Paper Scissors

✊ beats ✌️

🖐 beats ✊

✌️ beats 🖐

or

Rock beats Scissors

Paper beats Rock

Scissors beats Paper<p>

<p><ins>Strategy for JavaScript</ins>

1. Think about what steps we need (algorithm)

2. Convert those steps into code</p>

<p><ins>Steps or Algorithm (Rock Paper Scissors)</ins>

When we click a button:

1. Computer randomly selects a move

2. Compare the moves to get the result

3. Update a score

4. Display the result and score in a popup</p>

<p>Play the game with keyboard:

type 'r' => play rock

type 'p' => play paper

type 's' => play scissors</p>

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

<h2>Resources</h2>
<p>1. <a href="https://supersimple.dev/projects/booleans">Booleans Project</a></p>
<p>2. <a href="https://supersimple.dev/projects/objects">Rock Paper Scissors</a></p>
<p>3. <a href="https://supersimple.dev/projects/dom-rock-paper-scissors">Rock Paper Scissors</a></p>
<p>4. <a href="https://supersimple.dev/projects/rock-paper-scissors">Rock Paper Scissors</a></p>
<p>5. <a href="https://supersimple.dev/projects/advanced-functions">Rock Paper Scissors</a></p>
<code>website</code>: https://golla-udaykiran.github.io/rock-paper-scissors