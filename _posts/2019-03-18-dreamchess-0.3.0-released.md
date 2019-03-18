---
title: DreamChess 0.3.0 released
author: walter
---
DreamChess 0.3.0 is finally here. Eleven years have passed since the last
official release, with only a few release candidates happening in between.
Why has it taken so long? One reason is that the DreamChess team currently
consists of only two developers. Another reason is that we received very
little feedback for these release candidates, which made us reluctant to put
up a new official release. Especially considering the time and effort that
goes into building, testing and uploading official binaries.

Obviously this situation was far from ideal, and we wanted to lower the burden
for doing a release. We hope to have accomplished this now by integrating CI
systems. If things go according to plan, you can expect to see more frequent
releases from us going forward. These releases won't be getting the same
amount of testing that previous releases have had, but if problems pop up, we
should be able to get them sorted quickly, and push out a new version.

We hope you enjoy this long-awaited release.

Most important changes:
- Widescreen support
- Now uses SDL2 instead of SDL1
- Now uses Expat instead of mxml
- CMake build system
- Fixed issue with chess piece selection on some AMD GPUs
- Fixed issue with rotating chess board on some Linux machines
- Board is automatically flipped when playing with black
- Pondering support in Dreamer chess engine
- New icon
- Music pack support on macOS
