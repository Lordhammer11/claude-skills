# Jarvis Brain

> Persistent knowledge index across all lordhammer11 repos.
> Auto-synced daily · Last updated: 2026-05-29

## Active Work

| ID | Title | Status | Repo | Tags |
|----|-------|--------|------|------|
| `gemma3-metal-macos` | Gemma 3 Homebrew Formula — Metal GPU + Chat UI | 🟢 active | homebrew-tap | gemma3, metal, macos, ollama |
| `apex-agent` | Apex Agent Homebrew Formula | 🟢 active | homebrew-tap | agent, homebrew |
| `claude-skills-library` | Claude Skills Library (235+ skills) | 🟢 active | claude-skills | skills, claude, agents |
| `jarvis-brain` | Jarvis Brain — persistent knowledge index | 🟢 active | claude-skills | brain, jarvis, meta |
| `hammeros-ios-app` | HaMm3rOS iOS App | 🟢 active | claude-code-together | ios, swift, gemma3, brain |

## Entry Details

### gemma3-metal-macos
**Gemma 3 Homebrew Formula — Metal GPU + Chat UI**
- **Repo:** lordhammer11/homebrew-tap · **Branch:** main · **PR:** #1
- **Status:** active · **Updated:** 2026-05-29
- **Tags:** gemma3, metal, macos, ollama, ai, llm, homebrew, ui, gpu
- **Summary:** Homebrew formula that installs Google Gemma 3 locally on macOS with Metal GPU acceleration via Ollama. Embeds a Python interactive chat UI with model-size picker, coloured output, slash commands (/help /model /clear /save /quit), readline history, and conversation save-to-file.
- **Files:** Formula/gemma3.rb
- **Notes:** HEAD-only formula. Install: `brew install --HEAD lordhammer11/tap/gemma3`. Metal is auto-enabled on Apple Silicon via Ollama.

---

### apex-agent
**Apex Agent Homebrew Formula**
- **Repo:** lordhammer11/homebrew-tap · **Branch:** main
- **Status:** active · **Updated:** 2026-05-18
- **Tags:** agent, homebrew
- **Summary:** Existing Homebrew formula for Apex Agent in the tap.
- **Files:** Formula/apex-agent.rb
- **Notes:** Pre-existing formula — not modified in current sprint.

---

### claude-skills-library
**Claude Skills Library (235+ skills)**
- **Repo:** lordhammer11/claude-skills · **Branch:** main
- **Status:** active · **Updated:** 2026-05-29
- **Tags:** skills, claude, agents, engineering, marketing, finance, product, c-level
- **Summary:** 235+ production-ready skills across 9 domains: engineering, marketing, C-level advisory, product, project management, RA/QM, business growth, finance.
- **Files:** engineering-team/, marketing-skill/, c-level-advisor/, product-team/, project-management/, ra-qm-team/, business-growth/, finance/, engineering/
- **Notes:** See INSTALLATION.md for per-agent install commands.

---

### jarvis-brain
**Jarvis Brain — persistent knowledge index**
- **Repo:** lordhammer11/claude-skills · **Branch:** dev
- **Status:** active · **Updated:** 2026-05-29
- **Tags:** brain, jarvis, meta, knowledge, index, automation
- **Summary:** Central knowledge brain tracking all work, ideas, and creations across every repo.
- **Files:** brain/index.json, BRAIN.md, .claude/commands/brain.md, scripts/brain_update.py, .github/workflows/brain-sync.yml
- **Notes:** Query with `/brain` in Claude Code. Auto-syncs daily via GitHub Actions.

---

### hammeros-ios-app
**HaMm3rOS iOS App**
- **Repo:** lordhammer11/claude-code-together · **Branch:** dev · **PR:** #2
- **Status:** active · **Updated:** 2026-05-29
- **Tags:** ios, swift, swiftui, hammeros, gemma3, ollama, brain, mobile
- **Summary:** SwiftUI iOS app (iPhone + iPad, iOS 16+) — 5 tabs: Dashboard, Brain, Gemma chat, Ideas, Settings. Full context persistence (chat history, brain cache, tab state).
- **Files:** Sources/, Package.swift, README.md
- **Notes:** Open HaMm3rOS.swiftpm in Swift Playgrounds on iPhone/iPad — signs automatically with your Apple ID.

---

## Ideas (Backlog)

| ID | Title | Tags |
|----|-------|------|
| `idea-gemma3-swift-ui` | Native macOS SwiftUI app for Gemma 3 | macos, swift, ui, gemma3 |
| `idea-brain-web-dashboard` | Web dashboard for the Jarvis brain | web, brain, dashboard, visualization |

## Stats

| Metric | Count |
|--------|-------|
| Total entries | 5 |
| Active | 5 |
| Draft PR | 0 |
| Ideas backlog | 2 |
| Repos tracked | 4 |
