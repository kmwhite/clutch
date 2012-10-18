# Clutch

## What is it?
Clutch is a tool for passing instructions to EWMH compliant window managers to position then in any one of eight possible locations:
 * Top Half
 * Upper Right Quarter
 * Right Half
 * Bottom Right Quarter
 * Bottom Half
 * Bottom Left Quarter
 * Left Half
 * Top Left Quarter

It was inspired by the great tool [ShiftIt!](https://github.com/fikovnik/ShiftIt) for Mac OS X

## Using it
To use it, set up hotkeys in your window manager to trigger the script. A fluxbox example is:

    # Clutch Relating Bindings
    Mod1 Mod4 Up :Exec clutch top
    Shift Mod1 Mod4 Up :Exec clutch top-right
    Mod1 Mod4 Right :Exec clutch right
    Shift Mod1 Mod4 Right :Exec clutch bottom-right
    Mod1 Mod4 Down :Exec clutch bottom
    Shift Mod1 Mod4 Down :Exec clutch bottom-left
    Mod1 Mod4 Left :Exec clutch left
    Shift Mod1 Mod4 Left :Exec clutch top-left

## License
Copyright (c) 2012, Kristofer M White
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

 *  Redistributions of source code must retain the above copyright notice,
this list of conditions and the following disclaimer.`

 *  Redistributions in binary form must reproduce the above copyright
notice, this list of conditions and the following disclaimer in the
documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED
TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
