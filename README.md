# Coral Coast Youth Voices (prototype)

Prototype by [92 Logics](https://www.92logics.com), prepared as a sample for UNICEF Mozambique LTA work on AI-based solutions for qualitative data (LRPS-PS-2026-9206783). It is **not** an official UNICEF system. Fictional sample data only. Scripted AI suggestions only.

Live demo: https://92logics.github.io/unicef-qual-ai-demo/

## What it shows

A public, clickable sample of AI-assisted qualitative analysis for a fictional coastal youth study (**Coral Coast Youth Voices** — not a real place or real respondents).

| Screen | What you can do |
| --- | --- |
| **Início · Home** | Study brief, ethics banner (*Prototype / fictional data*), click-through guide. Light Portuguese chrome labels only. |
| **Ingest** | Pick from 8 preloaded KII/FGD transcripts or “upload” a local `.txt` (stays in the browser). Timestamped transcript viewer. |
| **Coding** | Scripted auto-suggested codes with human **accept / edit / reject**, shared codebook, and an audit log. |
| **Themes** | 4–5 themes with quote evidence; cosmetic merge/split. |
| **Dashboard** | Theme prevalence, sentiment-lite tags, respondent segments; CSV and print/PDF export in-browser. |
| **Relatório · Report** | Template narrative with mandatory human **approve / request-changes** and review history. |

The AI suggestions and report draft are scripted templates. Nothing calls a live AI API, nothing is uploaded to a server, and nothing leaves the browser. There are no API keys and no real personal data. No UNICEF logos or affiliation claims.

## How it maps to collect / process / analyse / report

| TOR capability | What this prototype shows |
| --- | --- |
| **Collect** | Ingest of KIIs/FGDs (preloaded + local file), modality and timestamps, segment labels |
| **Process** | Coding workspace with suggested codes, human decisions, codebook, audit trail |
| **Analyse** | Theme clustering with quote evidence; dashboard prevalence, sentiment-lite, segments |
| **Report** | Editable narrative draft with mandatory human approve / request-changes and history |

## Intended production stack

- **Qualitative / AI layer:** Python services with an LLM **behind mandatory human review** (no unsupervised publication of codes or narratives).
- **Application shell:** ASP.NET Core with React.
- **Database:** SQL Server.
- **Hosting:** UNICEF-directed cloud or tenant (region/residency as specified at award / call-off).
- **Languages:** English primary; Portuguese delivery via named capacity (employee or partner) as agreed — this demo only uses light UI labels, not live Portuguese NLP.

## Run it

Open `index.html` in a browser, or use the GitHub Pages copy. No install and no build step.

## Accessibility

Skip link, visible focus outlines, keyboard-operable tabs, and a polite live region for status messages.

## Disclaimer

This is a 92 Logics prototype. It is not an official UNICEF system and is not connected to any UNICEF or government system. All places, people, transcripts and quotes are fictional. The AI suggestions and report drafts are scripted templates, not output from a live AI service.

## Contact

92 Logics · cowork@92logics.com · https://www.92logics.com
