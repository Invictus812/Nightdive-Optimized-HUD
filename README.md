# SBARDEF HUD: Nightdive Optimized v0.9
Currently in beta: A hyper-optimized HUD for Doom inspired by the modified Nightdive HUDs by NightFright2k19 and liPillON. 
Only compatible with recent builds of Woof! at this time.
Please skip to the bottom for a bulleted list of features.

I suppose a part of me wishes I'd gone into graphic design :p  
After using several of NightFright2k19's _**excellent**_ HUDs from his SBARDEF mod, but not finding any particular one to be _just right_ **for me**, and discovering that the Cacoco Editor:  
1: exists, and  
2: is in a usable state,  
I endeavored to create my own HUD that builds on the others that came before, primarily intending to stick to the "modified Nightdive" theme.  My goal was the same as, I think, everybody intends when creating something like this: show the player everything they need, and nothing that they don't.  
As such, no parts of this HUD are truly static, and it is allergic to the number 0.  It will not display information about something if you have no use for it, and it will not show you redundant information.  For example, for your standard pistol start:  

<img width="1917" height="417" alt="woof0008" src="https://github.com/user-attachments/assets/16e928f2-91a2-45a7-a01f-ac33a4a4e5ad" />

This is what you're presented with.  There is no armor displayed as you have none.  No additional ammo is displayed; all it would say is "zero".  Your ammo display will update dynamically as you pick things up, eventually culminating in your HUD looking like this:

<img width="1917" height="1080" alt="woof0006" src="https://github.com/user-attachments/assets/713acf9a-a830-4088-a1fe-20e8776596af" />

The red fist in the bottom right next to the ammo counter is the berserk indicator. Yellow numbers indicate that the player has picked up a backpack.  
The "total ammo" display shifts as different types are picked up, and will change which are displayed depending on which weapon is selected.  

<img width="933" height="261" alt="woof0012" src="https://github.com/user-attachments/assets/fc8ffaa8-38e4-42b9-a52a-3d2a8bf4408f" />

When you switch to a melee weapon and the ammo counter has to disappear, the entire display collapses into the corner:  

<img width="1917" height="329" alt="woof0007" src="https://github.com/user-attachments/assets/b8371fce-d226-4262-a4ba-d38e93397506" />

Lastly, I wanted to do something special for an actual death screen:  The mugshot of our dead doomguy becomes centered, all other elements are cleared, and the obituary string gets a little extra flair (shown here with one of my custom DeHackEd strings, optional):  
<img width="1917" height="1080" alt="woof0005" src="https://github.com/user-attachments/assets/dc0c146b-b9cc-4879-9f64-79f6b08de1a9" />

I think this thing's pretty-well feature-complete, but there's absolutely no way I can anticipate, find, and squash every possible bug... and I know for sure they're there. So I'm calling this a v0.9 beta release and am hoping I get some decent feedback on any possible issues so they can be corrected, hopefully to push a 1.0 release before too much time passes.

**Complete List of Features:**  
- Dynamically updating ammo, armor, and keys displays
- Total ammo values shift from white to gold when a backpack is picked up.
- Berserk indicator
- Powerups appear over health with animations to alert the player when timers are nearing zero
- Ammo, keys, and berserk collapse when using a melee weapon.
- "Fuel" graphics for use with Legacy of Rust
- Messages are pushed a few pixels out of the corner for slightly better readability (inspired by Doom Retro)
- Weapons carousel has been adjusted down slightly and does not overlap either messages or level announcements
- New death screen behavior.

**Credits:**  
Roman Fomin & Fabian Greffrath - Woof and SBARDEF development  
Lizzie ShinKicker & Roman Fomin - Cacoco Editor  
NightFright2k19 & liPillON - Modified Nightdive HUDs for inspiration  
Nightdive - The original Nightdive HUD, duh.  
