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
