Final-year CS student at VU Amsterdam.

I make Minecraft mods for big YouTubers. The mods needed an engine, the engine needed an editor, and that led to a platform where other creators build their own. Now I'm building a voxel engine from scratch in C++20 and Vulkan.

Along the way I build the tools I need: a texture studio, map editors, and one window that runs all of them.

### Public

- [**perdix**](https://github.com/zlexo/perdix): a Minecraft-like voxel engine in C++20 and Vulkan, built the way a team builds software: an RFC before code, small reviewed PRs, and a CI pipeline (Linux and macOS, three sanitizers, clang-tidy, a software-Vulkan render run). 299 merged PRs, 1,000+ tests.
- [**deck**](https://github.com/zlexo/deck): one window for every local tool I run. Start, stop and tail them, a local CI runner, an AI reviewer that checks each PR against the repo's own rules, a merge gate, a spend ledger with monthly caps, and a private notes vault that every Claude Code session reads before it acts, pushed only to a private repo after a secret scan.
- [**atlas**](https://github.com/zlexo/atlas): an index for a folder of markdown notes, installed as a Deck app. Provenance on every entry, maps by tag, a report of notes that repeat each other, and a red banner when the index no longer matches the files.
- [**emoton**](https://github.com/zlexo/emoton): sources in, narrated explainer video out. The model fills a fixed schema, every claim cites a source page, and a validator sends bad output back.
- [**apps**](https://github.com/zlexo/apps): games and apps for general use at apps.zlex.me, each on its own address and made for an iPad or phone home screen. First is Strum, a guitar songbook with chord diagrams, words lit as they're sung and backing parts that slow down in key; Gemlight, a puzzle game, is next. Static apps on Cloudflare's free plan, the heavy work on a Mac through a tunnel.

### Private (happy to walk you through them)

- **Conduit** ([docs](https://conduit.zlex.me)): the Java engine under my Minecraft minigames. 11 modules, 400+ tests, mutation testing in CI.
- **Modplex** ([modplex.gg](https://modplex.gg)): the editor for games on Conduit, after Conduit Studio. It started as my own dev tool and is on its way to creators: remix a game with sliders and toggles instead of code.
- **Client work**: a 72-day Minecraft build for a YouTube creator with ~4M subscribers.

contact@zlex.me · Amsterdam
