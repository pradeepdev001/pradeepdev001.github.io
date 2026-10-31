---
layout: default
title: PK Player privacy policy
description: What PK Player stores, what it sends, and why.
permalink: /pk-player/privacy/
---

# PK Player privacy policy

<p class="meta">Effective 31 October 2026 · Android app <code>com.pktech.pkplayer</code> · Made by Pradeep Dev · <a href="mailto:pradeepdev001@gmail.com">pradeepdev001@gmail.com</a></p>

> **Your media stays on your phone.** PK Player has no account, no ads and no
> analytics. Nothing about what you keep, play or organise — file names, folders,
> titles or what you watched — ever leaves your device.
>
> **Two things can leave**, both through Google's Firebase: crash reports, which you
> can turn off, and push-notification registration, which only happens if you turn
> notifications on.

## What the app stores on your phone

All of it is kept in the app's private storage, which other apps cannot read:

| What                                                      | Why                                     |
| --------------------------------------------------------- | --------------------------------------- |
| The folders you chose, and permission to read them        | To list your media                      |
| An index of the media in them: names, sizes, dates, paths | To show your library without rescanning |
| Playback positions, finished items and your last queue    | To resume where you left off            |
| Playlists and favourites                                  | You made them                           |
| Tags read from your audio files, and cover art            | To group music by album and artist      |
| Your settings                                             | To remember your choices                |

Removing a folder in the app removes it from the index and changes nothing on
disk. Uninstalling the app, or clearing its data, deletes all of the above. The
app never moves, renames, deletes, copies or uploads your files.

## What leaves your phone

**Crash reports (Firebase Crashlytics).** If the app crashes or hits an error it
can recover from, it sends the technical details: where in the code it happened,
your device model, your Android version, the app version, and an installation
identifier that Crashlytics creates. While crash reports are on, Firebase also
records when the app is opened, so that crash rates can be worked out. Reports
never include anything about your media. This is **on by default** and can be turned off in
**Settings › Privacy › Send crash reports**; the change takes effect immediately.

**Push notifications (Firebase Cloud Messaging).** Off on a fresh install. Only if
you turn on **Settings › Privacy › Notifications** and allow the system prompt
does your phone register with Google's messaging service and receive a token, an
identifier for this installation. While notifications are off, no token is
requested.

Both services are run by Google, which processes this data on the app's behalf
under the [Firebase privacy and security terms](https://firebase.google.com/support/privacy).
Data is encrypted in transit. Nothing is sold, and nothing is shared with anyone
else.

## Permissions

| Permission                          | Why                                                |
| ----------------------------------- | -------------------------------------------------- |
| Foreground service (media playback) | Keep music playing when the app is not on screen   |
| Wake lock                           | Keep playback going while the screen is off        |
| Notifications                       | Show a push notification, only if you allow them   |
| Internet                            | Crash reports and push messaging                   |
| Receive Firebase messages           | Deliver push notifications, only if you allow them |

PK Player asks for **no** storage, photo, video, audio, microphone, camera,
contacts or location permission. You give it access to one folder at a time
through Android's own folder picker, and it can read nothing else.

Saving a video frame as a picture (Android 10 and later) adds that one picture to
your gallery and needs no permission. The app cannot see anything else there.

## How long data is kept

- **Crash reports** are kept by Crashlytics for 90 days, then deleted automatically.
- **The messaging token** stops working when you turn notifications off, withdraw
  the permission, or uninstall the app.
- **Everything on your phone** stays until you remove a folder, clear the app's
  data, or uninstall it.

To ask about, or ask for deletion of, crash reports from your installation, email
[pradeepdev001@gmail.com](mailto:pradeepdev001@gmail.com).

## Children

PK Player is a general media player, not designed for children. It has no content
of its own and no way to communicate with anyone.

## Changes

If what the app collects ever changes, this page will be updated first and the
date at the top changed.
