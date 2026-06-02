<div align="center">

# Text Counter

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://soumendrak.github.io/text-counter/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success?style=flat-square)](https://www.w3.org/TR/html52/)

<!-- Inline SVG logo -->
<svg width="140" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg">
<rect width="140" height="140" rx="24" fill="#0a0a14"/>
  <text x="70" y="40" text-anchor="middle" font-family="monospace" font-size="26" font-weight="bold" fill="#ff6b35">42</text>
  <text x="70" y="54" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#8a8a9a">characters</text>
  <rect x="30" y="70" width="80" height="4" rx="2" fill="#1a1a2e"/>
  <rect x="30" y="70" width="40" height="4" rx="2" fill="#ff6b35"/>
  <text x="70" y="90" text-anchor="middle" font-family="sans-serif" font-size="7" fill="#5a5a6e">twitter: 42/280</text>
  <rect x="30" y="100" width="80" height="4" rx="2" fill="#1a1a2e"/>
  <rect x="30" y="100" width="12" height="4" rx="2" fill="#4caf7d"/>
  <text x="70" y="120" text-anchor="middle" font-family="sans-serif" font-size="7" fill="#5a5a6e">sms: 42/160</text>
</svg>

**Real-time character, word, sentence, paragraph, and reading-time counter.**

**Live:** [https://soumendrak.github.io/text-counter/](https://soumendrak.github.io/text-counter/)

</div>

---

## Features

- Real-time: characters (with/without spaces), words, sentences, paragraphs, lines
- Reading time at 238 words per minute
- Speaking time at 183 words per minute
- Twitter/X (280) and SMS (160) limit progress bars
- Top 5 most frequent characters bar chart
- Clear button and Paste from clipboard button
- Dark theme with orange accent (#ff6b35)

## How It Works

Every keystroke triggers a counter recalculation. `text.split()` regex patterns count words, sentences (by `. ! ?`), and paragraphs (by double newline). Reading time = wordCount / 238, speaking time = wordCount / 183. Frequency analysis builds a character map from the input and displays the top 5 as horizontal bar segments.

## Usage

1. Open `https://soumendrak.github.io/text-counter/` in any browser.
2. No build step, no installation, no server required.
3. Deploy anywhere — GitHub Pages, Netlify, or any static host.

```bash
git clone https://github.com/soumendrak/text-counter.git
# Open index.html directly
```

## License

Licensed under the [MIT License](LICENSE).

---

<p align="center"><sub>Built with ❤️ and zero dependencies</sub></p>
