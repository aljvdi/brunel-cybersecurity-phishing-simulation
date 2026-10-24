# Spot the Phish

An interactive phishing-awareness game by **Brunel Cyber Security Society**, built to help students recognise suspicious emails and practise safer online habits.

**Play the game:** [phishing.brunelcs.org](https://phishing.brunelcs.org/)

## Features

- Eight fictional, university-themed email scenarios
- Decide whether each message is legitimate or phishing
- Inspect sender addresses, links and other warning signs
- Immediate explanations, score tracking and replay
- Responsive layout for desktop and mobile
- No accounts, analytics, database or external dependencies

## Technology

HTML5, CSS3 and vanilla JavaScript. Everything runs in the browser.

## Run locally

Download or clone the repository and open `index.html` in a browser. No build step or installation is required.

## Deployment

The production game is hosted at **https://phishing.brunelcs.org/**.

Deploy by placing `index.html` in the document root of the `phishing.brunelcs.org` subdomain. The HTML file contains the styling and JavaScript, so no additional assets or packages are required.

## Update the scenarios

Open `index.html` and edit the `emails` array in the JavaScript near the end of the file. The game currently has eight scenarios; if you change that number, check any hard-coded progress and results labels as well.

## What to do if you receive a suspicious email

Use Outlook's **Report Phishing** feature to report a genuine suspicious email. Choosing **Report phishing** in this game is only a simulation and does **not** submit a report.

If you have clicked a suspicious link, replied, shared information or approved an unexpected sign-in, seek advice promptly:

- [security-operations@brunel.ac.uk](mailto:security-operations@brunel.ac.uk)
- [studenthub@brunel.ac.uk](mailto:studenthub@brunel.ac.uk)

## Disclaimer

All emails shown are fictional educational examples, not genuine Brunel University communications. A message cannot be confirmed as safe from its appearance alone. When in doubt, verify through a trusted, independent channel.

## Organisation

Developed for **Brunel Cyber Security Society**.

- Society website: [brunelcs.org](https://brunelcs.org/)
- Game: [phishing.brunelcs.org](https://phishing.brunelcs.org/)
