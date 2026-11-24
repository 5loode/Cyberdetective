# 🕵️ Cyber Detective: Spot the Threat

A beginner-friendly cybersecurity awareness game. Study the evidence in each case, choose the safest response, and learn why.

**Live demo:** https://jade-crisp-7f1d26.netlify.app/
**GitHub Pages:** https://5loode.github.io/cyber-detective/

## About
Phishing, scam calls and fake attachments are the most common ways people get hacked. This game trains players to spot the warning signs in a safe, fun way.

## Features
- 5 realistic cases: phishing email, CEO gift-card text, unknown USB drive, fake IT support call, malicious invoice attachment
- 30-second countdown timer for each case
- Optional hints (a hint halves the points for that case)
- Clear explanation after every answer
- Score, rank and total time on the results screen
- Blue theme, responsive layout, keyboard and screen-reader friendly

## Scoring
| Result | Points |
|---|---|
| Correct answer | 20 |
| Correct answer with a hint | 10 |
| Wrong answer or time runs out | 0 |

Maximum score: 100.

## Run it locally
No installation needed. Download this repository and open `index.html` in a browser.

## Add your own cases
Open `index.html`, find the `CASES` array, and add a new entry with a title, type, evidence, hint and four options (mark the correct one with `ok: true`).

## Built with
HTML, CSS and vanilla JavaScript in a single file. No frameworks or dependencies.

## Author
Built by [5loode](https://github.com/5loode).
