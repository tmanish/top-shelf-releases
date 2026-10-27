# Top Shelf — User Guide

Top Shelf helps you choose the best photographs from a shoot *before* they go into your library. You review straight from the card or folder, mark what you want, and copy only those.

**The one rule Top Shelf never breaks:** it never changes your original files. It doesn't rename, move, edit, tag, or delete anything on your card or source folder. Ratings and keywords are written only to the copies.

This guide is built into the app (**Help ▸ Top Shelf Help**, ⌘?) and works offline. It's also published online in the [Top Shelf releases repository](https://github.com/tmanish/top-shelf-releases/blob/main/HELP.md).

**Contents**
1. [First launch](#1-first-launch)
2. [Opening a shoot](#2-opening-a-shoot)
3. [Finding your way around](#3-finding-your-way-around)
4. [Making decisions](#4-making-decisions)
5. [Best of Each Burst](#5-best-of-each-burst)
6. [One at a Time](#6-one-at-a-time)
7. [Looking closely](#7-looking-closely)
8. [Copying your keepers](#8-copying-your-keepers)
9. [Sending to your editor and other apps](#9-sending-to-your-editor-and-other-apps)
10. [Two-card shoots](#10-two-card-shoots)
11. [iCloud Drive folders](#11-icloud-drive-folders)
12. [Keyboard shortcuts](#12-keyboard-shortcuts)
13. [Settings](#13-settings)
14. [Updates](#14-updates)
15. [Troubleshooting](#15-troubleshooting)
16. [Privacy](#16-privacy)

---

## 1. First launch

Top Shelf asks you to choose two folders:

- **High-Resolution Cache** — where Top Shelf keeps temporary full-size working copies (used mainly for cameras). Pick a drive with free space. Top Shelf creates its own subfolder there and only ever cleans up that subfolder.
- **Default Export Folder** — where your chosen photos are copied unless you pick somewhere else. Each shoot gets its own folder inside it.

You can change both later in **Settings**.

## 2. Opening a shoot

From the home screen:

- **Memory card or drive** — insert it; it appears on the home screen. Click **Review Photos** and confirm access. (macOS requires that confirmation before any app can read a card.)
- **Folder** — click **Choose Folder to Review…** (⌘O), or drag a folder onto the home screen.
- **Camera** — connect it by USB; it appears on the home screen. If your camera doesn't show up or behaves oddly, put it in mass-storage/PC mode or insert its card instead.
- **Pick up where you left off** — recent reviews are listed on the home screen and under **File ▸ Open Recent Session**. Your decisions are saved automatically as you work.

You can start reviewing immediately. Top Shelf keeps organizing (finding moments, similar photos, and quality hints) in the background, starting with the photos nearest to where you are.

## 3. Finding your way around

- **Sidebar (left)** — show or hide it with the sidebar button at the top left.
  - *All Photos, Unreviewed, Picks, Alternates, Not Selected* — quick filters, each with a count.
  - *Suggestions ▸ Auto Suggest* — the frames Top Shelf would keep, kept apart from your own decisions. See [Auto Suggest](#auto-suggest) below.
  - *Dates* — each shooting day. Long archives are grouped by month; click a month to expand it.
  - *Moments* — runs of shooting close together in time. Right-click a moment to rename it ("Ceremony", "Golden hour"); the name follows your photos into your editor as a keyword.
  - *Focal Lengths* — filter by Ultra-Wide, Wide, Standard, Portrait, Telephoto, or Super-telephoto.
  - *Utilities* — Selection Story, Selection Coverage, and Recently Viewed.
  - At the bottom, your review progress with your Picks and Alternates.
- **Toolbar** — Home/Back, the **Grid | Bursts | Stacks** switch, grouping strength, Share (while a photo is selected), Copy, Search, and the Inspector button.
- **Title** — what you're looking at and how many photos. On the right: **Best of Each Burst** and **One at a Time**.
- **Inspector (right)** — camera, lens, exposure, file details, and quality notes for the current photo. Show or hide it with the button at the far right of the toolbar.
- **Home and Back** — on the grid, the house button returns to the home screen. Inside any photo view it becomes **Back**, which returns you to the grid.

**Three ways to see the shoot.**
- **Grid** — every photo, in moment sections. Pinch, or use ⌘+ and ⌘−, to make thumbnails bigger or smaller; ⌘0 returns to the standard size.
- **Bursts** — each group of similar shots laid out together as a contact strip, with how many you've kept from it.
- **Stacks** — one card per group, with its review status.

**Stacks.** Similar frames shot close together are grouped into a *stack* (shown with a "3 Similar" badge). Use the grouping menu to choose:
- **Tight** — only near-identical frames stack together.
- **Balanced** — the default.
- **Broad** — more variation from the same scene stacks together.

If a stack mixes two different moments, open it and use **Photo ▸ Split Stack**, or merge neighbouring stacks with **Merge with Previous/Next Stack**. **Mark Visually Distinct** takes a frame out of its stack.

### Auto Suggest

Choose **Auto Suggest** under *Suggestions* in the sidebar, or **View ▸ Auto Suggest** (⇧⌘A), to see which frames Top Shelf would keep. Choose **All Photos** to go back. **Nothing is marked**: the photos you've already picked appear beside the suggestions, and every other photo stays as it was.

- **Bursts.** The strongest frame is suggested: the subject is sharpest, the eyes are open, and the highlights aren't blown. A long burst can get two or three suggestions, but only when the extra frames are nearly as good and look clearly different, such as a different wing position.
- **Single shots.** Suggested when they're sharp, the eyes are open, and the highlights are mostly intact.
- **Close call.** The burst's best frames score almost the same, so it's worth a look yourself. Hover over any badge to see why that frame was chosen.
- **Your decisions come first.** Photos you've marked are never suggested. If you pick one suggestion in a burst, the others stay as long as they still look different from it.

When you're happy, click **Mark All as Pick**. It marks every suggestion shown as a Pick and leaves your other decisions alone. **Edit ▸ Undo** (⌘Z) reverses it in one step. Search narrows what's shown, and **Mark All as Pick** changes only what you can see. Auto Suggest works with Grid, Bursts, and Stacks.

Auto Suggest uses the on-device quality checks, so suggestions appear as analysis finishes. If **Settings ▸ General ▸ Show technical observations** was off when you opened the review, turn it on and reopen the review.

**First-time tour.** The first time you open each review mode, a short explainer shows what it does. You can replay the full tour any time with **Help ▸ Review Modes Tour**.

## 4. Making decisions

Every photo is in one of four states:

| State | Key | Meaning |
| --- | --- | --- |
| **Pick** | P | A keeper. |
| **Alternate** | A | A good backup or second choice. |
| **Not Selected** | X | Not keeping this one. *Nothing is deleted.* |
| **Undecided** | U | Not reviewed yet. |

You can also give stars with **1–5**. Select several photos to decide them all at once: **⌘-click** adds or removes one photo, **Shift-click** selects everything between. **⌘Z** undoes anything.

**Quality hints.** Top Shelf looks at sharpness (especially of the subject), clipped highlights, faces, and closed eyes. It may suggest the best frame in a stack and say why. These are only hints — Top Shelf never rejects a photo on its own.

## 5. Best of Each Burst

The fastest way through bursts: one decision per group of near-identical shots. Press **T**, or click **Best of Each Burst** at the top right. Click **Done** to go back to the grid.

Top Shelf shows each burst one at a time — only burst photos are shown (the header says so); single photos stay in the grid and One at a Time. The suggested frame is large; the burst's frames sit underneath in the order they were shot, with how sharp each one is and badges **1–4** on the best-ranked frames. **Frame 3 of 7** under the photo shows where you are in the burst.

- **S** or **Return** — Accept: this frame becomes the Pick, the burst's undecided frames become Not Selected, and you move to the next burst. Frames you already marked as a Pick or Alternate stay kept.
- **1–4** — look at a different frame from the strip instead.
- **→ / ←** — next / previous frame in the burst (or click the arrows beside *Frame 3 of 7*). Hold the key to scrub through the burst like video.
- **A** — mark this frame as an Alternate (keeps the burst open, for bursts worth two keepers).
- **X** — Reject the whole burst.
- **U** — Reset the burst to undecided.
- **↓** or **Next Burst** — move on to the next burst without deciding; **↑** goes back one.
- **Space** — Fit ↔ 100%. Zoom stays put as you move between frames of the same burst, so you can compare focus on the same spot.
- **Esc** — back to the grid.

Each burst decision is one undo step. When every burst is decided you'll get a summary and a shortcut to copy your Picks.

### Tips for high-speed bursts

Top Shelf is built for high frame-rate cameras — stacked-sensor bodies shooting 20 to 120 frames per second, and pre-capture modes (often called pre-burst, Pro Capture, Pre-Shot, or Pre-Release Capture) that save frames from just before you pressed the shutter.

- **Pick the right grouping.** At very high frame rates, **Tight** keeps each burst to near-identical frames, so a long sequence splits into separate moments of action. **Balanced** suits most sports and wildlife. Use **Broad** if a burst was split where you didn't want it.
- **Best of Each Burst first, One at a Time second.** Choose one frame from every burst, then use One at a Time with the **Unreviewed** filter to sweep up the single frames in between.
- **Scrub, then zoom.** Hold **→** to flip through a burst until the action peaks — the wing at full extension, the ball on the bat. Then press **Space** to check focus at 100% before accepting.
- **Pre-capture frames are ordinary frames.** They land in the same stack as the rest of the burst, so Top Shelf ranks them like any other frame. The decisive moment often sits in the pre-capture part.
- **Trust, but check, the suggestion.** Suggestions weigh subject sharpness, closed eyes, and clipped highlights. They can't judge the peak of action or your composition — that's still your call.
- **Shooting to two cards?** Cull the first card, then open the second; Top Shelf offers to carry your decisions over (see [Two-card shoots](#10-two-card-shoots)).

## 6. One at a Time

One photo at a time, full screen, one key each. Press **S**, or click **One at a Time** at the top right. Click **Done** to go back to the grid.

- **P** pick, **A** alternate, **X** not selected, **U** undecided — decides and jumps to the next photo.
- **← / →** move without deciding. The filmstrip below shows where you are; click any frame to jump to it.
- **Space** toggles Fit and 100%.
- **Esc** returns to the grid on the photo you reached.

One at a Time goes through whatever the grid is showing when you start — so you can, for example, filter to **Unreviewed** and cull only what's left.

## 7. Looking closely

**Stack Review.** Double-click a photo (or press Return) to see it large. The strip below shows every photo; each burst's frames share a shaded group labelled *Burst · 7*, and the current burst is highlighted. **← / →** go through every photo — through a burst and on to the photos after it. **↑ / ↓** jump to the previous / next burst or single photo.

**Zoom.** Real 100% means one pixel of your photo per pixel of your screen.
- **Space** — toggle Fit / 100%
- **⌘-scroll** or **pinch** — zoom around the pointer
- **Double-tap with two fingers** (trackpad) or **double-click** — toggle Fit / 100% at that spot
- **⌘+ / ⌘−** zoom in/out, **⌘0** fit, **⌘1** 100%
- Drag to move around when zoomed.

Top Shelf shows a quick preview first and loads full resolution in the background — a small status note shows while it's working. At 100% you'll feel a light tap on a Force Touch trackpad.

**Swipe.** At Fit, swipe left or right with two fingers to move to the next or previous photo.

**Rotate.** **⌘R** and **⌘L** (Photo ▸ Rotate Clockwise / Counterclockwise) turn how a photo is shown during review — handy for frames your camera didn't mark as portrait. Only the view changes: your originals and copies are not rotated or rewritten.

**Compare.** Press **C** to put photos side by side with zoom and position kept in sync. **←/→** swaps the candidate in the active pane; P/A/X/U decide the active photo.

**Selection Story** (sidebar ▸ Utilities) lays out your current Picks as a sequence so you can judge the set as a whole. **Selection Coverage** shows how many keepers each moment has, so you don't miss a part of the day.

## 8. Copying your keepers

Click the **Copy** button in the toolbar, or use the **File** menu:

- **Copy Selected…** (⌘E) — your Picks.
- **Copy Selected and Alternates…** (⇧⌘E) — Picks in a *Selects* folder, Alternates in an *Alternates* folder.
- **Copy Current Photo…** — just the photo you're on, with all its files.
- **Copy All Photos…** — the whole card, keeping its folder structure (handy for a full backup).

You'll see a summary before anything is copied: how many photos and files, how much space, and where they're going. Then:

- RAW + JPEG pairs and XMP sidecars are copied together.
- Every copied file is **verified** against the original (SHA-256). Only verified files count as done.
- If a file with the same name already exists at the destination, Top Shelf follows your setting. The default skips files that are identical and keeps both when they differ. You can also choose *Skip*, *Keep Both*, or *Replace* (Replace always asks you to confirm first).
- **Pause, resume, or cancel** at any time. If your Mac sleeps, a cable is pulled, or the app quits, the copy can be resumed later — from the copy sheet or the home screen — without re-copying finished files.
- **Work elsewhere while it runs.** The Dock icon shows the copy's progress. If you've switched to another app when it finishes, Top Shelf posts a notification and bounces its Dock icon; files that couldn't be copied leave a count on the icon. (macOS asks once, at your first copy, whether Top Shelf may show notifications.)

When the copy finishes you'll see a checklist confirming the result. Beside your photos you'll also find:
- **XMP sidecars** for RAW files with your ratings and keywords,
- **TopShelf Manifest.json** — used by the Lightroom plug-in,
- **Cull Receipt.txt** — a short readable summary of the cull (how many kept, per moment, gear used).

**What about the photos I didn't keep?** Top Shelf never deletes anything. If you want to clear rejects from a card or folder yourself, choose **Photo ▸ Show Not Selected in Finder** — Finder opens with those files selected, and what you do next is up to you.

## 9. Sending to your editor and other apps

Ratings travel with your copies: **Picks = ★★★★★, Alternates = ★★★** (or the stars you set yourself), plus the shoot and moment names as keywords.

- **Lightroom Classic** — install the plug-in once (**File ▸ Install Lightroom Plug-in…**, then restart Lightroom). After a copy, in Lightroom choose **Library ▸ Plug-in Extras ▸ Import Top Shelf Shoot…** and pick the *TopShelf Manifest.json* in your export folder. You get a *Top Shelf ▸ [Shoot]* collection set with **Picks** and **Alternates** collections, ratings, and keywords. Photos already in your catalog are not duplicated.
- **Capture One** — after a copy, click **Import into Capture One** with a catalog open. The first time, macOS asks whether Top Shelf may control Capture One; click OK.
- **Photomator, Lightroom, and others** — click **Send to Editor** after a copy and choose your app. Ratings and keywords come in through the XMP sidecars.

**Quick hand-offs while you review.** Other apps always receive a private copy of the photo, never the file on your card, so nothing they do can change your original.
- **Drag** photos from the grid into Finder, Mail, Messages, or an editor.
- **⌘C** (Edit ▸ Copy) puts the selected photos on the clipboard as files; paste them into Finder or another app.
- **Photo ▸ Open a Copy With** (also on the right-click menu) opens the photo in any app that can read it. Edits you save there land on that copy.
- **Share** (toolbar) sends the current photo with AirDrop, Messages, Add to Photos, and so on.

## 10. Two-card shoots

If your camera writes to two cards at once, cull one card as usual. When you open the second card, Top Shelf recognizes the same frames and offers to **Carry Over** your decisions. One click applies them; **⌘Z** undoes it. Top Shelf only offers this on a card you haven't started deciding yet.

## 11. iCloud Drive folders

If your photos live in iCloud Drive, macOS may keep some of them only in the cloud to save space. Top Shelf marks those with a cloud badge and won't download them behind your back.

- To bring them onto your Mac: right-click ▸ **Download from iCloud** (works on a selection), or use the button in the Inspector.
- Before copying, Top Shelf warns you if any chosen photos are still only in iCloud.

## 12. Keyboard shortcuts

**Deciding (grid, stack review, compare)**

| Key | Action |
| --- | --- |
| P | Pick |
| A | Alternate |
| X | Not Selected |
| U | Undecided |
| 1–5 | Star rating |
| ⌘Z / ⇧⌘Z | Undo / Redo |

**Moving around**

| Key | Action |
| --- | --- |
| ← → | Previous / next photo |
| ↑ ↓ | Previous / next burst |
| Return | Open the photo large |
| Esc | Back |
| G | Grid |
| T | Best of Each Burst |
| S | One at a Time |
| C | Compare |
| ⇧⌘A | Auto Suggest |

**Viewing**

| Key | Action |
| --- | --- |
| Space | Fit ↔ 100% |
| ⌘+ / ⌘− | Zoom in / out (in the grid: bigger / smaller thumbnails) |
| ⌘0 | Fit (in the grid: standard thumbnail size) |
| ⌘1 | 100% |
| ⌘R / ⌘L | Rotate the view clockwise / counterclockwise |

**Files and help**

| Key | Action |
| --- | --- |
| ⌘O | Choose a folder to review |
| ⌘C | Copy the selected photos to the clipboard |
| ⌘E | Copy Picks |
| ⇧⌘E | Copy Picks and Alternates |
| ⇧⌘W | Close the review |
| ⌘, | Settings |
| ⌘? | Top Shelf Help |

Best of Each Burst and One at a Time have their own keys — see [Best of Each Burst](#5-best-of-each-burst) and [One at a Time](#6-one-at-a-time).

## 13. Settings

Open **Top Shelf ▸ Settings…** (⌘,). There are four tabs:

- **General** — show the inspector by default, check for updates automatically (or **Check Now**), show quality hints (changes to background analysis apply when you reopen a review), and the default grouping strength for new reviews. Your work is saved automatically when you close a review or quit.
- **Copying** — include XMP sidecars, include videos in Copy All, what to do when a file already exists, and your preferred editor for **Send to Editor**. Verification is always on.
- **Cache** — change or clear the High-Resolution Cache, change the Default Export Folder, set the preview cache's maximum size or clear it, and remove old saved reviews.
- **Privacy** — a summary of what stays on your Mac, the sources Top Shelf remembers, and the full privacy policy.

Clearing caches never touches your photos — only Top Shelf's own working files.

## 14. Updates

Top Shelf can look for new versions on its own. The first time, it asks whether you'd like that; you can change your answer in **Settings ▸ General ▸ Updates**. To check right now, choose **Top Shelf ▸ Check for Updates…**.

When an update is available you'll see what's new and choose whether to install it. Nothing is downloaded or installed until you say so. Every update is signed by the developer, and Top Shelf checks that signature before installing anything. Your reviews, decisions, and settings are kept.

**Help ▸ Release Notes** lists every version on the releases page.

## 15. Troubleshooting

**My card doesn't appear.** Make sure it's mounted in Finder. If it is, use **Choose Folder to Review…** and select the card.

**Top Shelf asks to "reconnect" a saved review.** It's making sure it's the same card. Insert it (or choose the same folder) and confirm access. If the card's contents changed since last time, Top Shelf starts a new review instead of guessing.

**A photo says "Full-resolution preview unavailable".** The file may be in iCloud only, from a camera that hasn't finished transferring, or a RAW format your macOS version can't decode yet. Updating macOS adds newer camera RAW support.

**A copy failed or stopped.** Open the copy sheet (or the home screen's *Interrupted Copies*) and click **Resume** or **Retry Failed Files**. Finished, verified files are never copied twice. If a file changed on the card since the copy was planned, Top Shelf refuses to copy the changed version — rerun the copy to pick it up.

**A copy refuses a destination folder that is an alias or symbolic link.** For safety, Top Shelf only writes into real folders. Replace the link with a normal folder (or choose the folder it points to directly) and copy again.

**I don't get a notification when a copy finishes.** Notifications appear only when Top Shelf isn't the app in front. Check **System Settings ▸ Notifications ▸ Top Shelf**.

**Capture One import doesn't work.** Open a catalog or session in Capture One first. If you previously clicked *Don't Allow*, enable Top Shelf under **System Settings ▸ Privacy & Security ▸ Automation**.

**The Lightroom plug-in menu is missing.** Restart Lightroom Classic, then check **File ▸ Plug-in Manager** that *Top Shelf Bridge* is enabled.

**I'm running low on disk space.** Clear the High-Resolution Cache in Settings. It's only working copies.

**Something else is wrong.** Choose **Help ▸ Report an Issue…**. Please include your macOS version, the Top Shelf version (**Top Shelf ▸ About Top Shelf**), your camera model, and the steps that led to the problem. Issues are public, so don't attach photos you wouldn't want others to see.

## 16. Privacy

- Everything happens on your Mac. Top Shelf has no account and sends no analytics.
- Photo analysis uses Apple's on-device frameworks; your photos are never uploaded.
- The Top Shelf app itself has no access to the internet. Update checks happen in a separate, sandboxed helper — automatically only if you agreed when asked, or when you choose **Check for Updates…** — and send nothing about you or your photos.
- Every update is signed by the developer and verified before it installs.
- Top Shelf is sandboxed: it can read only the cards and folders you choose, and write only to destinations you choose.

The complete [privacy policy](PRIVACY.md) lists everything Top Shelf stores on your Mac and how to remove it. It's also in the app under **Help ▸ Privacy Policy**.

Top Shelf uses [Sparkle](https://sparkle-project.org) for updates, under its MIT license. The license is in the app under **Help ▸ Acknowledgements**.
