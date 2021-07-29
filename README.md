# Snyk pre-commit hook

### Requirements to run:

1. Have Snyk CLI installed (will return an error if Snyk is not installed)
2. Have Snyk CLI authenticated (if not authenticated, then pre-commit hook will warn the user)
3. Have pre-commit script in their .git/hooks directory as pre-commit
4. Make the pre-commit file executable