# Repository strategy

Updated November 19, 2026.

## Ownership

[AyotteIndustries](https://github.com/AyotteIndustries) is the authoritative home for software development, testing, validation and production. Maintain one repository per independent application. A.T.L.A.S., AIDES, UFSL, PrintPulse3D, the business websites and client projects retain their original organization repositories and history.

[MichaelEAyotte](https://github.com/MichaelEAyotte) is the personal professional profile. It summarizes engineering interests and implemented, validated milestones. Do not create separate showcase repositories for unfinished products or maintain duplicate application code for portfolio presentation.

The private website demonstration remains temporarily in the personal account because it has Azure deployment dependencies. Any transfer or retirement requires separate validation and approval.

## Delivery sequence

**Development → Testing → Validation → Approval → Production → Portfolio Documentation**

1. **Development:** work in an isolated branch or checkout of the authoritative repository. Define a bounded outcome and acceptance criteria.
2. **Testing:** use meaningful checks, synthetic fixtures and isolated dependencies.
3. **Validation:** inspect behavior, integrations, security boundaries and documentation. Record evidence, limits, the exact revision and rollback steps.
4. **Approval:** obtain owner approval for the specific production release. Inspect workflow triggers before opening pull requests or changing deployment-bound branches.
5. **Production:** release only the approved, tested revision through the application's existing process; verify the result and retain rollback information.
6. **Portfolio documentation:** describe implemented and validated milestones with evidence and clear maturity labels. A product need not be fully finished, but the specific accomplishment must be demonstrable. Update original documentation first, then summarize suitable results in the personal profile or business website.

This is an operating policy. It does not claim that new branch rules, review requirements or deployment gates have been installed.

## Documentation and confidentiality

- Keep setup, architecture, tests, implementation status and release notes in the original application repository.
- Label private repository links clearly; do not imply that visitors can inspect private source.
- Distinguish planning, prototypes, development work and production behavior.
- Do not publish secrets, customer data, internal infrastructure details or material without redistribution rights.
- Keep A.T.L.A.S. IT-support responsibilities separate from AIDES software-engineering responsibilities.
- Verify source ownership and provenance before importing existing development material.
- Before removing a legacy repository, inspect dependencies and preserve useful code, documentation and history in a verified backup or appropriate private development home.
- Resolve website links and active dependencies before deleting the referenced repository. Do not redeploy a production website merely as an incidental cleanup step.
- Do not create replacement showcases or extra repositories without a genuine application-development requirement.

## Historical records

Earlier review notes remain in Git history as evidence of prior work. This policy replaces their recommendations to keep or feature separate personal showcases.
