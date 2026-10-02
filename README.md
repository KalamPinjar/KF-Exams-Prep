# Kun Faqeehan — Level 1 · Mock Exams

A self-contained MCQ practice site for the **Kun Faqeehan Level 1** syllabus. Every question and
answer is drawn only from the uploaded course notes.

- **675 questions** across all 7 syllabus subjects, split into Easy / Medium / Hard
- **Hifz section** for the 12 Umdatul-Ahkam hadiths set for memorisation, with a hide-the-matn drill
- Practice mode (instant feedback + explanation) and Exam mode (feedback at the end)
- Per-subject tests, Full Papers, 3 Grand Mock Exams, and a custom test builder
- Full post-attempt review with explanations and a source reference on every question
- History, retakes, resume-in-progress, light/dark themes, mobile responsive
- All progress saved in the browser via `localStorage` — no accounts, no server

## Question coverage

| # | Subject | Book | Easy | Med | Hard | Total |
|---|---------|------|-----:|----:|-----:|------:|
| 1 | At-Taabeer *(oral)* | At-Taabeer | 18 | 16 | 11 | 45 |
| 2 | Al-Qira'ah wal-Kitabah *(oral)* | Al-Qira'ah wal-Kitabah + Mu'jam | 20 | 18 | 14 | 52 |
| 3 | Qawa'id al-Lughat-il-'Arabiyyah | Tehseen-an-Nahw | 17 | 17 | 25 | 59 |
| + | └ Pehchan (identification drill) | Tehseen-an-Nahw | 15 | 30 | 21 | 66 |
| 4 | At-Tawheed | Thalathat al-Usul + Nawaqid al-Islam | 19 | 19 | 40 | 78 |
| 5 | Fiqh | Aasan Fiqh (to p.59) | 21 | 33 | 51 | 105 |
| 6 | Seerat | Tajalliyat-e-Nabuwat | 27 | 47 | 63 | 137 |
| 7 | Ahadeeth al-Ahkam | Umdatul-Ahkam | 19 | 26 | 40 | 85 |
| + | └ Hifz ki 12 Ahadith | Umdatul-Ahkam | 4 | 20 | 24 | 48 |
| | | **Total** | **160** | **226** | **289** | **675** |

**At-Taabeer** and **Al-Qira'ah wal-Kitabah** are examined orally, so their questions target
vocabulary (*lughat*), useful phrases and spoken usage rather than written grammar analysis.

**At-Tawheed** carries 29 dedicated *daleel* (evidence) questions — "which ayah is the proof for
X" — since the matn of Thalathat al-Usul is built that way. Seerat carries 4 more where relevant.

## Language

The interface ships in **Roman English by default** and can be switched to **Urdu** — either from
the `EN / اردو` button in the navbar or from Settings. Urdu mode uses Noto Nastaliq Urdu, flips the
layout to right-to-left, and reverses the arrow-key navigation to match. The choice is saved and
survives a reload; resetting your data does not reset it.

**The interface and all 528 questions are fully translated into Urdu.** Every subject is complete —
question text, all four options, and the explanation. Arabic and Qur'anic quotations always render
in Naskh regardless of the setting, since those are quoted text rather than prose.

| Subject | Urdu question text |
|---|---|
| At-Taabeer | ✅ 45 / 45 |
| Al-Qira'ah wal-Kitabah | ✅ 52 / 52 |
| Qawa'id (incl. Pehchan) | ✅ 125 / 125 |
| At-Tawheed | ✅ 78 / 78 |
| Fiqh | ✅ 105 / 105 |
| Seerat | ✅ 137 / 137 |
| Ahadeeth al-Ahkam (incl. Hifz) | ✅ 133 / 133 |
| **Total** | **✅ 675 / 675** |


## Hifz — the 12 memorisation hadiths

The Umdat paper requires you to write out memorised hadiths and then answer on them, so there is a
dedicated **Hifz** page (reachable from the Ahadeeth al-Ahkam subject page). For each of the twelve
hadiths — #9, 11, 15, 17, 21, 22, 24, 28, 33, 39, 41, 43 — it carries:

