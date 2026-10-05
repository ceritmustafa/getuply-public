# GetUply Help Center

Everything GetUply does, and how to make it work for you.

GetUply is an alarm clock that asks you to *prove* you're up. Instead of a snooze
button next to your pillow, it gives you a short **wake mission** — scan a code in
the kitchen, take a photo of your coffee machine, walk twenty steps, say a phrase
out loud — and the alarm stops when the mission is done.

Everything described here runs **on your iPhone**. There is no GetUply account and
no GetUply server.

---

## Contents

- [Getting started](#getting-started)
- [Creating and editing alarms](#creating-and-editing-alarms)
- [Wake missions](#wake-missions)
  - [Classic](#classic) · [QR code](#qr-code) · [Math](#math) · [Photo](#photo) ·
    [Steps](#steps) · [NFC](#nfc) · [Typing](#typing) · [Memory](#memory) ·
    [Barcode](#barcode) · [Voice](#voice) · [Shake](#shake) · [Random](#random)
  - [Stacking missions](#stacking-missions)
  - [Photo variants](#photo-variants-sky-bed-pills-pet-nature)
  - [Push-ups and squats](#push-ups-and-squats)
- [The ringing screen](#the-ringing-screen)
- [Snooze, strict mode and emergency stop](#snooze-strict-mode-and-emergency-stop)
- [Sounds](#sounds)
- [Wake screens, themes and backdrops](#wake-screens-themes-and-backdrops)
- [Sleep, bedtime and wind-down](#sleep-bedtime-and-wind-down)
- [App Block](#app-block)
- [Insights, streaks and badges](#insights-streaks-and-badges)
- [Settings reference](#settings-reference)
- [Permissions](#permissions)
- [Languages](#languages)
- [GetUply Pro](#getuply-pro)
- [Privacy](#privacy)
- [Troubleshooting](#troubleshooting)
- [Contact](#contact)

---

## Getting started

The first run walks you through the app in a few steps:

1. **What GetUply does** — three short pages explaining missions.
2. **Your wake time** — pick a time, or tap one of the quick choices.
3. **Your first mission** — choose how you want to be made to get up.
4. **Permissions** — each explanation has one **Continue** button that opens
   the iOS request. Choose allow or deny in the system dialog; either decision
   lets setup continue. Notifications support reminders and backup alerts;
   AlarmKit has a separate permission for native Lock Screen alarms. Camera,
   Motion & Fitness, Microphone/Speech and Screen Time serve their named features.
5. **A practice run** — a real mission, right then, with no alarm attached, so the
   first time you do one isn't at 6 a.m.

You can skip the practice run, and you can change every choice later in Settings.

---

## Creating and editing alarms

Tap **+** on the Alarms tab. An alarm holds:

| Setting | What it does |
|---|---|
| **Time** | When it rings. |
| **Repeat** | Which weekdays. No days selected = rings once, then switches itself off. |
| **Label** | Shown on the ringing screen. |
| **Mission** | What you must do to dismiss it. See [Wake missions](#wake-missions). |
| **Sound** | The alarm tone, from the built-in library. |
| **Snooze** | On/off, length in minutes, and how many snoozes are allowed. |
| **Wake theme** | The look and copy of the ringing screen. |
| **Strict mode override** | Forces strict mode on or off for this one alarm, regardless of the global setting. |
| **Flash override** | Forces the torch strobe on or off for this one alarm. |

Swipe an alarm left to delete it. Toggle the switch to disable one without losing
its settings.

**System alarm.** With **Settings › Alarm behavior › System alarm** on, GetUply
registers your alarm with Apple's own alarm system (AlarmKit). That is what makes
it ring on the Lock Screen while the app is closed, with the reliability of the
built-in Clock app. Tapping **Open mission** on that alert brings you into
GetUply's mission screen. With the setting off, GetUply falls back to
notifications, which depend on your notification permissions, sound settings and
Focus.

---

## Wake missions

A mission is the thing standing between you and silence. Pick the one that
actually gets *you* out of bed — for most people that means one that cannot be
done from under the duvet.

### Classic

No mission. One tap stops the alarm, exactly like a normal clock. This is the
mission free accounts get, and it's a perfectly reasonable choice if you just want
GetUply's sounds and wake screens.

### QR code

GetUply generates a code for your alarm. Print it or screenshot it, then put it
somewhere you have to *walk to*: the bathroom mirror, the kettle, the front door.
In the morning you scan it to dismiss the alarm.

- The code is specific to your alarm. Scanning a random QR code from a cereal box
  will not dismiss it.
- Keep a spare copy somewhere. If you lose the code, open the alarm and generate a
  new one.

### Math

Answer a few arithmetic questions. Three difficulties:

- **Easy** — single and double-digit addition, subtraction, small multiplication.
- **Medium** — two-digit addition and subtraction, larger multiplication.
- **Hard** — combined operations like `7 × 8 + 23` and `84 ÷ 7 + 19`.

Every question must be right. A wrong answer asks again; nothing is skipped.

### Photo

Two ways to use it.

**Preset objects.** Choose household objects — fridge, TV, coffee machine, washing
machine, microwave, oven, sink, toilet, laptop and more, grouped by room. At
wake-up, point the camera at one and GetUply recognizes it with Apple's on-device
image classifier. Because it recognizes the *kind* of object, angle and distance
don't matter much.

- Pick two or more objects and you can require **two different** objects to be
  scanned in one session.
- With one object selected, turn on **Vary the object daily** to be asked for a
  different one of your chosen objects each day.

**Your own reference photo.** Capture a photo of something specific — your
particular coffee machine, a poster, a plant. In the morning you re-photograph it
and GetUply compares the two on-device by visual similarity.

Tips for the custom photo:

- Frame the object the way you will in the morning: same rough distance, object
  filling a good part of the frame.
- Avoid photographing a mostly-empty wall or a flat surface. There has to be
  something distinctive to match.
- Good light at set-up time and at wake-up time. A pitch-dark kitchen at 6 a.m. is
  a different picture from a sunny one at 3 p.m.
- If the match keeps failing, re-take the reference photo (Alarm › Photo mission ›
  **Retake**). The screen tells you whether you were close or completely off.

Photos are analysed on your device and never uploaded. The reference image lives
in the app's own storage and is deleted with the alarm.

### Steps

Walk a number of steps you choose when setting the alarm up (30 by default),
counted by the iPhone's motion sensor. Requires **Motion & Fitness** permission.
Progress is kept if the app is briefly interrupted.

### NFC

Tap a blank NFC sticker you've placed in another room. Set the alarm up by
scanning the tag once; in the morning you have to physically go and tap it again.

- Any NFC tag works: cheap NTAG stickers, a transit card, a hotel key card.
- NFC is iPhone hardware — the app cannot add it to a device that doesn't have it.
  The Permissions page tells you whether your phone supports it.

### Typing

Retype a short phrase shown on screen. Case, spacing and accents are all forgiven,
so you can type it on whatever keyboard you have installed — but you do have to
read it and type it.

### Memory

Four coloured tiles flash in order; you tap them back in the same order. One
wrong tap and the sequence starts again.

### Barcode

Scan any product barcode in your home — a cereal box, a shampoo bottle, a book.
Nothing is looked up online; GetUply only checks that a real barcode was read.

### Voice

Say a short phrase out loud. GetUply transcribes it with Apple's **on-device**
speech recognition, in **the language the app is running in** — the phrase you're
shown and the language being listened for always match, and the screen tells you
which language that is.

- Matching ignores case, accents and small recognition slips. You do not have to
  be word-perfect.
- The alarm sound pauses while the microphone is open, so it doesn't drown you
  out, and resumes if you back out.
- Requires **Microphone** *and* **Speech Recognition** permission.
- If your language has no on-device speech model on your iPhone, the mission says
  so and offers you a different way to dismiss — GetUply never sends your voice to
  a server to work around it.

### Shake

Shake the phone fifteen times. The least demanding mission, and the easiest to do
half asleep — fine as a gentle option, weak as a discipline tool.

### Random

A surprise mission every time it rings, drawn from the ones your phone supports.

### Stacking missions

An alarm can require **up to three missions**, done one after another, each with
its own settings. Walk twenty steps, *then* scan the kitchen QR code, *then*
answer two sums — that is a very hard alarm to go back to sleep through. Add them
in the alarm editor under the primary mission.

### Photo variants: sky, bed, pills, pet, nature

Five ready-made photo missions with the object fixed for you:

| Mission | You photograph |
|---|---|
| **Sky Photo** | The sky — which usually means opening a curtain or stepping outside. |
| **Make Bed** | Your made bed. |
| **Take Pills** | Your pills or supplements. |
| **Pet Hunt** | Your pet. |
| **Nature Hunt** | A tree or plant. |

They use the same on-device recognition as the Photo mission.

> **Take Pills is a nudge, not a medical feature.** GetUply does not track doses,
> does not know what your medication is, and must not be relied on for anything
> clinical.

### Push-ups and squats

Ten push-ups or fifteen squats in front of the camera. GetUply counts them with
Apple's on-device body pose detection.

- Prop the phone so your whole body is in frame. Front camera, a few steps back.
- Good light helps a lot; a dark room is the most common reason reps don't
  register.
- If the camera is unavailable, the mission offers a manual tap fallback so you're
  never stuck.

---

## The ringing screen

When an alarm fires you get the full-screen wake screen: the current time, the
alarm's label, a prompt, and the mission button.

- **Start mission** (or **Stop alarm** for Classic) begins the mission.
- **Snooze** appears when the alarm allows it and you have snoozes left.
- **Hold to emergency stop** appears when you've left it switched on. See below.

If you leave the app mid-mission, the alarm keeps ringing and GetUply re-alerts
you — an unfinished mission is not a dismissed alarm.

---

## Snooze, strict mode and emergency stop

**Snooze** is per-alarm: on or off, the interval in minutes, and a maximum number
of snoozes. When you've used them all, the button goes away.

**Strict mode** (Settings › Alarm behavior, with a per-alarm override) keeps the
mission required. If you explicitly enable **Allow snooze** for that alarm and
have snoozes left, you can snooze even in Strict mode. Snoozing pauses the alarm
for the chosen interval; it does not complete the mission.

**Emergency stop** is the escape hatch: press and hold for three seconds to
dismiss an alarm without finishing the mission. It is limited to **three uses per
calendar week**, so it can't quietly become your new snooze button, and the count
resets at the start of each week. Using it skips your mission and your streak.

You can switch the emergency stop **off** in Settings › Alarm behavior. With it
off, finishing the mission is genuinely the only way to stop an alarm. That is the
point of the switch — turn it off deliberately.

---

## Sounds

Around a hundred alarm tones, grouped by character: Classic, Energetic,
Emergency, Calm, Nature, Birds and more. Tap any tone to preview it.

- Some tones ship inside the app; the rest download on demand the first time you
  choose them, and are then cached.
- **Gradual volume** (Settings › Alarm behavior) eases the sound in over the first
  few seconds instead of starting at full blast.
- **Vibrate with sound** buzzes along with the alarm.
- **Flash during alarm** strobes the torch while it rings. There's a per-alarm
  override too.

> GetUply raises the system volume once when an alarm starts, and never again.
> Your volume buttons keep working exactly as iOS intends.

---

## Wake screens, themes and backdrops

A **wake theme** sets the personality of the ringing screen — its colours, its
effects, and the words it greets you with:

- **Classic** — the signature sunrise.
- **Emergency** — maximum urgency, no mercy.
- **Nature** — soft and green.
- **Motivation** — greeting, streak and a push.
- **Funny** — wake up smiling.
- **Retro** — arcade styling.
- **Night** — dark and quiet, for late shifts.

**Backdrops** are full-screen photographic wake screens that download on demand.
The central band of every image is kept calm so the clock stays readable, and text
colour adapts to the picture behind it.

**App icon** can be changed in Settings › Appearance: Sunrise, Midnight, Mint or
Rose.

---

## Sleep, bedtime and wind-down

**Settings › Sleep & bedtime.**

- **Sleep goal** — 5 to 11 hours. GetUply works backwards from your next alarm to
  show the bedtime that would hit it.
- **Bedtime reminder** — an opt-in nudge at a time you choose. When GetUply knows
  your next alarm, the reminder does the arithmetic for you ("sleep now for about
  8h before your 07:00 alarm"). It's a gentle notification, not an alert that
  pierces Focus.
- **Wind-down sounds** — ambient audio to fall asleep to, with a timer and a
  volume level. It has Lock Screen transport controls, so you can stop it without
  unlocking.
- **Sleep Focus** — a shortcut into iOS Settings › Focus. GetUply links to Apple's
  Focus rather than reimplementing Do Not Disturb.
- **Morning summary** — an optional encouraging note after you're up.

> GetUply is a productivity app, not a sleep tracker. It does not measure your
> sleep, makes no health claims, and is not a medical device.

---

## App Block

App Block uses Apple's Screen Time framework to keep you from dodging a mission:

- **Block app deletion** — stops GetUply being deleted while a mission is owed.
- **Shield distracting apps** — the apps you pick are unavailable **for the
  duration of a mission only**, and come back the moment it's done.

Both are off unless you turn them on, and both need Screen Time authorization.
Nothing about your app usage leaves the device.

---

## Insights, streaks and badges

The **Insights** tab shows your wake history: current streak, best streak, total
wake-ups, success rate, and how you do by mission type and by weekday.

**Badges** are earned for streaks, totals, and consistency — an early-bird badge,
a night-shift badge, a comeback badge after a broken streak, a per-mission badge
for completing five of one type, and more.

Your streak advances when you complete a mission. Emergency stops don't count.

You can reset statistics without touching your alarms: Settings › Account ›
**Reset streaks and stats**.

---

## Settings reference

| Page | What lives there |
|---|---|
| **Account** | Your plan, lifetime stats, restore purchases, reset stats. |
| **Alarm behavior** | Strict mode, emergency stop on/off, system alarm, default snooze length and count, gradual volume, haptics, vibrate, flash. |
| **Sleep & bedtime** | Sleep goal, bedtime reminder, wind-down sounds, Sleep Focus, morning summary. |
| **Default alarm sound** | The tone new alarms start with. |
| **Alarm protection** | A check that your alarm can actually ring, plus a report of any recent failure. |
| **Appearance & app icon** | Light/dark/system, accent, app icon. |
| **Permissions** | Every permission GetUply can ask for, its live status, and a way into iOS Settings. |
| **Sounds & haptics** | Feedback on taps and success. |
| **Data & privacy** | The privacy position, the privacy policy and terms, and **Delete all data**. |
| **Support** | This Help Center, rate the app, tell a friend. |

**Search** at the top of Settings finds any of these by name or by what they do —
type "vibrate", "dark", "delete" and it will get you there.

---

## Permissions

| Permission | Needed for | Without it |
|---|---|---|
| **Notifications** | Alarm reminders and backup alerts | Notification reminders/backups are unavailable. Native AlarmKit has its own permission. |
| **Alarms (AlarmKit)** | Native Lock Screen alarms | Native alerts are unavailable; notification fallback needs notification permission. |
| **Camera** | QR, barcode, photo, push-up and squat missions | Those missions can't run. |
| **Motion & Fitness** | Steps mission | Steps can't be counted. |
| **Microphone** | Voice mission | The mission can't hear you. |
| **Speech Recognition** | Voice mission | The phrase can't be checked. |
| **NFC** | NFC mission | Hardware, not a permission — supported or not. |
| **Screen Time** | App Block | App Block stays off. |

iOS only shows each permission prompt once. If you said no and changed your mind,
**Settings › Permissions › Open iOS Settings** takes you straight to GetUply's
switches. Denying a permission does not block setup or the rest of the app; it
makes the dependent mission or alert path unavailable. AlarmKit and notification
permissions are separate.

---

## Languages

GetUply is fully translated into **21 languages**: English, Arabic, German,
Spanish, French, Hindi, Indonesian, Italian, Japanese, Korean, Dutch, Polish,
Brazilian Portuguese, Russian, Swedish, Thai, Turkish, Ukrainian, Vietnamese,
Simplified Chinese and Traditional Chinese.

The app follows your iPhone's language. Every language-sensitive feature follows
it too:

- The **Voice mission** listens in the language the app is displaying, and tells
  you which one that is.
- The **Typing mission** compares what you typed in that language's own rules, so
  Turkish dotted and dotless i, German umlauts, and every other accented letter
  behave the way a speaker expects — and you can type the phrase on a keyboard
  that doesn't have those letters at all.
- Settings search works the same way.

To change it: iOS **Settings › GetUply › Language**.

---

## GetUply Pro

**Free** gives you one alarm, the Classic (no-mission) alarm, the default tone and
the default wake screen.

**Pro** unlocks:

- Unlimited alarms
- Every wake mission
- The full sound library
- Every wake theme and every backdrop
- Alternative app icons

Pro is an auto-renewing subscription, available weekly, monthly or yearly, with a
free trial on the monthly and yearly plans when eligible. Each plan includes the
same Pro features while the subscription is active. It's billed by Apple through
your App Store account.

- **Manage or cancel:** Settings › Account › *Manage in App Store*, or iOS
  Settings › your name › Subscriptions.
- **Restore:** Settings › Account › *Restore purchases* — use this on a new phone
  or after reinstalling.
- Cancelling keeps Pro until the end of the period you've paid for.

---

## Privacy

- **No account.** No email, no password, no sign-in.
- **No server.** There is no GetUply backend that your data goes to.
- Alarms, streaks, statistics, mission reference photos and settings are stored on
  your iPhone.
- Photos and voice are processed **on-device** by Apple's frameworks and are never
  uploaded.
- Alarm tones and backdrops are downloaded from a public GitHub repository. That
  is an ordinary file download; it carries nothing about you.
- Subscription status is handled by Apple's StoreKit and RevenueCat, which is what
  lets your purchase survive a reinstall.

**Settings › Data & privacy › Delete all data** erases every alarm, streak,
statistic and mission photo on the device.

Full text: [Privacy Policy](legal/PRIVACY.md) · [Terms of Use](legal/TERMS.md)

---

## Troubleshooting

### My alarm didn't ring

Work down this list:

1. **Alarm permissions.** Check System alarm permission and Notifications
   separately in Settings. Native alarms and notification backups use different
   permissions; grant the one needed for your alert path in iOS Settings.
2. **System alarm.** Settings › Alarm behavior › *System alarm*. On is the
   reliable path: it rings on the Lock Screen with the app closed.
3. **Alarm protection.** Settings › Alarm protection runs a check and reports any
   recent failure.
4. **Focus / Do Not Disturb.** Allow GetUply's notifications to break through, or
   rely on the system alarm.
5. **Silent switch and volume.** The system alarm rings regardless; the
   notification fallback depends on your sound settings.
6. **The alarm is actually on**, and its repeat days include today.

### The photo mission won't accept my photo

If you're using a **custom reference photo**:

- Take it from roughly the same distance and angle you used when setting it up.
- Fill more of the frame with the object.
- Turn a light on. The screen tells you whether you were *close* or not close at
  all — "close" means framing, "not close" usually means it's a different object
  in view.
- If it keeps failing, re-take the reference photo. A reference shot of a blank
  wall or a very dark room gives the matcher nothing to work with.

If you're using **preset objects**, make sure the object genuinely fills the
viewfinder and is lit. The scanner shows you what it thinks it's looking at and
how confident it is.

### The voice mission doesn't understand me

- Check the "Listening in …" line under the transcript. That is the language being
  transcribed; it follows the app's language.
- If it names the wrong language, change the app's language in iOS Settings ›
  GetUply › Language.
- If the mission says speech recognition isn't available for your language, your
  iPhone has no on-device model for it. Add the language in iOS Settings ›
  General › Keyboard › Dictation Languages, or use another mission.
- Speak at a normal pace, close to the phone. You don't need to be word-perfect.

### Push-ups or squats aren't counting

Whole body in frame, phone propped up a few steps away, lights on. If your camera
is blocked or unavailable, use the manual tap fallback.

### Steps aren't counting

Motion & Fitness permission must be allowed — Settings › Permissions. Carry the
phone as you walk; counting comes from the phone's own motion sensor.

### I lost my QR code

Open the alarm, go to the QR mission and generate a new one.

### I'm locked out of my alarm

Hold the **emergency stop** for three seconds — unless you switched it off, in
which case finishing the mission is the way out, by design. Three emergency stops
are available per week.

### I bought Pro but the app says Free

Settings › Account › **Restore purchases**. Make sure you're signed into the same
Apple Account you bought with.

---

## Contact

Questions, bugs, or a feature you want:
[open an issue](https://github.com/ceritmustafa/getuply-public/issues).

For support requests see [SUPPORT.md](legal/SUPPORT.md).
