# BitfocusCompanionATEM
ATEM control Preset for Bitfocus Companion with a Streamdeck XL

Created on a Raspberry Pi Companion build running v 2.2.0-1e65f702-3485
Built for and tested with an older generation Atem 2 ME
Set up with 5 inputs in the Program and Preview rows. 
4 keys with cut and auto buttons. This includes your upstream keys, so you can treat them more like downstream keys if you want.
Transiton select buttons for BG and keys. Note that The ATEM won't allow you to just have a downstream key tie selected. You must have the background and/or a upstream key in the transition select. 
Auto transiton on Upstream keys are set with a 600ms delay for actions that 'revert' the settings to normal, so if you want a longer auto transiton, you may need to adjust that to avoid running into issues.
