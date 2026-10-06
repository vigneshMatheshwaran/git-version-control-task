# Git Workflow

## Branches

- `main` - Production-ready code
- `dev` - Development integration branch
- `feature/*` - Individual feature development

## Workflow

1. Create a feature branch from `dev`.
2. Make changes and commit them.
3. Push the feature branch to GitHub.
4. Create a Pull Request to `dev`.
5. Review and merge the Pull Request.
6. Test the changes in `dev`.
7. Create a Pull Request from `dev` to `main`.
8. Merge the approved changes into `main`.
9. Create a Git tag for a release.

## Best Practices

- Use meaningful commit messages.
- Keep feature branches focused.
- Review changes through Pull Requests.
- Never commit secrets or unnecessary files.
- Use `.gitignore` for files that should not be tracked.
## Useful Git Commands

### Check Status

```bash
git status
