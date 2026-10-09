# Issue tracker: GitHub

Issues and specs live in GitHub Issues for `SaKaNa-Y/contribution-principles`.
Use the `gh` CLI from this repo.

## Operations

- Create: `gh issue create --title "..." --body-file <file>`
- Read: `gh issue view <number> --json number,title,body,labels,comments`
- List: `gh issue list --state open --json number,title,body,labels`
- Comment: `gh issue comment <number> --body-file <file>`
- Add a label: `gh issue edit <number> --add-label "<label>"`
- Remove a label: `gh issue edit <number> --remove-label "<label>"`
- Close: `gh issue close <number>`

For multiline content, write the text to a file and pass it with `--body-file`.

When a skill says "publish to the issue tracker", create a GitHub issue.
When a skill says "fetch the relevant ticket", read the GitHub issue.

## Pull requests as a triage surface

**PRs as a request surface: no.**
