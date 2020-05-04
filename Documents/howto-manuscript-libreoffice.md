# LibreOffice for Manuscript Formatting and development

#### Relevant artifacts

_Templates_
- `Manuscript, Short Story.ott`
- `Manuscript, Novel.ott`

_Examples_
- `libreoffice-manuscript-short-story-example.odt` and  
  `libreoffice-manuscript-short-story-example.pdf`
- `libreoffice-manuscript-novel-example.odt` and  
  `libreoffice-manuscript-novel-example.pdf`

# LibreOffice Templates

Included here are some LibreOffice Templates for both the short story and novel.

## Manuscript templates (for submissions)

### The templates:

Install the templates into `~/Templates` (Fedora Linux), and they will then be available for use.  

* [Manuscript, Novel.ott]
* [Manuscript, Short Story.ott]

> _(Note: The default template location is set in LibreOffice in Tools > Options
> LibreOffice > Paths. If your preferred location is not there, add it at the
> end of a path with `;/home/username/Templates` as an example)_


### Examples:

Install the above templates first, then open these in LibreOffice.

Short Story example
* ODT: [libreoffice-manuscript-novel-example.odt]()
* PDF: [libreoffice-manuscript-novel-example.pdf]()
Novel example
* ODT: [libreoffice-manuscript-short-story-example.odt]()
* PDF: [libreoffice-manuscript-short-story-example.pdf]()

Read carefully the comments. There are a couple things you need to know:
1. Most Novel/Story styles are listed under two parent styles in the "Styles
   and Formatting" manager widget: `Styles > Manage Styles(F11)`. Look for
   `Heading > Novel|Story Heading` and `Novel|Story Special-Cased Text`
2. Review the styles in use: `Frontmatter` and `Frontmatter, footer`; `Title`;
   `ByLine`; `Default Style` and `Default Style, noindent`; `Part`; `Chapter`
   and `Chapter, nonbreaking`; `Scene`; `Subscene`
   - `Part` and `Chapter` will start a new page and pad 2 inches from the top.
   - `Chapter, nonbreaking` will not start a new page and pad 2 inches. It is
     used if you want to create a chapter header right after a `Part`. You
     don't want to create two pages. In that case. See my example with Part 1 and I.
     (a Chapter).
   - `Part`; `Chapter` and `Chapter, nonbreaking`; `Scene` and `Subscene` will
     create a `Default Style, noindent` paragraph as soon as you hit enter.
     Traditionally, there is no indent after one of those header elements. And then
     all the rest of the paragraphs should be merely `Default Style` which does
     auto-indent.
3. Font: _TexGyreTermes_ is the default. The fonts are embedded in the examples and the templates, but install the fonts on your system: `sudo dnf install texlive-tex-gyre -y`  
   _Liberation Serif_ is another _Times New Roman_ -type font, but
   _TexGyreTermes_ is, IMHO, a better option. I will talk about fonts more
   elsewhere.  
   Fonts are set in _Tools_ > _Options_ > _LibreOffice Writer_ > _Basic Fonts (Wester)__
4. Note how the Fields are used to populate a lot of the metadata for the document. There are three primary places that metadata are stored:
   - _Tools_ > _Options_ > _LibreOffice_ > _User Data_
   - _File_ > _Properties_ > . . .
     - _File_ > _Properties_ > _General_ > [press Reset Properties] — press that when you change the name in the _User Data_ above.
     - _File_ > _Properties_ > _Description_
   - Fields: CTRL-F2 _-or-_ _Insert_ > _Fields_ > _More Fields_  — Customized fields include:
     - AddressLine1 and AddressCityStateZip
     - Phone and EmailAddress
     - DateMMMMYYYY
     - PenName (used for the byline)
     - PenNameCoAuthor (I didn't provide an example, but you can figure it out)
     - WordCount
     - Audience and Genre
     - DocumentVersion string
     - Surname and RunningTitle (for the header, a shorter title)
     - Thirty (the "The End" string)
5. The trickiest bit: If you mess with that first Part 1 the wrong way, you
   will end up with the wrong page number in the header. I can't explain it,
   but you will just have to be careful and backout any mistakes and try again.

That should get you started. Make a copy and play with the format. It should be relatively straight forward.

---
---

## Publish-ready templates (for self-publishing)

I don't have published book ebook and ePub templates yet.
