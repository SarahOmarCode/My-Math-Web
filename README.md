# Omar Math: Math Learning Website

A multi-page website for learning math. Visitors sign up, take a placement quiz, and unlock a learning hub once they pass.

**▶ [Open the live demo](https://sarahomarcode.github.io/My-Math-Web/)**

![Landing page](./frontpagephoto.png)

## User flow

1. **Landing page** (`index.html`): the visitor enters a name and email. The form is sent with [EmailJS](https://www.emailjs.com/), so there's no backend to run.
2. **Math quiz** (`mathQuiz.html`): 10 multiple-choice questions on arithmetic, percentages, basic algebra and area, with instant feedback and a final score.
3. **Learning hub** (`mainPage.html`): unlocked when you score 50% or more. It links to sections for games, videos, PDFs, practice tests, progress tracking and help.

![Math quiz](./mathquizphoto.png)
![Learning hub](./mainpagephoto.png)

## Run locally

No build step. Clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/SarahOmarCode/My-Math-Web.git
```

## Tech

HTML · CSS · JavaScript · EmailJS

## Status

The landing page, quiz and hub navigation work. The individual hub sections (games, videos, PDFs, tests, tracker) are placeholder pages.

---

*An early project from 2023, built while learning front-end development.*
