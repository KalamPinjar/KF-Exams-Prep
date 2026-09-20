# Kun Faqeehan — Level 1 · Mock Exams

A self-contained MCQ practice site for the **Kun Faqeehan Level 1** syllabus. Every question and
answer is drawn only from the uploaded course notes.

- **528 questions** across all 7 syllabus subjects, split into Easy / Medium / Hard
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
| 4 | At-Tawheed | Thalathat al-Usul + Nawaqid al-Islam | 19 | 19 | 40 | 78 |
| 5 | Fiqh | Aasan Fiqh (to p.59) | 20 | 26 | 43 | 89 |
| 6 | Seerat | Tajalliyat-e-Nabuwat | 18 | 24 | 30 | 72 |
| 7 | Ahadeeth al-Ahkam | Umdatul-Ahkam | 19 | 26 | 40 | 85 |
| + | └ Hifz ki 12 Ahadith | Umdatul-Ahkam | 4 | 20 | 24 | 48 |
| | | **Total** | **135** | **166** | **227** | **528** |

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
| Qawa'id al-Lughat-il-'Arabiyyah | ✅ 59 / 59 |
| At-Tawheed | ✅ 78 / 78 |
| Fiqh | ✅ 89 / 89 |
| Seerat | ✅ 72 / 72 |
| Ahadeeth al-Ahkam (incl. Hifz) | ✅ 133 / 133 |
| **Total** | **✅ 528 / 528** |


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

## Deploying on GitHub Pages

The whole site is one file with no build step.

1. Create a new repository on GitHub.
2. Upload `index.html` to the root of the repo (drag and drop works).
3. Go to **Settings → Pages**.
4. Under *Source*, choose **Deploy from a branch**, pick `main` and folder `/ (root)`, then Save.
5. Wait about a minute. Your site appears at `https://<username>.github.io/<repo>/`.

From the command line instead:

```bash
git init
git add index.html README.md
git commit -m "Kun Faqeehan Level 1 mock exams"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

Then enable Pages as in steps 3–5 above.

### Notes

- Works from `file://` too — just double-click `index.html` to open it locally.
- The only external requests are Google Fonts; the page degrades to system fonts offline.
- Renaming the file is fine for local use, but GitHub Pages needs it named `index.html`
  to serve at the root URL.
- Progress is per-browser. Clearing site data or switching device resets history.
