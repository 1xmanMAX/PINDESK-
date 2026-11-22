# PinDesk Privacy Policy

[← Back to the English overview](README.md) · [Español](../docs/privacidad.md)

This policy explains what data the **PinDesk** app (for Windows, Android, Mac and iPad, including
**PinDesk Templates** / *PinDesk Plantillas*) handles, why, and what you can do about it. It covers
every edition, including the Google Play one. The Spanish version is the reference text; if the two
differ, the Spanish one prevails.

Effective date: November 7, 2026. Last updated: November 22, 2026.

> **In short**
>
> - What you create in PinDesk is stored **on your device**.
> - To use PinDesk you **sign in with Google or with your email** (we send you a 6-digit code). We
>   store your email and, if you sign in with Google, your name and photo: only for your account,
>   your plan and your quota.
> - You can **delete your account** at any time: in the app (**Account › Delete my account**) or at
>   **https://api.mairumax.me/borrar-cuenta?lang=en**.
> - **Payments are processed by Google Play** (or the payment provider you choose outside Play). We
>   never see or store your card details.
> - What you ask the **AI** goes through our server to the AI provider, or straight to the provider
>   if you use your own key. **We do not store it.**
> - **No ads, no analytics, no crash reports, no tracking.** We do not sell data.
> - **Wi‑Fi** sync goes encrypted directly between your devices, without going through the
>   internet.
> - Speech-to-text and reading text in images run **on your device**, except the cloud voice
>   features explained in section 5.

