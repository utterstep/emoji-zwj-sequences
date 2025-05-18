# Emoji ZWJ Sequences Mirror

This repository is a simple mirror for [Unicode.org's Emoji ZWJ Sequences page](https://unicode.org/emoji/charts/emoji-zwj-sequences.html).

## Why this mirror exists

This mirror was created because unicode.org throttles downloads to approximately 10KB/s after about 1MB of data is downloaded. Since the original page is almost 30MB in size, this makes accessing the content very slow.

## Download command

If you want to create your own mirror, you can use:

```bash
wget -O index.html https://unicode.org/emoji/charts/emoji-zwj-sequences.html
```