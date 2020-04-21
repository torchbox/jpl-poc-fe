# JPL headess front-end 

Simplest possible POC, using Vue.js to present the Wagtail API.

## Minimise Tachyons filesize

1. Install purgecss: `npm i -g purgecss`
2. `purgecss --css tachyons.min.css --content index.html --output shrunk/`
