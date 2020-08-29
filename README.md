# Jekyll-Markdown-Cheat-Sheet

This cheat sheet provides a quick overview of all the Markdown syntax elements that are supported by Jekyll.

## What is Markdown?

Markdown is a lightweight and easy-to-use markup language for web writers. Markdown allows you to add formatting elements to plaintext documents and then convert them to structurally valid HTML.

Markdown syntax can be divided into two broad categories. These categories are (1) basic syntax outlined in the original design document and (2) extension of basic syntax for added capability and features.

Refer to [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/) for more examples.

## Basic syntax

These elements are defined in the original Markdown design document and can be used in all Markdown applications.

Detailed information and examples can be fount at [basic syntax guide](https://www.markdownguide.org/basic-syntax/).

### Headings

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

### Paragraph

```markdown
Here's a paragraph.
```

### Line break

```markdown
Here's another one  
with a line break.
```

### Bold

```markdown
**bold text**  
__bold also__
```

### Italic

```markdown
*italic text*  
_italic also_
```

### Blockquote

```markdown
> blockquote text
```

### Ordered list

```markdown
1. Item 1
1. Item 2
    1. Item 2a
    1. Item 2b
1. Item 3
```

### Unordered list

```markdown
- Item
- Item
    - Indented item
    - Indented item
- Item
```

### Inline code

```markdown
This is an inline `code`.
```

### Horizontal rule

```markdown
Here's some text.

---

Here's more text.
```

### Link

```markdown
[title](https://www.example.com)
```

### Image

```markdown
![alt text](image.jpg)
```

## Extended syntax

These elements provide additional features by extending the basic syntax. Not all Markdown applications support these elements and each `Markdown Flavor` differs slightly.

Note that GitHub.com uses its own version of the Markdown syntax called [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown) and some features are only available in the issues and pull requests.

Refer to [Jekyll Markdown coverage](https://www.markdownguide.org/tools/jekyll/) for a list of supported elements.

Detailed information and examples can be fount at [extended syntax guide](https://www.markdownguide.org/extended-syntax/).

### Table

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

```markdown
| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |
```

### Fenced code block

```
{
    "firstName": "John",
    "lastName": "Doe",
    "age": 25
}
```

    ```
    {
        "firstName": "John",
        "lastName": "Doe",
        "age": 25
    }
    ```

### Syntax highlighting

```json
{
    "firstName": "John",
    "lastName": "Doe",
    "age": 25
}
```

    ```json
    {
        "firstName": "John",
        "lastName": "Doe",
        "age": 25
    }
    ```

### Footnote

```
Here's a sentence with a footnote reference. [^1]

[^1]: This is the footnote.
```

### Abbreviation

```markdown
*[SMTP]: Simple Mail Transfer Protocol
The SMTP is a communication protocol for email transmission.
```

### Heading ID

```markdown
### Awesome Heading {#custom-id}
```

### Definition list

Not supported by Jekyll.

```markdown
term
: definition
```

### Strikethrough

```markdown
~~~text~~~
```

### Task list

```markdown
- [x] Read the Markdown guide
- [ ] Review the style guide
- [ ] Stay awesome!
```

### Emoji characters

```markdown
👍🤓
```

### Emoji shortcodes

Not supported by Jekyll.

```markdown
:rocket:
```

### Automatic URL linking

Not supported by Jekyll.

```markdown
https://www.example.com
```

### Disabling automatic URL linking

Not supported by Jekyll.

```markdown
`https://www.example.com`
```

### HTML

```html
<div>
    <p>HTML test paragraph.</p>
</div>
```

## Further reading

[The Markdown Guide](https://www.markdownguide.org/getting-started/) provides a detailed overview of Markdown, how it works, and what can be done with it.

Hands on Markdown experience can be achieved by completing [The Markdown Tutorial](https://www.markdowntutorial.com) or simply experimenting with online editors such as [StackEdit](https://stackedit.io).

A collection of awesome markdown goodies (libraries, services, editors, tools, cheatsheets, etc.) can be found at [Awesome Markdown Repo](https://github.com/mundimark/awesome-markdown) on GitHub.