- the full Arabic matn in Naskh, set large for reading and memorising
- transliteration, plus English and Roman Urdu translation
- a note on the narrating Companion (for the "write a brief note about the Sahabi" question)
- the key terms with their meanings (for the "meaning of the key term" question)
- the rulings and benefits derived (for the "derive two rulings" question)
- the source and grade — all twelve are Muttafaqun Alayhi

Three viewing modes: **Show everything**, **Arabic only**, and **Hide matn**, which blanks every
matn behind a tap-to-reveal panel while leaving the translation visible — so you can read the
meaning and recall the Arabic. A 48-question practice test covers narrators, translations, key
terms and derived rulings for all twelve.

### Mapping to the exam paper

| Paper question | Where to practise it |
|---|---|
| Q1 — write two memorised hadiths | Hifz page, **Hide matn** mode |
| Q2 — translate + note on the Sahabi | Hifz cards; narrator questions in the practice test |
| Q3 — translate, Sahabi, key term, lessons | Hifz cards (expand a card for all four) |
| Q4 — translate two + two rulings each | **Rulings & benefits** on each card |
| Q5 — translate + jurisprudential ruling | Hifz cards + the Fiqh subject tests |

## Study & Revision

A reference section (book icon in the navbar, or `#/study`) holding everything that has to be
memorised, in one place. Three tabs:

**Nawaqid al-Islam** — all ten nullifiers from the matn of Imam Muhammad bin Abdul Wahhab, each with
the Arabic text, Roman transliteration, Urdu translation, and the Qur'anic evidence where the matn
quotes one. Five of the ten carry an ayah — nullifiers 1, 6, 7, 8 and 10 — and the other five are
marked plainly as having no ayah in the matn rather than being padded with one from elsewhere.

| # | Nullifier | Evidence |
|---|---|---|
| 1 | Shirk | An-Nisa 48 · Al-Ma'idah 72 |
| 2 | Taking intermediaries | *ijma', no ayah in the matn* |
| 3 | Not declaring the mushrikeen disbelievers | *no ayah in the matn* |
| 4 | Preferring other than the Prophet's ﷺ guidance | *no ayah in the matn* |
| 5 | Hating what the Messenger ﷺ brought | *no ayah in the matn* |
| 6 | Mocking the religion | At-Tawbah 65–66 |
| 7 | Sihr | Al-Baqarah 102 |
| 8 | Supporting the mushrikeen against Muslims | Al-Ma'idah 51 |
| 9 | Believing one may leave the Shari'ah | *no ayah in the matn* |
| 10 | Turning away from the religion | As-Sajdah 22 |

**Anwa' al-Ibadah** — all fourteen types of worship named in Thalathat al-Usul, each with its own
daleel: Du'a, Khawf, Raja, Tawakkul, **Raghbah, Rahbah, Khushoo'**, Khashyah, Inabah, Isti'anah,
Isti'adhah, Istighathah, Dhabh and Nadhr. Raghbah, Rahbah and Khushoo' share one ayah (Al-Anbiya 90)
and the section says so explicitly, since that is how the matn presents them.

**Qawa'id charts** — ten tables covering the whole grammar tree: Lafz → Kalimah, the four divisions
of Ism, the three of Fi'l, the four i'rabi states, Huroof-e-Aamilah (17 / 6 / 5 / 4) and Ghair
Aamilah (3 / 10) with the actual letters listed, Murakkab Taam and its ten Insha'iyah types,
Murakkab Naqis and its six types, the alamaat of Ism/Fi'l/Harf, and the history of the science.

Where the notes give a count but not the full list — Huroof-e-Jarra are "17" with only examples
named, and Ma'rifah has 7 kinds of which the notes name 5 — the charts say exactly that rather than
completing the list from outside the syllabus.

## Question formats

The bank now uses every format the papers actually ask in, not just multiple choice. Each question
carries a style label shown above it in the runner:

