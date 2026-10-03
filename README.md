# Android Adware Removal Guide

A simple, step-by-step guide to remove stubborn adware and full-screen pop-up ads from your Android phone, **without a factory reset**.

As a software engineering student, I created this guide to give the public a clear way to deal with deeply hidden adware that standard uninstalls or DNS blocks cannot fix. It is written in plain English so anyone can follow it.

## What's Inside: 3 Methods, Easiest First

Each method has everything you need inside it, from start to finish. Start with Method 1. If the ads are still there, move on to the next one.

| Method | Level | What you need |
|---|---|---|
| **Method 1: Phone Settings** | Easy | Just your phone |
| **Method 2: ADB AppControl** | Medium | Phone, Windows computer, data-capable USB cable |
| **Method 3: Typing Commands (ADB)** | Advanced | Phone, Windows computer, data-capable USB cable |

Methods 2 and 3 do the same job. Method 2 is point-and-click (easier). Method 3 uses short commands (more control). You only need to do **one** of them.

## Why Use This Guide?
* **No Factory Reset:** Fix the issue without wiping your phone or losing photos, contacts, and notes.
* **Targeted Removal:** Finds the exact hidden app (its package name) behind the ads.
* **Free Tools Only:** Uses free tools: your phone's own settings, [ADB AppControl](https://adbappcontrol.com), and Google's official ADB (Android SDK Platform-Tools).
* **Beginner Friendly:** Simple language, clear steps, and an "Ask Google" check so you never have to guess which app is bad.
* **Stay Protected:** Includes a setup for **AdGuard DNS** and other settings to stop adware from coming back.

## Stay Protected with AdGuard DNS (Recommended)

Once the ads are gone, switch on **AdGuard DNS**. It is a free filter that blocks ads, trackers, and dangerous websites across your whole phone (browser, apps, and games). It also helps stop fake "Your phone has a virus!" pop-ups.

1. Open **Settings**, then **Connection & sharing** (or **Network & internet**).
2. Tap **Private DNS**.
3. Choose **Private DNS provider hostname**.
4. Type: `dns.adguard-dns.com`
5. Tap **Save**.

Works on Android 9 and newer. For extra protection for kids, use `family.adguard-dns.com` instead.

## ⚠️ Important Disclaimer & Risks
* **Do Not Guess:** Only uninstall apps you are absolutely certain are adware. Accidentally removing a core system app (like your phone's launcher or `com.android.systemui`) can crash the phone and force the exact factory reset you are trying to avoid.
* **Ask Google First:** If you are unsure about an app name, copy it into Google and add the word `adware`. If it is a trusted app from a well-known company, leave it alone.
* **Turn Off USB Debugging:** If you use Method 2 or 3, turn USB Debugging off in Developer Options when you are done. Leaving it on exposes your phone to security risks when plugged into public computers or charging stations.
* **Download from Official Sources Only:** Get ADB AppControl from [adbappcontrol.com](https://adbappcontrol.com) and Platform-Tools from the official Android Developer website. Copycat sites exist.
* **Use AI Assistance:** If you get confused by the command line interface or developer options, use tools like ChatGPT or Gemini to help clarify the steps.
* **Use at Your Own Risk:** This guide is provided as-is for educational purposes.

## How to Access the Guide
1. Click on `Android_Adware_Removal_Guide.pdf` in the files above.
2. Click the **Download raw file** button (the download icon on the right side) to save the PDF to your device.
3. Follow the instructions for the method you choose.

An editable Word version is also available: `Android_Adware_Removal_Guide.docx`.
