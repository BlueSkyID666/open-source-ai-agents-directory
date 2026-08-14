# Contributing

Thanks for helping keep this directory useful. It's only valuable if the entries are real, current, and actually open source.

## Adding a project

Check it isn't already listed first (search the page, or Ctrl/Cmd+F the README). Confirm the repo is public, open-source with a real license, and reasonably active — no dead links, no vaporware.

Then add one row to the right category table in README.md, in this shape:

```
| Project Name | One clear sentence describing what it does. | [org/repo](https://github.com/org/repo) |
```

And add the matching entry to the DATA array in index.html:

```
{cat:"Category Name", name:"Project Name", repo:"org/repo", desc:"One clear sentence.", url:"https://github.com/org/repo"},
```

Then open a pull request. If your project doesn't fit an existing category, propose a new one and add it to the Table of Contents in both files.

## Reporting a broken link or stale entry

Open an issue with the project name and what changed (renamed, archived, gone private, etc.), or just fix it yourself in a PR — either is welcome.

## Style notes

Keep descriptions to one sentence, factual, no marketing language. Link directly to the GitHub repo, not a landing page, where possible. Curated lists ("awesome-X" repos) are welcome under Awesome Lists (Meta), but prefer linking directly to individual projects when you can.
