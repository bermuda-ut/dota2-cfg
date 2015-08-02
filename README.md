Bermuda's DOTA 2 CFG
==============
**By The Community**



What is it?
--------------
It is Dota 2 Configuration file to expand option pool for further customization to meet user's taste.
The Features include:
- Quick Courier
- Quick Rune Cameras
- Toggle HP marks
- Performance Improvements (Testing for Reborn)
- Easter Eggs :P
- And MORE!
Before Reborn Beta, it used to be created and updated by Bermuda however now it is open to community to contribute.

Visit [the original Wordpress post](wp.me/p18fP6-ir), for details.


Contributing
--------------
**Before submitting any changes**
- Make sure it is useful and optimized for the general public. (Ex. fps cap to replace vsync > most people has 60Hz monitor therefore 60.)
- Comment your functions and intentions clearly.
- You may use 1(one) line of comment for credits in cfg file.
- Do not copy/paste from other CFG, post them on discussions.
Bermuda will respond to updates daily, any major changes in the CFG will lead to updating the blog post.


Personal Note
--------------
*It has come to the state where I cannot respond to Dota 2 updates and cfg changes as quickly as I used to be able to.*
*Due to this, I decided to make the CFG open source and allow anyone to contribute to the CFG. I will monitor the requests daily and respond as soon as possible. (I will still work on the cfg.)*
*Thank you for your support. See you in game. :)*


Release Log
--------------
Final log 02/08/2015

*10/02/2014* : v1.00
- Initial version

*14/04/2014* : v1.10
Change log :
- APM is now a separate command.
- dota_embers disabled on default. Moved to client side settings.
- Camera settings disabled on default. Remove the most front // in the line to apply settings
- Command for taunt line is now more appropriate
- New taunt line
- Roshan timer will now only show the time of Roshan death in chat instead of buggy weird lines.

*22/05/2014* : v1.20
Change log :
- Added spectator mode! Custom camera speed and higher camera distance upon toggle.
- In-game mic volume setup added. (voice_mixer_volume)
- Rearranged bindings section. Bindings are grouped accordingly.
- Rearranged greeting message.
- The cfg is now more notepad friendly.
- Link to this post use WordPress short link now.

*08/06/2014* : v1.21
Change log :
- Added manual disconnect. Default key is keypad minus (-)
- Fixed memory issues that caused the game to crash.
- Re-optimized network setting.

*22/06/2014* : v1.30
Change log :
- Fixed basic rune camera according to the latest patch. Thank you Thiago for the report!
- Added quick rune cameras. Custom binding Space. 3 types available, use whichever comfortable.
- Lone Druid Bear return binding moved to k on default.
- Added custom chat channel script. Please edit to join your channels automatically.
- Removed Spectator higher camera - Valve added this officially now :) Simply use mouse scroll to zoom out!
- r_renderoverlayfragment enabled on default due to error reports. Disable it manually for possible performance improvement.
- Changed some explanations and annotations in the cfg.

*24/06/2014* : v1.31
Change log :
- Quick Rune Camera should work according to the gif now :)
- Fixed the rune camera according to the new patch. (Valve changed the command for camera position in the latest patch.)
- Fixed some typos in the annotations.
- Changed some descriptions and annotations to squeeze more sense out of them.
- “contimes 3″ is now together with “developer” command. That makes much more sense now.
- Slightly regrouped and rearranged bindings section.

*09/07/2014* : v1.32
Change log :
- Roshan Timer does not work anymore (Thank you Karosuu for the report!). Valve decided to disable the feature in multiplayer games. Nothing we can do.. :/
- Roshan Timer command is now Roshan Death. Only displays the time of its death on team chat.
- Quick courier script optimized. Still does the same thing.
- Lone Druid bear script changed a bit. It will now select the bear and the hero when you use “bear_return” or “bear_phase_boots”. Does not move the camera.
- Changed some annotations in the CFG. Deleted off unnecessary.

*26/08/2014* : v1.33
Change log :
- APM is now default bound to F6. Enhanced APM command - Press F6 to view APM, press F6 to go back to game! Initially, it was a simpler inefficient command pointed out by spamowysmietnik666. However, unlike his solution, I decided to add stuff rather than keeping it simple. Thank you for the report spamowysmietnik666!
- Troll command added. Tells a short story of potato engineer in Wadiya to everyone in game..
- Manual disconnect now logs console message.
- Kill camera disable/enable function deleted - ie. dota_killcam_show deleted from the config. The command no longer exists. Yet to find a replacement.
- Just in case someone tried to revive kill cam command but failed like I did, dota_sf_hud_force_killcam 0 added - keep this 0. Will still show kill cams when your hero dies.

*07/09/2014* : v1.40
Change log :
- Re-worked System/Performance settings. Things have changed and adopted to the latest big patch.
- New on/off commands to improve your fps : r_deferred_simple_light, r_deferred_simple_projections
- You have beast PC? Use r_lod. Enables high quality textures.
- snd_mix_async moved to multi-core settings.
- Gameplay related section re-arranged.
- Easter Eggerino.
- Added toggle console command : default bound to F11.
- Added a command to list out current settings in the console. Press the key, opens console, outputs current settings! Default bound to Page Down.
- Binding section rearranged. Comments changed a bit.

*27/09/2014* : v1.41
Change log :
- r_deferred_simple_projections 0 actually disables AOE skill circles. Default is now 1. Excuse my mistake and ignorance. Thank you Iѕмαιℓy for the report!
- Changed some comments and explanations about the commands.
- Added 1.50 announcement in the title.

*24/11/2014* : v1.50
Change log :
- CFG layout is now optimized for Notepad++. You can use this custom language to make your editing easier.
- Added ping function. Press END to automatically open console, output everyone’s ping. Press ESC to go back.
- Added dsp_slow_cpu and snd_pitchquality. Both are set to default values, more optmized value written in cfg.
- Added mat_reduceparticles and mat_reducefillrate.
- Correctly shows welcoming message at the start of the game.
- Reloading script now does not toggle console.
- contimes now default to 5.
- fps_max moved to the top of the cfg to encourage editing it.
- Minor description changes.

*10/02/2015* : v1.51
Change log :
- cl_singleplayernetworkbackdoor option added under Client Side Settings. Recommend keeping it 0.
- dota_hud_reduced_flash added under System/Performance. Default at 0, make it 1 to squeeze more performance.
- Added cl_detaildist and cl_detailfade. Increase/decrease it within the recommended range for visual/performance.
- Added HP mark toggles. Marks toggle 350>450>250(default). Useful for Axe ultimate. Credits to お ƘƝȊƓȞƮ を
- Updated descriptions for System/Performance. Thanks for the reminder(quite long ago lol), Aphotic.

*02/08/2015* : vCommunity
Change log :
- Removed/Commented out obselete commands.
- Tweaks reset to defaults.
- The CFG is now on github. Bermuda will respond to updates daily, any major changes in the cfg will lead to updating the blog post.
- This is the last entry of this change log. Please check github changelogs for details.