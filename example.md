# Kuriyota's Markdown CSS

Kuriyota's Markdown CSS is a custom CSS stylesheet for Markdown files that provides a consistent and visually appealing presentation of Markdown content. It is designed to be used with the [Markdown-it](https://github.com/markdown-it/markdown-it) library, which is a popular Markdown parser for JavaScript.

## Usage

#### Using NPM

```bash
npm i @cn_chestnut/markdown-css
```

#### Using CDN

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@cn_chestnut/markdown-css/index.css" />
```

#### How to use

```html
<div class="markdown-body">
  <!-- Your Markdown content goes here -->
</div>
<div class="markdown-body theme-light">
  <!-- Your Markdown content goes here -->
</div>
<div class="markdown-body theme-dark">
  <!-- Your Markdown content goes here -->
</div>
```

You can add `theme-dark` / `theme-light` class to the `markdown-body` element to switch between light and dark themes.

---

## Styles

This is **bold text**, this is _italic text_, this is ~~strikethrough~~, this is `inline code`, this is [link example](https://example.com), this is keyboard input: <kbd>Ctrl+S</kbd>

## Heading Test

# H1 Heading

## H2 Heading

### H3 Heading

#### H4 Heading

##### H5 Heading

###### H6 Heading

## List Test

### Unordered List

- Level 1 item
  - Level 2 nested item
    - Level 3 nested item
- Items with various styles:
  - **Bold item**
  - _Italic item_
  - ~~Strikethrough item~~

### Ordered List

1. First item
2. Second item
   1. Nested ordered item
   2. Another nested item
3. Third item

## Code Block Test

```javascript
function helloWorld() {
  console.log('Hello, World!')
  const num = 123
  return num.toString(16)
}
```

```python
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        yield a
        a, b = b, a + b
```

## Table Test

| Feature | Syntax         | Example     | Status       |
| ------- | -------------- | ----------- | ------------ |
| Bold    | `**text**`     | **Sample**  | Supported ✅ |
| Italic  | `*text*`       | _Sample_    | Supported ✅ |
| Code    | `` `code` ``   | `Code`      | Supported ✅ |
| Link    | `[title](url)` | [Sample](#) | Supported ✅ |

## Multimedia Elements

![Alt text](https://picsum.photos/600/400 'Image title')

<https://example.com> (auto-link test)

## Blockquote Test

> Level 1 blockquote text
>
> > Nested blockquote text
>
> Blockquote containing **bold** and `code`

## Horizontal Rule Test

---

---

## Special Elements

### Task List

- [x] Completed task
- [ ] Incomplete task
  - [ ] Nested task

### Footnote Test

This is text with a footnote[^1], and another footnote[^2]

[^1]: First footnote content
[^2]: Second footnote content (contains **formatting** and `code`)

### Math Formulas

$$
f(x) = \int_{-\infty}^\infty \hat f(\xi)\,e^{2 \pi i \xi x} \,d\xi
$$

Inline formula: $E = mc^2$

### Definition List

Term 1
: Definition content 1

Term 2
: Definition content 2
: Second definition

## Mixed Content Test

1. **List items containing**:
   - Nested unordered list
   - `Code` and ![Small icon](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHElEQVQI12P4//8/w38GIAXDIBKE0DHxgljNBAAO9TXL0Y4OHwAAAABJRU5ErkJggg==)
2. Special content in tables:
   | Column 1 | Column 2 |
   |----------|----------|
   | `Code` | **Bold** |
   | $x^2$ | ![Small icon](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHElEQVQI12P4//8/w38GIAXDIBKE0DHxgljNBAAO9TXL0Y4OHwAAAABJRU5ErkJggg==) |

## Long Text Test

This is very very very very very very very very very very very very very very very very very very very very very very very very very very very very very very long text to test automatic line breaks and line height settings.

This is very very very very very very very very very very very very very very very very very very very very very very very very very very very very very very long text to test automatic line breaks and line height settings.
