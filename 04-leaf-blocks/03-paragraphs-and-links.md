# 4. Leaf Blocks: Paragraphs, HTML, and References

## Paragraphs
A sequence of non-blank lines that cannot be interpreted as other block elements.

## HTML Blocks
Groups of lines treated as raw HTML.
```markdown
<table>
  <tr>
    <td>hi</td>
  </tr>
</table>
```

## Link Reference Definitions
Define a label for reference links and images elsewhere in the document.
```markdown
[foo]: /url "title"
```

## Blank Lines
Used to separate block-level elements and determine if a list is tight or loose.
