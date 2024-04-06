# On Fonts and Typography for Writers

### TL;DR

##### Typefaces for …

1. **Drafts:** use whatever font you like.
2. **Developmental manuscripts:**
   - *narrative prose and poetry:* some readable Times serif New Roman-like typeface.
   - *non-narrative prose:* some readable sans-serif Arial-like typeface
   - *screenplays:* a typeface that matches Courier's metrics precisely. This is a strict rule.
3. **Submitted manuscripts:** Times New Roman, Arial/Helvetica/Calibri, Courier for the categories above, -OR- whatever the agent or publisher demands in their submission guidlines.

##### What about …

- **Alternatives to those proprietary fonts:** See below. And only choose those typefaces for drafts, developmental manuscripts, or submissions that allow them.
- **Installing those proprietary fonts on linux:** Google it. It's simple, and Microsoft allows it, apparently. (They didn't for the longest time.)
- **Recommendations for wordy websites?** See below.

### Settling on a set of fonts for a project is hard

There are a zillion different fonts to choose from. Each has their own personality, vibe, _feel_. Fonts are nuanced. Something that wows on screen can disappoint on the page. A font that looks amazing on the printed page can make a web page look stilted. Fonts that look great in small doses, look mediocre once viewed as a page full of text. And some fonts make great headers but are terrible in the text body.

We have all wasted countless hours trying one font, then another, and then another. The more look-and-feel is important to a project, the more difficult the choice. The more permanent selection—for example, with printed material—the choice becomes truly challenging.

The purpose of this document is to discuss the typeface (font) needs for the writer. Font selection in the general sense will be touched upon, but that is a large topic and will not be fully explored here. Therefore, we will not be, for example, focusing on the needs of the advertiser, designer, or graphic artist. It could be argued that the real discussion should surround _typography_ more than merely _fonts_ but .&nbsp;.&nbsp;. well, I talk mostly about fonts. Read more about typography here: <https://practicaltypography.com/typography-in-ten-minutes.html>.

_**Developmental writing**_

When it comes to developmental writing in the earliest stages, the choice of font becomes relatively easy: use whatever you like. For example, I'm writing this document using a text editor. The typeface is Courier Prime, a monospaced font. Last week I was using Victor Mono, another monospaced font with some fancy flourishes when words are italicized.

_**Submission**_

Once past the developmental stages, if going the traditional publishing route (literary journals, magazines, book publishers), we writers cobble everything together and prep for submission. In this case, the work needs to be initially put into a generalized manuscript form. For that, the very best guidelines, IMHO, can be found on writer William Shunn's website here: [www.shunn.net/format/](https://www.shunn.net/format/). I have reviewed a zillion sites and his is, hands-down, the best.

So, get your document into manuscript form. The font? The font selection becomes even easier: **Times New Roman**. Now, this initial document (before you look at submission guidelines) can be any font you like, but my recommendation is to cave to convention and format it in Times New Roman. It's proprietary, but it is what the industry expects. And if you are submitting to a third party, you need to give them what they demand.

*A write-to-completion tip:* Everything I write I write to completion, whether I submit it or not, I eventually format it in such a way. It is good practice to file all of your work for posterity in a completed state. I also print it out and file the hardcopy away as well. Electrons are ephemeral; paper is forever.

> Note, Shunn's site focuses on narrative prose and poetry. For non-narrative non-fiction, the guidelines can be different. Some Arial-like sans-serif typeface is generally accepted, though, again, Times New Roman is always a safe bet if they give you no guidelines. I don't have a lot of experience with non-narrative prose in the submissions process.

