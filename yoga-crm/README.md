# Lotus Studio — Yoga CRM

A static, multi-page CRM mockup for managing a yoga studio. Built with plain HTML and CSS — no build step, no JavaScript, no dependencies.

## Pages

- **`index.html`** — Dashboard with key stats (active members, weekly classes, sign-ups, revenue), today's class list, and a recent-activity feed.
- **`clients.html`** — Filterable client roster with membership type, last visit, total classes, and status badges.
- **`classes.html`** — Card grid of class offerings (Vinyasa, Hatha, Yin, Meditation, Workshops) with lead instructor and frequency.
- **`schedule.html`** — Weekly grid showing sessions placed across days and time slots.

## Design

- **Palette** — warm cream background (`#f5f1ea`), sage green primary (`#8aa68b`), soft terracotta accent (`#c89b7b`).
- **Typography** — Cormorant Garamond (serif) for headings, Inter / system sans for body.
- **Feel** — generous whitespace, soft 14px radii, subtle shadows. Aimed at a quiet, considered tone rather than a dense admin look.
- **Icons** — inline SVG, no icon font.
- **Responsive** — collapses to a single column on narrow screens.

## Running it

Open `index.html` directly in a browser. That's it.

If you want to serve it locally instead:

```sh
# from inside the yoga-crm/ folder
python -m http.server 8000
# then open http://localhost:8000
```

## Structure

```
yoga-crm/
├── index.html        # Dashboard
├── clients.html      # Client roster
├── classes.html      # Class catalog
├── schedule.html     # Weekly schedule
├── styles.css        # Shared styles
└── README.md
```

All pages share `styles.css` and an identical sidebar. The data shown is illustrative placeholder content.
