---
layout: post
title: "The First Post"
date: 2026-06-18
author: "Charbel Daher"
description: "A test post"
tags:
  - testing
---

# Heading Level 1

## Heading Level 2

### Heading Level 3

#### Heading Level 4

##### Heading Level 5

###### Heading Level 6

---

## 1. Text Formatting

This paragraph tests standard text formatting properties. You can easily make text **bold** using double asterisks or __bold__ with double underscores. To emphasize text, use *italics* or _italics_. 

You can also combine them to create ***bold and italicized*** text.

### Extended GFM Formatting
* ~~Strikethrough text~~ uses double tildes.
* ==Highlighted text== (supported by parsers like Obsidian).
* Subscript: H~2~O
* Superscript: X^2^

---

## 2. Lists

### Unordered List
* First item
* Second item
  * Indented sub-item A (requires 2 or 4 spaces)
  * Indented sub-item B
* Third item

### Ordered List
1. First ordered item
2. Second ordered item
   1. Nested ordered item (indented)
   2. Another nested item
3. Third ordered item

### Task Lists (GFM)
- [x] This task is completed
- [ ] This task is incomplete
- [ ] This task is locked/disabled

---

## 3. Blockquotes

> This is a standard single-line blockquote element.
>
> > This is a nested blockquote layer.
> 
> Back to the first level of quoting text.

---

## 4. Code Display

### Inline Code
Use the `printf()` utility or define a variable like `const testing = true` inside a standard text sentence.

### Fenced Code Blocks (With Syntax Highlighting)
```javascript
// JavaScript Test Block
function greetUser(name) {
  console.log(`Hello, ${name}!`);
  return true;
}
greetUser("Markdown Tester");
```

```python
# Python Test Block
def calculate_square(number):
    """Returns the square of a number."""
    return number ** 2

print(calculate_square(4))
```

---

## 5. Rich Links and Media

### Standard Links
* [Markdown Guide Official Website](https://www.markdownguide.org)
* [Anonymous Link with Title](https://www.google.com "Google Homepage")

### Reference-Style Links
You can use [Reference Link A][link-source-1] or [Reference Link B][link-source-2] elsewhere in this document.

[link-source-1]: https://github.com
[link-source-2]: https://bitbucket.org

### Images
![Placeholder Test Image](/assets/images/cat.jpg "Optional Hover Title")

---

## 6. Tables (GFM)

| Feature Name | Syntax Rule | Expected Output | Status |
| :--- | :---: | :---: | ---: |
| Left-aligned | `:---` | Text shifts left | Verified |
| Centered | `:---:` | Text is centered | Verified |
| Right-aligned | `---:` | Text shifts right | Verified |

---

## 7. Miscellaneous & Edge Cases

### Escaping Formatting Characters
If you want literal symbols without formatting, use backslashes: \*This is not italic\* and \# This is not a heading.

### Horizontal Rules
Three different syntax options to generate a divider line:

***

---

___

### Inline HTML Elements
Most processors allow raw HTML rendering. You can use <kbd>Ctrl</kbd> + <kbd>C</kbd> to copy text, or write text in <span style="color:red">explicitly styled red spans</span>.