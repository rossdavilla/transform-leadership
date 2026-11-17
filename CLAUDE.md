# The 4 I's of Transformational Leadership (`transform-leadership`)

An interactive page for **PSY170** (I/O Psychology) at UC Merced: students pick one of the four
I's — Idealized Influence, Inspirational Motivation, Intellectual Stimulation, Individualized
Consideration — to see what the trait means and a well-known leader who shows it.
Live at <https://rossdavilla.github.io/transform-leadership/>.

## Layout

```
index.html                       the whole page — HTML, CSS and JS in one file, no build step
img/idealized-influence.png      one illustration per trait
img/inspirational-motivation.png
img/intellectual-stimulation.png
img/individualized-consideration.png
img/<Leader Name>.jpg|webp|avif  the leader portraits, named after the person
```

## Things to know

- **Leader portraits are named after the person** (`Howard Schultz.jpg`, `Whitney Wolfe.jpg`,
  `Sam Altman.webp`, `Scott Galloway.avif`) and the file names carry spaces, so URLs need `%20`.
  Mixed formats are fine — match whatever the source image was.
- The leaders are the part that dates. When swapping one, change the portrait, the file name and
  the text together, and keep the example a well-known figure who genuinely illustrates that
  trait.
- Nothing is collected: no backend, no analytics, no storage.
- It runs on students' phones in class, so check the layout at phone width.

## Publishing

GitHub Pages serves `main` from the repository root, so a push to `main` is the deploy. Already
listed in `data/sites.json` in the
[`rossdavilla.github.io`](https://github.com/rossdavilla/rossdavilla.github.io) repo under the
`PSY170` tag.
