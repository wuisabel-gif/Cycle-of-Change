# Cycle of Change (變化之道)

Cycle of Change is a client-facing reflection tool inspired by the **Yijing (I Ching / Book of Changes)**, presented in a Chinese **fengshui** visual style. It transforms two clean inputs — your birthday and today's date — into a deterministic daily reading that feels poetic, structured, and grounded in the authentic 64-hexagram tradition.

## Based on the Yijing Book

This project draws on the 64-hexagram framework of the **Yijing (Book of Changes / 周易)**. Each reading uses the **authentic King Wen sequence**: real Chinese hexagram names, the true trigram composition, and faithfully condensed **Judgment (卦辭)** and **Image (象辭)** text after the Wilhelm / Baynes translation.

## Features

### The reading
- **Authentic hexagram figures** drawn from the real King Wen line patterns, with bottom-up line numbering (Line 1 = bottom, as in the tradition)
- **Chinese name + pinyin** for every hexagram (e.g. 乾 Qián, 咸 Xián)
- **Judgment (卦辭) and Image (象辭)** classical text for all 64 hexagrams
- **Bagua trigram breakdown** — upper/lower trigram with its nature symbol (天 澤 火 雷 風 水 山 地), five-element phase, and fengshui direction
- **Relating (future) hexagram (之卦)** — when a line is changing, a `今 Present → 之 Relating` panel shows the transformation with a line-morph animation
- **Momentum, stability, and Yin/Yang balance** indicators
- **Guidance page** — lucky number, Chinese lucky color (with swatch), active element, and best time block (時辰)

### Wu Xing & symbols
- **Five-element compass (五行)** highlighting the active element and its direction
- **Stacked nature-symbol emblem** rendering the Image as upper-nature over lower-nature (e.g. 水 over 地)

### Ritual & interaction
- **Three-coin casting animation** echoing the traditional divination method
- **Paper-unfold opening animation** — the scroll unrolls when the page loads
- **Question / Intention field** to focus a reading
- **Reading journal (卷宗)** — your past casts (date, hexagram, question) saved locally, with a clear option
- **Daily streak** tracking
- **Day / Night mode** — a ☯ toggle swaps to a dark ink-and-gold palette (preference is remembered)
- **Shareable output** for social or journaling use

## How It Works (Deterministic)

- `Life Number = sum of birthday digits`
- `Today Number = sum of today's digits`
- `Hexagram Number = (Life Number × Today Number) mod 64` (a `0` maps to `64`)
- The figure for that number uses its **authentic King Wen trigram pattern**
- Prime-day rule: if `Today Number` is prime, one line becomes a **changing line**, producing the relating hexagram

This is a **pattern-based reflection system**, not a claim of supernatural prediction.

## Tech

- Single-file web app (`index.html`)
- HTML, CSS, Vanilla JavaScript — no build step, no dependencies
- Web fonts (Ma Shan Zheng, Noto Serif SC, Cinzel) for calligraphic styling
- State persisted in `localStorage` (streak, journal, theme)
- GitHub Pages friendly

## Who It Is For

- Fortune-telling lovers who enjoy a daily ritual
- People who want a quick, structured personal reflection
- Journalers who like prompts tied to meaningful patterns
- Anyone drawn to the Yijing and Chinese fengshui aesthetics

## Disclaimer

Cycle of Change is inspired by the Yijing and designed for reflection and self-inquiry. It does **not** claim to predict the future, guarantee outcomes, or provide medical, legal, or financial advice.

## Original Book PDF

For those who want to explore the source material directly, the original reference PDF (`Yijing.pdf`) is available in the repo.
