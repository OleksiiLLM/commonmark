# 2. Preliminaries

## Characters and Lines
Any sequence of characters is a valid CommonMark document. A character is a Unicode code point.

## Tabs
Tabs in lines are preserved, but in contexts like indentation, a tab behaves exactly the same as four spaces would.

## Backslash Escapes
Backslashes before ASCII punctuation characters are treated as literal backslashes, preventing them from formatting text.

### Examples
```markdown
\*not emphasized*
\[not a link](/foo)
```

## Entity and Numeric Character References
Valid HTML entity references and numeric character references can be used in place of their corresponding Unicode characters, except within code blocks/spans.
