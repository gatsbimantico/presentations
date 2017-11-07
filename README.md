# PRESENTATIONS

This repo makes use of
https://github.com/hakimel/reveal.js/
to generate presentations.

The repo contains three elements:

- `/index.html` : An index of the presentations on this project.

- `/viewer.html` : A `slides` loader and viewer, is where `reveal.js` is loaded.<br><br>
With a hash and a name e.g. `#state-of-js` the sides in `/slides/state-of-js.html` will be loaded.<br><br>
If the hash starts with `http...` and contains an `encodeURIComponent` URL, it will load the slides on that url instead, e.g. for development serving on port 5000, `http://localhost:5000/viewer.html#http%3A%2F%2Flocalhost%3A5000%2Fslides%2Fnew-presentation.html`

- `/slides/*.html` : Each presentation hosted on this github project.
