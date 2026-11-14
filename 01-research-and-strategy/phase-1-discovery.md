# Phase 1: Discover & Define — Synapse

## 1. Problem Statement & Market Gap
Knowledge workers, UX researchers, and product strategists regularly synthesize large volumes of unstructured qualitative data (interview transcripts, user feedback, competitor benchmarks, and PDF reports). 

Current tools create three core bottlenecks:
1. **Linear Document Bottleneck (Notion, Google Docs):** Force multi-dimensional, interconnected ideas into rigid vertical lists, obscuring cross-cutting patterns.
2. **Infinite Canvas Sprawl (Miro, FigJam):** While spatial, large boards rapidly become cluttered. Manually dragging sticky notes into groups and drawing connector arrows consumes up to 40% of synthesis time.
3. **Context Stripping:** Condensing rich research insights into tiny sticky notes strips away source citations and user context.

**Solution:** **Synapse** is an AI-augmented spatial intelligence and sensemaking canvas that combines an infinite 2D workspace with semantic auto-clustering, AI-inferred relationship edges ("Synaptic Links"), and automated executive summaries.

---

## 2. Target Persona
* **Name:** Dr. Maya Lin
* **Role:** Senior UX Researcher & Product Strategist
* **Workflow:** Analyzes 30–50 qualitative interview notes and market benchmarks per sprint.
* **Core Pain Points:**
  * Loses spatial orientation when boards exceed 30+ frames.
  * Text becomes unreadable when zooming out to view the macro picture.
  * Must manually rewrite canvas findings into slide decks for executive stakeholders.
* **Primary Goal:** Ingest raw research notes onto a single canvas, automatically uncover thematic clusters and hidden links, and export a structured executive brief.

---

## 3. Core User Flows
1. **Flow 1 — Ingestion:** User imports or drops unstructured research cards onto the infinite canvas.
2. **Flow 2 — Spatial Sensemaking:** User marquee-selects loose cards and triggers `[Synthesize Canvas]`. The spatial engine clusters cards by semantic similarity, creates titled cluster boundaries, and draws dashed confidence edges between related nodes.
3. **Flow 3 — Semantic Zoom & Export:** User zooms smoothly across Micro (100% full card), Meso (50% summary badge), and Macro (20% thematic cluster map) levels, then opens the right-hand inspector to export an AI-generated executive brief.

---

## 4. Information Architecture (IA)
* **Top Bar:** Project breadcrumb, collaborator status, primary `[Synthesize Canvas]` trigger.
* **Left Collapsible Rail:** Unsorted Ingest Tray, tag filters, document sources, minimap toggle.
* **Center Infinite Viewport:** Semantic research cards, solid manual links, dashed AI "Synaptic" links, magnetic cluster enclosures, and a bottom floating tool dock (`Select`, `Pan`, `Add Card`, `Connect`, `Zoom`).
* **Right Context Inspector:** Node metadata, source citations, AI link confidence explanations, and cluster summary drawer.
