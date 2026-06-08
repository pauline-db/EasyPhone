# EasyPhone

> *Accessibility-first smartphones — designed with and for older adults.*

Built in **24 hours** at **HackDelft 2026**.

---

## The Problem

Standard smartphones were not built with older adults in mind:

- **Overwhelming interfaces** — hundreds of apps, dense/hidden menus, and constant notifications create daily stress
- **Small text & invisible controls** — default font sizes and tap targets are designed for younger eyes and steady hands; gestures like swipe and pinch feel unnatural to older individuals
- **No fast path to safety** — navigating menus to call for help takes precious time in an emergency

> **1 in 6** people worldwide is aged 65 or over (WHO projects 1 in 5 by 2050).  
> **53%** of adults aged 65+ feel overwhelmed by new technology, with 35% citing fear of making mistakes.  
> **68%** of older adults report struggling with digital literacy skills *(National Council on Aging, 2022)*.

---

## What is EasyPhone?

EasyPhone is an open-source Android OS layer that goes beyond a simple launcher — while competitors like Elder Launcher, ONYPhone, and BaldPhone replace the home screen UI but reuse Android's default apps underneath, **EasyPhone redefines the apps themselves, for seniors**.

It runs on any **Android 8+** device and supports **English, French, and Dutch**.

### Core principles

| | |
|---|---|
| **Simplicity** | No hidden gestures — every button is visible, overcomplicated functionalities made accessible |
| **Consistency** | No lost functionality — a constant navigation bar always present on screen |
| **Safety** | Easily accessible emergency button and navigation home, activated with a single click |
| **Set Up by Someone Who Cares** | A PIN-protected setup mode lets a family member configure the experience once — the user never needs to touch settings |

---

## Features

| App | Description |
|---|---|
|  **Call** | One tap to reach contacts |
|  **Take Me Home** | Direct routing home with clear instructions |
|  **Messages** | Accessible messages with customisable font size |
|  **Camera & Gallery** | One tap anywhere to take a picture, clear recording alert for videos, large zoom buttons |
|  **Emergency SOS** | Instant alert and shared location to emergency contact with one click |
|  **Torch** | One large button, instant light |
|  **Calendar** | Clear week view with personal events |
|  **Wallet** | Clear button linked to wallet for accessible payments |
|  **YouTube & others** | Other desired apps can easily be added to the interface |

---

## Emergency SOS

**One press. Help is on the way.**

1. Press the red Emergency tile
2. Confirm the pop-up
3. Emergency call placed to the predefined contact — location is shared automatically

> Works even when the user cannot describe their location.

---

## Take Me Home — Accessible Navigation

- **Home address saved once** — configured by a family member, never changed by accident
- **Choose your travel mode** — car or walking, buttons disappear once selected
- **Clear routing** — step-by-step instructions displayed at the bottom of the screen
- Powered by **OpenStreetMap + Leaflet**

---

## How We're Different

Existing solutions (Elder Launcher, ONYPhone, BaldPhone) are **launchers** — they change what the home screen looks like, but the apps behind them are still the standard Android ones.

**EasyPhone rebuilds the apps themselves** from the ground up, designed specifically for seniors at every level of the experience.

---

## Requirements

- Android 8.0 (Oreo) or higher
- Phone & location permissions (for Call and Emergency SOS)
- NFC (optional, for Wallet)

---

## Getting Started

### Install via APK
1. Download the latest APK from the [Releases](../../releases) page
2. On your Android device, enable **Install from unknown sources** in Settings
3. Open the APK and follow the on-screen instructions
4. Hand the phone to a family member to complete the PIN-protected caregiver setup
