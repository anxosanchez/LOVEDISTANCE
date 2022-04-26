---

marp: true
theme: gaia
paginate: true
header: "Universidade de Vigo"
footer: "![w:240 h:48](erasmus-cofunded-logo.png) LOVEDISTANCE"
size: 16:9
Divider:
---

<!-- _paginate: false -->
<!-- _class: lead -->

#  <!-- fit -->  Markdown Authoring
## Anxo Sánchez Bermúdez
## University of de Vigo

---
<!-- header: "" -->
<!-- footer: "" -->
<!-- class: invert -->

# Frustrations with  word processors

- Most teachers I know fall into one of two groups: **Microsoft Word'ers** or **Google Docs'ers**
- Both are terrible, especially in a world where there’s Markdown.
- When we want share with students we use **PDF** format.
- Make presentations with **Powerpoint**, **Impress** or **Google Slides** ...
- Try to convert a **MS word ```docx```** file to **MS PowerPoint ```pptx```** and then share it in **Adobe ```pdf```**!

---

# What is markdown?

Markdown is a markup language. The Markdown language lets you write plain text documents with a few annotations that specify the document format. Format is independet of source.

- Text: headers, footers, etc.
- Fonts and font sizes.
- Line, page numbes, etc.

---

# Math fórmulas

$$
\frac{\partial (\rho u_{i})}{\partial t} + \frac{\partial[\rho u_{i}u_{j}]}{\partial x_{j}} = -\frac{\partial p}{\partial x_{i}} + \frac{\partial \tau_{ij}}{\partial x_{j}} + \rho f_{i}
$$
$$
\frac{\partial \rho}{\partial t} + \overrightarrow{\nabla}\cdot(\rho\overrightarrow{u})=0 
$$
$$
\frac{\partial(\rho \overrightarrow{u})}{\partial t} + \overrightarrow{\nabla}\cdot[\rho\overline{\overline{u\otimes u}}] = -\overrightarrow{\nabla p} + \overrightarrow{\nabla}\cdot\overline{\overline{\tau}} + \rho\overrightarrow{f}
$$

---

# Mermaid Diagrams

