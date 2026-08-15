# pycon-jp-2026-docs

This repository contains the materials for my talk at PyCon JP 2026, titled "Python and language learning: How did Python help me get the JLPT N1?".

## Table of Contents

- [pycon-jp-2026-docs](#pycon-jp-2026-docs)
  - [Table of Contents](#table-of-contents)
  - [Abstract](#abstract)
  - [Slides](#slides)
  - [Open-source tools](#open-source-tools)
  - [Reference books per level](#reference-books-per-level)
    - [JLPT N5](#jlpt-n5)
    - [JLPT N4](#jlpt-n4)
    - [JLPT N3](#jlpt-n3)
    - [JLPT N2](#jlpt-n2)
    - [JLPT N1](#jlpt-n1)
  - [Tips for studying](#tips-for-studying)
  - [Resources](#resources)

## Abstract

In April 2026, Japan added a JLPT N2 language requirement for some Engineer/Specialist visas. Most IT engineers are exempt, but these tighter rules highlight that Japanese proficiency is increasingly important for living and working in Japan.

This talk presents my wrestling with the Japanese language and how, from being an international student frustrated that I could only speak English, I, ten years later, led an engineering team in a mostly Japanese-led firm. What did I learn during this time? How has language learning evolved with the arrival of LLMs? And how can we use the king of scripting languages, Python, to customize our studies? I will talk about my experience, open-source Python libraries (genanki, onsei, and others).

## Slides

Link to slides: [https://docs.google.com/presentation/d/1g0k5J4v6]

## Open-source tools

- [anki](https://github.com/ankitects/anki)
- [genanki](https://github.com/kerrickstaley/genanki)
- [onsei](https://github.com/ikegami-yukino/onsei)
- [manga-ocr](https://github.com/kanaka/manga-ocr)
- [understand-anything](https://github.com/understand-anything/understand-anything)

## Reference books per level

This is the reference book material I used to study for each level of the JLPT. You can use this as a reference for your own studies. I recommend starting with the easier books and working your way up to the harder ones. I also recommend using Anki to memorize vocabulary and grammar points.

### JLPT N5

- Kanji Look and Learn
- Genki I
- Official practice tests

### JLPT N4

- Kanji Look and Learn
- Genki II
- Official practice tests

### JLPT N3

- Kanji Look and Learn
- Genki II
- Try N3 Grammar
- Shinkanzen Master Series (Especially grammar and reading. I didn't like the kanji versions)

### JLPT N2

My studied followed the order of the books below. I recommend starting the Shinkanzen after finishing the easier Sou Matome.

- Sou Matome N2 series (you can avoid the grammar, as it is can be too easy)
- Try N2 Grammar
- Shinkanzen Master Series (Especially grammar and reading. I didn't like the kanji versions)
- Japan Times JLPT N2 Practice Tests
- Official tests

### JLPT N1

My studied followed the order of the books below. I recommend starting the Shinkanzen after finishing the easier Sou Matome. In six months time, I couldn't finish the grammar book.

- Sou Matome N1 series (I avoided the listening book)
- Try N1 Grammar (a little outdated, but still useful)
- Shinkanzen Master Series (I did all except the kanji book).
- Japan Times JLPT N1 Practice Tests.
- Official tests.

## Tips for studying

- Anki is still the king for memorization. You can use anki brain to customize your studying experience.
- JLPT N2 is famous for being a "reading test". Time out your reading speed.
- JLPT N1 is especially hard at vocabulary. Listening can be tricky even for highly immersed learners.
- Ultimately the JLPT tests your Japanese proficiency, but it is not a measure of your ability to communicate in Japanese. I recommend using the JLPT as a guide for your studies, but not as a goal to speak properly. The goal is to learn organically. Use immersion to practice your speaking and listening skills.

## Resources

For the survey data from slide 7, please visit the following articles:

- <https://2025.surveys.tokyodev.com/en-US>
- <https://www.tokyodev.com/articles/japan-residents-only-why-some-japanese-firms-won-t-hire-english-speaking-developers-internationally>

On spaced repetition please check:

- Hermann Ebbinghaus (1885): For the original mathematical formulation of the forgetting curve and the initial discovery that distributed practice dramatically slows memory loss.

- Robert A. Bjork & Elizabeth L. Bjork (1992, 1994): For the New Theory of Disuse and Desirable Difficulties. This explains why spacing works: retrieving an item when its immediate accessibility ("retrieval strength") has decayed causes a large increase in long-term durability ("storage strength").

- Nicholas J. Cepeda et al. (2006): For the meta-analysis across over 14,000 participants proving the universal robust effect of spaced practice over massed practice.

For the algorithms used in spaced repetition software, please check:

- Piotr Wozniak (1987): Creator of the SuperMemo SM-2 algorithm, which served as the classic benchmark for computer-driven spaced repetition scheduling in software like Anki for over three decades.
- [Understanding Spaced Repetition](https://help.remnote.com/en/articles/9337171-understanding-spaced-repetition)

- Jarrett Ye & The Open Spaced Repetition Community (2022–2024): Creators of the Free Spaced Repetition Scheduler (FSRS). FSRS uses machine learning based on the Difficulty, Stability, Retrievability (DSR) model, which has been benchmarked on over 500 million review logs to reduce study workload by 20% to 30% compared to legacy heuristics.

Finally the study of long-term memory retention for foreign language learning has been studied in:

- Harry P. Bahrick et al. (1984, 1993): "Fifty years of memory for Spanish learned in school".

