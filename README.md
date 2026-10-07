# DJ Portfolio

Hosted case study pages for the portfolio. Each page is a self-contained folder served by GitHub Pages, and Readymag shows it through a small loader block. Push a change here and the live Readymag page updates on its own, no edits in Readymag.

## Pages

| Page | Live URL | Readymag loader |
| --- | --- | --- |
| Follow Your Ears (Froot Loops) | https://manicpixiedigifairy.github.io/dj-portfolio/follow-your-ears/ | `loader/readymag-follow-your-ears.html` |

## How it works

1. `follow-your-ears/index.html` is the full page. Its images and GIFs live in `follow-your-ears/assets/`.
2. GitHub Pages publishes the `main` branch, usually within a minute of a push.
3. The Readymag Code widget holds the loader block. It opens the published page full screen and adds a timestamp to the address, so visitors always get the newest version.

## Set up in Readymag (one time)

1. Open the Readymag page for the case study and add a **Code** widget.
2. Paste the contents of `loader/readymag-follow-your-ears.html` into **Widget Code**. Leave **Use iFrame** off.
3. Check it in **Preview** (the Editor may not render custom code).
4. Publish.

Readymag's Free plan only accepts plain `<iframe>` code. On that plan, paste just the `<iframe ...></iframe>` line and size the widget to fill the page.

## Update a page

Edit the files in the page folder, commit and push to `main`. The live page refreshes on the next visit.
