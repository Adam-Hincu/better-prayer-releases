# Better Prayer — Desktop Islamic Prayer Times App for Windows

> A calm, polished Islamic prayer app for Windows that helps Muslims stay consistent with salah through prayer times, Quran reminders, fasting times, and an optional device lockdown at prayer time.

**Better Prayer** is a Windows desktop prayer app for Muslims who spend a lot of time on their computer and want a beautiful, practical way to remember prayer on time. It combines accurate Islamic prayer times, prayer reminders, a Quran daily verse, fasting times, the next Islamic event, Jumu'ah awareness, and a unique optional **Prayer Lockdown** feature that can temporarily lock the device at prayer time.

Most Islamic prayer apps are mobile-first. Better Prayer is built specifically as an **Islamic PC app** and **desktop Islamic prayer times app** for Windows 10 and Windows 11. It is designed for people who sit at their computer for long sessions and sometimes think, "I'll pray later," only to lose track of time. Better Prayer helps turn prayer time into a clear interruption, a reminder, and, if you choose, a stronger habit-building guardrail.

> [!IMPORTANT]
> The device lockdown feature is optional. You can use Better Prayer as a normal Windows prayer times app with reminders, Quran, fasting times, and Islamic events without enabling lockdown.

## Download

- Website: [better-prayer.com](https://better-prayer.com)
- GitHub Releases: [Better Prayer Releases](https://github.com/Adam-Hincu/better-prayer-releases/releases/latest)
- Community: [Join the Discord](https://discord.gg/B6pFQjpy65)

Better Prayer is distributed as a Windows installer. You can install it using either the `.exe` installer or the `.msi` installer.

## Table of Contents

- [Why Better Prayer Exists](#why-better-prayer-exists)
- [Who Better Prayer Is For](#who-better-prayer-is-for)
- [Core Features](#core-features)
- [Prayer Lockdown](#prayer-lockdown)
- [Prayer Times](#prayer-times)
- [Prayer Reminders](#prayer-reminders)
- [Daily Quran Verse](#daily-quran-verse)
- [Fasting Times](#fasting-times)
- [Islamic Events and Jumuah](#islamic-events-and-jumuah)
- [First-Time User Flow](#first-time-user-flow)
- [Installation](#installation)
- [Supported Platform](#supported-platform)
- [Account and Internet Requirements](#account-and-internet-requirements)
- [Settings and Customization](#settings-and-customization)
- [Performance](#performance)
- [Updates](#updates)
- [Safety and Windows SmartScreen](#safety-and-windows-smartscreen)
- [Known Limitations](#known-limitations)
- [Roadmap](#roadmap)
- [FAQ](#faq)
- [Credits](#credits)
- [License](#license)
- [Repository Purpose](#repository-purpose)
- [Community](#community)
- [Website](#website)

## Why Better Prayer Exists

Better Prayer was created for a simple but serious problem: it is easy to disappear into your computer.

You open your Windows PC to work, study, browse, code, watch videos, chat, or play. A prayer time arrives. You see the time, hear the reminder, or remember it for a moment. Then the thought comes: "I'll pray in a few minutes." The few minutes become longer. The computer keeps pulling your attention back in.

Better Prayer is designed to help Muslims break that loop.

It is not only a **PC prayer times app**. It is a desktop prayer companion for building consistency. It gives you prayer times, reminders, Quran reflection, fasting times, and Islamic events in a clean interface. For users who want a stronger nudge, it also includes an optional **PC prayer lockdown app** feature that can lock the computer at prayer time and encourage you to physically get up for wudu.

The goal is not to make prayer feel complicated. The goal is to make it harder for your computer to quietly steal the time you intended to give to Allah.

## Who Better Prayer Is For

Better Prayer is for Muslims who want their Windows computer to support their prayer routine instead of distracting from it.

It is especially useful if you are looking for:

- A **desktop Islamic prayer times app** for Windows
- A **PC prayer times app** with a clean and modern interface
- A **Windows prayer times app** that shows the next prayer clearly
- An **Islamic PC app** for prayer reminders, Quran reflection, fasting times, and Islamic events
- A **prayer reminder app for PC** that can notify you before prayer and at prayer time
- A **desktop prayer app** that helps build a stronger salah habit
- A **PC prayer lockdown app** that can optionally lock your device when prayer time arrives
- A calm Islamic desktop app that feels lightweight, minimal, and focused

Better Prayer is not meant to replace intention, discipline, or sincere worship. It is meant to reduce one specific modern problem: losing track of prayer because the computer keeps your attention.

## Core Features

| Feature | Description |
|---|---|
| **Prayer Lockdown** | Optionally lock your Windows device at selected prayer times so you stop delaying salah. |
| **Phone Verification** | Unlock early by connecting your phone through a QR code or local link and taking a sink photo as wudu proof. |
| **AI Sink Detection** | A local AI model checks whether the photo contains a sink before considering the verification successful. |
| **Optional 5-Minute Enforced Lock** | After sink verification, you can keep the computer locked for 5 more minutes to help protect the prayer window. |
| **Prayer Times** | See the next prayer and the full prayer schedule for the day. |
| **Prayer Notifications** | Get a reminder 10 minutes before prayer and another notification at prayer time. |
| **Daily Quran Verse** | Receive a shared Quran daily verse with Arabic text, transliteration, translation, and explanation. |
| **Fasting Times** | See suhoor and iftar times clearly inside the app. |
| **Islamic Events** | See the next Islamic event and how much time remains until it. |
| **Jumu'ah Awareness** | Know whether Jumu'ah is today. |
| **Windows Desktop Experience** | Built for Windows 10 and Windows 11, with a clean, calm, lightweight interface. |
| **Auto and Manual Updates** | Get updates automatically or check manually from inside the app. |
| **In-App Bug Reports** | Report bugs without leaving Better Prayer. |
| **Discord Community** | Join the Better Prayer community for feedback, support, and updates. |

## Prayer Lockdown

Prayer Lockdown is the flagship feature of Better Prayer.

It is what makes Better Prayer different from a normal Islamic prayer times app, a normal reminder app, or a mobile prayer app. The feature is designed for Muslims who use their Windows computer heavily and want a real barrier between "prayer time has arrived" and "I will do it later."

When Prayer Lockdown is enabled, Better Prayer can temporarily lock your device at selected prayer times. Instead of simply showing a notification that can be ignored, the app creates a stronger interruption. This makes it useful for people who want to build a prayer habit, reduce procrastination, and make salah harder to delay during computer use.

Again: **Prayer Lockdown is optional**. You can turn it off and use Better Prayer as a normal desktop prayer app.

### How Prayer Lockdown Works

1. A selected prayer time arrives.
2. Better Prayer locks the Windows device.
3. The lock screen shows a QR code and a local connection link.
4. You connect your iPhone or Android phone to the locally hosted verification page.
5. You get up from the computer and take a picture of the sink.
6. A local AI model checks whether the image contains a sink.
7. If the sink is detected, Better Prayer considers that you got up for wudu.
8. The device unlocks according to your configured lockdown behavior.

By default, the lockdown automatically unlocks after 15 minutes. This means that even if you do not use phone verification, the computer will not stay locked forever.

### Optional 5-Minute Enforced Lock After Verification

Some users may walk to the sink, verify, and immediately return to the computer. Better Prayer includes an optional setting for this.

If enabled, the app will keep the device locked for 5 minutes even after successful sink verification. This is meant to protect the prayer window and encourage the full action: get up, make wudu, and pray.

This setting is optional and can be changed from Settings.

### Select Which Prayers Use Lockdown

Not every user needs the same strictness for every prayer. Better Prayer lets you choose which prayer times should trigger device lockdown.

For example, you may choose to enable Prayer Lockdown for:

- Fajr
- Dhuhr
- Asr
- Maghrib
- Isha

Or you may only enable it for the prayer times that are hardest for you to keep while using your computer.

### Why This Feature Matters

A standard prayer reminder is easy to dismiss. A normal notification competes with everything else on your computer.

Prayer Lockdown is different because it changes the moment. It turns prayer time into a real pause. It helps users step away from the screen, break the cycle of delay, and reconnect with their intention.

For people searching for a **PC prayer lockdown app**, **desktop prayer app**, **Islam app desktop**, or **Islamic PC app**, this is the core reason Better Prayer exists.

## Prayer Times

Better Prayer shows Islamic prayer times directly on your Windows desktop.

The main screen is designed around the most important question: **what is the next prayer?**

You can see:

- The next prayer
- How much time remains until the next prayer
- Today's full prayer schedule
- Prayer times in your preferred time format
- Prayer times based on your current or custom location

There is also a dedicated Prayer Times tab in the sidebar. This tab shows the next prayer at the top and the full list of today's prayer times underneath it.

Better Prayer is designed to be a clean **Windows prayer times app** and **desktop Islamic prayer times app**, not a cluttered utility. Prayer time information should be clear at a glance.

## Prayer Reminders

Better Prayer includes prayer notifications so you can prepare before prayer time and be reminded when the prayer time arrives.

You can receive:

- A reminder 10 minutes before prayer
- A notification exactly at prayer time

Both reminder types are configurable. You can turn either one on or off from Settings.

You can also customize which prayers you want to be notified about. This is useful if you only want reminders for selected prayers or if your schedule already handles certain prayer times.

A good prayer reminder app should not feel annoying. Better Prayer is built to be calm, useful, and adjustable.

## Daily Quran Verse

Better Prayer includes a **Quran daily verse** feature for reflection. The Quran daily verse is designed to make the app feel like more than a utility: it gives you a small moment of Quran reflection each day.

Every day, users receive the same daily verse. The verse is shown with:

- Original Arabic text as it appears in the Quran
- Transliteration
- Verified translation
- A natural-language explanation in the selected language

Supported languages include:

- English
- Chinese
- Hindi
- Spanish
- Arabic
- French
- Bengali
- Portuguese
- Russian
- Urdu
- Turkish

This makes Better Prayer more than a prayer timer. It becomes a small daily Islamic habit on your Windows PC: see the next prayer, remember Allah, reflect on Quran, and keep your routine connected to something meaningful.

## Fasting Times

Better Prayer shows fasting times for Muslims who want quick access to suhoor and iftar information.

Inside the app, you can see:

- Suhoor time
- Iftar time
- Daily fasting-related timing information

This is especially useful during Ramadan, voluntary fasting days, or any time you want fasting times available inside the same desktop Islamic app that already handles prayer times.

## Islamic Events and Jumuah

Better Prayer shows the next Islamic event and how much time remains until it.

The app also shows whether Jumu'ah is today, making it easier to stay aware of Friday prayer while using your computer.

This section is designed to keep important Islamic time markers visible without overwhelming the main interface.

## First-Time User Flow

Better Prayer is designed to feel simple from the first launch.

### 1. Install Better Prayer

Download the `.exe` or `.msi` installer from the official website or GitHub Releases. Open the installer and follow the guided setup.

### 2. Sign In

Sign-in is required. If you are not signed in, Better Prayer shows the login screen.

### 3. Complete Onboarding

If this is your first time signing in, Better Prayer shows a short onboarding flow. The onboarding is designed to be concise and focused only on the essentials.

### 4. Open the Dashboard

After signup and onboarding, you land on the main dashboard.

The dashboard shows:

- Next prayer
- Next Islamic event
- Fasting times
- Quran daily verse

### 5. Check Prayer Times

Use the Prayer Times tab in the sidebar to view the next prayer and the full prayer schedule for the day.

### 6. Customize Settings

Open Settings to personalize Better Prayer.

You can configure prayer reminders, Prayer Lockdown, time format, selected prayer notifications, custom location, app theme, cache clearing, update checks, and bug reporting.

## Installation

Better Prayer currently supports Windows.

### Windows 10 and Windows 11

1. Download the latest Better Prayer installer from [better-prayer.com](https://better-prayer.com) or [GitHub Releases](https://github.com/Adam-Hincu/better-prayer-releases/releases/latest).
2. Choose either the `.exe` installer or the `.msi` installer.
3. Open the installer.
4. Follow the guided setup.
5. Launch Better Prayer.
6. Sign in and complete onboarding if this is your first time.

The installer is designed to be straightforward: download, open, continue through the installer, and launch the app.

## Supported Platform

| Platform | Status | Notes |
|---|---|---|
| Windows 10 | Supported | Use the `.exe` or `.msi` installer. |
| Windows 11 | Supported | Use the `.exe` or `.msi` installer. |
| macOS | Planned | macOS support is on the roadmap. |
| Linux | Planned | Linux support is on the roadmap. |
| iOS | Planned companion app | Planned for connection to the Better Prayer service. |
| Android | Planned companion app | Planned for connection to the Better Prayer service. |

Better Prayer is currently a Windows desktop prayer app. macOS, Linux, iOS, and Android support are planned for future development.

## Account and Internet Requirements

Better Prayer requires:

- A Better Prayer account
- An internet connection
- Windows 10 or Windows 11

Offline support is not currently available.

If you are not signed in, the app will show the login screen. Once signed in, Better Prayer loads the main dashboard and prayer experience.

## Settings and Customization

Better Prayer includes a Settings area where users can control the experience.

Available settings include:

- Enable or disable Prayer Lockdown
- Choose which prayer times trigger lockdown
- Enable or disable the optional 5-minute enforced lock after sink verification
- Enable or disable the 10-minute pre-prayer reminder
- Enable or disable the prayer-time notification
- Choose which prayers send notifications
- Change the time format
- Use current location or set a custom location
- Change the app theme
- Clear cache
- Check for updates
- Report bugs inside the app

The goal is to make Better Prayer flexible. Some users may want a gentle prayer reminder app. Others may want a stronger habit-building desktop prayer app with lockdown enabled. Settings make both experiences possible.

## Performance

Better Prayer is designed to be lightweight.

The app should run properly on weak Windows devices and does not require a powerful processor. It is intended to feel smooth, calm, and responsive while staying out of the way until prayer time.

Better Prayer is a desktop app for daily use, so performance matters. It should not feel heavy, noisy, or distracting.

## Updates

Better Prayer supports both automatic and manual updates.

You can:

- Receive updates automatically
- Check for updates manually from inside the app
- Download the latest installer from the official website
- Download releases from GitHub Releases

Release updates are focused on improving stability, polishing the user experience, and expanding platform support over time.

## Safety and Windows SmartScreen

Better Prayer is free to use and distributed through the official website and GitHub Releases.

Because the app is not currently signed with a paid code-signing certificate, Windows may show a SmartScreen or security warning when you install it. This can happen with new or unsigned Windows desktop apps, even when they are distributed intentionally by the developer.

To stay safe:

- Download Better Prayer only from [better-prayer.com](https://better-prayer.com) or the official GitHub Releases page.
- Do not install Better Prayer from random mirrors or unofficial download websites.
- Make sure the file name and release source match the official Better Prayer release.

Better Prayer is not open source. The GitHub repository is used for releases, downloads, and project information, not for publishing the application source code.

## Known Limitations

Better Prayer is actively maintained, but there are current limitations.

- Windows only for now.
- macOS support is planned but not currently available.
- Linux support is planned but not currently available.
- Sign-in is mandatory.
- Internet is required.
- Offline support is not available.
- There are no keyboard shortcuts currently.
- Import and export are not part of the app.
- There are no third-party integrations currently.
- The app is not currently signed with a paid Windows code-signing certificate.
- The source code is not public.

These limitations are listed clearly so users know what to expect before downloading.

## Roadmap

Planned improvements include:

- macOS release
- Linux release
- iOS app for connecting to the Better Prayer service
- Android app for connecting to the Better Prayer service
- Continued UI polish
- A larger visual refresh
- More refinements to make the app feel even cleaner, calmer, and more beautiful

The long-term direction is to make Better Prayer a polished, lightweight Islamic desktop app that helps Muslims keep prayer visible while using modern devices.

## FAQ

### What is Better Prayer?

Better Prayer is a Windows desktop Islamic prayer app with prayer times, prayer reminders, a Quran daily verse, fasting times, Islamic events, Jumu'ah awareness, and an optional device lockdown feature for prayer time.

### Is Better Prayer a normal prayer times app?

Yes. You can use Better Prayer as a normal PC prayer times app to see the next prayer, today's prayer schedule, prayer reminders, the Quran daily verse, fasting times, and Islamic events.

### What makes Better Prayer different?

Better Prayer is built specifically for Windows desktop users and includes an optional Prayer Lockdown feature. This feature can lock your computer at selected prayer times and help you step away from the screen for wudu and salah.

### Is the device lockdown required?

No. Prayer Lockdown is completely optional. You can turn it off from Settings.

### What happens if Prayer Lockdown is enabled?

At selected prayer times, Better Prayer can lock your Windows device. You can either wait for the automatic unlock after 15 minutes or connect your phone and verify that you got up by taking a sink photo.

### How does phone verification work?

The lock screen shows a QR code or local link. You open it on your iPhone or Android phone, take a picture of the sink, and a local AI model checks whether a sink is present.

### Why does Better Prayer ask for a sink photo?

The sink photo is used as a practical signal that you got up from the computer and went to make wudu.

### Can Better Prayer keep the computer locked after sink verification?

Yes. There is an optional 5-minute enforced lockdown setting after successful verification. This is meant to help protect the prayer window.

### Does Better Prayer support Windows 10?

Yes. Better Prayer supports Windows 10.

### Does Better Prayer support Windows 11?

Yes. Better Prayer supports Windows 11.

### Does Better Prayer work offline?

No. Better Prayer currently requires an internet connection.

### Is sign-in required?

Yes. Sign-in is required to use Better Prayer.

### Is Better Prayer open source?

No. Better Prayer is free to use, but the source code is not public.

### Why does Windows show a warning?

Better Prayer is not currently signed with a paid code-signing certificate, so Windows SmartScreen may show a warning. Download only from the official website or GitHub Releases.

### Does Better Prayer have keyboard shortcuts?

No. Better Prayer does not currently include keyboard shortcuts.

### Does Better Prayer support macOS or Linux?

Not yet. macOS and Linux support are planned.

### Where can I report bugs?

You can report bugs inside the app. You can also join the Discord community: [https://discord.gg/B6pFQjpy65](https://discord.gg/B6pFQjpy65)

## Credits

Better Prayer uses Islamic timing and Quran-related services to provide its core experience.

Credits:

- [AlAdhan API](https://aladhan.com/prayer-times-api)
- [AlQuran API](https://alquran.cloud/api)

Thank you to the services and communities that make Islamic prayer time and Quran access easier for Muslims around the world.

## License

Better Prayer is free to use, but it is not open source.

Unless a separate written license says otherwise, all rights are reserved by the developer. The source code is not published, redistributed, or licensed for public modification.

## Repository Purpose

This repository, **Better-Prayer-Releases**, exists for Better Prayer release information, installer downloads, and public project details.

The application source code is not included in this repository.

## Community

Join the Better Prayer Discord community for updates, support, feedback, and discussion:

[https://discord.gg/B6pFQjpy65](https://discord.gg/B6pFQjpy65)

## Website

Visit the official Better Prayer website:

[https://better-prayer.com](https://better-prayer.com)
