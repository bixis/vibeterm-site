# $vterm — The Terminal That Vibes

**A terminal emulator that plays YouTube videos in the background.**

You know the feeling. You're deep in a coding session, lo-fi beats playing, everything flowing. Now imagine that vibe is *inside* your terminal — video playing behind your code, fully transparent, fully functional.

VibeTerm is a real terminal. zsh, tmux, vim, neovim — everything works. But behind your text, there's a YouTube video filling the screen. Code on top. Vibes underneath.

## Why?

Because every developer already codes with YouTube open in another tab. We just moved it behind your cursor.

- **Real terminal.** Full PTY. Not a toy, not a gimmick. Run anything you'd run in iTerm2 or Terminal.app.
- **Any YouTube video.** Paste a URL and it plays. Lo-fi streams, tutorials, music videos, live coding sessions.
- **Audio-only mode.** Don't want the video? Just the music? One flag: `vibeterm play <url> -a`
- **Boss mode.** One shortcut and the video vanishes. Your terminal looks completely normal. Nobody will ever know.
- **Smart overlay.** Dark highlights only where text is. Empty lines show pure video. Your code is readable. Your vibes are untouched.

## Get it

1. Install [yt-dlp](https://github.com/yt-dlp/yt-dlp): `brew install yt-dlp`
2. [Download VibeTerm](https://github.com/bixis/vibeterm-site/releases/latest) for macOS (Apple Silicon)
3. Open the `.dmg`, drag to Applications, right-click > Open on first launch

## Quick start

```bash
vibeterm play "https://youtube.com/watch?v=jfKfPfyJRdk"   # lo-fi girl
vibeterm volume 30                                          # lower the volume
vibeterm watch                                              # full screen video
vibeterm watch                                              # back to coding
vibeterm boss                                               # hide everything
```

## What people use it for

- **Vibe coding** — lo-fi beats, ambient visuals, coding flow
- **Learning** — tutorial video in the background while you follow along in the terminal
- **Streaming** — coding streamers get a unique visual for their content
- **Fun** — because why should terminals be boring?

---

**[Download](https://github.com/bixis/vibeterm-site/releases/latest)** · **[Landing page](https://bixis.github.io/vibeterm-site/)** · Built by [@bixis](https://github.com/bixis)
