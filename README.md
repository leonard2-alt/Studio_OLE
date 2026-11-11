# Studio Orbit static website

Open `index.html` in a browser to view the site. The page uses only HTML and CSS; its illustrated cover art is made with CSS shapes, and it works offline without external assets.

## Replace the project links

In `index.html`, each project card has a clearly labeled placeholder link such as:

```html
<a class="text-link" href="https://example.com/replace-with-guardians-of-mali">
  Game link coming soon <span aria-hidden="true">↗</span>
</a>
```

Replace the `href` value with the actual game page, playable build, video, or animation URL. You can also change the visible link text from “Game link coming soon” or “Watch link coming soon” to “Play now” or “Watch animation”. Search `example.com/replace-with-` in `index.html` to find all six project placeholders.

The contact button uses `mailto:hello@example.com`; replace that address with the creator's preferred email. To personalize the page, edit the headings, descriptions, footer label, and CSS colors in `styles.css` (near the top under `:root`).

## Files

- `index.html` — page structure and project content
- `styles.css` — responsive layout, colors, typography, and CSS-only artwork
