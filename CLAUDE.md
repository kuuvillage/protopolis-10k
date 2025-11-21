# Project Guidelines for Essay Writing

## 1. Project Overview

**Project Name (working title):** [To be determined]

**Essay Theme:** Designing a "new municipality" under 10,000 residents

**Purpose & Background:**
Define the vision, motivation, and societal challenge your essay addresses.

**Intended Audience / Venue:** Policy researchers, civic-tech practitioners, local governance experts

**Language:** Japanese (with English abstract)

**Style Orientation:** Proposal-driven and practical rather than purely academic

### Directory Structure

```
protopolis-10k/
├── contents/        # 論文本体（章ごとのMarkdownファイル）
│   ├── 01_introduction.md
│   ├── 02_background.md
│   ├── 03_concept.md
│   ├── 04_implementation.md
│   ├── 05_discussion.md
│   └── 06_conclusion.md
├── docs/           # 参考文献・収集した情報・調査資料
│   ├── basic_research #日本国内の現状についてのリサーチ
│   ├── external_env_research #外部環境の現状についてのリサーチ
│   └── paper_structure.md #論文アウトライン
├── figs/           # 図表・画像ファイル
│   ├── figure1_overview.png
│   └── table1_comparison.png
├── CLAUDE.md       # Claudeへの執筆ガイドライン
└── README.md       # プロジェクト概要
```

## 2. Essay Structure Guide

### Suggested Chapter Layout:

1. Introduction
2. Background & Related Work
3. Concept / Vision (the new municipality model)
4. Implementation Path
5. Discussion
6. Conclusion & Future Outlook

### Key Focus for Each Chapter:

- **Introduction:** Problem statement, objectives, hypotheses
- **Background:** Existing systems, challenges, opportunities
- **Concept:** Design of community, governance, economy, and technology
- **Implementation Path:** Transition scenarios, enablers, and risks
- **Discussion:** Feasibility, constraints, and generalization
- **Conclusion:** Summary, implications, and next steps

## 3. Writing Style & Formatting Rules

**Tone:** Formal academic / declarative style ("– de aru" form in Japanese)

**Terminology:** Present full term with English in parentheses on first use; keep consistent afterward.

**Citations:** APA 7th edition or in-text form (e.g., Yamada, 2023).

### Figures & Tables:
- **Caption format:** Figure 1. Title / Table 1. Title
- Include sources for all external data or images.

**Mathematical Symbols:** Define each variable or notation when introduced.

**File Naming Convention:** Use snake_case (e.g., `chapter3_concept.md`).

## 4. Claude's Role & Instructions

Claude acts as a writing and structuring assistant, not a co-author.

### Tasks include:
- Suggesting chapter outlines and section headings
- Drafting text and refining tone and coherence
- Checking style consistency and term alignment
- Generating English abstracts when requested

### Response Guidelines:
- If data or facts are uncertain, mark them as "to be verified."
- Always cite sources where applicable.
- Follow all style and citation rules from Section 3.
- Avoid hallucinated references or unverifiable claims.