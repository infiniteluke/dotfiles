# Git Commit Style

## Format
<type>(<scope>): <subject>
<body> (Uses the imperative, present tense: “change” not “changed” nor “changes”. Includes why?)
<footer> (Closes: #123, or BREAKING CHANGE notes)

## Types:
feat (new feature for the user, not a new feature for build script)
fix (bug fix for the user, not a fix to a build script)
docs (changes to the documentation)
style (formatting, missing semi colons, etc; no production code change)
refactor (refactoring production code, eg. renaming a variable)
test (adding missing tests, refactoring tests; no production code change)
chore (updating script etc; no production code change)

## Source
Thanks to http://karma-runner.github.io/1.0/dev/git-commit-msg.html
