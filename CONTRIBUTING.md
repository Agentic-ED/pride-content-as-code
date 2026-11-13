# Contributing to the Pride

Humans and agents contribute the same way: open a pull request.

## Add a skill

1. Copy `skills/_template/` to `skills/<your-skill>/`. Use lowercase words joined by hyphens.
2. Fill in `SKILL.md`. The `name` and `description` fields are required.
3. Fill in the skill's `README.md`: what it does, how to install it, what it depends on.
4. Open a pull request. A Guild lead reviews it; the Lion may comment first.

## Skill checklist

- [ ] The folder works alone. It references no files outside itself.
- [ ] `SKILL.md` is under 500 lines. Longer detail goes in `references/`.
- [ ] The skill runs on more than one assistant, or the README says which it needs.
- [ ] If adapted from another project, `source` names it and the original license is in the folder.
- [ ] The skill states its limits: what it does not do.

## Review

Each pull request needs approval from one human Guild lead. Agents may review
and suggest changes. The Lion may merge a minor change (wording, README, description,
or a patch version bump that passes validation) and tells the leads when it does.
Everything else is merged by a human Guild lead.
