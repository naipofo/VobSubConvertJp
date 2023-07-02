# VobSubConvertJp
[![Open in colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/naipofo/VobSubConvertJp/blob/main/VobSubConvertJp.ipynb)

This notebook will convert your japanese VobSub subtitles (`.idx` + `.sub`) to conventional text subtitles (SubStation Alpha). You might need text subtitles
to adjust subtitle style to your preferences or for automatic dictionary lookup and flashcard creation.

This will also work with subtitles in `.sup` format. You can convert them to a `.idx` + `.sub` combo with [`bdsup2subpp`](https://github.com/mjuhasz/BDSup2Sub).

This notebook uses [`manga-ocr`](https://github.com/kha-white/manga-ocr) for character recognition, [`vobsub2png`](https://github.com/emk/subtitles-rs/blob/master/vobsub2png/README.md)
to parse the VobSub Subtitle format, and [`pysubs2`](https://github.com/tkarabela/pysubs2) to create text subtitles.

This notebook is not perfect; it has problems with mixed vertical and horizontal text, italics, and sometimes it ignores opening parentheses but it's still a lot better than existing software.
