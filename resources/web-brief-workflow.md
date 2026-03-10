# Web Brief Workflow

- Purpose: Keep the developer brief clean while preserving strategic thinking and revision history
- Date: 2026-03-09

---

## 1. Artifact Roles

| File | Role |
|---|---|
| `web-brief-digihub-position-paper.md` | Source of truth for web build scope, page structure, content model, and acceptance criteria |
| `web-brief-digihub-position-paper-notes.md` | Strategy notes, unresolved questions, review findings, reference prompts, content watchouts |
| `changelog-YYYY-MM-DD-*.md` | Decision log for adopted changes that affected the brief or the publication |

---

## 2. Working Rule

New thinking does not go straight into the brief.

It first lands in notes, then gets decided, then gets distilled into the brief, and only then turns into build work.

---

## 3. Revision Cycle

1. Capture

- Put new ideas, questions, references, and critiques into the notes file.
- Do not insert unresolved thinking into the brief.

2. Decide

- Review new notes with the relevant leads.
- Decide whether each item changes:
  - argument
  - page structure
  - content model
  - component scope
  - supporting material only

3. Distill

- Update the main brief only with decisions that are now stable enough for build or content production.
- Rewrite the result as requirements, not discussion.

4. Implement

- Turn brief changes into build tasks, design tasks, and content tasks.
- Keep task wording aligned to the brief, not to the notes.

5. Log

- Add a changelog entry for adopted changes that materially alter the brief or publication.
- Do not use the changelog as a brainstorming space.

---

## 4. What Stays Out of the Main Brief

- open questions
- research trails
- competing wording options
- long lists of references
- workshop notes
- speculative future variants

If a line contains "maybe," "consider," or "we should discuss," it probably belongs in notes, not in the brief.

---

## 5. Definition of Ready for the Brief

A section is ready to appear in the main brief when it has:

- a clear user-facing purpose
- a stable content requirement
- a known default state in the UI
- any required diagrams or supporting elements identified
- no unresolved strategic debate inside the section spec

---

## 6. Definition of Done for Each Revision

- The brief reflects the current build reality.
- Notes still hold the unresolved and exploratory material.
- The changelog records adopted changes.
- Any new work has been translated into actionable tasks.

---

## 7. GitHub Integration

The existing two-branch workflow (draft / main) carries the revision cycle:

| Workflow step | GitHub mechanism |
|---|---|
| Capture new thinking | Edit notes file or section `.md` on `draft` branch |
| Decide on open questions | GitHub Issues labeled `decision-needed`; resolve in comments or meetings, close when decided |
| Distill into brief | PR from `draft` to `main` with changelog entry in the PR description |
| Implement | Build/content work on `draft`; preview at `/preview/` URL |
| Log | Changelog file updated in the same PR that updates the brief |
| Invite colleague feedback | "Edit on GitHub (draft)" buttons in the live preview; GitHub comments on PRs |

### Issue Labels

| Label | Use |
|---|---|
| `decision-needed` | Open question from the notes backlog |
| `content` | Section drafting or revision work |
| `build` | Web implementation task |
| `diagram` | Visual/diagram production |

### Converting the Open Question Backlog

The 12 items in `web-brief-digihub-position-paper-notes.md` Section 5 should be created as GitHub Issues labeled `decision-needed`. This makes them trackable, assignable, and closeable — and visible to the team without reading the notes file.

---

## 8. Suggested Cadence

- Update notes continuously.
- Review and distill into the brief at the end of each meaningful content or strategy session.
- Write a changelog entry only when the brief itself changes.
