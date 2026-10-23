
# QLC Protocol
> **The Decentralized Data Exchange & Matching Standard.**
> *Zero servers. Zero databases. Pure client-side bitwise matching.*

---

## ⚡ What is QLC?

**QLC** is a lightweight, decentralized data exchange and matching protocol designed for human intent, preferences, and structured attributes. 

Think of it as the **QR Code for structured data and matching**: it takes complex profiles (hiring, real estate, social matchmaking, surveys) and compresses them into a high-density, lightning-fast binary state. No central servers, no middlemen, and complete data sovereignty.

---

## 🧠 Core Architecture: The 16x16 Matrix

Traditional forms and surveys are bloated and cause extreme cognitive load. QLC solves this using a **Hierarchical 16x16 Bitmask System**:

1. **Macro-Blocks (16 Categories)**: Users or communities define 16 core dimensions.
2. **Micro-Items (16 States per Block)**: Up to 256 bits of total resolution.
3. **Dual-Mode Flexibility**: 
   * **Quick Mode (16-bit)**: Perfect for instant everyday selections (ASL, quick filters, casual surveys).
   * **Pro Mode (256-bit)**: Deep, precise professional mappings (tech stacks, detailed real estate specs).

---

## 🛠️ How It Works (The 0.001s Match)

```text
[ User A: QLC String ] ──┐
                         ├──> [ Local JS Engine (Client-side) ] ──> 🟢 Green / 🔴 Red Match Result
[ User B: QLC String ] ──┘

 * Decentralized Lists: Anyone can fork, create, or adopt a community-driven list (e.g., frontend-v26.json, realestate-taipei.json) hosted anywhere (GitHub, IPFS, static storage).
 * Instant Local Compute: Both parties load the same standard list, generate their concise QLC code, and run a bitwise comparison directly in the browser.
 * Zero Trust Required: No personal data is uploaded to a cloud. The math speaks for itself.
🚀 Quick Start (For Developers)
1. The List Schema
A QLC list is simply a standard JSON structure mapping your 16x16 matrix:
{
  "protocol": "qlc-v1",
  "namespace": "tech.frontend",
  "version": "2026.10",
  "categories": [
    { "id": 0, "name": "Core Languages", "items": ["TypeScript", "Rust", "Go", "Python"] }
  ]
}

2. The Matching Engine
Drop this lightweight snippet into any frontend to compute instant matches:
// Example: Client-side bitwise intersection
function qlcMatch(codeA, codeB) {
  const intersection = codeA & codeB;
  const union = codeA | codeB;
  return (intersection / union) * 100; // Match Percentage
}

🌌 Ecosystem & Use Cases
 * Hiring & Talent: Instant peer-to-peer engineering skill matching without ATS gatekeepers.
 * Real Estate & Rentals: Quick binary filtering of floor levels, layouts, and orientations.
 * Micro-Surveys: 16-question ultra-fast market research with instant collective heatmaps.
 * Social / Matchmaking: Modern, secure evolution of chatroom ASL matching.
📜 Philosophy & License
QLC has no central authority, no required domains, and no commercial locks.
It is an open specification—like Markdown or Git. Take it, fork it, build your own lists, and run your matching engines anywhere you want.
Licensed under the MIT License.

