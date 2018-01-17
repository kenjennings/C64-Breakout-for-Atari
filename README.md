# C64_Breakout_for_Atari

Video of game and attract mode play on YouTube:  https://www.youtube.com/watch?v=7OfxLa1_2Jk

[![BreakoutTitleScreen](https://github.com/kenjennings/C64-Breakout-for-Atari/blob/master/BreakoutTitleScreen.png)](#features)

Breakout clone originally written for the C64. Source code ported to run on Atari with MINIMAL changes.

---

```asm
; C64 Breakout clone
; 2016 - Darren Du Vall aka Sausage-Toes
; Original C64 source at: 
; Github: https://github.com/Sausage-Toes/C64_Breakout
```

---

```asm
; Atari-fied for eclipse/wudsn/atasm by Ken Jennings
; Atari source at:
; Github: https://github.com/kenjennings/C64-Breakout-for-Atari
; Google Drive: https://drive.google.com/drive/folders/0B2m-YU97EHFESGVkTXp3WUdKUGM
```

---

NOTE that there are TWO release versions here.  
Version 1.0 works with some minor display issues.  
Version 1.0a is the current version with display problems fixed and the addition of an automatic running attract/demo mode. 

---

This is primarily a demonstration in porting code between platforms.  As a Breakout clone it's pretty flawed exhibiting several questionable behaviors:
- Gigantic ball 
- Four rows of bricks instead of 8 rows. 
- No speed progression. 
- The ball rebounds in all directions from all objects all the time.
- Huge gaps between bricks.
- Ball movement is prone to becoming trapped in rows and zippering through a line of bricks.
