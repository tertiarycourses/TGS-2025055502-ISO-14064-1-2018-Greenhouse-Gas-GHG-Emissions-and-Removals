# Courseware QA Report — v2.0

Course: ISO 14064-1:2018 Greenhouse Gas (GHG) Emissions and Removals  
Course code: TGS-2025055502  
Audit date: 20 August 2026

## Overall verdict

**PASS.** The current courseware, activity and assessment artifacts pass structural, alignment and rendered-page review. The approved public distribution boundary excludes assessments, source references, secrets, build tooling and QA renders.

## A. PowerPoint quality — PASS

- 116-slide editable PowerPoint and matching 116-page PDF.
- Course-specific image-generated cover hero, single `v2.0` label and correct course code.
- Separate general trainer template and named Dr Alfred Ang profile.
- Visual activity-access, assessment-flow, topic-model, decision-lens, activity-process and acceptance-check slides.
- No click-by-click activity procedure in the deck; detailed procedures are in the Learner Guide and activity packs.
- All 116 rendered pages were inspected after the final rebuild; no clipped or overlapping text remains.
- Practice Exam: not applicable. This is not a certification-preparation course and no matching approved practice exam was supplied.

## B. Assessment quality — PASS

- Original instrument types and timings preserved: WA (SAQ), 9 open-ended questions, 60 minutes; Case Study, 4 open-ended questions, 60 minutes.
- Page 1 is the correct instrument cover. Candidate page 2 contains Trainee Information, full instructions, clickable LMS link and grading block. Questions begin on page 3.
- All 34 rendered pages across the two papers and two answer keys were inspected.
- Candidate papers are learner-accessible on Drive. Answer keys are in the limited-access `Assessment/Trainer Answer Keys` folder, have zero effective public/domain permissions and do not return DOCX content anonymously.

| Criterion | Assessment question | Activity alignment |
|---|---:|---|
| K1 | WA Q1 | Activities 1-3 |
| K2 | WA Q2 | Activities 1, 3 and 10 |
| K3 | WA Q6 | Activities 6-7 |
| K4 | WA Q7 | Activity 8 |
| K5 | WA Q3 | Activities 1-4 |
| K6 | WA Q4 | Activities 4-5 |
| K7 | WA Q5 | Activities 5 and 10 |
| K8 | WA Q8 | Activities 9-10 |
| K9 | WA Q9 | Activities 7, 9 and 10 |
| A1 | CS Q3 | Activities 6-7 |
| A2 | CS Q4 | Activity 9 |
| A3 | CS Q1 | Activities 1-3 |
| A4 | CS Q2 | Activities 4-5 |
| A5 | CS Q4 | Activity 10 |
| A6 | CS Q3 | Activity 8 |
| A7 | CS Q1 | Activities 2-3 |
| A8 | CS Q2 | Activity 5 |

## C. Lesson Plan — PASS

- WSQ cover, version-control record, page-numbered TOC and copyright/page footer present.
- Two days each total exactly 480 training minutes excluding lunch.
- Slide references were rebuilt against the final 116-slide deck.
- All 7 rendered pages inspected; schedule rows stay intact, headers repeat as needed, and the competency map fits on one page.

## D. Learner Guide — PASS

- WSQ cover, version-control record, compact page-numbered TOC and footer present.
- Markdown and DOCX/PDF are generated from the same source.
- Detailed scenarios, questions, procedures, required evidence and acceptance checks are included for all ten activities.
- All 30 rendered pages inspected; competency headers repeat and no content is clipped.

## E. Activities and alignment — PASS

- Ten learner-facing folders under `activities/`; no learner-facing `labs/` folder.
- Every folder contains `README.md`, matching `README.pdf`, an activity-pack PDF and a working Excel workbook.
- All 10 workbooks open successfully; all 40 current Drive activity files checksum-match local files.
- Activities form one connected EcoForge Asia case from inventory purpose through board-level carbon strategy.

## F. Files, versions and publication — PASS

- Single current v2.0 deck; matching current PDFs for deck, Learner Guide and Lesson Plan.
- Google Drive dry-run completed before write; 51/51 current files checksum-matched on readback.
- Drive duplicate-name audit completed; three identical duplicate IDs were moved to archive before LMS selection.
- LMS/TMS dry-run completed, followed by a full read-modify-write update (`HTTP 200`) and live-link readback for all seven fields.
- Before/after audit confirmed all unrelated course fields were preserved and the 4-topic structure remained semantically unchanged.
- The requested `/tms-push-qa` command was not installed. Equivalent safeguards were completed through this QA, a secure 46-field before snapshot, TMS dry-run, duplicate-resolution check, production write and semantic readback.

