# AURA — Asset Unified Reasoning Agent

**Problem 08 · AI for Industrial Knowledge Intelligence: Unified Asset & Operations Brain**

> An AI that connects the knowledge scattered across an industrial plant — engineering, maintenance, reliability, safety, compliance and email — into one queryable brain, and surfaces what no single team can see.

AURA is not a better search box. It is a reasoning layer that links maintenance history, sensor data, manufacturer manuals, safety reports, regulations and email into a single knowledge graph, then answers any question with **cited, confidence-scored** intelligence — on any device.

---

## Demo in 30 seconds

Open **`aura_copilot.html`** in any modern browser.

1. Click the **"Why does P-1101A keep failing?"** question.
2. Watch AURA connect four separate systems and conclude the real root cause is **shaft misalignment** — not the seal that kept getting replaced.
3. Open the **Knowledge Graph** tab and click the **Misalignment** node to see the hidden link light up.
4. Toggle the **phone icon** for the field/mobile experience.

> **Live AI vs Demo mode:** In *Live AI* mode the prototype performs real retrieval-augmented generation over the document set. *Demo* mode gives instant, offline-safe answers for recording.

---

## The demonstration scenario

One critical pump (`P-1101A`) at a fictional refinery fails three times in eight months. Every clue lives in a different system, and no one connects them:

| System | What it held |
|--------|--------------|
| CMMS | 3 work orders — each closed as an isolated seal replacement |
| Reliability | Vibration rising 2.8 → 4.5 → 7.1 mm/s — textbook misalignment |
| OEM manual | Misalignment is the #1 cause of repeat seal failure |
| Email | Two engineers diagnosed it — but no work order was ever raised |
| Compliance | A required root-cause analysis was never done |

AURA fuses all five in seconds.

---

## What's in this repo

```
aura_copilot.html            # The working prototype (RAG copilot + knowledge graph)
aura_architecture.png        # Reference architecture diagram
AURA_Submission_Document.pdf # Detailed submission document
AURA_Pitch_Deck.pptx         # Pitch deck
/corpus                      # Sample industrial document set (8 PDFs) the demo runs on
```

## How it works

`Sources → Ingest & Understand → The Unified Brain → Agentic Intelligence → Point of Need`

- **Ingest & understand** — OCR + document intelligence, computer vision for P&ID/drawing parsing, LLM entity & relationship extraction, industrial-ontology mapping.
- **The unified brain** — a knowledge graph + vector store, kept live by continuous sync.
- **Agentic intelligence** — RAG copilot plus purpose-built agents for root-cause analysis, compliance-gap detection, and lessons-learned mining.
- **Point of need** — engineer web console, field mobile app, cited answers, one-click compliance evidence packs.

## Tech

`RAG` · `Knowledge Graph` · `Industrial Ontology` · `Computer Vision (P&ID)` · `OCR & Document Intelligence` · `Vector Embeddings` · `Agentic AI` · `QMS Integration`

## Deliverables

- Working prototype · Reference architecture · Detailed document · Pitch deck · Demo video

## Team

**Viktory** — Vikas Yadav

Demo video: [ paste link ]

---

*The plant, asset and document set used in the demonstration are illustrative and fictional.*
