# Chapter 11 — GitHub Actions

## Meaning
GitHub Actions គឺជា automation tool។

**Example tasks:**
- build
- test
- deploy

## Workflow file
`.github/workflows/main.yml`

## Example
```yaml
name: CI/CD

on: push

jobs:
  build:
    runs-on: ubuntu-latest