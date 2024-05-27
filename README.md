# Markdown for Beginners

Markdown is a lightweight markup language that's easy to learn and very useful for formatting text in a simple, readable way spacialy for github repos. To get started, here are some basics of Markdown:

## Basic Syntax

### 1. Headings:
- Use # for headings. The number of # signs indicates the heading level.
```markdown

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
```
this will render as:
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5

### 2. Pragraph or text:
- In Markdown, creating paragraphs or blocks of text is very straightforward. Simply writing text on separate lines will create paragraphs. Here are some key points to remember:
    - To create a new paragraph, just leave a blank line between blocks of text.
    - If there is no blank line, the text will be part of the same paragraph.
    - If you want to insert a line break (i.e., start a new line but not a new paragraph), end a line with two spaces and then press Enter.
    - You can combine paragraphs with other Markdown formatting, such as bold, italic, lists, etc.
        Example:

        ```markdown

        ## Introduction

        This is the first paragraph. It's an introduction to **Markdown**.  
        Here is a second line in the same paragraph.

        This is the second paragraph. It contains an _italicized word_.
        ```
        this will render as:
        ## Introduction

        This is the first paragraph. It's an introduction to **Markdown**.  
        Here is a second line in the same paragraph.

        This is the second paragraph. It contains an _italicized word_.




### 3. Bold and Italics:

- Use ** or __ for bold text, and * or _ for italics.

```markdown

**bold text**
*italic text*
```
this will render as:

**bold text**
*italic text*


### 4. Lists:

- Unordered Lists: Use -, +, or * to create bullet points.

    ```markdown

    - Item 1
    - Item 2
    ```
    this will render as:

    - Item 1
    - Item 2
    

- Ordered Lists: Use numbers followed by a period.

    ```markdown

        1. First item
        2. Second item
    ```
    this will render as:
1. First item
2. Second item
    
- sub list: just use tab frist then as per unordered or ordered lists.
    Exaple
    ```markdown

    1. First item
        1. Frist item
            1. Frist item
                1. Frist item
                2. Second item
            2. Second item
        2. Second item
    2. Second item
        ```
    this will render as:
1. First item
    1. Frist item
        1. Frist item
            1. Frist item
            2. Second item
        2. Second item
    2. Second item
2. Second item


### 5. Links:

- Use [link text](URL) for hyperlinks.

```markdown

    [OpenAI](https://www.openai.com)
```
this will render as:
[Opern AI](http://www.openai.com)

### 6. Images:

- Use ![alt text](image URL or image path) to embed images.

```markdown

    ![Logo](https://www.example.com/logo.png)
```
this will render as:
![Logo](https://www.example.com/logo.png)


### 7. Blockquotes:

- Use > to create blockquotes.

```markdown

    > This is a blockquote.
```
this will render as:
> This is a blockquote.


### 8. Code:

- For inline code, use backticks: 
    ```markdown
    `code`
    ```
    this will reder as:
    `code`

- For code blocks, use triple backticks:
    Exaple:
    ```markdown

    |```python
    def function():
        return "Code block"
    \``` 
        
    ```
    ```python
    def funtion():
        return "Code block"
    ```

### 9. Horizontal Rules:

- Use ---, ***, or ___ to create horizontal lines.

```markdown
---
```

this will render as:

---

### 10. Tables

- To create a table, use pipes (|) and three dashes (-). The pipes separate columns and the dashes create the header row.
Example:

```markdown

| Header 1 | Header 2 | Header 3 |
|---|---|---|
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 |
| Row 2 Col 1 | Row 2 Col 2 | Row 2 Col 3 |
```
this will render as:
 Header 1 | Header 2 | Header 3 |
|---|---|---|
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 |
| Row 2 Col 1 | Row 2 Col 2 | Row 2 Col 3 |

- You can also align text within columns by adding colons (:):
Example:

```markdown

| Left Align | Center Align | Right Align |
|:---|:---:|---:|
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 |
| Row 2 Col 1 | Row 2 Col 2 | Row 2 Col 3 |
```
this will render as:

| Left Align | Center Align | Right Align |
|:-----------|:------------:|------------:|
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 |
| Row 2 Col 1 | Row 2 Col 2 | Row 2 Col 3 |


### 11. Checkboxes

To create checkboxes, use - [ ] for an unchecked box and - [x] for a checked box.

```markdown

- [ ] Task 1
- [x] Task 2
- [ ] Task 3
```
this will render as:

- [ ] Task 1
- [x] Task 2
- [ ] Task 3



## Examples text

Here’s a sample Markdown document that uses these elements:

```markdown

# My Markdown Document

## Introduction

This is a simple document to demonstrate **Markdown**.

### Features

- Easy to read
- Easy to write
- Converts to HTML

## Example Code

Here is some example code:

|```python
def hello_world():
    print("Hello, world!")
|```

```
