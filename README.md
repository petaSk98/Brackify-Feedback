# Brackify — Community Testing Guide

Welcome! This repository is the place for **bug reports**, **feedback**, and **feature suggestions** for **Brackify** — a Reddit app for bracket-style voting tournaments.

Community testers like you play an important role in making Brackify better. Every bug you find and every idea you share helps improve the app for everyone. Thank you for being part of this!

---

## What is Brackify?

Brackify lets Reddit communities run bracket tournaments directly inside Reddit posts. An organizer sets up a tournament with images or text entries, the community votes in head-to-head matchups, and round by round a winner emerges.

---

## How to Test

No special setup is needed — just use the app as a regular Reddit user.

- **Use the app normally.** Vote in matchups, explore the bracket, check the ranking.
- **Try different scenarios.** Create your own tournament, submit entries in community mode, vote through multiple rounds.
- **Test on both mobile and desktop** if you can — the app can behave differently on each.
- **Try various actions:**
  - Voting in matchups
  - Navigating between matches
  - Switching between bracket view and ranking
  - Viewing competitor details
  - Sharing results
  - Submitting entries (when submissions are open to the community)
- **Try edge cases.** What happens if you tap things quickly? What if you go back and forth between screens?

---

## How to Report a Bug

Found something broken or unexpected? [Open an issue](../../issues/new) and include the following information:

### What to include in a bug report

- **Title** — A short description of the problem
- **Steps to reproduce** — What exactly did you do, step by step?
  1. I opened the tournament post
  2. I tapped on "Vote"
  3. I selected the left image
  4. ...
- **Expected behavior** — What should have happened?
- **Actual behavior** — What happened instead?
- **Platform** — Mobile (iOS / Android) or Desktop? Which browser?
- **Screenshot or screen recording** — If possible, attach one. A picture is worth a thousand words!

> **Tip:** The more specific you are, the faster we can find and fix the issue.

---

## How to Suggest a Feature

Have an idea for how Brackify could be better? We'd love to hear it!

- [Open an issue](../../issues/new) and describe your idea
- Explain **what problem it would solve** or **what it would improve**
- You don't need to be technical — just describe it in your own words
- Feel free to include sketches, examples, or references to other apps

---

## App Screens Overview

When reporting a bug or making a suggestion, it helps to mention **which screen** you're talking about. Here's a quick guide to the main parts of the app:

### Landing Page

The first screen you see when you open a tournament. It shows the tournament title, description, and cover image, along with a button to start voting.

### Setup Screens

The screens where a tournament organizer creates and configures a new tournament — setting a title, description, cover image, adding entries, and choosing rules. These are only visible to the person who created the tournament.

### Match Card

The core voting screen. Two competitors are shown side by side (or stacked on mobile). You pick your favorite by tapping on it. After voting, your choice is highlighted.

### Full Bracket View

A complete tournament bracket tree showing all matches across all rounds, connected by lines. You can pan and zoom to explore the entire bracket. Best experienced on desktop or larger screens.

### Compact Bracket View

A simplified, vertical bracket layout optimized for mobile devices. It shows the tournament progression in a scrollable, round-by-round format that's easy to follow on smaller screens.

### Matchup Detail

A popup that appears when you tap on a specific match in the bracket. It shows the two competitors, vote counts, and the result. You can navigate between matches using arrow buttons.

### Ranking

A leaderboard showing all competitors sorted by their performance and total votes. Useful for seeing how everyone did overall, not just who won.

### Competitor Detail Card

Appears when you tap on a competitor in the ranking view. Shows a larger image preview and detailed statistics for that competitor.

### Winner View

The final screen displayed when the tournament is complete. It celebrates the champion and offers options to share the result, view the full bracket, or explore the ranking.

---

## Navigation Tips

- **Arrow buttons** — Use the left/right arrow buttons to move between matches
- **Swipe** — On mobile, you can swipe to navigate between matches
- **Scroll** — On desktop, use scroll to explore the bracket or ranking
- **Tap a match in the bracket** — Opens the matchup detail with vote counts
- **Back button** — Returns you to the previous screen

---

## Quick Links

- [Report a bug](../../issues/new)
- [Suggest a feature](../../issues/new)
- [View all open issues](../../issues)

---

Thanks for testing Brackify! Your feedback makes a real difference.
