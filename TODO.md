# TODO 

We are looking for someone to help us to fix GitHub Actions.
We currently have NextJS project that few GitHub Actions

```
/.github
    /issue-branch.yml
    /pull_request_template.md
    /workflows
        /create-branch.yml
        /issue-autolink.yml
        /lint.yml
        /release-please.yml (on main)
```

Lint has 4 steps: ESlint, TypeScript, Prettier, and Test.


Issues:

1. release-please.yml not bumping versions

2. when ticket open the create branch dont work

3. CHANGES.md and version.txt not updated



# Semantic Commit Messages

See how a minor change to your commit message style can make you a better programmer.

Format: `<type>(<scope>): <subject>`

`<scope>` is optional

## Example

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

More Examples:

- `feat`: (new feature for the user, not a new feature for build script)
- `fix`: (bug fix for the user, not a fix to a build script)
- `docs`: (changes to the documentation)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `refactor`: (refactoring production code, eg. renaming a variable)
- `test`: (adding missing tests, refactoring tests; no production code change)
- `chore`: (updating grunt tasks etc; no production code change)

References:

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
- https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
