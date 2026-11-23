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

Try it / source: <paste your GitHub or Pages link here>

## Tips

- Attach 2–3 screenshots (the sentence card, the theme gallery, the generated script), or a 15-second screen recording cycling themes with [ and ].
- Put the link in the first comment, not the post body: LinkedIn shows posts with outside links to fewer people.
