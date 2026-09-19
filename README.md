# Kun Faqeehan — Level 1 · Mock Exams

A self-contained MCQ practice site for the **Kun Faqeehan Level 1** syllabus. Every question and
answer is drawn only from the uploaded course notes.

- **480 questions** across all 7 syllabus subjects, split into Easy / Medium / Hard
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
