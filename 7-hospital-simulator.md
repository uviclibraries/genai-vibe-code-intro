---
layout: default
title: 7-Hospital Capacity Simulator UNDER CONSTRUCTION
nav_order: 9
parent: Workshop Activities
customjs: http://code.jquery.com/jquery-1.4.2.min.js
---

# !!!UNDER CONSTRUCTION!!!
# Make an Hospital Capacity Simulator App! 
<img src="images/CHANGE-ME.png" style="float:right;width:320px;" alt="decorative"> 

Simulators can be a helpful way to help people spend more time on task learning about new topics or learning new skills. Here's an example of a Hospital Capacity Simulator to help users learn more about healthcare system factors and see how they affect hospital operations: [Hospital Capacity Simulator](https://richmccue.github.io/learning-games/salish-sea-guardian.html){:target="_blank"}.

You can use any Generative AI tool for this activity, but for coding I'd recommend using Anthropic's [Claude](https://claude.ai/){:target="_blank"}, as the free version creates more visually attractive web applications by default. Alternatively, you can use [Google Gemini](https://gemini.google.com/){:target="_blank"} (which comes free with Gmail), [ChatGPT](https://chatgpt.com/){:target="_blank"}, [Microsoft Copilot](https://copilot.microsoft.com/){:target="_blank"}, or any other GenAI tool that you are familiar with.

If you get stuck, please ask your instructor for assistance, and don't forget to have fun!

## Planning with some GenAI assistance

Step 1
{: .label .label-step}
- Copy and paste the following prompt into your GenAI tool (feel free to change the language of course) and then press **Enter** on your keyboard: <br>

```
Create an HTML file for a hospital capacity simulator.

The simulator should allow users to explore how healthcare resources affect a hospital by adjusting different factors and running a simulation. The interface should be visually appealing, interactive, and easy for beginners to understand.

Include:

- A colourful hospital-themed design with a simple illustration of a hospital.
- Sliders for:
  - Number of incoming patients (this represents the expected number of patients for the day)
  - Number of available healthcare workers
  - Number of available hospital beds
  - Emergency room capacity
- A "Today's Conditions" selector with options such as:
  - Normal Day
  - Flu Season
  - Heat Wave
  - Holiday Weekend
  - Local Outbreak
- Each condition should affect the simulation differently. For example:
  - Flu Season increases patient arrivals and the number of patients needing admission.
  - Heat Wave increases emergency room visits but fewer admissions.
  - Holiday Weekend increases trauma-related emergency visits.
  - Local Outbreak creates the highest demand on the hospital.
- Each time the user clicks "Run Simulation," include a small amount of randomness (approximately ±15%) so the same settings can produce slightly different results, making the simulation feel more realistic.
- Display today's simulated patient arrivals compared with the user's forecast so the variation is easy to understand.
- Include a "Run Simulation" button.
- Show an animated visual after the simulation runs, such as patients entering the hospital, ambulances arriving, and a hospital stress meter that changes colour:
  - Green = Operating Normally
  - Yellow = Busy
  - Red = Overwhelmed
- Display:
  - Hospital status
  - Hospital efficiency score
  - Estimated patient wait time
  - Number of available beds remaining
- Include a short educational section explaining how healthcare resources, staffing, and unexpected events can affect hospital capacity and patient care.
- Include a brief explanation that this is a simplified educational simulation and not a real hospital prediction tool.

The entire application should be contained in a single HTML file that can be opened directly in a web browser.

Make the simulator interactive, visually engaging, beginner-friendly, and suitable for educational use.
```
{: .step}

Step 2
{: .label .label-step}
- Now let's evaluate the suggestions from...
{: .step}

Step 3
{: .label .label-step}
- Next we need to wait a minute or two for the AI to read the web page and create the HTML file for you. While it works, you can watch it write the code.
- If you are using Claude, it will display a preview of the webpage on the right side of the screen once it generates the file. Before downloading, you can review the preview and provide additional prompts if you would like to make any changes
- Once it’s finished, click the Download button and make note of where you saved the file on your laptop (usually your Downloads folder).
{: .step}

Step 4
{: .label .label-step}
- Download the zip file that contains all the MP3 audio files for each Portuguese letter to the same folder where you downloaded the HTML file Claude created for you:
  - Download the Portuguese audio for each letter in the zip file called: [assets.zip](assets/assets.zip)
  - Find the assets.zip file on your laptop and unzip it. On a Mac you simply **double-click** on the file and it will unzip. On Windows you **right mouse click** on the file and select **Extract All…** 
{: .step}

Step 5
{: .label .label-step}
- Now that you have the audio files folder in the same place as the HTML file you downloaded, you can open the mp3 audio files in your file manager by **double clicking** on the sound files, and the sounds for each of the letters should play back to you.
{: .step}

Step 6
{: .label .label-step}
- If you created your Soundboard in Claude, [it should look something like this](https://richmccue.github.io/brasil-letters/portuguese.html){:target="_blank"}.
- Your soundboard should be playing the sounds for letters in the Portugues alphabet now. If you are having any problems, please let your instructor know and they help you get your soundboard up and running!
{: .step}

Step 7
{: .label .label-step}
- If you are creating a soundboard for a language like Hul'q'umi'num, that has letters in it's alphabet with non-English accents like glottal stops, you should follow up with a prompt like this (depending on the types of accents used in the language):
{: .step}
```text
Change the letter mapping to the letter files with the letters that have a glottal stop so
that for example the c' file name is: c_glottal.mp3
```

Congratulations on completing this Alphabet Soundboard vibe code project! Here's an example of a soundboard app crated for Language Revitalization purposes: [LiK'wala Soundboard for language learners](https://richmccue.github.io/likwala/likwala-soundboard.html){:target="_blank"}.

[NEXT STEP: ??????](3-????.html){: .btn .btn-blue }
