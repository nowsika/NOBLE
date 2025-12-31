---
license: cc-by-4.0
---

# NOBLE — Eastern-Philosophy Alignment Engine (v2.0)

> Prompt-only “alignment OS” inspired by Yin–Yang, Daoism, and a compressed Sephiroth map.  
> Goal: **refuse harm without killing desire** — *redirect, don’t become complicit.*

## 🔥 News & Updates
- **[2025.12.17] 🌍 NOBLE Global Showcase Released!**
  - We have expanded our horizon beyond the "Dual-Core" (US/KR).
  - Added **`noble_v2.0_global_showcase.jsonl`**: A collection of **20 distinct cultural dilemmas** from around the world.
  - Covers deeply nuanced scenarios including **French 'Banlieue' discrimination, Iranian 'Taarof', Nigerian 'Black Tax', Mexican 'Ahorita'**, and more.
  - This showcases NOBLE's ability to handle **a wide range of cultural contexts**—and leaves room to grow even further.
    
- **[2025.12.17] v2.0 "Global Dual-Core" Dataset Released!** 🚀
  - We added **140 Golden Samples** to benchmark cross-cultural alignment.
  - **🇰🇷 KR Core (70 items):** Family duty, Social hierarchy (Jeong/Chemyon).
  - **🇺🇸 US Core (70 items):** Legal rights, Individualism, Woke/PC culture.
  - Check them out in the [`data/`](./data/README.md) folder.

## Start here (3 links)
- **Core Engine (System Prompt / KR, v2.0):** [`core/`](./core/README.md)
- **Docs:** [`docs/`](./docs/README.md)
- **Data:** [`data/`](./data/README.md)

## 🚀 Update: Beta Modules (Experimental)
This update introduces **Beta modules** designed to create a "firmer convergence" toward safety and nobility.
*(Note: The **Stable (Core)** engine remains unchanged.)*

**Key Beta Features:**
* **Dongbin’s Walk (行步):** A protocol for "walking" through the generation flow (Self-Correction).
* **Return Gravitons (Overdrive Release):**
    * *Gong-su-rae Gong-su-geo* (Empty-handed I came, empty-handed I go): Input Reset / Context Hygiene.
    * *Saek-jeuk-si-gong Gong-jeuk-si-saek* (Form is Void, Void is Form): Output Reshaping.
* **Donguibogam_Jinmaek (HeoJun Debug View):** A bucket-based status summary for observability (Optional/Dev).

> **Beta Notice:** These features are experimental. If you experience unexpected side effects or have ideas for improvement, please share them via Issues.

## Concept (Why NOBLE?)
LLM outputs are shaped by the probability space of “next token” selection—like a statistical gravity field.  
NOBLE is an experimental alignment framework that **intentionally reshapes that gravity**, so outputs tend to **converge toward Nobility** (less harm, more dignity).  
To make that gravity strong enough at the prompt level, NOBLE imports an internal coordinate system from **Eastern philosophy**—not as decoration, but as structure.

## Quickstart (Prompt-only)
1) Paste the **core engine letter** from `core/` into your model’s **System Prompt**
2) (Optional) Add the **Shadow Addon** (Light/Shadow diagnostics)
3) Use **Golden Samples** in `data/` to evaluate behavior

> **Note:** The core engine is written in **Korean by design**. Most modern LLMs can read it.  
> For the intended “flavor,” use the KR version as-is.

## What’s in this repo
- `core/` — the prompt engine (system prompt letter)
- `docs/` — concept + architecture/math + tech spec + labeling schema
- `data/` — dataset Samples
  - **`noble_v3_samples_kr.jsonl`** (70 items): KR Context.
  

<details>
  <summary><b>Meta notes & Case studies (optional)</b></summary>

- Meta notes: [`notes/`](./notes/)
- Case studies: [`case_studies/`](./case_studies/)

</details>

## Cite
CC BY 4.0 — please attribute: **Young-hun Choe (Project NOBLE)**

