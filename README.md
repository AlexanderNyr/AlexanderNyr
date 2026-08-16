# Hi, I'm Alexander 👋

**I build hard things from scratch.**

An x86_64 operating system. A physics engine. A multiplayer FPS with no game engine. Minecraft shaders in raw GLSL. A falling-sand sim with a nuclear-physics layer. A small LLM. I pick the language that fits the problem — **C, C++, Rust, Kotlin, GLSL, Python, C#** — and I avoid black boxes: if a subsystem is interesting, I'd rather write it myself than import it.

This shows up in my own **AuraLite** projects *and* in open source, where I'm just as happy translating docs or chasing a Unicode bug in someone else's repo. Several of these ship **versioned releases** — 25 on the shader pack, 11 on the FPS, plus the OS.

---

### 🏔 Flagship

- **[AuraLite-OS](https://github.com/AlexanderNyr/AuraLite-OS)** — a from-scratch **x86_64 hobby OS**: custom BIOS + UEFI bootloader (NASM & freestanding C), higher-half kernel, preemptive multitasking, Ring 3 ELF userland + small libc, a VFS (tmpfs / FAT32 / ext2), an e1000 TCP/IP stack with DNS, AHCI & USB, and a kernel framebuffer GUI compositor. *This is my main focus right now.*

### 🧩 The AuraLite ecosystem

| | Project | What it is |
| --- | --- | --- |
| 🖥 | [AuraLite-OS](https://github.com/AlexanderNyr/AuraLite-OS) | from-scratch x86_64 OS — kernel, networking, GUI compositor | `C` · `NASM` |
| ⚙️ | [AuraLite-Physics-Engine](https://github.com/AlexanderNyr/AuraLite-Physics-Engine) | GJK/EPA/SAT collision, sequential-impulse rigid-body dynamics, joints, CCD, PBF fluids, XPBD cloth — zero deps, 116 tests | `Rust` |
| 🎮 | [AuraLite-FPS-Game](https://github.com/AlexanderNyr/AuraLite-FPS-Game) | **LAN FPS** — no engine. Authoritative server + Android client, hand-written OpenGL ES 3.2, UDP snapshots | `Kotlin` |
| 🌌 | [AuraLite-Shaders](https://github.com/AlexanderNyr/AuraLite-Shaders) | Minecraft shaders on OpenGL 4.6: true TAA (Halton + YCoCg), HDR bloom, godrays, SSR, SSAO | `GLSL` |
| ☢️ | [AuraLite-Powder](https://github.com/AlexanderNyr/AuraLite-Powder) | Powder-Toy-style sim **with nuclear physics** — fission (U-235/Pu-239), fusion (D+T), chain reactions & meltdowns; desktop + WebAssembly | `Rust` |
| 🩸 | [AuraLite-Horror-Game](https://github.com/AlexanderNyr/AuraLite-Horror-Game) | **AnxietyHorror** — first-person psychological horror, fully procedural world/audio, PBR renderer (C++ desktop, Java/Android) | `C++` · `Java` |
| 🗺 | [AuraLite-world-generator](https://github.com/AlexanderNyr/AuraLite-world-generator) | procedural rural-world generator: FBM terrain + hydraulic erosion, villages, A* roads, rivers, biomes | `C#` · `Unity 6` |
| 🧠 | [AuraLite-AI](https://github.com/AlexanderNyr/AuraLite-AI) | educational LLM in PyTorch: RoPE/GQA/KV-cache, quantization (GPTQ/AWQ/HQQ/FP8), RAG, OpenAI-compatible FastAPI server | `Python` |
| 🛠 | [AuraLite-Realistic-Crafting](https://github.com/AlexanderNyr/AuraLite-Realistic-Crafting) | 1,258 reworked Minecraft recipes — shipped as datapack + Fabric + Forge | `Python` |
| 🎨 | [AuraLiteResourcePack](https://github.com/AlexanderNyr/AuraLiteResourcePack) | companion Minecraft resource pack | — |

### 🎯 Also

- **[telegram-bot-moderator](https://github.com/AlexanderNyr/telegram-bot-moderator)** (`Python`) — a full-featured Telegram moderation bot: warns/mutes/bans, trigger-word filtering, anti-spam, chat statistics, permissions.

### 🤝 Open-source contributions

- **[claude-code-cache-fix #334](https://github.com/cnighswonger/claude-code-cache-fix/pull/334)** — full French README translation. *Merged* — "this shipped because you did the hard part."
- **[scam-guardian #7](https://github.com/rusmoody/scam-guardian/pull/7)** — Turkish fraud-pattern dataset (18 tactic groups, 199 markers, sourced from public reports) **+ a Unicode fix** so all-caps scam SMS match despite the dotted/dotless-`i` collapse.
- **[melcloudhome #250](https://github.com/andrew-blake/melcloudhome/pull/250)** — Home Assistant integration: 5 new translations (cs, da, hu, pl, si).

### 🛠 Languages & tools

`C` · `C++` · `Rust` · `Kotlin` · `Python` · `C#` · `GLSL` · `NASM` · Git (GPG-signed) · GitHub Actions · Docker · Unity · PyTorch

---

### 📫 Get in touch

- 📧 Email: nyrovaleksandr80@gmail.com
