# 7-Day Gen AI Tools Bootcamp
## Built from the Be10X AI Tools workshop notes, redesigned with new scenarios and free-tier-first labs

### Design rules
- Each day uses only free or free-trial access paths.
- No paid-only integrations, no enterprise-only features, and no heavy usage assumptions.
- Every lab ends with a concrete output you can verify.
- Scenarios are original and are not copied from the workshop note.

---

## Day 1 — Research, reading, and voice-first productivity
### Tools
- NotebookLM
- Wispr Flow

### Learning outcome
Turn long content into usable study material, then capture ideas faster by voice.

### Tool 1: NotebookLM
**What it is**
A source-grounded research assistant for PDFs, docs, web sources, and notes.

**Free-tier-friendly scenario**
Build a “7-day bootcamp source notebook” from:
1. one PDF,
2. one article,
3. one pasted note,
4. your own bullet list.

Then use it to generate:
- a short summary,
- a study guide,
- a quiz,
- a mind map,
- an audio overview.

**Step-by-step lab**
1. Sign in with a Google account.
2. Create a new notebook.
3. Add 3–4 sources only. Keep the source set small to stay within free usage comfortably.
4. Ask for a 150-word summary of the sources.
5. Ask for a “common mistakes” list.
6. Generate a quiz with 5 questions.
7. Generate an Audio Overview.
8. Review the output and mark 3 points that were missed.
9. Ask for a refined summary based on the missed points.
10. Export or copy the final notes into a shared doc.

**Deliverable**
One notebook with summary, quiz, and audio overview.

### Tool 2: Wispr Flow
**What it is**
Voice dictation that turns spoken thoughts into clean text.

**Free-tier-friendly scenario**
Use voice dictation to draft a workshop announcement, a follow-up email, and a LinkedIn post without typing the first draft.

**Step-by-step lab**
1. Install the app on a supported device.
2. Open a blank note or document.
3. Press the trigger button.
4. Speak a 60–90 second rough draft.
5. Stop dictation.
6. Edit obvious errors manually.
7. Ask NotebookLM or Claude to polish the draft later.
8. Repeat once with a faster speaking pace to test accuracy.

**Deliverable**
Three usable first drafts created by voice.

---

## Day 2 — UI creation and rapid app prototyping
### Tools
- Google Stitch
- Google AI Studio

### Learning outcome
Convert a product idea into a usable interface, then move from UI concept to working prototype.

### Tool 3: Google Stitch
**What it is**
An AI UI generation tool for web and mobile interfaces.

**Free-tier-friendly scenario**
Design a “Micro Learning Dashboard” for a bootcamp student:
- course cards,
- progress tracker,
- quiz button,
- saved notes section,
- reminder panel.

**Step-by-step lab**
1. Open Stitch in Google Labs.
2. Start with one clear prompt describing the audience and screen purpose.
3. Add layout requirements: dashboard, sidebar, cards, and a top search bar.
4. Ask for a light theme and a dark theme version.
5. Refine the prompt by removing extra UI clutter.
6. Pick the best version and review spacing, hierarchy, and button placement.
7. Export the design or copy the structure into your notes.
8. List what is missing before build time.

**Deliverable**
A clean dashboard mockup with two UI variations.

### Tool 4: Google AI Studio
**What it is**
A place to experiment with Gemini models and prototype app logic.

**Free-tier-friendly scenario**
Turn the dashboard concept into a simple “study assistant” prototype that:
- accepts a user question,
- summarizes a source,
- generates a checklist,
- returns a sample next action.

**Step-by-step lab**
1. Open AI Studio and start a new chat or project.
2. Paste the UI requirements and expected behavior.
3. Ask for a front-end implementation outline first.
4. Request the HTML/CSS/JS structure in small chunks.
5. Ask for the logic to be separated from the UI.
6. Test one feature at a time: summary, checklist, and next-step suggestion.
7. Ask for improvements to button text and error messages.
8. Keep the app minimal so it stays easy to test on a free account.

**Deliverable**
A simple prototype spec or working starter code.

---

## Day 3 — Writing, coding, and data analysis
### Tools
- Claude
- Julius AI

### Learning outcome
Use one tool for deep writing/coding help and another for data analysis and visual storytelling.

### Tool 5: Claude
**What it is**
A general-purpose AI assistant strong at reasoning, writing, and code assistance.

**Free-tier-friendly scenario**
Create a “bootcamp operations pack”:
- syllabus outline,
- FAQ,
- learner checklist,
- follow-up email draft,
- mini lesson script.

**Step-by-step lab**
1. Open Claude Free.
2. Give a precise task with one output at a time.
3. Ask for a 7-day syllabus skeleton first.
4. Then ask for learner FAQ questions.
5. Next ask for a short instructor script for Day 1.
6. Finally ask it to tighten the wording and remove repetition.
7. Keep prompts bounded so the free limit is not wasted on overlong chats.

**Deliverable**
A polished operations pack for the bootcamp.

### Tool 6: Julius AI
**What it is**
An AI analysis tool for spreadsheets, charts, and slide-friendly insights.

**Free-tier-friendly scenario**
Analyze a fake learner-feedback sheet with columns like:
- day,
- satisfaction score,
- confusion area,
- recommended improvement.

**Step-by-step lab**
1. Prepare a small CSV with 20–50 rows.
2. Upload the file.
3. Ask for a summary of the highest and lowest scoring days.
4. Ask for a chart showing score trends.
5. Ask for the top 3 confusion topics.
6. Request a slide-ready summary in bullets.
7. Check whether the answer is grounded in the uploaded file.
8. Export the key insights manually.

