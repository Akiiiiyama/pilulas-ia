# Meaghan Choi: Designing Claude Code (and what's coming next)

*[Leia em português](pt.md)*

> Claude Code's design lead opens up her kitchen: how she goes from idea to prototype, validates with stakeholders through shareable artifacts and takes the result all the way to a PR.

| | |
|---|---|
| **Who** | Meaghan Choi, Design Lead for Claude Code at Anthropic |
| **Where** | Dive Club podcast, with Michael Riddering (Ridd) |
| **Link** | https://www.youtube.com/watch?v=jEEbjiC4JE0 |
| **Length** | ~54 min |
| **Watched on** | 2026-10-26 |
| **Topics** | design process · prototyping · artifacts · design engineering · the designer's role |

## Summary

- The designer's work hasn't shrunk, it has **moved up**: execution goes to the model, thinking about the product's shape and mental model stays with the person.
- **Artifacts** became the way to prototype, share and record decisions. They started as a workaround: people asked Claude for HTML and sent it to each other.
- Her flow goes from a team's request to an **artifact**, from the artifact to the **real components**, and from there to a **PR**, skipping the traditional transfer from design to engineering.
- More than half of the code she ships today comes from **Claude-initiated PRs**.
- The designer's core skill is now **discernment**: knowing when to automate and when to stop and think deeply.

## Insights

### 1. Shape first, screens later

Before talking about the interface, she uses Claude as a product partner: it brings in research and data and maps the workflow. The first question may be whether the product needs a UI at all.

**Why it matters:** the model will execute a bad idea without questioning it. Deciding the product's shape and mental model is still the designer's job, and it's what gives value to everything else.

### 2. A prototype is a live link, not a static file

Instead of sending a file nobody opens, she shares an artifact: an interactive, versioned link the stakeholder uses as if it were the product. Ridd compares it to sending Figma files to executives, who rarely open them.

**Why it matters:** fast validation depends on lowering the effort for the reviewer. A link that works in the browser brings earlier, more concrete feedback.

### 3. From artifact to PR, in one flow

The flow she showed:

1. The team sends a feature request.
2. She asks Claude for an artifact with the proposal.
3. The team iterates on the artifact.
4. At mid-fidelity, Claude rebuilds it with the real components and checks it into the repo.
5. It becomes a **pull request**, where the review continues with engineering.

**Why it matters:** the prototype is no longer throwaway. What was validated is the starting point for the code, and the conversation with engineering happens in the PR.

### 4. The artifact is also a decision log

She asks for 3 or 4 variants, adds a summary of research and data, and links related artifacts. She describes it as "almost like a mini microsite and decision log".

**Why it matters:** anyone can trace *why* a decision was made, not just *what* was decided. It replaces documentation that usually gets lost.

### 5. Delegate tactical execution, with saved preferences

UI polish, code cleanup and opening PRs go to the model. Her preferences are saved: draft PRs, before-and-after screenshots, CI checks. Claude follows Slack discussions and merged work, proposes changes and reports back when they merge. She is also building an automated reviewer that checks design principles.

**Why it matters:** what's repetitive becomes configuration. The time saved goes to ambiguous problems, like explaining an organization-wide Claude while respecting security boundaries.

### 6. Respect engineering's work

She sometimes stacks refinement PRs on top of an engineer's PR instead of rewriting it, so the original work is preserved.

**Why it matters:** a designer who ships code earns the team's trust by contributing without overriding anyone's work.

### 7. Know when craft matters

Experimental work doesn't need polish. Craft matters most once the product's shape is settled. And quality belongs to the whole team: make it easier for engineers and PMs to identify quality issues, and raise the bar together.

**Why it matters:** polishing too early wastes time on something that will still change.

### 8. Fixed and adaptive interfaces

Login, billing and settings still need to be stable. Other parts can adapt to the user. The designer decides what stays fixed and what changes.

### 9. The right tool for each moment

She still uses Figma, with auto layout, when iterating there is faster than in code. The choice is about speed, not dogma.

### 10. The designer who will thrive

Ridd asked what profile of designer will succeed in the future. The first skill she named wasn't technical: it was **being open and curious**.

In practice:

- **Have ideas and develop them, but let go when you need to.** If it doesn't work, or a better way shows up, change course.
- **Keep updating everything:** how you think, your role and the product.
- **Lean into ambiguity.** Figure out what you want, find a place to start and keep moving, even when it feels chaotic.

She adds two more skills: discernment about what to build and end-to-end ownership. And she reminds us it's still early, so the people working now get to shape what comes next.

**Why it matters:** with AI, tools and ways of working change every few months. Waiting for things to settle before you start means falling behind.

## What I'll apply

- [ ] On the next feature request, send an artifact prototype (interactive link) instead of screenshots or a static file.
- [ ] Generate 3 variants of the solution with a short rationale, and use it as the decision record.
- [ ] Once the prototype is validated, bring it into the repo with the real components and open a draft PR with before-and-after screenshots.
- [ ] Save my PR preferences (draft, screenshots, checklist) in a `CLAUDE.md` so I don't repeat them.
- [ ] Before opening any tool, write the product's shape and mental model in a few lines.

## Moments to revisit

| Time | Topic |
|---|---|
| 01:35 | Joining Anthropic and early Claude Code days |
| 03:14 | Designing for the command line (CLI) |
| 07:45 | The "magic moment" and personality in the tool |
| 10:19 | Artifacts: prototyping, sharing and decision log |
| 19:38 | Claude Tag: a Claude shared across the organization |
| 27:56 | Claude-initiated PRs |
| 31:53 | Offloading execution vs. high-level design thinking |
| 38:48 | Letting go of craft |
| 42:48 | Fixed vs. adaptive interfaces |
| 46:53 | New challenges and the designer's role |
