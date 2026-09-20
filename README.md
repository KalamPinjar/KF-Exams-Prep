# Kun Faqeehan — Level 1 · Mock Exams

A self-contained MCQ practice site for the **Kun Faqeehan Level 1** syllabus. Every question and
answer is drawn only from the uploaded course notes.

- **480 questions** across all 7 syllabus subjects, split into Easy / Medium / Hard
- Practice mode (instant feedback + explanation) and Exam mode (feedback at the end)
- Per-subject tests, Full Papers, 3 Grand Mock Exams, and a custom test builder
- Full post-attempt review with explanations and a source referen# Kun Faqeehan — Level 1 · Mock Exams

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
ce on every question
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
| | | **Total** | **131** | **146** | **203** | **480** |

**At-Taabeer** and **Al-Qira'ah wal-Kitabah** are examined orally, so their questions target
vocabulary (*lughat*), useful phrases and spoken usage rather than written grammar analysis.

**At-Tawheed** carries 29 dedicated *daleel* (evidence) questions — "which ayah is the proof for
X" — since the matn of Thalathat al-Usul is built that way. Seerat carries 4 more where relevant.

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
