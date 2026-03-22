# yt-dlp

## What It Is
`yt-dlp` is an external command-line tool for downloading videos, audio, playlists, and metadata from YouTube and many other sites.

It is not bundled with A2B. A2B only points AI to this tool when media-download work is better handled outside the browser.

## Prerequisites
- Install `yt-dlp` separately on the local machine before trying to use it.
- Verify it is available in the shell with `yt-dlp --version`.

## When To Use
- The user explicitly wants to download video or audio files
- Browser automation is not enough and a dedicated downloader is the better tool
- The AI needs a stable external project reference for media capture workflows

## Recommended Flow
1. Read the official project page or README.
2. Confirm `yt-dlp` is installed by running `yt-dlp --version`.
3. Use `yt-dlp` shell commands directly for download work.
4. Use A2B only when browser-side inspection, login-state checks, or page discovery is still needed.

## Notes
- Treat this as a link-first external tool entry, not an A2B built-in capability.
- If `yt-dlp` is not installed, stop and tell the operator that an external dependency is missing.

## External Links
- Project repo: https://github.com/yt-dlp/yt-dlp
