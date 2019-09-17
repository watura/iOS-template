# Setup
```
mint bootstrap
mint run yonaskolb/xcodegen xcodegen
```

# Semantic Commit Message
## Format
```
<type>(<scope>): <subject>

<body>

<footer>
```

## Types
Type | Definitions
|:---|:----------
chore   | updating grunt tasks etc; no production code change
docs    | changes to the documentation
feat    | new feature for the user, not a new feature for build script
fix     | bug fix for the user, not a fix to a build script
refactor|refactoring production code, eg. renaming a variable
style   | formatting, missing semi colons, etc; no production code change
test    | adding missing tests, refactoring tests; no production code change
