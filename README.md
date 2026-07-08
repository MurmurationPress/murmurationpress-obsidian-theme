# MurmurationPress Obsidian Theme

Quiet tools for complex stories.

This is an early test theme for the Murmuration Press / PRIME writing ecosystem.

## Includes

- Warm paper-like light mode
- Soft charcoal dark mode
- Greenshank-inspired teal accent
- Custom callout styling for:
  - `prime-log` / `prime`
  - `janus-log` / `janus`
  - `divergent` / `skip`
  - `constraint`
  - `state`
  - `annotation` / `annotate`
- Table styling suitable for JANUS triples
- Initial CSS hooks for the Murmuration Writing Companion panel

## Local install for testing

Copy the repository folder into your vault here:

```text
.obsidian/themes/MurmurationPress/
```

The folder should contain:

```text
manifest.json
theme.css
README.md
```

Then open Obsidian:

```text
Settings → Appearance → Themes → MurmurationPress
```

## Callout tests

```markdown
> [!prime-log] PRIME LOG
> Observation recorded.
> Constraint identified.
> Action minimized.
```

```markdown
> [!janus-log] JANUS ASSESSMENT
> | indicator | observed_state | operational_reading |
> |---|---|---|
> | Exposure | increasing | intervention likely |
```

```markdown
> [!divergent] SKIP
> I do not think that means what they think it means.
```

```markdown
> [!state] State
> POV: Tobias · Story date: 2029-01-20 · Status: Draft
```

```markdown
> [!annotation] Annotation
> Human note: Tobias knows more than he is saying here.
```

## Note

This replaces the visual role of Callout Manager for these callouts, but it does not migrate any Callout Manager settings automatically.

## Version 0.1.2

Aligns `annotation` / `annotate` with `state`: soft, human-readable manuscript notes rather than editorial/review tooling.

## Version 0.1.1

Adds `state` as a soft top-of-chapter highlight and `annotation` / `annotate`.
