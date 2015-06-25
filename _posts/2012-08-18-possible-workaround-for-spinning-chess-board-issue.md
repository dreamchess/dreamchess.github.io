---
title: Possible workaround for spinning chess board issue
author: Walter van Niftrik
---
A few days ago we were contacted by Martin Deisenroth. He kindly offered to help us investigate the spinning chess board issue in Linux. It turned out that in his case the problem is caused by an accelerometer in his HP laptop, that is being reported as a joystick by the operating system. DreamChess has joystick support, a leftover from the original DreamCast version. This accelerometer is continuously sending events to DreamChess, causing the board to spin. If you're also experiencing this issue, you could try the following workaround:

Run DreamChess like this:

**SDL_JOYSTICK_DEVICE=/dev/null dreamchess**

or, for a more permanent solution, put this in your ~/.profile file and reboot:

**export SDL_JOYSTICK_DEVICE=/dev/null**

A big thanks to Martin for his help!
