# Agent Instructions - GitHub profile README

This repo exists for one reason. GitHub renders `README.md` from a public repo
named exactly the owner's username onto `github.com/gorkaperezs`, and that README
is the profile's About section. There is no other way to get one, which is why this
cannot live inside another repo and cannot be private.

**This repo is public and permanent.** Everything committed here is visible to
anyone and cached by search engines. Universal working habits live in
`~/.claude/CLAUDE.md`; this file only adds what a public profile needs.

## Rules

1. **When in doubt about any fact, ask Gorka. Never assume.** A wrong guess here is
   read by recruiters, founders and search engines.
2. **Point at sources, never copy them.** Career facts live in
   `gorka-code/context/job-experience.md`, product facts in each product's own repo. Read
   them, write derived prose, and never commit the source files: they carry
   internal context that must not reach a public repo. Pointing also means this
   page cannot silently drift from the CV.
3. **`gorka-code/context/job-experience.md` owns career framing.** It marks which facts are
   outward-facing and how each must be phrased. Follow it exactly. Where it is
   silent, ask Gorka rather than inventing a phrasing.
4. **No dead links.** Verify every URL resolves before committing, and leave a link
   out rather than ship one that fails.
5. **US English, short plain sentences, no em dashes** (universal rules 7 and 8).

## Structure

`README.md` and this file, nothing else.

No `TODO.md`: per universal rule 12, a repo whose entire content is a single public
artifact keeps its tasks in the tracker of the workspace that owns them, which here
is `gorka-code/TODO.md`.

No image assets either. GitHub hosts profile avatars itself once uploaded through
the browser, and the canonical copy of the photo lives in `gorka-code/assets/`.
