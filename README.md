# CS Self-Learning

[![Website](https://img.shields.io/badge/website-tingggggg.github.io%2Fcs--self--learning-red)](https://tingggggg.github.io/cs-self-learning/)

My CS self-learning log: open courses, labs, and side projects, organized by topic. The layout follows [PKUFlyingPig/cs-self-learning](https://github.com/PKUFlyingPig/cs-self-learning).

Each page records what the course covers, what I implemented, and links to my code and notes. Status: ✅ done · 🚧 in progress.

## Catalog

### Operating Systems

| Course / Project | Links | Status |
| --- | --- | --- |
| [NTHU OS: NachOS](docs/operating-systems/nthu-nachos.md) | [Code](https://github.com/tingggggg/NTHU_Nachos_Project) | ✅ |
| [Raspberry Pi OS (ARMv8)](docs/operating-systems/raspberry-pi-os.md) | [Code](https://github.com/tingggggg/OSDIg) · [Notes](https://hackmd.io/@timm/osdi) | ✅ |
| [RISC-V OS (QEMU)](docs/operating-systems/riscv-os.md) | [Code](https://github.com/tingggggg/riscv-operating-system/tree/main/os) | ✅ |

### Linux Kernel

| Course / Project | Links | Status |
| --- | --- | --- |
| [NCKU Linux Kernel Internals: fibdrv](docs/linux-kernel/ncku-linux-kernel.md) | [Code](https://github.com/tingggggg/fibdrv) · [Notes](https://hackmd.io/@timm/fibdrv) | ✅ |

### Computer Vision

| Course / Project | Links | Status |
| --- | --- | --- |
| [Advanced Digital Image Processing](docs/computer-vision/advanced-dip.md) | — | ✅ |

## Adding a New Entry

1. Copy [template.md](./template.md) into the matching `docs/<category>/` folder.
2. Add the page to `nav` in [mkdocs.yml](./mkdocs.yml).
3. Add a row to the catalog in this README and in [docs/index.md](./docs/index.md).

Preview locally:

```bash
pip install -r requirements.txt
mkdocs serve
```
