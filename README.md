<!-- ********************** Syntacticum START  ********************** -->

# **Project Syntacticum** #

### Overview
Project Syntacticum is a compendium of various technologies and programming languages that documents their respective syntax.
The purpose of this compendium is not to give examples of code using syntax, but is to be used only to reference syntax.

### Syntax

- New section:          **`# NEW SECTION / acronym expansion (".filetype") #`**
- New item:               **`- "NEW ITEM" `**
- Highlight Syntax:   **` ```HIGHLIGHT CODE``` `**
- New Table:           `| Heading 1 | Heading 2 | Heading 3 |`
                       `|-----------|-----------|-----------|


<a name="table-of-contents"></a>

### Table of Contents
* [Git](#git)
* [HTML](#html)
* [Markdown](#markdown)
* [NPM](#npm)
* [Terminal](#terminal)

### Contributing Guidelines
* Add only one definition in one pull request.
* Pull request title format includes: [Syntax Name] -> [Section]
    * Example: [For Loop] -> [Java]
* Provide a reference for the syntax.
    * Example: Link: https://www.w3schools.com/java/java_for_loop.asp


<!-- ********************** Syntacticum End  ********************** -->




<!-- ********************** Git START ********************** -->

<a name="git"></a>
# Git

| Command &nbsp;&nbsp;&nbsp;&nbsp; | Syntax &nbsp;&nbsp;&nbsp;&nbsp;| Description&nbsp;&nbsp;&nbsp;&nbsp; | 
|----------------------------------|--------------------------------|-------------------------------------|
| Clone  | `git clone https://github.com/user-name/repo-name.git`   | Clone a repo.                       |
| Commit | `git commit -m "Your message for the commit goes here."` | Commit your changes.                |
| Pull   | `git pull`                                               | Pull from a repo.                   |
| Push   | `git push repo-name branch-name`                         | Push your changes to a repo.        |

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>
    
<!-- ********************** Git END ********************** -->





<!-- ********************** HTML START  ********************** -->
<a name="html"></a>

# HTML / Hypertext Markup Language (.html) #

| Command &nbsp;&nbsp;&nbsp;&nbsp; | Syntax &nbsp;&nbsp;&nbsp;&nbsp;| Description&nbsp;&nbsp;&nbsp;&nbsp; | 
|----------------------------------|--------------------------------|-------------------------------------|
| Article                          | `<article>Article 1</article>` | Article section syntax for html.    |
| Comment                          | `<!-- This is an HTML Comment -->` | Comment syntax for html.        |
| Footer                           | `<footer>Footer 1</footer>`    | Footer section syntax for html.     |
| Header                           | `<header>Header 1</header>`    | Header section syntax for html.     |    
| Image                            | `<img src="image/path/here">`  | Image syntax for html.              |
| Text Headers                     | `<h1>header 1</h1>` <br/> `<h2>header 2</h2>` <br/> `<h3>header 3</h3>` <br/> `<h4>header 4</h4>` <br/> `<h5>header 5</h5>` <br/> `<h6>header 6</h6>`         | Header Level 1 <br/> Header Level 2 <br/> Header Level 3 <br/> Header Level 4 <br/> Header Level 5 <br/> Header Level 6                                            |
| List Item                        | `<li>List Item</li>`           | List item                           |
| Link                             | `<a name="link name">"anchor text</a>`| Creates a link with specified anchor text. |
| Main Section                     | `<main>Main 1</main>`          | Main section syntax for html.       |
| Ordered List                     | `<ol>Ordered List</ol>`        | Ordered list                        |
| Paragraph                        | `<p>Paragraph 1</p>`           | Paragraph syntax for html.          |
| Unordered List                   | `<ul>Unordered List</ul>`      | Unordered list                      |

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>
    
<!-- ********************** HTML END  ********************** -->





<!-- ********************** Markdown START  ********************** -->
<a name="markdown"></a>

# Markdown (.md / .markdown) #

| Command &nbsp;&nbsp;&nbsp;&nbsp; | Syntax &nbsp;&nbsp;&nbsp;&nbsp;| Description&nbsp;&nbsp;&nbsp;&nbsp; | 
|----------------------------------|--------------------------------|-------------------------------------|
| Text Headers                     | `# header1` <br/> `## header2` <br/> `### header3` <br/> `#### header4` <br/> `##### header5` <br/> `###### header6`                                     | Header Level 1 <br/> Header Level 2 <br/> Header Level 3 <br/> Header Level 4 <br/> Header Level 5 <br/> Header Level 6                                            | 
| Horizontal Line                  | `***`  <br/> `---` <br/> `___` | Makes a horizontal line.            |



