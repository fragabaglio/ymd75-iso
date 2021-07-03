# ymd75-iso
QMK config files for the ymd75-iso keyboard (revision 3).
Created using the initial config available on [mtkeyboard.vip](mtkeyboard.vip).

That config has one missing thing: it does not have volume up/down/mute; so I have added that. Also, the second key of the 5th row is mapped wrong. After trial and error I've found the right one, which is <code>KC_NUBS</code>, and I've corrected it.

I have then exported the .json file and converted it using [noroadsleft's kbf_qmk_converter tool](https://noroadsleft.github.io/kbf_qmk_converter). 
