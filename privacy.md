---
layout: page
title: Privacy policy
permalink: /privacy/
updated: 2026-11-19
---

This policy covers the **The Pacer** app for Android and this website, thepacer.app. It describes the app as it is today.

## Who is responsible

Jörg Dietrich, Arndtstr. 10, 55124 Mainz, Germany, info@thepacer.app. See also the [Impressum]({{ '/impressum/' | relative_url }}).

## The app

### In short

The Pacer keeps your runs on your phone. It has no account, no analytics and no advertising. Data leaves your phone in only two ways, and each is your choice:

- **Share .fit file** sends one run's full record to an app you pick, such as Strava or Garmin Connect. It goes to that app, never to us.
- **Share my runs** sends us data about how each run was measured, and reports of what failed in the app. It never includes where you ran, when, your heart rate or who you are. It is off until you turn it on, and you can turn it off and have the data deleted at any time.

### What the app stores on your phone

| Data | Why | Kept until |
|---|---|---|
| Your sessions | So you can run them again | You delete them |
| Your runs: time, positions, distance, speed, cadence and, with a strap, heart rate | For the summary, the history and the comparison | You delete the run, or uninstall the app |
| The .fit file of each run | So you can share it | You delete the run, or uninstall the app |
| What the app learned about your stride | To set the beat for your pace | You reset it in Settings, or uninstall the app |
| Your settings: language, units, height if you gave it, your heart rate strap | To work the way you chose | You change them, or uninstall the app |

Your height is optional. The app uses it only to estimate your stride on your first session.

Heart rate counts as health data. The app records it only from a chest strap that you choose yourself, keeps it on your phone and uses it only for your summaries and your .fit files.

### Permissions

| Permission | What it is used for |
|---|---|
| Location | Distance and pace during a session. Location is read only while a session runs. |
| Notifications | The notification Android shows while a session runs, which keeps it alive with the screen off. |
| Nearby devices (Bluetooth) | Connecting to your heart rate strap. Asked only when you choose a strap. |
| Foreground service, wake lock | Keeping a session, its beat and its cues running while the phone is locked. |
| Internet | Sending measurement data and crash reports to us, only if you turned on *Share my runs*. |

The app reads the phone's motion sensors to measure your cadence. Android needs no permission for this. With *Share my runs* on, recordings of these readings are sent to us; otherwise they stay on your phone.

### Share .fit file

This sends a run to **another app, not to us**. **Share .fit file**, on a run's summary, hands the file to the app you choose in Android's share sheet: Strava, Garmin Connect, e-mail, a cloud drive and so on. The file contains your positions, times, distances, speeds and, with a strap, heart rate. We never receive it. Once sent, the file is handled under that service's privacy policy, not ours.

### Share my runs

This sends **measurement data to us**, so we can tune how the app measures pace and cadence on phones and runners beyond our own. It is separate from *Share .fit file*: it sends no .fit file, and none of your positions.

The app asks once, during setup, whether to turn on *Share my runs*, and Settings holds the same switch afterwards. Nothing is selected for you, and nothing is sent until you turn it on.

| Sent with each run | Never sent |
|---|---|
| Pace, distance and time, counted from the start of the run | Where you ran: no positions, no heading, no compass |
| GPS signal quality and your step cadence | The day and time you ran |
| The app's version, and your phone's maker, model, Android version and battery | Your heart rate |
| The week of each run | Your name, e-mail, or anything else that says who you are |
| Your height, if you gave it | |
| Motion-sensor recordings of each run | |
| Crash reports: what failed and where in the app, with any numbers in the message hidden | |

If a later version of the app sends more than this list, it asks for your consent again before it does.

**Your install ID.** What you send is grouped under a random ID that the app makes when you agree. It is not linked to your name, your Google account or your phone's identifiers, so the data is pseudonymous: we cannot tell who you are, but everything under one ID belongs together. Settings shows the ID and lets you copy it.

**When it is sent.** Each run you keep is sent once, when it ends, over any network. If the phone is offline then, it waits and goes the next time you open the app. A crash report is sent the same way, on the next launch if the app crashed. Motion-sensor recordings wait until the phone is on Wi-Fi and charging, are sent once, and are then deleted from the phone. An aborted run is not sent.

**Where it goes, and who sees it.** The data goes to a service we run on Cloudflare (Cloudflare, Inc., USA), which acts as our processor. It is stored in Cloudflare's EU data location, in an R2 bucket created in the EU jurisdiction. The request may be handled on its way by a Cloudflare server outside the EU, under Cloudflare's data processing agreement and the EU standard contractual clauses. Our service keeps no IP address and no log of your requests, and no one else receives the data.

**What the server can tell.** It files each upload under the week it arrived and records when it arrived, which is about when a run ended. That is the only time it learns.

**How long it is kept.** Everything is deleted automatically 12 months after it was sent.

**Legal basis.** Your consent (Art. 6(1)(a) GDPR). You can withdraw it at any time, without affecting what was sent before.

**Stopping and deleting.** Turn off *Share my runs* in Settings, and nothing more is sent: runs still waiting to go are dropped. You can choose there to delete everything already sent under your install ID, at once or later with *Delete what was sent*. If you are offline, the deletion goes out the next time the phone is online, and the app keeps your ID until it is done. If you have uninstalled the app, e-mail us your install ID and we delete everything under it. Keep the ID before you uninstall. Without it we cannot tell which data is yours, so it is deleted only after the 12 months. The [manual]({{ '/manual/deleting-your-data/' | relative_url }}) walks through each step.

### Other software on your phone

The spoken cues use your phone's own text-to-speech engine, usually Google's. The app passes it short phrases such as "Repetition 3 of 6". Downloading a voice is between you and the speech engine.

### Deleting your data

Delete a run in the history, or a session in the session list. Uninstalling the app deletes everything it stored on your phone. What *Share my runs* sent us is deleted as described under *Share my runs*, or 12 months after it was sent. A .fit file you sent to another app is deleted there.

## This website

thepacer.app is a static website. It sets no cookies and runs no analytics or tracking. It loads no fonts or scripts from other sites.

The site is hosted by GitHub Pages (GitHub, Inc., USA) and delivered through Cloudflare (Cloudflare, Inc., USA). To deliver a page, these providers process your IP address and technical details of your request, such as the browser and the time, and may keep them briefly in their logs for security and operation. Our legitimate interest in running a secure and reliable website is the legal basis (Art. 6(1)(f) GDPR). Both providers transfer data to the USA under the EU–US Data Privacy Framework. See the [GitHub privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) and the [Cloudflare privacy policy](https://www.cloudflare.com/privacypolicy/).

If you e-mail us, we use your address and your message only to answer you, and delete them when they are no longer needed.

## Your rights

Under the GDPR you have the right to access, correct and erase your personal data, to restrict or object to its processing, and to data portability. You may also complain to a data protection supervisory authority. Contact us at the address above.

## Changes

When the app or this website changes how it handles data, this page changes first, and the date at the top says when.
