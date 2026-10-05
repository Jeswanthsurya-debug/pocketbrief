# PocketBrief

**Turn the deadlines buried in your phone's messages into a clear daily plan, privately and offline.**

Built for the iQOO Hackathon | Track: Productivity

**Live demo:** https://jeswanthsurya-debug.github.io/pocketbrief/

## The Problem

Students and young professionals get important tasks scattered across WhatsApp groups, college circulars, emails and screenshots. Deadlines get buried in long chats and people miss submissions, reviews and events. To-do apps need manual typing, and cloud AI tools need your private messages uploaded to a server.

## The Solution

PocketBrief reads any pasted message or screenshot directly on the phone and automatically extracts the **task**, **deadline** and **priority**. It then builds a **Today** view sorted by urgency, with live countdowns and a short daily brief. Everything runs on the device, so messages never leave the phone, and it works offline as an installable app.

## Features

- Paste any message or scan a screenshot (on-device OCR)
- Automatic task, deadline and priority extraction
- Understands deadlines like "tomorrow 5 PM", "by Friday" and "12 Oct"
- Today view with live countdowns and one-tap completion
- Daily Brief summary
- 100% on-device and private
- Works offline and installs on the home screen (PWA)
- Light and dark mode

## How It Works

1. Paste a message or scan a screenshot.
2. On-device rules extract the task, deadline and category.
3. A priority score is calculated from urgency words and time left.
4. The Today view shows tasks by urgency, with countdowns.

## Tech Stack

HTML, CSS, JavaScript, Progressive Web App (service worker and manifest), Tesseract.js for on-device OCR, localStorage for saving data.

## Run Locally

```bash
git clone https://github.com/Jeswanthsurya-debug/pocketbrief.git
cd pocketbrief
```

Open `index.html` in a browser. To install it as an app, open the live demo on your phone and choose **Add to Home Screen**.

## Future Scope

- Smarter on-device language model for harder messages
- Reminders and notifications before deadlines
- Calendar sync and voice input
- Support for Indian regional languages

## Author

**Jeswanth Surya**
[GitHub](https://github.com/Jeswanthsurya-debug) | [LinkedIn](https://linkedin.com/in/jeswanth-surya-98517b339)
