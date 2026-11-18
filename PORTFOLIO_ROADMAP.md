# brand-assets portfolio roadmap

Baseline reviewed on November 17, 2026. Repository roadmap published on November 18, 2026.

This roadmap applies to this repository and follows the shared Null Catchers portfolio plan. Verify the documented state against the current code and runs before starting work.

**Estimated initial demo effort** 4–8 hours for a developer familiar with the project. The estimate excludes external reviews, store accounts, target environment setup, and later milestones.

## Project priorities

**Documented state** The repository contains SVG and PNG logos, icons, social assets, design tokens, and project-specific assets. The work focuses on documenting the existing identity.

**P0 — Demo** Document the current logo system and validate a reusable asset package.

**P1 — Validation and depth** Create a contact sheet or static gallery with asset names, dimensions, and light and dark variants. Validate JSON, SVG, agreed PNG sizes, links, and text contrast.

**P2 — Later** Generate favicons, app icons, and social previews deterministically from master assets. Regenerate binary assets when their inputs change.

**Acceptance criteria** Each featured project has a consistent icon and social cover, clear usage instructions, and a single source of design tokens.

**Demo scenario** Organization identity board and three project cards using existing assets. [README](https://github.com/The-Null-Catchers/brand-assets/blob/main/README.md), [Brand Tokens](https://github.com/The-Null-Catchers/brand-assets/blob/main/brand-guide/brand-tokens.json).

## Next milestones

Review the [design tokens](brand-guide/brand-tokens.json) alongside the horizontal, stacked, and monochrome logo variants.

1. [ ] Show approved variants on light and dark backgrounds. Document clear space and minimum sizes.
2. [ ] Check that PNG dimensions match their labels, confirm links and contrast, and document usage rights and attribution for assets and fonts before distributing the package.

## Portfolio acceptance checklist

- [ ] Another person can reproduce the primary workflow from a clean checkout using the README and test credentials or fixtures.
- [ ] The demo tells one complete story with a defined user, problem, and saved result.
- [ ] Tests cover the main flow, an important failure, and access boundaries when multiple accounts are involved.
- [ ] Demo data is labeled synthetic and reproducible. Review screenshots and recordings for secrets and customer data.
- [ ] Include four to six real screenshots where appropriate, a 60–120 second recording, and working links. Identify the revision used for capture.
- [ ] The README describes implemented capabilities, setup, architecture, limits, tests, and the demo.
- [ ] A short case study explains two engineering decisions, a considered alternative, and how the system handles an actual failure.
- [ ] Release evidence records the commit SHA, CI, prerequisites, and limits. Performance data includes workload, hardware, and method.
- [ ] Licensing and contributor attribution are settled before distribution. Choose the license for each repository individually.

A hosted demo is optional. Code execution, server administration, and secret management can be demonstrated through a recording and a reproducible isolated environment. Keep public demo access scoped to the activities it needs.

## Implementation and follow-up

- Break P0 into tasks with expected behavior, acceptance criteria, and a suitable test.
- Verify existing functionality first. Update this plan when evidence tied to a commit or PR closes a milestone.
- Record the fixture source, the revision used for evidence, and the tested limits.
- Review the final diff and verify required checks for its exact SHA before merging. Follow branch protection.
- For documentation-only changes with no applicable workflow, verify content and links and record the checks actually performed.
- Tie performance, security, and readiness claims to supporting evidence.
