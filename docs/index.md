# Markdown Playground Demo

This preview supports *italic*, **bold**, ***bold+italic***, ~~strikethrough~~, and inline code like `npm run dev`.

## Headers

### H3 Section
#### H4 Section
##### H5 Section

## Lists

- Unordered list item
- Another item with **strong** text

1. Ordered step one
2. Ordered step two

## Image

![Sample chart](/static/home/users-graph.png)

## Code blocks

```python
def greet(name: str) -> str:
    return f"Hello, {name}"
```

```javascript
const users = [{ name: "Alice" }, { name: "Bob" }];
console.log(users.map((u) => u.name).join(", "));
```

```bash
curl -s https://www.devtoolsdaily.com/sitemap.xml | head -n 5
```

## Table

| Feature | Status | Notes |
| --- | :---: | --- |
| GFM Tables | Yes | Uses `remark-gfm` |
| Syntax Highlighting | Yes | Multiple languages |
| Inline Code | Yes | Styled with monospace |
