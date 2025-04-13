# Flash Player Proof of Concept

This is a lightweight proof-of-concept web app for rendering old `.swf` (Adobe Flash) files using the [Ruffle](https://ruffle.rs/) Flash Player emulator.

## 🚀 Live Demo

[Click here to try it live](https://shane-aktiga.github.io/flashplayer-poc/)


## 🧠 What It Does

- Allows users to upload a `.swf` file from their local computer.
- Renders the Flash content directly in the browser using Ruffle WebAssembly.
- Requires **no plugins, installs, or extensions**.

## 📂 How to Use

1. Open the [live demo link](https://shane-aktiga.github.io/flashplayer-poc/).
2. Click the **Upload** button and select a `.swf` file.
3. The Flash content will be displayed right below.

> ⚠️ Ruffle supports ActionScript 1 and 2 very well, but ActionScript 3 support is still in progress. Some Flash files may not work as expected.

## 🛠 Tech Stack

- HTML + JavaScript
- [Ruffle WebAssembly](https://ruffle.rs/)
- Hosted on GitHub Pages

## 🧪 Local Development

If you want to run it locally:

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/flash-player-poc.git
   cd flash-player-poc
