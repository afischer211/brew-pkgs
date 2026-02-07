# Brew Packages

A list of recommendations for Homebrew packages on macOS I find useful.

## Essential

- [`neovim`](https://formulae.brew.sh/formula/neovim) (Text Editor)
- [`git`](https://formulae.brew.sh/formula/git) (Version Control)
- [`tmux`](https://formulae.brew.sh/formula/tmux) (Terminal Multiplexer)
- [`htop`](https://formulae.brew.sh/formula/htop) (Process Manager)
- [`python3`](https://formulae.brew.sh/formula/python@3.9) (Scripting Language)
- [`iterm2` (Cask)](https://formulae.brew.sh/cask/iterm2) (Terminal Emulator)
- [`ghostty` (Cask)](https://formulae.brew.sh/cask/ghostty) (Terminal Emulator)
- [`latest` (Cask)](https://formulae.brew.sh/cask/latest) (Update Checker)
- [`raycast` (Cask)](https://formulae.brew.sh/cask/raycast) (Raycast Launcher - Spotlight replacement)

## CLI Tools

- [`trash`](https://formulae.brew.sh/formula/trash) (Trash helper)
- [`tree`](https://formulae.brew.sh/formula/tree) (Recursive directory lister)
- [`rename`](https://formulae.brew.sh/formula/rename) (Batch rename tool)
- [`fzf`](https://formulae.brew.sh/formula/fzf) (Fuzzy finder)
- [`jq`](https://formulae.brew.sh/formula/jq) (JSON processor)
- [`yq`](https://formulae.brew.sh/formula/yq) (YAML processor)
- [`rlwrap`](https://formulae.brew.sh/formula/rlwrap) (Readline wrapper)
- [`wget`](https://formulae.brew.sh/formula/wget) (download tool)
- [`tlrc`](https://formulae.brew.sh/formula/tlrc) (Official tldr client written in Rust https://tldr.sh/tlrc/)
- `macfetch` - brew tap gantoreno/macfetch && brew install macfetch [A macOS Neofetch alternative](https://github.com/gantoreno/macfetch)

## Development

- [`android-studio` (Cask)](https://formulae.brew.sh/cask/android-studio) (Android Studio)
- [`coreutils`](https://formulae.brew.sh/formula/coreutils) (GNU utils)
- [`copilot-for-xcode` (Cask)](https://formulae.brew.sh/cask/copilot-for-xcode) (GitHub Copilot Addon for XCode)
- [`cursor` (Cask)](https://formulae.brew.sh/cask/cursor) (Cursor AI IDE)
- [`visual-studio-code` (Cask)](https://formulae.brew.sh/cask/visual-studio-code) (Editor/IDE)
- [`cmake` (Cask)](https://formulae.brew.sh/cask/cmake) (Build tool)
- [`ninja`](https://formulae.brew.sh/formula/ninja) (Lightweight build system)
- [`cocoapods`](https://formulae.brew.sh/formula/cocoapods) (Cocoa dependency manager)
- [`openjdk`](https://formulae.brew.sh/formula/openjdk) (Java)
- [`zulu8` (Cask)](https://github.com/Homebrew/homebrew-cask-versions/blob/master/Casks/zulu8.rb) (Java 8 with ARM64 support)
- [`node`](https://formulae.brew.sh/formula/node) (Node.js)
- [`gradle`](https://formulae.brew.sh/formula/gradle) (JVM build tool)
- [`haskell-stack`](https://formulae.brew.sh/formula/haskell-stack) (Haskell build tool)
- [`rustup-init`](https://formulae.brew.sh/formula/rustup-init) (Rust toolchain installer)
- [`swi-prolog`](https://formulae.brew.sh/formula/swi-prolog) (Prolog environment)
- [`flutter` (Cask)](https://formulae.brew.sh/cask/flutter) (UI toolkit)
- [`processing` (Cask)](https://formulae.brew.sh/cask/processing) (Software sketchbook)
- [`dotnet-sdk` (Cask)](https://formulae.brew.sh/cask/dotnet-sdk) (.NET SDK)
- [`llvm`](https://formulae.brew.sh/formula/llvm) (Compiler infrastructure, alternatively install via Xcode)
- [`ghidra` (Cask)](https://formulae.brew.sh/cask/ghidra) (Reverse engineering tools)
- [`sf-symbols` (Cask)](https://formulae.brew.sh/cask/sf-symbols) (Symbols browser)
- [`gh`](https://formulae.brew.sh/formula/gh) (GitHub CLI)
- [`gcenx/wine/wine-crossover` (Cask)](https://github.com/Gcenx/homebrew-wine/blob/master/Casks/wine-crossover.rb) (Compatibility layer for Windows applications)
  - Note that [`wine-stable`](https://formulae.brew.sh/cask/wine-stable) also works, but does not support 32-bit applications
  - See [this gist](https://gist.github.com/fwcd/903e0851f66a675a3a253b1837c7553f) for details
- [`winetricks`](https://formulae.brew.sh/formula/winetricks) (Helper scripts for Windows libraries in Wine)
- [`jenv`](https://formulae.brew.sh/formula/jenv) (Java Environment Manager)
- [`rbenv`](https://formulae.brew.sh/formula/rbenv) (Ruby Environment Manager)
- [`zed` (Cask)](https://formulae.brew.sh/cask/zed) (Zed Editor)
- [`github` (Cask)](https://formulae.brew.sh/cask/github) (Desktop client for GitHub repositories)

## Security

- [`little-snitch` (Cask)](https://formulae.brew.sh/cask/little-snitch) (Personal firewall)
- [`lulu` (Cask)](https://formulae.brew.sh/cask/lulu) (Personal Firewall)
- [`silentknight` (Cask)](https://formulae.brew.sh/cask/silentknight) (fully automatic checks of firmware and security systems)
- [`suspicious-package` (Cask)](https://formulae.brew.sh/cask/suspicious-package) (Application for inspecting installer packages)
- [`openvpn-connect` (Cask)](https://formulae.brew.sh/cask/openvpn-connect) (VPN Client)
- [`cryptomator` (Cask)](https://formulae.brew.sh/cask/cryptomator) (Multi-platform client-side cloud file encryption tool)

## Server

- [`postgresql`](https://formulae.brew.sh/formula/postgresql) (Database)
  - Note that you can use `brew services` [as described here](https://gist.github.com/ibraheem4/ce5ccd3e4d7a65589ce84f2a3b7c23a3?permalink_comment_id=3443897#gistcomment-3443897) to start and stop PostgreSQL as needed

## Emulation/Virtualization

- [`qemu`](https://formulae.brew.sh/formula/qemu) (Emulator)
- [`utm` (Cask)](https://formulae.brew.sh/cask/utm) (Virtual machines UI on top of QEMU)

## Containers

- [`docker` (Cask)](https://formulae.brew.sh/cask/docker) (Docker Desktop, container builder and runner)
- [`kubernetes-cli`](https://formulae.brew.sh/formula/kubernetes-cli) (Kubernetes API client)
- [`k9s`](https://formulae.brew.sh/formula/k9s) (Kubernetes TUI)
- [`helm`](https://formulae.brew.sh/formula/helm) (Kubernetes package manager)
- [`orbstack` (Cask)](https://formulae.brew.sh/cask/orbstack) (Docker alternative for Mac)
- [`ctop`](https://formulae.brew.sh/formula/ctop) (Top-like interface for container metrics)

## Utilities

- [`appcleaner` (Cask)](https://formulae.brew.sh/cask/appcleaner) (App removal utility)
- [`the-unarchiver` (Cask)](https://formulae.brew.sh/cask/the-unarchiver) (Unarchival tool)
- [`coconutbattery` (Cask)](https://formulae.brew.sh/cask/coconutbattery) (Battery info utility)
- [`barrier` (Cask)](https://formulae.brew.sh/cask/barrier) (KVM)
- [`raspberry-pi-imager` (Cask)](https://formulae.brew.sh/cask/raspberry-pi-imager) (Image flashing utility)
- [`burn` (Cask)](https://formulae.brew.sh/cask/burn) (CD/DVD burning tool)
- [`mas`](https://formulae.brew.sh/formula/mas) (Mac App Store command-line interface)
- [`topgrade`](https://formulae.brew.sh/formula/topgrade#default) (Upgrade all the things)
- [`finetune`](https://formulae.brew.sh/cask/finetune) (Per-application volume mixer, equalizer, and audio router)
- [`thaw`(Cask)](https://formulae.brew.sh/cask/thaw) (Menu bar manager)

## Automation

- [`hammerspoon` (Cask)](https://formulae.brew.sh/cask/hammerspoon) (Desktop automation application)
- [`hazel` (Cask)](https://formulae.brew.sh/cask/hazel#default) (Automated organisation)

## Cloud

- [`nextcloud` (Cask)](https://formulae.brew.sh/cask/nextcloud) (Nextcloud desktop sync client)
- [`nextcloud-vfs` (Cask)](https://formulae.brew.sh/cask/nextcloud-vfs) (Nextcloud desktop sync client with VFS support)

## Internet

- [`firefox` (Cask)](https://formulae.brew.sh/cask/firefox) (Web Browser)
- [`helium-browser` (Cask)](https://formulae.brew.sh/cask/helium-browser) (Web Browser)
- [`vivaldi` (Cask)](https://formulae.brew.sh/cask/vivaldi) (Web Browser)
- [`zen` (Cask)](https://formulae.brew.sh/cask/zen) (Gecko based web browser)
- [`discord` (Cask)](https://formulae.brew.sh/cask/discord) (Voice and Text Chat)
- [`mattermost` (Cask)](https://formulae.brew.sh/cask/mattermost) (Text Chat)
- [`signal` (Cask)](https://formulae.brew.sh/cask/signal) (Messenger)
- [`zulip` (Cask)](https://formulae.brew.sh/cask/zulip) (Text Chat)
- [`slack` (Cask)](https://formulae.brew.sh/cask/slack) (Text Chat)
- [`zoom` (Cask)](https://formulae.brew.sh/cask/zoom) (Video Conferencing)
- [`cyberduck` (Cask)](https://formulae.brew.sh/cask/cyberduck) (Server and cloud storage browser)

## Productivity

- [`mactex` (Cask)](https://formulae.brew.sh/cask/mactex) (LaTeX)
- [`pdfpc`](https://formulae.brew.sh/formula/pdfpc) (PDF presenter console)
- [`libreoffice` (Cask)](https://formulae.brew.sh/cask/libreoffice) (Office suite)
- [`zotero` (Cask)](https://formulae.brew.sh/cask/zotero) (Bibliography manager)
- [`obsidian` (Cask)](https://formulae.brew.sh/cask/obsidian) (Obsidian PKM)

## Fonts

- [`font-jetbrains-mono` (Cask)](https://github.com/Homebrew/homebrew-cask-fonts/blob/master/Casks/font-jetbrains-mono.rb) (Typeface for developers)
- [`font-hack-nerd-font` (Cask)](https://formulae.brew.sh/cask/font-hack-nerd-font) (Hack Nerd Font)

## Audio/Video

- [`ffmpeg`](https://formulae.brew.sh/formula/ffmpeg) (Audio/video converter)
- [`vlc` (Cask)](https://formulae.brew.sh/cask/vlc) (Multimedia player)
- [`spotify` (Cask)](https://formulae.brew.sh/cask/spotify) (Music streaming)
- [`mixxx` (Cask)](https://formulae.brew.sh/cask/mixxx) (DJing)
  - For an unofficial native arm64/Apple Silicon build, try [`fwcd/mixxx/m1xxx` (Cask)](https://github.com/fwcd/homebrew-mixxx/blob/main/Casks/m1xxx.rb)
- [`blender` (Cask)](https://formulae.brew.sh/cask/blender) (3D modeling)
- [`obs` (Cask)](https://formulae.brew.sh/cask/obs) (Broadcasting and screencasting)
- [`blackhole-2ch` (Cask)](https://formulae.brew.sh/cask/blackhole-2ch) (Virtual Audio Driver, useful for routing desktop audio)
- [`iina`(Cask)](https://formulae.brew.sh/cask/iina) (Free and open-source media player)

## AI
- [`claude` (Cask)](https://formulae.brew.sh/cask/claude) (Claude Desktop by Anthropic)
- [`ollama`](https://formulae.brew.sh/formula/ollama) (Ollama model runtime)
- [`codex` (Cask)](https://formulae.brew.sh/cask/codex) (OpenAI's coding agent that runs in your terminal)
- [`codex-app` (Cask)](https://formulae.brew.sh/cask/codex-app) (OpenAI's Codex desktop app for managing coding agents)
- [`claude-code` (Cask)](https://formulae.brew.sh/cask/claude-code) (Terminal-based AI coding assistant)
- [`antigravity` (Cask)](https://formulae.brew.sh/cask/antigravity) (AI Coding Agent IDE)

## Graphics

- [`gimp` (Cask)](https://formulae.brew.sh/cask/gimp) (Image editor)
- [`inkscape` (Cask)](https://formulae.brew.sh/cask/inkscape) (Vector graphics editor)
- [`drawio` (Cask)](https://formulae.brew.sh/cask/drawio) (Diagram editor)
- [`yed` (Cask)](https://formulae.brew.sh/cask/yed) (Diagram editor)
- [`affinity` (Cask)](https://formulae.brew.sh/cask/affinity) (Affinity Suite)
- [`immich-cli`](https://formulae.brew.sh/formula/immich-cli) (CLI for self-hosted photo manager Immich)

## CAD

- [`prusaslicer` (Cask)](https://formulae.brew.sh/cask/prusaslicer) (3D slicer)
- [`openscad` (Cask)](https://formulae.brew.sh/cask/openscad) (Programmable CAD modeler)

## Gaming

- [`epic-games` (Cask)](https://formulae.brew.sh/cask/epic-games) (Epic Games Launcher)
- [`steam` (Cask)](https://formulae.brew.sh/cask/steam) (Game Distribution Platform)
- [`gog-galaxy` (Cask)](https://formulae.brew.sh/cask/gog-galaxy) (GOG Galaxy game client)
- [`prismlauncher` (Cask)](https://formulae.brew.sh/cask/prismlauncher) (Minecraft Launcher)
- [`0-ad` (Cask)](https://formulae.brew.sh/cask/0-ad) (0 A.D. Real-time strategy game)
