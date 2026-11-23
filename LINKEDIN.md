# LinkedIn post: Devbox in one go (story version)

## Post text (paste as is)

I opened Docker's new Agentic Platform and stopped scrolling at the very first screen.

There was no form and no wall of dropdowns. It was just one sentence:

"Launch shell with a secret. It'll run in a sandbox with open access, no tools added, on medium compute, and stops after 1 hour."

Every underlined word was a setting. Tap "medium compute", pick another size, and the sentence rewrites itself. You configure infrastructure by reading it out loud.

My first thought: why isn't everything set up like this?

The thing I dread most is a new machine. A whole day of installing Python, Node, Docker, the cloud CLIs, the editor, the fonts, the dotfiles, then forgetting half of it.

So I borrowed the idea and built Devbox:

"Set up my Windows box with Python, Node and Java, talking to GCP and AWS. Ship with Docker and Terraform. Pair-program with Claude Code…"

Tap any word, swap what you want, and it writes one setup script for PowerShell, Git Bash, WSL, Ubuntu or macOS. It can also export a Dockerfile or a devcontainer. Every step checks before it installs, so you can run it again whenever you add a tool.

Then I kept going:
→ 108 tools, from zoxide and atuin to Bun, Zed, Tailscale and aider
→ 23 themes, 16 inspired by rune.build. Pick Carmack (amber on black) and your prompt, VS Code and terminal follow
→ ⌘K search, a vim-style status bar, syntax-highlighted output

Before shipping, I generated every combination: 474 files, and all 204 shell scripts passed a syntax check.

What I learned: the best interface is sometimes a sentence. If you can read your config out loud, you can understand it.

Built by pair-programming with Claude Code. Credit to the Docker team for the spark. 🐳

What's the first thing you install on a new machine? 👇

#DeveloperTools #DevEx #Docker #BuildInPublic #ClaudeCode

## First comment (post right after publishing)

Try it here 👉 https://devbox.ayazmirza54.in

## Tips

- Images are in `social/` (1080×1350 at 2x, LinkedIn's portrait size). Upload in this order: `1-sentence.png`, `5-four-themes.png`, `2-themes.png`, `3-script.png`, `4-palette.png`.
- Optional: put your Docker Agentic Platform screenshot first so readers see the spark next to the result. Crop out the sandbox list and the phone status bar first; they show your account's sandbox names.
- Tag Docker (type @Docker and pick the company page) in the "Credit to the Docker team" line.
- The link preview card uses `og-image.png` (1200×630). After deploying, paste the URL into linkedin.com/post-inspector to refresh LinkedIn's cache.
- Put the link in the first comment, not the post body: LinkedIn shows posts with outside links to fewer people.
