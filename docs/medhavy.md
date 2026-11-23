# Medhavy

[Medhavy](https://www.medhavy.com/) is an interactive textbook platform, with a [Learning Hub](https://hub.medhavy.com/) and individual textbook editions. The platform has textbook sites and code for learner access, class invitations and textbook assignments, search, and tutoring. Assigning an existing book to a class is different from building a new course from it. Public project pages describe the broader vision; they are not a verification receipt for a specific workflow.

| Capability | Status |
|---|---|
| Textbook platform and Learning Hub | Existing product and code; this project did not verify signed-in use or all textbook features |
| Medhavy MCP for educator access to a rights-aware catalog and source-grounded text | Design in progress; no deployed endpoint or end-to-end test verified |
| Creating and revising an instructor-owned course from a book via the MCP | Proposed; not verified in a working Medhavy workflow |
| AI readiness review of an existing course | [AI Readiness / ARC](https://github.com/nikbearbrown/ai-readiness) is a separate working skill and CLI; its local checks and packaging are not a deployed Medhavy integration |
| Turning an authorized book into a new IMSCC course and importing it | Proposed integration; structural and sandbox import checks are distinct milestones |

**Medhavy** should supply authorized, versioned course material and an instructor workspace. **AI Readiness** should vet the teaching design and give instructors concrete changes they can accept or reject. **IMS Common Cartridge** is the delivery format for a course the instructor can import into an LMS. Keep the original textbook unchanged throughout.

The first pilot is complete only when an instructor can choose a versioned book, adapt two modules using natural language, review every change, and import the resulting cartridge into a blank unpublished course. A README or manifest cannot substitute for that import test.
