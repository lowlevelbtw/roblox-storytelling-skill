# Changelog

All notable changes to `roblox-town-cinematic-studio` / `roblox-town-director` are documented in this file.

## [0.1.1] - 2026-11-19 (Unvalidated Prototype)
### Architecture & Universal Compatibility
- Re-architected `roblox-town-director` from an Android-first filming assistant into a **universal, hardware-independent, provider-independent Roblox storytelling and content-production director** following the open [Agent Skills specification](https://agentskills.io/specification).
- Reorganized the creative production workflow into **12 stages (A–L)** across 6 natural-language operating modes (`IDEA`, `SCRIPT`, `SHOOT`, `POST`, `REVIEW`, `FULL`).
- Added explicit **3-Tier Capability-Based Production-Method Classification** (`Live Gameplay Staging`, `Custom Roblox Animation`, `Hybrid / External Production`) in `references/production-workflow.md` and templates.
- Documented the **"In This Town..."** high-concept rule-based Shorts storytelling format as a distinct reusable framework in `references/storytelling.md`.
- Added 6 dedicated platform integration guides under `integrations/` (`claude-code.md`, `claude-app.md`, `codex.md`, `chatgpt.md`, `gemini-cli.md`, `ai-studio.md`) aligned to documented discovery paths without duplicating `SKILL.md`.
- Integrated capability honesty ("Capability Limitations Never End the Conversation"), 4-part continuity checks, and flexible editing handles.

## [0.1.0] - 2026-11-18 (Initial Prototype)
- Initial repository scaffold, Dual-Gate evaluation rubric, templates, solo example, and 10-scenario evaluation suite.
