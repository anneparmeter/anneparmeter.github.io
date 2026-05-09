---
layout: narrow
---

# Markdown Cheat Sheet

Thanks for visiting [The Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax/) and [extended syntax](https://www.markdownguide.org/extended-syntax/).

## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

### Headings

```
# H1
## H2
### H3
```

# H1
## H2
### H3

---

### Bold

```
**bold text**
```

This is some **inline bold** text

---

### Italic

```
*italicized text*
```

This is some *inline italicized* text

---

### Ordered List

```
1. First item
2. Second item
3. Third item
```

1. First item
2. Second item
3. Third item

---

### Unordered List

```
- First item
- Second item
- Third item
```

- First item
- Second item
- Third item

---

### Footnote

```
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
```

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

---

### Horizontal Rule

```
---
```

The dividers between each section of this document are in-fact horizontal rules, so you can see what they look like and how the help lay things out. For example, that one right there 👇🏻

---

### Link

```
[Markdown Guide](https://www.markdownguide.org)
```

[Markdown Guide](https://www.markdownguide.org)

---

### Image

```
![alt text](https://www.markdownguide.org/assets/images/tux.png)
```

![alt text](https://www.markdownguide.org/assets/images/tux.png)

---

### Table

```
| Syntax | Description |
| --- | --- |
| Header | Title |
| Paragraph | Text |
```

| Syntax | Description |
| --- | --- |
| Header | Title |
| Paragraph | Text |

---

### Code

```
`code`
```

This is some `inline code` right here

---

### Fenced Code Block

Wrap code blocks in ``` (<- that is 3 back ticks) and you can have multi-line code.

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
