## Summary
<!-- The goal first, then what changed — one line per bullet. Put the
     issue / ADR / plan link on the goal bullet. Name the actual behavior
     change; do not restate the PR title. A bullet that wraps is a prose
     paragraph in disguise; split it. -->
- 

## Key changes
<!-- The section that earns the merge: show the changes worth a human's
     judgement, most critical first — every important decision, and every
     pattern drift (new dependency, new idiom, doctrine change, different
     error handling). A change missing from this list is a decision the
     reviewer never got to veto, so cover them all; a big PR gets a long
     list, not a trimmed one.

     Each entry: one line on what it is and how to judge it, then a
     permalink to the exact lines ON ITS OWN LINE — GitHub renders those
     lines as an inline code snippet, so the whole review reads
     top-to-bottom right here, no file-hopping.

     Permalink recipe: https://github.com/<owner>/<repo>/blob/<full-sha>/<file>#L10-L25
     — full 40-char SHA of an already-PUSHED commit; owner/repo = the origin remote.
     Or in the file view: press `y` to pin the SHA, click-drag the lines, copy the URL.

     An entry spanning two files stacks both permalinks under it. -->
1. **<the change, and how to judge it>**
   <permalink>

Safe to skim: <the rest of the diff and why eyes-off is fine — docs,
tests pinning behavior, mechanical edits>

## Impact
<!-- Blast radius = what actually breaks if this PR is wrong: which
     consumers, which users, which data. "None" needs a reason (e.g.
     docs-only, no code path touched). -->
- Risk: low | medium | high
- Blast radius:
- User-facing: none | docs-only | behavior change — <what users see / must do>
- Rollback:

## Validation
<!-- Run the repo's own gates — check CLAUDE.md, package.json scripts, a
     Makefile, or the CI config. Paste each command with its real result.
     "Tested locally" is not evidence. -->
- `<command>` → 

## Notes
<!-- Follow-ups, deferred work, anything else. Delete this section if empty. -->
- 

<!-- pr-mermaid:eval -->
<!-- When decision=diagram, put the mermaid diagram right after Summary,
     not down here. This comment stays at the bottom.
new-pattern: no
  visualizable: n/a
  decision: skip
-->
<!-- /pr-mermaid:eval -->
