# About

Here we took the original bytecode file (C++ compiled with emscripten), minified the JavaScript (separated from HTML) and page to 990 KB, and then compressed to 250 KB. Without JavaScript minifying, we can get the original file to 385KB compressed just with deflate (82% removed).

# Deflater
Just samples to demonstrate compression. www.whak.ca/deflater.htm creates a self extracting JavaScript/HTML archive that will automatically decompress and execute client side VIA HTML5 web browser. The built in decompressor (auto extractor uncompresses compressed data) is 5KB.
