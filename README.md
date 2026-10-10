# break-beat-bytes

A library of **1,230 classic funk / soul / breakbeat drum breaks** as `.wav` files,
packaged for use with [Strudel](https://strudel.cc) (and anything else that can load a
`strudel.json` sample map).

## Use in Strudel

```js
samples('github:catherinezetadrones-stack/break-beat-bytes')

// then play any break by its slug name:
s('amen_brother')          // example slug
s('funky_drummer').slice(8, '0 1 2 3 4 5 6 7')
```

Sample names are ASCII slugs derived from the original track names, e.g.
`20th Century Steel Band - Hot Pants` becomes `20th_century_steel_band_hot_pants`.
The full slug -> original-name map is in [`namemap.json`](namemap.json); the machine
map Strudel reads is [`strudel.json`](strudel.json). Breaks load lazily -- only the ones
you actually play are fetched.

## Source and attribution

Mirrored from the **"Breaks & Drum Loops Collection"** by *Unoriginal Entity* on the
Internet Archive (uploaded 2022-08-14):

> https://archive.org/details/breaks-and-drum-loops-collection

## License

Licensed under **Creative Commons Attribution-NonCommercial 4.0 International
(CC BY-NC 4.0)** -- see [`LICENSE`](LICENSE). You may share and adapt these for
**non-commercial** purposes with attribution.

**Note:** these breaks are sampled fragments of previously released musical works. The
CC BY-NC license covers this compiled collection; it does not clear the underlying
recordings. For any **commercial** use you must contact the respective rights holders.
This repo exists for personal, non-commercial experimentation.
