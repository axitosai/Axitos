# Axitos — Book Publishing & Metadata Kits

A working repository of **publisher-grade metadata and discoverability kits**, one per book title. Each kit is a ready-to-implement package for launching a book across **Amazon (KDP)**, **IngramSpark**, and the open web (**SEO / AEO / GEO**), plus assets for the marketing team — all built to support a high-conversion sales pitch within **1–3 months** of launch.

---

## Why this repo exists

Publishing a book well is a metadata problem as much as a writing one. Retailers (Amazon, Ingram), search engines (Google), answer engines (AI assistants), and generative engines (ChatGPT, Gemini, Perplexity) each need the *right* words in the *right* fields to make a book discoverable and to convert browsers into buyers.

This repo standardizes that work: for every title, we produce the **same complete set of deliverables** so nothing is missed and every book launches with professional, consistent, search-optimized metadata.

---

## How it's organized

```
/
├── README.md                         ← you are here (global guide + standards)
├── TEMPLATE.md                       ← blank checklist of deliverables (copy for each new book)
└── <book-title-slug>/                ← one folder per title
    └── <Book-Title>-Publishing-Kit.md
```

- **One folder per title**, named with a lowercase slug (e.g. `secrets-of-sage/`).
- Inside, the primary deliverable is `<Book-Title>-Publishing-Kit.md`.
- Supporting assets for that title (sell sheets, cover copy variants, ad drafts, discussion guides, etc.) can live alongside it in the same folder.

### Current titles
| Title | Author | Folder | Status |
|---|---|---|---|
| Secrets of Sage | Keven Baxter | [`secrets-of-sage/`](./secrets-of-sage/) | Complete |
| All Powers of God Almighty | Pastor Dr. Gabriel Ayorinde | [`all-powers-of-god-almighty/`](./all-powers-of-god-almighty/) | Complete |

---

## What every kit includes (the standard deliverables)

Each book's kit delivers, in this exact order:

1. **70-Word Author Bio** — for the back cover
2. **150-Word Author Bio** — for Amazon & IngramSpark
3. **500-Word Author Bio** — for marketing team use
4. **120-Word Book Summary** — for the back cover
5. **350-Word Book Summary** — for Amazon & IngramSpark
6. **Book Genre & Sub-Genre**
7. **Category Search** — Amazon browse placements (print + Kindle)
8. **IngramSpark Categories**
9. **Regional Subject** *(Ingram)*
10. **Thema Qualifiers** *(Ingram)*
11. **Thema Subjects** *(Ingram)*
12. **Amazon BISAC Categories**
13. **Keywords Search** — for Ingram and Amazon
14. **SEO / AEO / GEO Meta Titles** — ≤60 chars (SEO) and ≤90 chars (AEO/GEO)
15. **SEO / AEO / GEO Meta Descriptions** — ≤160 chars (SEO) and ≤200 chars (AEO/GEO)
16. **Target Audience & Reading Level**

**Marketing extras** (added for the marketing team's use):

17. **AEO FAQ** — answer-engine-optimized Q&A block
18. **GEO Citation Snippet** — a quotable, fact-dense paragraph for generative engines
19. **Product Schema** — schema.org `Book`/`Product` JSON-LD
20. **Author Schema** — schema.org `Person` JSON-LD
21. **Comparable Titles**
22. **Trending Reader Angles**
23. **Search Visibility Score**

---

## Standards & conventions

- **Character limits are hard limits.** Meta titles and descriptions are always counted and kept within the SEO/AEO/GEO caps above.
- **Word counts hit their targets.** Bios and summaries are written to the specified length.
- **Codes are verified, not guessed.** BISAC codes are checked against the current [BISG](https://www.bisg.org/) list; Thema subjects/qualifiers against the latest [EDItEUR Thema](https://ns.editeur.org/thema/en) release at time of writing.
- **Placeholders are flagged.** Anything the author/publisher must supply later (ISBN, price, page count, cover URL, buy links, review counts) is written in `[brackets]` so it's easy to find and fill before going live.
- **Faith/values, audience, and comps are stated as facts** so answer/generative engines can cite them reliably and consistently across every channel.

---

## Adding a new book

1. Share the book's information in the chat (title, author, bios, synopsis, audience, sample chapters, goals — as much as you have).
2. A new folder `<book-title-slug>/` is created with a fresh `Publishing-Kit.md` built from [`TEMPLATE.md`](./TEMPLATE.md).
3. The kit is committed on its own branch and opened as a pull request for review.
4. The "Current titles" table above is updated.
