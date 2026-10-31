---
layout: default
title: PK Downloader privacy policy
description: What PK Downloader stores, what it sends, and why.
permalink: /pk-downloader/privacy/
---

# PK Downloader privacy policy

<p class="meta">Effective 31 October 2026 · Android app <code>com.pktech.pkdownloadmanager</code> · Made by Pradeep Dev · <a href="mailto:pradeepdev001@gmail.com">pradeepdev001@gmail.com</a></p>

> **Your browsing and your downloads stay on your phone.** PK Downloader has no
> account, no ads, no analytics and no server of its own. It connects only to the
> websites you visit and the files you download.
>
> Two things can leave through Google's Firebase: crash reports, which you can
> turn off, and push-notification registration, which is off until you turn it on.

## What the app stores on your phone

Kept in the app's private storage, which other apps cannot read:

| What                                                                      | Why                                      |
| ------------------------------------------------------------------------- | ---------------------------------------- |
| Browsing history, bookmarks and open tabs                                 | The built-in browser                     |
| Website settings and the permissions you gave each website                | To remember your choices per site        |
| Your downloads: each file's link, the page it came from, and its location | The download list, resuming and retrying |
| Your settings                                                             | To remember your choices                 |

Downloaded files are saved to your phone's Downloads, or to a folder you choose
in Settings. Uninstalling the app, or clearing its data, deletes everything
above — but not the files you downloaded, which are yours. Android
backup is turned off for this app.

## What leaves your phone

**The websites and files you choose.** Your phone connects directly to the
websites you visit and the servers you download from. When you download from a
web page, the app sends what a browser would send so that the download works:
the browser's user-agent, the page you came from, and that website's cookies.

**Searches** typed in the address bar go to the search engine you pick (Google,
DuckDuckGo or Bing), under that company's privacy policy. Address-bar suggestions
come only from your own history and bookmarks.

**Ad-blocking filter lists.** If **Update filter lists** is on, the app downloads
the public EasyList filter lists from `easylist.to`. Nothing about you is sent.

**Crash reports (Firebase Crashlytics).** If the app crashes, it sends the
technical details: the error and where in the code it happened, your device
model, Android version, app version, and an installation identifier that
Crashlytics creates. Firebase also records when the app is opened, so that crash
rates can be worked out. The app does not add the addresses you visit or the
names of your files to these reports, although a technical error message could
occasionally contain one. This is **on by default** and can be turned off in
**Settings › Send crash reports**.

**Messages from the app (Firebase Cloud Messaging).** Off by default. Only if you
turn on **Settings › Messages from the app** does your phone register with
Google's messaging service and receive a token, an identifier for this
installation. Turning it off again deletes the token.

Firebase is run by Google, which processes this data on the app's behalf under
the [Firebase privacy and security terms](https://firebase.google.com/support/privacy).
Crash reports and messaging are encrypted in transit. Nothing is sold, and
nothing is shared with anyone else.

## Clipboard and sharing

The app checks whether your clipboard holds a link, so that it can offer to
download it, by looking only at the type of the clipboard's content. It reads the
text itself only when you tap to use it. You can also share links and files into
the app, and share downloads out through Android's share sheet.

## Permissions

| Permission                                                     | Why                                                      |
| -------------------------------------------------------------- | -------------------------------------------------------- |
| Internet, network state                                        | Browsing and downloading                                 |
| Foreground service (data sync), wake lock, user-initiated jobs | Keep downloads running when the app is not on screen     |
| Notifications                                                  | Show download progress, and messages if you turn them on |
| Camera, microphone                                             | Only when a website you visit asks, and you allow it     |
| Location (approximate and precise)                             | Only when a website you visit asks, and you allow it     |
| Receive Firebase messages                                      | Deliver messages, only if you turn them on               |

Camera, microphone and location are never used by the app itself. A website can
use them only after you allow it, for that website, while you are using it. You
can change these choices for each website in the app.

## How long data is kept

- **Crash reports** are kept by Crashlytics for 90 days, then deleted automatically.
- **The messaging token** is deleted when you turn messages off.
- **Everything on your phone** stays until you delete it in the app, clear the
  app's data, or uninstall it.

To ask about, or ask for deletion of, crash reports from your installation, email
[pradeepdev001@gmail.com](mailto:pradeepdev001@gmail.com).

## Children

PK Downloader is a general-purpose browser and download manager, not designed
for children.

## Changes

If what the app collects ever changes, this page will be updated first and the
date at the top changed.
