# The-Mortuary-Assistant-VR
VR Mod for The Mortuary Assistant 


THE MORTUARY ASSISTANT VR  v0.1.5
=================================
VR mod for "The Mortuary Assistant" (Unity 2021.2.4f1, IL2CPP x64, HDRP, Unity Input System) - BepInEx 6 be.788.

Install
-------
1.unzip into the game folder (next to "The Mortuary Assistant.exe").
   
2. Start Quest Link / Virtual Desktop / SteamVR first (it must be the OpenXR runtime), then the game.

You see the world from Rebecca's eyes. Head look: she looks, walks and uses things where you look. The game's
menus and HUD float on a screen in front of you (solid in menus, see-through in play).

Controls (the VR controllers are an Xbox controller for the game)
--------
Normal play:
  Left stick ................... walk 
  
  Right stick left / right ... turn (snap or smooth)
  
  Right stick up ............... d-pad up  
  
  Right stick down ........... d-pad down (**start game**)
  Right grip ................... A (use)  
  
  Left grip .................. LB
  
  Triggers ..................... LT / RT  sprint\crouch
  
  Hold X (0.6 s) ............... interact laser on / off (a tap is still X)
  
  Pushing the gurney ........... it turns with the right stick (the game's own steering), not with your head;
                                 your view turns with Rebecca, you can look around freely
                                 
  Interacting: point the RIGHT controller at what you want to use (thin green laser); the interaction prompt
  
  (reticle, the name of what you point at, the gurney prompt) floats just above the right controller, the small
  icons from the bottom right of the HUD just below it.
  Quick inventory: you keep turning as in play
  
Main menu (title screen): right stick = d-pad down

Menus, inspecting items, clipboard, computer, cut-scenes: a normal Xbox controller

Always:
  X + Y together ............... Back
  
  A + B together ............... Start
  
  Tap both stick clicks ........ re-centre the view
  
  Hold both stick clicks 1.2 s . VR settings menu (right stick = choose / change, A = select, B = close)

In your LEFT hand: the clipboard (while Rebecca holds it up) and any item you pick up and examine (turn it with the

Her arms on your controllers (option, off by default): VR settings menu > "Her arms follow your controllers"
([Arms] GameArmsFollowControllers). Each of Rebecca's arms follows its controller (what she holds comes along);
the VR hands are hidden then. Hand place / turn: [Arms] HandOffset, HandRotation.

Blue laser in menus (option, off by default): VR settings menu > "Blue laser pointer in menus" ([Input] MenuLaser).
Point the right controller at the floating screen, right trigger = click.

