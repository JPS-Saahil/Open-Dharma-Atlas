# Open Dharma atlas
[This documentation is currently in the planning and research phase. The structure and content are expected to evolve as additional sources are studied and the project's understanding deepens. This should be considered a working blueprint rather than the final architecture.]
## 1) Site Vision

The website should feel like:

- a **knowledge tree**
- a **study map**
- a **civilizational archive**
- a **guided reading experience**

The goal is not just to list texts, but to show **how the parts relate to one another** and, where scholarship genuinely disagrees, to show *that* honestly rather than flattening it into a single false-precision chart.

---

## 2) Visual Identity

*(unchanged from your original carried forward as-is)*

### Tone
- scholarly
- calm
- reverent
- modern
- highly readable

### Visual language
- **Root** → foundational source
- **Branch** → major category
- **Sub-branch** → sub-category or tradition
- **Leaf** → a specific text, school, or discipline

### Suggested style
- background: parchment / ivory / soft stone
- primary accent: indigo or deep blue
- secondary accent: saffron / gold
- tertiary accent: maroon / copper
- typography: serif for headings, clean sans-serif for body

---

## 3) Master Tree Overview

```text
Hindu Knowledge System
├── Shruti (revealed / heard - apaurusheya, authorless)
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
│   │   ├── Shiksha       - phonetics
│   │   ├── Vyakarana     - grammar
│   │   ├── Chhanda       - metre
│   │   ├── Nirukta       - etymology
│   │   ├── Jyotisha      - astronomy/timing
│   │   └── Kalpa         - ritual procedure
│   │       ├── Shrauta Sutras   - public/solemn ritual
│   │       ├── Grihya Sutras    - domestic ritual
│   │       ├── Dharma Sutras    - conduct & law (proto-Dharmashastra)
│   │       └── Shulba Sutras    - altar geometry & measurement
│   │
│   └── Upavedas (4 - applied knowledge; associations vary by source, see 5A5)
│       ├── Ayurveda        - medicine
│       ├── Dhanurveda      - archery / warfare
│       ├── Gandharvaveda   - music, dance, arts
│       └── Arthashastra    - statecraft / economics
│           (variant: Sthapatyaveda - architecture)
│
├── Smriti (remembered tradition - paurusheya, authored)
│   ├── Upangas (4 traditional "sub-limbs" - often the most overlooked layer)
│   │   ├── Nyaya            - logic (name shared with the Darshana)
│   │   ├── Mimamsa          - exegesis (covers both Purva & Uttara Mimamsa)
│   │   ├── Itihasa-Purana   - "the fifth Veda" (see 5B3–5B4)
│   │   │   ├── Itihasa
│   │   │   │   ├── Ramayana
│   │   │   │   └── Mahabharata
│   │   │   │       └── Bhagavad Gita (embedded, not separate)
│   │   │   └── Purana
│   │   │       ├── 18 Mahapuranas (full list, 5B4)
│   │   │       └── 18 Upapuranas (variable list, 5B4)
│   │   └── Dharmashastra    - codes of law & conduct (the Smritis proper)
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
│   ├── Astika (6 - accept Vedic authority), traditionally paired
│   │   ├── Nyaya            ─┐ pair 1: epistemology & physics
│   │   ├── Vaisheshika      ─┘
│   │   ├── Samkhya          ─┐ pair 2: metaphysics & practice
│   │   ├── Yoga             ─┘
│   │   ├── Purva Mimamsa    ─┐ pair 3: ritual & knowledge
│   │   └── Uttara Mimamsa   ─┘ (= Vedanta)
│   │       ├── Prasthanatrayi
│   │       │   ├── Upanishads      - Shruti Prasthana
│   │       │   ├── Brahma Sutras   - Nyaya/Sutra Prasthana
│   │       │   └── Bhagavad Gita   - Smriti/Sadhana Prasthana
│   │       └── major Vedanta streams
│   │           ├── Advaita (non-dualism)
│   │           ├── Vishishtadvaita (qualified non-dualism)
│   │           ├── Dvaita (dualism)
│   │           ├── Dvaitadvaita, Shuddhadvaita, Achintya Bheda Abheda...
│   │           └── other sampradaya-linked sub-schools
│   │
│   └── Nastika (3 core - do not accept Vedic authority as supreme)
│       ├── Bauddha (Buddhism)
│       ├── Jaina (Jainism)
│       └── Charvaka / Lokayata (materialism)
│       [Ajivika is often added as a 4th in broader classifications - see 6.4]
│
└── Agama / Tantra literature - TWO related but distinct classifications:
    │
    ├── (a) The Agama textual corpus proper - 3 branches
    │   ├── Shaiva Agamas       (~28 canonical texts)
    │   ├── Vaishnava Agamas    (~108, aka Pancharatra Samhitas)
    │   │   ├── Pancharatra
    │   │   └── Vaikhanasa
    │   └── Shakta Agamas / Tantras  (~64)
    │
    └── (b) The Shanmata - six-fold Smarta worship tradition
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

## 4) Clean Visual Tree for a Web Page

```text
HINDU KNOWLEDGE SYSTEM
├── SHRUTI
│   ├── 4 VEDAS
│   │   ├── Rigveda
│   │   ├── Yajurveda
│   │   ├── Samaveda
│   │   └── Atharvaveda
│   ├── VEDANGAS
│   │   ├── Shiksha
│   │   ├── Vyakarana
│   │   ├── Chhanda
│   │   ├── Nirukta
│   │   ├── Jyotisha
│   │   └── Kalpa
│   └── UPAVEDAS
│       ├── Ayurveda
│       ├── Dhanurveda
│       ├── Gandharvaveda
│       └── Arthashastra
├── SMRITI
│   ├── UPANGAS
│   │   ├── Nyaya
│   │   ├── Mimamsa
│   │   ├── Itihasa-Purana
│   │   └── Dharmashastra
│   ├── SUTRA LITERATURE
│   │   ├── Shrauta Sutra
│   │   ├── Grihya Sutra
│   │   ├── Dharma Sutra
│   │   └── Shulba Sutra
│   ├── ITIHASA
│   │   ├── Ramayana
│   │   └── Mahabharata
│   │       └── Bhagavad Gita
│   └── PURANAS
│       ├── 18 Mahapuranas
│       └── 18 Upapuranas
├── DARSHANA
│   ├── ASTIKA
│   │   ├── Nyaya
│   │   ├── Vaisheshika
│   │   ├── Samkhya
│   │   ├── Yoga
│   │   ├── Purva Mimamsa
│   │   └── Uttara Mimamsa
│   │       └── Prasthanatrayi
│   │           ├── Upanishads
│   │           ├── Brahma Sutras
│   │           └── Bhagavad Gita
│   └── NASTIKA
│       ├── Bauddha
│       ├── Jaina
│       └── Charvaka
└── AGAMA
    ├── Agama corpus
    │   ├── Shaiva Agamas
    │   ├── Vaishnava Agamas
    │   └── Shakta Agamas
    └── Shanmata
        ├── Shaiva
        ├── Vaishnava
        ├── Shakta
        ├── Ganapatya
        ├── Kaumara
        └── Saura
```

---

## 5) Detailed Content Tree

### A. Shruti

Shruti is the revealed / heard corpus - traditionally regarded as *apaurusheya* (authorless, not composed by any human), the root layer of authority in the system.

#### A1. The Four Vedas
1. **Rigveda** - hymns, praise, invocation, cosmological vision. The oldest layer.
2. **Yajurveda** - sacrificial formulas, ritual action, priestly procedure. Exists in "Shukla" (White) and "Krishna" (Black) recensions.
3. **Samaveda** - melodic chant, liturgical singing; largely draws its verses from the Rigveda but sets them to musical notation.
4. **Atharvaveda** - practical hymns: healing, protection, domestic and social concerns, some philosophical material.

#### A2. Internal Layers of Each Veda
Each Veda is itself a four-layer stack:

| Layer | Nature |
|---|---|
| **Samhita** | The core mantra/hymn collection |
| **Brahmana** | Prose commentary explaining ritual application |
| **Aranyaka** | "Forest texts" - transition from ritual to contemplation |
| **Upanishad** | Philosophical inquiry into ultimate reality (Atman/Brahman) |

> This layering is genuinely one of the most important things to make visible on the site - it's what lets a visitor see *where the Upanishads physically sit* inside the Vedic corpus, rather than treating them as a free-floating fifth text.

#### A3. Vedangas
Six auxiliary sciences that preserve, pronounce, interpret, and ritualize Vedic knowledge:

1. **Shiksha** - phonetics, pronunciation, sound discipline
2. **Vyakarana** - grammar, linguistic analysis (Panini's Ashtadhyayi is the classic text)
3. **Chhanda** - metre, poetic form, rhythm
4. **Nirukta** - etymology, word-derivation (Yaska's Nirukta is foundational)
5. **Jyotisha** - astronomy/astrology, calendrical and ritual timing
6. **Kalpa** - ritual procedure, practical injunctions

#### A4. Kalpa Sub-Branches
Kalpa is not one vague label - it has four well-defined textual families:

- **Shrauta Sutras** - formal, public "solemn" ritual instructions (agnihotra, soma sacrifices, etc.)
- **Grihya Sutras** - domestic rites: birth, naming, marriage, funeral rites, daily worship
- **Dharma Sutras** - early rules of conduct and social-religious order - the direct ancestors of the later Dharmashastras (e.g. Apastamba, Baudhayana, Gautama, Vasishtha)
- **Shulba Sutras** - geometry and measurement for constructing Vedic altars; historically important as an early source of Indian mathematics

#### A5. Upavedas
Four applied-knowledge traditions. **Lists and Veda-associations genuinely vary by source** - this should be shown as a real scholarly variance, not an error to smooth over:

| Upaveda | Domain | *Charanavyuha* association | *Vishnu Purana* / common association |
|---|---|---|---|
| **Ayurveda** | Medicine, health, longevity | Atharvaveda | Rigveda (some traditions: Atharvaveda) |
| **Dhanurveda** | Archery, warfare, martial discipline | Yajurveda | Yajurveda |
| **Gandharvaveda** | Music, dance, poetry, arts | Samaveda | Samaveda |
| **Sthapatyaveda / Arthashastra** | Architecture / statecraft & economics | Sthapatyaveda ↔ Rigveda | Arthashastra ↔ Atharvaveda |

> Display note: some traditions substitute **Sthapatyaveda** (architecture) for **Arthashastra** (statecraft) as the fourth Upaveda, or list both. The *Bhagavata Purana* (3rd skandha) and the *Charanavyuha* don't fully agree with each other on either the names or the Veda-pairings. The site should present this with a "tradition varies" toggle rather than picking one silently.

---

### B. Smriti

Smriti is remembered/authored tradition (*paurusheya*) texts and traditions derived from human transmission and interpretation of Shruti, generally treated as secondary in authority but foundational in daily practice.

#### B1. Upangas the missing layer
Classical sources (e.g. the Charanavyuha tradition, and later digests like the *Chaturdasha Vidya* / "fourteen branches of knowledge" scheme) define exactly **four Upangas**:

1. **Nyaya** logic and epistemology (note: this name is shared with the Nyaya Darshana; here it refers to the discipline of reasoned inquiry as a support for understanding dharma, not the formal six-school Darshana)
2. **Mimamsa** exegetical method for interpreting Vedic injunctions (covers both Purva and Uttara Mimamsa in some framings)
3. **Itihasa-Purana** epic-and-mythic historical literature; sometimes listed as one combined category, sometimes as "Purana" alone
4. **Dharmashastra** codified law and conduct

> **Why this matters for the site:** the original video's "four Upangas" slide actually names five things (Dharmashastra, Purana, Itihasa, Mimamsa, Nyaya) and never resolves that Itihasa and Purana are traditionally one Upanga, not two. Showing the proper 4-fold structure with a clickable note explaining *why* Nyaya and Mimamsa reappear later as full Darshanas turns a confusing overlap into an interesting teaching moment instead of hiding it.

#### B2. Dharmashastra
The ethical and legal framework later, expanded verse-form descendants of the Dharma Sutras.

- law · conduct · duties · social norms · stages of life (ashramas) · rites and obligations
- Best-known example: **Manusmriti**; others include Yajnavalkya Smriti, Narada Smriti, Parashara Smriti

#### B3. Itihasa "History," and the Fifth Veda
Civilizational memory through epic narrative:

1. **Ramayana** (attributed to Valmiki)
2. **Mahabharata** (attributed to Vyasa) the longest epic poem in existence
   - includes the **Bhagavad Gita** as an embedded philosophical dialogue (Bhishma Parva), not a separate freestanding scripture

> Worth surfacing on the site: the **Chandogya Upanishad (7.1.2)** refers to "Itihasa-Purana" as the *pancama veda* the "fifth Veda" a striking classical claim about how central epic-and-mythic literature was considered to be, even though it's technically Smriti rather than Shruti.

#### B4. Puranas
**18 Mahapuranas**, traditionally grouped into three sets of six by *guna* (quality)  according to the Padma Purana's own internal classification. (Note: a handful of sources swap 1–2 titles between groups, or dispute whether the *Devi Bhagavata Purana* or the *Bhagavata Purana* belongs on the Mahapurana list - flagged in the table.)

| Sattva (purity) - Vishnu-centered | Rajas (passion) | Tamas (inertia) - Shiva-centered |
|---|---|---|
| Vishnu Purana | Brahmanda Purana | Matsya Purana |
| Bhagavata Purana * | Brahma Vaivarta Purana | Kurma Purana |
| Naradiya (Narada) Purana | Markandeya Purana | Linga Purana |
| Garuda Purana | Bhavishya Purana | Shiva Purana |
| Padma Purana | Vamana Purana | Skanda Purana |
| Varaha Purana | Brahma Purana | Agni Purana |

*\* Some traditions (Vayu, Matsya, Aditya Upapurana) list the Devi Bhagavata Purana here instead of / alongside the Bhagavata Purana - a genuinely unresolved classical dispute worth a footnote on the site.*

**18 Upapuranas** - this list is far less standardized than the Mahapurana list (scholars including Rajendra Hazra and Ludo Rocher note the Maha/Upa distinction itself is not strictly historical). One commonly cited list:

Sanatkumara · Narasimha · Brihannaradiya · Sivarahasya · Durvasa · Kapila · Vamana · Bhargava · Varuna · Kalika · Samba · Nandi · Surya · Parasara · Vashishtha · Devi Bhagavata · Ganesha · Hamsa

> Display note: label this list clearly as *"one representative tradition - regional and sectarian lists vary considerably,"* rather than presenting it with the same certainty as the Mahapurana list.

Content themes across the Puranas: cosmology · genealogy (dynastic lists) · kingship · devotion (bhakti) · pilgrimage (tirtha-mahatmya) · creation and dissolution cycles (kalpa/manvantara) · sacred geography.

#### B5. Sutra Literature as Smriti Support
Shown here again as a visible cross-link, since it also lives under Vedanga/Kalpa (Section A4):

- **Shrauta Sutra** · **Grihya Sutra** · **Dharma Sutra** · **Shulba Sutra**

#### B6. Relationship Note
On the page, clarify:

- **Smriti does not mean "unimportant."** It means *remembered / transmitted* by human sages, as distinct from *heard* (Shruti) by them.
- It is often interpretive, explanatory, or practical rather than purely revealed.
- Where Smriti and Shruti conflict, classical hermeneutics generally gives Shruti precedence - but in lived practice, Smriti (especially Dharmashastra, Itihasa, and Purana) shapes daily religious life far more directly.

---

### C. Darshanas

Darshanas ("viewpoints") are the formal philosophical systems.

#### C1. Astika Darshanas
Accept the epistemic authority of the Vedas. Traditionally studied as three **pairs**:

| Pair | Schools | Shared concern |
|---|---|---|
| 1 | **Nyaya** + **Vaisheshika** | Logic, epistemology, and the atomistic categories of physical reality |
| 2 | **Samkhya** + **Yoga** | Enumeration of cosmic principles (Purusha/Prakriti) + disciplined practice toward that realization |
| 3 | **Purva Mimamsa** + **Uttara Mimamsa** | Ritual-action exegesis of the Vedas + knowledge-based inquiry into Brahman (= Vedanta) |

1. **Nyaya** - logic, reasoning, valid knowledge (pramana theory)
2. **Vaisheshika** - categories of reality, atomism, metaphysical analysis
3. **Samkhya** - consciousness (Purusha) and matter (Prakriti); oldest dualist system
4. **Yoga** - discipline, concentration, mental and spiritual practice (Patanjali's Yoga Sutras)
5. **Purva Mimamsa** - ritual action, interpretation of Vedic injunctions, duty-centered exegesis
6. **Uttara Mimamsa / Vedanta** - inquiry into Brahman, Self, reality, liberation; culmination of Upanishadic thought

#### C2. Vedanta and the Prasthanatrayi
Deserves its own content box - this is the core of what your Advaita site already covers in depth.

**Prasthanatrayi** = the three canonical sources every Vedanta commentator (Shankara, Ramanuja, Madhva, and others) must write a bhashya on:

| Text | Sanskrit designation | Character |
|---|---|---|
| **Upanishads** | Shruti Prasthana / Upadesha Prasthana | Revealed - the starting axiom |
| **Brahma Sutras** | Nyaya Prasthana / Yukti Prasthana / Sutra Prasthana | Logical - systematizes Upanishadic doctrine |
| **Bhagavad Gita** | Smriti Prasthana / Sadhana Prasthana | Remembered - practical, narrative synthesis |

**Vedanta sub-schools** (each is a distinct reading of the Prasthanatrayi):
- **Advaita** (non-dualism) - Shankara
- **Vishishtadvaita** (qualified non-dualism) - Ramanuja
- **Dvaita** (dualism) - Madhva
- **Dvaitadvaita** (Nimbarka), **Shuddhadvaita** (Vallabha), **Achintya Bheda Abheda** (Chaitanya), and others

#### C3. Nastika Darshanas
Do not accept Vedic authority as supreme:

1. **Bauddha** (Buddhism) - founded by Siddhartha Gautama
2. **Jaina** (Jainism) - twenty-four tirthankaras, Mahavira the 24th
3. **Charvaka / Lokayata** - materialism, radical empiricism, rejects afterlife and rebirth

> See Section 6.4 below for the Ajivika nuance - treat these traditions on the site as historically major Indian philosophical systems, not merely as negative "non-Vedic" labels.

#### C4. Optional Vedanta Subpage
If the site wants more depth (recommended, given your existing Advaita content):
- Advaita · Vishishtadvaita · Dvaita · Dvaitadvaita · Shuddhadvaita · Achintya Bheda Abheda · other sampradaya-linked developments

---

### D. Agama

Agama/Tantra literature is the ritual, temple, mantra, and sadhana layer of practice - and it needs **two clearly separated sub-trees**, because "the six Agamas" (as commonly taught in survey videos) is actually a conflation of two different classification systems.

#### D1. Core Function
Agamas govern: temple construction · deity worship · mantra systems · ritual sequence · iconography · daily worship · spiritual practice (sadhana).

#### D2. The Agama Textual Corpus - 3 Branches
This is the *actual* native classification of Agama literature:

| Branch | Approx. canonical count | Sub-schools |
|---|---|---|
| **Shaiva Agamas** | ~28 | (Kamika, Suprabheda, Vira, etc.) |
| **Vaishnava Agamas** | ~108 (also called Pancharatra Samhitas) | **Pancharatra** (philosophical/devotional) · **Vaikhanasa** (ritualistic, closer to Vedic form) |
| **Shakta Agamas / Tantras** | ~64 | often overlapping heavily with Shaiva Tantra in metaphysics |

> Some Vaishnava Agamas are also called Vaishnava-tantras; older texts of this genre are called Yamalas.

#### D3. The Shanmata - Six-Fold Worship Tradition
This is what the video's "six Agamas" slide is actually describing. The **Shanmata** ("six opinions/paths") is a household- and temple-worship framework historically associated with **Adi Shankaracharya**, organizing devotion around six principal deities:

1. **Shaiva** - Shiva
2. **Vaishnava** - Vishnu
3. **Shakta** - Devi / Shakti
4. **Ganapatya** - Ganesha
5. **Kaumara** - Kartikeya / Murugan / Skanda
6. **Saura** - Surya, the Sun

> **Site design note:** show D2 and D3 as two connected but distinct nodes under "Agama," each with a one-line explainer: *"D2 = the texts; D3 = the worship traditions those texts (along with Puranic material) support."* This is more accurate than presenting six items as if they were the native shape of Agama literature - and it's genuinely a more interesting structure to visualize, since it shows how one set of scriptures underwrites a broader lived devotional map.

#### D4. Content Ideas for Each Branch
Each branch (in either D2 or D3) can have a page with: deity focus · worship style · philosophical emphasis · temple/ritual implications · representative texts or practices.

#### D5. Display Note
Agamas are not "extra ritual texts" - they form a major, independent practical tradition (arguably as large in volume as the Puranas) that shapes lived worship far more directly than Shruti does for most practitioners.

---

## 6) Scholarly Accuracy Notes

For a site like this, being transparent about where sources genuinely disagree is *more* credible than false precision. Six specific spots worth a "tradition varies" callout:

**6.1 - Upaveda–Veda pairings.** The *Charanavyuha* and the *Vishnu Purana* (and regional traditions) don't fully agree on which Upaveda attaches to which Veda, or even on whether the fourth Upaveda is Arthashastra or Sthapatyaveda. See the table in 5A5.

**6.2 - "Four Upangas" is a specific, fixed list - not a loose bucket.** The traditional four are Nyaya, Mimamsa, Itihasa-Purana, and Dharmashastra. A video or summary that separately lists "Dharmashastra, Purana, Itihasa, Mimamsa, Nyaya" as "four Upangas" has silently expanded the list to five by splitting Itihasa-Purana in two. Worth fixing precisely because Nyaya and Mimamsa *also* name two of the six Darshanas - that overlap is a genuinely interesting feature of the tradition, not a mistake, but it needs to be shown, not hidden.

**6.3 - Itihasa-Purana as "the fifth Veda."** This is a real classical claim (Chandogya Upanishad 7.1.2, and later echoed by the Mahabharata and Natyashastra about themselves), worth surfacing since it explains *why* epic and Puranic material carries so much weight despite being Smriti.

**6.4 - Nastika count: 3 vs. 4.** The "textbook" Nastika trio is Charvaka, Jaina, and Bauddha. But modern academic surveys (and some classical doxographies) commonly add **Ajivika** (founded by Makkhali Gosala, teaching strict fatalism/*niyati*) as a fourth major heterodox school. Worth a toggle: "core 3" vs. "extended 4."

**6.5 - "Six Agamas" = Shanmata, not a native Agama sixfold.** Covered in depth in Section 5D. This is the single biggest structural correction in this pass - the Agama corpus itself is a 3-branch system (Shaiva/Vaishnava/Shakta); the six-deity framework is the *Shanmata* worship tradition, a related but separate classification.

**6.6 - Mahapurana list stability vs. Upapurana variance.** The 18-Mahapurana list is comparatively stable across sources (with one real dispute: Bhagavata vs. Devi Bhagavata). The 18-Upapurana list is genuinely unfixed - different regional and sectarian traditions name different texts. The site should visually distinguish "canonical and stable" from "traditional but variable" content.

---

## 7) Recommended Homepage Blueprint

*(unchanged from your original)*

### Hero section
- Title: **Hindu Scriptures & Knowledge Systems**
- Subtitle: **Explore the tree of revelation, interpretation, philosophy, and practice**
- Primary button: **Explore the Tree**
- Secondary button: **Read the Guide**

### Overview panel
Show four large pillars: Shruti · Smriti · Darshana · Agama

### Interactive tree preview
Clickable cards for: Vedas · Vedangas · Upavedas · Upangas · Prasthanatrayi · Puranas · Epics · Agamas · Shanmata

### Learning path
Offer 3 reading paths: beginner path · philosophy path · ritual and tradition path

---

## 8) Page Structure Blueprint

| Page | Purpose |
|---|---|
| **Home** | Orient the visitor quickly |
| **The Tree** | Show the whole knowledge system in one visual map |
| **Vedas** | Explain the four Vedas and their internal layers |
| **Vedangas** | Explain the six study tools, incl. the four Kalpa sub-branches |
| **Upavedas** | Explain applied knowledge and show variant lists |
| **Smriti** | Show law, memory, epics, and Puranic tradition |
| **Upangas** *(new)* | Clarify the 4-fold Upanga structure and its overlap with Darshana names |
| **Darshanas** | Show the six Astika schools (as three pairs) and the three-or-four Nastika traditions |
| **Prasthanatrayi** | Explain Vedanta's textual foundation clearly |
| **Agamas** *(split)* | Show the 3-branch Agama corpus **and** the 6-deity Shanmata worship tradition as related but separate |
| **Glossary** | Beginner-friendly vocabulary |
| **Sources / Notes** | Show where traditions vary and why |

---

## 9) Suggested Card Design Text

Each card on the site can use the same format: **Name** · **One-line meaning** · **Role in the system** · **Key sub-branches** · **Why it matters**

Example:

**Kalpa**
Ritual and procedural literature.
Supports practice, ceremony, and observance.
Sub-branches: Shrauta Sutras, Grihya Sutras, Dharma Sutras, Shulba Sutras.
Why it matters: it turns sacred knowledge into action.

Example 2 (new, illustrating the corrected Agama split):

**Agama - the texts**
Shaiva, Vaishnava, and Shakta scripture branches (~28 / ~108 / ~64 texts).
Governs temple architecture, iconography, and ritual sequence.
Why it matters: this *is* the ritual constitution behind Hindu temple worship.

**Shanmata - the paths**
Six deity-focused household and temple worship traditions.
Popularized by Adi Shankaracharya as a unifying devotional framework.
Why it matters: shows how scripture (Agama + Purana) translates into six lived devotional communities.

---

## 10) Best-Match Summary Tree for the Site

```text
ROOT: Hindu Knowledge System
├── SHRUTI
│   ├── Vedas
│   │   └── Samhita / Brahmana / Aranyaka / Upanishad (×4)
│   ├── Vedangas
│   │   └── Shiksha / Vyakarana / Chhanda / Nirukta / Jyotisha / Kalpa
│   └── Upavedas
│       └── Ayurveda / Dhanurveda / Gandharvaveda / Arthashastra (Sthapatyaveda)
├── SMRITI
│   ├── Upangas
│   │   ├── Nyaya
│   │   ├── Mimamsa
│   │   ├── Itihasa-Purana (Ramayana, Mahabharata+Gita, 18+18 Puranas)
│   │   └── Dharmashastra
│   └── Sutra literature (Shrauta / Grihya / Dharma / Shulba)
├── DARSHANA
│   ├── Astika (paired: Nyaya-Vaisheshika, Samkhya-Yoga, Purva/Uttara Mimamsa)
│   │   └── Uttara Mimamsa / Vedanta
│   │       └── Prasthanatrayi (Upanishads, Brahma Sutras, Gita)
│   │           └── Advaita / Vishishtadvaita / Dvaita / ...
│   └── Nastika
│       ├── Bauddha
│       ├── Jaina
│       ├── Charvaka
│       └── (Ajivika - often added)
└── AGAMA
    ├── Textual corpus: Shaiva / Vaishnava (Pancharatra+Vaikhanasa) / Shakta
    └── Shanmata (worship): Shaiva / Vaishnava / Shakta / Ganapatya / Kaumara / Saura
```
---

## 10.1) Traditional 16-School Survey of Indian Philosophy

The list below follows the classic 16-system doxographical survey associated with Madhava's *Sarva-Darsana-Sangraha*. It is a traditional map of Indian philosophical schools, not a claim that these are the only schools that ever existed.

For each school, the table gives a short English description and the primary epistemic emphasis or principal means of knowledge highlighted by that tradition. Where a school accepts more than one pramana, the entry below keeps the summary deliberately short.

| # | School | Short English name | Primary epistemic emphasis |
|---|---|---|---|
| 1 | Charvaka / Lokayata | Materialism | Perception only (direct sense evidence) |
| 2 | Bauddha | Buddhism | Direct experience and disciplined insight |
| 3 | Arhata / Jaina | Jainism | Many-sided truth and standpoint-sensitive knowledge |
| 4 | Ramanuja system | Sri Vaishnavism | Scriptural testimony and devotional revelation |
| 5 | Purna-Prajna / Tattvavada | Dvaita Vedanta | Scripture, reasoning, and real distinction |
| 6 | Nakulisa-Pashupata | Pashupata Shaivism | Scripture, ascetic discipline, and yogic practice |
| 7 | Shaivism | Shaiva philosophy | Revelation, mantra, and devotion |
| 8 | Pratyabhijna | Kashmir Shaivism | Recognition of consciousness as self-aware reality |
| 9 | Raseshvara | Mercurial / alchemical school | Experimental transformation and yogic alchemy |
| 10 | Vaisheshika / Aulukya | Atomism | Perception and inference |
| 11 | Akshapada / Nyaya | Logic | Valid knowledge through the pramanas |
| 12 | Jaimini | Purva Mimamsa | Scriptural injunction and ritual interpretation |
| 13 | Paniniya | Grammar | Linguistic analysis and authoritative speech |
| 14 | Samkhya | Enumeration | Rational analysis of tattvas |
| 15 | Patanjala | Yoga | Disciplined direct realization guided by pramana |
| 16 | Vedanta / Adi Shankara | Advaita Vedanta | Upanishadic testimony and reasoning |

> Note: different doxographies sometimes group, rename, or reorder these schools. The list above is the 16-school survey used in classical doxographical literature, with concise English labels added for readability.

---

## 11) Machine-Readable Node Data

A compact JSON representation for wiring straight into a D3.js hierarchical layout (e.g. `d3.hierarchy` / `d3.tree`). `id` values are stable keys you can use as DOM/data-binding anchors; `parent: null` marks the root.

```json
{
  "nodes": [
    { "id": "root", "label": "Hindu Knowledge System", "parent": null, "tier": "root" },

    { "id": "shruti", "label": "Shruti", "sanskrit": "श्रुति", "parent": "root", "tier": "pillar", "blurb": "Revealed / heard, authorless (apaurusheya)." },
    { "id": "smriti", "label": "Smriti", "sanskrit": "स्मृति", "parent": "root", "tier": "pillar", "blurb": "Remembered / authored tradition." },
    { "id": "darshana", "label": "Darshana", "sanskrit": "दर्शन", "parent": "root", "tier": "pillar", "blurb": "Philosophical systems / viewpoints." },
    { "id": "agama", "label": "Agama / Tantra", "sanskrit": "आगम", "parent": "root", "tier": "pillar", "blurb": "Ritual, temple, and sadhana literature." },

    { "id": "vedas", "label": "The 4 Vedas", "parent": "shruti", "tier": "branch" },
    { "id": "rigveda", "label": "Rigveda", "parent": "vedas", "tier": "leaf" },
    { "id": "yajurveda", "label": "Yajurveda", "parent": "vedas", "tier": "leaf" },
    { "id": "samaveda", "label": "Samaveda", "parent": "vedas", "tier": "leaf" },
    { "id": "atharvaveda", "label": "Atharvaveda", "parent": "vedas", "tier": "leaf" },

    { "id": "vedangas", "label": "Vedangas (6)", "parent": "shruti", "tier": "branch" },
    { "id": "shiksha", "label": "Shiksha", "parent": "vedangas", "tier": "leaf" },
    { "id": "vyakarana", "label": "Vyakarana", "parent": "vedangas", "tier": "leaf" },
    { "id": "chhanda", "label": "Chhanda", "parent": "vedangas", "tier": "leaf" },
    { "id": "nirukta", "label": "Nirukta", "parent": "vedangas", "tier": "leaf" },
    { "id": "jyotisha", "label": "Jyotisha", "parent": "vedangas", "tier": "leaf" },
    { "id": "kalpa", "label": "Kalpa", "parent": "vedangas", "tier": "leaf" },
    { "id": "shrauta_sutra", "label": "Shrauta Sutras", "parent": "kalpa", "tier": "sub-leaf" },
    { "id": "grihya_sutra", "label": "Grihya Sutras", "parent": "kalpa", "tier": "sub-leaf" },
    { "id": "dharma_sutra", "label": "Dharma Sutras", "parent": "kalpa", "tier": "sub-leaf" },
    { "id": "shulba_sutra", "label": "Shulba Sutras", "parent": "kalpa", "tier": "sub-leaf" },

    { "id": "upavedas", "label": "Upavedas (4)", "parent": "shruti", "tier": "branch", "blurb": "Veda associations vary by source." },
    { "id": "ayurveda", "label": "Ayurveda", "parent": "upavedas", "tier": "leaf" },
    { "id": "dhanurveda", "label": "Dhanurveda", "parent": "upavedas", "tier": "leaf" },
    { "id": "gandharvaveda", "label": "Gandharvaveda", "parent": "upavedas", "tier": "leaf" },
    { "id": "arthashastra", "label": "Arthashastra (var. Sthapatyaveda)", "parent": "upavedas", "tier": "leaf" },

    { "id": "upangas", "label": "Upangas (4)", "parent": "smriti", "tier": "branch" },
    { "id": "nyaya_upanga", "label": "Nyaya", "parent": "upangas", "tier": "leaf" },
    { "id": "mimamsa_upanga", "label": "Mimamsa", "parent": "upangas", "tier": "leaf" },
    { "id": "itihasa_purana", "label": "Itihasa-Purana", "parent": "upangas", "tier": "leaf", "blurb": "Called the 'fifth Veda' in Chandogya Up. 7.1.2." },
    { "id": "dharmashastra", "label": "Dharmashastra", "parent": "upangas", "tier": "leaf" },

    { "id": "itihasa", "label": "Itihasa", "parent": "itihasa_purana", "tier": "sub-leaf" },
    { "id": "ramayana", "label": "Ramayana", "parent": "itihasa", "tier": "text" },
    { "id": "mahabharata", "label": "Mahabharata", "parent": "itihasa", "tier": "text" },
    { "id": "gita", "label": "Bhagavad Gita", "parent": "mahabharata", "tier": "text", "blurb": "Embedded in the Bhishma Parva; also the Smriti Prasthana of Vedanta." },

    { "id": "purana", "label": "Purana", "parent": "itihasa_purana", "tier": "sub-leaf" },
    { "id": "mahapuranas", "label": "18 Mahapuranas (complete list)", "parent": "purana", "tier": "text",
      "items": ["Brahma", "Padma", "Vishnu", "Shiva", "Bhagavata", "Narada",
                "Markandeya", "Agni", "Bhavishya", "Brahma Vaivarta", "Linga", "Varaha",
                "Skanda", "Vamana", "Kurma", "Matsya", "Garuda", "Brahmanda"] },
    { "id": "upapuranas", "label": "18 Upapuranas (one full traditional list)", "parent": "purana", "tier": "text",
      "items": ["Sanatkumara", "Narasimha", "Brihannaradiya", "Sivarahasya", "Durvasa", "Kapila",
                "Vamana", "Bhargava", "Varuna", "Kalika", "Samba", "Nandi",
                "Surya", "Parasara", "Vashishtha", "Devi Bhagavata", "Ganesha", "Hamsa"] },

    { "id": "purana_major", "label": "Mahapuranas - complete node list", "parent": "purana", "tier": "branch" },
    { "id": "mp_brahma", "label": "Brahma Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_padma", "label": "Padma Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_vishnu", "label": "Vishnu Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_shiva", "label": "Shiva Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_bhagavata", "label": "Bhagavata Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_narada", "label": "Narada Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_markandeya", "label": "Markandeya Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_agni", "label": "Agni Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_bhavishya", "label": "Bhavishya Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_brahmavaivarta", "label": "Brahma Vaivarta Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_linga", "label": "Linga Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_varaha", "label": "Varaha Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_skanda", "label": "Skanda Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_vamana", "label": "Vamana Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_kurma", "label": "Kurma Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_matsya", "label": "Matsya Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_garuda", "label": "Garuda Purana", "parent": "purana_major", "tier": "leaf" },
    { "id": "mp_brahmanda", "label": "Brahmanda Purana", "parent": "purana_major", "tier": "leaf" },

    { "id": "purana_minor", "label": "Upapuranas - complete node list", "parent": "purana", "tier": "branch" },
    { "id": "up_sanatkumara", "label": "Sanatkumara Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_narasimha", "label": "Narasimha Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_brihannaradiya", "label": "Brihannaradiya Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_sivarahasya", "label": "Sivarahasya Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_durvasa", "label": "Durvasa Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_kapila", "label": "Kapila Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_vamana", "label": "Vamana Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_bhargava", "label": "Bhargava Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_varuna", "label": "Varuna Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_kalika", "label": "Kalika Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_samba", "label": "Samba Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_nandi", "label": "Nandi Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_surya", "label": "Surya Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_parasara", "label": "Parasara Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_vashishtha", "label": "Vashishtha Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_devi_bhagavata", "label": "Devi Bhagavata Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_ganesha", "label": "Ganesha Purana", "parent": "purana_minor", "tier": "leaf" },
    { "id": "up_hamsa", "label": "Hamsa Purana", "parent": "purana_minor", "tier": "leaf" },

    { "id": "sutra_literature", "label": "Sutra Literature", "parent": "smriti", "tier": "branch" },

    { "id": "astika", "label": "Astika (6)", "parent": "darshana", "tier": "branch" },
    { "id": "nyaya_d", "label": "Nyaya", "parent": "astika", "tier": "leaf", "pair": "1" },
    { "id": "vaisheshika", "label": "Vaisheshika", "parent": "astika", "tier": "leaf", "pair": "1" },
    { "id": "samkhya", "label": "Samkhya", "parent": "astika", "tier": "leaf", "pair": "2" },
    { "id": "yoga", "label": "Yoga", "parent": "astika", "tier": "leaf", "pair": "2" },
    { "id": "purva_mimamsa", "label": "Purva Mimamsa", "parent": "astika", "tier": "leaf", "pair": "3" },
    { "id": "uttara_mimamsa", "label": "Uttara Mimamsa / Vedanta", "parent": "astika", "tier": "leaf", "pair": "3" },

    { "id": "prasthanatrayi", "label": "Prasthanatrayi", "parent": "uttara_mimamsa", "tier": "branch" },
    { "id": "upanishads", "label": "Upanishads", "parent": "prasthanatrayi", "tier": "text", "blurb": "Shruti Prasthana" },
    { "id": "brahma_sutras", "label": "Brahma Sutras", "parent": "prasthanatrayi", "tier": "text", "blurb": "Nyaya Prasthana" },
    { "id": "gita_prasthana", "label": "Bhagavad Gita", "parent": "prasthanatrayi", "tier": "text", "blurb": "Smriti Prasthana - same text node as 'gita' above" },

    { "id": "vedanta_schools", "label": "Vedanta Sub-Schools", "parent": "uttara_mimamsa", "tier": "branch" },
    { "id": "advaita", "label": "Advaita", "parent": "vedanta_schools", "tier": "leaf" },
    { "id": "vishishtadvaita", "label": "Vishishtadvaita", "parent": "vedanta_schools", "tier": "leaf" },
    { "id": "dvaita", "label": "Dvaita", "parent": "vedanta_schools", "tier": "leaf" },

    { "id": "nastika", "label": "Nastika (3, +Ajivika)", "parent": "darshana", "tier": "branch" },
    { "id": "bauddha", "label": "Bauddha (Buddhism)", "parent": "nastika", "tier": "leaf" },
    { "id": "jaina", "label": "Jaina (Jainism)", "parent": "nastika", "tier": "leaf" },
    { "id": "charvaka", "label": "Charvaka / Lokayata", "parent": "nastika", "tier": "leaf" },
    { "id": "ajivika", "label": "Ajivika (often added)", "parent": "nastika", "tier": "leaf", "note": "optional 4th" },

    { "id": "agama_corpus", "label": "Agama textual corpus (3 branches)", "parent": "agama", "tier": "branch" },
    { "id": "shaiva_agama", "label": "Shaiva Agamas (~28)", "parent": "agama_corpus", "tier": "leaf" },
    { "id": "vaishnava_agama", "label": "Vaishnava Agamas (~108)", "parent": "agama_corpus", "tier": "leaf" },
    { "id": "pancharatra", "label": "Pancharatra", "parent": "vaishnava_agama", "tier": "sub-leaf" },
    { "id": "vaikhanasa", "label": "Vaikhanasa", "parent": "vaishnava_agama", "tier": "sub-leaf" },
    { "id": "shakta_agama", "label": "Shakta Agamas / Tantras (~64)", "parent": "agama_corpus", "tier": "leaf" },

    { "id": "shanmata", "label": "Shanmata (6-fold worship)", "parent": "agama", "tier": "branch", "blurb": "Popularized by Adi Shankaracharya." },
    { "id": "shanmata_shaiva", "label": "Shaiva - Shiva", "parent": "shanmata", "tier": "leaf" },
    { "id": "shanmata_vaishnava", "label": "Vaishnava - Vishnu", "parent": "shanmata", "tier": "leaf" },
    { "id": "shanmata_shakta", "label": "Shakta - Devi/Shakti", "parent": "shanmata", "tier": "leaf" },
    { "id": "shanmata_ganapatya", "label": "Ganapatya - Ganesha", "parent": "shanmata", "tier": "leaf" },
    { "id": "shanmata_kaumara", "label": "Kaumara - Kartikeya", "parent": "shanmata", "tier": "leaf" },
    { "id": "shanmata_saura", "label": "Saura - Surya", "parent": "shanmata", "tier": "leaf" }
  ]
}
```

---

## 12) Sanskrit Diacritics Reference (optional polish layer)

For a site that already renders Sanskrit terms with care (Cormorant Garamond, gold accents), IAST diacritics for the key top-level terms:

| Plain | IAST |
|---|---|
| Rigveda | Ṛgveda |
| Vaisheshika | Vaiśeṣika |
| Samkhya | Sāṃkhya |
| Shaiva | Śaiva |
| Shakta | Śākta |
| Chhanda | Chandas |
| Jyotisha | Jyotiṣa |
| Charvaka | Cārvāka |
| Prasthanatrayi | Prasthānatrayī |

---

## 13) Source Notes

This structure was cross-checked against: Wikipedia entries for *Vedas*, *Puranas*, *Prasthanatrayi*, *Āstika and nāstika*, *Hindu philosophy*, and *Agama (Hinduism)*; Hindupedia's *Upaveda* and *Upanga* entries; Dharmawiki's *Vaidika Vangmaya* and *Prasthana Trayi* pages; and several Ayurveda/Vedic-heritage reference sites for the Upaveda association tables. Where these sources disagreed with each other (which happens more than survey videos usually admit), that disagreement is preserved on the page rather than resolved by picking one version silently - see Section 6.

---

## 14) Final Build Intent

This site should help a visitor understand:

1. what the core texts are
2. how the supporting sciences work
3. how applied knowledge branches out
4. how philosophy is organized - including the real overlap between "Upanga" names and "Darshana" names
5. how ritual and worship traditions fit into the whole system - including the real distinction between Agama texts and the Shanmata worship framework
6. where the Bhagavad Gita belongs in the wider map (embedded in the Mahabharata *and* the Smriti Prasthana of Vedanta - both, simultaneously)

The website should feel less like a textbook and more like a **living sacred archive** - one confident enough to show its own scholarly seams instead of sanding them flat.
