# JOURNAL
---
**Date: 17 Jun, 8.15pm**

**Time Spent: 1.5hr**

**What I Did:**

1. researched some models to use as reference

    [model 1](https://makerworld.com/en/models/2513119-fidget-clicker-12-combos-satisfying-clicks?from=search#profileId-2764156)

    [model 2](https://www.printables.com/model/1077133-2x2-key-switch-fidget-lanyard)

    [model 3](https://www.printables.com/model/749387-double-key-switch-fidget-lanyard)

    [model 4](https://www.printables.com/model/681858-single-key-switch-fidget-lanyard)

    [model 5 (has lighting too)](https://makerworld.com/en/models/2180608-lighted-led-clickers#profileId-2366663)

2. found a tutorial on how to connect battery + led without using microcontroller

    [tutorial link](https://www.instructables.com/Keyboard-Switch-Keychain/)

3. found a tutorial for making the case, but it's in tinkercad and does not have space for the electronics

    [youtube tutorial link](https://www.youtube.com/watch?v=eqajrLeaFB8)

4. Finally found a box/LED template to fix the LEDs in. Will use it to design the base.

    [link to the model containing the base (i'm using box.stl from this)](https://makerworld.com/en/models/2776610-led-clicker#profileId-3085159)

---

**Date: 17 Jun, 11:40pm**

**Time Spent: 3.5hr**

**What I Did:**

Locked In on CAD case. Almost done with it,

Steps I followed:
- finally managed to upload the holder.stl file to existing fusion design (which I had just created)
- measured the holder.stl file, took some time finding how to do it (couldn't locate the measurement tool)
- found out the stl file is not in center, re-imported it properly
- made sketch 1 for the outer case + sketch 2 for the inner hole to place holder in
- extruded them at least 3 times, because I kept messing it up => case looked like case
- added fillet + chamfer to the case
- realised i wanted to make 2x2 fidget, not single keycap
- deleted the fillet + chamfer
- confused myself for the next 20-30 mins on how to make the other same ones (since there is no dedicated duplicate button)
- found the obvious answer, just duplicate it and place it together
- duplicated and placed 4 of them together
- added fillet + chamfer again
- realised the thickness of the case is not enough
- removed the duplicated ones
- modified inital sketches to increase the thickness
- added the duplicates again
- started to add fillet + chamfer again
- realised i need to make this a pendant => i need to add a hole
- searched online again for inspiration => settled on cut from inside kinda one
- found out how to make it (shoutout to gemini for telling me so many do-i-even-need-these steps)
- made the holde to add pendant ribbon
- added fillets + chamfers
- tried rendering the thing
- realised i missed one edge => added fillet to it
- took a photo of the completed thing!!!

screenshot of the case without holder
![screenshot of the case without holder](./images/day1_case_img1.png)
screenshot of the case with holder
![screenshot of the case with holder](./images/day1_case_img2.png)

gonna get it sanity checked now.

will write BOM and readme properly now.

---

**Date: 18 Jun, 10:30am**

**Time Spent: 1hr**

**What I Did:**

made the BOM.

1. made a list of stuff I needed
2. found each component individually on many many platforms
3. comapred prices + shipping
4. didn't find many alternatives for most components
5. learnt how to make table in Markdown
6. ultimately used a markdown table generator
7. calculated prices in usd and totalled them

next step is readme + assembly + adding files

---

**Date: 19 Jun, 12:50am**

**Time Spent: 1hr**

**What I Did:**

added case files to the repo
added readme to the repo
added pictures to the repo
make + added schematic from kicad

---