<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>
    
<!-- ********************** Markdown END  ********************** -->





<!-- ********************** NPM START  ********************** -->

<a name="npm"></a>

# NodeJS #

<!-- ********************** NPM END  ********************** -->

| Command &nbsp;&nbsp;&nbsp;&nbsp; | Syntax &nbsp;&nbsp;&nbsp;&nbsp;| Description&nbsp;&nbsp;&nbsp;&nbsp; | 
|----------------------------------|--------------------------------|-------------------------------------|
| install nvm                      | curl -o- 
https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash | Installs nvm on your computer.   |
| install node                     | nvm install node                  | Installs latest version.         |
| ls                               | nvm ls                            | Shows all installed versions.    |
| ls-remote                        | nvm ls-remote                     | Shows all available lts versions.|
| run                              | nvm run node                      | Runs the CLI for nodeJS.         |
| use                              | nvm use node                      | Sets the version of node to latest downloaded. |    


<!-- ********************** Terminal START  ********************** -->
<a name="terminal"></a>

# Terminal #

| Command &nbsp;&nbsp;&nbsp;&nbsp; | Syntax &nbsp;&nbsp;&nbsp;&nbsp;| Description&nbsp;&nbsp;&nbsp;&nbsp; | 
|----------------------------------|--------------------------------|-------------------------------------|
| cd                               | `cd` *OR* `cd ~` *OR* `cd ~/`  | Brings you to home directory.       |
| cd w/ path                       | `cd "path/to/directory/"`      | Brings you to a specified directory.|
| chmod 777                        | `chmod 777 "directory/path"`   | Grants RWX permissions to all users.|
| chmod 755                        | `chmod 755 "directory/path"`   | Grants R-X permissions to group and others.|
| clear                            | `clear`                        | Clears your terminal.               |
| echo                             | `echo "your string"`           | Repeat the input.                   |
| ls                               | `ls **OR** ls "path/to/directory/"`| List current directory.         |
| ls -a                            | `ls -a`                        |Show all files including hidden ones.|
| ls -l                            | `ls -l`                        |Show all files and their permissions.|
| mkdir                            | `mkdir "path/to/new/directory"`| Make a directory.                   |
| mv                               | `mv "filename" "path/to/new/location"`| Move a file.                 |
| mv (rename file)                 | `mv "filename" "newfilename"`  | Rename a file.                      |
| open                             | `open "filename"`              | Open a file.                        |
| touch                            | `touch "filename.filetype"`    | Make a file.                        |

| homebrew commands                | Syntax &nbsp;&nbsp;&nbsp;&nbsp;| Description&nbsp;&nbsp;&nbsp;&nbsp; | 
|----------------------------------|--------------------------------|-------------------------------------|
| install homebrew                 | `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`| Installs homebrew.                  |
| install homebrew nvm pkg         | `brew install nvm`             | Installs nvm package w/ homebrew    |
| install homebrew pyenv pkg       | `brew install pyenv`           | Installs pyenv package w/ homebrew. |
| install homebrew sqlite pkg      | `brew install sqlite`          | Installs sqlite package w/ homebrew.|
| install homebrew tree pkg        | `brew install tree `           | Installs tree package w/ homebrew   |
| install homebrew zlib pkg        | `brew install zlib`            | Installs zlib package w/ homebrew.  |

| python commands                  | Syntax &nbsp;&nbsp;&nbsp;&nbsp;| Description&nbsp;&nbsp;&nbsp;&nbsp; | 
|----------------------------------|--------------------------------|-------------------------------------|
| pip3 list                        | `pip3 list`                     | Lists all of the pkgs installed with pip3. |
| venv                             | `python3 -m venv "name of venv"`|Creates a virtual environment in current directory.| 

| xcode commands                   | Syntax &nbsp;&nbsp;&nbsp;&nbsp;| Description&nbsp;&nbsp;&nbsp;&nbsp; | 
|----------------------------------|--------------------------------|-------------------------------------|
| xcode cli                        | `xcode-select --install`       | Installs xcode CLI.                 |

<div align ="right"> <b><a href="#table-of-contents">⬆️ Back To Top</a></b></div>
    
 

<!-- ********************** Terminal END  ********************** -->
