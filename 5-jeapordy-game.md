---
layout: default
title: 5-Jeapordy Game
nav_order: 7
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

# Make a Classroom Jeopardy Game in 10-Minutes!
<img src="images/7-jeopardy-logo.png" style="float:right;width:350px;" alt="decorative"> 

Jeopardy-style review games are a fun and effective way to help students review course material in teams. In this activity you will use a Generative AI tool to "vibe code" a classroom Jeopardy game based on the content of a web page, complete with team scoring, Daily Doubles, and a Final Jeopardy round. Here is an example of a finished game: [Classroom Jeopardy - The Future of Education](https://richmccue.github.io/learning-games/jeopardy.html){:target="_blank"}.

For this activity we will use this blog post as the source of the questions and answers: [Is Your Smartphone Listening to You?](https://richmccue.com/2026/05/26/is-your-smartphone-listening-to-you/){:target="_blank"}. That said, **we strongly encourage you to find a web page or [Wikipedia article](https://en.wikipedia.org/wiki/Main_Page){:target="_blank"} on a topic you know well**, because Generative AI tools sometimes make mistakes when writing questions and answers, and you will be able to fact check the game content in real time as you play through it.

If you get stuck, please ask your instructor for assistance, and don't forget to have fun!

Step 1
{: .label .label-step}
- You can use any Generative AI tool for this activity, but for coding I'd recommend using Anthropic's [Claude](https://claude.ai/){:target="_blank"}, as the free version creates more visually attractive web applications by default. Alternatively, you can use [Google Gemini](https://gemini.google.com/){:target="_blank"} (which comes free with Gmail), [ChatGPT](https://chatgpt.com/){:target="_blank"}, [Microsoft Copilot](https://copilot.microsoft.com/){:target="_blank"}, or any other GenAI tool that you are familiar with.

![Screenshot of the Claude.ai home screen with the prompt box highlighted](images/7-jeopardy-1.png)

{: .step}

Step 2
{: .label .label-step}
- Copy and paste the following prompt into your GenAI tool, replacing the web page link with a page on a topic you know well if you prefer, and **if you're using Claude, select the latest model and highest level of effort available to you** (see image below). Then press **Enter** on your keyboard:

```
I'd like to create a classroom Jeopardy game as a single self-contained HTML file that I
can host on GitHub Pages. Please base all of the questions and answers on the content of
this web page: https://richmccue.com/2026/05/26/is-your-smartphone-listening-to-you/

The game should include:
- A setup screen where I can choose 2, 3, or 4 teams and enter team names
- A game board with 5 categories and 5 clues per category, with point values from 100 to 500
- Clues written as answers, with teams responding in the form of a question, just like
  real Jeopardy
- One or two hidden Daily Doubles where the team that finds it can wager points
- A button to reveal the correct response after each clue, and buttons to award points to
  the team that answered correctly (or to no team)
- A Final Jeopardy round where each team secretly wagers up to their current score before
  seeing the final clue
- A champion screen at the end showing the winning team and final scores
Here is an example of the look and feel I'm going for:
https://richmccue.github.io/learning-games/jeopardy.html
```

![Screenshot of the prompt pasted into the GenAI chat box](images/7-jeopardy-2.png)

{: .step}

Step 3
{: .label .label-step}
- Next we need to wait several minutes for the GenAI tool to create the HTML file for you. In Claude you will see the game being built in a preview window on the right-hand side of the screen as the code is written.

![Screenshot of Claude generating the Jeopardy game code with the live preview pane](images/7-jeopardy-3.png)

{: .step}

Step 4
{: .label .label-step}
- Once the game is finished, play a quick round directly in the preview window. **This is the most important step**: because you chose a web page you know well, check each question and answer against the source page as you reveal them. GenAI tools sometimes invent plausible-sounding but incorrect answers, so open the source web page in another browser tab and verify anything that looks even slightly off.

{: .step}

Step 5
{: .label .label-step}
- If you find a question or answer that is incorrect, or you'd like to adjust the game, simply tell the GenAI tool what to change in a follow-up prompt. For example:

```
The 300 point clue in the second category has an incorrect answer. According to the source
web page, the correct answer is [the correct answer]. Please fix that clue, and also
rename the third category to something shorter.
```

{: .step}

Step 6
{: .label .label-step}
- When you are happy with the game, click on the **Download** button to save the HTML file to your laptop, and make note of where you saved it.
![Screenshot of the Download button in Claude's artifact preview](images/7-jeopardy-6.png)
{: .step}

Step 7
{: .label .label-step}
- Find the HTML file you just downloaded in your file manager and **double-click** on it to open it in your web browser. Set up two teams, give them fun names, and play through a few clues, a Daily Double, and Final Jeopardy to make sure everything works, including the scoring.
- Another way to create a Jeaporday game is to ask your GenAI tool to:
  - Only generate questions and answers for the game, inlucing extra questions for each category (I ask for 10 questions for each category).
  - Review the quesitons and answers, deleting poor questions, until you have 5 questons for each category.
  - Use the updated questions and answers text with the App Generation prompt in **Step 2**.
{: .step}

Step 8 (Optional)
{: .label .label-step}
- Want to make the game your own? Try follow-up prompts like these to customize the look and feel, or to make the game reusable with other content:

```
Change the colour scheme to my school's colours: [your colours here], and add a fun sound
effect when a Daily Double is revealed.
```

```
Now create a second version of the game using the content from this web page instead:
[link to another web page you know well... Maybe: https://en.wikipedia.org/wiki/BC_Ferries]
```

![Screenshot of a customized version of the game with a different colour scheme](images/7-jeopardy-8.png)

{: .step}

Congratulations on completing this Classroom Jeopardy vibe code project! If you'd like to share your game with students or colleagues, ask your instructor about hosting it for free on [GitHub Pages](https://pages.github.com/){:target="_blank"}, just like the example game: [Classroom Jeopardy - The Future of Education](https://richmccue.github.io/learning-games/jeopardy.html){:target="_blank"}.

[NEXT STEP: Workout Tracker](6-workout-tracking.html){: .btn .btn-blue }
