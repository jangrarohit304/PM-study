# Repository Context

## What This Repository Does

This repository contains a browser-based Memory (Concentration) game. Players reveal cards two at a time and try to find every matching pair. The game offers 4x4 and 6x6 boards, shuffles the symbols for each game, and tracks elapsed time and moves. It also provides a star rating and saves recent high scores in the browser's local storage.

The interface is responsive and includes keyboard access and ARIA labels. The game runs entirely in the browser and has no external dependencies or build step.

## Purpose and Name

The README describes the project as a teaching example for students learning AI with "GHCP" in VS Code. In that context, GHCP appears to refer to GitHub Copilot, although the repository does not explicitly spell out the acronym.

The game itself does not call an AI model or require GitHub Copilot to run. It is a small, approachable web application that can serve as a project for learning about AI-assisted development in VS Code.

## Implementation

The application is implemented in `memory-game.html`, which contains the page markup, styling, and JavaScript game logic. The JavaScript manages the game state, creates and shuffles cards, checks matches and wins, updates the timer and rating, and stores scores with `localStorage`.

## Running the Game

Open `memory-game.html` directly in a browser. For local HTTP serving, run `python3 -m http.server 8000` from the repository directory and visit `http://localhost:8000/memory-game.html`.
