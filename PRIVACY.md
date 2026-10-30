# Top Shelf privacy

Last updated: October 29, 2026

Top Shelf is a photo culling app. It doesn't need to know who you are, and it doesn't try to find out. Your photographs are the most personal thing on your Mac, so Top Shelf is built to keep them there.

## The short version

- No account, sign-in, analytics, advertising, or tracking of any kind.
- Your photos are reviewed on your Mac. Top Shelf never uploads them, and all photo analysis happens on your Mac.
- Top Shelf never changes your original files.
- The Top Shelf app itself has no permission to use the internet. A separate, sandboxed helper checks for updates, and you decide whether that happens automatically.
- Nothing Top Shelf sends identifies you, your photos, or your Mac.

## Your photos and your originals

Top Shelf reads your memory cards, cameras, drives, and folders **read-only**. It never renames, moves, edits, tags, or deletes anything there. Star ratings and keywords are written only to the copies you make, in the destination you choose.

Top Shelf is sandboxed by macOS. It can read only the sources you choose to open and write only to the destinations you choose. It can't look around the rest of your Mac.

**Photo analysis stays on your Mac.** Sharpness, faces, closed eyes, and similar-photo grouping are computed with Apple's on-device frameworks. Nothing is sent to a server, ours or anyone else's.

**Location data.** Top Shelf never reads the location (GPS) information in your photos. Copies are exact byte-for-byte duplicates, though, so if your camera recorded a location, it stays inside the copied files, just as it was in the originals.

## When Top Shelf connects to the internet

### Checking for updates

Top Shelf uses [Sparkle](https://sparkle-project.org), the update framework many Mac apps rely on. Sparkle's sandboxed helper makes the connection. The Top Shelf app itself has no permission to make network connections at all, so it couldn't send your photos or data anywhere even by mistake.

A check happens only:

- when you choose **Top Shelf ▸ Check for Updates…** or **Check Now** in Settings, or
- about once a day, if you've turned on automatic checks. Top Shelf asks before the first one, and you can change your answer in **Settings ▸ General ▸ Updates**.

Each check downloads one small file that lists the available versions:

`https://raw.githubusercontent.com/tmanish/top-shelf-releases/main/appcast.xml`

The request includes the app's name and version and Sparkle's version, plus the routine details macOS adds to any web request, such as your preferred language. That's all.

It doesn't include your photos, file or folder names, camera details, settings, hardware details, a device identifier, or anything else that identifies you. Sparkle can optionally send a profile of your Mac's hardware and system. Top Shelf turns that option off.

Like any web server, GitHub sees the IP address a request comes from and handles it under the [GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement). We don't receive these requests or any log of them. GitHub shows us only a total download count for each release.

### Downloading an update

This happens only after you choose to install. The update comes from this repository's [Releases](https://github.com/tmanish/top-shelf-releases/releases) page on GitHub. Before installing, Sparkle checks that the update was signed by the developer, and it won't install anything whose signature doesn't match.

### Things you start yourself

These features hand your photos to another app or service, and only when you use them:

- **Share** sends private copies of the photos you choose to the service you pick (AirDrop, Messages, and so on), under that service's terms.
- **Send to Editor** and **Import into Capture One** open your copied photos in the editing app you choose. The first time you use the Capture One import, macOS asks whether Top Shelf may control Capture One.
- **Dragging** photos out of Top Shelf, **copying** them with ⌘C, and **Photo ▸ Open a Copy With** hand the receiving app a private copy of the photo, never the original on your card. What that app does with its copy is up to that app.
- The **Lightroom Classic plug-in** runs inside Lightroom on your Mac. It reads the manifest file Top Shelf saved next to your copies, and it makes no internet connections.
- **Help ▸ Release Notes** and **Help ▸ Report an Issue…** open this repository's pages in your web browser. The user guide, this privacy policy, and the acknowledgements are built into the app and open without a connection.

## Notifications

When a long copy finishes while you're working in another app, Top Shelf can show a notification such as "Copy Complete — 312 files copied and verified to Selects." macOS asks for your permission the first time you start a copy. Notifications are created on your Mac and shown by macOS; nothing is sent to a server. Turn them off any time in **System Settings ▸ Notifications ▸ Top Shelf**.

## What Top Shelf keeps on your Mac

Top Shelf's own data lives in its private folder, `~/Library/Containers/com.topshelf.TopShelf`. None of it is ever sent anywhere.

| What | Why | How long |
|---|---|---|
| Review sessions: the list of photos in each shoot (file names and locations, capture times, camera, lens, and exposure details), your Picks, Alternates, stars, moment names, view rotations, and quality notes | So you can close Top Shelf and pick up where you left off | Until you remove the session (Settings ▸ Cache ▸ Remove Old Sessions) |
| Similarity data: compact numeric summaries used to group similar photos | So grouping doesn't have to be recomputed every time | Removed with its session |
| Preview cache: small and medium-sized previews of your photos | Fast scrolling and instant review | Kept under the size you set in Settings; clear it anytime there |
| Copy progress records, including the source and destination locations | So an interrupted copy can resume without re-copying finished files | Removed when the copy completes or you discard it |
| Folder and card access you've granted, stored as macOS bookmarks; for connected cameras, the camera's serial number | So you aren't asked again, and so a review resumes on the same card or camera | Until you remove the session |
| Shared copies: private copies of photos you shared, dragged out, or copied with ⌘C | So the receiving app gets a copy instead of your original | Removed automatically after a day |
| Opened copies: private copies of photos you opened in another app with **Open a Copy With**, including any edits you saved to them there | So your saved edits remain available | No automatic expiry; use Photo ▸ Show Opened Copies in Finder to find or remove them yourself |
| Your settings, including your preferred editor, update preferences, and which introductions you've already seen | So Top Shelf works the way you set it up | Until you remove the folder |

**High-Resolution Cache.** You choose this folder on first launch. Top Shelf creates its own subfolder there for full-size working copies, used mainly when reviewing from a connected camera. It's yours to see and clear: **Settings ▸ Cache ▸ Clear High-Resolution Cache**. Top Shelf only ever removes its own subfolder.

Like the rest of your home folder, these files are included in your Mac's backups, such as Time Machine.

## What Top Shelf writes next to your copies

When you copy photos, Top Shelf can also save these files in the destination folder:

- **XMP sidecars** for RAW files, containing the star rating and keywords: the shoot name and moment names.
- **TopShelf Manifest.json**, used by the Lightroom Classic plug-in. It lists the copied file names, their Pick or Alternate state, rating, moment name, capture time, and camera model.
- **Cull Receipt.txt**, a readable summary of photo counts, moment names, and the camera and lens models used.

These files contain no personal information beyond what your photos and your own labels already hold. If you share an export folder with a client, they'll see these files too. Delete any of them you'd rather not share.

## Crash reports and diagnostics

Top Shelf has no crash reporter of its own and collects no usage statistics. Separately, macOS may send diagnostics to Apple, depending on **System Settings ▸ Privacy & Security ▸ Analytics & Improvements**.

## Removing your data

Quit Top Shelf, then delete `~/Library/Containers/com.topshelf.TopShelf`, and the High-Resolution Cache folder you chose, if you'd like that gone too. Your original photos and the copies you made aren't in either place. They stay where they are.

## Changes

If any of this changes, this page and the release notes will say so before the release that makes the change.

Questions? [Open an issue](https://github.com/tmanish/top-shelf-releases/issues).
