# tej-my_markdown-repo
Hello to Anyone other than me, In this repo i am documenting markdown syntax to the best of my knowledge.    
This repo can act as you quick reference markdown guide.

<br>

Syntax of markdown from below.

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



## Line break and Horizontal

### Line break
The best method for achieving an Line break in markdown is using HTML syntax br inside < >
- how it looks:

below is Line break

<br>

above is Line break

- Syntax of Line break
```markdown
There is an Line break below

<br>

There is an Line break above
```
- Note: it is best to leave a line above and below, for GitHub's markdown render engine to avoid miss-renders

### Horizontal
The syntax for Horizontal line is 3 hyphens or underscores or asterisks.
- how it looks:

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



## List , Numarical list and Check list

### Lists
Lists are generated using hyphen followed by white space, and for sub lists use tab space before the hyphen.

how it looks:
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

### Numarical list
Similar to lists but we use number followed by fullstop and whitespace.

how it looks
1. list 1
2. list 2
    1. list 2.1
    2. list 2.2
        1. list 2.2.1

- Sunctax for Numerical list
```markdown
1. list 1
2. list 2
    1. list 2.1
    2. list 2.2
        1. list 2.2.1
```

### Check list
Similar to Lists, for checklist we use [ ] for unchecked and [x] for checked.

how it looks
- [] list 1
- [x] list 2
    - [x] list 2.1
    - [] list 2.2
        - [x] list 2.2.1

- Syntax for Checked list
```markdown
- [] list 1
- [x] list 2
    - [x] list 2.1
    - [] list 2.2
        - [x] list 2.2.1
```
