<div align="center">

# Hi, I'm Adrián Barriuso

**Web developer** · Higher Technician in Multiplatform Application Development (DAM)

I build web applications and take them to production, with care for
performance, accessibility and SEO. I deploy and run my own infrastructure.

[LinkedIn](https://www.linkedin.com/in/adri%C3%A1n-barriuso/)

**English** · [Español](README.es.md)

</div>

### Web

- **[Las Brasas de Losar](https://lasbrasasdelosar.com)** · *in production*: restaurant website I built and deployed end to end: front and back end without templates, in three languages (ES/EN/FR), self-hosted on my own infrastructure (Proxmox + Ubuntu LXC + Nginx + Cloudflare Tunnel) with automatic CI/CD deployment. **[Visit →](https://lasbrasasdelosar.com)**
- **[palafoxiana-redesign](https://github.com/abarriuso/palafoxiana-redesign)**: concept redesign of the Biblioteca Palafoxiana website: semantic HTML, accessibility (ARIA), ES/EN i18n and responsive AVIF/WebP images. Portfolio project, not affiliated with the institution. **[Try it →](https://abarriuso.github.io/palafoxiana-redesign/)**

### Desktop apps and homelab

- **[NASMirror](https://github.com/abarriuso/nasmirror)**: Windows app that keeps a copy of your folders on a NAS or an external drive, in one click. It shows what will change before anything happens and copies only what changed. In the benchmark, 6,000 small files copy 7× faster than dragging them in File Explorer, and copying them again when nothing has changed is 35× faster. Robocopy, or encrypted, versioned snapshots with restic; Wake-on-LAN and an unattended mode for Task Scheduler. Tauri 2 + React + Rust, MIT. **[Download →](https://github.com/abarriuso/nasmirror/releases/latest)**
- **[netscan](https://github.com/abarriuso/netscan)**: network scanner, live inventory and monitoring dashboard for homelabs. It brings nmap, RustScan, nuclei, scapy and mDNS together in one panel, with new/down device alerts and Proxmox VE, TrueNAS, AdGuard Home and Pi-hole integrations. FastAPI + React, one-command install (Windows, Linux, Proxmox LXC, Docker). Work in progress.
- **[bulkhead](https://github.com/abarriuso/bulkhead)**: Docker container for Windows with Claude Code, OpenCode and Open WebUI, connected to Claude or to a local model served by LM Studio or llama.cpp on the GPU. One container per project, unprivileged user, an outbound firewall that only lets allowed domains through, and persistent volumes. Docs in Spanish.

### Science and machine learning

- **[melanoma-detection](https://github.com/abarriuso/melanoma-detection)**: binary classification of dermoscopic images (benign / malignant) with transfer learning: VGG16, ResNet50V2 and EfficientNetV2S compared under the same protocol, with Grad-CAM. The demo runs all three models in the browser with TensorFlow.js. Not a medical tool. **[Try it →](https://abarriuso.github.io/melanoma-detection/)**
- **[Analemas](https://github.com/abarriuso/Analemas)**: the equation of time, the solar analemma, the retrograde loops of the planets and the pentagram of Venus, computed by an ephemeris engine written from scratch (IAU precession and nutation) and validated against NASA/JPL Horizons. Canvas 2D, dependency-free JavaScript. Idea and first prototype by Sandra Fernández Domínguez. **[Try it →](https://abarriuso.github.io/Analemas/)**

### 3D printing (OpenSCAD)

- **[bay2rack](https://github.com/abarriuso/bay2rack)**: parametric adapter that turns the 5.25" bays of an old PC case into a 6" mini rack for a homelab: switches, KVM over IP, Raspberry Pi blades, keystone patch panel. A browser configurator with a live 3D view (OpenSCAD compiled to WebAssembly, three.js) downloads every STL and the bill of materials; the promo film is rendered in Blender from the same models. **[Try it →](https://bay2rack.pages.dev/)**
- **[igneus-v2-et4-4010-led](https://github.com/abarriuso/igneus-v2-et4-4010-led)**: remix of Locos3D's IGNEUS V2 hotend carriage for the Anet ET4: adapters for 4010 blowers, LED mounts that light the nozzle, one-piece ducts and a 2510 → 30 mm fan adapter. Printed and running. The site has an interactive 3D viewer and a part generator (OpenSCAD) that makes the STL from your measurements. CC BY-NC-SA 4.0, like the original. **[Try it →](https://abarriuso.github.io/igneus-v2-et4-4010-led/)**

---

I use AI assistants during development. The design, the technical decisions, the validation and the code review are mine.
