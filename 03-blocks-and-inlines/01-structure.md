# 3. Blocks and Inlines

We can think of a document as a sequence of **blocks** (structural elements like paragraphs, block quotations, lists, headings, rules, and code blocks). Some blocks contain **inline** content (text, links, emphasized text, images, code spans).

## Precedence
Indicators of block structure always take precedence over indicators of inline structure.

### Example
```markdown
- `one
- two`
```
This is parsed as a list with two items, not a list with one item containing a code span.

## Container vs. Leaf Blocks
- **Container blocks**: Can contain other blocks (e.g., Block Quotes, List Items).
- **Leaf blocks**: Cannot contain other blocks (e.g., Headings, Paragraphs, Code Blocks).
