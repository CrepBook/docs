# CrepBook Roadmap

This roadmap describes the planned development of CrepBook.

The goal: a fast, Markdown-first, AI-assisted note system with reliable sync and an extensible plugin ecosystem.

> Status legend:  
> ✅ done · 🚧 in progress · 🧩 planned

---

## Phase 1 — Markdown Editor (Core)

**Goal:** a usable local-first app for writing and organizing Markdown notes.

### Editor
- 🧩 Basic Markdown editor (desktop first)
- 🧩 Live preview (toggle / split view)
- 🧩 File-based vault/workspace (folder + indexing)
- 🧩 Autosave + crash recovery
- 🧩 Basic formatting shortcuts

### Organization
- 🧩 Tags
- 🧩 Wiki-links / backlinks
- 🧩 Note list + pinned notes
- 🧩 Search (title + full text)

### UX baseline
- 🧩 Fast startup
- 🧩 Keyboard-first navigation (core shortcuts)
- 🧩 Settings (theme, editor preferences)

---

## Phase 2 — AI Functionality

**Goal:** AI tools that improve writing and navigation without locking users in.

### AI tools (local UI)
- 🧩 Summarize note / selection
- 🧩 Rewrite: shorter / clearer / formal / casual
- 🧩 Extract action items / key points
- 🧩 Smart tags & titles suggestions

### Q&A over notes
- 🧩 Ask questions about the current note
- 🧩 Ask across a workspace (index-based)

### Safety & control
- 🧩 Clear “what is sent to AI” boundaries
- 🧩 Opt-in settings for AI features
- 🧩 Caching + cost control (if using paid models)

---

## Phase 3 — Sync Server

**Goal:** secure cross-device sync with conflict handling.

### Accounts & auth
- 🧩 User accounts
- 🧩 Sessions / tokens
- 🧩 Device registration

### Sync
- 🧩 Upload/download notes
- 🧩 Versioning
- 🧩 Conflict resolution strategy (spec first)
- 🧩 Encrypted at rest (server-side)
- 🧩 Optional end-to-end encryption (stretch)

### Operations
- 🧩 Deployment plan (Docker)
- 🧩 Backups / restore
- 🧩 Monitoring basics

---

## Phase 4 — Plugin Ecosystem

**Goal:** allow community extensions without bloating the core app.

### Plugin API
- 🧩 Plugin runtime model (permissions, sandboxing)
- 🧩 UI extensions (commands, panels, context actions)
- 🧩 Data access rules (read/write boundaries)

### SDK & examples
- 🧩 Plugin template
- 🧩 Documentation + examples

### Plugin distribution
- 🧩 Plugin registry service
- 🧩 Plugin publishing & updates
- 🧩 Verification/signing (optional)

---

## Later / Nice-to-have

- 🧩 Mobile clients
- 🧩 Collaboration features
- 🧩 Public sharing / publishing notes
- 🧩 Graph view / visual knowledge map
- 🧩 Import/export tools (Obsidian, Notion, etc.)

---

Roadmap will evolve with feedback and development progress.
