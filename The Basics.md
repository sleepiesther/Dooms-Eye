# The Basics

## Chaos Control

Chaos Control is charged by killing enemies, or by breaking a Chaos Control capsule. 5 normal enemies (egg pawns, GUN robots etc) or a single Black Arms enemy will fully charge your Chaos Control.

When Chaos Control is activated you gain a few benefits:

- The In Game Timer stops for 6 seconds (yes I know the counter starts at 5 but trust me it is 6)
- Most nearby objects or enemies freeze in place, and are unaffected by damage until time is restored. Capsule breaking is paused until time restores.
- You are able to stand on some otherwise damaging objects, such as missiles.
- Your boost gauge is immediately filled to 100%

[Chaos Control Showcase](https://github.com/user-attachments/assets/ccfb900f-8ba1-44cf-8e93-14c0ae0a215e)

The IGT pause is essential in [IL runs](<Getting Started.md#individual-level-il>), that are timed using IGT. IT is often worth it to take a "slower" route in ILs that gets more Chaos Controls.

### Chaos Control Duplication
For whatever reason, Chaos Control capsules actually give you 2 charges of Chaos Control. One invisible charge is given immediately, another is given through the charge orbs the capsule drops. Holding the Chaos Control button as the capsule breaks will allow you to use the first charge, without using the second one. This allows you to get two Chaos Controls from one capsule.

## Wingless Movement
This section will go over most basic movement tech that isn't level specific. It will assume you have beat the game and have a basic understanding of Shadow's base movement, and how all of the Doom Powers work.

### Speed Values

Speed values differ between 3D levels, 2D levels, and White Space. It's not too important to know these exact values, but knowing if something is faster or slower than something else can be useful.

| Action            | 3D Speed | 2D Speed | White Space Speed |
| :---------------: | :------: | :------: | :---------------: |
| Ground boosting   | 60       | 30       | 30                |
| Running           | 50       | 22       | 30                |
| Air boosting      | 50       | 25       | 25                |
| Max air speed     | 23       | 20       | 25                |
| Stomping          | 100      | 70       | 100               |
| Max falling speed | 55       | 30       | 55                |
| Surfing           | 55       | 18       | 28                |
| Surf boosting     | 100      | 30       | 40                |
| Morph swimming    | 20       | 15       | 17.5              |
| Morph boosting    | 80       | 40       | 50                |
| Wings flight      | 50       | 30       | 40                |
 

### Speargliding
When you throw a Chaos Spear in midair, two things happen:

- Whatever action you're currently doing (airboost, double jump) is interrupted
- You enter a special "Spear state" for 0.66 seconds

In the Spear state, all of your current horizontal speed is perfectly maintained. Normally, in midair, you slow down incredibly quickly. Using Chaos Spear allows you to prevent this and carry speed for way longer than intended, allowing you to fly across the level.

Speargliding is pretty simple. All you have to do is be airborne while at high speed (this can be done by boosting off of a ledge, airboosting etc), and input a Chaos Spear at least once every 0.66 seconds. This will maintain the speed you had when you started speargliding until you land on the ground.

Often, objects such as dash rings while give you more speed than you can normally obtain. Speargliding using this speed can lead to massive skips, so keep an eye out for these objects!

This does have one caveat, while in the Spear state Shadow has no terminal velocity. Normally, Shadow will accelerate while falling until he hits the max falling speed, and then stay at that speed. However, when in the Spear state, Shadow just... keeps accelerating down. This normally isn't too impactful, but it's something to keep in mind. You can reset your falling speed using an air boost or a double jump, cancelled with a Spear. When done properly this does not lose any speed, but the input is pretty tight.

When falling from massive heights it is often faster to spam Chaos Spear instead of stomping.

### Powersliding (written by Moha)
Powersliding is a technique that utilizes a held sidestep input to move forward. Usually, its best use is in parts of levels where you only move in straight lines.
In order to powerslide correctly, you need to move the left stick (movement stick) in the opposite direction of the sidestep side you choose (move the stick to the left if you do a sidestep to the right, and vice versa).

There are two ways in order to stay centered while powersliding:

- Hold an angle that holds Shadow in a preferable direction (usually up-left/up-right depending on the choice of the sidestep input) and adjust with holding forward if needed.
- Quickly alternate between holding opposite to the sidestep direction and a neutral stick position

These methods work most of the time, but in some specific places, the powerslide input behaves differently.

Notable spots where it’s different:

- You can just move normally while powersliding in Whitespace.
- The last section in Kingdom Valley Act 1 gives you big curves while sidestepping, making powersliding more difficult.
- The last section in Radical Highway Act 1 lets you hold forward normally while powersliding.

There are probably more places where powersliding behaves differently input-wise that are unnoticed so far, but generally, you're good to go with the two main methods.

Important powersliding properties:

- You move slightly faster than basic boosting.
- Shadow will stick to ledges, meaning you can't fall off.

### Neutral Sticking
For whatever reason, keeping the stick in a neutral position allows you to retain more speed when jumping compared to holding the stick forward. This is especially noticable on rails. Neutral stick jumping off of a rail will retain **ALL** of your speed, even through a double jump, as long as you stay in ball form and don't move the stick. If you've ever played with 0 jump deceleration in Frontiers, it's that but only in this specific situation and literally nowhere else.

Also, neutral sticking seems to make entering levels from White Space more responsive. Don't ask me why it's like this, I will start sobbing.

On a more serious note, neutral sticking is also pretty useful for angling Shadow precisely. Boosting or air boosting while neutral sticking will send Shadow at the exact angle he is facing. If you want to retain an angle while still moving, neutral sticking makes it easy.

### Rail Switching
Switching between rails that are sloped downwards gives you a significant amount of speed. This can be stacked by repeatedly switching back and forth between downwards facing rails, allowing you to build a massive amount of speed. The speed isn't unlimited, it seems to cap at around 90.

### Bunnyhopping
Just before you land, while in the Spear state, you have a very small input window to double jump. This will refresh your air boost but not count you as properly grounded. This can be used to build speed when done on a slope, but is mainly used to skip the building sliding section in ARK 1 and RH 1.

### Surf Brother
Spamming sidestep or jumping while using Doom Surf will conserve all of your speed. Doing this after a Surf boost allows you to go incredibly fast across the water.

### Morph Jumping
Pressing jump just as you get the speed boost from a Morph boost allows you to carry the speed in the air. This can be used to get massive height when boosting upwards, or allows you to traverse massive gaps.

## Doom Wings

### Flight Basics
Holding air boost in midair with Wings activated allows Shadow to start flying. While flying, Shadow will maintain *most* of his height (there is slight height loss, this is especially noticable in 2D) and glide freely through the air.

In 3D levels, flight speed can exceed the "maximum". When you start flight, the game multiplies your current speed by some number ranging from 0.83 to 0.9 (the exact specifics elude me and I do not want to go crazy researching them). If the result of this multiplication is less than 50, it'll set your speed to 50. If the result is more than 50, your max flight speed will be that speed. This seemingly doesn't apply to 2D levels. From what I can test, your speed will always be set to max flight speed (30) when starting flight, but there aren't really many places in 2D levels where you can get significant speed, so it's hard to test.

### Wingteching
Wingteching is when you start an air boost with Wings, then immediately cancel it with a Spear. Because Doom Wings give you infinite air boosts, you can keep wingteching until you run out of boost.

Wingteching has two main purposes:

- Maintaining speed across incredibly long distances. Wingteching cancels the air boost before the flight speed reduction kicks in, while also resetting your falling speed. This allows you to zoom across incredible distances with way more speed than intended.
- Gaining height. Air boosting gives you a very slight amount of height. Normally, this doesn't matter, but wingteching allows you to chain these height gains into each other repeatedly.

### Instawings
Activating Wings normally traps Shadow in an animation for about 1 second. This animation can be cancelled by hitting something like a spring or a dashpad just as you activate Wings.
