# About

Here we took the original 2,200 kilobyte bytecode file (C++ compiled with emscripten), minified the JavaScript (separated from HTML) and page to 990 KB, and then compressed to 290 KB.

Without JavaScript minifying, we can get the original file (2,200 KB) to 385KB compressed just with deflate (82% removed) by simply drag/drop entire web page and then pushing the "Compress HTML" button (save as HTM).

# Deflater
Just samples to demonstrate compression. www.whak.ca/deflate.htm creates a self extracting JavaScript/HTML archive that will automatically decompress and execute client side VIA HTML5 web browser. The built in decompressor (auto extractor uncompresses compressed data) is 5KB.
