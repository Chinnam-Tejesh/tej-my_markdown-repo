# tej-my_markdown-repo
Hello to Anyone other than me, In this repo i am documenting markdown syntax to the best of my knowledge.    
This repo can act as you quick reference markdown guide.

<br>

Syntax of markdown from below.

---
---

## General Text

### Headings
Headings in markdown are level based, think of Lower level headings are sub-topics of the Higher level headings.
- Syntax of headings start with # followed by white space and the title. note the more #-es the lower level is the heading.
    ```markdown
    # heading1
    ## heading2
    ### heading3
    and more...
    ```

### Text Bold
Bold text in markdown is achived by using 2 asterisk before and after the text that is to be rendered Bold.
- eg: **This text is rendered Bold**
- Syntax of Text Bold is
```markdown
The line below is bold
**This line is bold**
```

### Text Italic 
Italic text is markdown is achived similar to Bold but using 1 asterisk before and after.
- eg: *This text is rendered Italic*
- Syntax of Text italic
```markdown
The line below is italix
*This line is italic*
```

### Text Bold and Italic
Both Bold and Italic on an text is achived using 3 asterisk before and after.
- eg: ***This text is rendered Bold and Italic***
- Syntax of Text Bold and Italic
```markdown
The line below is Bold and Italic
***This line is both Bold and Italic***
```

### Text Monospace
Text Monospace is achived using backtick before and after. (mostly used for inline code)
- eg: `This text is rendered Monospace`
- Syntax of Text Monospace
```markdown
The line below is Text Monospace
`This line is Text Monospace`
```

### Text Strike
Text Strike is achived using 2 tilde before and after.
- eg: ~~This text is rendered strikethrough~~
- Syntax of Test strike
```markdown
The line below is Text Strike
~~This line is Text Strike~~
```

### Block Quotes
Block Quotes is achived using grater-than symbol (for first level) and 2 grater-thans (for second level).
- eg: the following is a Block Quote

> This is first level Block Quote.
>> this is second level Block Quote.
> rough, still first level Block Quote.

- Syntax for Block Quotes
```markdown
> This is first level Block Quote.
>> this is second level Block Quote.
```

---
---

## Line break and Horizontal

### Line Break
The best method for achieving an Line Break in markdown is using HTML syntax br inside < >
- eg:

below is Line Break

<br>

above is Line Break

- Syntax of Line Break
```markdown
There is an Line Break below

<br>

There is an Line Break above
```
- Note: it is best to leave a line above and below, for GitHub's markdown render engine to avoid miss-renders

### Horizontal
The syntax for Horizontal line is 3 hyphens or underscores or asterisks.
- eg:

below is Horizontal

---

above is Horizontal

- Syntax of Horizontal
```markdown
There is an Horizontal below

---

There is an horizontal above
```
- Note: level 1 Headings in GitHub automatically render an thin horizontal, the syntatically induced render is thick in comparision.
- Note: cant generate an Horizontal inside points / list.

---
---

## List , Numarical list and Check list

### Lists
Lists are generated using hyphen followed by white space, and for sub lists use tab space before the hyphen.

eg:
- list 1
- list 2
    - list 2.1
    - list 2.2
        - list 2.2.1

- Syntax for List
```markdown
- list 1
- list 2
    - list 2.1
    - list 2.2
        - list 2.2.1
```

### Numarical List
Similar to lists but we use number followed by fullstop and whitespace.

eg:
1. list 1
2. list 2
    1. list 2.1
    2. list 2.2
        1. list 2.2.1

- Sunctax for Numerical List
```markdown
1. list 1
2. list 2
    1. list 2.1
    2. list 2.2
        1. list 2.2.1
```

### Check List
Similar to Lists, for checklist we use [ ] for unchecked and [x] for checked.

eg:
- [ ] list 1
- [x] list 2
    - [x] list 2.1
    - [ ] list 2.2
        - [x] list 2.2.1

- Syntax for Checked List
```markdown
- [ ] list 1
- [x] list 2
    - [x] list 2.1
    - [ ] list 2.2
        - [x] list 2.2.1
```

---
---

## Code 

### Single/In-line Code
Single/In-Line code in markdown is achived use backtick before and after the code.
- eg: this is text `this is in-line code` this is text.
- Syntax of Single/In-line Code:
```markdown
this is text `this is in-line code` this is text.
```

### Multi-line Code
Multi line code in markdown is achived using 3 backticks before and after the code.
- eg:
```
this is a multi line code block
this is a multi line code block
```
- Syntax of Multi-line Code:
```
```
this is a multi line code block
this is a multi line code block
```
```
- Note: in Multi-line code we can use syntax highlighting by typing programming language name after the first/starting 3 backticks.
- syntax highliting of markdown eg:
```
```markdown
# this is a multi line code block
## this is a multi line code block
```
```