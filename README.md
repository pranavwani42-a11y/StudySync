# StudySync 📚

StudySync is a simple, responsive student productivity web app that brings study tasks, notes, practice quizzes, focus sessions, and exam planning together in one dashboard.

## Features

- **Task checklist:** Add and complete study tasks and track progress.
- **Notes:** Write and save study notes in your browser.
- **Practice quiz generator:** Paste study text and generate fill-in-the-blank questions using a rule-based JavaScript approach.
- **Focus timer:** Run focused study sessions.
- **Exam planner:** Keep exam dates visible while planning revision.
- **Progress overview:** See task completion and study-session information.
- **Responsive layout:** Use the app on desktop or mobile-sized screens.

## Tech stack

- **HTML** — page structure
- **CSS** — styling and responsive layout
- **JavaScript** — interactive features
- **Browser localStorage** — saves supported notes and app data locally in the current browser

## Run locally

No build tools or package installation are required.

1. Clone or download this repository.
   ```bash
   git clone https://github.com/pranavwani42-a11y/StudySync.git
   ```
2. Open the `index.html` file in a modern web browser.

## Deploy with GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/(root)` folder, then save.
5. After GitHub Pages finishes publishing, open the site URL shown in the Pages settings. The expected URL for this repository is:

   https://pranavwani42-a11y.github.io/StudySync/

The URL will work only after GitHub Pages has been enabled and the deployment has completed.

## Data and limitations

- This is a lightweight front-end prototype; it does not currently require a server or user account.
- Data saved with `localStorage` stays in that browser on that device. It does not automatically sync across devices or browsers.
- The quiz generator is rule-based JavaScript, **not an AI-powered quiz generator**.
- Clearing browser storage may remove locally saved app data.
- Features such as accounts, cloud synchronization, reminders, and AI-generated quizzes could be added in future versions.

## Future improvements

- AI-assisted quiz and flashcard generation
- User accounts and cloud sync
- Assignment reminders and notifications
- Shared notes and study groups
- More detailed study analytics

## Project purpose

StudySync aims to help students organize their academic workload, revise more actively, and build consistent study habits through one approachable dashboard.

## Repository

https://github.com/pranavwani42-a11y/StudySync
