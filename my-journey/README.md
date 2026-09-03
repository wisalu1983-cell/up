# My Journey — Kala's Plans & Progress

This folder is **not part of the upstream `byoungd/up` project**. It's a personal
add-on inside my fork, used to track my own learning plans, progress logs,
diagnostic results, and reference materials while following the guide.

- Upstream (original guide, read-only for me): `byoungd/up`
- My fork (where this folder lives): `wisalu1983-cell/up`

## Folder layout

```
my-journey/
├── README.md              # this file
├── gdc-2027-plan.md       # main goal + phased plan for GDC 2027
├── diagnostics/           # dated copies of english-diagnostic.md, filled in
├── weekly-reviews/        # dated copies of weekly-review.md, filled in
└── resources/             # reference materials used for learning
    └── talks/              # conference talks and related source files
        └── gdc-2024-ai-workflows/
            ├── README.md
            ├── media/      # audio and video
            └── transcript/ # readable transcript and subtitle files
```

## Sync workflow (fork + stay updated with upstream)

This repo has two remotes:

| Remote     | URL                                  | Purpose                          |
| ---------- | ------------------------------------- | --------------------------------- |
| `origin`   | https://github.com/wisalu1983-cell/up | My fork — push my plans here      |
| `upstream` | https://github.com/byoungd/up         | Original guide — pull updates from here |

**Push my own progress (to my fork):**

```bash
git add my-journey/
git commit -m "update: <what changed>"
git push origin master
```

**Pull the latest guide updates from the original author:**

```bash
git fetch upstream
git merge upstream/master
# resolve conflicts if any (rare, since my-journey/ is untouched upstream)
git push origin master   # keep my fork updated too
```

Since all my personal content lives only in `my-journey/` (a path the upstream
repo doesn't touch), merging upstream updates should almost never conflict.

## Optional: contribute back

If something in `my-journey/` turns into a generally useful improvement to the
guide itself (not just personal notes), open a PR from my fork back to
`byoungd/up` the normal GitHub way.