| Format | Label | Count |
|---|---|---|
| Multiple choice | Multiple choice | 479 |
| Vocabulary recall | Lughat · vocabulary | 51 |
| Spoken usage | Bol-chaal · speaking | 42 |
| Evidence | Daleel · evidence | 37 |
| Translation | Translation | 17 |
| True / false | True or false | 13 |
| Fill in the blank | Fill in the blank | 12 |
| One-line answer | Short answer | 13 |
| Long answer | Long answer | 8 |
| Match the pair | Match the pair | 3 |

Everything is still answered by tapping an option — a true/false question offers the statement plus
the reason, a fill-in-the-blank shows the sentence with the gap and four candidates, and a long-answer
question offers four complete multi-part answers to choose between. Nothing is typed, so marking
stays instant.

## Pehchan — the identification drill

A dedicated test on the Qawa'id subject page. Each question hands you a word or a sentence and asks
what it is and which category it belongs to, and every answer explains the reason rather than just
naming the type. 66 questions covering:

- **Ism / Fi'l / Harf** by their alamaat — Alif-Lam, Tanween, Jar, gol Ta, Musanna, Jama for Ism;
  Qad, Seen/Sawfa, Jazm, Ta-e-Taanees Saakina, Ta-ul-Fa'il for Fi'l; absence of all for Harf
- **Mufrad vs Murakkab**, then Taam vs Naqis
- All six **Murakkab-e-Naqis** types — Tauseefi, Izafi, Ishari, Jari, Binai, Imtizaji
- **Jumla Ismiyah vs Fi'liyah**, **Khabariyah vs Insha'iyah**, and the Insha'iyah subtypes
- **Muzakkar/Muannas** with the three alamat-e-taanees, and the three kinds of **Jama**
- **Ma'rifah vs Nakirah**, **Mu'rab vs Mabni**
- The four **i'rabi halatein** and why each applies
- **Fi'l**: Ma'roof/Majhool with Na'ib Fa'il, Lazim/Muta'addi, and zamana
- Every kind of **harf** — Jarra, Mushabbahah, Jazimah, Nasibah, Istifham, Atf
- Full **tarkeeb** of complete sentences

It includes the traps the notes themselves flag — `الرَّجُلُ العَاقِلُ` is Tauseefi but
`مُحَمَّدٌ عَاقِلٌ` is a Mubtada-Khabar sentence, and the Waw-Noon of `تَعْلَمُونَ` is a verb
pronoun rather than a Jama-e-Muzakkar-Salim ending.

## Nasab naama — the lineage

A fourth tab in the Study section carries the Prophet's ص full lineage as a numbered spine, for
self-study. The paternal line runs all 22 generations to Adnan, which is where scholarly consensus
ends; above Adnan the notes record that names are disputed even though the broad chain to Ismail,
Ibrahim and Adam (AS) is agreed.

```
Muhammad ﷺ ← Abdullah ← Abdul Muttalib ← Hashim ← Abd Manaf ← Qusai ← Kilab ←
Murrah ← Ka'ab ← Luay ← Ghalib ← Fihr ← Malik ← An-Nadr ← Kinana ← Khuzaima ←
Mudrikah ← Ilyas ← Mudar ← Nizar ← Ma'ad ← Adnan
```

Four ancestors are highlighted because the syllabus keeps returning to them:

- **Kilab** — where the paternal and maternal lines meet
- **Fihr** and **An-Nadr** — the two opinions on whose title "Quraysh" was
- **Adnan** — the limit of consensus

Each ancestor carries the detail the paper asks for: real names before the titles (Hashim was *Amr*,
Abd Manaf was *Mughira*, Abdul Muttalib was *Shaybah*), why "Abdul Muttalib" stuck even though he was
Muttalib's **nephew** rather than his slave, Qusai's five offices and his marriage to Hubba bint
Hulail, and Hashim's two trade journeys.

The maternal line (Aminah bint Wahb bin Abd Manaf bin Zuhra bin Kilab) is shown separately with a
warning: its **Abd Manaf bin Zuhra** is a different man from **Abd Manaf bin Qusai** in the paternal
line, and the two chains meet only at Kilab. That trips people up in exams, so it is flagged in the
chart and tested in the questions.

