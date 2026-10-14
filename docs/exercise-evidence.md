# Exercise evidence

Participant: **KokoaSkr1**.

Steps 1, 2, and 3 passed. Step 4 has not been completed. This exercise has not been submitted to MLH as complete.

Original course discussion: https://github.com/KokoaSkr1/hacktoberfest-2026-code-with-codespaces/issues/1

## Privacy-preserving history

On October 14, 2026, personal author/committer email metadata was replaced with the GitHub noreply identity. Exercise file contents, commit messages, author/committer timestamps, and merge structure were retained. Commit IDs changed, and old commit signatures do not carry over. This evidence document is a subsequent documentation commit.

The records below were captured from GitHub Actions before cleanup. They describe actual original checks; they are not claims that workflows were rerun on the replacement commit IDs. The preserved-content commit column identifies an unchanged file tree in the cleaned history. Failed attempts remain documented. Private original exports and the commit mapping are retained locally by the owner.

## Recorded workflow results

| Workflow | Result | Started (UTC) | Preserved-content commit |
|---|---|---|---|
| Step 1 | success | 2026-10-14T17:54:07Z | `9d74a8c327dc2e5467fd76ba5314a3f1c276d8d7` |
| Step 0 | success | 2026-10-14T17:54:07Z | `9d74a8c327dc2e5467fd76ba5314a3f1c276d8d7` |
| Step 1 | success | 2026-10-14T17:57:59Z | `848fa2e3e07651534b17cd5d08c8a84a1d7a4799` |
| Step 2 | success | 2026-10-14T18:01:51Z | `cf7e1a0e32a1182758496539a17c09fce5ed1c66` |
| Step 3 | failure | 2026-10-14T18:12:46Z | `3eefb3d02ce715b86e887b40ffcec70e74d509eb` |
| Step 3 | success | 2026-10-14T18:18:11Z | `b86d5000d82ffc86eeca1f799126998fa66a9895` |

## Work performed

- Created and used an actual two-core GitHub Codespace.
- Ran the starter Python program, changed it to Hello World, and committed the result.
- Built the minimal Debian environment and verified that its development tools were initially absent.
- Added Python 3.10, the Python and Python Debugger extensions, and the post-create script installing the sl animation.
- Rebuilt and verified Python 3.10.22, Hello World output, both extension IDs, and the installed animation.
- Step 3 initially failed because the checker required literal “install sl”; moving the equivalent -y flag after sl fixed it. The successful retry is recorded above.
- Stopped the Codespace to conserve resources. Step 4 remains unfinished. A stopped workspace retaining the old Git history must be aligned to the cleaned remote before any future push.

This work used AI assistance. The record does not represent every action as unaided personal work.
