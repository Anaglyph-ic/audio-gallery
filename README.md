# Anaverse audioguided gallery example

You can explore this gallery live [here](https://anaver.se/?gallery=1&galc=KT1NesjBBrgx1iDneL4FVDVcgjQei2ZPo2wi&galid=21).

Your gallery.json file will necessarily be different from the one in this repository. What you need to do to enable the anaverse to discover the audioguide is add a field as follows:

```js
 "audioguide": { "mainTrack": "audioguide.mp3" },
```

Please use either audioguides you recorded yourself, or soundtracks you have a right to use. You can also use generative music from [this notebook](https://observablehq.com/@anaglyph-ic/rami-radio) using a browser sound recording extension.
