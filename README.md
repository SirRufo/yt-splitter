# YT-Splitter (MP3)

<img src="https://github.com/redsolver/yt-splitter/raw/main/image.png">

Downloads and splits audio tracks from a YouTube video according to the chapters/tracks.
Useful for compilations or full album uploads.

## Requirements

`youtube-dl` and `ffmpeg` installed and in your `PATH`.

## Install

1. Download the binary for your system from https://github.com/redsolver/yt-splitter/releases
2. Rename it to `yt-splitter`
3. Place it in a directory which is in your `PATH`
4. Make it executable (`chmod +x yt-splitter` on Linux)

## Usage

1. `cd` into the directory you want to save the tracks in. `yt-splitter` will automatically create a subdirectory with the title of the video and store the downloadeded tracks in it.
2. Execute `yt-splitter VIDEOID` (`VIDEOID` can be a YouTube video id or a URL to a YouTube video)