**Deliverable**
A short analytics brief with charts and action points.

---

## Day 4 — Resume, job search, and interview practice
### Tools
- ATS Resume workflow from the workshop note
- ChatGPT Voice

### Learning outcome
Improve a resume for a target role and practice answering interview questions aloud.

### Tool 7: ATS Resume Workflow
**What it is**
A resume optimization workflow based on a resume plus job description.

**Free-tier-friendly scenario**
Optimize a resume for a “Junior AI Tools Analyst” role using a target job description you paste manually.

**Step-by-step lab**
1. Start with a plain resume in text or PDF form.
2. Paste the job description into the assistant.
3. Ask for missing skills, weak keywords, and formatting issues.
4. Ask for a rewritten summary, skills section, and 3 impact bullets.
5. Compare the old and revised versions.
6. Keep the output ATS-safe: simple headings, no tables, no fancy graphics.
7. Save the final version as a clean document.

**Deliverable**
One ATS-safe resume revision.

### Tool 8: ChatGPT Voice
**What it is**
A voice-based conversation mode for live practice and dictation.

**Free-tier-friendly scenario**
Run a mock interview for the same job you optimized the resume for.

**Step-by-step lab**
1. Open ChatGPT and start voice mode.
2. Tell it to act like an interviewer.
3. Ask it to question you on your resume, tools, and project experience.
4. Answer out loud for 5–7 minutes.
5. Ask for feedback on weak answers.
6. Repeat with one tougher question set.
7. Use the feedback to rewrite two weak answers.

**Deliverable**
A mock interview transcript plus improved answers.

---

## Day 5 — Browser automation and job search workflows
### Tool
- Comet

### Learning outcome
Use browser-level AI to search, filter, and organize online tasks faster.

### Free-tier-friendly scenario
Find role listings for a specific profile and build a short application tracker without automating risky or high-volume actions.

**Step-by-step lab**
1. Open the browser and attach the profile or resume if needed.
2. Give one focused job-search prompt.
3. Ask for roles in one title family only.
4. Ask it to exclude internships, unpaid work, and unrelated domains.
5. Capture 10 relevant openings in a sheet.
6. Manually verify the company, location, and seniority.
7. Create a shortlist of 3 applications.
8. Use the tracker to note status, follow-up date, and required edits.

**Deliverable**
A verified shortlist of roles with an application tracker.

---

## Day 6 — Automation and agentic workflows
### Tool
- n8n

### Learning outcome
Build a no-code workflow that connects triggers, AI steps, and output actions.

### Free-tier-friendly scenario
Create a weekly “content assistant” workflow:
- input: a saved idea,
- AI step: expand it into a post outline,
- output: store it in a notes file.

**Step-by-step lab**
1. Use n8n Community Edition or a free trial path.
2. Create a new workflow.
3. Add a manual trigger first.
4. Add one text input node.
5. Add an AI node or HTTP-based AI call only if it is available on free access.
6. Ask the workflow to generate a short outline.
7. Add a final node that writes the result to a text file, email draft, or webhook.
8. Run the workflow once manually.
9. Fix the mapping if the output format breaks.
10. Save the workflow and rename the nodes clearly.

**Deliverable**
One working automation workflow.

---

## Day 7 — Capstone build day
### Tools
- NotebookLM
- Wispr Flow
- Stitch
- AI Studio
- Claude
- Julius AI
- ATS workflow
- ChatGPT Voice
- Comet
- n8n

### Capstone scenario: “AI Bootcamp Assistant”
Build a small end-to-end system for a student who wants to study, draft, analyze, apply, and automate.

**What the system does**
- NotebookLM stores the source material.
- Wispr Flow captures spoken notes.
- Stitch designs the student dashboard.
- AI Studio shapes the app logic.
- Claude writes the supporting copy.
- Julius AI reviews feedback data.
- ATS workflow improves the resume.
- ChatGPT Voice runs a mock interview.
- Comet finds opportunities.
- n8n automates weekly follow-ups.

**Build steps**
1. Define the student workflow in one page.
2. Add only the most important screens.
3. Create the UI mockup in Stitch.
4. Draft the app behavior in AI Studio.
5. Use Claude to generate help text and onboarding copy.
6. Store source notes in NotebookLM.
7. Test the voice note capture with Wispr Flow.
8. Add a small analytics set and review it in Julius AI.
9. Run the resume and interview exercise.
10. Add one n8n workflow for reminders or content follow-up.
11. Finish by documenting the full flow as a one-page handoff.

**Final deliverable**
A complete bootcamp project pack with:
- source notebook,
- UI mockup,
- prototype text,
- resume revision,
- mock interview notes,
- analytics summary,
- one automation workflow.

---

## Free-tier guardrails
- Keep every lab small and focused.
- Use one task per prompt.
- Limit source counts and file sizes.
- Prefer draft generation over long back-and-forth chats.
- Avoid paid-only integrations, bulk automation, and enterprise features.
- Keep one reusable sample dataset for the whole week.

## What learners leave with
- Research and summarization skills
- Voice-to-text productivity
- UI prototyping habits
- AI-assisted writing and coding workflow
- Data analysis and charting workflow
- Resume and interview preparation
- Browser automation basics
- No-code automation basics
- A complete capstone workflow
