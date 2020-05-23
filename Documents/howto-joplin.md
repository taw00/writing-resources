# Joplin, Writing Managed as a Project

Joplin is an end-to-end encrypted notebook manager that enables contextual storage of nearly anything: Documents, Images, Files, everything. Everything is structured as either a notebook (a folder) or a [markdown document](https://en.wikipedia.org/wiki/Markdown) (just like the document you are reading now). Non-markdown objects (images, files, etc) are attachments within markdown documents. Thus, everything retains context.

Joplin is my second brain. It's where I store all of my ideas, many of my draft documents, all of my staged blog posts. It's my creative dumping ground. It's also where I do a ton of drafting before moving to Google Docs or LibreOffice.

Check out the project website, [joplinapp.org](https://joplinapp.org/). Joplin is available for all platforms, but if you are a Fedora Linux user, there are native packages available [here (joplin-rpm)](https://github.com/taw00/joplin-rpm).

## Why Joplin?

These are the features that attracted me to Joplin:
* Your documents are formatted in [Markdown](https://en.wikipedia.org/wiki/Markdown). Nice and simple.
* It nicely previews the Markdown so you can see what a printout would look like, roughly.
* I can store to several different cloud storage services (I use Dropbox).
* It's all end-to-end encrypted.
* You can sync between desktop and mobile.
* Everything is organized in a notebook + notes format. And they can be hierarchical.
* You can edit everything directly within the application or use an external editor if you want to use advanced features like spellcheck and search and replace.

## How I Use Joplin

I'm not going to detail out how to use Joplin completely, but this is what I do as a writer. I build out a structure for each project that looks something like this:
* Project 1 - Story Title
  - 00 Manuscript  
    _<small>Where all the writing resides: scene by scene.</small>_
    - Act 1
      - Scene 1.1 - scene title (these are documents)
      - Scene 1.2 - scene title
      - Scene 1.3 - scene title
      - .&nbsp;.&nbsp;.
    - Act 2
      - Scene 2.1 - scene title
      - Scene 2.2 - scene title
      - .&nbsp;.&nbsp;.
    - Act 3
      - .&nbsp;.&nbsp;.
  - 01 Research
    - random things: images, documents, notes, etc.
  - 02 Outlines
    - Statements of theme (these are documents)
    - Premise
    - Plots and subplot summaries
    - Other documents associated to outlining
  - 03 Scene Cards  
    _<small>Scene by scene summary cards. Could conceivably combine with the written out scenes.</small>_
    - Act 1
      - Scene 1.1 (these are documents)
      - Scene 1.2
      - Scene 1.3
      - .&nbsp;.&nbsp;.
    - Etc.
  - 04 Characters
    - Protagonist - Name (these are documents)
    - Antagonist - Name
    - Role - Name
    - Role - Name
    - etc.
  - 05 Backstory
    - World building stuff (these are documents)
    - Extra character backstory
* Eventually the scenes development is completed until ready for outside review
* The text will be transfered to Google Docs or LibreOffice
* Final copies of the manuscript (LibreOffice or a Google Docs export) and PDFs will eventually land in the Project folder
* Query letters, everything, ends up in the Project folder. Everything from beginning to end. Probably with additional organizing Notebooks (folders).

Note that, even through Joplin retains an encrypted copy in Dropbox and an unencrypted copy locally, I regularly make `.jex` backups (of the whole Joplin deployment) and save a copy to the Keybase Filesystem in a private folder.
