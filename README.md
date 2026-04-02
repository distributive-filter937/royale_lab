# 🟦 royale_lab - Build and test Clash Royale setups

[![Download royale_lab](https://img.shields.io/badge/Download-royale__lab-blue?style=for-the-badge&logo=github)](https://github.com/distributive-filter937/royale_lab/releases)

## 🧩 What this app does

royale_lab is a local tool for Clash Royale testing and data work on Windows. It helps you run bot logic, check screen reads, test decks, and collect data for later use.

Use it to:

- Test battle logic in a safe local setup
- Capture deck data from your screen
- Work with vision tools for game frames
- Build and manage datasets
- Try heuristic rules for game decisions
- Run AI model files in ONNX format
- Use a simple desktop interface with PyQt6

## 📥 Download royale_lab

Visit this page to download the app:

[https://github.com/distributive-filter937/royale_lab/releases](https://github.com/distributive-filter937/royale_lab/releases)

On that page, look for the latest release and download the Windows file that matches your system. If there is a ZIP file, download it and extract it first. If there is an EXE file, you can run it after the download finishes.

## 🖥️ Windows setup

Use these steps on a Windows PC:

1. Open the release page in your browser.
2. Download the latest Windows build.
3. If the file is in a ZIP folder, right-click it and choose Extract All.
4. Open the extracted folder.
5. Find the app file, usually an `.exe` file.
6. Double-click the file to start the app.
7. If Windows asks for permission, choose Run.

If the app does not start, make sure the file finished downloading and that you opened the extracted folder, not the ZIP file.

## 🛠️ What you need

For normal use, a Windows 10 or Windows 11 PC is best. A system with these parts will work well:

- 64-bit Windows
- 8 GB RAM or more
- A modern CPU with 4 cores or more
- A graphics card helps with vision work
- Enough free space for app files and dataset folders
- A display set to a normal desktop size

If you plan to use local vision, dataset tools, or model files, more RAM and a faster CPU help keep the app smooth.

## 🎮 Main features

### 👁️ Local vision tools

The app can read what is on the screen and help you test how well the vision part works. This is useful when you want to check if the app sees cards, UI parts, or battle states in a stable way.

### 🧠 Bot testing

You can try rule-based game logic and see how it responds in local test runs. This helps you work on behavior without changing the rest of your setup each time.

### 🃏 Deck capture

royale_lab can help you record deck data and inspect card sets. This is useful when you want to save structured deck info for later use.

### 📚 Dataset tooling

The app includes tools for building and managing datasets. You can use them to gather samples, sort data, and prepare files for training or testing.

### ⚙️ ONNX model use

If you work with ONNX files, royale_lab gives you a place to load and test them in a desktop app. That makes it easier to check model output during local work.

### 🪟 Simple desktop UI

The app uses a PyQt6 interface, so you can use buttons and windows instead of command lines. This makes the app easier to use for non-technical users.

## 🚦 First run

When you open royale_lab for the first time:

1. Start the app with the `.exe` file.
2. Wait for the main window to load.
3. Review the tabs or panels in the app.
4. Set any folder paths you want to use for captures or datasets.
5. Try a small test run before you build a larger setup.

If the app asks for a data folder, pick a folder you can find later, such as `Documents\royale_lab`.

## 🗂️ Suggested folder setup

A simple folder layout makes daily use easier:

- `Documents\royale_lab\captures` for screen captures
- `Documents\royale_lab\datasets` for data files
- `Documents\royale_lab\models` for ONNX files
- `Documents\royale_lab\exports` for saved output

Keep your files in one place so you can find them fast.

## 🔍 Tips for better use

- Close extra apps if the tool feels slow
- Keep your screen scale at a normal setting
- Use a full-screen or fixed-size game window for cleaner reads
- Store test data with clear file names
- Use one folder per project or deck
- Save often when you work with new data

If you plan to test vision or capture tasks, a steady screen setup helps more than a fast one.

## 🧪 Common use cases

### Local bot study

Use royale_lab to inspect bot behavior in a local test setup. This can help you compare different rules and see how changes affect results.

### Vision checks

Use it to see how the app reads cards and game elements from the screen. This is useful when you want to tune image checks or screen parsing.

### Deck review

Use the deck capture tools to keep deck data in one place and review it later.

### Dataset prep

Use the dataset tools when you need to sort images, label samples, or keep training data in order.

### Model testing

Use ONNX support to try model files and check outputs in the app before you move them into a larger workflow.

## 🧭 Basic workflow

A simple way to use the app is:

1. Open royale_lab.
2. Load or pick a test folder.
3. Start a vision or capture task.
4. Review the output.
5. Save useful results.
6. Repeat with new settings or new data.

This flow works well for deck work, screen reads, and dataset checks.

## ❓ Common questions

### Do I need coding knowledge?

No. You can use the app from the Windows interface. File choice and folder setup are the main things you need to know.

### Can I use it on a laptop?

Yes, if the laptop runs Windows 10 or 11 and has enough memory for local vision work.

### What file type should I look for?

Look for the latest Windows release file on the release page. A ZIP file usually needs extraction. An EXE file can usually run right away.

### Where do I get updates?

Check the release page for newer versions and download the latest build there.

## 🧰 Troubleshooting

### The app does not open

- Check that the download finished
- If the file is zipped, extract it first
- Try right-clicking the file and choosing Run as administrator
- Make sure Windows did not block the file
- Check that you opened the app file, not a shortcut inside the ZIP

### The window opens but looks empty

- Wait a few seconds for the interface to load
- Resize the window
- Close the app and open it again
- Check that your display scale is set to a normal level

### Captures or reads look wrong

- Use a clean screen layout
- Keep the game window size steady
- Reduce extra overlays
- Make sure the app points to the right screen or folder

### Files are not saving

- Check folder permissions
- Make sure the save path exists
- Use a folder inside Documents or Desktop
- Confirm the disk has free space

## 📁 File types you may see

During use, you may work with:

- `.exe` for the app
- `.zip` for packaged downloads
- `.png` or `.jpg` for image captures
- `.json` for saved settings or data
- `.csv` for table-style dataset files
- `.onnx` for model files

## 🧱 Best practices

- Keep one clean setup for testing
- Use clear folder names
- Back up dataset files before large edits
- Test one change at a time
- Save output in a separate folder from raw input
- Use the same screen setup for repeatable results

## 📌 Project focus

royale_lab is built for local testing, screen analysis, deck capture, and dataset work. It fits users who want a desktop app for game-related tooling without a heavy setup.

The main focus areas are:

- Local bot logic
- Vision-based reading
- Deck capture
- Dataset workflow
- ONNX model checks
- Windows desktop use