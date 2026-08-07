# Club BCD

Website for **Club BCD – Brazoria County Diving Club**, a family-friendly scuba diving group that meets the second Saturday of each month at Mammoth Lake, Lake Jackson, Texas.

## Pages

| Page | Description |
| --- | --- |
| [`index.html`](index.html) | Home page – meeting info, club purpose, rules, and contact links |
| [`calendar.html`](calendar.html) | 2026 events calendar with monthly dive days |
| [`cardgenerator.html`](cardgenerator.html) | Card Designer – build a printable diver info card with emergency contacts, up to 12 scuba certifications, a profile photo, and custom front/back backgrounds |

## Features

- Modern Tailwind CSS design (via the Play CDN – requires internet)
- Responsive layout with a sticky navigation bar
- Card Designer input validation: required fields, phone number (7–15 digits, 15-char max), and image upload checks (image files only, max 8 MB)
- Print / Save PDF and Save JPG (front/back) export from the Card Designer
- Footer links to this source repository

## Usage

Serve the files from any static web server or open them directly in a browser:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

The pages rely on these CDNs, so an internet connection is needed:
- `https://cdn.tailwindcss.com` (Tailwind CSS)
- Google Fonts (Inter)
- `https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js` (JPG export)

## Project files

- `Banner.png` – site banner
- `Stamp.png` – club stamp image

## License

Licensed under the [GNU General Public License v3.0](LICENSE). See the [LICENSE](LICENSE) file for details.

© 2026 Club BCD – Brazoria County Diving Club



tails1154 was here
