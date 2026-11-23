# From a textbook to an editable course

This is the proposed instructor workflow, not a claim that course construction or IMSCC export is already available in Medhavy.

1. **Choose a book.** Select one canonical edition, with its Git commit or release, intended learner level, and reuse terms. The catalog distinguishes public reading from permission to adapt and distribute.
2. **Run the education readiness check.** Verify source structure, pedagogical coverage, citations, rights, accessibility, and how reliably an agent can retrieve and cite the material. Record evidence and scope at that revision. A book can be excellent and still need preparation for course generation.
3. **Start a course draft through Medhavy MCP.** Ask for a semester length, audience, prerequisites, learning outcomes, policies, and assessment preferences. Pick and reorder chapters and draft modules, assignments and rubrics in a separate instructor workspace. Keep each draft tied to source sections and identify generated or modified material. Use plain-language prompts to edit the draft; never edit the canonical textbook as a side effect.
4. **Review before exporting.** Show a course map and changes for the instructor to accept. Check factual accuracy, outcomes and assessment alignment, accessibility, allocation of time, and which material can legally be copied. Restrict answer keys to instructor-facing review. Never package student data, authentication material, or private resource links.
5. **Export and import.** Make a downloadable IMS Common Cartridge (.imscc) for the chosen LMS profile. The instructor imports it into an unpublished Canvas sandbox, verifies module sequence, pages, assets and any supported assessments, then decides whether to publish. No automatic changes to a live class.

## Smallest useful pilot

One authorized, source-pinned book. Two modules. Each has an explicit learning outcome, reading, accessible HTML page and activity. Export pages, module structure and permitted assets first. Assessments, question banks, LTI integrations, due dates and other native LMS objects are separate compatibility checks, not promises.

Use the matching [1EdTech Common Cartridge specification](https://www.1edtech.org/standards/cc). Validate the root manifest, resources, links and references before attempting import. Record the profile/version, artifact digest, expected object counts and actual outcomes from an unpublished sandbox. A valid package is not evidence of a successful Canvas import. Record unsupported items rather than silently omitting them.

## MCP design boundary

Proposed capabilities, not live tool names: list authorized books; read source-grounded text and readiness evidence; create and revise an instructor-owned draft; preview changes; validate an approved draft; and prepare an instructor-scoped download. Authorization belongs to the service, not to prompts. The first version should keep private books, draft keys, and export links inaccessible to unauthenticated users, separate instructors’ drafts, and neither publish to Canvas nor require Canvas credentials to produce a file.

## What ARC already supports

The [ARC tool](https://github.com/nikbearbrown/ai-readiness) can inspect folders and Canvas exports and build accepted edits into a separate copy of an existing export. For the first integration, use a versioned empty or synthetic Canvas template where appropriate, retain its original and its manifest, and test only the supported changes. ARC can also turn a folder into a simple local package, as the [INFO 6205 smoke test](info-6205-pilot.md) illustrates. This is scaffolding, not the integrated textbook-to-course product. Keep the original .imscc file, temporary work folders, and any identifying records out of the project repository.
