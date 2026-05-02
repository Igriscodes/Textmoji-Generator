# Textmoji Generator

A lightweight, browser-based utility that transforms standard images into vibrant **Full Color ASCII** art or intricate **Braille (Unicode)** patterns.

<img width="297" height="632" alt="demo" src="https://github.com/user-attachments/assets/7ae998f1-a782-4ab9-9e3e-06fcb4d2ea4c" />

## Features

*   **Dual Rendering Modes**:
    *   **Full Color ASCII**: Uses a 70-character density map with inline CSS coloring to replicate your image's original palette.
    *   **Braille (Dots)**: Utilizes 2x4 Unicode Braille patterns for high-density, monochrome representations.
*   **Real-time Controls**: 
    *   Adjust resolution (width) on the fly.
    *   Fine-tune Braille output with a "Dot Sensitivity" threshold slider.
*   **One-Click Export**: Quickly copy the raw text/braille to your clipboard or export the result.
*   **Zero Server-Side**: All image processing happens locally in your browser using the HTML5 Canvas API—your images are never uploaded to a server.

## Technology

*   **HTML5 & CSS3**: Responsive UI with a modern dark-mode aesthetic.
*   **Vanilla JavaScript**: Custom image processing logic without external dependencies.
*   **Canvas API**: Used for image sampling and pixel data extraction.

## How to Use

1.  Download HTML file and Open in any browser
2.  **Upload**: Select any image file from your device.
3.  **Configure**:
    *   Choose **Full Color ASCII** for a vibrant look or **Braille** for a classic terminal/text-art feel.
    *   Slide the **Resolution** bar to increase detail or decrease the output size.
    *   If using Braille mode, adjust the **Dot Sensitivity** to find the perfect contrast balance.
4.  **Export**: Click **Copy to Clipboard** to paste your art into Discord, Slack, or code comments.

## License
[Mozilla Public License Version 2.0](LICENSE) - Feel free to use and modify
