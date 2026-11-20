# Repository strategy

Established November 19, 2026.

## Ownership

[AyotteIndustries](https://github.com/AyotteIndustries) is the authoritative development organization. Maintain one repository per independent application, including `atlas`, `aides`, `ufsl` and `printpulse3d`. Existing client and business websites keep their original repositories and history.

[MichaelEAyotte](https://github.com/MichaelEAyotte) is the professional engineering portfolio. The profile and A.T.L.A.S. demonstration remain active. Archived showcases preserve useful evidence without becoming parallel application roadmaps.

The private website demonstration remains an explicit exception because an existing Azure deployment and business-site link depend on it. Review its deployment ownership before considering a separately approved transfer or retirement.

## Delivery sequence

**Development → Testing → Validation → Approval → Production → Portfolio Documentation**

1. **Development:** use a short-lived branch or isolated checkout in the authoritative repository. Define a bounded outcome and acceptance criteria.
2. **Testing:** run meaningful checks with synthetic fixtures and isolated dependencies. Keep development/testing separate from production.
3. **Validation:** inspect behavior, relevant integrations, security boundaries and documentation. Record evidence, known limits, exact revision and rollback steps.
4. **Approval:** obtain owner approval for the specific production release. Check workflow triggers before opening a pull request; some existing pull-request workflows deploy previews.
5. **Production:** release only the approved, tested revision through the existing application-specific process. Verify the result and preserve rollback information.
6. **Portfolio documentation:** update the original repository first; publish only sanitized, verified descriptions or bounded examples after checking rights and confidentiality.

This is a documented operating policy. It does not claim that new branch rules, required reviews or deployment-environment enforcement have been installed. Existing deployment settings remain unchanged.

## Documentation and maintenance

- Keep architecture, local setup, tests, implementation status and release notes with their application.
- Distinguish planned, experimental, development and production behavior.
- Keep secrets, customer data and internal infrastructure details out of public material.
- Preserve prior licensing permissions and third-party attribution.
- Retain archived public URLs where websites use them as case studies; archiving is not deletion or a privacy change.
- Do not add showcase repositories or duplicate application code. Create a new repository only for a genuine independent development requirement.
- Keep A.T.L.A.S. IT-support responsibilities separate from AIDES software-engineering responsibilities.
- Before importing existing A.T.L.A.S. or related service-desk material, establish source ownership, provenance and the safe migration boundary. Documentation-only repositories are not completed implementations.

## Historical records

Earlier review notes and commits record the October–November 2026 publication work. Their test results, licensing decisions and approved scope remain historical evidence. This policy supersedes their pin selection and ongoing repository-maintenance recommendations.
