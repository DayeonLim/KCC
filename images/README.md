# 📸 Photos folder

Drop your photos in this folder using these exact file names, and they'll show up
automatically on the site (replacing the cute placeholder boxes).

## Board members group photo
- `board.jpg` — one group photo of all the board members (shown at the top of the team section)

## Event photos
- `westgate-2026.jpg`   — Fashion + Famous @ Westgate Center (Feb 15, 2026)
- `booth-2026.jpg`      — Multicultural Booth Faire (Jan 21, 2026)
- `rally-2025.jpg`      — Famous Performance @ Rally (Nov 18, 2025)
- `eta-rally-2025.jpg`  — ETA Performance @ Rally (Apr 24, 2025)
- `booth-2025.jpg`      — Multicultural Booth / Tteokkochi (Jan 22, 2025)
- `carnival-2024.jpg`   — Carnival dart game & snacks (Oct 10, 2024)

## How to add a photo to the page
For each photo, open `index.html`, find the matching placeholder block, e.g.:

```html
<div class="g-photo">
  <span class="ph-emoji">👗</span>
  <span class="ph-text">Add photo → images/westgate-2026.jpg</span>
</div>
```

and replace the inside with an image tag:

```html
<div class="g-photo">
  <img src="images/westgate-2026.jpg" alt="Fashion + Famous @ Westgate Center">
</div>
```

That's it! 💕
