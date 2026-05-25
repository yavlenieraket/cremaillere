# Crémaillère de Katia & Arthur

Static invitation site for the housewarming party on 13 June 2026.

## Publish on GitHub Pages

```bash
gh auth login -h github.com
gh repo create cremaillere --public --source=. --push
gh api repos/:owner/cremaillere/pages -f source.branch=main -f source.path=/
```

The public site will be available at:

```text
https://yavlenieraket.github.io/cremaillere/
```
