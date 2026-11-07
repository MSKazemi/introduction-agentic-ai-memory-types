# Project roadmap and decision gates

**Governance-first project.** Do not begin mass chapter generation until the initial gates below are met. Scope: scientific/engineering textbook and examples on agentic AI memory, accessible to students, engineers and researchers.

| Phase | Deliverable | Exit criteria |
| --- | --- | --- |
| 0 — Charter and safety | Shared project charter, public/private boundaries, editorial standards, issue backlog, role assignments | Owner accepts scope, publication policy, source workflow and dual-git dry-run |
| 1 — Discovery protocol | Search questions, source register, inclusion criteria, paper review template, technology inventory schema | Search and selection log can be independently followed; sources prioritized without cherry-picking |
| 2 — Knowledge map | Definitions, competing taxonomies, evidence map, annotated outline, terminology | Reviewers can trace each major concept to evidence or an explicit hypothesis |
| 3 — Publishing infrastructure | Book source, citations, link checks, reproducible preview, visual library | Public build succeeds on a clean environment with no private assets |
| 4 — Foundational modules | Intro chapters, simple examples, concept diagrams, quizzes | Scientific and beginner reader checks pass |
| 5 — Engineering modules | Versioned framework comparisons, runnable labs, design patterns | Tests and instructions pass with pinned configurations |
| 6 — Evaluation modules | Metrics, benchmarks, baselines, negative results, threat model | Experiments independently rerunnable and limitations disclosed |
| 7 — Pilot and release | Technical review, student/engineer pilot, accessibility QA, release notes | All high-risk claims sourced, assets cleared, broken links fixed |
| 8 — Maintenance | Dated technology updates, issue triage, errata, new literature | Scheduled reviews and versioned release history |

## Four operating loops
1. **Research:** identify -> acquire lawfully -> full-text read -> record precise evidence -> compare conflicting sources -> flag gaps.
2. **Editorial:** learning objective -> outline -> draft -> evidence check -> plain-language review -> visual and accessibility pass.
3. **Engineering:** design -> minimal working example -> test -> reproduce -> document limitations -> publish.
4. **Release:** private classification -> inspect files/diffs/history -> public export -> run checks -> human approval -> release.

## Management rules
* Private issues are the planning source of truth; public issues accept reproducible bugs, errata and learner requests.
* One issue per deliverable with scope, owner, acceptance criteria, evidence, dependencies and public/private classification.
* Claude Code may generate drafts, tests and diagrams; human owner approves scientific claims, legal/license decisions and publication.
* Never infer that two remotes can receive identical commits: **identical commit messages** are preferred, but the private superset and public subset will have different hashes and often different trees.
* No automatic promotion of private material or private-issued credentials into the public history.
* Each substantive change gets a research and release review. Mark unverified, experimental and outdated content.
