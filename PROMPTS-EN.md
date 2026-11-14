# One More Show - prompt archive (English)

## Full prompt list

[Full prompt list — original production chat (Polish), including Codex replies](https://maciejmatyka.github.io/one-more-show-jam/booklet-v3/FULL-CHAT-PL.html)

[Full prompt list — English translation, including Codex replies](https://maciejmatyka.github.io/one-more-show-jam/booklet-v3/FULL-CHAT-EN.html)

These separate complete records contain 87 user messages and 606 Codex replies/updates, through the original-sketch request of 14 November 2026. The English transcript is machine-assisted, with all user prompts and selected replies editorially revised by Codex; the Polish record is authoritative. The 45 translations below are the preserved historical RC1 selection.

---

These are English translations of all 45 available project user messages, in their recorded order. They retain the instructions and decisions; spelling and punctuation are normalized in translation. Question/reply envelopes are rendered as readable exchanges; internal tool-call identifiers are omitted. This is not a verbatim English transcript. Original Polish files, visible assistant responses, code, variants and tool evidence remain in the private development archive.

**\* Translated from the original Polish prompt.**

## P0001 *

We are starting work on https://itch.io/jam/2026-epic-ai-megajam. Keep a complete record of conversations, inputs and outputs in your directory so that we can later prepare GlassBox for the documentation contest, starting from the first prompt. First, let's brainstorm: give me 10 varied game ideas for the jam theme, Director's Cut. I will choose which ideas to develop.

<small>* Translated from the original Polish prompt.</small>

## P0002 *

Give me another 10.

<small>* Translated from the original Polish prompt.</small>

## P0003 *

Make playable JS/HTML game prototypes, one file per game. I want a simple but playable and interesting level to evaluate the mechanic, so use simple graphics but make the prototype playable. I choose projects 1, 3, 9, 10, 12, 15 and 19. Create seven prototypes.

<small>* Translated from the original Polish prompt.</small>

## P0004 *

Develop two prototypes. For prototype 3, make a second, less trivial level. For 12, add a timeline (soundtrack) where sounds can be placed as in film editing. Sounds should cause different behaviours in the scene, as originally proposed.

<small>* Translated from the original Polish prompt.</small>

## P0005 *

Prototype 3 is interesting. Assess whether the idea is original and whether something similar is already on the market. Do thorough research. Then develop 10 options for representing the game scene: two 2D, two top-down, two full 3D, different concepts and viewpoints. Describe pros and cons and make maximum use of Unreal, which matters for the contest; it must suit the technology. These are concepts, so do not create the game, only example engine renders showing the character, view and style. I want something spectacular for an eventual 30-60 second GameJam trailer, so it must not look like a prototype. One version should suit the NVIDIA award: go all out there. I'm leaving, so don't ask for approval; work, I'll be away for half an hour.

<small>* Translated from the original Polish prompt.</small>

## P0006 *

I have another idea. This time I want you to make a prototype directly in Unreal with the highest possible level of physics. Imagine a ragdoll hanging from strings attached to its hands and feet, like a puppet. It is also attached by the head. Everything uses full physics. A 2.5D view: the object is three-dimensional with full physics, but we see it as if in 2D. The player can play a scene showing the object's shadow. The shadow falls to the ground in a particular way, moves a hand or performs an action such as picking up an object. The entire shadow action is produced by cutting these strings. The player's task is to cut the strings at the right moments to match the object's movement to what they see as closely as possible. Score this as a percentage, for example 70% similarity. We aim for 100%, which should be very difficult. Scene after scene. A little like Cut the Rope, but different and fitting Director's Cut. Make the prototype. Focus on this. Make it genuinely high quality because I want to play it: use Unreal's physics engine and attractive visuals. Let's go.

<small>* Translated from the original Polish prompt.</small>

## P0007 *

Let's work on it. "Teatr Cieni" will be the working title, "Shadow Theatre" in English. Create a private repository on my GitHub and keep subsequent versions there so that nothing gets lost. Remember GlassBox: everything should be there, from the initial exploration of ideas and concepts, with drawings, through my idea and the choice of Shadow Theatre.

<small>* Translated from the original Polish prompt.</small>

## P0008 *

Let's work in turns with revisions. Make the next version and keep it so I can return to earlier versions by specifying them; clearly number the names so I know which one we are working on and can roll back.

1. Allow cutting a rope anywhere along its length.
2. Cut with the mouse or a finger on mobile. For now retain the possibility of a mobile game; tell me whether that makes sense for the contest.
3. After showing the shadow, immediately switch to "now you cut" so the player can start at once. Polish the UI: fewer labels at the top; a simple HUD with attempts, scene number, time, best score and similarity. At the bottom, I prefer Restart, exit to menu and replay shadow.
4. Does the game use NVIDIA technology for the special award? Do not implement anything for this, but consider and summarize the options.

<small>* Translated from the original Polish prompt.</small>

## P0009 *

Is it worth moving to mobile now, or should we develop the mechanic further on Windows and then migrate and make a mobile version?

<small>* Translated from the original Polish prompt.</small>

## P0010 *

What next steps do you suggest?

<small>* Translated from the original Polish prompt.</small>

## P0011 *

I like this plan. Go ahead with point 1.

<small>* Translated from the original Polish prompt.</small>

## P0012 *

Reply to the request to close the Windows firewall dialog using Cancel so interface testing could continue: "I closed the message."

<small>* Translated from the original Polish prompt.</small>

## P0013 *

There is a problem: I get stuck trying to catch the first-cut moment. It is difficult because the scene has no clear starting moment. I propose that my first cut in every scene should automatically synchronize with the original first cut. When I cut, start the reference scene's first cut at that same moment, then measure differences arising from the physics. Ask if this is unclear; if it is clear, apply it in a new version.

<small>* Translated from the original Polish prompt.</small>

## P0014 *

I think it is playable now, but the first level should have two cuts, the right and left hands, because it is not a challenge now. If possible, deliver faster: these changes take too long, especially since I am not asking for much at this stage. Perhaps reduce the model's depth of analysis for small changes?

<small>* Translated from the original Polish prompt.</small>

## P0015 *

How do I configure Windows Firewall so I do not have to click permission prompts during your next tests?

<small>* Translated from the original Polish prompt.</small>

## P0016 *

I cannot find that option.

<small>* Translated from the original Polish prompt.</small>

## P0017 *

OK, I found it.

<small>* Translated from the original Polish prompt.</small>

## P0018 *

Let's work on the game. Improve the flow: the player should be able to start cutting whenever they want. Do not wait until the actual starting point and pause at the first cut; wait with physics running, and start the background shadow animation when the cut happens. The player will see the initial shadow and that their cut starts it. Also write a scenario for your next steps.

<small>* Translated from the original Polish prompt.</small>

## P0019 *

Work on point 1: tune scoring so that waiting before the first cut does not reduce the score, while physics keeps running and there is no jump at the cut. Make another version. Percentage scoring is fine, but treat a score above 90% as success, with all consequences.

<small>* Translated from the original Polish prompt.</small>

## P0020 *

I preferred the previous version, where you could see discrepancies with the shadow caused by a different physical arrangement. A little randomness is welcome: we are not aiming for 100%, but roughly the planned fall of the puppet. Return to the previous version and change only the treatment of scores above 90% as success, with all consequences.

<small>* Translated from the original Polish prompt.</small>

## P0021 *

Before the player's round, play the shadow's movement once; that is missing now. Also do point 2 from your list immediately.

<small>* Translated from the original Polish prompt.</small>

## P0022 *

While the shadow is playing, allow skipping by pressing a mouse button. Indicate this with small central text that does not obscure the view. Do points 3, 4 and 5 together; don't ask, because I'm going out. I imagine a theatre with red cloth curtains, an attractive setting, theatrical props and so on.

<small>* Translated from the original Polish prompt.</small>

## P0023 *

The sounds are weak. I suggest using free assets from WeLoveIndies.com, which the contest rules mention. Download everything needed from https://www.weloveindies.com/en/epicmegajam. Give the levels theatrical names to preserve the atmosphere: I suggest Act 1: Prologue, Act 2, then Act 3: Epilogue. Polish the HUD and buttons and use fonts that suit the theatre. Do not change the film yet; we will work on it later.

<small>* Translated from the original Polish prompt.</small>

## P0024 *

Reply to the license question: "Yes, accept and download."

Question context: five sound effects and "The Puppet Master" for Shadow Theatre, total EUR 0. The question asked permission to accept the FREE & DEMO project license for demos and non-commercial use, with another license required for a commercial release.

<small>* Translated from the original Polish prompt.</small>

## P0025 *

Change all application text to English and let's work in English from now on. For the UI, read some guides about how this HUD should look and follow the guidelines and good design practice; it looks very amateurish now.

<small>* Translated from the original Polish prompt.</small>

## P0026 *

Write to me in Polish here in Codex, but use English in the application. Keep GlassBox in Polish as before; we will translate it at the end.

<small>* Translated from the original Polish prompt.</small>

## P0027 *

Gameplay is OK. A tester noticed that an additional mechanic, variety or a storyline is missing. Perhaps something at the scene-selection level, so the menu tells the player what these levels are for? A theme of performing scenes for an audience and earning satisfaction percentages? Or earning money from tickets? Let's discuss and brainstorm.

<small>* Translated from the original Polish prompt.</small>

## P0028 *

Good. The tester accepted 1 and 6 with "Grand Finale". At the end, meet a fat director who summarizes whether we succeeded. Adapt the level-selection menu accordingly, as you described. Make the first story prototype following this recipe, with suitable graphics. In Grand Finale there must no longer be a shadow: the player has to manage using their training.

<small>* Translated from the original Polish prompt.</small>

## P0029 *

Add a visible audience to Grand Finale that reacts to the performance: applause for a good score, displeasure for a weak one. I want a clear difference between practice and performing for an audience. Show all percentages as progress bars too. The director should be fat, with a cigar, behind a desk. At the beginning, include an introductory letter explaining what is happening. Make the next version.

<small>* Translated from the original Polish prompt.</small>

## P0030 *

What should I send a friend if I want to share it for testing?

<small>* Translated from the original Polish prompt.</small>

## P0031 *

At the very beginning, add language selection with US, Polish and French flags. Show messages in the chosen language; translate all text and maintain three language versions. Select the default from the system settings; if that is unavailable, default to USA (English).

<small>* Translated from the original Polish prompt.</small>

## P0032 *

Put language selection only in the menu, as three flags, and keep the system language as the default. Add applause for successful attempts above 90%. Do not applaud in the final scene if the score was not above 90%. At the end, start percentages at 0 and animate the progress bar for about one second, always with particles showing the progress. Play applause on crossing 90%, or booing if it fails; in that case, also fade the colour towards red. At the director ending, have him shake his head left and right if there is no success.

<small>* Translated from the original Polish prompt.</small>

## P0033 *

Continue.

<small>* Translated from the original Polish prompt.</small>

## P0034 *

How can I run this fullscreen?

<small>* Translated from the original Polish prompt.</small>

## P0035 *

I have tester feedback. Fix these:
1. The replay-shadow button does not work.
2. The right-hand menu panel should appear only after all the left-hand rehearsals are complete. Until then, show an elegant message that the dress rehearsal is tomorrow and these three must be finished first.
3. Remove time information from the gameplay HUD.
4. Rename "Programme" to "Menu".
5. Change the blue progress bar to green; as percentages increase, smoothly change from burgundy to green.
6. Personalize the director's final summaries precisely according to results. For 2/3, say roughly: "You did well here and here, but you still need to polish the third cut there." If the third act succeeds, something like: "You managed the hardest one, but still need work on the basics." Write it nicely.

After a successful game, add "Grand BONUS Finale" with the director suspended by his hands and feet, so we can cut his strings: a funny ending. When a performance starts for the audience, first animate them entering their seats, then open the curtain to reveal the puppet. Show a large, attractive "Act 1: [name]" and a small instruction to repeat what was learned in that act without the shadow. Go ahead.

<small>* Translated from the original Polish prompt.</small>

## P0036 *

Make failure audio more subtle: no applause and some murmuring, not booing. Replay shadow is unreliable: I press it and see flickering. Fix this completely because it matters. It seems holding the button quickly turns the shadow off; it should not treat that as an intentional action. I also do not know how to reset game progress; there should be an option. Animate the audience entering only in Act 1, because the same audience watches the following scenes continuously. Between acts, briefly close the curtain, change the prop, then reopen it. Put a prop on the right pedestal in each scene that clearly identifies the act: the heads in the first, a small balance beam in the second, and keep the bell in the third. Make the director's left-right "no" headshake twice as slow. In the upper-right of the letter, show an animated sketch of the shadow and cutting strings, a proxy drawing that explains the mechanic as the player reads.

<small>* Translated from the original Polish prompt.</small>

## P0037 *

One additional note: that little animation is very weak. Make it by recording the screen of the game while someone cuts one of the strings, then transform it into lines like a pencil sketch. Right now it looks like childish stick figures; I want it done professionally.

<small>* Translated from the original Polish prompt.</small>

## P0038 *

After completing a rehearsal in one of the three acts, replace "Another attempt" with progression to the next act: from Act 1, show "Next: Act 2", and so on. During show preparation, make the progress bar green with particles like the percentage count-up; the progress is hard to see. At the end of the final performance, the audience starts visibly clapping too soon and there is no sound. Only the second clapping phase is right, with sound after percentages are calculated. Keep that phase.

<small>* Translated from the original Polish prompt.</small>

## P0039 *

After unlocking it, make the Grand Finale button green. All percentages should use a palette that transitions smoothly from burgundy at 0% to green at 100%.

<small>* Translated from the original Polish prompt.</small>

## P0040 *

On later Grand Finale attempts, put the attempt number on the button and make the director increasingly angry. Each time he says which attempt it is. At the eighth, his eye should fall out. At the twelfth, he should stand up and overturn the desk. Tension should build until attempt 25, when his assistant replaces him; she also discusses results and gets increasingly angry. At attempt 100, she takes a pistol, shoots at the screen, and the game ends with a large "Your theater got closed. Game Over" in the centre, with no playing or reset: a real game over.

<small>* Translated from the original Polish prompt.</small>

## P0041 *

Suggest a title. For now we have Shadow Theatre, but perhaps something like "Theatre" or "The Last Show"?

<small>* Translated from the original Polish prompt.</small>

## P0042 *

I like "One More Show". Change the game title to that and add the menu tagline "Cut the strings. Win the crowd. Save the theatre." Make another version.

Then prepare the final video and GlassBox as a file on GitHub, with a link suitable for the jam according to its rules. Prepare the final product and close the first "release candidate". Afterwards, summarize today's work and say what else you would improve to win the contest.

<small>* Translated from the original Polish prompt.</small>

## P0043 *

For the film and GlassBox, remember that everything must be in English. Where necessary, for prompts, add an asterisk and a small note that the original was in Polish. Prepare the material for an English-speaking jury.

<small>* Translated from the original Polish prompt.</small>

## P0044 *

Reply to the author/team-name question: "I don't know - what do the contest rules say?"

Question context: what team/author name should appear on the contest package and end credits? The proposed name was Maciej Matyka, matching the GitHub account.

<small>* Translated from the original Polish prompt.</small>

## P0045 *

Then do that: Maciej Matyka.

<small>* Translated from the original Polish prompt.</small>

