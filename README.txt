# WonderLab Studio Website

A responsive single-page website built with plain HTML, CSS and JavaScript.

## Files
- index.html — page structure/content
- style.css — complete visual design/responsive layout
- script.js — menu, scroll reveal, counters, modal and small interactions
- assets/wonderlab-logo.png — your supplied WonderLab Studio logo

## Replace your images/videos
The portfolio cards intentionally use CSS placeholders so you can replace them with your original work.

### Easiest image replacement
In `index.html`, find:
`<div class="work-media placeholder p1">`
and replace the contents with:
`<img src="assets/your-image.jpg" alt="Project name">`

Then add this to `style.css`:
`.work-media img{width:100%;height:100%;object-fit:cover;display:block}`

You can also replace the hero showreel placeholder with a YouTube/Vimeo iframe or an MP4 `<video>`.

## Contact
The template uses:
- Email: wonderlabstudio.lk@gmail.com
- WhatsApp: +94 76 980 1157

Change these in `index.html` if needed.

## Run locally
Double-click `index.html`, or use VS Code Live Server.

## Deployment
The folder can be uploaded to any normal static web host. It can also be adapted into a Blogger/WordPress page later.
