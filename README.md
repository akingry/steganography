# Kingry Tools: Steganography Web App

A browser-based tool to hide compressed and optionally encrypted text inside images via LSB pixel manipulation.

- HTML5, CSS3
- Vanilla JavaScript
- LZ-String compression
- Canvas API

## Versions
- KTSteg.html encodes plain text
- KTStegRich.html encodes formatted text and images

## Features

- LZ-String compression
- Optional XOR + Base64 encryption
- Drag-and-drop or manual file selection
- Byte-size estimation and limit enforcement
- Input: .jpg, .jpeg, .png, .gif, .webp, .bmp, .tif, .tiff
- Output: .png
- Data written to least significant bits of RGB channels
- Full client-side

## License

MIT License
