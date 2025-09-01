# Markdown Project Template
A reusable,fully-featured README scaffold that demonstrates and documents every major Markdown element you'll likely need.Copy this file into new projects,then keep only the sections you need.  

> **Why this exists**  
>
>  * Teams repeat README boilerplate.
>  * New contributors need examples.
>  - Can also use 'hiphen' for bullet points.
> > This template serves as a living reference and starter  
> > It shows _how_ and _why_ with examples.  

three underscores  is for horizontal line
___

## Quick Start
1. Clone or download this repository
2. Copy ` README.md` into your project root.
3. Create a sample content with your own while keeping the structures you need  
___

## Project Status
* [X] Template complete
* [ ] Replace placeholder links
* [ ] Add Project-Specific setup steps
* [ ] Configure CI badges

Three hiphens  will also work for horizontal line

---
 
## Contents
1. [Features](#features)  
2. [Install](#install)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [FAQ](#faq)
6. [Contributing](#contributing)
7. [License](#license)
8. [Appendix: Markdown Reference](#appendix:markdown-reference)  

Note:  
1. 'square brackets [ ]' contain 'link text'. 'parantheses ( )' contain 'link target'.
2. Link text (the label shown to readers)
3. Parentheses ( ) is the link target/destination (URL, relative path, or anchor ID).
## Features

* Asterisks list item
* List continues  
    * Nested items supported
+ Plus sign also works for bullet points
+ Same Semantics
- Dash works too
* Choose a single style per doc for consistency

---

## Install
**Requirements**  
* Git
* A recent runtime for your stack
* A terminal  
   
**Steps**
1. Numbers
2. Doesn't matter
    1. Nested step one
    2. Nested step two
---
## Usage
**Basic example**  
Create a program printing "hello" once and then twice.    
Create a program saying your name and age.

Inline code: `print("Hello World)` then call `print("Hello world"*2)`.
```python
# minimal demo program
name = "Akshay"
age = 24
print(f"My name is {name} and i'm {age} years old.")
```

---
Two spaces at the end of this line creates a line break.  
This line is directly below without a blank paragraph.  
  

Automatic linking is supported in many renderers: https://example.com  


Angle-bracket link form : <https://example.com/docs>  
Note: Opening and closing angle brackets can be used to enclose links.  

Link with label : [Project Home](https://example.com)  

Relative link example : [CONTRIBUTING](./CONTRIBUTING.md)  
Note: './CONTRIBUTING.md' and '.CONTRIBUTING.md' works  when both are in the same folder.  

  
Link to an id in this doc: [Jump to Appendix](#appendix:markdown-reference) 

___
## Configuration

| Key | Type | Default |Description |  
| --- |--- | --- | --- |
| `timeout` | number | `30` |Request time in seconds |  
| `retries` | number | `2` |Retry attempts |  
| `loglevel` | string | `info` |Log verbosity |  

  
Alignment demo:
|Right|Center|Left|
|---:|:---:|:---|
|100|mid|low|
|10|mid|high|

---

## Visuals
Absolute image:

![Open graph placeholder](https://placehold.co/200x100)

Relative image (add `docs/diagram.jpg to your repo`):
![Architecture Diagram](./docs/diagram.jpg)

----

## Text Styling Reference

**Bold** and **also bold** in-word as**teris**ks.  
_italic_ and  _also italic_ and in-word as*teris*ks.  
***Both styles*** and ***also both*** and ***combo*** and mid-word as***teris***ks.  

~~Strikethrough~~ for removed items. 
   
⚠ Github does not support highlight `==like this==`, so use **bold** or ___italic___ for emphasis instead.
   
⚠ GitHub does not support subscript/superscript with `~` or `^`.Use plain tet like `H2O` or `x^2`.  

I am happy :smile:
    
Horizontal rules

___
***
---
___

## FAQ

**Q: How do i cite sections of this document?**  
A: Use auto-generated id links like `[Features](#features)`.  
  
**Q: Can i use checklists for roadmaps?**
A: Yes. See the "Project Status" section.  

**Q: Do line breaks require blank lines?**  
A: No.Add two trailing spaces at line end to force a `<br>`.

---
## Contributing
> Start simple. Improve iteratively.

- Fork the repo
- Create a feature branch
- Write tests
- Open a PR
  
Code of conduct link: [Back to top](#markdown-project-template)  
  
Inline code sample : Python variable `name="Akshay`
```bash
# Standard GitHub flow
git checkout -b feat/my-change
git commit -m "feat: my change"
git push origin feat/my-change
```


