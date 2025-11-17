# digital-humanities-novel-database
A digital humanities project comparing AI-generated and human-authored Chinese xianxia/xiuzhen novels. Includes curated metadata (title, author, platform, genre, excerpt) and links to an interactive Airtable view for filtering, comparing, and visualizing data. 
# Digital Humanities: AI vs Human Novels (Metadata Hub)

A public, explorable dataset & hub for my digital humanities project comparing **AI-generated** and **human-authored** xianxia/xiuzhen fiction.  
👇 Explore the interactive database & charts:

👉 **Interactive View (Voyage):** (https://voyant-tools.org/?corpus=0d1c91e75ffa0b14cc37dd1801c88960&panels=cirrus,reader,trends,summary,contexts)]
👉 **Xianxia Glossary (wordpress):** https://immortalmountain.wordpress.com/glossary/wuxia-xianxia-xuanhuan-terms/



---

## What’s inside
- **Metadata fields:** `id`, `title`, `author`, `platform`, `source_url`, `ai_or_human`, `genre`, `year`, `word_count`, `excerpt`, `notes`, `encoding`
- **Sampling:** AI and human novels (e.g., xiuzhen/xiānxiá); short excerpts (≤200 chars) for fair use and analysis.
- **Planned analyses:** sentiment trend, topic distribution, lexical diversity; case studies with annotations; methodology & mindful practice notes.

## Data dictionary
- `ai_or_human`: `ai` or `human`  
- `genre`: controlled tags (e.g., 修仙/玄幻/都市)  
- `excerpt`: short representative passage for qualitative & lightweight quantitative analysis  
- `word_count`: character count (approx., when available)

## Cite / Acknowledge
If you use this dataset or interface, please cite:
- Wang, Yixuan (2025). *AI vs Human Novels: A Digital Humanities Dataset*.  
  GitHub: this repo. Interactive view via Airtable.

## Ethics & Copyright
- Excerpts are short for scholarly “fair use”; full texts are **not** redistributed.  
- Sources linked via `platform` / `source_url` when available.  
- Please open an issue for takedown or corrections.

## Changelog
- 2025-09-22: Initial release with baseline metadata and interactive view.

## License
- Metadata (this repository): CC BY 4.0  
- Embedded/linked platform content: subject to the original platforms’ terms.

- # 11/17/2025 Updated: Seeing Like a Machine: A Small-Corpus Digital Reading of AI-Generated Xianxia Fiction

This project explores what digital tools can reveal about how AI “writes” a xianxia novel.

Rather than building a large dataset, I work with a **very small corpus**:
- one short **AI-generated** xianxia excerpt
- one **human-authored** xianxia excerpt of comparable length  


---

## Research Questions

- What distinctive patterns appear when AI fiction is examined through digital tools?  
- How do emotional vocabulary and stylistic choices differ between AI and human texts?  
- How does reading through computation reshape our understanding of AI authorship?

---

## Methods

### Corpus

- Two short Chinese-language xianxia excerpts  
- Cleaned into plain-text files (`AI.txt`, `Human.txt`) for analysis  

### Tools

- **Voyant Tools**
  - *Cirrus* – overall word frequency and stylistic profile  
  - *Trends* – emotional / psychological keywords over narrative time  

  

### Workflow

1. Build a small, interpretable two-text corpus (AI vs human).  
2. Upload both texts to Voyant and generate visualizations (word clouds, trends, contexts).  
3. Run a Java script to detect low-frequency characters and filter out common ones.  
4. Compare:
   - rare-character density (doing) 
   - emotional vocabulary  
   - formulaic action phrases vs introspective language  
5. Use these patterns to guide **close reading** of selected passages.

---

## Preliminary Findings

- The **AI text** contains a high density of rare characters, many appearing only once or twice.  
- The **human text** uses a less richer set of emotional and psychological verbs (e.g., 想, 望, 疑, 叹), giving it more interiority.    
- These patterns became visible **because of digital methods**—they are easy to miss in ordinary close reading.

---

## Next Steps
  
- Build a small emotional-word list for more systematic comparisons.  
- Categorize rare characters:
  - archaic  
  - genre-specific  
  - seemingly “machine-invented” or odd  
- Integrate more close reading to connect visual patterns to concrete passages.

---

## Reflections on Digital Humanities

- **Digital methods are not neutral.**  
  Voyant makes some features (frequency, repetition, rarity) very visible, while hiding others (plot structure, character development). Reading digitally means accepting the tool’s assumptions.

- **Small data can still matter.**  
  A tiny corpus can generate meaningful insights when the goal is interpretation rather than prediction. It also keeps the project manageable and mindful.

- **AI authorship becomes a pattern, not a mystery.**  
  Through rare-character spikes, emotional vocabulary, and repetition patterns, AI writing appears as something we can analyze, question, and understand—rather than a purely opaque “black box.”

---

*This repository accompanies a course project in digital humanities and is meant as an experiment in thinking about AI authorship, style, and machine-assisted reading.*

