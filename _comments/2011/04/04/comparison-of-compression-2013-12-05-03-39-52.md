---
date: '2013-12-05 03:39:52'
link: ''
name: Robert Ruedisueli
post_id: /2011/04/04/comparison-of-compression
---

I recommend 7z, it uses LZMA algorithm, but adds checksums and archiving capabilities.   This adds a little to the overhead, but saves you from having to use tar for archinving, and gives you the reliability of built-in checksums.

As for single files that you don't need checksums on, I recommend LZMA.

As a note, many of these algorithms you can push further with command line options that most archivers use the default options.  This is because, the higher-compression options can take exponentially longer and use more computer resources for only a small gain, and some of them can be very memory and/or processor intensive to decompress.