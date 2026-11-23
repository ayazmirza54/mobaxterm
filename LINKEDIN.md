# LinkedIn post: Devbox in one go

## Post text (paste as is)

Setting up a new laptop still eats a whole day. So I turned it into one sentence. ⚡

"Set up my Windows box with Python, Node and Java, talking to GCP and AWS. Ship with Docker and Terraform. Pair-program with Claude Code…"

Tap any word, swap what you want, and Devbox writes the setup script for you.

How it came together:

🧱 v1: a sentence builder that spits out one re-runnable script for PowerShell, Git Bash, WSL, Ubuntu or macOS, or a Dockerfile, or a devcontainer. Every step checks before it installs, so you can run it again whenever you add a tool.

🎨 v2: I wanted it to feel like my editor, not a form. So:
→ 23 themes, 16 inspired by rune.build (try Carmack: amber on black). The theme follows you into your starship prompt, VS Code, Windows Terminal and Ghostty
→ 108 tools, up from ~50: zoxide, atuin, mise, delta, Bun, Zed, Tailscale, aider…
→ ⌘K command palette, a vim-style status bar, syntax-highlighted output

🧪 Before shipping, every combination got generated headlessly: 474 files, and all 204 shell scripts passed a syntax check.

Built by pair-programming with Claude Code.

What's the first thing you install on a new machine? 👇

#DeveloperTools #DevEx #BuildInPublic #ClaudeCode #OpenSource

## First comment (post right after publishing)

Try it here 👉 https://devbox.ayazmirza54.in

## Tips

- Images are in `social/` (1080×1350 at 2x, LinkedIn's portrait size). Upload in this order: `1-sentence.png`, `5-four-themes.png`, `2-themes.png`, `3-script.png`, `4-palette.png`.
- The link preview card uses `og-image.png` (1200×630). After deploying, paste the URL into linkedin.com/post-inspector to refresh LinkedIn's cache.
- Put the link in the first comment, not the post body: LinkedIn shows posts with outside links to fewer people.
