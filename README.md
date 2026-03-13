# Number & Symbol Typing Trainer

A simple browser-based typing practice app focused on the **number row** and its **shifted special characters**.

This goofy tool is meant to help build muscle memory for the part of the keyboard that often gets ignored in regular typing practice.

## Features

- **Easy mode** with a small rotating set of neighboring keys
- **Numbers only** mode
- **Symbols only** mode
- **Combined** numbers and symbols mode
- **30 / 60 / 120 second** timed drills
- Live **WPM**
- Live **accuracy**
- **Correct / incorrect** tracking
- **Current streak** and **best streak**
- Simple **single-file HTML** app
- Easy to host

## Why this exists

There we were in a group call waiting for Manny to plug in a cable on a switch when this glorious idea came to fruition. Most typing trainers focus heavily on letters and words. This app is designed specifically to help practice:

- `1 2 3 4 5 6 7 8 9 0`
- `! @ # $ % ^ & * ( )`

That makes it useful for people who want better speed and confidence when entering:

- passwords
- IDs
- codes
- ticket numbers
- commands
- symbols used in technical work

## Modes

### Easy
Starts with a smaller group of nearby number-row keys and their shifted symbols, such as:

- `1 2 ! @`
- `3 4 # $`
- `5 6 % ^`

This is the best place to start if the full row feels too chaotic.

### Numbers only
Practices just:

`1234567890`

### Symbols only
Practices just:

`!@#$%^&*()`

### Both
Mixes the number row and shifted symbols together.

## How to use

1. Open the app in your browser.
2. Click inside the typing box.
3. Type the highlighted character sequence exactly as shown.
4. Watch your stats update live.
5. Restart anytime or switch modes and timer length.

## GitHub Pages setup

This project is designed to run as a **single `index.html` file**, so there is no build step.

### Publish on GitHub Pages

1. Create a new GitHub repository
2. Add the file as `index.html`
3. Commit it to the `main` branch
4. Go to **Settings**
5. Open **Pages**
6. Under **Build and deployment**:
   - set **Source** to `Deploy from a branch`
   - choose **main**
   - choose **/(root)**
7. Save

After GitHub finishes publishing, your site will be available at:

```text
https://YOUR-USERNAME.github.io/REPO-NAME/
