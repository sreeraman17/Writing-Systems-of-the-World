# Writing Systems of the World — First-Principles Classifier

A single-file, offline-capable reference tool for language students and script enthusiasts. Covers ~60 writing systems across all major lineages, with special depth on the Brahmi family (Sanskrit, Prakrit, Devanagari and descendants) and a dedicated section on why Chinese script developed in complete isolation from neighbouring traditions.

Built by [Sree](https://sreeraman.in/) as a personal language study companion.

---

## What's inside

| Section | Systems covered |
|---|---|
| Proto-Sinaitic → Semitic branch | Proto-Sinaitic, Phoenician, Aramaic, Hebrew, Arabic, Syriac |
| Greek → Latin / Cyrillic branch | Greek, Latin, Cyrillic, Coptic, Armenian, Georgian, Runic, Ogham |
| **Brahmi lineage** ⭐ | Brahmi, Sanskrit, Prakrit, Devanagari, Gupta, Sharada, Gurmukhi, Gujarati, Bengali, Tamil, Telugu, Kannada, Malayalam, Tibetan, Sinhala, Burmese, Khmer, Thai and more |
| Aramaic → Central Asian branch | Sogdian, Old Uyghur, Mongolian, Manchu |
| East Asian logographic branch | Classical Chinese, Traditional, Simplified, Kanji, Hiragana, Katakana, Hangul |
| Independent / notable systems | Ethiopic, Egyptian Hieroglyphics, Cuneiform, Linear B, Cherokee, Braille, IPA |

Each row carries **11 attributes** per script:

- Script name + native glyphs
- Type (Abjad / Alphabet / Abugida / Syllabary / Logographic / Featural)
- Origin era
- Direct ancestor
- Geographic origin
- Writing direction
- How vowels are encoded (or not)
- Phoneme unit (the key first-principles classifier)
- Active speaker / reader count
- Key languages that use the script today
- One defining distinctive feature

---

## How to use it for language studies

### Getting started
Download `writing_systems_world_classifier.html` and open it in any browser. No internet connection required after download. No installation, no dependencies.

### 1. Understand the first-principles taxonomy before picking a language

The **Type** column and **Phoneme unit** column are the most important for a learner. They tell you *how* the script encodes sound, which determines your learning strategy:

| Type | What you memorise | Example scripts | Learning approach |
|---|---|---|---|
| **Abjad** | Consonants only; vowels inferred | Arabic, Hebrew | Learn consonant shapes first; vowel diacritics come later with reading practice |
| **Alphabet** | Consonants + vowels as separate letters | Latin, Greek, Cyrillic | One-to-one letter mapping; most familiar to English speakers |
| **Abugida** | Consonant carries an inherent vowel; other vowels are diacritics | Devanagari, Tamil, Thai | Learn base consonants, then vowel modifiers (matras); think in CV units |
| **Syllabary** | One symbol per syllable | Hiragana, Katakana, Cherokee | Memorise fixed syllable grid; no spelling rules, purely phonetic |
| **Logographic** | One symbol per morpheme (word/meaning) | Chinese, Kanji | High memorisation load; learn by radical + stroke order; ~3,500 for functional literacy |
| **Featural** | Letter shape encodes how the sound is physically produced | Hangul, IPA | Learn the geometric logic once; the system is self-explaining after that |

### 2. Use the filter buttons to study a family at a time

Rather than surveying all 60 systems at once, filter by type to see structural patterns:

- **Abugidas filter** — shows the entire Brahmi family together. You'll immediately see how Devanagari, Tamil, Tibetan, and Thai all share the same DNA of inherent-vowel consonants + diacritic modifiers.
- **Abjads filter** — compare Arabic and Hebrew side by side; both omit vowels by default, but use different strategies (harakat vs. niqqud) to optionally mark them.
- **Logographic filter** — see Chinese, Kanji, and Hieroglyphics in one view; note how each handles the vowel problem differently.

### 3. Trace the lineage column before studying a new script

The **Direct ancestor** column is a study shortcut. Before learning a new script, look up what it descended from and what you already know:

- Learning **Gujarati**? You already know Devanagari structure — Gujarati is Devanagari without the top bar (shirobrekha).
- Learning **Katakana**? You already know Hiragana — Katakana uses the same syllable grid with angular instead of curved forms.
- Learning **Cyrillic** (for Russian)? Your Greek letter recognition gives you a head start on ~15 characters.

### 4. Use the Brahmi section for Indian language studies

All rows highlighted in blue belong to the Brahmi family. For Sanskrit / Vedic studies the key lineage to trace is:

```
Proto-Sinaitic (or indigenous) 
  → Brahmi (~300 BCE, Ashokan edicts)
    → Gupta script (~320–600 CE)
      → Siddham (Buddhist tantric texts)
        → Nagari
          → Devanagari (~1200 CE mature form)
```

Devanagari's 11 independent vowels + 36 consonants + matra (vowel modifier) system is directly inherited from Brahmi's inherent-vowel logic. Understanding Brahmi first makes Devanagari structurally obvious rather than a list of memorised shapes.

For South Indian languages the lineage diverges earlier:

```
Brahmi → Kadamba → Telugu-Kannada (split ~6th c. CE)
Brahmi → Pallava → Grantha → Tamil (classical branch)
Brahmi → Pallava → Mon → Khmer → Thai (Southeast Asian branch)
```

### 5. Use the Direction column to prepare your hand and eye

Writing direction affects physical practice habits from day one:

- **RTL scripts** (Arabic, Hebrew): train your eye to scan right-to-left; start handwriting practice from the right margin.
- **Vertical scripts** (Mongolian, traditional Japanese/Chinese): use grid paper rotated 90°; columns run top-to-bottom, left-to-right across the page.
- **Boustrophedon** (early Greek): alternating direction per line — historical curiosity, not a modern writing concern.

### 6. The Chinese isolation section as a comparative study anchor

Before studying any East Asian script, read the Chinese section in the middle of the page. It explains four structural reasons why Chinese script shares no ancestry with Brahmi or Semitic scripts, despite geographic proximity. This context helps you avoid false cognates when comparing Chinese characters with Indian scripts, and explains why Japanese had to *invent* Hiragana and Katakana on top of borrowed Chinese characters to handle a completely different grammar.

---

## Technical notes

- Single `.html` file — no frameworks, no external dependencies, no CDN calls
- Dark mode: auto-detects system preference via `prefers-color-scheme`
- Filter buttons work via plain JavaScript — no libraries
- Tested in Chrome, Firefox, Safari, Edge
- Print-friendly: use browser print to PDF for an offline reference sheet

---

## Suggested study sequence

1. Read the **Types** legend and understand the six categories (5 minutes)
2. Filter to **Abugidas** — study the Brahmi family tree (20 minutes)
3. Filter to **Alphabets** — trace Phoenician → Greek → Latin → Cyrillic (15 minutes)
4. Filter to **Abjads** — understand consonant-only writing and optional vowel marking (10 minutes)
5. Read the **Chinese isolation section** in full (10 minutes)
6. Filter to **Logographic** — compare Chinese, Kanji, Hieroglyphics, Cuneiform (15 minutes)
7. Filter to **Featural** — study Hangul's geometric logic (10 minutes)
8. Return to **All systems** and browse the ancestor column for the language you are currently learning

---

## License

Free to use for personal study and educational purposes.

Data accurate to scholarly consensus as of 2025.
