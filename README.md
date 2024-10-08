# lab02-debugging

# Solution(s)

[Link to Shadertoy](https://www.shadertoy.com/view/flGfRc)

Bugs:
- uv2 compilation error; just read the compiler error and fixed
- uv2 not used instead of uv; noticed that the view seemed to be limited to a quadrant of the screen
- H/V cross product bugs; noticed that the view was upside down/flipped and then noticed the cross-product equations for H and V were wrong
- ray-march distance bug; noticed that the view was cut off and just experimented with # of steps in the ray-march

# Setup 

Create a [Shadertoy account](https://www.shadertoy.com/). Either fork this shadertoy, or create a new shadertoy and copy the code from the [Debugging Puzzle](https://www.shadertoy.com/view/flGfRc).

Let's practice debugging! We have a broken shader. It should produce output that looks like this:
[Unbelievably beautiful shader](https://user-images.githubusercontent.com/1758825/200729570-8e10a37a-345d-4aff-8eff-6baf54a32a40.webm)

It don't do that. Correct THREE of the FIVE bugs that are messing up the output. You are STRONGLY ENCOURAGED to work with a partner and pair program to force you to talk about your debugging thought process out loud.

Extra credit if you can find all FIVE bugs.

# Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solution with the bugs corrected
- In the README, describe each bug you found and include a sentence about HOW you found it.
- Make sure all three of your shadertoys are set to UNLISTED or PUBLIC (so we can see them!)
