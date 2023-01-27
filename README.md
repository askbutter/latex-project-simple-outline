# latex-project-simple-outline
This is a LaTeX file that can be used to define projects you are working on. Simple, not to be replaced with a Project Plan.
Edit spacing and customize however you would like!

# Features
1. Cover page
  * Project Title, Course information, Semester, Year, and to be fun include a picture of each group memeber.
2. Team Members
  * A table for the team members which includes their name, roles, and contact information.
3. Collaboration Tools
  * State your method of collaborations that will help your group communicate easier.
4. Overview of Project
  * Include a description of your project
5. Platform
  * Describe the software or hardware that your team plans to use.
6. Deliverables
  * Goal of the project

# Screenshots
<img src="https://github.com/askbutter/latex-project-simple-outline/blob/main/projectTeamLatex-1.png" width="500" height="650">
<img src="https://github.com/askbutter/latex-project-simple-outline/blob/main/projectTeamLatex-2.png" width="500" height="650">



# Install
Linux and emacs.

## Install Emacs

Command-line install (Ubuntu):
```
sudo apt-get install emacs
```

[Link to other Distribution Downloads](https://www.gnu.org/software/emacs/download.html)


## Install Latex
``` 
sudo apt-get install texlive-full
```

## Open a .tex files on emacs 

## Preview the PDF while you write:
1. Have MELPA package repository, if not include this in your init.el file
```(require 'package)
(add-to-list 'package-archives
     '("melpa" . "http://melpa.org/packages/") t)
(package-initialize)
```

2. Use m-x to enable
``` 
M-x latex-preview-pane-mode
```

or include this in your init.el file to have it load automatically
``` 
(latex-preview-pane-enable)
```

[Link to LaTeX Preview Pane Documentation](https://www.emacswiki.org/emacs/LaTeXPreviewPane)

# Credit
I used this website to help me put this document together:
https://www.overleaf.com/learn
