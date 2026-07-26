# ✂️ Image Splitter CLI & Utility

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.8%2B-brightgreen)](https://www.python.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> A fast, high-precision image splitting tool that seamlessly divides large images, sprite sheets, and banners into customizable grids or exact pixel-dimension tiles.

---

## 🌟 Overview

**Image Splitter** is a lightweight Python-based tool designed to automate the process of slicing images. Whether you are creating seamless Instagram grid posts, splitting game sprite sheets, or slicing massive infographics for digital distribution, this tool delivers lossless quality with sub-millisecond execution speeds.

---

## ✨ Key Features

* **📐 Multiple Splitting Modes:**
  * **Grid-Based (Rows x Columns):** Split images into equal parts based on exact row and column counts (e.g., 3x3 for social media).
  * **Pixel-Based (Custom Width x Height):** Slice images into precise dimensions, ideal for UI assets and game textures.
* **⚡ High-Speed Processing:** Powered by Pillow (PIL) for ultra-fast and memory-efficient image rendering.
* **🖼️ Multi-Format Support:** Works seamlessly with PNG, JPEG, WEBP, BMP, and TIFF files.
* **🛡️ Aspect Ratio & Quality Retention:** Preserves the original image resolution, color profile, and pixel sharpness without compression loss.
* **📁 Auto-Organized Output:** Automatically generates output folders and exports systematically named sub-images (e.g., `tile_0_1.png`).
* **💻 Interactive CLI & Automation Ready:** Simple step-by-step command-line interface, plus easy integration into backend scripts.

---

## 🛠️ Tech Stack

* **Language:** Python 3.8+
* **Core Library:** [Pillow (PIL)](https://python-pillow.org/) — Python Imaging Library

---

## 🚀 Quick Start

### Prerequisites

Ensure you have Python 3.8 or higher installed:
```bash
python --version
