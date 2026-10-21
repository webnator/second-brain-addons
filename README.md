# Second Brain Add-ons

A small collection of additions I made while using an Obsidian and Claude Code second brain: two conversational skills and templates for beliefs, milestones, quotes, and unfinished ideas.

This is not my private vault and does not include its notes or history. It is also not the original second-brain template. That template was created by Jesús Copado; its MIT attribution is retained in [LICENSE](LICENSE).

## Included

- `/think`: explore an idea before deciding whether anything needs to become a note.
- `/rant`: talk through a frustration, then choose which useful insights or actions to keep.
- Templates for beliefs, milestones, quotes, and scratchpads.
- Base Atom and Project templates referenced by the skills, retained from the upstream template.

## Use with an existing vault

Requires an existing vault using `Atoms/`, `Projects/`, `Maps/`, `Calendar/`, and `x/Templates/`, plus a configured Claude Code installation.

1. Read both skills before installing them.
2. Copy the desired skill directories into your vault's `.claude/skills/` folder.
3. Copy missing templates into `x/Templates/`. Keep your existing versions if you have customized them.
4. Check that the destination paths match your own vault conventions.
5. Invoke `/think` or `/rant` from the vault. Decide explicitly what, if anything, should be saved.

These are prompts, not a deterministic application. Their behavior depends on the model, permissions, and surrounding instructions. They are intended for personal reflection, not clinical use.

Your vault can contain sensitive information. Choose your model/provider accordingly and keep personal notes out of public repositories. This bundle includes no notes, contacts, credentials, account configuration, or bundled Obsidian plugins.

## Example

Use `/think` with a question such as: “Should this weekend project stay a small tool or become a product?” The skill explores the decision before offering to save a note. No real journal entries are included here.

## Authorship and license

The `think` and `rant` skills and four additional templates were extracted from my changes to the private vault. The underlying vault conventions and base templates come from Jesús Copado's MIT-licensed template. See [LICENSE](LICENSE).
