# Cycle of Change (易数周期)

Cycle of Change is a modern, client-facing reflection tool inspired by the **Yijing (I Ching / Book of Changes)**.
It transforms two clean inputs, your birthday and today’s date, into a deterministic daily reading that feels poetic, structured, and actionable.

## Based on the Yijing Book

This project is based on the 64-hexagram framework from the **Yijing (Book of Changes / 周易)**.
The app maps date-derived numbers to a hexagram-style result and provides contemporary interpretation prompts for daily reflection.

## What Clients Get

- Simple input flow: birthday + today
- Daily hexagram-style result (1-64)
- Momentum and stability indicators
- Yin/Yang balance and change-line mechanic
- Two-page prediction experience:
  - Page 1: Core reading
  - Page 2: Guidance (lucky number, color, element, time block, action cue, avoid pattern)
- Daily streak tracking
- Shareable output for social or journaling use

## How It Works (Deterministic)

- `Life Number = sum of birthday digits`
- `Today Number = sum of today’s digits`
- `Hexagram Number = (Life Number × Today Number) mod 64`
- If the result is `0`, it maps to `64`
- Prime-day rule: if `Today Number` is prime, one line flips

This is a **pattern-based reflection system**, not a claim of supernatural prediction.

## Tech

- Single-file web app (`index.html`)
- HTML, CSS, Vanilla JavaScript
- GitHub Pages friendly (no build step required)

## Who It Is For

Cycle of Change is especially for people who love fortune-telling style rituals, but want something clean, structured, and easy to trust.

- Fortune-telling lovers who enjoy daily guidance
- People who want a quick personal reflection ritual
- Journalers who like prompts tied to meaningful patterns
- Creators building poetic, philosophy-inspired wellness tools

## Disclaimer

Cycle of Change is inspired by the Yijing and designed for reflection and self-inquiry.
It does **not** claim to predict the future, guarantee outcomes, or provide medical, legal, or financial advice.

## Original Book PDF

For clients who want to explore the source material directly, the original reference PDF is available in the repo.
