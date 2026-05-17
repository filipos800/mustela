# 🦦 Mustela

> **Engineered for the Unforgiving.** High-performance static site engine and documentation reference forged for forensic documentation and high-pressure operations. Built to deliver data when failure isn't an option.

🌐 **Official Website:** [mustela.vercel.app](https://mustela.vercel.app)  
📖 **Documentation:** [mustela.vercel.app/doc/get-started](https://mustela.vercel.app/doc/get-started)  
📰 **Field Reports (Blog):** [mustela.vercel.app/blog](https://mustela.vercel.app/blog)  
📺 **Video Demonstration:** [Watch on YouTube](https://youtu.be/jJHkLPb4rk8?si=Y44YEYgpUfLiys4F)

### 📦 Ecosystem Repositories (Codeberg)

📦 **Mustela Web (Codeberg):** [codeberg.org/mustela/web](https://codeberg.org/mustela/web)  
⚡ **Mustela Preset Vite (Codeberg):** [codeberg.org/mustela/preset-vite](https://codeberg.org/mustela/preset-vite)  

---

Mustela is a blazing-fast static site engine (SSG) written in the **V language**. The entire architecture is built on the principle of "reductive engineering"—no unnecessary abstractions, zero dependencies, zero tracking, just pure performance optimized for the physical limits of hardware.

Validated by the creator of the V language ([Alex](https://x.com/v_language/status/2053465241535557759)), who confirmed build speeds exceeding **9,000 pages per second**, Mustela is the ultimate tool for high-pressure CI/CD pipelines and massive technical documentation hubs.

## 🎥 Video Demonstration

Watch the video [**Mustela SSG Demo: 1.3MB High-Speed Vlang Engine with Parallel Pipeline**](https://youtu.be/jJHkLPb4rk8?si=Y44YEYgpUfLiys4F) to see exactly how to spin up a Mustela website on your local machine using just the pre-compiled binary.

## ⚡ The Mustela Edge

- **Blazing Fast Performance:** Processes 5,000 Markdown files in 528 ms (~9,470 pages/sec) with warm-cache build times under 20 ms.
- **Zero-Dependency Core:** Distributed as a single, statically linked binary (~1.3 MB). No `node_modules`, no external registries.
- **Zero-Copy Architecture:** Strictly avoids redundant memory allocations by passing raw pointers across a stateful DSL engine.
- **Minimal Memory Footprint:** Standard builds consume around 4.8 MB RAM, eliminating the risk of memory-exhaustion attacks.
- **Unix-First Philosophy:** Leverages native system calls (e.g., `inotify` on Linux) for zero-latency filesystem monitoring.
- **Total Sovereignty & GDPR-Compliant:** Contains zero telemetry, analytics, or "phone-home" features. Operates 100% locally and offline.

## 🛠 Quick Start

Scaffold your project in under a minute:

```bash
# For pure HTML/CSS with maximum simplicity (Vanilla preset)
mustela init

# For modern pipelines with Tailwind CSS, PostCSS, and Vite (Vite preset)
mustela init -p vite

# Perform a one-time build into the ./dist folder
mustela build

# Start local development mode with real-time filesystem hot-reloading
mustela watch
```

## ⚙️ Source Code & Licensing

The core **Mustela Engine is private source**. The entire system was coded completely from scratch without a single external library or runtime framework.

This approach is driven by a clear pragmatic and economic model:

- **Custom B2B Hardware Tuning:** The engine serves as the baseline for commercial enterprise solutions (such as Mustela Tactical Edition). Binaries are compiled and tuned directly on the client's production servers using `-march=native` and CPU-specific compiler flags to extract every microsecond of throughput.
- **Absolute Supply-Chain Integrity:** We guarantee the complete absence of hidden telemetry, third-party vulnerabilities, or backdoors—making it ideal for forensic, air-gapped, and high-security infrastructure.

## 🤝 Contribution Policy

While the repository remains closed-source, Mustela welcomes developers who share the same extreme technical discipline. If you wish to contribute, the pipeline is entirely built on personal arrangement:

- **Collaboration Request:** Contact me directly. Every proposed feature and architectural alignment will be reviewed personally by the lead architect (Filip Vrba) to keep the core codebase lean and zero-bloat.
- **Revenue Share:** If your contribution is approved and integrated into the commercial B2B offerings, an equitable revenue share from license sales will be established. True engineering skill should never work for free.

---

Designed and maintained by Filip Vrba.  
Mustela Engine © 2026. All rights reserved.
