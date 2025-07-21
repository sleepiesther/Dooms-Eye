# Getting Started

## Setup
To start off, you'll need some way to record your run. 

On console you can use a capture card connected to a PC, use the console's built in recording system (unfortunately not an option on Switch, as the 30 second recording limit is too short for basically any run), or record your monitor with a camera or a phone (make sure your video is a good enough quality to be verified!). 

On PC you can use basically any recording software, the most popular being [OBS](https://obsproject.com). [Click here for a good setup guide for OBS made by Stelmo.](https://youtu.be/qQOZOx5U6Qs?t=201) It's made for Project 06 but the steps for Shadow Generations are basically the same.

If you're running a [category](#categories) timed using IGT or RTA, you're all set! If you're running a category timed using LRT, you'll need to setup [LiveSplit](https://livesplit.org) and include the loadless timer in your recording. You can learn how to set up the loadless timer [here](https://www.speedrun.com/Shadow_Generations/guides/btoqj).

### Settings and binds
There aren't too many important settings in this game. The only setting that affects control is deceleration. Deceleration controls how quickly Shadow stops moving when you stop inputting a movement. At 100 (default), Shadow will stop instantly. The lower your deceleration value, the longer it'll take for Shadow to stop. This isn't too impactful, I'd recommend keeping it at 100 for tighter controls but its up to preference.

The other important setting is FPS. FPS is only really impactful when you try and break the game, and the possible options depend on platform:

- Switch, PS4, Xbox One: Locked at 30 FPS
- PS5, Xbox Series X/S: Toggle between 30 FPS at higher resolution (Image Quality Priority), or 60 FPS at lower resolution (Performance Priority) 
- PC: Toggle between 30 FPS, 60 FPS and 120 FPS. Can be set to non-default values using either Vsync or graphics card settings, but will never exceed 120.

There are some glitches that rely on FPS, but it doesn't affect normal gameplay. You should set your FPS to the highest possible option.

Binds are mostly preference, but it is highly recommended that you move Chaos Spear to a bumper. How you arrange the rest of the buttons is up to you.

### FPS optimisation
The next two sections only apply to PC runners. If you're on console, skip to [categories](#categories).

You may have noticed that this game struggles way more at maintaining 120 FPS than it realistically should. This is because Shadow Generations has Denuvo anti-piracy. I'll spare you the technical explanation, but in short this means that all that really matters for performance is your CPU's clock speed. Number of cores is generally irrelevant and the performance of other parts is generally irrelevant.

To remedy this, you have three main options:
- Raise Shadow Generations' priority in task manager
- Overclock your CPU
- Upgrade your CPU

If you want a good goal value for your clock speed, a speed of 4.3 - 4.5 GHz seems to be enough to run at 1080p 120 FPS.

### Downpatching
There are a couple of glitches in this game that only work on a pre-Tokyo DLC patch. The main practice tool [Chaos Spear](https://github.com/sleepiesther/Chaos-Spear) also doesn't work on the most recent patch for annoying memory address reasons, though it is compatible with the Tokyo launch patch.

Because of this, most PC runners run on the version just before Tokyo was released. To learn how to obtain this version, follow [this guide](https://www.speedrun.com/Shadow_Generations/guides/scmlk). 

If you plan on speedrunning Tokyo, then it is recommended to use the Tokyo launch patch instead of the most recent patch. The manifest ID of the Tokyo launch patch is 8323993515852168922.

Unfortunately, downpatching isn't very viable on console, so the vast majority of console runners run on the most recent patch.

## Categories
Shadow Generations speedruns are separated into multiple different categories, each with a different ruleset. 
There are three different timing methods used for Shadow Generations:
- In Game Time (IGT). IGT is the time you see when you complete a level. This timer is paused by Chaos Control.
  
- Real Time Attack (RTA). RTA is very simple, you start a timer at the start of the run, and end it when you finish the run.
  
- Load Removed Time (LRT). LRT is a PC exclusive timing method. It is a modified RTA that pauses during load screens, so that differing specs does not affect runs.

### Category Extensions (Catex)
Catex is a seperate leaderboard consisting of more niche or stupid categories, alongside categories that can't go on the main leaderboard for logistical reasons. You can find the Category Extensions leaderboard [here](https://www.speedrun.com/shadow_generations_catex)

### Limited Tech Selection (LTS)
LTS is a type of category that appends a ban list onto the rules of an existing category. For example, Any% LTS has the same rules as Any% alongside the bans that LTS brings. For more elaboration on the exact bans of LTS, read it's full page [here](https://github.com/sleepiesther/Dooms-Eye/blob/main/LTS.md)

### Individual Level (IL)
IL runs are speedruns of a single level in the game, such as a main stage, boss, or challenge. ILs are timed using IGT, so using Chaos Control to pause the timer is integral to getting a good time, which leads to unique routing compared to other categories.
This category has an [LTS](https://github.com/sleepiesther/Dooms-Eye/blob/main/LTS.md) variant on catex.

### [Any%](https://www.speedrun.com/Shadow_Generations?h=any-pc&x=xk973ovd-789v4x0n.1w4dk9oq)
Any% runs start from a new game and aim to reach the credits as quickly as possible. Time starts when you select the save file for your new game, and ends when you finish the button mash at the end of Neo Devil Doom. PC runs are timed using LRT, and console runs are timed using RTA.
This category has an [LTS](https://github.com/sleepiesther/Dooms-Eye/blob/main/LTS.md) variant.

### [All Stages](https://www.speedrun.com/Shadow_Generations?h=all-stages-pc-no-wings&x=5dwwyy5d-wl3jw968.le24w55l-wlegp9xn.lx58j921)
All Stages runs complete every main stage and boss in the game. There are two All Stages categories: one that allows the use of Doom Wings and one that doesn't. You can complete the stages in any order, but Devil Doom must be last. Time starts when you press the input to enter the first stage, and ends when you finish the button mash at the end of Neo Devil Doom. PC runs are timed using LRT, and console runs are timed using RTA.
This category has an [LTS](https://github.com/sleepiesther/Dooms-Eye/blob/main/LTS.md) variant.

### [All Challenges](https://www.speedrun.com/Shadow_Generations?h=all-challenges-pc&x=wk6l11ok-2lge95o8.139mypd1)
All Challenges runs complete every challenge in the game. The use of Wings is allowed, but they're rarely actually used. You can complete the challenges in any order. Time starts when you input to enter the first challenge, and ends when you press continue after completing the final challenge. PC runs are timed using LRT, and console runs are timed using RTA.

### [100%](https://www.speedrun.com/Shadow_Generations?h=100-pc&x=q25v3wvd-68k1654l.1929wk0q)
100% runs aim to get both percentages in the Records tab of the menu to 100% from a new file. Timing is the same as Any%.