> The screenplay standards are strict. You screenplay is _required_ to use a typeface that is metrically identical to Courier. Not Courier New, but Courier. But Courier is dated. Instead use *[Courier Prime](https://johnaugust.com/2013/introducing-courier-prime)*, and if your prefer (and they allow), *Courier Prime Sans*. Courier Prime is a safe bet and the industry has embraced it. (If you use the programs Fade In or Final Draft to write your screenplay, their own versions of Courier also meet the spec.) And that is all I am going to say about screenplays now.

Okay. You have a manuscript. It's submission time!

For this process, it's now time to review an agent's or a publisher's submission guidelines for how they expect the manuscript to be formatted. Usually they simply ask for it to be in a conventional manuscript format, 12pt Times New Roman, double-spaced, and sent to them as a `.docx` file (formatted for Microsoft Word). Publishers are becoming more flexible though and they may simply as that it be in some standard manuscript format, any professional serif or sans-serif typeface, and sent as a `.docx` or `.odt` file. But you can't go wrong with, especially until you are established as a writer, `.docx` and Times New Roman for your final output.

_**Self-Publishing**_

If you self-publishing (printed, ebook, epub, or blog), your choice of font (or set of fonts) widens and needs to match the overall design of the book, publication, or website. Book content design is an entire subject unto itself that I will not go into here. Maybe I will at some later date, but great typeface choices for body-text are in the families of: Garamond, Goudy, Crimson Text, Sabon, Utopia, Merriweather, Minion Pro, Palantino. See below for excellent, unencumbered, options.


### But! But! Linux doesn't supply Times New Roman!

The short answer/solution: if you are on a platform that does not have Times New Roman installed, just do an internet search for how to install it and do it today.

For example, as of Fedora Linux 39, you need to do this:
```
sudo dnf install curl cabextract xorg-x11-font-utils fontconfig -y
sudo rpm -i https://downloads.sourceforge.net/project/mscorefonts2/rpms/msttcore-fonts-installer-2.6-1.noarch.rpm
```

Linux users don't typically have the name-brand fonts installed (Times New Roman, Courier, Arial/Helvetica/Calibri). In fact, for a very long time, the selection of fonts available to the open source world were very limited, and none that looked particularly great on both the screen _and_ the page. The Linux desktop used to be full of usable, but unattractively grainy, fonts that served as poor substitutes for fonts provided by the proprietary world of Apple and Microsoft.

Boy things have changed!

Open source dominates all platforms now: mobile, web, servers, and even the the proprietary desktops of the world (Apple and Microsoft). The desire for _open everything_, the availability of font design tools, and strategic corporate sponsorship has led to a blossoming of open source fonts. And on top of the list are fonts that can serve as drop-in replacements (metrically compatible) for, you guessed it, Times New Roman, Courier, Arial, Helvetica, and Calibri. Feel free to use these mimics in place of the proprietary typefaces until you are forced to do otherwise but a particular publisher or agent.

And so, today, the available variety of fonts is vast and of high quality. Especially in support of latin-based languages. (*If you have to support a breadth of character types, check out the Noto family of typefaces.*)

For linux, many fonts are available as packaged items&nbsp;.&nbsp;.&nbsp;.

> * In the Gnome desktop, open the _Software_ application (gnome-software)
> * Scroll towards the bottom and in "Other categories" there should be a button labeled "Fonts". Click that.
> * At the time of this writing (December 29, 2023 and Fedora Linux 39), I count nearly 300 fonts available.

But even more can be found at or [Open Font Library](https://fontlibrary.org/), [Google Fonts](https://fonts.google.com), [dafont](https://www.dafont.com), and [FontSquirrel](https://fontsquirrel.com).

And with that said, Times New Roman—and Courier and Arial and the rest—have open alternatives that, I would argue, are just as mature and effective today as the ones they emulate. Some reasonable alternatives are listed in the next section below.


## The Fonts I Use

> **Spoiler alert!**
>
> This is a long article just to say that nine times out of ten, given no other guidance, you want to choose **Times New Roman** for narrative and poetry works when submitting your work. And for the draft and revision process, use whatever you want.

There are alternative typefaces out there that nicely mimic the proprietary fonts. I often use these for my manuscripts that store away until forced to comply to some standard from a publisher. Here are those fonts …
**LibreOffice, Google Docs, or even MS Word**
* _Manuscript-standard (Times New Roman) mimics (12pt. always)_
  - Text body: Croscore Tinos, TeX Gyre Termes, or Liberation Serif
  - Heading and Frontmatter (story facts): Surprise! Use the same font for everything.
* _San-Serif mimics_
  - Arial: Croscore Arimo, Liberation Sans
  - Helvetica: TeX Gyre Heros
  - Calibri: Crosextra Carlito
* _Screenplay-standard mimics_
  - Courier (monospace): Courier Prime, TeX Gyre Cursor, Nimbus Mono PS, or Noto Mono. For a Courier-like, but more "sans-serif" experience, check out Courier Prime Sans, Courier Prime Code, or Croscore Cousine.

**For Self-publishing, some of my choices are&nbsp;.&nbsp;.&nbsp;.**
  - Text body: EB Garamond, Cormorant Garamand Medium, Cardo (11pt), Libre Caslon Text (10pt), or Crimson Text or Crimson Pro
  - Headings: Fira Sans Book, TeX Gyre Pagella (Palantino-like), Overpass, Crosextra Carlito, Montserrat, or Avería Sans/Serif Libre (the Avería fonts are almost too unique).

**For the web**  
I didn't really talk much about website typefaces, but I maintain three websites using these fonts (they change a bit frequently):

1. <!--tf-->Text: Cardo and Fira Mono / Headings: Fira Sans Book
2. <!--tr-->Text: Crimson Pro and Fira Mono / Headings: Fira Sans Book
3. <!--er-->Text: Libre Caslon Text and Fira Mono / Headings: Avería Sans Libre<br />
   Used for select blog posts (non-inclusive): Chilanka, Fira Sans Book, Crimson Pro, Croscore Cursor, Overpass, Overpass Mono

**Installation of some of these on Fedora Linux 39**
```
# TeX Gyre Termes, TeX Gyre Cursor, TeX Gyre Heros, and more
# Croscore Tinos, Croscore Cousine, Croscore Arimo, Crosextra fonts, and more
# Liberation Serif, Liberation Sans, Nimbus Mono PS, Noto Mono, and more
sudo dnf install texlive-tex-gyre* google-croscore-* google-crosextra-* google-noto-* liberation-* urw-*-nimbus-*
```



<!--

> We could stop right there for the purposes of putting together a manuscript, but, for those who want to explore some of the other fonts out there, read on. There is a whole world of nuanced fonts for publishing, whether that be to the web (blog posts and such) or print.

---

## More Artful Fonts for Publication and Presentation

For print and ebook publication, and content-heavy websites, you may want something more nuanced than Times New Roman. You may also want to start considering different fonts for different purposes (font pairings): headers, text body, quotations and asides, etc.

That being said, unless you really really need to make a particular statement, stick to fonts that are relatively subdued in how much they diverge from the norm rather than choosing something boldly different or bizarre. One of the most commonly cited criticism of poorly designed self-published books is that authors sometimes pick really distracting fonts. Don't do that. Err on the side of pragmatism.

### Font categories and some associated fonts

At a high level, this is how fonts are categorized.

> _<span style="font-size: 75%;">Note: I assuming a baseline font size of 12pt compared to the standard set of fonts. I annotate a pt change where I think it is appropriate for that particular font to behave similarly to the standard fonts. You may have to adjust up or down depending on how the font looks on the page or website.</span>_

#### Serif (aka Roman)

The fonts that have little decorative things at the end of the strokes used to draw them. In theory—and there is some modest science to back this claim—serif fonts are easier to read. On the printed page at least. More often than not, they are more aesthetically pleasing.

_Proportional_ — Each character takes up space that is complementary to that characters form. An _M_ will take up more horizontal space than an _I_.

_Monospace_ — Each character takes up precisely the same amount of space as any other character.

> I've ❤_highlighted_ some of my favorite fonts. It should be noted that Latin Modern fonts look reasonable on screen, but truly shine as printed fonts. Many fonts are better screen fonts than print fonts, and vice versa. Experiment!

> ***Installation of these fonts will be discussed at the end of this document.***

_**Proportional Serif fonts**_

<div style="font-size: 75%;">

| Metrically Compatable<br/><span style="font-size: 75%;">to Times New Roman</span> | Other Serif<br/><span style="font-size: 75%;">like Constantia, Georgia, Palantino, etc.</span> |  |
| -- | -- | -- |
| FreeSerif | Accanthis ADF Std | ❤ _Garamond (Cormorant Garamond)_<br/><span style="font-size: 50%;">(medium version for text body)</span> |
| ❤ _Liberation Serif_ | ❤ _Avería Serif Libre (11pt)_<br/><span style="font-size: 50%;">(light version for text body)</span> | ❤ _Garamond (EB Garamond)_<br/><span style="font-size: 50%;">(EB Garamond 12 for text body)</span> |
| Nimbus Roman | Baskerville (10pt)<br/><span style="font-size: 50%;">(Libre Baskerville)</span> | Gelasio<br/><span style="font-size: 50%;">(Georgia clone)</span> |
| ❤ _Termes (TeX Gyre Termes)_ | Bonum (TeX Gyre Bonum)<br/><span style="font-size: 50%;">(Bookman-like)</span> | Goudy Bookletter 1911 |
| ❤ _Tinos (Croscore Tinos)_ | ❤ _Caslon (10pt)_<br/><span style="font-size: 50%;">(Libre Caslon Text)</span> | Latin Modern Roman |
| | ❤ _Cardo (11pt)_ | Merriweather |
| | Cormorant Infant Medium | Pagella (TeX Gyre Pagella)<br/><span style="font-size: 50%;">(like Palantino)</span> |
| | ❤ _Crimson Pro_ | Schola (TeX Gyre Schola, 11pt)<br/><span style="font-size: 50%;">(like Century Schoolbook)</span> |
| |  | Source Serif Pro |

</div>

_**Monospace Serif fonts**_

> Note: many monospaced fonts are serif-ish or sans-serif-ish or somewhere in between. Many applications lump them all together and label them "monospaced" for this reason.

<div style="font-size: 75%;">

| Metrically Compatable<br/><span style="font-size: 75%;">to Courier</span> | Other Mono-Serif<br/>&nbsp; |
| -- | -- |
| ❤ _Cursor (TeX Gyre Cursor)_ | ❤ _Anonymous Pro_ |
| | | |
| Nimbus Mono PS | | |
| Noto Mono  |  | |

</div>

Serif fonts can be further classified: Old-style, Transitional, Didone, Slab serif, and more. We won't discuss such nuance here.

#### Sans Serif

Fonts that are literally _sans_, or without, serif. They don't have extra decorators at the end of the stokes that define them. They can, TeX Gyre Schola (Century Schoolbook-like) be, similarly to serif fonts, proportional or monospace.

> For print, sans-serif fonts are best used for headers or blocks of specialized text mixed in with serif text. In this way the sans-serif text acts as a complementary but differentiating typeface.

_**Proportional sans-serif fonts**_

<div style="font-size: 75%;">

| Metrically Compatable<br/><span style="font-size: 75%;">to Arial</span> | Other Sans Serif<br/><span style="font-size: 75%;">like Calibri, Helvetica, etc.</span> |  |
| -- | -- | -- |
| ❤ _Arimo (Croscore Arimo)_ | Adventor (TeX Gyre Adventor)<br/><span style="font-size: 50%;">(like Avant Garde Gothic)</span> | ❤ _Montserrat_ |
| Liberation Sans | ❤ _Avería Sans Libre_ | ❤ _Overpass_ |
| Nimbus Sans | ❤ _Carlito (Crosextra Carlito)_<br/><span style="font-size: 50%;">(like Calibri)</span> | ❤ _Quicksand_ |
| Noto Sans | ❤ _Heros (TeX Gyre Heros)_<br/><span style="font-size: 50%;">(like Helvetica)<span> |  |
|  | ❤ _Fira Sans Book_ | Tiresias<br/><span style="font-size: 50%;">(for the visually impaired)</span> |
|   | Fira Sans Light | Andika<br/><span style="font-size: 50%;">(for beginning readers)</span> |

</div>

_**Monospace sans-serif fonts**_

> Note: many monospaced fonts are sans-serif-ish or serif-ish. You could lump them all together and judged them as something in between.

<div style="font-size: 75%;">

| Metrically Compatable<br/><span style="font-size: 75%;">to Courier (but Sans)</span> | Other Mono Sans<br/><span style="font-size: 75%;">like Menlo, SF Mono, Consolas, etc.</span> |
| -- | -- |
| Cousine<br/><span style="font-size: 50%;">(Croscore family)</span> | Comfortaa |
| DejaVu Sans Mono | ❤ _Fira Mono_ |
| Droid Sans Mono | ❤ _Overpass Mono_ |
| ❤ _Liberation Mono_ | Inconsolata<br/><span style="font-size: 50%;">(like Consolas)</span> |
| Noto Sans Mono |  |
| ❤ _Source Code Pro_ | |

</div>

#### [Cursive Script](https://en.wikipedia.org/wiki/List_of_typefaces#Script), Fancy, Brush, Calligraphic, Handwriting, Other

Cursive. There's a whole group of fonts that mimic hand-printed text, scripted text, and calligraphy. These fall into what some call the "cursive" font grouping. It's a terrible category name, but it hints at what may be included.

_**Cursive examples:**_  
TeX Gyre Choral (Zapf Chancery-like), Architects Daughter, Steve Hand, SMonohand, Grand Hotel, Serafettin Cartoon, Isabella, Chilanka, Blokletters Viltstift (Comic Sans-like)

Other character fonts. There a lot of subcategories that I am not going to spell out, but for now we'll call them "other." Art decco, block-characters .&nbsp;.&nbsp;. all those characters that are text but very specialized and not organic (hand-written).

_**Other character fonts examples:**_  
Cormorant Unicase, Comorant SC, .&nbsp;.&nbsp;.

Symbols. Glyphs and images that aren't letters. Emoji. Dingbats. And more. Useful for [separators and flourishes between scenes and things](https://www.thebookdesigner.com/2010/06/book-design-8-solutions-to-the-text-break-dilemma/) in stories and books. I'll let you find these on your own. :)

## Whew!

In conclusion, once you have whittled down the fonts that interest you&nbsp;.&nbsp;.&nbsp;.
* Keep the number of fonts to a minimum
  - For a manuscript (submission), and with no other guidance from the editor, use only a single font (a Times New Roman equivalent) is ideal.
  - For books and websites (published), use _at most_ two or three complementary fonts. Check out this [font pairing website](https://fontpair.co/) for ideas and inspiration.
* Test your fonts
  - For a manuscript, print a handful of pages for each candidate font and look at them and consider: Does the font disappear from my attention when I read the page? Is it easy to read? Print a 12pt Times New Roman comparable and make sure the font size is roughly the same and the double-spacing for each are adequate.
  - For a book, print out a handful of pages for each candidate font and compare them to books from your bookshelf. Again, are they attractive _and_ non-distracting? Does the tone of each font fit the genre of your writing? What do other books in your genre use for their fonts, both headings and body text? And don't forget to compare your frontmatter with the frontmatter of other books.
  - For a webpage, deploy your font selection and then zoom in and out, stretch the window, make it tall, print the webpage. What happens?

-->

&nbsp;  
Fonts can lead you down a path of darkness and sorrow. Be careful out there. Just make sure you are happy with the fonts you have chosen. Good luck!

—Todd Warner <todd@errantruminant.com>



---
---

## <center>Addendum</center>

### Where to find certain fonts and how to install them

#### The core metrically compatible fonts

**Desktop installation (as described previously):**
```
# TeX Gyre Termes, TeX Gyre Cursor, TeX Gyre Heros, and more
# Croscore Tinos, Croscore Cousine, Croscore Arimo, Crosextra fonts, and more
# Liberation Serif, Liberation Sans, Nimbus Mono PS, Noto Mono, and more
sudo dnf install texlive-tex-gyre* google-croscore-* google-crosextra-* google-noto-* liberation-* urw-*-nimbus-*
```

**Website availability:**

All but the TeX fonts are easy to use for any website. Just use [Google Fonts](https://fonts.google.com/) or [Open Font Library](https://fontlibrary.org/). Please note that the CSS for the liberation fonts as configured by Open Font Library made them relatively inflexible. I redid the CSS and include it here for your convenience.

```
<!-- HTML -->
<!-- liberation sans and serif -->
<link rel="stylesheet" media="screen" href="https://raw.githubusercontent.com/taw00/writing-resources/master/Artifacts/css/toddwarner-font-sans-liberation.css" type="text/css"/>
<link rel="stylesheet" media="screen" href="https://raw.githubusercontent.com/taw00/writing-resources/master/Artifacts/css/toddwarner-font-serif-liberation.css" type="text/css"/>
<!-- Tinos (a Croscore font) -->
<link href="https://fonts.googleapis.com/css2?family=Tinos:ital,wght@0,400;0,700;1,400;1,700&display=swap" rel="stylesheet">
```

Or . . .

```
/* CSS */
/* liberation sans and serif */
@import url("https://raw.githubusercontent.com/taw00/writing-resources/master/Artifacts/css/toddwarner-font-sans-liberation.css");
@import url("https://raw.githubusercontent.com/taw00/writing-resources/master/Artifacts/css/toddwarner-font-serif-liberation.css");
/* Tinos (a Croscore font) */
@import url("https://fonts.googleapis.com/css2?family=Tinos:ital,wght@0,400;0,700;1,400;1,700&display=swap");
```

Example configuration (web):
```
/* CSS */
p, .libserif {
  font-family: 'Liberation Serif', serif;
}

.tinosserif {
  font-family: 'Tinos', serif;
}
```

I leave it to the reader to figure out the rest. Most of the other fonts can be installed similarly. I will mention a couple others where there may be more too it than that.

<!--

#### Fira

There are two major forks of Fira and a third future Fira. All this is confusing. The Fira that is canonical is [Mozilla's Fira](https://github.com/mozilla/Fira). [bBoxType's Fira](https://github.com/bBoxType/FiraSans) is somehow a smidge different and should be avoided, IMHO (controversy?). But bBoxType is working on something called [FiraGO](https://github.com/bBoxType/FiraGO), but it is no where near completion so .&nbsp;.&nbsp;. Anyway. Just use Mozilla's Fira and maybe Tonsky's Fira Code extension of Fira Mono. They can easily be utilized on the desktop via supplied OS packages and on the web via Mozilla and Tonksy directly, Google Fonts, or FontSquirrel

Direct from source (only if your OS can't supply them):
* Sans and Mono: https://github.com/mozilla/Fira
* Code: https://github.com/tonsky/FiraCode

Google and FontSquirrel (only if your OS can't supply them):
* Sans: https://fonts.google.com/specimen/Fira+Sans
* Mono: https://fonts.google.com/specimen/Fira+Mono
* Code: https://fonts.google.com/specimen/Fira+Code
* Sans: https://www.fontsquirrel.com/fonts/fira-sans
* Mono: https://www.fontsquirrel.com/fonts/fira-mono
* Code: https://www.fontsquirrel.com/fonts/fira-code

**Desktop installation:**
```
# Fira Sans, Mono and Code
sudo dnf install fira-code-fonts mozilla-fira-*
```

**Web availability (add to your HTML or CSS):**
```
-->
<!-- HTML -->
<!--
<link rel="stylesheet" href="https://code.cdn.mozilla.net/fonts/fira.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/tonsky/FiraCode@3/distr/fira_code.css">
```

Or . . .

```
/* CSS */
@import url(https://code.cdn.mozilla.net/fonts/fira.css);
@import url(https://cdn.jsdelivr.net/gh/tonsky/FiraCode@3/distr/fira_code.css);
```

Example configuration (web):
```
p { font-family: 'Fira Sans', sans-serif; }
code { font-family: 'Fira Code', monospace; }
@supports (font-variation-settings: normal) {
  code { font-family: 'Fira Code VF', monospace; }
}
```

Or, if you are like me, and on a webpage you prefer straight-up Fira Mono:
```
p { font-family: 'Fira Sans', sans-serif; }
code { font-family: 'Fira Mono', monospace; }
```

-->

#### Cardo

You can get old versions of Cardo from Google and FontSquirrel but there is a newer version at the designer's website. It hasn't been updated since 2011 so .&nbsp;.&nbsp;. the designer may have abandoned it or die or something. Regardless, I like the font.

**For Desktop:**
* Download the font from http://www.scholarsfonts.net/cardofnt.html
* Then ...  
  ```
  cd ~/.fonts/
  mkdir cardo ; cd cardo
  mv ~/Download/cardo104.zip ./
  unzip *.zip
  rm Cardoi99.ttf Cardob101.ttf
  fc-cache -vfr
  ```

**For the web:**  
_Just use the dated Google fonts. They are not noticeably different to me._

```
<!-- HTML -->
<link href="https://fonts.googleapis.com/css2?family=Cardo:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
```

Or . . .

```
/* CSS */
@import url('https://fonts.googleapis.com/css2?family=Cardo:ital,wght@0,400;0,700;1,400&display=swap');
```

Example configuration (web):
```
/* CSS */
p { font-family: Cardo, serif; }
```

#### Avería

Avería is a wickedly cool set of fonts. [The designer][averiawebsite] essentially developed the fonts by averaging many popular fonts and .&nbsp;.&nbsp;. boom! Avería was born. It makes for a smooshy, but attractive print that looks good for many things, but will not be right for all projects. I particularly like the font for headings, though for text it looks interesting as well.

[averiawebsite]: http://iotic.com/averia/ "Designer's Website for Avería"

**For Desktop:**
* Download the fonts from https://fonts.google.com/specimen/Averia+Serif+Libre and https://fonts.google.com/specimen/Averia+Sans+Libre
* Then ...  
  ```
  cd ~/.fonts/
  mkdir averia ; cd averia
  mkdir serif sans
  mv ~/Download/Averia_Serif_Libre.zip ./serif/
  mv ~/Download/Averia_Sans_Libre.zip ./sans/
  unzip ./serif/Averia_Serif_Libre.zip  -d ./serif/
  unzip ./sans/Averia_Sans_Libre.zip  -d ./sans/
  fc-cache -vfr
  ```

**For the web:**  

```
<!-- HTML -->
<link href="https://fonts.googleapis.com/css2?family=Averia+Serif+Libre:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Averia+Sans+Libre:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap" rel="stylesheet">
```

Or . . .

```
/* CSS */
@import url('https://fonts.googleapis.com/css2?family=Averia+Serif+Libre:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Averia+Sans+Libre:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap');
```

Example configuration (web):
```
/* CSS */
h1, h2, h3, h4, h5, h6 { font-family: 'Averia Sans Libre', sans-serif; }
p { font-family: 'Averia Serif Libre', serif; }
```

The fonts can also be found here: [serif](https://fontlibrary.org/face/averia-serif) and [sans serif](https://fontlibrary.org/face/averia-sans)

---

Resources

* All about the font formats used on the web: [The Missing Guide to Font Formats: TTF, OTF, WOFF, WOFF2, EOT, and SVG](https://creativemarket.com/blog/the-missing-guide-to-font-formats). WARNING: The font compatibility chart is significantly out of date. Instead use this one .&nbsp;.&nbsp;.
* [Webfont and Browser Combatibility Chart](https://transfonter.org/formats). And here's another one by good folks at Mozilla: [The Web Open Font Format (WOFF)](https://developer.mozilla.org/en-US/docs/Web/Guide/WOFF)
* Butterick, Matthew. Publishing date unknown (2018?). _Practical Typography._ [practicaltypography.com](https://practicaltypography.com/). Accessed, May 24, 2020.
