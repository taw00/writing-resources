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

I'm not going to detail out how to use Joplin completely, but this is what I do as a writer. I build out a structure for each project that looks something like this (you can also seem this in the notebook structure template I provide in [the Artifacts folder for Joplin](../Artifacts/Joplin/writing-projects-template/Writing Projects/!README.Writing Projects.md)):


#### Project 1, Novel — Saeculum
- !Artifacts

  Manuscripts

  Query Letters

  Final Versions

- 1.0 Manuscript
	- Act 1

	  Scene 1.1 — Burying a Body

	  Scene 1.2 — A Chance Encounter

	- Act 2

	  Scene 2.1 — Run!

	  Scene 2.1 — A Near Miss

	- Act 3

      Scene 3.x — Some scene title

      Scene 3.y — Some other scene title

- 1.1 Structure
	- 1.1.0 Outline

	  Themes and Premise

	  Synopsis

	  Three-act structure writeup, or .&nbsp;.&nbsp;.

	  Seven-point storty structure, or .&nbsp;.&nbsp;.

	  Save the Cat beats, or .&nbsp;.&nbsp;.

	  The Snowflake progressive story expansion, or .&nbsp;.&nbsp;.

      Plot Diagrams and Freytag Triangles, or .&nbsp;.&nbsp;.

      .&nbsp;.&nbsp;.

	- 1.1.1 Scene Cards
		- Act 1

		  Scene Card 1.1 — Burying a Body

	      Scene Card 1.2 — A Chance Encounter (inciting incident)

		- Act 2

	      Scene Card 2.1 — Run!

	      Scene Card 2.1 — A Near Miss (midpoint)

		- Act 3

          Scene Card 3.x — Some scene title

          Scene Card 3.y — Some other scene title

          Scene Card 3.z — They Lived Happily Ever After

- 1.2 Research and Notes
- ~Trash and Archive

* `Project 1` actually lives (is a sub-notebook) within a notebook called `Writing Projects` and Project 1 is just one project in that notebook.
* Eventually the scenes development is completed until ready for outside review
* The text will be transferred to Google Docs or LibreOffice
* Final copies of the manuscript (LibreOffice or a Google Docs export) and PDFs, query letters, and any other artifacts of the project will eventually land in the Project 1 notebook in the !Artifacts folder (sub-notebook)

Note that, even through Joplin retains an encrypted copy in Dropbox and an unencrypted copy locally, I regularly make `.jex` backups of the whole Joplin deployment and save a copy of that to the Keybase Filesystem in a private folder: File > Export > JEX - Joplin Export File.
