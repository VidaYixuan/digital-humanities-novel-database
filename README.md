# digital-humanities-novel-database
A digital humanities project comparing AI-generated and human-authored Chinese xianxia/xiuzhen novels. Includes curated metadata (title, author, platform, genre, excerpt) and links to an interactive Airtable view for filtering, comparing, and visualizing data. 
# Digital Humanities: AI vs Human Novels (Metadata Hub)

A public, explorable dataset & hub for my digital humanities project comparing **AI-generated** and **human-authored** xianxia/xiuzhen fiction.  
👇 Explore the interactive database & charts:

👉 **Interactive View (Voyant):** [[(https://voyant-tools.org/?corpus=0d1c91e75ffa0b14cc37dd1801c88960&panels=cirrus,reader,trends,summary,contexts)]](https://voyant-tools.org/?corpus=3113b8b25a46d2fd2196838d0ae7762d&panels=cirrus,reader,trends,summary,contexts)](https://voyant-tools.org/?corpus=3113b8b25a46d2fd2196838d0ae7762d&panels=cirrus,reader,trends,summary,contexts)
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
  - *Cirrus* – overall word frequency profile  
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

  ## 🌟 Project Update — December 9, 2025 (emotion words updates)

This final update reflects a refined direction for my Digital Humanities project. Over the semester, my focus has developed to make a **interpretive, and tool-assisted reading of AI vs. human xianxia fiction**.

This version of the project emphasizes:
- 🧭 A clearer research question about *narrative logic* and *emotional structure*
- 📊 The use of **Voyant Tools** (Trends, Bubblelines) to reveal stylistic and structural patterns
- ✨ A new set of **geometric visual signatures** that distinguish human teleology from AI stochasticity
- 🔠 A computational replication using Python that helped to figure out how Chinese words can be successflully telled by Voyant
- 
- 

Rather than trying to “prove” whether AI can write like a human, this update frames the project as an exploration of **what becomes visible when we read through machines**—and how narrative patterns differ when authorship is algorithmic versus intentional.

 Emotions & Sensations words
1. (Positive Emotions): 笑 (Laugh / Smile), 高兴 (Happy / Glad), 欢 (Joy / Delight), 喜 (Happy / Joyful), 乐 (Joy / Fun), 兴 (Excitement / Interest), 悦 (Delight / Pleased), 爱 (Love), 柔 (Gentle / Soft), 温柔 (Tenderness / Gentle), 满意 (Satisfied / Content), 欣喜 (Ecstatic / Joyfully surprised), 欣慰 (Relieved / Gratified), 愉 (Pleasant / Cheerful), 愉快 (Happy / Cheerful), 兴奋 (Excited), 激动 (Agitated / Thrilled / Emotional)

2.  (Negative Emotions): 苦 (Bitter / Suffering), 痛 (Pain), 痛苦 (Suffering / Agony), 哭 (Cry), 泪 (Tears), 悲 (Sad / Sorrow), 悲伤 (Sorrow / Sadness), 哀 (Grief / Mourning), 愁 (Worry / Melancholy), 怒 (Anger / Rage), 恨 (Hate / Hatred), 怨 (Resentment), 憎 (Detest / Abhor), 恐 (Fear / Dread), 怕 (Scared / Afraid), 惧 (Fear), 惊 (Surprise / Shock / Fright), 累 (Tired / Weary), 疲 (Fatigue / Exhausted), 心酸 (Heartbroken / Poignant), 难过 (Sad / Upset), 冷酷 (Cold-blooded / Ruthless)

3. (States & Cognition): 想 (Think / Miss), 感 (Feel / Sense), 觉 (Feel / Perceive), 恍惚 (Trance / Absent-minded), 犹豫 (Hesitate), 好奇 (Curious), 平静 (Calm / Peaceful), 冷静 (Cool-headed / Calm), 腼腆 (Shy / Bashful)

This README now includes:
- A reorganized project overview  
- Updated methodology and corpus description  
- Summarized key findings  
- A Python snippet that reconstructs the logic behind Voyant’s relative-frequency analysis
- The Python I have tried to use for adding spaces:
- import jieba

# 读取原文件
with open('人蜜_作者_黑猫白袜子_3_.txt', 'r', encoding='utf-8') as f:
    text = f.read()

# 分词
words = jieba.cut(text)
result = ' '.join(words)

# 保存结果
with open('人蜜_分词版.txt', 'w', encoding='utf-8') as f:
    f.write(result)

print("分词完成！")

This version represents my final DH project for Fall 2025, highlighting both digital technique and humanistic interpretation.


---

*This repository accompanies a course project in digital humanities and is meant as an experiment in thinking about AI style, and machine-assisted reading.*

