# Splitpage

**The script editor for videos you actually have to shoot.**

Picture on the left, words on the right, and everything the shoot needs is pulled out of the script as you write it. Then you read it off the built-in teleprompter, one scene at a time.

<picture>
  <source media="(prefers-color-scheme: light)" srcset="images/split-view-light.png">
  <img alt="Splitpage split view: visual column with reference frames and tagged props, audio column with narration" src="images/split-view-dark.png">
</picture>

<p align="center">
  <a href="https://github.com/RetroGorilla/splitpage-releases/releases/tag/v3.0.0-beta.1"><b>Download 3.0 beta</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/RetroGorilla/splitpage-releases/releases">All releases</a>
</p>

---

## Why it's different

You've written scripts in a Google Doc, kept your shot list in another doc, tracked props in a spreadsheet, and pasted the narration into a teleprompter app. Splitpage does all of that in one file.

### Tag while you write, get a shot list for free

Type `[gaffer tape]`, `{kitchen}`, `~lens flare~` or `<wireless lav>` and it becomes a tracked prop, location, VFX shot or piece of gear. Cast and music/SFX are one click. Every tag lands in the **Production breakdown** with the scenes it appears in, who's getting it, and how far along it is: *Needed → Sourcing → Have it → Returned*.

Forgot to tag something you already track? Splitpage underlines it and offers to tag it for you.

### Plan the shoot day by location

The **Shoot** view regroups your script by where it's filmed. Every scene at one location sits in one block, with everything that has to be there and whether it's in hand yet.

![Production breakdown grouped by shooting location](images/shoot-day.png)

### A teleprompter built for solo shooters

**Scene mode** cues one scene, plays it, and stops at the end, ready for the next take. Step through takes with ← →. **Follow My Voice** scrolls as you talk. In the Windows app it runs on Windows' own speech recognition, so it works offline. Mirror and flip are there if you use a beam-splitter rig.

![Teleprompter in scene mode](images/teleprompter.png)

### Pick up where you left off on day two

Click a scene's dot to mark it *To do → Ready → Shot*. **Hide shot scenes** (Ctrl+Alt+H) collapses everything you've already recorded, the runtime chip shows what's left to read, and the teleprompter skips shot scenes too.

![Shot scenes collapsed into one strip](images/hide-shot.png)

---

## Also in the box

<table>
<tr>
<td width="50%" valign="top">

**Writer mode.** Just the narration, as one flowing document, with the visuals greyed out in the margin. Word count and runtime update as you type. Export the narration as `.docx` for a voice artist.

</td>
<td width="50%" valign="top">

<img alt="Writer mode" src="images/writer.png">

</td>
</tr>
<tr>
<td valign="top">

**Comments that stay put.** Anchored to the exact phrase, with replies, assignees and Open / Resolved filters. Send an editor or client a **review link**: they can read, run the teleprompter and comment, but the server won't let them change a word.

</td>
<td valign="top">

<img alt="Comments panel" src="images/comments.png">

</td>
</tr>
<tr>
<td valign="top">

**A gear list that isn't in the script.** Nobody writes "wireless lav" into narration. Type your kit into the Gear screen, one item per line, then print a packing list to check off before you leave.

</td>
<td valign="top">

<img alt="Gear screen" src="images/gear.png">

</td>
</tr>
</table>

- **Runtime estimate** per scene and for the whole video, set to your own reading speed.
- **Reference frames** in each scene: drag an image onto the visual column.
- **One undo for everything** (new in 3.0): typing, tags, moved or split scenes, statuses, pictures, comments.
- **Work with other people** on your network. Edits to different scenes merge on their own, and in 3.0 edits to the same scene merge word by word.
- **Exports** to Word, PDF, Markdown, plain text and a CSV breakdown that filters down to one person's pull list.
- **Your files, no account.** Scripts save as plain Markdown or a single `.splitpage` file, with version history built in.

---

## Install

Grab a file from the [releases page](https://github.com/RetroGorilla/splitpage-releases/releases):

| File | For |
| --- | --- |
| `SplitpageDesktopSetup-<version>-x64.exe` | Most Windows PCs (Intel/AMD) |
| `SplitpageDesktopSetup-<version>-arm64.exe` | Windows on ARM (Snapdragon, Surface Pro X) |
| `splitpage-<version>.zip` | Portable, for Windows, macOS and Linux. Unzip, then run `start.bat` or `./start.sh` |

The installers aren't code-signed yet, so Windows SmartScreen will warn on first run. Click **More info → Run anyway**. `SHA256SUMS.txt` on each release lets you check the download.

Installed copies update themselves from this page.

> **3.0 is in beta.** Copies on 2.1 won't be offered it automatically. Download it from the [3.0.0-beta.1 release](https://github.com/RetroGorilla/splitpage-releases/releases/tag/v3.0.0-beta.1). The beta's portable zip can't detect later updates, so check back here. The installers aren't affected.

---

<sub>This repository only hosts release builds. The source is private.</sub>
