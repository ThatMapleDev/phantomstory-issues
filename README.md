# PhantomStory Issue Tracker

This is where you report bugs and suggest features for **PhantomStory** ([phantom.ms](https://phantom.ms)).

A good report gets fixed fast. A report that says "the game is broken" usually cannot be fixed, because nobody
can find the problem. This page explains what to put in an issue so we can find it on the first try.

**[→ Open a new issue](https://github.com/ThatMapleDev/phantomstory-issues/issues/new)**

---

## Before you post

1. **Search first.** Look through the [open issues](https://github.com/ThatMapleDev/phantomstory-issues/issues).
   If someone already reported your problem, add a comment with your own details or give it a 👍.
   Don't open a second issue for the same problem.
2. **One problem per issue.** If you found three bugs, open three issues. Each issue gets closed on its own
   when its problem is fixed.
3. **Try it again once.** If you can, refresh the page or restart the game and check whether the problem
   happens again. Tell us what you found either way. A problem that happens only once is still worth
   reporting.
4. **Never post your password** or anything you use to log in, not even in a screenshot.

> **Found an exploit** (item or meso duplication, a way to get infinite EXP, a way to crash the server or other
> players)? **Do not post the steps publicly.** Open an issue titled `Private report` that only says what
> kind of problem it is. We will contact you for the details.

---

## Writing the issue

### The title

The title should say **what goes wrong and where**, in one line.

| ❌ Not helpful | ✅ Helpful |
| --- | --- |
| Bug | Character falls through the floor on the left rope in Henesys |
| Help!!! | Inventory window stays open after closing it with Esc (browser) |
| Doesn't work | Buying 100 potions from the Henesys shop takes the mesos but gives no potions |
| Crash | Game freezes when I enter the portal to Ellinia with a party |

### The description

Copy the template below into your issue and fill in every part. If a part does not apply, write `n/a`.

```markdown
**What happened**
<!-- One or two sentences. What went wrong? -->

**What I expected to happen**
<!-- What should have happened instead? -->

**Steps to make it happen**
1. 
2. 
3. 

**How often**
<!-- Every time / sometimes (about how often?) / only once -->

**Where and when**
- Character name:
- Map:
- Date and time (with your time zone):

**How I play**
- Device: <!-- Windows PC / Mac / Android phone / Android tablet / ... -->
- In the browser? <!-- Yes: which browser (Chrome, Edge, Firefox, Safari, ...) / No: which app -->
- Controls: <!-- keyboard / gamepad / touch -->

**Screenshots or video**
<!-- Drag files into this box. See the README for how. -->

**Anything else**
<!-- Browser console errors, what you did right before, whether other players saw it too, ... -->
```

#### Why each part matters

- **Steps to make it happen** are the most important part. If we can make the problem happen ourselves, we
  can almost always fix it. Write them as if the reader has never played the game: *"Go to Henesys. Open the
  inventory with I. Drag the Red Potion onto the equipment window."* Don't write "use an item".
- **Character name, map, date and time** let us find your session in the server logs. Always add your time
  zone (for example `2026-09-18 21:40 CEST`), because the server runs on a different clock than you do.
- **Device and browser** matter because the game runs in the browser, on Windows and on Android, and a
  problem often shows up on only one of them.
- **How often** tells us whether to look for a mistake that always happens or a timing problem.

---

## Screenshots

A screenshot often explains a problem faster than a paragraph of text.

### How to take one

| Where you play | How |
| --- | --- |
| Windows | Press **Win + Shift + S**, drag a box around the game, then paste into the issue with **Ctrl + V** |
| Mac | Press **Cmd + Shift + 4**, drag a box; the file lands on your desktop |
| Android | Press **Power + Volume down** at the same time |
| iPhone / iPad | Press **Side button + Volume up** at the same time |

### How to add it to the issue

Drag the image file into the description box, or paste it with **Ctrl + V** (Mac: **Cmd + V**). GitHub
uploads it and puts a link in the text. Wait until the upload finishes before you press *Submit*.

### What makes a good screenshot

- **Show the whole game window**, not just the broken part. The map, your position and the open windows around
  the problem are often the clue.
- **Mark the problem** with a circle or arrow if it is small. The Windows Snipping Tool and most phones have
  a pen tool for this.
- **One screenshot per thing.** For a before/after problem, add one screenshot before and one after.
- **Leave the text readable.** Don't shrink the image down or take a photo of your screen with a phone.
- **Hide private information** (your email address, other chat windows, your desktop) before uploading.

---

## Videos

Use a video when the problem **moves**: bad animations, falling through the floor, lag, a monster that
walks the wrong way, a window that flickers, or anything that takes several steps.

### How to record one

| Where you play | How |
| --- | --- |
| Windows 11 | Open the **Snipping Tool**, choose the video camera icon, and drag a box around the game |
| Windows (any) | Press **Win + Alt + R** to start and stop recording (Xbox Game Bar). Videos are saved in `Videos\Captures` |
| Mac | Press **Cmd + Shift + 5** and choose *Record Selected Portion* |
| Android | Swipe down twice and tap **Screen recorder** |
| iPhone / iPad | Add *Screen Recording* in Control Centre settings, then tap it in Control Centre |
| Anything | [OBS Studio](https://obsproject.com) (free) |

### Tips

- **Start recording a few seconds before the problem** and stop shortly after it. 10–30 seconds is plenty.
- **Keep it small.** GitHub accepts `.mp4`, `.mov` and `.webm` files up to **10 MB** on free accounts.
  Drag the file into the description box, like a screenshot.
- **Too big?** Upload it to YouTube as *Unlisted* (or to any video site) and paste the link in the issue.
- **Say at what second the problem happens**, for example *"at 0:12 my character goes through the floor"*.
- Turning on in-game sound helps for sound problems. For everything else it doesn't matter.

---

## Browser console log (browser players)

When the game freezes, shows a black screen or will not load, the browser often writes an error message you
cannot see. It helps a lot to include it.

1. Press **F12** (Mac: **Cmd + Option + I**) while the game tab is open.
2. Click the **Console** tab.
3. Make the problem happen again if you can.
4. Right-click inside the console, choose **Save as…**, and drag the saved file into the issue.
   If that option is missing, select the red lines, copy them, and paste them into the issue between
   ```` ``` ```` lines.

---

## Suggesting a feature

Feature ideas are welcome too. Describe:

- **What you want**, in one or two sentences.
- **Why**: which problem it solves, or what it would make better for you.
- **Examples** from the original game or other games, with screenshots if you have them.

---

## A good report, start to finish

> **Title:** Character falls through the floor on the left rope in Henesys
>
> **What happened**
> When I climb up the left rope in Henesys and jump off at the top, my character falls through the platform
> to the ground.
>
> **What I expected to happen**
> To land on the platform at the top of the rope.
>
> **Steps to make it happen**
> 1. Go to Henesys and walk to the far left.
> 2. Climb the rope next to the tree to the top.
> 3. Hold the right arrow and press the jump key to jump off to the right.
>
> **How often**
> Every time (5 out of 5 tries).
>
> **Where and when**
> - Character name: Mushroomer
> - Map: Henesys
> - Date and time: 2026-09-18 21:40 CEST
>
> **How I play**
> - Device: Windows PC
> - In the browser? Yes, Chrome
> - Controls: keyboard
>
> **Screenshots or video**
> `rope-fall.mp4` (the fall happens at 0:07)
>
> **Anything else**
> Jumping off to the left works fine.

---

## What happens after you post

1. We read the issue and add a **label**:

   | Label | Meaning |
   | --- | --- |
   | `bug` | Something is broken |
   | `enhancement` | A new feature or an improvement |
   | `question` | We need more information from you. **Please check back and answer** |
   | `duplicate` | Already reported. We'll link the other issue |
   | `accessibility` | Makes the game harder to play for people with a disability |
   | `wontfix` | We decided not to change this, and we'll explain why |
   | `invalid` | Not a problem with the game |

2. If we ask a question, reply in the same issue. Issues labelled `question` without an answer may be closed
   after a while.
3. When the problem is fixed, the issue is closed. If it comes back later, open a new issue and link the old one.

Thank you for helping make PhantomStory better!
