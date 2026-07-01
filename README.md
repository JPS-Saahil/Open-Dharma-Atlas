# Open Dharma Atlas
<p align="center">

![Status](https://img.shields.io/badge/Status-In%20Development-blue)
![Docs](https://img.shields.io/badge/Documentation-In%20Progress-informational)
![Website](https://img.shields.io/badge/Website-Blueprint-brightgreen)
![License](https://img.shields.io/badge/License-TBD-lightgrey)

</p>

<p align="center">
A structured, research-oriented knowledge archive for organizing the scriptures, philosophy, traditions, and classical knowledge systems of Sanātana Dharma.
</p>

---

## Overview

This repository is intended to become a clean and interconnected reference system for Sanātana Dharma.

Rather than keeping the material as disconnected notes, the project arranges the tradition into a hierarchy that makes the relationships between texts, schools, and practices easier to understand. The long-term goal is to turn this into a website with visual navigation, readable sections, and expandable content.

The focus is on clarity, structure, and long-term usability.

---

## Repository Links

Repository: `<REPO_URL>`

Clone:

```bash
git clone https://github.com/JPS-Saahil/Open-Dharma-Atlas.git
```

---

## What This Project Covers

### Scriptural Foundations
- The four Vedas
- Internal layers of Vedic literature
- The role of the Upaniṣads
- The Prasthānatrayī

### Supporting Disciplines
- Vedāṅgas
- Sanskrit interpretation tools
- Ritual and textual preservation methods

### Applied Traditions
- Upavedas
- Dharmashāstra
- Purāṇas
- Itihāsas

### Philosophical Systems
- Āstika darśanas
- Nāstika darśanas
- Vedānta and its foundations

### Ritual and Worship Traditions
- Āgamas
- Sectarian temple traditions
- Mantra and sādhana frameworks

---

## Knowledge Structure

```text
Sanātana Dharma
├── Vedas
│   ├── Rigveda
│   ├── Yajurveda
│   ├── Samaveda
│   └── Atharvaveda
│
├── Vedic Literature
│   ├── Saṃhitā
│   ├── Brāhmaṇa
│   ├── Āraṇyaka
│   └── Upaniṣad
│
├── Vedāṅgas
│   ├── Śikṣā
│   ├── Vyākaraṇa
│   ├── Chandas
│   ├── Nirukta
│   ├── Jyotiṣa
│   └── Kalpa
│
├── Upavedas
│   ├── Āyurveda
│   ├── Dhanurveda
│   ├── Gāndharvaveda
│   └── Arthaśāstra
│
├── Upāṅgas
│   ├── Dharmashāstra
│   ├── Purāṇas
│   ├── Itihāsas
│   └── Mīmāṃsā and Nyāya
│
├── Darśanas
│   ├── Āstika
│   │   ├── Nyāya
│   │   ├── Vaiśeṣika
│   │   ├── Sāṃkhya
│   │   ├── Yoga
│   │   ├── Pūrva Mīmāṃsā
│   │   └── Vedānta
│   └── Nāstika
│       ├── Bauddha
│       ├── Jaina
│       └── Cārvāka
│
├── Vedānta
│   └── Prasthānatrayī
│       ├── Upaniṣads
│       ├── Bhagavad Gītā
│       └── Brahma Sūtras
│
└── Āgamas
    ├── Śaiva
    ├── Vaiṣṇava
    ├── Śākta
    ├── Gāṇapatya
    ├── Kaumāra
    └── Saura
```

---

## High-Level Tree

```text
Core Knowledge System
├── Shruti (revealed / heard apaurusheya, authorless)
│   ├── 4 Vedas
│   │   ├── Rigveda
│   │   │   ├── Samhita
│   │   │   ├── Brahmana
│   │   │   ├── Aranyaka
│   │   │   └── Upanishad
│   │   ├── Yajurveda
│   │   │   ├── Samhita
│   │   │   ├── Brahmana
│   │   │   ├── Aranyaka
│   │   │   └── Upanishad
│   │   ├── Samaveda
│   │   │   ├── Samhita
│   │   │   ├── Brahmana
│   │   │   ├── Aranyaka
│   │   │   └── Upanishad
│   │   └── Atharvaveda
│   │       ├── Samhita
│   │       ├── Brahmana
│   │       ├── Aranyaka
│   │       └── Upanishad
│   │
│   ├── Vedangas (6 limbs of Vedic study)
│   │   ├── Shiksha       — phonetics
│   │   ├── Vyakarana     — grammar
│   │   ├── Chhanda       — metre
│   │   ├── Nirukta       — etymology
│   │   ├── Jyotisha      — astronomy/timing
│   │   └── Kalpa         — ritual procedure
│   │       ├── Shrauta Sutras   — public/solemn ritual
│   │       ├── Grihya Sutras    — domestic ritual
│   │       ├── Dharma Sutras    — conduct & law (proto-Dharmashastra)
│   │       └── Shulba Sutras    — altar geometry & measurement
│   │
│   └── Upavedas (4 — applied knowledge; associations vary by source, see 5A5)
│       ├── Ayurveda        — medicine
│       ├── Dhanurveda      — archery / warfare
│       ├── Gandharvaveda   — music, dance, arts
│       └── Arthashastra    — statecraft / economics
│           (variant: Sthapatyaveda — architecture)
│
├── Smriti (remembered tradition — paurusheya, authored)
│   ├── Upangas (4 traditional "sub-limbs" — often the most overlooked layer)
│   │   ├── Nyaya            — logic (name shared with the Darshana)
│   │   ├── Mimamsa          — exegesis (covers both Purva & Uttara Mimamsa)
│   │   ├── Itihasa-Purana   — "the fifth Veda" (see 5B3–5B4)
│   │   │   ├── Itihasa
│   │   │   │   ├── Ramayana
│   │   │   │   └── Mahabharata
│   │   │   │       └── Bhagavad Gita (embedded, not separate)
│   │   │   └── Purana
│   │   │       ├── 18 Mahapuranas (full list, 5B4)
│   │   │       └── 18 Upapuranas (variable list, 5B4)
│   │   └── Dharmashastra  codes of law & conduct (the Smritis proper)
│   │
│   ├── Sutra Literature (practical support; overlaps with Vedanga/Kalpa)
│   │   ├── Shrauta Sutra
│   │   ├── Grihya Sutra
│   │   ├── Dharma Sutra
│   │   └── Shulba Sutra
│   │
│   └── auxiliary Smriti traditions (Grihya customs, regional Achara texts, etc.)
│
├── Darshanas (philosophical systems / "viewpoints")
│   ├── Astika (6 — accept Vedic authority), traditionally paired
│   │   ├── Nyaya            ─┐ pair 1: epistemology & physics
│   │   ├── Vaisheshika      ─┘
│   │   ├── Samkhya          ─┐ pair 2: metaphysics & practice
│   │   ├── Yoga             ─┘
│   │   ├── Purva Mimamsa    ─┐ pair 3: ritual & knowledge
│   │   └── Uttara Mimamsa   ─┘ (= Vedanta)
│   │       ├── Prasthanatrayi
│   │       │   ├── Upanishads      — Shruti Prasthana
│   │       │   ├── Brahma Sutras   — Nyaya/Sutra Prasthana
│   │       │   └── Bhagavad Gita   — Smriti/Sadhana Prasthana
│   │       └── major Vedanta streams
│   │           ├── Advaita (non-dualism)
│   │           ├── Vishishtadvaita (qualified non-dualism)
│   │           ├── Dvaita (dualism)
│   │           ├── Dvaitadvaita, Shuddhadvaita, Achintya Bheda Abheda...
│   │           └── other sampradaya-linked sub-schools
│   │
│   └── Nastika (3 core do not accept Vedic authority as supreme)
│       ├── Bauddha (Buddhism)
│       ├── Jaina (Jainism)
│       └── Charvaka / Lokayata (materialism)
│       [Ajivika is often added as a 4th in broader classifications see 6.4]
│
└── Agama / Tantra literature TWO related but distinct classifications:
    │
    ├── (a) The Agama textual corpus proper — 3 branches
    │   ├── Shaiva Agamas       (~28 canonical texts)
    │   ├── Vaishnava Agamas    (~108, aka Pancharatra Samhitas)
    │   │   ├── Pancharatra
    │   │   └── Vaikhanasa
    │   └── Shakta Agamas / Tantras  (~64)
    │
    └── (b) The Shanmata six-fold Smarta worship tradition
        (organizes household/temple worship around six deities;
         popularized by Adi Shankaracharya; not itself a 4th Agama branch)
        ├── Shaiva     → Shiva
        ├── Vaishnava  → Vishnu
        ├── Shakta     → Devi / Shakti
        ├── Ganapatya  → Ganesha
        ├── Kaumara    → Kartikeya / Murugan
        └── Saura      → Surya

```

---

## Project Goals

- Preserve the traditional structure of knowledge in a clean digital format.
- Present the material in a way that is easy to navigate on GitHub and in a future website.
- Separate major categories instead of mixing everything into one list.
- Keep the system expandable for future pages and modules.
- Support long-term documentation with consistent naming and cross-links.
- Create a foundation for an interactive `plan.html` page.

---

## Planned Website Features

- homepage overview
- clickable category tree
- scripture pages
- philosophical school pages
- glossary entries
- reference links
- simple navigation between related concepts
- responsive design for desktop and mobile
- clean typography and minimal layout

---

## Proposed File Structure

```text
.
├── README.md
├── tree.md
├── plan.html
├── assets/
│   ├── images/
│   ├── diagrams/
│   └── icons/
├── vedas/
├── vedangas/
├── upavedas/
├── upangas/
├── darshanas/
├── vedanta/
├── agamas/
├── puranas/
├── itihasas/
├── glossary/
└── references/
```

---

## Tags

`#SanatanaDharma` `#Vedas` `#Upanishads` `#Vedanta` `#Darshanas` `#Puranas` `#Agamas` `#Sanskrit` `#KnowledgeTree` `#Documentation`

---

## Status

- Content structure: In progress
- Website blueprint: Planned
- Interactive HTML: Planned
- Visual navigation: Planned

---

## Contribution Focus

Future contributions may include:

- adding source references
- refining category boundaries
- expanding individual scripture pages
- improving the visual tree
- building the HTML prototype
- standardizing glossary entries

---

## License

License information will be added before public release.
