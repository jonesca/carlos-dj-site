# DJ Carlos Website

A multi-page promotional website for DJ Carlos, featuring a hero landing page, interactive mixes player, and booking form.

## Live Repository

- GitHub: https://github.com/jonesca/carlos-dj-site

## Project Structure

- `index.html`: Home page with branding, call-to-action, and social links.
- `mixes.html`: Mix player page with playlist controls and an audio visualizer.
- `booking.html`: Booking form page wired to Formspree.
- `MusicMix/`: Local audio assets used by the mixes page.

## Features

- Responsive multi-page layout
- Animated UI and page transitions
- Custom audio player controls
- Audio unlock flow for mobile browsers
- Form submission via Formspree
- Social profile links and contact email in footer

## Run Locally

This is a static site, so no build tools are required.

1. Open the project folder.
2. Open `index.html` in your browser.

For best results (especially with media loading), run a local server:

```bash
python3 -m http.server 8080
```

Then visit:

- http://localhost:8080/index.html

## Configuration Notes

- Booking form endpoint is currently set in `booking.html`:
  - `https://formspree.io/f/maqkdlwq`
- Social links are placeholders and should be replaced with real profiles:
  - SoundCloud, Spotify, Instagram, YouTube
- Contact email currently used in page footer:
  - `carlos@djcarlosmusic.com`

## Deploy Options

This project can be deployed on any static host:

- GitHub Pages
- Netlify
- Vercel (static)

### Quick GitHub Pages Setup

1. In GitHub, open repository settings.
2. Go to Pages.
3. Set source to `Deploy from a branch`.
4. Choose branch `main` and folder `/ (root)`.
5. Save and wait for the site URL to be generated.

## License

No license has been added yet. If this is for public reuse, add a license file (for example, MIT).
