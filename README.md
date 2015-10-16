# Files

PNGCrush-compressed.htm	- 292 kilobytes - JavaScript minified, then compressed with deflate
PNGCrush-no.minify-compressed.htm - 376 kilobytes - entire page compressed with deflate, no minify
PNGCrush-uncompressed.htm - 2,100 kilobytes (2.04 megabytes) - the original HTML web app before compress/minify

# About

Here we took the original 2,200 kilobyte bytecode file (C++ compiled with emscripten), minified the JavaScript (separated from HTML) and page to 990 KB, and then compressed to 290 KB.

Without JavaScript minifying, we can get the original file (2,200 KB) to 385KB compressed just with deflate (82% removed) by simply drag/drop entire web page and then pushing the "Compress HTML" button (save as HTM).

# Deflater

These are just samples created to demonstrate compression achieved. www.whak.ca/deflate.htm creates a self extracting JavaScript/HTML archive that will automatically decompress and execute client side VIA HTML5 web browser. The built in decompressor (auto extractor uncompresses compressed data) is 5KB.
