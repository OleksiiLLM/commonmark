# 6. Inlines: Links, Images, and Autolinks

## Links
- **Inline Links**: `[link text](/uri "title")`
- **Reference Links**: `[link text][label]` (requires a link reference definition)

### Example
```markdown
[Inline link](https://example.com)
[Reference link][ref]

[ref]: https://example.com
```

## Images
Images use the same syntax as links, but are prefixed with an exclamation mark `!`.
```markdown
![Alt text](/path/to/image.jpg "Optional Title")
```

## Autolinks
Absolute URIs and email addresses surrounded by `<` and `>`.
```markdown
<https://example.com>
```
