# 🌍 Writing Systems of the World

**An Interactive First-Principles Classifier**

🌐 **Live Site** → [sreeraman17.github.io/Writing-Systems-of-the-World](https://sreeraman17.github.io/Writing-Systems-of-the-World/)  
📦 **Repository** → [github.com/sreeraman17/Writing-Systems-of-the-World](https://github.com/sreeraman17/Writing-Systems-of-the-World)

---

## What this is

A single-page, interactive reference that explains how writing systems work — structurally, not just visually.

Built for language learners, linguistics enthusiasts, script explorers, and anyone who wants to understand *why* scripts look and behave the way they do.

---

## What makes it different

Most resources list scripts. This one answers a more useful question:

> **How does each writing system encode sound?**

Each script is broken down into 11 attributes, including type (Abjad / Alphabet / Abugida / Syllabary / Logographic / Featural), phoneme unit, writing direction, vowel encoding strategy, historical lineage, and languages using it today.

This lets you compare systems by structure, not just appearance.

---

## Coverage

~60 writing systems across major traditions:

| Tradition | Scripts |
|---|---|
| Semitic lineage | Proto-Sinaitic → Phoenician → Arabic, Hebrew |
| European lineage | Greek → Latin → Cyrillic |
| Brahmi lineage ⭐ | Devanagari, Tamil, Thai, Tibetan, Khmer, and more |
| Central Asian | Sogdian → Mongolian → Manchu |
| East Asian | Chinese, Kanji, Hiragana, Katakana, Hangul |
| Independent | Hieroglyphics, Cuneiform, Cherokee, Braille, IPA |

---

## The core idea

Everything revolves around how scripts encode sound:

| Type | What it encodes | Examples | How to learn |
|---|---|---|---|
| Abjad | Consonants only | Arabic, Hebrew | Learn consonants first |
| Alphabet | Consonants + vowels | Latin, Greek | Direct mapping |
| Abugida | Consonant + inherent vowel | Devanagari, Thai | Base + modifiers |
| Syllabary | Whole syllables | Hiragana | Memorise a grid |
| Logographic | Meaning units | Chinese | High memorisation |
| Featural | Articulation in shape | Hangul | Learn the system logic |

**Start with Type + Phoneme Unit — they determine everything.**

---

## How to explore effectively

### 1. Use filters instead of scrolling

- Filter **Abugidas** → see the full Brahmi family  
- Filter **Abjads** → compare Arabic vs Hebrew  
- Filter **Logographic** → Chinese vs others  

Patterns become obvious instantly.

### 2. Use ancestry as a shortcut

Before learning a script, check where it came from — you're rarely starting from scratch:

- Gujarati → derived from Devanagari  
- Katakana → same grid as Hiragana  
- Cyrillic → partly derived from Greek  

### 3. Understand the Brahmi system

All major Indian and many Southeast Asian scripts share one idea:

```
Consonant = default vowel
Other vowels = modifications
```

This explains Devanagari, Tamil, Telugu, Thai, Khmer, and Tibetan. Once this clicks, these scripts stop feeling "complex".

### 4. Read the Chinese section

The site explains why Chinese writing evolved independently and has no structural relation to Brahmi or Semitic systems — which prevents a lot of common misunderstandings.

---

## Suggested learning flow

1. Learn the 6 script types (5–10 min)
2. Explore Abugidas (Brahmi family)
3. Trace Phoenician → Greek → Latin / Cyrillic
4. Compare Abjads
5. Read the Chinese isolation section
6. Explore Logographic systems
7. Study Hangul (featural system)
8. Return to full view and connect everything

---

## Running locally

```bash
git clone https://github.com/sreeraman17/Writing-Systems-of-the-World
```

Then open `index.html`. No install, no setup, works offline after first load.

---

## Technical details

- Single `index.html` file — no frameworks, no dependencies
- Auto dark mode via `prefers-color-scheme`
- Lightweight, fast, and print-friendly (export to PDF)

---

## Contributing

Found something off or missing? Open an issue or submit a PR — improvements are welcome.

---

## License

Free for personal and educational use.
