# BATCH-2021-June


Repositories &amp; exercises of batch 2021 july.

___
## Table of Contents

- [BATCH-2021-June](#batch-2021-june)
  - [Table of Contents](#table-of-contents)
  - [Setup and installation](#setup-and-installation)
  - [Markdown ✨](#markdown-)
    - [Introduction 📜](#introduction-)
    - [History 🕐](#history-)
    - [What is Markdown in simple language?? 🤔](#what-is-markdown-in-simple-language-)
    - [Markdown Cheat Sheets 📖](#markdown-cheat-sheets-)
  - [Git](#git)
  - [Guides](#guides)
  - [Contributers 🎓](#contributers-)
  - [- **Sudesh Acharya**](#--sudesh-acharya)

___


## Setup and installation

>First, you need to clone the repository inorder to access the content. <br/>  `git clone https://github.com/iBootcamp/batch-2021-june.git`

---

## Markdown ✨

### Introduction 📜

Markdown is a lightweight markup language for creating formatted text using a plain-text editor. John Gruber and Aaron Swartz created Markdown in 2004 as a markup language that is appealing to human readers in its source code form.Markdown is widely used in blogging, instant messaging, online forums, collaborative software, documentation pages, and readme files.
<br>

### History 🕐

In 2002 Aaron Swartz created atx, "the true structured text format". Swartz and John Gruber then worked together to create the Markdown language in 2004, with the goal of enabling people "to write using an easy-to-read and easy-to-write plain text format, optionally convert it to structurally valid XHTML (or HTML)".<br>

Its key design goal is readability – that the language be readable as-is, without looking like it has been marked up with tags or formatting instructions, unlike text formatted with a markup language, such as Rich Text Format (RTF) or HTML, which have obvious tags and formatting instructions. To this end, its main inspiration is the existing conventions for marking up plain text in email, though it also draws from earlier markup languages, notably setext, Textile, and reStructuredText.<br>

Gruber wrote a Perl script, Markdown.pl, which converts marked-up text input to valid, well-formed XHTML or HTML and replaces angle brackets '<' '>' and ampersands '&' with their corresponding character entity references. It can take the role of a standalone script, a plugin for Blosxom or a Movable Type, or of a text filter for BBEdit.
<br>

### What is Markdown in simple language?? 🤔

  It is a simple language just like markup language i.e (Html) but is more simpler than it or can also be said as lightweight markup language which is simply used for creating certain texts using a simple text editor. The read-me file that you are reading right now is also a markdown file. It's extension is `.md` which stands for markdown. 
  <br>

### Markdown Cheat Sheets 📖

In this section, you will find the easiest way to implement  most of the Markdown syntax elements...
>Note:- Remember to save the file in `.md` extension to make it markdown.

There are two types of markdown syntax elements. Namely:-
1. Basic Syntax 
2. Extended Syntax
  
**Basic Syntax:-** <br>
  Generally, basic syntax are the very basic syntax of elements used in md (markdown files) which are supported by all markdown applications. Some basic syntaxes are given below: 👇
| Elements | Syntax |
| --------- | -------- |
| Heading  | ` # H1, ## H2, ### H3 ` |
| Bold text| `** I am bold **` |
| Italic text | `* I am italic *` |
| Blockquote | `> For writing blockquote` |
| Ordered List | `1. abc  ` |
| ... |` 2. yoohoo` |
| ... |` 3. and so on` |
| Unordered List | `- abc ` |
| ... | `- yohoo `|
| ... | `- I m number 3 and so on` |
| Code | ` `` `  |
| Horizontal line / Margin | `---` |
| Link | `[title you want](url of it)` |
| Image | `![alt text](image.jpg)` |
| Comment | ` <!--- This is comment ---> ` |

> Note:- 
> 1. In the elements section, "..." is used to determine the continuity of above elements. 
> 2. The syntax used for code is ` `` ` called as tics. It's above the tab button in the keyboard.
<br>

**Extended Syntax:-**<br>
  Basically, these syntax extends the properties or workings of the basic syntax by adding some additional features like creating the tables , fenced block notes and so on. Also, some syntaxes are given below: 👇
| Elements | Syntax |
| --------- | -------- |
| Footnote | `Here's a sentence with a footnote. [^1]` |
| .... | ` [^1]: This is the footnote. ` |
| Fenced Code Block | ` ``` ` |
| ... | `{` |
| ... | ` "firstName": "John", "lastName": "Smith", "age": 25` |
  | ... | `}` |
| ... | ` ``` ` |
| Heading ID | `### My Great Heading {#custom-id} `|
| Definition List | `term` |
| ... | `: definition` |
| Strikethrough | `~~The world is flat.~~` |
| Task List | `- [x] Write the press release` |
| ... | `- [ ] Update the website` |
| ... | `- [ ] Contact the media` |
| Table | ``` | Anime | Cartoon | ``` |
| ... | ``` | ----- | ------- | ``` |
| ... | ``` | Hello | Bye-Bye | ``` |
| ... | ``` | Life | Happy    |  ``` |

> Note:- 
> 1. In the elements section, "..." is used to determine the continuity of above elements. 
> 2. The ` ~ ` symbol is called as 'Tilde' and is present above tab button in the keyboard . Press " SHIFT + ` " to ge tilde ( ~ ) symbol.
<br>

*For further more information, you can click on link below to learn about the markdown cheat sheets. 👇*

  *[Markdown Cheat Sheets](https://www.markdownguide.org/cheat-sheet/)*

  *[Markdown Cheat Sheet Online](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)*
  
---
## Git

- Introduction
  - Git
    Git is a software which is used to in our local computer(PC or laptop) to track file or folders which contains data of users and saves the files or folders date for future use. Git is mordern way of saving, protecting and sharing our program files. Git is also known as version control software. Version control simply means the way of managing changes of the softwar code or application code with previous version and we can easily track previous data easily. Git can be used for personal use or office use(team use).We can use git with command line(Git bash) or with git GUI. There are other Git GUI interfaces which are easy to use example tortoise-git (https://tortoisegit.org/download/).

  - Github
    Github is a online cloude aka online storage where we can keep our program file and documents mostly software data or codes over there. Github makes use of git hence we can view our commits and changes in github aslw well. We use git command to push local data(PC data) from our local repository(add link) to Github repository(Remote). In github we can get open source code and use it freely by cloning in our local computer. There are other similiar platform like gitlab bitbucket and many more.
  - Git vs Github

        | Git                                           | Github                                        |
        | -------------                                 | -------------                                 |
        |1. Installed locally                           |1. Hosted in the cloud                         |
        |2. First released in 2005                      |2. Company launched in 2008                    | 
        |3. Focused on version control and sharing      |3. Focused on centralized source code hosting  |
        |4. Primarily a command line tool               |4. Administered through the web                | 
        |5. Provides a desktop interface named Git Gui  |5. Desktop interface named Github Desktop      |
        |6. No user management                          |6. Built-in user management                    | 
        |7. Minimal external tool                       |7. Active marketplace for tool integration     | 
        |8. Open source licened                         |8. Inludes a free tier and pay-for-use tiers   |
        


  - Motivation
- Guides
- Documentation
  - Initialize a repo
  - Remote
    - Add Remote
    - Origin
  - Cloning
  - Untracked files , tracked files & modified files
  - branch (default)
  - Status
  - add
  - commit
  - alias
  - diff
  - Advanced branch

---
## Guides
In order to start learning git, we need to first download and install git. Here is the link for git:  <br/>  `https://git-scm.com/downloads`

---
## Contributers 🎓

- [**Rakesh Shrestha**](https://github.com/aomini)
- [**shreyash Shrestha**](https://github.com/Shr3yashhh)
- [**Debrath Sharma**](https://github.com/Madara-coder)
- [**Sudesh Acharya**](https://github.com/thesudesh)
---
