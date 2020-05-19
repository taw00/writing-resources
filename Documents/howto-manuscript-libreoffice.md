# Using LibreOffice for Manuscript Formatting and Development

LibreOffice works well for manuscript submission. It can track changes and save to .docx or .odt, two formats that most publishing houses accept and prefer.

### Relevant artifacts

_Templates_
- Short Story: [manuscript-short-story.ott](../Artifacts/LibreOffice/manuscript-short-story.ott)
- Novel: [manuscript-novel.ott](../Artifacts/LibreOffice/manuscript-novel.ott)

_Example documents based on those templates_  

&emsp;Short Story example
* ODT: [libreoffice-manuscript-novel-example.odt](../Artifacts/LibreOffice/libreoffice-manuscript-novel-example.odt)
* PDF: [libreoffice-manuscript-novel-example.pdf](../Artifacts/LibreOffice/libreoffice-manuscript-novel-example.pdf)

&emsp;Novel example
* ODT: [libreoffice-manuscript-short-story-example.odt](../Artifacts/LibreOffice/libreoffice-manuscript-short-story-example.odt)
* PDF: [libreoffice-manuscript-short-story-example.pdf](../Artifacts/LibreOffice/libreoffice-manuscript-short-story-example.pdf)

## The LibreOffice Templates

The templates relatively closely follow William Shunn's excellent formatting guidance which can be found here: <https://format.ms/story>, or here: <https://www.shunn.net/format/story/>.

Just copy the `.ott` files into your `$HOME/Templates/` directory (Fedora Linux's default location, your system defaults may vary) and restart LibreOffice.

The templates should be now listed all options in File > Templates in LibreOffice. In this case they will be listed as `Manuscript, Novel` and `Manuscript, Short Story`.

If you don't see the templates listed, check your template paths setting in Tools > Options > LibreOffice > Paths.

## Starting a new manuscript

File > New > Templates&nbsp;.&nbsp;.&nbsp;. and then select which template you want to use.

You can also do the same from File > Templates > Manage > double-click on desired template&nbsp;.&nbsp;.&nbsp;.

Save the document to something other than Untitled. Maybe in the common format of `YOURLASTNAME-SHORTTITLE.odt` or `YOURLASTNAME.SHORTTITLE.odt`

## Starting a new manuscript but from an existing document

Follow the "new manuscript instructions" above and then you will have to do some brute force cutting and pasting into the document from your other document. There is no way around this. Even if your existing story is saved as a LibreOffice document, there is no way to select a template and then apply it to the existing document. You have to start fresh and cut and paste into it. It's really not that bad. Just tedious.

## Using the templates

First make sure the style panel is open (usually on the right). F11 or View > Styles is how you make sure it is open.

Next open the Navigator panel (F5 or View > Navigator). If it is not on the right side, dock it there by dragging the window to a place next to the Styles panel.

**The relevant customized styles**
* _Headings_ > .&nbsp;.&nbsp;.
  - Title
  - _Novel|Story Headings_ > .&nbsp;.&nbsp;.
    - ByLine
    - Chapter and Chapter, nonbreaking
    - Part
    - Scene
    - Subscene
    - Thirty
* Text Body > .&nbsp;.&nbsp;.
  - First Line indent
  - _Novel|Story Additional Text styles_ > .&nbsp;.&nbsp;.
    - Frontmatter
    - Frontmatter, footer


**Fonts**

The template and example LibreOffice Writer documents have the TeX Gyre Termes font embedded in them. Or should. Regardless, make sure that font is installed: `sudo dnf install texlive-tex-gyre -y`

That should be enough for you go get started. Save often. If an editor asks you to submit a `.docx` file, ask if they'll take an `.odt` instead. They will likely say yes. If not, just convert it to `.docx` when you submit it: File > Save As... > change document type to 'Word 2007-365 (.docx)' and Save.  If you want to create a PDF for beta-readers and whatnot, File > Export As > Export as PDF.

Good luck!
