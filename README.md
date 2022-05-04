# Nerd-Dictation Toggler

![script-showcase](https://user-images.githubusercontent.com/10383240/166626003-aaf5bb84-a77f-49a0-ad8b-c3b2619f223f.png)

## What is it?
This is a shell script to toggle nerd-dictation on and off. You can bind this script to a keyboard shortcut in your desktop environment/window manager, or use it in a Cinnamon applet like `commandLauncher@scollins`. 

## Directory checking
By default, this script runs from and lives in a subfolder you create, `nerd-dictation/toggle`, when nerd-dictation is located at `/home/$USER/Documents/git/nerd-dictation`. Keep that in mind, or change the checked path.

## Additional Notes
If you want to combine other on/off commands, retooling this script might save you some time. I made this after realizing `nerd-voice` didn't have a toggle option a-la `albert toggle`. 

Try holding ctrl+shift while dragging `togglevoice` from another Nemo window into one opened as root to `/usr/bin`. This will create a symlink, allowing you to run it without adding anything to your PATH. Note: You'll *need* to do this for the `nerd-dictation` executable for the script to work. 

## Nerd Dictation?
"Simple, hackable offline speech to text - using the VOSK-API." - https://github.com/ideasman42/nerd-dictation


