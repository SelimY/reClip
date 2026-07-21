To set up and run ReClip on Windows, you can choose between two main methods depending on your technical comfort level:

## Method 1: Using the Pinokio Browser (Recommended for quick setup)

1. Download and install **Pinokio** (the open-source browser that automates app installations).
2. Open Pinokio, search for **ReClip**, and click **Install**.
3. Launch the app to access the clean web interface where you can paste URLs and download media.

## Method 2: Manual Installation via Python/Docker

1. **Prerequisites:** Ensure you have Git and Python installed on your Windows system.
2. **Clone the Repository:** Open Command Prompt and run `git clone https://github.com/SelimY/reClip.git`.
3. **Install Dependencies:** Navigate to the folder (`cd reClip`) and install required backend packages like `yt-dlp` and `ffmpeg`.
4. **Launch:** Run the setup script to start the local server, then open `http://localhost:8899` in your web browser to start downloading.

## Original Repo
https://github.com/averygan/reclip
