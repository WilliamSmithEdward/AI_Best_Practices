# AI Best Practices

A small set of language-agnostic, portable guidance documents for agentic AI
coding assistants and the people working alongside them. Drop any of them into a
repository as-is, or copy the parts you need into an AGENTS.md, CLAUDE.md, or a
style guide. Each document records its sources inline so a reader can audit the
basis for every rule.

## Documents

- [Programming best practices for agentic AI coding](docs/agentic_ai_programming_best_practices.md)

  Twenty-six research-gated practices covering small focused changes, reviewable
  code, deterministic validation, tests as behavior contracts, secure-by-design
  defaults, dependency and supply-chain discipline, grounding claims instead of
  fabricating, treating external content as untrusted input, safe use of powerful
  tools, performance and resource budgets, concurrency safety, resilient error
  handling, data privacy, safe migrations, and threat modeling. It adds nine
  user-mandated design principles, a change
  checklist, a review rubric, a source matrix, and a copy-paste agent-instruction
  template. Each research-gated practice is backed by at least three independent
  sources (three separately operated publishing organizations).

- [AI smells for agents to avoid](docs/ai_smells_for_agents_to_avoid.md)

  A field guide to writing patterns that read as machine-generated: non-ASCII
  punctuation, the "AI style" word cluster, promotional inflation, negative
  parallelism, rule-of-three filler, transition pileups, hedging, vague
  attribution, sycophancy, and low-density genericism. Every entry carries an
  evidence tier (A peer-reviewed, B documented, C convergent). The target is
  clear prose that carries information, not text that fools a detector.

- [Web UI/UX guidelines for agents](docs/ui_ux_guidelines_for_agents.md)

  Web UI/UX heuristics spanning usability foundations, visual hierarchy and
  typography, responsive layout, forms and data entry, data tables, navigation,
  dashboards, feedback and loading states, reduced motion, internationalization,
  and WCAG-aligned accessibility. A heuristic is admitted only when at least three
  independent reputable publishers corroborate it, with the sources listed under
  each entry.

## Using these

These are guidance, not code. Pick the document that fits the task, follow the
repository's own conventions first, and treat this set as a default the project
can override. The practices are written to be enforceable in review: each one
states what good looks like and what to watch for.

## License

Released under the [MIT License](LICENSE).