[![w:600 h:400](https://mermaid.ink/img/pako:eNpt0M2qAjEMBeBXidk68wJdKILC1a3bbkJ7dMrtj9YWEfHd7YzjzqwC-U4gebJJFqz4hmtFNNg6OWcJOlKrjXcG_Wq1PKQhKvqD94nGvqMh3Uky6JHq-if-MCNxJDRAMgXMdJz1jfZTpi12n3RH-ykx6RZb_OZ7OgGezhlSZvIt7jggB3G23fQcZ5rLgADNqrVW8r9mHV_N1YuVgp11JWVWJ_E3dCy1pOMjGlYlV3zR_JRZvd5_C2Gl)](https://mermaid.live/edit#pako:eNpt0M2qAjEMBeBXidk68wJdKILC1a3bbkJ7dMrtj9YWEfHd7YzjzqwC-U4gebJJFqz4hmtFNNg6OWcJOlKrjXcG_Wq1PKQhKvqD94nGvqMh3Uky6JHq-if-MCNxJDRAMgXMdJz1jfZTpi12n3RH-ykx6RZb_OZ7OgGezhlSZvIt7jggB3G23fQcZ5rLgADNqrVW8r9mHV_N1YuVgp11JWVWJ_E3dCy1pOMjGlYlV3zR_JRZvd5_C2Gl)


---

# What is not markdown?

- A WYSIWYG (what you see is what you get) editor.
- You decide your text with information (chapters, sections, etc), but not its format.

This workflow paradigm makes it easier to produce different kinds of outputs. Working together with [pandoc](https://pandoc.org) your markdown source can easily be transformed into other formats like HTML, PDF, or DOCX

---

# <!-- fit --> Markdown Principal Characteristics

- Markdown is simple. Annotations are minimal, and in made in plain text.
- Markdown is generates easyly documents in other markup languages or formats.
- It uses also templates so you can write custom templates and stylesheets.
- Math expresions are writen in LaTeX.
- It uses Pandoc as translation support (several extensions.)

--- 

# Why Use Markdown

* If you are an content author which changes versions and outputs formats (like a learner)
* If you thing WYSIWYG editors such as Microsoft Word can ba a nightmare.
* When you share your documents with others, the use of plain text is a good idea.
* Plain text editors are free, light and portable. If you are authoring in plain text file, you know exactly what you are editing.
* If you need your document in different formats, for example, pdf, slides, etc. 

---

# Semantics vs Format

* Texts consist of chapters and sections, plain text and emphasized text, figures and citations, quotes, and lists. 
* Semantic elements are visualized by different fonts, bold and italic text, different font sizes, and we do not directly see the semantic structure.
* Most word processors separate semantics from formatting. 
* Using WYSIWYG word processors doesn’t prevent you from structuring your documents as semantic units—they.

---

# Preprocessing Documents

- There are a lot of options in order to process documents before convert them into a final output.
- There are a lot of tools that will work well with plain text and markdown as preprocessors.
- Preprocessing documents often require a few programming skills, so it might not be the first thing to learn about markdown

---

# Concepts 

- First, we can learn about:
  - Files
  - Templates
  - Style sheets
  - Outputs
  - Pandoc

---

# Markdown Process

<!-- backgroundColor: gray -->

![](flowchart1.png)

* You can translate the text in multiple documents, or merge multiple chapters into a single one.
* You combine templates for formatting the documents, and using **Pandoc** to produce the documents you want.

---

<!-- backgroundColor: default -->

 Why Use MarkdoWn and pandoc?

* You can write without worrying about it initially, and format later.
* You have a lot of code examples.
* You use math formulas
* You make graphs or charts with online software
* Yu wabt easily capture web pages
* You share documents with many people
* You use online sites that can render markdown (Moodle, Jupyter, wordpress, Hugo, etc)

---

Why Markdown?

* It's a markup languege easier to leran than any other (HTML)
* Is much easy but compayibler with TeX and LaTeX
* What makes Markdown particularly pleasant to work with is its simplicity.

* Consider this Markdown document:

```markdown
* One
* Two
```

---

# In LateX

```latex
\begin{itemize}
\item One
\item Two
\end{itemize}
```
# In HTML

```html
<ul>
<li>One</li>
<li>Two</li>
</ul>
```
----

# Why Pandoc?

* Since Markdown is just a language for adding structure to a text, it is not tied to any particular tool.
* Many blogging platforms accep Markdown and automatically format it for you to HTML (**Moodle**).
* Now, many text editors also support Markdown but may be you need to export to different file formats and in different styles, then that is obviously the easiest way for you to export your Markdown text. 
* Pandoc is vastly more versatile than any Markdown-aware text editor.

--- 

# Writing Markdown

```markdown
# Header level 1
## Header level 2
### Header level 3
```
# Header level 1
## Header level 2
### Header level 3

---

# Emphasis

```markdown
*Italics* or _Italics_
**Bold** or __Bold__
_**Italic Bold**_
**_Italic Bold_**
```
*Italics* or _Italics_
**Bold** or __Bold__
_**Italic Bold**_
**_Italic Bold_**

---

# Lists

```markown
1. This is a numbered list.
2. Where this is list item two.
3. And this is list item three.
```

1. This is a numbered list.
2. Where this is list item two.
3. And this is list item three.

---

```markdown
1. This is a multi-line list item.
   This is also part of the list item.
   And so is this
2. Here is another one.
   Where this is also part of the list item.
```

1. This is a multi-line list item. This is also part of the
   list item. And so is this.
2. Here is another one. Where this is also part of the list
   item.
  
---

# Sublists

```markdown
- This is a top-level list item
    * Here is a sublist item
    * Here is another
```
- This is a top-level list item
    * Here is a sublist item
    * Here is another

---

# Block Quotes

```markdown
> This is a blockquote. The blockquote
>  can span multiple lines. If you don't
> put any new lines in it, you only
```

> This is a blockquote. The blockquote
> can span multiple lines. If you don't
> put any new lines in it, you only

---

# Verbatim Text 

\`\`\`
This will be shown absolutely verbatim
\`\`\`

The result will then look like this:

```
This will be shown absolutely verbatim
```

---

# Links

This is a link to [my blog](https://github.io/anxosanchez/).


This is a link to [my blog](https://pdf2md.morethan.io/[http://www.mailund.dk](http://www.mailund.dk)).


This is a link to [the section](https://pdf2md.morethan.io/#verbatim).

---

# Images

![Title of the figure](https://eei.uvigo.es/wp-content/uploads/2022/04/Tecnologias_XR.jpeg)

---

# combined with HTML

<style>
img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
</style>

![w:649 center](https://eei.uvigo.es/wp-content/uploads/2022/04/Tecnologias_XR.jpeg)

---

```markdown
a. This list uses letters instead of numbers.
b. We can make a sublist with roman numerals:
i. This sublist also uses parenthesis
ii. Cool, isn’t it?
```

looks like

a. This list uses letters instead of numbers.
b. We can make a sublist with a roman numerals:
i. This sublist also uses parenthesis
ii. Cool, isn’t it?

---

# Tables

```markdown
| Right | Left | Default | Center |
| ----: | :--- | :------ | :----: |
|    12 | 12   | 12      |   12   |
|   123 | 123  | 123     |  123   |
```
Result:
| Right | Left | Default | Center |
| ----: | :--- | :------ | :----: |
|    12 | 12   | 12      |   12   |
|   123 | 123  | 123     |  123   |

---

# Footnotes

Footnote inside a paragraph.[^1]

Reference to a footnote.[[1\]](https://pdf2md.morethan.io/#fn1)

[^1]: This is footnote one.

---

# Syntax Highligthing

```python
for (int i = 0; i < n; i++) 
printf("%d\n", i);
```

```matlab
function v = f(x);
    v = exp(a^3)  - x
```
---

# Maths

```latex
$$p_k(x)=\prod_{\substack{i=1\\i\ne k}}^n
\left(\frac{x-t_i}{t_k-t_i}\right)$$
```
looks like

$$p_k(x)=\prod_{\substack{i=1\\i\ne k}}^n
\left(\frac{x-t_i}{t_k-t_i}\right)$$

---

# Presenter notes

```
<!-- This is a presenter note for this page. -->
<!-- EXAMPLE: An EXAMPLE directive is not defined in Marp/Marpit, so this works as presenter notes. -->
```
```<!-- fit -->``` This is not a presenter note.

---

<!-- class: lead -->

# <!-- fit --> Thank you!
## Creative Commos License
![w:300 h:100](by-nc-nd.eu.png) 


---
