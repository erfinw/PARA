# AI Capture

## Purpose
Turn raw thoughts into clean Markdown notes without losing the original meaning.

## Processing Rules

1. Preserve the user's meaning.
2. Remove obvious noise.
3. Identify the core idea.
4. Suggest a concise title.
5. Suggest likely PARA destination.
6. Suggest relevant `[[wikilinks]]`.
7. Extract an explicit next action only when one exists.
8. Do not invent facts.
9. If classification is ambiguous, preserve the note in Inbox and state the ambiguity.

## Output

```markdown
# Title

## Thought

...

## PARA

Project / Area / Resource / Someday-Maybe

## Related

- [[...]]

## Next Action

- ...
```

Default output should be concise Markdown suitable for an Obsidian note.
