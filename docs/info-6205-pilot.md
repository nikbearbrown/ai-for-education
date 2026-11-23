# First pilot: INFO 6205 Algorithms and Data Structures

**Local smoke test, November 23, 2026.** No Canvas import, Medhavy MCP connection, or faculty approval took place. The artifact is not a release.

- **Pinned textbook:** [INFO 6205 Algorithms and Data Structures by Nik Bear Brown and Nimish Magre](https://github.com/nikbearbrown/Coursera_INFO_6205_Algorithms/tree/af3a760cf9003d1908f61596d07788f9b3cc6d91/INFO_6205_Algorithms_and_Data_Structures_Book).
- **Scope:** the standalone Markdown manuscript only. The same directory’s README and manuscript are byte-for-byte identical at this revision, so only one was ingested. The multi-format book, labs, quizzes, notebooks and other course assets were not included. A [license file](https://github.com/nikbearbrown/Coursera_INFO_6205_Algorithms/blob/af3a760cf9003d1908f61596d07788f9b3cc6d91/INFO_6205_Algorithms_and_Data_Structures_Book/LICENSE) states MIT; review the provenance of any third-party figures, examples and bundled assets separately before distributing a course.
- **Tool:** [AI Readiness / ARC at 2c0c51e](https://github.com/nikbearbrown/ai-readiness/tree/2c0c51ef090230aacaf0d45e0b2a141c39e125b6). All 27 unit tests passed. On this source, ARC created one module and one page. Its six-question preflight reported R1 and R5 not supplied, and R2, R3, R4 and R6 missing from the selected material. These are screening signals for this narrow input, not verdicts on the taught course.
- **Package:** ARC validated and packed the local baseline with zero failures and zero warnings from its structural checks. The archive contains a root manifest, the page, and Canvas module metadata. This did not test how Canvas renders math, handles links, or imports the package. No cartridge is distributed in this repository.

## Turn the check into a course improvement

The manuscript has a natural seam at its graph traversal sections. Split them into a module on reachability and a module on shortest paths, rather than shipping a single long page. For the first exercise, have learners trace a search themselves, then ask an AI tool for a second trace on the same small graph. Ask learners to check the trace against the graph and its edge rules, find a planted mistake, and document which claim they accepted or rejected and why. Assess whether students can justify the traversal and transfer the reasoning to a different graph without the tool. This is a proposed course exercise; it is not present in the pilot package.

Next: confirm the two-module goals and bundling rights, produce a reviewed draft with stable source anchors, and test the resulting cartridge in an empty unpublished Canvas course.
