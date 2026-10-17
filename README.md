# Looki Skills

Agent instructions for working with personal context stored in Looki.

## Install

Install all skills in this repository with the Skills CLI:

```bash
npx skills add looki-ai/looki-skills
```

Alternatively, copy the contents of this repository's `skills/` directory into
an agent's supported skill directory, preserving each skill's directory
structure.

Installing these skills does not install the Looki CLI or authorize access to a
Looki account.

## Structure

```text
skills/
  <skill-name>/
    SKILL.md
    references/
```

Each skill directory contains its instructions and any supporting references it
needs at runtime.
