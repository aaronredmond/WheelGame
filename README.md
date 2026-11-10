# WheelGame

A random wheel spinner that runs in the browser. Put your own options on the wheel, or use a number range, then spin to pick a winner.

No build step and no dependencies: plain HTML, CSS and JavaScript.

## Running it

Open `index.html` in a browser. To serve it locally instead:

```sh
python3 -m http.server
```

Then visit http://localhost:8000.

## Features

- **Two wheel types:** a custom list of up to 50 spokes, or a number range (with a minimum and maximum).
- **Weighted spokes:** give each spoke a weight so bigger slices are more likely to win.
- **Remove winner after each spin:** useful for drawing without repeats.
- **Paste a list:** replace the spokes with one item per line, or fill them with 1…N.
- **Spin history:** the most recent results are shown under the wheel.
- **Sound effects and confetti:** sound can be switched off. Reduced-motion preferences are respected.
- **Appearance:** five colour schemes (Rainbow, Pastel, Ocean, Sunset, Forest), hand-picked colours per spoke, and several wheel sizes including "Fit screen".
- **Saved settings:** your wheel and options are stored in the browser's `localStorage`.

## Controls

- Click **Spin!** or press the **Space bar** to spin.
- Use the gear button to show or hide the settings panel.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Page structure and settings panel |
| `script.js` | Wheel drawing, spin logic, settings and persistence |
| `styles.css` | Styling |
