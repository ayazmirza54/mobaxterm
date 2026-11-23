# devbox

A single-file web app that turns one editable sentence into a setup script for a fresh dev machine:
PowerShell (winget), Git Bash, WSL / Ubuntu, or macOS (Homebrew), plus Dockerfile and devcontainer exports.

Open `index.html` in a browser. No build step.

- 108 tools in 13 groups: languages, clouds, infra, data, AI coding agents, deploy CLIs, terminal goodies,
  shell superpowers (zoxide, atuin, mise, direnv, just…), git power-ups, network & security, Android, editors, desktop apps
- 23 themes: 16 inspired by rune.build (Romero, Carmack, Frost, Wozniak, Brevik, Sanfilippo, Kernighan, Kelleher,
  Thompson, Hopper, Ritchie, Auge, Reynolds, Mullen, Pike, Furman) and 7 classics. The theme restyles the page and,
  when enabled, the generated starship prompt, VS Code / Cursor colours, Windows Terminal scheme and Ghostty theme.
  A theme-pack tab adds WezTerm, Alacritty and kitty configs.
- Command palette: Ctrl/⌘ K or `/`. `[` and `]` cycle themes. Ctrl/⌘ Enter generates.
- Every generated step checks before it installs, so scripts are safe to re-run.
