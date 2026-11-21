# CyberBoot

**An interactive cybersecurity bootcamp that teaches online safety by letting you practice it.**

**Live site:** [cyber-boot.vercel.app](https://cyber-boot.vercel.app)

![CyberBoot illustration](images/online-security-character-1.svg)

## The story behind CyberBoot

We're taught not to click suspicious links or share personal information, but how often do we actually get to practice making those decisions before encountering them in real life?

CyberBoot was built around the idea that online safety should be learned through experience. By recreating everyday digital interactions in a safe environment, it gives people the opportunity to make mistakes, learn from them, and build better habits.

## What's inside

| Activity | What you do |
|---|---|
| **Phishing inbox** | Go through a realistic inbox and decide which emails are safe and which are phishing. |
| **Chat scenarios** | Respond to messages from strangers online and choose the safest reply. |
| **Password checker** | Type a password and see how it measures up against strength criteria. |
| **Quiz** | Test what you learned, with a running score of correct and incorrect answers. |
| **Certificate** | Finish the activities with a passing score and get a certificate with your name on it. |

## How it works

CyberBoot runs entirely in the browser. There's no account, no server and no data collected. You enter your name at the start, work through each activity, and your score is tracked as you go.

## Run it locally

No build step or install is needed:

```bash
git clone https://github.com/riaseth1/CyberBoot.git
cd CyberBoot
open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Built with

- HTML, CSS and JavaScript
- Bootstrap
- Deployed on Vercel

## Project structure

```
CyberBoot/
├── index.html                  # Welcome screen, enter your name
├── activiy-intro.html          # Activity overview
├── phishing-activity.html      # Phishing inbox
├── phishing-activity-open.html # Opened email view
├── chat.html                   # Chat scenarios
├── password-activity.html      # Password strength checker
├── quiz.html                   # Quiz
├── certificate.html            # Completion certificate
├── css/                        # Styles
├── script/                     # App logic
└── images/                     # Illustrations
```

---

Made by [Ria Sethi](https://riaseth1.github.io).
