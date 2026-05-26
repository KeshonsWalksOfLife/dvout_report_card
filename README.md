# DVouT. — Academic Record

> *Working Craft, Chasing Purpose.*

A personal academic record built as an editorial-style web page — part report card, part manifesto. It tracks the journey toward **Summa Cum Laude** in the B.S. Software Development program at **Grand Canyon University**, where a cumulative GPA of **3.90 – 4.00** is the threshold for the institution's highest academic honor.

This page is the receipt of that pursuit: a living record of the discipline behind the dream.

---

## Live Preview

Open `HTML/report_card.html` directly in a browser, or serve the project root with any static server (e.g. VS Code Live Server, `python3 -m http.server`).

---

## What's Inside

| Section | What it shows |
| --- | --- |
| **Hero** | Brand mark, degree kicker, and the mission statement behind the goal. |
| **Student + GPA** | Name, institution, and the cumulative GPA tracker (`WIN. 3.77`). |
| **Degree Progress** | A slim progress bar showing courses completed vs. remaining. |
| **Current Courses** | The class currently in session. |
| **Scheduled Courses** | Upcoming courses with start / end dates and credits. |
| **Completed Courses** | The full transcript — every course with its final letter grade. |

Each panel is collapsible: click the `+` to expand, `−` to collapse.

---

## Project Structure

```
dvout_report_card/
├── HTML/
│   └── report_card.html      # Page markup
├── CSS/
│   └── report_card.css       # Editorial styling, dark theme + white hero
├── JS/
│   └── report_card.js        # Accordion toggle behavior
└── README.md
```

---

## Design Notes

- **Typography**: `Playfair Display` (serif, editorial weight) paired with `DM Sans` (clean modern body).
- **Palette**: Charcoal `#555` backdrop with a stark white hero panel — black-on-white headline against white-on-grey content, drawing the eye to the mission statement first.
- **Tone**: Closer to a literary magazine spread than a school portal. The goal is to make the academic record feel *intentional*, not transactional.

---

## Credits

Designed and built by **Keshon D. Bowman** — *DVouT.*
Grand Canyon University · B.S. Software Development.

*Keep Walking, Friends.*