The tab closes with the principle the lecture builds to — Surah Al-Hujurat 13 and
*bu'ithtu min khayri qurūni banī Ādam* — that lineage is for **ta'aruf**, while the measure with
Allah is **taqwa**, illustrated by Abu Lahab and Abu Talib on one side and Bilal, Salman al-Farsi
and Suhaib ar-Rumi (RA) on the other.

25 questions cover all of it, including the full chain as a long-answer and the Quraysh dispute.

## Seerat — second pass

A second pass over the Seerat notes added 40 questions, mostly from Lectures 5, 6, 20 and 22, which
were thinly covered the first time:

- **Lecture 5–6**: the definition of *khamr* (anything that veils or overpowers the intellect —
  drunk, inhaled or injected), halal/haram judged on benefit vs harm, the false notion of generosity
  in drunkenness, the stepmother-inheritance custom, the four kinds of jahili marriage with their
  mechanics, and the four Arab virtues including memorised camel and horse lineages
- **Lecture 20**: the Prophet's ﷺ character before prophethood — zuhd, hilm, tawadu, his modesty
  compared to a secluded virgin, Abu Talib's couplet, Abu Jahl's admission ("I do not doubt you, I
  doubt what you say"), the two nights he intended to attend entertainment and was put to sleep, and
  the three strands of his protection from shirk
- **Lecture 22**: the pre-prophethood signs, the threefold *ghatt* in the cave with
  "Mā anā bi-qāri'", and the first five ayat of Surah Al-Alaq

## Fiqh — additions from the Aasan Fiqh notes

16 questions were added from the uploaded Aasan Fiqh notes, covering material the bank did not
already have. Existing questions were left alone where the notes agreed with them.

- **Azaan and Iqamat phrase-by-phrase** — the 15 and 11 phrase breakdowns, including the difference
  (shahadatain and hayya'alah once each in iqamat, plus `Qad qaamatis-salah` twice)
- **Women**: azaan not obligatory / iqamat mustahab; mosque permitted with purdah but home is
  better; going adorned or perfumed is haram
- **Cigarette and bidi smell** alongside raw garlic and onion, for the same reason
- **Tayammum**: dusty wall permitted on the raajeh qaul; blowing on the hands after striking
- **Masah**: the three things that nullify it, as a set
- **Haidh**: no delaying ghusl, and the one-rakat rule — if a woman becomes pure with enough time
  left for a single rakat, that prayer must be made up
- **Water**: predators' leftovers paak if plentiful and unchanged (Daraqutni); dog and pig saliva;
  the fly ruling
- **Qay** paak on the raajeh qaul and not a nullifier of wudu; the 40-day limit on nails and hair

## Deploying on GitHub Pages

Repo: **https://github.com/KalamPinjar/KF-Exams-Prep**

The whole site is a single file with no build step, so deployment is just committing it.

```bash
git clone https://github.com/KalamPinjar/KF-Exams-Prep.git
cd KF-Exams-Prep

# copy the downloaded index.html into the repo root, then:
git add index.html README.md
git commit -m "Kun Faqeehan Level 1 — 610 questions, Urdu + Hifz + Study + Pehchan"
git push origin main
```

Then on GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save.**

The site goes live at **https://kalampinjar.github.io/KF-Exams-Prep/** in about a minute.

### Requirements and gotchas

- The file **must** be named `index.html` and sit in the **repo root** for that URL to work.
  If you put it in a `docs/` folder instead, choose `main / docs` as the Pages source.
- The repo must be **public**, or you need GitHub Pro for Pages on a private repo.
- No build step, no dependencies, no framework — do not add a workflow file; "Deploy from a
  branch" is all this needs.
- Pushing a new `index.html` later redeploys automatically within a minute. If you don't see the
  change, hard-refresh (Ctrl/Cmd + Shift + R) — the browser caches aggressively.
- Progress is stored per-browser in `localStorage`, keyed to the origin. Moving from a local file
  to the Pages URL starts history fresh; that's expected, not data loss.