Contents: [1 Controller](#1-who-is-responsible) · [2 Your account](#2-your-account) ·
[3 On your device](#3-data-kept-on-your-device) ·
[4 What leaves](#4-data-that-leaves-your-device) ·
[5 Voice](#5-speech-to-text-and-reading-aloud) · [6 Payments](#6-payments) ·
[7 Sync and backups](#7-sync-trash-and-backups) · [8 What we don't do](#8-what-we-dont-do) ·
[9 Retention and deletion](#9-retention-and-deletion) ·
[10 Permissions](#10-permissions-and-foreground-services) · [11 Security](#11-security) ·
[12 Audience and children](#12-intended-audience-and-children) · [13 Rights](#13-your-rights) ·
[14 Transfers](#14-international-transfers) · [15 Changes](#15-changes-to-this-policy) ·
[16 Contact](#16-contact)

## 1. Who is responsible

PinDesk is developed by **Max Anthony Mamani Maquera**, an independent developer based in Peru
("we"). He is the controller of the data stored on the PinDesk server (`api.mairumax.me`), described
in sections 2, 4, 5 and 6. For any privacy matter, write to **max.antony.8.5.1@gmail.com**.

## 2. Your account

You need to **sign in with an account** to use PinDesk. There are two ways:

- **With Google**: you pick one of the Google accounts on your device. Google confirms your
  **email**, your **name**, your **profile photo** and an identifier of your Google account, which
  we only keep as a hash (a one-way digest).
- **With your email**: you type your email and we send you a **6-digit code** that is valid for 10
  minutes and only once. Of the code we only keep an encrypted hash while it is valid, and how many
  times it was requested and failed (to stop abuse). This way we store no name or photo.

On our server we keep, for your account: your email, name and photo (if you signed in with Google),
how you sign in (Google, email or both), when you created it and last used it, your plan (Free, the
Pro trial or Pro) and until when, any account settings we make by hand (for example, gifted Pro or a
usage limit), and how much of the daily **quota** of AI features you use (only how many times,
never what you asked).

We use them to:

- know which **plan** you have and link what you buy to your account, on all your devices;
- give you the **AI assistant without entering any key**, with its daily quota;
- **reply to you** if you contact us about your account or a payment.

The app checks with our server from time to time to confirm your account and licence (which is
signed so nobody can forge it). Nothing you create is sent in that check. Your session is stored on
your device, outside the backup.

**Signing in with Google does not give us access to your Drive, Calendar or email.** On Windows,
that only happens if you connect those services to the assistant yourself (section 4), and it is
asked for separately.

Legal basis: performance of the contract you accept by using PinDesk (the [Terms](terms.md)).

## 3. Data kept on your device

PinDesk stores in its data folder (on Windows, `%APPDATA%\PinDesk`, or next to the program in the
portable version; on Android, Mac and iPad, in the app's private storage) what you create or bring
into it:

- Chats, messages, notes, tasks, timetables, reminders, lessons, templates, drawings and documents.
- Screenshots, pins, sketches, photos, videos, voice notes and class or meeting recordings.
- Transcripts, topics and notes from a meeting, and their finished summaries.
- The words you teach dictation, and your settings.
- The **trash** (what you delete stays there for 30 days) and the **project copies** the app makes
  by itself before receiving or syncing something over a project, so you can go back.
- Your **session** and any **API keys** you paste (for example Anthropic, DeepSeek, Soniox,
  TypeSafe or Brave Search): keys are stored **encrypted** with the system's protections (on
  Android, with a key in the phone's keystore; on Windows, with your Windows user), never in the
  settings file and never in the backup.
- Reports you make about AI responses (section 4).

And these things happen **on your device, without sending anything**:

- Text recognition in images (OCR) and reading PDF, Word, Excel and drawings.
- Transcribing recordings with the models that run on the device (section 5).
- **Your location**: on Android, your position is only used when you tap "My position" on a
  georeferenced drawing, to place you on it. It is not stored on any server or sent to anyone. If
  you tap "View on map", OpenStreetMap opens in your browser with those coordinates.
- **Android widgets** (Today, tasks, lists, gallery, recent files, quick actions and class) read your
  data on the device and show it on the home screen. They send nothing, but anyone who sees your
  screen will see what they show: remove them if you don't want that.
- **Send to Anki** writes the cards into AnkiDroid, on your phone.

We have no access to this data unless it leaves your device through one of the ways in sections 4,
5 and 7.

## 4. Data that leaves your device

Besides sections 2, 5, 6 and 7, something leaves your device **only when you use a feature that
needs it**. Everything travels over an encrypted connection (HTTPS/TLS), and each third-party
service handles data under its own privacy policy. On Android, **Settings › Privacy and data**
summarises this list; on Windows, **Settings → General → Privacy and data** shows it with a button
to where each feature is turned on or off. Depending on your plan, some features are **Pro**.

| Feature | What is sent | To whom |
|---|---|---|
| **AI assistant**, **Templates with AI**, **the AI call** and the **documents** (Excel, Word, PowerPoint, PDF) the assistant makes | What you write or say (already turned into text), the recent conversation and what you attach (a photo, a screenshot, a document). | Without your own key: **our server**, which forwards it to **Anthropic** (Claude) and counts your quota. With your own key: straight to **Anthropic** or **DeepSeek**, without going through us. |
| **Summaries of and questions about a recorded class or meeting** | The transcript text and your question (never the audio). | Our server, which forwards it to Anthropic. |
| **Jev** (task urgency and meeting topics) | Text snippets (sentences already transcribed on your device, note lines, tasks) and, in some features, an image, to get a classification. **Never the audio.** | **TypeSafe**, only with your TypeSafe key and that feature turned on. |
| **Assistant web search** | Search terms and the addresses of the pages it reads. No cookies, no AI key and no account data. | **DuckDuckGo**, or **Brave Search** with your Brave key; and the pages read. It can be turned off in the assistant settings. |
| **Community gallery** | What you choose to publish (a mini app, a shape, a template, a canvas, a drawing…), with its title, description and your name as author; and your likes. | Our server. Other users can see and download what you publish; your email is never shown. |
| **Shapes and libraries from the server** | Only the download request. Nothing of yours. | Our server. |
| **Google connections** (Windows) | The Drive files you pick and the calendar events you ask for. | Google, only if you connect those services. Disconnect them in Settings → Assistant. |
| **Share by link** | The file you choose to share. | A public temporary file host (litterbox.catbox.moe or temp.sh). Anyone with the link can open it until it expires (hours to days). Do not use it for private things. |
| **Model, dictionary and tool downloads** | Only the download request (the server sees your IP address). Nothing of yours. | The sites that publish them: alphacephei.com (Vosk), Hugging Face and GitHub (Whisper, Qwen3-ASR, the voice detector, the dictionary), and cdn.jsdelivr.net (Python for the assistant, the first time it is used). |
| **Updates** (only editions outside Google Play) | Only the check for the latest version. | Our server and GitHub. The Google Play version is only updated through Google Play. |
| **Links and pages you open** | Handled by your browser or the program you choose. An HTML page you open in PinDesk may load images or code from the internet, as in a browser. | The destination site or program. |

**About AI requests.** When they go through our server, we only forward them to the provider and
return the answer: **we do not store their content** or use it for anything else. Of your usage we
only record how much of your daily quota you spend. Documents made by the assistant are kept in the
server's memory only until your device collects them, and are deleted from Anthropic as soon as they
are downloaded. The AI provider handles what it receives under its own terms: review them before
sending it sensitive information.

**AI-generated content.** Responses come from third-party models and may be inaccurate. You can
report an inappropriate response with **Report response…** (message menu › More, or the flag on the
response; on Android also in Settings › Privacy and data): pick a reason, it is saved on your device
and your email program opens with the report written, so you can send it to us if you wish. We only
receive what you choose to send.

## 5. Speech-to-text and reading aloud

PinDesk can turn your voice into text in several ways. **Most of them run on your device, offline**;
the ones that use the cloud are listed here, and none of them stores your audio on our server.

| Engine | Where it runs | What is sent and to whom |
|---|---|---|
| **Vosk**, **Whisper** and **Qwen3-ASR** (models you download once) | On your device. | Nothing (only the model download, section 4). |
| **The phone's speech recogniser** (Google's or whichever your phone has) | The system's speech service. | Depending on your phone and its settings, that service may work offline or send the audio to its provider (for example Google), which handles it under its own terms. |
| **Cloud voice for the AI call** (Whisper on Groq) | In the cloud, sentence by sentence. | The audio of each sentence you say during the call goes to **our server**, which transcribes it with **Groq** and returns the text. **We do not store the audio or the text.** Meanwhile Vosk also transcribes it on your device, in case the network fails. |
| **High-accuracy live voice** (Soniox) | In the cloud, while you speak. | With **your own Soniox key** (Settings › Agent), the audio goes **straight from your device to Soniox**, without going through our server; along with it go the words you taught dictation and a little context (for example, names of your files) so it understands better. If one day we provide it with the account, our server only gives you a temporary single-use key and the audio still goes straight to Soniox. It can be turned off in Settings › Agent. |

**Reading aloud.** The reader uses the **phone's voice** (offline). In editions outside Google Play,
and on Windows, you can also pick one of **Microsoft's online voices**: the text being read is then
sent to Microsoft to turn it into audio, and the returned audio is cached on your device so it is
not requested again. The Google Play version does not include Microsoft's voices.

## 6. Payments

**In the Google Play version**, PinDesk Pro (monthly, yearly or lifetime) is bought with **Google
Play Billing**: Google takes the payment and your payment details **are handled by Google, not by
us**. To give you Pro, the app sends us the **purchase receipt** (the purchase token and the
product) and our server **verifies it with Google** (the Google Play Developer API) before
activating it; Google also notifies us of renewals, cancellations and refunds. The purchase carries
an **encrypted** identifier of your PinDesk account (no personal data), so we know whose it is.
Subscriptions are cancelled in Google Play.

**Outside Google Play**, the payment is processed by a **payment provider** (for example Mercado
Pago or Lemon Squeezy, depending on the method you choose). Your payment details (card number,
payment account) **are received and handled by that provider, not by us**. **We do not store your
card details.**

For each purchase we keep only what is needed to activate your licence, support you and meet our
legal and accounting obligations: the account it belongs to and its email, the provider, the plan
bought, the amount and currency when the provider gives them to us, the dates, the status (active,
renewed, cancelled, expired or refunded) and the transaction ID.

Legal basis: performance of the purchase contract and compliance with legal obligations.

## 7. Sync, trash and backups

### Over Wi‑Fi (all plans)

Your devices find each other on the local network and pair with a code or a QR code. Everything that
travels is **encrypted** with a key only your devices know, directly from one to the other, **with
no intermediate servers on the internet**. The same applies when you use your phone as the PC's
camera. If you share a chat with someone, that person receives a copy on their device.

What you delete on one device is deleted on the others when they sync, and stays **30 days in the
trash** of each one, with the name of the device where it was deleted, in case you want it back.

### Through the cloud (shared chats)

A shared chat can also travel **through a cloud**: a server whose address and key you enter in
**Sync › Cloud** (for example, your work team's). The messages, files and changes of that chat are
then uploaded to **that server**, encrypted in transit, and the other people in the chat download
them from there. Your personal chats keep syncing only over the local network. Whoever runs that
server is responsible for what it stores; if we run it for you, we use that data **only to sync
it**: we do not look at it, analyse it or use it for anything else, unless you ask us for help with
a problem or a law or competent authority requires it.

### Backups

- **Android backup** (the one in your Google account, if you have it turned on) may include your
  PinDesk data, as with any app. It **does not include** your API keys, your session, your sync
  group code or the key to your shared chats: on a new phone you sign in and pair again. A direct
  transfer from one phone to another (cable or Wi‑Fi) does carry your shared chats, but not the
  device's identity.
- **The project copies** the app makes (section 3) stay on the device and do not travel.

Legal basis: performance of the contract (the service you ask for when you sync).

## 8. What we don't do

- No ads and no advertising identifiers.
- No analytics, remote crash reports or trackers. App logs stay on your device (in the AI call you
  can copy a technical report to send us, if you want).
- We do not sell, rent or give away personal data.
- We do not store what you ask the AI or the audio of your voice.
- We do not use your data to train AI models. (The AI providers you send data to have their own
  terms; review them.)

## 9. Retention and deletion

### Deleting your account

You can delete your account at any time, in two ways:

- **In the app**: **Account › Delete my account**, and type the word it asks for to confirm.
- **Without the app** (for example, if you already uninstalled it): at
  **[https://api.mairumax.me/borrar-cuenta?lang=en](https://api.mairumax.me/borrar-cuenta?lang=en)**
  enter your account email and we send you a link (valid for one hour) to confirm with a button.

Deleting it removes **for good** from our server: your account (email, name and photo), your licence
and Pro, your quotas, any pending email code and what you published in the community gallery. **Your
purchases are unlinked**: your account and email are removed from them, and only what accounting
law requires is kept (with no personal data). The subscription stays in Google Play (or wherever you
paid) and must be cancelled there. Only a record without personal data remains that an account was
deleted (when, how and how many purchases were unlinked). What is on your device is not touched: the
session is just closed.

The account Google Play reviewers use to test the app is the only one that cannot be deleted.

### Retention periods

- **On your device**, data is kept until you delete it. On Android, **Settings › Privacy and data ›
  Delete all my data** erases everything the app has on the phone (so does uninstalling it). On
  Windows, **Settings → General → Your data, on your disk** opens the data folder: copy it to take
  your data with you, or close PinDesk and delete it to remove everything. Uninstalling on Windows
  may leave that folder (so nothing is lost by accident); delete it by hand if you wish.
- **The trash** keeps deleted items for 30 days and then empties itself.
- **Your account** is kept until you delete it.
- **The email sign-in code** expires after 10 minutes and works only once.
- **The payment data** we keep (section 6) is kept for the time tax and accounting law requires,
  even if you delete your account (unlinked from it).
- **Backups on our server** are overwritten within up to 30 days.
- **What you sent to a third party** (sections 4 and 5) is governed by that service. Temporary links
  expire on their own.
- **Copies on your other devices**, or on the devices of people you shared a chat with, are deleted
  on those devices.

## 10. Permissions and foreground services

PinDesk asks for each permission **when you use the feature that needs it**, not at install time.

- **Microphone**: voice notes, dictation, the AI call and recording classes or meetings; only while
  you use them.
- **Camera**: photos, videos, scanning a QR code, the 3D sketch, the in-person meeting and using the
  phone as the PC's camera; only when you choose it.
- **Screen recording or capture**: only when you start it (a screenshot, a clip or a screen
  recording). Android asks for permission each time and shows that recording is on.
- **Location** (Android): only "My position" on a drawing, with the app open. Never in the
  background and it never leaves the phone.
- **Display over other apps** (Android): floating pins and the bubble.
- **Network and Wi‑Fi**: signing in, checking your licence, the features in sections 4 and 5 and
  sync (finding your devices on the local network).
- **Notifications, exact alarms and start with the system**: task, class and exam notices and
  reminders on time, also after the device restarts.
- **AnkiDroid**: only if you use "Send to Anki".

**Foreground services** (Android). When something has to keep going with the app off screen, Android
does it with a foreground service and shows **a notification for as long as it lasts**, from which
you can stop it: recording a class or a meeting (microphone, and camera for the in-person meeting),
recording the screen, the AI call, listening to a document read aloud, floating pins, transcribing a
recording or downloading a model, and syncing or sending your files to your devices. None of these
services sends anything to the internet on its own: they do what you started.

PinDesk does not read your contacts, your phone's calendar, your messages or your email.

## 11. Security

Your keys are stored encrypted on your device. Internet connections use HTTPS, Wi‑Fi sync is
encrypted between your devices and your licence is signed. On the server, the email sign-in code is
only kept as a hash, attempts are limited and access is restricted to what is essential. No system
is infallible: protect your device and your Google or email account with a password and, if you
can, two-step verification. If a security incident affects your data, we will tell you and notify
the authority where the law requires.

## 12. Intended audience and children

PinDesk is meant for **adults (18 or older)**: university students and professionals. It is not
directed to children and does not knowingly collect children's data. The AI features use
third-party services that require users to be adults (for example, Anthropic requires 18). If you
are a minor, do not use PinDesk without the permission and supervision of your parents or
guardians. If you believe a minor has given us data, write to us and we will delete their account.

## 13. Your rights

Depending on the law that applies to you (for example Peru's **Personal Data Protection Law
No. 29733** and its regulations, the EU **GDPR** or Spain's LOPDGDD), you have the right to
**access**, **rectify**, **cancel or erase** your data, **object** to its processing and, where
applicable, to **portability**. You control the data on your device directly. You can delete your
account yourself (section 9). For anything else about your account or payments, write to
**max.antony.8.5.1@gmail.com** from your account email; we will reply within the time limits set by
law.

You can also complain to your data protection authority: in Peru, the **National Authority for
Personal Data Protection** (Ministry of Justice and Human Rights); in Spain, the AEPD.

## 14. International transfers

Our server, Google, the payment providers and the AI and voice providers (Anthropic, Groq, Soniox
and, if you choose DeepSeek, DeepSeek) may be outside your country (for example in the United
States, the European Union or, with DeepSeek, China). When you use those features, your data may be
processed there. We choose providers that offer adequate protection safeguards.

## 15. Changes to this policy

If we change this policy, we will publish the new version at this same address with its date. If
the change is important, we will also announce it in the app before it applies.

## 16. Contact

**Max Anthony Mamani Maquera** · Email: **max.antony.8.5.1@gmail.com**

This policy can also be read at **https://api.mairumax.me/privacy** (in Spanish,
**https://api.mairumax.me/privacidad**).
