# Woodward Academy Middle School: Confidential Student Reporting Form and Resources

A mobile-friendly web app that gives students topic resources, school contacts, crisis lines, and a link to the confidential reporting form.

The whole app is a single file: `index.html`. There is nothing to install or build.

## Updating content

Open `index.html` and search for these names near the top of the `<script>`:

| To change | Search for |
|---|---|
| Report form link | `FORM_URL` |
| Counselors / administrators | `PEOPLE` |
| Staff photos | `PHOTOS` |
| Crisis lines | `LINES` |
| Topic text and resource links | `TOPICS` |
| Colors and fonts | `BRAND TOKENS` (top of the file) |

## Hosting

Served with GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).

## Home-screen icon

`icon-180.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `icon-32.png`, and `manifest.webmanifest` make the app install with the red-and-black whistle/speech-bubble icon. Keep them in the same folder as `index.html`.
