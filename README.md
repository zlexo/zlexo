# Alex

Final-year CS student at VU Amsterdam.

I make Minecraft mods for big YouTubers. The mods needed an engine, the engine needed an editor, and that led to a platform where other creators build their own. Now I'm building a voxel engine from scratch in C++20 and Vulkan.

Along the way I build the tools I need: a texture studio, map editors, and one window that runs all of them.

### Public

- [**perdix**](https://github.com/zlexo/perdix): a Minecraft-like voxel engine in C++20 and Vulkan, built the way a team builds software: an RFC before code, small reviewed PRs, and CI on every one (Linux and macOS, three sanitizers, clang-tidy, a software-Vulkan render run). 287 merged PRs, 1,000+ tests.
- [**deck**](https://github.com/zlexo/deck): one window for every local tool I run. Start, stop and tail them, a local CI runner, an AI reviewer that checks each PR against the repo's own rules, a merge gate, and a spend ledger with monthly caps.
- [**emoton**](https://github.com/zlexo/emoton): sources in, narrated explainer video out. The model fills a fixed schema, every claim cites a source page, and a validator sends bad output back.

### Private (happy to walk you through them)

- **Conduit** ([docs](https://conduit.zlex.me)): the Java engine under my Minecraft minigames. 11 modules, 400+ tests, mutation testing in CI.
- **Modplex** ([modplex.gg](https://modplex.gg)): remix Minecraft games with sliders and toggles instead of code, and share them. Runs on Conduit.
- **Client work**: a 72-day Minecraft build for a YouTube creator with ~4M subscribers.

contact@zlex.me · Amsterdam
