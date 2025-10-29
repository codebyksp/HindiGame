# Bollywood Escape Room

A very basic creative project made for fun as part of a Hindi language course. The goal was to practice both **Hindi vocabulary and grammar** while also experimenting with **HTML, CSS, and JavaScript**.

This was made quickly and is intentionally simple—just a playful way to merge language learning with coding practice.

Check it out here: https://codebyksp.github.io/HindiGame/

## About the Game

* The player is “trapped” in a Bollywood studio and must answer Hindi-related challenges to escape.
* Challenges include translation, fill-in-the-blank, and film trivia about Bollywood.
* Feedback is shown in real time, and you can type answers or `skip` to move on.
* Some visual cues and GIFs change dynamically throughout the game.

## Features

* Built entirely with vanilla **HTML**, **CSS**, and **JavaScript** (no frameworks).
* Includes a **typed text effect** for interactive storytelling.
* Uses **basic DOM manipulation** for input validation and response flow.
* Hindi text and translation exercises reinforce vocabulary learned in class.
* Responsive enough to work in most browsers without external dependencies.

## Technical Notes

* All GIFs are loaded from a local `/static/` directory.
* The “typed print” animation uses recursive timeouts instead of any external typing library.
* Each challenge is implemented as a standalone function (`question1`, `question2`, etc.) connected through callbacks for sequential flow.
* The GIF transition uses a simple **cross-fade** implemented with CSS opacity and JavaScript timing.
* There’s no backend—everything runs client-side in the browser.

## Future Improvements (if I ever revisit)

* Add more levels or randomized challenges.
* Store player progress locally using `localStorage`.
* Replace manual timeouts with a cleaner **state management** system.
* Improve visuals with smoother transitions and mobile optimization.
* Add sound effects or background music for immersion.
* Support Devanagari input for Hindi answers instead of only transliteration.

## How to Run

1. Clone or download this repository.
2. Open `index.html` directly in your browser.
3. Make sure your `static/` folder contains the referenced GIFs (`deewar.gif`, `3idiots.gif`, `best.gif`, etc.).

## Notes

* This project was created quickly for a language class assignment and personal experimentation.
* It’s intentionally minimal, focused more on learning than design polish.
* Best experienced on a desktop browser.
