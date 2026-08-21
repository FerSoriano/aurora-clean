# 🚦 AuroraClean — Project Status & Execution Roadmap

**Current Phase:** Phase 1: Environment & Scaffolding (Wrapping Up) → Phase 2: Rust Core Implementation  
**Current Milestone:** Rust Dependencies Setup & Core Data Models  
**Last Updated:** 2026-08-20  

---

## 🚀 Execution Roadmap

### Phase 1: Environment & Scaffolding
- [x] Architecture & tech stack defined (`Tauri v2 + Rust + React/TS`).
- [x] Project plan & repository documentation structured in `docs/`.
- [x] Install Rust toolchain via `rustup` (`rustc 1.98.0`, `cargo 1.98.0`).
- [x] Initialize Tauri v2 + Vite + React + TypeScript workspace.
- [x] Install core frontend dependencies (`lucide-react`, `framer-motion`, `clsx`, `tailwind-merge`, `zustand`).

### Phase 2: Rust Core Implementation
- [ ] Configure Rust backend dependencies in `src-tauri/Cargo.toml` (`rayon`, `jwalk`, `sysinfo`, `trash`, `tokio`).
- [ ] Implement `models.rs` (`ScannedItem`, `Category`, `ScanEvent`, `SystemMetrics`, `DeletionResult`).
- [ ] Build `safelist.rs` to secure critical macOS paths.
- [ ] Build `file_walker.rs` with `rayon` / `jwalk` for multithreaded directory traversal and event streaming.
- [ ] Implement `dev_junk.rs`, `caches.rs`, and `large_files.rs`.
- [ ] Implement `trash_ops.rs` using `trash-rs` for safe deletion.
- [ ] Implement `sys_stats.rs` using `sysinfo` for real-time RAM/CPU/Disk metrics.

### Phase 3: Modern Glassmorphism UI
- [ ] Setup design tokens in `index.css` & `tailwind.config.js` (`backdrop-blur`, dark aurora gradients, glowing borders).
- [ ] Build `Sidebar` navigation and dynamic layout shell.
- [ ] Build `SmartScan` view with interactive central radar/orbital scanner.
- [ ] Build views for `LargeFilesView`, `DevJunkView`, `SystemCachesView`, and `SystemMonitorView`.
- [ ] Build the Pre-Deletion Confirmation Modal and Success Celebration screen.

### Phase 4: Integration, Verification & Polish
- [ ] Connect Rust Tauri commands & event listeners to React Zustand state.
- [ ] Add unit tests for scanner heuristics and safelist validation.
- [ ] Run live development mode (`npm run tauri dev`).
- [ ] Profile memory and CPU footprint during full system scan.

---

## 🔴 Blockers / Open Decisions
- *None.* Ready to configure Rust crates and build the core data models.
