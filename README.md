# Project Resonance: Graduation

A browser-based card game about making it through your final year.

## Overview

This is an early stage project exploring a roguelike deckbuilder where your resources are mood, energy, and social capital instead of health and mana. The setting is senior year, with classes, relationships, deadlines, and the occasional existential crisis, all filtered through turn based card play.

Right now the project consists of a single HTML file that runs entirely in your browser. No build tools, no dependencies, no setup. Just open the file and you're in.

## Getting Started

1. Clone or download the repository
2. Open `Project-Resonance-Graduation.html` in any modern browser
3. Click Start and see what happens

That's it. If you want to look under the hood, open the file in a text editor. The game logic lives in the `<script>` section. Changing a number, refreshing the page, and seeing the effect is the fastest way to learn how things connect.

## Current State

As of now, the project includes:

- A basic character selection screen with two placeholder characters (Jason and Aaron)
- Simple stat display: Mood, Energy, Responsibilities, Social
- Resource counters for deck, hand, discard pile, and currency
- A start screen and minimal UI scaffolding
- The beginnings of a turn structure

Nothing is finalized. The values are placeholders and the systems are incomplete. This is intentional, as the repository is meant to serve as a starting point rather than a polished product.

## How to Contribute

If you're new to the project, here are low-barrier ways to jump in:

- Play through what exists and note what feels confusing or broken
- Suggest card ideas, event scenarios, or character traits that fit the theme
- Tweak values in the HTML file to test balance or behavior
- Help structure the JavaScript into clearer functions or modules
- Add basic CSS to improve readability or visual feedback

You don't need deep experience to help. If you can read a little JavaScript or just have ideas about what makes a stressful semester feel engaging to play, your input matters.

## Technical Notes

- Built with plain HTML, CSS, and vanilla JavaScript
- No frameworks, no bundlers, no transpilation
- All game state is currently held in memory (no save system yet)
- Designed to be readable and editable without a build step

This simplicity is a feature, not a limitation. It keeps the barrier to entry low and makes experimentation fast.

## If You're Stuck

- Open the browser's developer console (F12) to see any errors or logged output
- Search the HTML file for keywords like "card", "turn", or "stat" to find relevant code
- Start small: change a displayed number, add a console.log, or adjust a starting value
- When in doubt, ask by opening an issue. No question is too basic.
