---
layout: default
title: PK SMS privacy policy
description: What PK SMS stores, what it sends, and why.
permalink: /pk-sms/privacy/
---

# PK SMS privacy policy

<p class="meta">Effective 1 November 2026 · Android app <code>com.pktech.pksms</code> · Made by Pradeep Dev · <a href="mailto:pradeepdev001@gmail.com">pradeepdev001@gmail.com</a></p>

> **Your messages stay on your phone.** PK SMS has no account, no ads,
> no analytics and no server of its own. It never sends your messages, phone
> numbers or contacts to the developer or to anyone else.
>
> One thing can leave through Google's Firebase: crash reports, which contain no
> message content and which you can turn off.

PK SMS is an SMS app. It works only after you choose it as your
default SMS app, which you can undo at any time in Android's
**Settings › Apps › Default apps**.

## What the app stores on your phone

| What | Where | Why |
| ---- | ----- | --- |
| Your text and picture messages | Android's own message store, shared by every SMS app on the phone | To show, send, receive and delete messages |
| Which conversations you archived, moved to the Recycle Bin, starred, pinned, muted or moved to another tab | The app's private database: conversation numbers and times only, no message text and no phone numbers | To keep your organizing |
| Messages still being sent: which parts the network has confirmed | The app's private storage, until sending finishes | To report "Sent" only when every part was sent |
| Picture messages on their way: the file going to or coming from your operator | The app's private cache, deleted as soon as the transfer ends | Android's MMS service reads and writes it there |
| Your settings, including your quick replies | The app's private storage | To remember your choices |

**Sorting** into Personal, Transactions and Promotions happens on your phone, by
simple rules (business sender tags and words such as "OTP" or "offer"). It does
not use AI, and nothing is uploaded to do it.

**Contacts** are read from your phone's contacts, if you allow it, to show names
and photos and to attach a contact to a message. Names are kept only in memory,
for a few minutes, and are never saved or sent.

Uninstalling the app, or clearing its data, deletes everything in the app's
private storage. Your messages stay in Android's message store, for whichever SMS
app you use next, unless you delete them. Android backup is turned off for this
app.

## What leaves your phone

**The messages you send.** Like any SMS app, PK SMS hands the message
and the recipient's number to your mobile operator, which delivers it under its
own terms. Picture messages (MMS), sent and received, travel through your
operator's MMS service over mobile data; Android's own MMS service handles that
connection. PK SMS itself does not use the internet for messages.

**Crash reports (Firebase Crashlytics).** If the app crashes, it sends the
technical details: the error and where in the code it happened, your device
model, Android version, app version, and an installation identifier that
Crashlytics creates. Firebase also records when the app is opened, so that crash
rates can be worked out. The app never adds message text, phone numbers,
contact names or conversation details to these reports. This is **on by
default** and can be turned off in **Settings › Privacy › Send crash reports**.
It is the only reason the app holds the internet permission.

Firebase is run by Google, which processes this data on the app's behalf under
the [Firebase privacy and security terms](https://firebase.google.com/support/privacy).
Crash reports are encrypted in transit. Nothing is sold, and nothing is shared
with anyone else.

## When you choose to share

- **Translate** hands the message text to the translation app you pick, under
  that app's own privacy policy.
- **Share, Copy and Attach contact** pass only what you chose, to the app or field
  you chose. Copied one-time codes are marked sensitive, so Android hides them in
  its clipboard preview.
- **Attach picture** uses Android's photo picker, which gives the app only the
  pictures you choose. A picture is made smaller to fit your operator's limit and
  sent to the people in the conversation; a copy waits in the app's cache for a
  day if you do not send it.
- **Block** adds the number to Android's own block list, which your phone and its
  other apps also use.
- **Tell a friend** opens Android's share sheet with a short note about the app.

## Notifications

New messages are shown in notifications on your phone. On a locked screen they
show only "New message", without the sender or the text. Muted conversations do
not notify.

## Permissions

| Permission | Why |
| ---------- | --- |
| Receive, read and send SMS; receive MMS and WAP push | To work as your SMS app. Android grants these only when you choose the app as your default SMS app |
| Phone state | To list your SIM cards, so you can choose which one sends |
| Notifications | To tell you when a message arrives or fails to send |
| Contacts (optional) | To show names and photos instead of numbers, and to attach a contact. The app works without it |
| Internet, network state | Crash reports only |

## How long data is kept

- **Crash reports** are kept by Crashlytics for 90 days, then deleted automatically.
- **Everything on your phone** stays until you delete it in the app, clear the
  app's data, or uninstall it. Messages stay in Android's message store until you
  delete them.

To ask about, or ask for deletion of, crash reports from your installation, email
[pradeepdev001@gmail.com](mailto:pradeepdev001@gmail.com).

## Children

PK SMS is a general-purpose messaging app, not designed for children.
It collects no personal information from anyone.

## Changes

If what the app collects ever changes, this page will be updated first and the
date at the top changed.
