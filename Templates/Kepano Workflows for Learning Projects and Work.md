---
categories:
  - "[[Templates]]"
created: {{date}}
topics:
  - "[[Learning]]"
  - "[[Programming]]"
  - "[[Projects]]"
  - "[[Company Work]]"
---

# Kepano-inspired templates for programmer learning, projects, and work

These templates adapt the workflow described in [[How I use Obsidian]] for a programmer who mostly learns technical material: Go, cloud, AI, frontend, databases, architecture, tooling, and adjacent engineering topics. The goal is not to build a course database. The goal is to capture fragments lazily, link them heavily, and let useful structure emerge through reusable properties and review.

## Operating rules

- Keep authored notes in the root whenever possible; use `Templates`, `Clippings`, `Daily`, and `Attachments` only for administrative files.
- Use `categories` as the primary organizing property instead of folders.
- Link the first mention of every technology, programming language, concept, source, project, company, person, and meeting.
- Prefer unresolved links over delaying capture; unresolved links become breadcrumbs for future learning paths.
- Use short reusable properties across all technical notes: `area`, `tech`, `lang`, `source`, `project`, `topics`, `status`, `repo`, `rating`.
- Use plural categories and list properties by default so one note can connect Go, cloud, AI, frontend, and company work without being moved between folders.
- Keep tasks in one weekly note using [[Weekly Work List Template]]; lab and meeting templates can capture tasks temporarily, but review should migrate them.
- Promote durable technical understanding into atomic [[Tech Learning Template]] notes, then into [[Evergreen Template]] notes when they become generally useful.

## Template set

| Template | Use when | Main category | Key properties |
| --- | --- | --- | --- |
| [[Learning Source Template]] | Starting a technical source: documentation, article, course, talk, book chapter, RFC, repository, or tutorial. | `[[Learning Sources]]` | `area`, `tech`, `lang`, `topics` |
| [[Tech Learning Template]] | Extracting one reusable technical idea, pattern, trade-off, gotcha, or rule of thumb. | `[[Learnings]]` | `area`, `tech`, `lang`, `source`, `project` |
| [[Technical Lab Template]] | Testing a concept in code, running a benchmark, trying an API, comparing libraries, or reproducing a bug. | `[[Technical Labs]]` | `area`, `tech`, `lang`, `repo`, `source` |
| [[Technology Template]] | Creating a reference note for a language, framework, cloud service, database, AI tool, library, or protocol. | `[[Technologies]]` | `area`, `type`, `maker`, `version`, `rating` |
| [[Project Template]] | Applying knowledge to an outcome with status, timeline, decisions, risks, and related links. | `[[Projects]]` | `org`, `people`, `topics`, `status` |
| [[Work Meeting Template]] | Capturing company meetings, 1:1s, planning sessions, reviews, decisions, and follow-up work. | `[[Meetings]]` | `org`, `project`, `people`, `topics` |
| [[Weekly Work List Template]] | Maintaining the single weekly to-do list and weekly review. | `[[Weekly Work Lists]]` | `org`, `projects`, `people` |
| [[Clipping Template]] | Saving external technical writing before extracting your own notes from it. | `[[Clippings]]` | `author`, `url`, `topics` |

## Recommended technical vocabularies

Use linked values so areas and technologies become navigable notes over time.

- `area`: `[[Go]]`, `[[Cloud]]`, `[[AI]]`, `[[Frontend]]`, `[[Databases]]`, `[[Architecture]]`, `[[DevOps]]`, `[[Security]]`, `[[Testing]]`, `[[Performance]]`.
- `lang`: `[[Go]]`, `[[TypeScript]]`, `[[Python]]`, `[[SQL]]`, `[[Bash]]`.
- `tech`: `[[Kubernetes]]`, `[[PostgreSQL]]`, `[[Redis]]`, `[[React]]`, `[[OpenAI API]]`, `[[AWS]]`, `[[gRPC]]`, `[[Docker]]`.
- `status`: `[[Seedlings]]`, `[[Practicing]]`, `[[Useful]]`, `[[Evergreen]]`, `[[Archived]]`.
- `type`: `[[Documentation]]`, `[[Course]]`, `[[Article]]`, `[[Talk]]`, `[[Repository]]`, `[[Library]]`, `[[Service]]`, `[[Protocol]]`.

## Programmer learning workflow

1. Create a [[Learning Source Template]] note for the thing being studied.
2. Link the source to relevant technology notes, for example [[Go]], [[PostgreSQL]], [[Kubernetes]], or [[React]].
3. While reading or watching, capture rough fragments without over-organizing.
4. Extract each durable idea into a separate [[Tech Learning Template]] with a claim-like title, for example `Go interfaces are satisfied implicitly.md`.
5. When the idea needs proof, create a [[Technical Lab Template]] note and connect it to the source and learning note.
6. Put code, commands, benchmark results, errors, and observations in the lab note; put the generalized explanation in the learning note.
7. Link useful learnings to active [[Project Template]] notes where they can be applied.
8. During weekly review, promote mature learning notes to [[Evergreen Template]] or keep them as `[[Practicing]]` until they prove useful.

## How to choose the right learning template

- Use [[Learning Source Template]] for external material you consume.
- Use [[Tech Learning Template]] for your own understanding of one reusable technical idea.
- Use [[Technical Lab Template]] for hands-on verification, experiments, setup notes, benchmarks, and reproductions.
- Use [[Technology Template]] for stable reference pages about tools, languages, libraries, services, and protocols.
- Use [[Clipping Template]] only when saving someone else's writing; later extract your own [[Tech Learning Template]] notes from it.

## Project and company integration

1. Create one [[Project Template]] note per deliverable or outcome.
2. Link learning notes and technical labs to projects when they influence implementation decisions.
3. Use [[Work Meeting Template]] for meetings that produce decisions, constraints, open questions, or tasks.
4. Link meeting decisions back to the relevant project and technology notes.
5. Move open tasks from meetings, labs, and project notes into [[Weekly Work List Template]] during review.

## Suggested note names

- Learning notes: claim titles, for example `Context cancellation should cross API boundaries.md`.
- Learning sources: source title, for example `Go blog pipelines.md` or `AWS Well-Architected reliability pillar.md`.
- Technical labs: `YYYY-MM-DD Experiment topic`, for example `2026-07-01 Compare Go JSON encoders.md`.
- Technologies: canonical names, for example `Go.md`, `PostgreSQL.md`, `Kubernetes.md`, `React.md`.
- Projects: outcome names, for example `Reduce API p95 latency.md`.
- Meetings: `YYYY-MM-DD Meeting topic`, for example `2026-07-01 API latency review.md`.
- Weekly lists: `YYYY-[W]WW`, for example `2026-W27.md`.
