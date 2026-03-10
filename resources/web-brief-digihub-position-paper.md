# Web Brief
## DigiHub Liechtenstein - Regenerative Digital Ecosystem

- Status: Working brief for the first web build
- Date: 2026-03-09
- Primary reader: Web developer
- Secondary readers: Design lead, content lead, strategy lead
- Lineage: Distilled from `content-brief-digihub-position-paper-v2.md`, `content-brief-digihub-position-paper-v3.md`, and `changelog-2026-03-09-v3-to-v4.md`

---

## 1. Project Goal

Build a clear, credible, responsive web publication for DigiHub Liechtenstein's strategic position paper.

The page should let a new reader:
- understand the core thesis in under 60 seconds
- scan the full argument in under 5 minutes
- expand into deeper material without losing orientation
- see a clear invitation to collaborate

This is not a product site, a research repository, or a technical architecture document.

---

## 2. Core Message

### One-Sentence Thesis

Programmable Organizational Domains (PODs) are the institutional layer that connects digital self-determination, commons governance, and regenerative economics.

### Page Promise

The publication should make one main claim legible: DigiHub Liechtenstein is using a small but well-connected jurisdiction to prototype a replicable institutional pattern for bioregional digital sovereignty.

### Non-Negotiable Framing Rules

- Lead with institutional capability, not technology.
- Keep the argument pattern-over-platform. IXO may be named, but never as the point of the paper.
- Treat Liechtenstein as a laboratory, not the universal end state.
- Be explicit about limits, dependencies, and what cannot be sovereignized locally.
- Keep collaborative finance contained and practical.
- Treat AI sovereignty inside the Data Commons section, not as a detached side-topic.

---

## 3. Primary Audiences

| Audience | What they need quickly | What will lose them |
|---|---|---|
| EDIH and EU policy audience | Why this matters now, how it differs from existing EU instruments, what is replicable | Platform pitch language, crypto-first framing, vague claims |
| Practitioners and partners | What the model does in practice, where collaboration starts, what the domains are | Abstract theory with no institutional form |
| Researchers and deep readers | Clear conceptual lineage, honest limitations, references and methodology access | Over-claiming novelty or ignoring known critiques |

---

## 4. Delivery Scope

### P0 - First Build

- Single responsive page with anchored section navigation
- Hero with title, summary, position statements, attribution
- Main sections with visible summaries and expandable deeper content
- Static diagram slots or image blocks for key visuals
- Separate supporting material area for glossary, references, methodology, and changelog
- Strong closing invitation with collaboration next steps
- Mobile, keyboard, and screen-reader friendly structure

### P1 - Strong Enhancement

- Maturity/status badges per section
- Glossary definitions inline or in a side panel
- Deep links to sub-sections
- Better diagram presentation and cross-links to supporting material

### P2 - Later

- Interactive diagram exploration
- Section-level changelog surfacing in the UI
- Alternate audience views or filters
- Interactive Wardley map

---

## 5. Page Structure

| Section | User job | Must include | Default state |
|---|---|---|---|
| Hero | Orient fast | Title, subtitle, 1-minute summary, 3-5 position statements, DigiHub attribution, collaboration CTA | Fully visible |
| 1. Framing | Understand why this paper exists | Sovereignty problem, institutional middle layer, why EU context is insufficient on its own | Summary visible, body collapsed |
| 2. Foundations | Understand the conceptual basis | Regenerative economics, digital self-determination, bioregional lens | Summary visible, body collapsed |
| 3. Situational Analysis | See actual dependencies and limits | Dependency landscape, Self/Together/Others framing, what stays in Others | Summary visible, body collapsed |
| 4. The Model | Understand DigiHub's original contribution | Architecture overview, PODs, domain deep dives, cross-domain tensions | Summary visible, sub-sections expandable |
| 5. Liechtenstein as Laboratory | Understand why this context matters | Regulatory agility, EDIH context, bioregional relevance, limitations and privilege critique | Summary visible, body collapsed |
| 6. Pathways | Understand how the model unfolds over time | Flywheel stages, stage criteria, failure modes, replication path | Summary visible, body collapsed |
| 7. Collaborative Finance | Understand economic sustainability without derailment | Funding logic, revenue sketch, clear boundaries on scope | Summary visible, body collapsed |
| 8. Invitation | Understand what DigiHub wants next | Partnership ask, pilot pathways, concrete next steps, contact route | Open near page end |
| Supporting material | Deepen without cluttering the main page | Glossary, methodology, references, changelog, case studies | Separate from core reading flow |

---

## 6. Section Content Model

Each main section should use the same pattern:

1. Descriptive heading
2. One- or two-sentence scan summary that remains visible when collapsed
3. Core argument block
4. Optional sub-sections
5. Diagram, image, or visual placeholder where needed
6. References or links to supporting material

Do not place unresolved questions, long research notes, or internal musings inside the section body.

---

## 7. Content Priorities

| Content area | Status | Build note |
|---|---|---|
| Framing | Strongest starting material | Safe to build now |
| The Model / PODs | Core differentiator | Safe to build now |
| Liechtenstein as Laboratory | Strong enough for first pass | Safe to build now |
| Pathways | Strong concept, needs metrics later | Build shell now |
| Foundations | Good substance, still synthesis-heavy | Build shell now, expect copy iteration |
| Situational Analysis | Needs workshop output and mapping work | Build shell with clear placeholder state |
| Collaborative Finance | Sensitive and easy to over-expand | Keep visually and editorially contained |
| Invitation | Depends on offer clarity | Build structure now, write final copy late |
| Supporting material | Useful but secondary | Keep out of the main argument flow |

---

## 8. Required Global Elements

- Sticky or persistent section navigation
- Clear current-section state
- Visible summary text for every major section
- Diagram slots for:
  - dependency landscape
  - POD typology
  - ecosystem architecture
  - sovereignty flywheel
- Separate glossary and references access
- Changelog link
- Version/date marker

---

## 9. UX and Visual Direction

- The experience should feel like a workshop document, not a brochure.
- Use generous spacing and strong hierarchy to reduce cognitive load.
- Headings should describe content directly. Avoid internal or academic labels as the main visible navigation language.
- Do not hide essential context behind interactions. Summaries must remain visible even when sections are collapsed.
- Treat diagrams as content, not decoration.
- Avoid stock imagery and generic "future tech" visuals.
- Keep the visual tone grounded, serious, and human.

---

## 10. Non-Goals

- No separate policy/practitioner/technical versions in v1
- No full technical architecture page in the core reading flow
- No deep monetary theory in the main page
- No "all references inline at all times" layout
- No product-led homepage language

---

## 11. Acceptance Criteria

- A new visitor can understand the thesis and why DigiHub is making this claim within the hero and first section.
- Every major section is scannable without opening all sub-sections.
- The Model section clearly differentiates PODs from adjacent concepts and does not read like a platform pitch.
- The Situational Analysis and Liechtenstein sections both show limits and constraints, not just upside.
- The Data Commons material includes a concrete treatment of AI sovereignty.
- Supporting material is available without overloading the main page.
- The page works well on mobile and desktop, with semantic headings and accessible interactive controls.

---

## 12. Build Sequence

1. Build the page shell, section system, and navigation.
2. Implement the Hero, Framing, Model, Liechtenstein, and Invitation sections first.
3. Add supporting material surfaces for glossary, references, methodology, and changelog.
4. Add richer diagrams and status treatments after the shell is stable.
