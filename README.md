# Brew Packages

A list of recommendations for Homebrew packages on macOS I find useful.

## Essential

- [`neovim`](https://formulae.brew.sh/formula/neovim) [Text Editor](https://neovim.io/)
- [`git`](https://formulae.brew.sh/formula/git) [Version Control](https://git-scm.com)
- [`tmux`](https://formulae.brew.sh/formula/tmux) [Terminal Multiplexer](https://tmux.github.io/)
- [`htop`](https://formulae.brew.sh/formula/htop) [Process Manager](https://htop.dev/)
- [`python3`](https://formulae.brew.sh/formula/python@3.9) [Scripting Language](https://www.python.org/)
- [`iterm2` (Cask)](https://formulae.brew.sh/cask/iterm2) [Terminal Emulator](https://iterm2.com/)
- [`ghostty` (Cask)](https://formulae.brew.sh/cask/ghostty) [Terminal Emulator](https://ghostty.org/)
- [`latest` (Cask)](https://formulae.brew.sh/cask/latest) [Update Checker](https://max.codes/latest)
- [`raycast` (Cask)](https://formulae.brew.sh/cask/raycast) [Raycast Launcher - Spotlight replacement](https://raycast.com/)
- [`mole`](https://formulae.brew.sh/formula/mole) [Deep clean and optimize your Mac](https://github.com/tw93/mole)

## CLI Tools

- [`trash`](https://formulae.brew.sh/formula/trash) [Trash helper](https://hasseg.org/trash/)
- [`tree`](https://formulae.brew.sh/formula/tree) [Recursive directory lister](https://oldmanprogrammer.net/source.php?dir=projects/tree)
- [`rename`](https://formulae.brew.sh/formula/rename) [Batch rename tool](http://plasmasturm.org/code/rename)
- [`fzf`](https://formulae.brew.sh/formula/fzf) [Fuzzy finder](https://github.com/junegunn/fzf)
- [`jq`](https://formulae.brew.sh/formula/jq) [JSON processor](https://jqlang.github.io/jq/)
- [`yq`](https://formulae.brew.sh/formula/yq) [YAML processor](https://github.com/mikefarah/yq)
- [`rlwrap`](https://formulae.brew.sh/formula/rlwrap) [Readline wrapper](https://github.com/hanslub42/rlwrap)
- [`wget`](https://formulae.brew.sh/formula/wget) [download tool](https://www.gnu.org/software/wget/)
- [`tlrc`](https://formulae.brew.sh/formula/tlrc) [Official tldr client written in Rust https://tldr.sh/tlrc/](https://tldr.sh/tlrc/)
- `macfetch` - brew tap gantoreno/macfetch && brew install macfetch [A macOS Neofetch alternative](https://github.com/gantoreno/macfetch)

## Development

- [`android-studio` (Cask)](https://formulae.brew.sh/cask/android-studio) [Android Studio](https://developer.android.com/studio/)
- [`coreutils`](https://formulae.brew.sh/formula/coreutils) [GNU utils](https://www.gnu.org/software/coreutils/)
- [`copilot-for-xcode` (Cask)](https://formulae.brew.sh/cask/copilot-for-xcode) [GitHub Copilot Addon for XCode](https://github.com/intitni/CopilotForXcode)
- [`cursor` (Cask)](https://formulae.brew.sh/cask/cursor) [Cursor AI IDE](https://www.cursor.com/)
- [`visual-studio-code` (Cask)](https://formulae.brew.sh/cask/visual-studio-code) [Editor/IDE](https://code.visualstudio.com/)
- [`cmake` (Cask)](https://formulae.brew.sh/cask/cmake) [Build tool](https://www.cmake.org/)
- [`ninja`](https://formulae.brew.sh/formula/ninja) [Lightweight build system](https://ninja-build.org/)
- [`cocoapods`](https://formulae.brew.sh/formula/cocoapods) [Cocoa dependency manager](https://cocoapods.org/)
- [`openjdk`](https://formulae.brew.sh/formula/openjdk) [Java](https://openjdk.org/)
- [`zulu8` (Cask)](https://github.com/Homebrew/homebrew-cask-versions/blob/master/Casks/zulu8.rb) [Java 8 with ARM64 support](https://www.azul.com/downloads/zulu/)
- [`node`](https://formulae.brew.sh/formula/node) [Node.js](https://nodejs.org/)
- [`gradle`](https://formulae.brew.sh/formula/gradle) [JVM build tool](https://www.gradle.org/)
- [`haskell-stack`](https://formulae.brew.sh/formula/haskell-stack) [Haskell build tool](https://haskellstack.org/)
- [`rustup-init`](https://formulae.brew.sh/formula/rustup-init) [Rust toolchain installer](https://rustup.rs/)
- [`swi-prolog`](https://formulae.brew.sh/formula/swi-prolog) [Prolog environment](https://www.swi-prolog.org/)
- [`flutter` (Cask)](https://formulae.brew.sh/cask/flutter) [UI toolkit](https://flutter.dev/)
- [`processing` (Cask)](https://formulae.brew.sh/cask/processing) [Software sketchbook](https://processing.org/)
- [`dotnet-sdk` (Cask)](https://formulae.brew.sh/cask/dotnet-sdk) [.NET SDK](https://www.microsoft.com/net/core#macos)
- [`llvm`](https://formulae.brew.sh/formula/llvm) [Compiler infrastructure, alternatively install via Xcode](https://llvm.org/)
- [`ghidra` (Cask)](https://formulae.brew.sh/cask/ghidra) [Reverse engineering tools](https://github.com/NationalSecurityAgency/ghidra)
- [`sf-symbols` (Cask)](https://formulae.brew.sh/cask/sf-symbols) [Symbols browser](https://developer.apple.com/sf-symbols/)
- [`gh`](https://formulae.brew.sh/formula/gh) [GitHub CLI](https://cli.github.com/)
- [`gcenx/wine/wine-crossover` (Cask)](https://github.com/Gcenx/homebrew-wine/blob/master/Casks/wine-crossover.rb) [Compatibility layer for Windows applications](https://github.com/Gcenx/homebrew-wine)
  - Note that [`wine-stable`](https://formulae.brew.sh/cask/wine-stable) also works, but does not support 32-bit applications
  - See [this gist](https://gist.github.com/fwcd/903e0851f66a675a3a253b1837c7553f) for details
- [`winetricks`](https://formulae.brew.sh/formula/winetricks) [Helper scripts for Windows libraries in Wine](https://github.com/Winetricks/winetricks)
- [`jenv`](https://formulae.brew.sh/formula/jenv) [Java Environment Manager](https://github.com/jenv/jenv)
- [`rbenv`](https://formulae.brew.sh/formula/rbenv) [Ruby Environment Manager](https://rbenv.org)
- [`zed` (Cask)](https://formulae.brew.sh/cask/zed) [Zed Editor](https://zed.dev/)
- [`github` (Cask)](https://formulae.brew.sh/cask/github) [Desktop client for GitHub repositories](https://desktop.github.com/)

## Security

- [`little-snitch` (Cask)](https://formulae.brew.sh/cask/little-snitch) [Personal firewall](https://www.obdev.at/products/littlesnitch/index.html)
- [`lulu` (Cask)](https://formulae.brew.sh/cask/lulu) [Personal Firewall](https://objective-see.org/products/lulu.html)
- [`silentknight` (Cask)](https://formulae.brew.sh/cask/silentknight) [fully automatic checks of firmware and security systems](https://eclecticlight.co/lockrattler-systhist/)
- [`suspicious-package` (Cask)](https://formulae.brew.sh/cask/suspicious-package) [Application for inspecting installer packages](https://www.mothersruin.com/software/SuspiciousPackage/)
- [`openvpn-connect` (Cask)](https://formulae.brew.sh/cask/openvpn-connect) [VPN Client](https://openvpn.net/client-connect-vpn-for-mac-os/)
- [`cryptomator` (Cask)](https://formulae.brew.sh/cask/cryptomator) [Multi-platform client-side cloud file encryption tool](https://cryptomator.org/)

## Server

- [`postgresql`](https://formulae.brew.sh/formula/postgresql) [Database](https://www.postgresql.org/)
  - Note that you can use `brew services` [as described here](https://gist.github.com/ibraheem4/ce5ccd3e4d7a65589ce84f2a3b7c23a3?permalink_comment_id=3443897#gistcomment-3443897) to start and stop PostgreSQL as needed

## Emulation/Virtualization

- [`qemu`](https://formulae.brew.sh/formula/qemu) [Emulator](https://www.qemu.org/)
- [`utm` (Cask)](https://formulae.brew.sh/cask/utm) [Virtual machines UI on top of QEMU](https://mac.getutm.app/)

## Containers

- [`docker` (Cask)](https://formulae.brew.sh/cask/docker) [Docker Desktop, container builder and runner](https://www.docker.com/)
- [`kubernetes-cli`](https://formulae.brew.sh/formula/kubernetes-cli) [Kubernetes API client](https://kubernetes.io/docs/reference/kubectl/)
- [`k9s`](https://formulae.brew.sh/formula/k9s) [Kubernetes TUI](https://k9scli.io/)
- [`helm`](https://formulae.brew.sh/formula/helm) [Kubernetes package manager](https://helm.sh/)
- [`orbstack` (Cask)](https://formulae.brew.sh/cask/orbstack) [Docker alternative for Mac](https://orbstack.dev/)
- [`ctop`](https://formulae.brew.sh/formula/ctop) [Top-like interface for container metrics](https://bcicen.github.io/ctop/)
- [`container`](https://formulae.brew.sh/formula/container) [Create and run Linux containers using lightweight virtual machines](https://apple.github.io/container/documentation/)

## Utilities

- [`appcleaner` (Cask)](https://formulae.brew.sh/cask/appcleaner) [App removal utility](https://freemacsoft.net/appcleaner/)
- [`the-unarchiver` (Cask)](https://formulae.brew.sh/cask/the-unarchiver) [Unarchival tool](https://theunarchiver.com/)
- [`coconutbattery` (Cask)](https://formulae.brew.sh/cask/coconutbattery) [Battery info utility](https://www.coconut-flavour.com/coconutbattery/)
- [`barrier` (Cask)](https://formulae.brew.sh/cask/barrier) [KVM](https://github.com/debauchee/barrier/)
- [`raspberry-pi-imager` (Cask)](https://formulae.brew.sh/cask/raspberry-pi-imager) [Image flashing utility](https://www.raspberrypi.com/software/)
- [`burn` (Cask)](https://formulae.brew.sh/cask/burn) [CD/DVD burning tool](https://burn-osx.sourceforge.io/)
- [`mas`](https://formulae.brew.sh/formula/mas) [Mac App Store command-line interface](https://github.com/mas-cli/mas)
- [`topgrade`](https://formulae.brew.sh/formula/topgrade#default) [Upgrade all the things](https://github.com/topgrade-rs/topgrade)
- [`finetune`](https://formulae.brew.sh/cask/finetune) [Per-application volume mixer, equalizer, and audio router](https://github.com/ronitsingh10/FineTune)
- [`thaw`(Cask)](https://formulae.brew.sh/cask/thaw) [Menu bar manager](https://github.com/jakehilborn/thaw)

## Automation

- [`hammerspoon` (Cask)](https://formulae.brew.sh/cask/hammerspoon) [Desktop automation application](https://www.hammerspoon.org/)
- [`hazel` (Cask)](https://formulae.brew.sh/cask/hazel#default) [Automated organisation](https://www.noodlesoft.com/)

## Cloud

- [`nextcloud` (Cask)](https://formulae.brew.sh/cask/nextcloud) [Nextcloud desktop sync client](https://nextcloud.com/)
- [`nextcloud-vfs` (Cask)](https://formulae.brew.sh/cask/nextcloud-vfs) [Nextcloud desktop sync client with VFS support](https://nextcloud.com/)

## Internet

- [`firefox` (Cask)](https://formulae.brew.sh/cask/firefox) [Web Browser](https://www.mozilla.org/firefox/)
- [`helium-browser` (Cask)](https://formulae.brew.sh/cask/helium-browser) [Web Browser](https://helium.computer/)
- [`vivaldi` (Cask)](https://formulae.brew.sh/cask/vivaldi) [Web Browser](https://vivaldi.com/)
- [`zen` (Cask)](https://formulae.brew.sh/cask/zen) [Gecko based web browser](https://zen-browser.app/)
- [`discord` (Cask)](https://formulae.brew.sh/cask/discord) [Voice and Text Chat](https://discord.com/)
- [`mattermost` (Cask)](https://formulae.brew.sh/cask/mattermost) [Text Chat](https://mattermost.com/)
- [`signal` (Cask)](https://formulae.brew.sh/cask/signal) [Messenger](https://signal.org/)
- [`zulip` (Cask)](https://formulae.brew.sh/cask/zulip) [Text Chat](https://zulip.com/)
- [`slack` (Cask)](https://formulae.brew.sh/cask/slack) [Text Chat](https://slack.com/)
- [`zoom` (Cask)](https://formulae.brew.sh/cask/zoom) [Video Conferencing](https://www.zoom.us/)
- [`cyberduck` (Cask)](https://formulae.brew.sh/cask/cyberduck) [Server and cloud storage browser](https://cyberduck.io/)

## Productivity

- [`mactex` (Cask)](https://formulae.brew.sh/cask/mactex) [LaTeX](https://www.tug.org/mactex/)
- [`pdfpc`](https://formulae.brew.sh/formula/pdfpc) [PDF presenter console](https://pdfpc.github.io/)
- [`libreoffice` (Cask)](https://formulae.brew.sh/cask/libreoffice) [Office suite](https://www.libreoffice.org/)
- [`zotero` (Cask)](https://formulae.brew.sh/cask/zotero) [Bibliography manager](https://www.zotero.org/)
- [`obsidian` (Cask)](https://formulae.brew.sh/cask/obsidian) [Obsidian PKM](https://obsidian.md/)

## Fonts

- [`font-jetbrains-mono` (Cask)](https://github.com/Homebrew/homebrew-cask-fonts/blob/master/Casks/font-jetbrains-mono.rb) [Typeface for developers](https://www.jetbrains.com/lp/mono)
- [`font-hack-nerd-font` (Cask)](https://formulae.brew.sh/cask/font-hack-nerd-font) [Hack Nerd Font](https://github.com/ryanoasis/nerd-fonts)

## Audio/Video

- [`ffmpeg`](https://formulae.brew.sh/formula/ffmpeg) [Audio/video converter](https://ffmpeg.org/)
- [`vlc` (Cask)](https://formulae.brew.sh/cask/vlc) [Multimedia player](https://www.videolan.org/vlc/)
- [`spotify` (Cask)](https://formulae.brew.sh/cask/spotify) [Music streaming](https://www.spotify.com/)
- [`mixxx` (Cask)](https://formulae.brew.sh/cask/mixxx) [DJing](https://www.mixxx.org/)
  - For an unofficial native arm64/Apple Silicon build, try [`fwcd/mixxx/m1xxx` (Cask)](https://github.com/fwcd/homebrew-mixxx/blob/main/Casks/m1xxx.rb)
- [`blender` (Cask)](https://formulae.brew.sh/cask/blender) [3D modeling](https://www.blender.org/)
- [`obs` (Cask)](https://formulae.brew.sh/cask/obs) [Broadcasting and screencasting](https://obsproject.com/)
- [`blackhole-2ch` (Cask)](https://formulae.brew.sh/cask/blackhole-2ch) [Virtual Audio Driver, useful for routing desktop audio](https://existential.audio/blackhole/)
- [`iina`(Cask)](https://formulae.brew.sh/cask/iina) [Free and open-source media player](https://iina.io/)

## AI
- [`claude` (Cask)](https://formulae.brew.sh/cask/claude) [Claude Desktop by Anthropic](https://claude.com/download)
- [`ollama`](https://formulae.brew.sh/formula/ollama) [Ollama model runtime](https://ollama.com/)
- [`codex` (Cask)](https://formulae.brew.sh/cask/codex) [OpenAI's coding agent that runs in your terminal](https://github.com/openai/codex)
- [`codex-app` (Cask)](https://formulae.brew.sh/cask/codex-app) [OpenAI's Codex desktop app for managing coding agents](https://openai.com/codex)
- [`claude-code` (Cask)](https://formulae.brew.sh/cask/claude-code) [Terminal-based AI coding assistant](https://www.anthropic.com/claude-code)
- [`antigravity` (Cask)](https://formulae.brew.sh/cask/antigravity) [AI Coding Agent IDE](https://antigravity.google/)
- [`gemini-cli`](https://formulae.brew.sh/formula/gemini-cli) [Interact with Google Gemini AI models from the command-line](https://github.com/google-gemini/gemini-cli)

## Graphics

- [`gimp` (Cask)](https://formulae.brew.sh/cask/gimp) [Image editor](https://www.gimp.org/)
- [`inkscape` (Cask)](https://formulae.brew.sh/cask/inkscape) [Vector graphics editor](https://inkscape.org/)
- [`drawio` (Cask)](https://formulae.brew.sh/cask/drawio) [Diagram editor](https://www.diagrams.net/)
- [`yed` (Cask)](https://formulae.brew.sh/cask/yed) [Diagram editor](https://www.yworks.com/products/yed)
- [`affinity` (Cask)](https://formulae.brew.sh/cask/affinity) [Affinity Suite](https://www.affinity.studio/)
- [`immich-cli`](https://formulae.brew.sh/formula/immich-cli) [CLI for self-hosted photo manager Immich](https://immich.app/docs/features/command-line-interface)

## CAD

- [`prusaslicer` (Cask)](https://formulae.brew.sh/cask/prusaslicer) [3D slicer](https://www.prusa3d.com/slic3r-prusa-edition/)
- [`openscad` (Cask)](https://formulae.brew.sh/cask/openscad) [Programmable CAD modeler](https://www.openscad.org/)

## Gaming

- [`epic-games` (Cask)](https://formulae.brew.sh/cask/epic-games) [Epic Games Launcher](https://www.epicgames.com/)
- [`steam` (Cask)](https://formulae.brew.sh/cask/steam) [Game Distribution Platform](https://store.steampowered.com/about/)
- [`gog-galaxy` (Cask)](https://formulae.brew.sh/cask/gog-galaxy) [GOG Galaxy game client](https://www.gog.com/galaxy)
- [`prismlauncher` (Cask)](https://formulae.brew.sh/cask/prismlauncher) [Minecraft Launcher](https://prismlauncher.org/)
- [`0-ad` (Cask)](https://formulae.brew.sh/cask/0-ad) [0 A.D. Real-time strategy game](https://play0ad.com/)
