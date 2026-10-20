# Awesome Open-Source & Free CS Tools & Resources

*A curated list of high-quality, actively-maintained open-source tools and repositories for computer science education, research, and practice.*

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![GitHub last commit](https://img.shields.io/github/last-commit/mawady/awesome-open-source-cs)](https://github.com/mawady/awesome-open-source-cs) [![GitHub stars](https://img.shields.io/github/stars/mawady/awesome-open-source-cs?style=social)](https://github.com/mawady/awesome-open-source-cs)

**Focus**: Quality over comprehensiveness. Every entry is here because it genuinely solves a problem for students, researchers, and professionals of computer science.

---

## Curation Philosophy

This list prioritizes **quality over comprehensiveness**:

**Active Maintenance**: Tools actively updated within the past few years.

**Genuine Utility**: Each tool solves real problems for CS students, researchers, and practitioners. No bloat, no niche-only tools.

**Learning Value**: Educational context provided where appropriate. We explain *why* a tool matters, not just *that* it exists.

**Cross-Platform Support**: Priority given to tools working on Linux, macOS, and Windows. Platform-specific alternatives are noted.

**Community Adoption**: Established projects with proven track records. Generally 100+ GitHub stars indicates real-world usage.

### What This List Is NOT

- A complete registry of all open-source CS tools (see [GitHub Topics](https://github.com/topics) for exhaustive lists)
- A replacement for language-specific [awesome](https://awesome.re) lists (Python, JavaScript, Rust, etc.)
- A dumping ground for every project tagged "open-source"
- Promotional material for anyone's pet project

---

## Table of Contents

- [Linux Distributions](#linux-distributions)
- [Package Managers](#package-managers)
- [Version Control & Git](#version-control--git)
- [Editors & IDEs](#editors--ides)
- [Terminals & Shells](#terminals--shells)
- [Terminal Multiplexers](#terminal-multiplexers)
- [Shell Prompt Customization](#shell-prompt-customization)
- [Resource Monitors](#resource-monitors)
- [Documentation & Knowledge Management](#documentation--knowledge-management)
- [API Development & Testing](#api-development--testing)
- [Databases & Data Management](#databases--data-management)
- [Testing & Quality Assurance](#testing--quality-assurance)
- [DevOps & CI/CD](#devops--cicd)
- [Monitoring & Observability](#monitoring--observability)
- [Containers & Virtualization](#containers--virtualization)
- [Security](#security)
- [Media & Diagramming](#media--diagramming)
- [USB Bootable OS Burners](#usb-bootable-os-burners)
- [Remote Desktop & Access](#remote-desktop--access)
- [Archive & Compression](#archive--compression)
- [Web Browsers](#web-browsers)
- [Related Awesome Lists](#related-awesome-lists)

---

## Linux Distributions
> Open-source or free Linux operating systems used for desktops, servers, development, privacy, security, embedded systems, and specialized computing environments.

- **Ubuntu** `General / Beginner` `Debian Family` [[Website](https://ubuntu.com/)] | [[GitHub](https://github.com/canonical)]: Widely adopted Debian-based OS maintained by Canonical, powering servers, cloud infrastructure, enterprise desktops, and AI/ML workflows.
- **Debian** `General / Server` `Debian Family` [[Website](https://www.debian.org/)] | [[GitLab](https://salsa.debian.org/)]: Foundational, community-driven distribution celebrated for extreme stability, strict free software guidelines, and expansive package repositories.
- **Linux Mint** `General / Windows-like` `Debian / Ubuntu Family` [[Website](https://linuxmint.com/)] | [[GitHub](https://github.com/linuxmint)]: Desktop-oriented distribution focused on out-of-the-box usability, traditional workflows via Cinnamon, and an accessible beginner experience.
- **MX Linux** `General / Lightweight` `Debian Family` [[Website](https://mxlinux.org/)] | [[GitHub](https://github.com/MX-Linux)]: High-efficiency, mid-weight Debian-based distro known for rock-solid stability, low hardware overhead, and extensive built-in graphical admin tools (MX Tools).
- **Fedora** `General / Beginner` `Fedora Family` [[Website](https://fedoraproject.org/)] | [[GitLab](https://gitlab.com/fedora)]: Upstream, community-driven distro sponsored by Red Hat, showcasing cutting-edge Linux technologies, modern developer tools, and GNOME implementations.
- **Arch Linux** `General / Advanced` `Arch Family` [[Website](https://archlinux.org/)] | [[GitLab](https://gitlab.archlinux.org/archlinux)]: Minimalist, rolling-release DIY distribution focused on simplicity, user control, the `pacman` package manager, and the Arch User Repository (AUR).
- **Manjaro** `General / Beginner` `Arch Family` [[Website](https://manjaro.org/)] | [[GitLab](https://gitlab.manjaro.org/)]: Accessible Arch-based distribution featuring an automated graphical installer, curated rolling software branches, and pre-configured desktop environments.
- **openSUSE** `General / Beginner` `SUSE Family` [[Website](https://www.opensuse.org/)] | [[GitHub](https://github.com/openSUSE)]: Community Linux distribution available in rolling-release Tumbleweed and stable Leap variants, with strong administration and packaging tools.
- **NixOS** `General / DevOps` `Nix Family` [[Website](https://nixos.org/)] | [[GitHub](https://github.com/NixOS/nixpkgs)]: Fully declarative, reproducible Linux distribution built on the Nix package manager, offering atomic system upgrades and instant state rollbacks.
- **Alpine Linux** `General / Containers` `Independent / musl` [[Website](https://alpinelinux.org/)] | [[GitLab](https://gitlab.alpinelinux.org/alpine)]: Ultra-lightweight, security-oriented distribution built on musl libc and BusyBox, standard for Docker container base images and routers.
- **Rocky Linux** `Enterprise` `RHEL Family` [[Website](https://rockylinux.org/)] | [[GitHub](https://github.com/rocky-linux)]: 100% bug-for-bug compatible community replacement for Red Hat Enterprise Linux, founded by original CentOS co-creator Gregory Kurtzer.
- **AlmaLinux** `Enterprise` `RHEL Family` [[Website](https://almalinux.org/)] | [[GitHub](https://github.com/AlmaLinux)]: Community-owned, ABI-compatible enterprise Linux distribution governed by a 501(c)(6) non-profit for cloud, data center, and server workloads.
- **CentOS Stream** `Enterprise` `RHEL Family` [[Website](https://www.centos.org/stream/)] | [[GitLab](https://gitlab.com/redhat/centos-stream)]: Upstream continuous-delivery development platform sitting immediately ahead of future Red Hat Enterprise Linux minor releases.
- **Kali Linux** `Security` `Debian Family` [[Website](https://www.kali.org/)] | [[GitLab](https://gitlab.com/kalilinux)]: Industry-standard Debian-derived distribution purpose-built for penetration testing, digital forensics, ethical hacking, and vulnerability assessments.
- **Parrot OS** `Security` `Debian Family` [[Website](https://www.parrotsec.org/)] | [[GitLab](https://gitlab.com/parrotsec)]: Security-focused distribution offering toolsets for penetration testing, cryptography, privacy defense, and reverse engineering.
- **Qubes OS** `Security` `Fedora / Xen Family` [[Website](https://www.qubes-os.org/)] | [[GitHub](https://github.com/QubesOS)]: Ultra-secure desktop operating system utilizing Xen hardware virtualization to compartmentalize applications into isolated, disposable virtual machines (AppVMs).
- **Tails** `Privacy` `Debian Family` [[Website](https://tails.net/)] | [[GitLab](https://gitlab.tails.boum.org/tails/tails)]: Live, amnesic portable OS engineered to leave zero traces on host storage while forcing all outgoing network traffic through the Tor network.
- **Bazzite** `Gaming` `Fedora Family` [[Website](https://bazzite.gg/)] | [[GitHub](https://github.com/ublue-os/bazzite)]: Fedora Atomic/OSTree-based immutable gaming distribution designed for desktop PCs, handheld gaming PCs (Steam Deck, ROG Ally), and living-room setups.
- **SteamOS** `Gaming` `Arch Family` [[Website](https://store.steampowered.com/steamos)] | [[GitLab](https://gitlab.steamos.cloud/)]: Valve's immutable, Arch-based gaming operating system powering the Steam Deck, built around Gamescope, Proton, and the Steam Big Picture interface.
- **Nobara** `Gaming` `Fedora Family` [[Website](https://nobaraproject.org/)] | [[GitHub](https://github.com/Nobara-Project)]: Fedora-based distribution customized by GloriousEggroll (GE-Proton creator) featuring kernel tweaks, third-party drivers, media codecs, and pre-configured gaming tools out of the box.
- **CachyOS** `Gaming` `Arch Family` [[Website](https://cachyos.org/)] | [[GitHub](https://github.com/cachyos)]: Performance-focused Arch Linux derivative optimized with custom x86-64-v3/v4 compiled packages, advanced CPU schedulers (BORE/EEVDF), and pre-tuned gaming environments.
- **Raspberry Pi OS** `Single-Board` `Debian Family` [[Website](https://www.raspberrypi.com/software/)] | [[GitHub](https://github.com/RPi-Distro)]: Official Debian-optimized operating system tailored specifically for the Raspberry Pi single-board computer lineup.
- **DietPi** `Single-Board` `Debian Family` [[Website](https://dietpi.com/)] | [[GitHub](https://github.com/MichaIng/DietPi)]: Extremely lightweight Debian-based distribution with automated configuration and software installation tools for SBCs and low-resource systems.
- **Puppy Linux** `Minimal` `Multiple Families / Independent` [[Website](https://puppylinux-woof-ce.github.io/)] | [[GitHub](https://github.com/puppylinux-woof-CE)]: Extremely lightweight Linux family designed to run efficiently on older hardware, removable media, and systems with limited resources.
- **Tiny Core Linux** `Minimal` `Independent` [[Website](https://tinycorelinux.net/)] | [[GitHub](https://github.com/tinycorelinux)]: Extremely small modular Linux distribution designed to provide a minimal base system that can be extended with packages and applications as needed.

---

## Package Managers
> Tools used to automate the installation, updating, and management of software dependencies.


- **Homebrew** `MacOS` [[Website](https://brew.sh/)] | [[Github](https://github.com/Homebrew/brew)]: The standard package manager for macOS. Installs command-line tools, applications, and programming language packages.
- **MacPorts** `MacOS` [[Website](https://www.macports.org/)] | [[Github](https://github.com/macports/macports-base)]: Alternative to Homebrew with a different philosophy; less commonly used.
- **Nix** `Linux / MacOS` [[Website](https://nixos.org/)] | [[Github](https://github.com/NixOS/nixpkgs)]:  Declarative package manager with reproducible builds; steep learning curve but powerful.
- **Snap** `Linux` [[Website](https://snapcraft.io/)] | [[Github](https://github.com/canonical/snapd)]: Canonical's containerized package format; great for quick installation of apps.
- **Flatpak** `Linux` [[Website](https://flatpak.org/)] | [[Github](https://github.com/flatpak/flatpak)]: Sandboxed application framework; similar to Snap but with different trade-offs.
- **Scoop** `Windows` [[Website](https://scoop.sh/)] | [[Github](https://github.com/ScoopInstaller/Scoop)]:  Command-line installer for Windows; similar philosophy to Homebrew.
- **Chocolatey** `Windows` [[Website](https://chocolatey.org/)] | [[Github](https://github.com/chocolatey/choco)]: Largest package manager for Windows; GUI and CLI options available.

---

## Version Control & Git

> Platforms used to track code changes, collaborate, manage versions, and contribute to open-source projects.

- **GitHub** [[Website](https://github.com/)]: Largest Git hosting platform; excellent for discovering projects, contributing, and building your portfolio.
- **GitLab** [[Website](https://about.gitlab.com/)] | [[Github](https://github.com/gitlabhq/gitlabhq)]: Full DevOps platform with built-in CI/CD, container registry, and issue tracking.
- **Forgejo** [[Website](https://forgejo.org/)] | [[CodeBerg](https://codeberg.org/forgejo/forgejo)]: Lightweight, self-hosted Git service; perfect for private repositories on your own infrastructure.

---

## Editors & IDEs

> Tools used to write, edit, debug, and manage code efficiently.

- **Visual Studio Code (VSCode)** `Full-Featured IDE` `Linux / MacOS / Windows` [[Website](https://code.visualstudio.com/)] | [[Github](https://github.com/microsoft/vscode)]: The most popular editor today. Lightweight yet extensible with thousands of plugins. Best for beginners and professionals alike.
- **VSCodium** `Full-Featured IDE` `Linux / MacOS / Windows` [[Website](https://vscodium.com/)] | [[Github](https://github.com/VSCodium/vscodium)]: VS Code without Microsoft branding, telemetry, or proprietary licensing; pure open-source.
- **Zed** `Full-Featured IDE` `MacOS / Linux` [[Website](https://zed.dev/)] | [[Github](https://github.com/zed-industries/zed)]: High-performance collaborative editor written in Rust; designed for speed and collaboration.
- **JetBrains** `Full-Featured IDE` `Linux / MacOS / Windows` [[Website](https://www.jetbrains.com/)]: Full-featured IDEs for specific languages (PyCharm for Python, IntelliJ for Java, WebStorm for JavaScript). Free Community editions available.
- **Apache NetBeans** `Full-Featured IDE` `Linux / MacOS / Windows` [[Website](https://netbeans.apache.org/)] | [[Github](https://github.com/apache/netbeans)]: Full IDE for Java, C++, PHP, and JavaScript development.
- **Eclipse** `Full-Featured IDE` `Linux / MacOS / Windows` [[Website](https://www.eclipse.org/)] | [[Github](https://github.com/eclipse-platform/eclipse.platform)]: Extensible open-source IDE with support for Java, C/C++, Python, and many other languages through plugins; highly customizable with a large ecosystem of extensions.
- **Sublime Text** `Lightweight Editors` `Linux / MacOS / Windows` [[Website](https://www.sublimetext.com/)]: Fast, distraction-free editor with powerful multi-selection and command palette. Commercial license available.
- **Lapce** `Lightweight Editors` `Linux / MacOS / Windows` [[Website](https://lapce.dev/)] | [[Github](https://github.com/lapce/lapce)]: Fast, modern editor written in Rust; open-source alternative to VS Code with similar philosophy.
- **Geany** `Lightweight Editors` `Linux / MacOS / Windows` [[Website](https://www.geany.org/)] | [[Github](https://github.com/geany/geany)]: Lightweight GTK editor; great for quick editing without overhead.
- **Vim** `Terminal Editors` `Linux / MacOS / Windows` [[Website](https://www.vim.org/)]: Modal text editor; available on every Unix system. Master the basics to be productive everywhere.
- **Emacs** `Terminal Editors` `Linux / MacOS / Windows` [[Website](https://www.gnu.org/software/emacs/)]: Extensible Lisp machine; incredible power and flexibility but challenging for beginners.
- **Nano** `Terminal Editors` `Linux / MacOS / Windows` [[Website](https://www.nano-editor.org/)]: Beginner-friendly terminal editor; always available on Unix systems.
- **Neovim** `Terminal Editors` `Linux / MacOS / Windows` [[Website](https://neovim.io/)] | [[Github](https://github.com/neovim/neovim)]: Modern successor to Vim; highly extensible with Lua configuration; steep learning curve but unmatched efficiency for power users.
- **Helix** `Terminal Editors` `Linux / MacOS / Windows` [[Website](https://helix-editor.com/)] | [[Github](https://github.com/helix-editor/helix)]: Modal editor combining the best of Vim and modern ergonomics.

---

## Terminals & Shells

> Tools used to interact with your computer, run commands, and manage development workflows.

- **Alacritty** `Terminal` `Linux / MacOS / Windows` [[Github](https://github.com/alacritty/alacritty)]: GPU-accelerated terminal written in Rust. Blazing fast, minimal configuration. Best for speed.
- **Wezterm** `Terminal` `Linux / MacOS / Windows` [[Website](https://wezfurlong.org/wezterm/)] | [[Github](https://github.com/wez/wezterm)]: Feature-rich, written in Rust; excellent font rendering and tab support.
- **Kitty** `Terminal` `Linux / MacOS` [[Website](https://sw.kovidgoyal.net/kitty/)] | [[Github](https://github.com/kovidgoyal/kitty)]: Modern terminal with image support, fast graphics, and cross-window operations.
- **iTerm2** `Terminal` `MacOS` [[Website](https://iterm2.com/)] | [[Github](https://github.com/gnachman/iTerm2)]: Full-featured macOS terminal with split panes, search, autocomplete, and advanced features.
- **Ghostty** `Terminal` `MacOS / Linux` [[Website](https://ghostty.org/)]: Fast, modern terminal emulator focused on simplicity and performance.
- **Zsh** `Shell Environments` `Linux / MacOS` [[Website](http://www.zsh.org/)]: More powerful than Bash with better completion and theming. Default on modern macOS.
- **Fish** `Shell Environments` `Linux / MacOS` [[Website](https://fishshell.com/)] | [[Github](https://github.com/fish-shell/fish-shell)]: User-friendly shell with syntax highlighting and smart completions out of the box.

---

## Terminal Multiplexers

> Tools used to split terminals, manage panes, and maintain persistent sessions.

- **tmux** `Linux / MacOS` [[Website](https://github.com/tmux/tmux)]: The standard multiplexer; available on every Unix system. Steep learning curve but industry standard.
- **Zellij** `Linux / MacOS / Windows` [[Website](https://zellij.dev/)] | [[Github](https://github.com/zellij-org/zellij)]: Modern, user-friendly alternative to tmux written in Rust; better defaults.
- **GNU Screen** `Linux / MacOS` [[Website](https://www.gnu.org/software/screen/)]: Older multiplexer; less popular than tmux but still widely available.
- **mtm** `Linux / MacOS` [[Website](https://github.com/deadpixi/mtm)]: Minimal terminal multiplexer; lightweight alternative.

---

## Shell Prompt Customization
> Tools used to customize your terminal prompt with useful information and visual enhancements.

- **Starship** `Linux / MacOS / Windows` [[Website](https://starship.rs/)] | [[Github](https://github.com/starship/starship)]: Minimal, fast shell prompt written in Rust. Works with any shell.
- **Oh My Zsh** `Linux / MacOS` [[Website](https://ohmyzsh.sh/)] | [[Github](https://github.com/ohmyzsh/ohmyzsh)]: Framework for Zsh configuration; includes themes, plugins, and aliases.
- **Pure** `Linux / MacOS` [[Github](https://github.com/sindresorhus/pure)]: Minimal Zsh/Bash prompt written in pure shell script.
- **Powerlevel10k** `Linux / MacOS / Windows` [[Github](https://github.com/romkatv/powerlevel10k)]: Powerful Zsh theme with instant prompt; highly customizable.

---

## Shell Extensions & Utilities
> Tools used to extend shell functionality with plugins and command-line utilities.

- **zsh-syntax-highlighting** [[Github](https://github.com/zsh-users/zsh-syntax-highlighting)]: Real-time syntax highlighting in Zsh; catches errors before executing.
- **zsh-autosuggestions** [[Github](https://github.com/zsh-users/zsh-autosuggestions)]: Suggests previous commands as you type; huge productivity boost.
- **Bat** [[Github](https://github.com/sharkdp/bat)]: Cat clone with syntax highlighting and line numbers; makes code readable in terminal.
- **fd** [[Github](https://github.com/sharkdp/fd)]: Fast alternative to find command; simpler syntax and colored output.
- **ripgrep (rg)** [[Github](https://github.com/BurntSushi/ripgrep)]: Blazingly fast grep alternative; searches code recursively with smart defaults.
- **fzf** [[Github](https://github.com/junegunn/fzf)]: Fuzzy finder for command-line; search files, history, and processes interactively.
- **Atuin** [[Github](https://github.com/atuinsh/atuin)]: Shell history database in SQLite; search and sync shell history across machines.
- **The Fuck** [[Github](https://github.com/nvbn/thefuck)]: Corrects your previous console command; fun and useful.
- **eza** [[Github](https://github.com/eza-community/eza)]: Modern replacement for ls; colored output, tree views, and better defaults.

---

## Resource Monitors
> Tools used to monitor CPU, memory, disk, network, and overall system performance.

- **htop** `Linux / MacOS` [[Github](https://github.com/htop-dev/htop)]: Interactive process viewer; better than top with colors and easy navigation.
- **btop** `Linux / MacOS` [[Github](https://github.com/aristocratos/btop)]: Modern resource monitor with graphs; beautiful dashboard.
- **Glances** `Linux / MacOS / Windows` [[Github](https://github.com/nicolargo/glances)]: Cross-platform system monitoring tool; available as web interface.
- **bpytop** `Linux / MacOS` [[Github](https://github.com/aristocratos/bpytop)]: Archived in favor of btop; still functional for older systems.

---

## Documentation & Knowledge Management
> Tools used to document code, projects, and technical knowledge.

- **MkDocs** [[Website](https://www.mkdocs.org/)] | [[Github](https://github.com/mkdocs/mkdocs)]: Static site generator for project documentation using Markdown. Simple and fast.
- **Sphinx** [[Website](https://www.sphinx-doc.org/)] | [[Github](https://github.com/sphinx-doc/sphinx)]: Documentation generator originally for Python; now used for many projects.
- **Hugo** [[Website](https://gohugo.io/)] | [[Github](https://github.com/gohugoio/hugo)]: Static site generator written in Go; extremely fast with thousands of themes.
- **Jekyll** [[Website](https://jekyllrb.com/)] | [[Github](https://github.com/jekyll/jekyll)]: Static site generator powering GitHub Pages; perfect for blogs and documentation.
- **Obsidian** [[Website](https://obsidian.md/)]: Local-first knowledge base with powerful linking and backlinking; proprietary but stores files locally.
- **Logseq** [[Website](https://logseq.com/)] | [[Github](https://github.com/logseq/logseq)]: Open-source knowledge base with outliner and graph view; alternative to Obsidian.
- **Joplin** [[Website](https://joplinapp.org/)] | [[Github](https://github.com/laurent22/joplin)]: Open-source note-taking and to-do app with Markdown support, end-to-end encryption, syncing, and cross-platform support; alternative to Evernote and Obsidian.

---

## API Development & Testing
> Tools used to build, test, and interact with APIs efficiently.

- **Bruno** `API Client` `Linux / MacOS / Windows` [[Github](https://github.com/usebruno/bruno)]: Lightweight, Git-friendly API client. Similar to Postman but open-source and stores collections as text files.
- **Hoppscotch** `API Client` `Online / Self-hosted` [[Website](https://hoppscotch.io/)] | [[Github](https://github.com/hoppscotch/hoppscotch)]: Free, lightweight API client that runs in the browser.
- **Insomnia** `API Client` `Linux / MacOS / Windows` [[Website](https://insomnia.rest/)] | [[Github](https://github.com/Kong/insomnia)]: Full-featured API platform for design and testing.
- **HTTPie** `API Client` `Linux / MacOS / Windows` [[Website](https://httpie.io/)] | [[Github](https://github.com/httpie/httpie)]: Command-line HTTP client; simpler syntax than curl.
- **FastAPI** `API Framework` [[Website](https://fastapi.tiangolo.com/)] | [[Github](https://github.com/tiangolo/fastapi)]: Modern Python framework for building APIs with automatic documentation.
- **Flask** `API Framework` [[Website](https://flask.palletsprojects.com/)] | [[Github](https://github.com/pallets/flask)]: Lightweight Python web framework; great for learning and small projects.
- **Django** `API Framework` [[Website](https://www.djangoproject.com/)] | [[Github](https://github.com/django/django)]: Full-featured Python framework with batteries included (ORM, admin panel, authentication).
- **Express.js** `API Framework` [[Website](https://expressjs.com/)] | [[Github](https://github.com/expressjs/express)]: Minimal Node.js framework for building web APIs.

---

## Databases & Data Management
> Databases used to store, query, and manage data for different applications and use cases.

- **PostgreSQL** `Relational` [[Website](https://www.postgresql.org/)] | [[Github](https://github.com/postgres/postgres)]: The most advanced open-source relational database. Powerful, reliable, battle-tested at scale.
- **MySQL** `Relational` [[Website](https://www.mysql.com/)] | [[Github](https://github.com/mysql/mysql-server)]: Fast, reliable database; the M in LAMP and MEAN stacks.
- **SQLite** `Relational` [[Website](https://www.sqlite.org/)] | [[Github](https://github.com/sqlite/sqlite)]: Embedded database; perfect for single-file databases and development.
- **MongoDB** `NoSQL` [[Website](https://www.mongodb.com/)] | [[Github](https://github.com/mongodb/mongo)]: Document database; flexible schemas, great for rapid development.
- **Cassandra** `NoSQL` [[Website](https://cassandra.apache.org/)] | [[Github](https://github.com/apache/cassandra)]: Distributed NoSQL database; horizontal scalability and fault tolerance.
- **Redis** `In-Memory` [[Website](https://redis.io/)] | [[Github](https://github.com/redis/redis)]: In-memory data structure store; excellent for caching, sessions, and real-time applications.
- **Memcached** `In-Memory` [[Website](https://memcached.org/)] | [[Github](https://github.com/memcached/memcached)]: Simple, high-performance distributed memory caching system.
- **ClickHouse** `Time-Series` [[Website](https://clickhouse.com/)] | [[Github](https://github.com/ClickHouse/ClickHouse)]: Blazingly fast analytical database for big data; optimized for OLAP queries.
- **InfluxDB** `Time-Series` [[Website](https://www.influxdata.com/)] | [[Github](https://github.com/influxdata/influxdb)]: Time-series database; perfect for metrics, monitoring, and time-stamped data.
- **Kafka** `Streaming` [[Website](https://kafka.apache.org/)] | [[Github](https://github.com/apache/kafka)]: Distributed event streaming platform for high-throughput, real-time data pipelines and event-driven applications.

---

## Testing & Quality Assurance
> Tools used to test software at different levels and ensure reliability.

- **pytest** `Unit Testing` `Python` [[Website](https://pytest.org/)] | [[Github](https://github.com/pytest-dev/pytest)]: The most popular Python testing framework; simple to write, powerful assertions.
- **Jest** `Unit Testing` `JavaScript` [[Website](https://jestjs.io/)] | [[Github](https://github.com/facebook/jest)]: Popular JavaScript test framework with great defaults and snapshot testing.
- **JUnit** `Unit Testing` `Java` [[Website](https://junit.org/)] | [[Github](https://github.com/junit-team/junit4)]: Standard testing framework for Java.
- **Cypress** `E2E Testing` `Web` [[Website](https://www.cypress.io/)] | [[Github](https://github.com/cypress-io/cypress)]: Modern E2E testing framework; excellent developer experience with real browser automation.
- **Selenium** `E2E Testing` `Web` [[Website](https://www.selenium.dev/)] | [[Github](https://github.com/SeleniumHQ/selenium)]: Industry-standard browser automation; works with many languages and browsers.
- **Playwright** `E2E Testing` `Web` [[Website](https://playwright.dev/)] | [[Github](https://github.com/microsoft/playwright)]: Modern browser automation from Microsoft; supports Chrome, Firefox, and WebKit.
- **Appium** `UI Testing` `Mobile/Web/Desktop` [[Website](https://appium.io/)] | [[Github](https://github.com/appium/appium)]: Cross-platform automation framework for testing native, hybrid, and mobile web applications.
- **Lighthouse** `UI Testing` `Web` [[Website](https://developer.chrome.com/docs/lighthouse/)] | [[Github](https://github.com/GoogleChrome/lighthouse)]: Automated web auditing tool for performance, accessibility, SEO, best practices, and progressive web apps.
- **Maestro** `UI Testing` `Mobile/Web` [[Website](https://maestro.dev/)] | [[Github](https://github.com/mobile-dev-inc/Maestro)]: Simple, declarative UI testing framework focused on reliable mobile and web end-to-end tests.
- **Flashlight** `UI Testing` `Mobile` [[Website](https://docs.flashlight.dev/)] | [[Github](https://github.com/bamlab/flashlight)]: Open-source mobile application performance testing and profiling tool.
- **axe-core** `Accessibility Testing` `Web` [[Website](https://www.deque.com/axe/)] | [[Github](https://github.com/dequelabs/axe-core)]: Open-source accessibility testing engine for detecting WCAG violations in web applications.
- **WAVE** `Accessibility Testing` `Web` [[Website](https://wave.webaim.org/)]: Browser-based accessibility evaluation tool for identifying WCAG-related issues and accessibility improvements.
- **k6** `Load Testing` `JavaScript` [[Website](https://k6.io/)] | [[Github](https://github.com/grafana/k6)]: Modern load testing tool; write tests in JavaScript, analyze results easily.
- **Apache JMeter** `Load Testing` `Java` [[Website](https://jmeter.apache.org/)] | [[Github](https://github.com/apache/jmeter)]: Popular load testing tool with GUI; supports many protocols.
- **SonarQube** `Code Quality` `Multiple languages`  [[Website](https://www.sonarqube.org/)] | [[Github](https://github.com/SonarSource/sonarqube)]: Code quality and security analysis; integrates with CI/CD pipelines.
- **ESLint** `Code Quality` `JavaScript` [[Website](https://eslint.org/)] | [[Github](https://github.com/eslint/eslint)]: Find and fix problems in JavaScript code.
- **Pylint** `Code Quality` `Python` [[Website](https://pylint.pycqa.org/)] | [[Github](https://github.com/pylint-dev/pylint)]: Python code quality analyzer.

---

## DevOps & CI/CD
> Tools used to automate testing, building, and deploying software.

- **GitHub Actions** `CI/CD` [[Website](https://github.com/features/actions)] | [[Docs](https://docs.github.com/en/actions)]: Native GitHub integration; free tier generous. Best for GitHub projects.
- **GitLab CI/CD** `CI/CD` [[Docs](https://docs.gitlab.com/ee/ci/)]: Built into GitLab; powerful and flexible. Great for self-hosted runners.
- **Jenkins** `CI/CD` `Self-hosted` [[Website](https://www.jenkins.io/)] | [[Github](https://github.com/jenkinsci/jenkins)]: The classic CI/CD platform; powerful but requires maintenance.
- **Travis CI** `CI/CD` [[Website](https://www.travis-ci.com/)] | [[Github](https://github.com/travis-ci/travis-ci)]: Hosted CI/CD platform with simple YAML-based configuration; integrates with GitHub and is well suited for automated builds, tests, and deployments.
- **Woodpecker** `CI/CD` [[Website](https://woodpecker-ci.org/)] | [[Github](https://github.com/woodpecker-ci/woodpecker)]: Simple, container-based CI/CD; works with GitHub, GitLab, Gitea.
- **Terraform** `Infrastructure as Code` [[Website](https://www.terraform.io/)] | [[Github](https://github.com/hashicorp/terraform)]: Infrastructure as code for any cloud provider; manage resources declaratively.
- **Ansible** `Infrastructure as Code` [[Website](https://www.ansible.com/)] | [[Github](https://github.com/ansible/ansible)]: Configuration management and infrastructure provisioning; agentless and simple.

---

## Monitoring & Observability
> Tools used to monitor system health, application performance, metrics, and logs.

- **Prometheus** `Metrics` [[Website](https://prometheus.io/)] | [[Github](https://github.com/prometheus/prometheus)]: Time-series metrics database and alerting system. Industry standard.
- **Grafana** `Dashboard` [[Website](https://grafana.com/)] | [[Github](https://github.com/grafana/grafana)]: Visualization and analytics platform; create beautiful dashboards from any data source.
- **Loki** `Logging` [[Website](https://grafana.com/oss/loki/)] | [[Github](https://github.com/grafana/loki)]: Log aggregation system by Grafana; works great with Prometheus.
- **Loguru** `Logging` [[Website](https://loguru.readthedocs.io/)] | [[Github](https://github.com/Delgan/loguru)]: Simple, developer-friendly Python logging library with structured logging, automatic exception handling, rotation, and serialization.
- **Sentry** `Crash Reporting` [[Website](https://sentry.io/)] | [[Github](https://github.com/getsentry/sentry)]: Real-time error tracking and application performance monitoring; captures exceptions, crashes, traces, and performance issues.
- **Countly** `Crash Reporting` [[Website](https://countly.com/)] | [[Github](https://github.com/Countly/countly-server)]: Open-source product analytics and crash reporting platform for tracking user behavior, application performance, and crashes.

---

## Containers & Virtualization
> Tools used to package applications with their dependencies for consistent deployment.

- **Docker** `Container Engine` `Linux / MacOS / Windows` [[Website](https://www.docker.com/)] | [[Github](https://github.com/moby/moby)]: The standard container platform; ubiquitous in modern development.
- **Podman** `Container Engine` `Linux / MacOS / Windows` [[Github](https://github.com/containers/podman)]: Drop-in Docker replacement; rootless containers, no daemon required.
- **containerd** `Container Engine` `Linux` [[Github](https://github.com/containerd/containerd)]: Low-level container runtime used by Docker and Kubernetes.
- **Incus** `Container Engine / Virtual Machines` `Linux` [[Website](https://linuxcontainers.org/incus/)] | [[Github](https://github.com/lxc/incus)]: Open-source system container and virtual machine manager; lightweight alternative to Docker and traditional VM platforms, with support for Linux containers and full VMs.
- **container** `Container Engine` `MacOS` [[Github](https://github.com/apple/container)]: Apple's lightweight Linux container runtime for macOS, designed for fast, isolated Linux containers using Apple's virtualization technology.
- **Buildah** `Building Images` [[Github](https://github.com/containers/buildah)]: Build container images without a daemon; flexible and scriptable.
- **UTM** `Virtual Machines` `MacOS` [[Website](https://mac.getutm.app/)] | [[Github](https://github.com/utmapp/UTM)]: Virtual machine manager for macOS with great UI.
- **Quickemu** `Virtual Machines` `Linux / MacOS` [[Github](https://github.com/quickemu-project/quickemu)]: Quick virtual machine provisioning script.
- **VirtualBox** `Virtual Machines` `Linux / MacOS / Windows` [[Website](https://www.virtualbox.org/)]: Free, powerful virtualization; works everywhere.
- **WebVM** `Virtual Machines` `Browser` [[Website](https://webvm.io/)] | [[Github](https://github.com/leaningtech/webvm)]: Browser-based virtual machine environment powered by WebAssembly; run Linux and other software directly in the browser without local installation.
- **Kubernetes** `Container Orchestration` [[Website](https://kubernetes.io/)] | [[Github](https://github.com/kubernetes/kubernetes)]: Production-grade container orchestration; steep learning curve but industry standard.
- **Docker Compose** `Container Orchestration` [[Website](https://docs.docker.com/compose/)] | [[Github](https://github.com/docker/compose)]: Define and run multi-container applications; great for development.
- **Colima** `Container Runtime` `MacOS / Linux` [[Github](https://github.com/abiosoft/colima)]: Lightweight container runtime for macOS and Linux; provides Docker and containerd environments using a minimal virtual machine with simple CLI-based management.

---

## Security
> Tools used to identify vulnerabilities and improve software security.

- **OpenSSL** `Cryptography / TLS Toolkit` [[Website](https://www.openssl.org/)] | [[Github](https://github.com/openssl/openssl)]: Cryptography and SSL/TLS libraries and tools.
- **GnuPG** `Encryption / Signature` [[Website](https://gnupg.org/)] | [[Github](https://github.com/gpg/gnupg)]: GNU implementation of PGP; sign and encrypt files and emails.
- **Bitwarden** `Password Manager` [[Website](https://bitwarden.com/)] | [[Github](https://github.com/bitwarden)]: Password manager with self-hosted option; secure and open-source.
- **KeePassXC / KeePass** `Password Manager` [[Website](https://keepass.info/)] | [[Github](https://github.com/keepassxreboot/keepassxc)]: Offline password manager; stores database locally.
- **HashiCorp Vault** `Password Manager` [[Website](https://www.vaultproject.io/)] | [[Github](https://github.com/hashicorp/vault)]: Secrets management for infrastructure; handles credentials, API keys, certificates.
- **OWASP ZAP** `Security Scanner` [[Website](https://www.zaproxy.org/)] | [[Github](https://github.com/zaproxy/zaproxy)]: Web application security scanner; find vulnerabilities before attackers do.
- **Trivy** `Security Scanner` [[Website](https://www.aquasec.com/trivy/)] | [[Github](https://github.com/aquasecurity/trivy)]: Vulnerability scanner for containers and artifacts.

---

## Media & Diagramming
> Tools used to create diagrams, presentations, graphics, and other visual content.

- **VLC** `Media Player` `Linux / MacOS / Windows` [[Website](https://www.videolan.org/vlc/)] | [[Github](https://github.com/videolan/vlc)]: Universal media player; plays virtually any format.
- **OBS Studio** `Media Streaming / Recording` `Linux / MacOS / Windows` [[Website](https://obsproject.com/)] | [[Github](https://github.com/obsproject/obs-studio)]: Live streaming and screen recording software.
- **Shotcut** `Media Editor` `Linux / MacOS / Windows` [[Website](https://www.shotcut.org/)] | [[Github](https://github.com/mltframework/shotcut)]: Video editor with timeline; free and feature-rich.
- **Inkscape** `Graphics Editor` `Linux / MacOS / Windows` [[Website](https://inkscape.org/)] | [[Github](https://github.com/inkscape/inkscape)]: Vector graphics editor; design logos, illustrations, and technical drawings.
- **GIMP** `Graphics Editor` `Linux / MacOS / Windows` [[Website](https://www.gimp.org/)] | [[Github](https://github.com/GNOME/gimp)]: Raster graphics editor; image manipulation and photo editing.
- **Krita** `Graphics Editor` `Linux / MacOS / Windows` [[Website](https://krita.org/)] | [[Github](https://github.com/KDE/krita)]: Painting software designed for digital artists; excellent brush engine.
- **draw.io** `Diagram Editor` `Web / Desktop` [[Website](https://draw.io/)] | [[Github](https://github.com/jgraph/drawio-desktop)]: Diagram editor for flowcharts, mockups, and architecture diagrams.
- **Mermaid** `Diagram Editor` [[Website](https://mermaid.js.org/)] | [[Github](https://github.com/mermaid-js/mermaid)]: Create diagrams from markdown text; flowcharts, sequence diagrams, and more.
- **Excalidraw** `Diagram Editor` [[Website](https://excalidraw.com/)] | [[Github](https://github.com/excalidraw/excalidraw)]: Virtual whiteboard with hand-drawn aesthetic; great for sketches.
- **D2** `Diagram Editor` [[Website](https://d2lang.com/)] | [[Github](https://github.com/terrastruct/d2)]: Modern diagram language; write diagrams as text.
- **Slidev** `Presentation Editor` [[Website](https://sli.dev/)] | [[Github](https://github.com/slidevjs/slidev)]: Presentations written in Markdown; developer-friendly.

---

## USB Bootable OS Burners
> Tools used to create bootable USB drives for installing or running operating systems.

- **balenaEtcher** `Windows / MacOS / Linux` [[Website](https://etcher.balena.io/)] | [[Github](https://github.com/balena-io/etcher)]: Flash OS images to USB drives with one click.
- **Rufus** `Windows` [[Website](https://rufus.ie/)] | [[Github](https://github.com/pbatard/rufus)]: Fast and reliable USB bootable media creator.
- **Ventoy** `Windows / Linux` [[Website](https://www.ventoy.net/)] | [[Github](https://github.com/ventoy/Ventoy)]: Create bootable USB from multiple ISO files.

---

## Remote Desktop & Access
> Tools used to remotely access and manage development machines.

- **RustDesk** `Remote Desktop` `Linux / MacOS / Windows` [[Website](https://rustdesk.com)] | [[Github](https://github.com/rustdesk/rustdesk)]: Open-source, self-hostable remote desktop solution with low-latency access, file transfer, and cross-platform support.
- **TigerVNC** `Remote Desktop` `Linux / MacOS / Windows` [[Website](https://tigervnc.org/)] | [[Github](https://github.com/TigerVNC/tigervnc)]: Open-source, high-performance VNC server and client for remotely accessing graphical desktops.
- **Apache Guacamole** `Remote Gateway` `Web / Linux / MacOS / Windows` [[Website](https://guacamole.apache.org/)] | [[Github](https://github.com/apache/guacamole-server)]: Open-source, clientless remote desktop gateway accessible through a web browser; supports VNC, RDP, and SSH.
- **RealVNC** `Remote Desktop` `Linux / MacOS / Windows` [[Website](https://www.realvnc.com/)]: Reliable VNC-based remote access with cloud connectivity, direct connections, and cross-platform support.
- **Chrome Remote Desktop** `Remote Desktop` `Web` [[Website](https://remotedesktop.google.com/)]: Simple, free remote access solution for securely connecting to computers through a web browser.
- **AnyDesk** `Remote Desktop` `Linux / MacOS / Windows` [[Website](https://anydesk.com/)]: Fast, low-latency remote desktop with cross-platform support, file transfer, and remote administration features.
- **TeamViewer** `Remote Desktop` `Linux / MacOS / Windows` [[Website](https://www.teamviewer.com/)]: Popular cross-platform remote desktop and support platform with remote access, file transfer, device management, and collaboration features.
- **Mosh** `Remote Terminal` `Linux / MacOS / Windows` [[Website](https://mosh.org/)] | [[Github](https://github.com/mobile-shell/mosh)]: SSH-like remote terminal designed for unreliable or changing networks; maintains sessions when switching networks or temporarily losing connectivity.
- **MeshCentral** `Remote Management` `Linux / Windows` [[Website](https://meshcentral.com/)] | [[Github](https://github.com/Ylianst/MeshCentral)] — Open-source, self-hosted remote computer management platform with browser-based desktop, terminal, file transfer, and device administration.

---

## Archive & Compression
> Tools used to create, extract, compress, encrypt, and manage archives and compressed files.

- **PeaZip** `Linux / Windows / macOS` [[Website](https://peazip.github.io/)] | [[Github](https://github.com/peazip/PeaZip)]: Open-source archive manager supporting a wide range of formats, with encryption, archive conversion, secure deletion, file splitting, and portable versions.
- **Keka** `macOS` [[Website](https://www.keka.io/)] | [[Github](https://github.com/aonez/Keka)]: Native macOS file archiver supporting formats such as 7z, ZIP, TAR, GZIP, BZIP2, and XZ, with encryption and Finder integration.
- **7-Zip** `Linux / Windows / macOS` [[Website](https://www.7-zip.org/)] | [[Github](https://github.com/ip7z/7zip)]: Open-source file archiver with high compression ratios, broad format support, strong AES-256 encryption, and a lightweight command-line interface.
- **UPX** `Linux / macOS / Windows` [[Website](https://upx.github.io/)] | [[Github](https://github.com/upx/upx)]: Open-source executable packer that compresses supported binaries while keeping them directly executable, commonly used to reduce application and binary size.
- **The Unarchiver** `macOS` [[Website](https://theunarchiver.com/)]: Lightweight archive extraction utility for macOS with support for numerous legacy and less-common archive formats.
- **Bandizip** `Windows / macOS` [[Website](https://www.bandisoft.com/bandizip/)]: Fast archive utility with support for common compression formats, multi-core compression, archive repair, encryption, and convenient Windows integration.

---

## PDF Readers
> Tools used to view, read, annotate, search, and manage PDF documents.

- **Stirling-PDF** `Linux / MacOS / Windows` [[Website](https://stirlingpdf.com/)] | [[Github](https://github.com/Stirling-Tools/Stirling-PDF)]: Open-source, self-hosted web application for manipulating PDFs, including merging, splitting, conversion, compression, OCR, metadata editing, signing, and other document operations.
- **KOReader** `Linux / MacOS / Windows / Android` [[Website](https://koreader.rocks/)] | [[Github](https://github.com/koreader/koreader)]: Open-source document reader optimized for e-ink devices, supporting PDF, EPUB, DJVU, CBZ, MOBI, and other formats with extensive reading and layout controls.
- **SumatraPDF** `Windows` [[Website](https://www.sumatrapdfreader.org/)] | [[Github](https://github.com/sumatrapdfreader/sumatrapdf)]: Lightweight, open-source document viewer focused on fast startup and low resource usage; supports PDF, EPUB, MOBI, CBZ, CBR, and other formats.
- **MuPDF** `Linux / MacOS / Windows` [[Website](https://mupdf.com/)] | [[Github](https://github.com/ArtifexSoftware/mupdf)]: Lightweight, high-performance PDF and document viewer with a minimal interface and a strong focus on rendering performance.
- **PDFgear** `MacOS / Windows` [[Website](https://www.pdfgear.com/)]: Free PDF reader and editor with support for viewing, annotation, form filling, PDF conversion, editing, and AI-powered document interaction.
- **Adobe Acrobat Reader** `MacOS / Windows` [[Website](https://www.adobe.com/acrobat/pdf-reader.html)]: Widely used PDF reader with support for viewing, searching, printing, commenting, form filling, and basic document annotation.
- **Foxit PDF Reader** `MacOS / Windows` [[Website](https://www.foxit.com/pdf-reader/)]: Feature-rich PDF reader supporting viewing, annotation, form filling, document signing, and collaboration features.

---

## Web Browsers
> Tools used to browse the web, access online services, and manage web applications.

- **Firefox** `Linux / MacOS / Windows` [[Website](https://www.mozilla.org/firefox/)] | [[Github](https://github.com/mozilla-firefox/firefox)]: Open-source web browser developed by Mozilla with strong privacy controls, extensive extensions, developer tools, and cross-platform support.
- **Brave** `Linux / MacOS / Windows` [[Website](https://brave.com/)] | [[Github](https://github.com/brave/brave-browser)]: Privacy-focused Chromium-based browser with built-in tracker and advertisement blocking, fingerprinting protections, and optional privacy-oriented features.
- **Chromium** `Linux / MacOS / Windows` [[Website](https://www.chromium.org/)] | [[Github](https://github.com/chromium/chromium)]: Open-source browser project that forms the foundation of Chrome and many Chromium-based browsers, with support for modern web standards and developer tooling.
- **Mullvad Browser** `Linux / MacOS / Windows` [[Website](https://mullvad.net/browser)] | [[Github](https://github.com/mullvad/mullvad-browser)]: Privacy-focused Firefox-based browser developed by Mullvad and the Tor Project, designed to reduce tracking and browser fingerprinting.
- **Ladybird** `Linux / MacOS / Windows` [[Website](https://ladybird.org/)] | [[Github](https://github.com/LadybirdBrowser/ladybird)]: Independent open-source web browser and rendering engine project written in C++, developed separately from Chromium, Firefox, and WebKit.
- **Google Chrome** `Linux / MacOS / Windows` [[Website](https://www.google.com/chrome/)]: Popular Chromium-based browser with broad web compatibility, extensive extension support, synchronization, developer tools, and integration with Google services.
- **Microsoft Edge** `Linux / MacOS / Windows` [[Website](https://www.microsoft.com/edge)]: Chromium-based browser with strong web compatibility, developer tools, synchronization, productivity features, and Microsoft ecosystem integration.
- **Opera** `Linux / MacOS / Windows` [[Website](https://www.opera.com/)]: Chromium-based browser with integrated productivity features, sidebar applications, tab management, and additional built-in browsing utilities.
- **Vivaldi** `Linux / MacOS / Windows` [[Website](https://vivaldi.com/)]: Highly customizable Chromium-based browser offering advanced tab management, workspaces, keyboard shortcuts, built-in productivity tools, and extensive interface customization.
- **LibreWolf** `Linux / MacOS / Windows` [[Website](https://librewolf.net/)]: Privacy-focused Firefox fork with enhanced tracking protection, reduced telemetry, hardened defaults, and additional privacy-oriented configuration.

---

## Related Awesome Lists

- **[awesome-computer-vision-resources](https://github.com/mawady/awesome-computer-vision-resources)**: Structured learning reference for computer vision: from image fundamentals to research frontiers.
- **[awesome-computer-vision-tools](https://github.com/mawady/awesome-computer-vision-tools)**: Curated tools for the full CV pipeline: training, data augmentation, experiment tracking, inference, edge deployment, and MLOps.
- **[awesome-academic-cs](https://github.com/mawady/awesome-academic-cs)**: Academic resources for teaching and research in computer science.

---

## Contributing

Contributions are welcome! Before submitting, please review these guidelines.

### What We're Looking For

1. **Open-source & actively maintained** (updated within the past 2 years)
2. **Solves a real problem** for CS students, researchers, or professionals
3. **Has community adoption** (100+ GitHub stars is a good indicator)
4. **Educational value** (good documentation, learning resources)

### What We're NOT Looking For

- Duplicate entries
- Commercial products (even with free tiers)
- Abandoned projects (>2 years without updates)
- Niche tools with very small user base

### Submission Format

Format your suggestion like this:

```markdown
- **Name** `Platform(s)` [[Website](url)] | [[Github](url)]
  - One-sentence description of what it does.
  - Key features that make it stand out.
```

### Guidelines

- **Does this really belong here?** Check existing categories first. Don't fragment categories.
- **Creating a new category?** Ensure there are 3+ tools to justify it. Keep categories focused.
- **Test all links** before submitting to ensure they're current.
- **Respect the format** so the list remains consistent and scannable.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Mohamed Elawady](https://github.com/mawady) has waived all copyright and related rights to this work.

---

## Thanks

- The open-source community for building amazing tools
- Contributors who've improved this list
- [awesome.re](https://awesome.re) for the awesome badge and guidelines