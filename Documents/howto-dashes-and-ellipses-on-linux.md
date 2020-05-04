# Dashes and Spaces and Ellipses

There are certain characters that writers use all the time but aren't readily available on the keyboard. These include the various dashes (&hyphen; &minus; - &ndash; &mdash; &#x2E3A; &#x2E3B;) and the ellipses (… .&nbsp;.&nbsp;.) and several specialized spaces.

> **When writing fiction in particular, we use the em dash (&mdash;) and the [chicago-style](https://www.chicagomanualofstyle.org/) open ellipsis (.&nbsp;.&nbsp;.) a lot!**

In order to make my writing easier I have configured my Fedora Linux desktop so that I can simply hit a simple key combination and BAM! there's the dash or ellipsis or specialized space I need.

Let me show you how I configured my system to do this. The end goal will be to:
1. Enable the _Compose Key_
   - The _Compose Key_ allows you to type many international characters, but importantly for us, the **em dash and the en dash**.
2. Configure the AutoKey application
   - AutoKey runs in the background and enables user defined hotkeys and shortcuts to do just about anything. In our case, we will use it to be able easily type **ellipses and special spaces**.
3. Briefly introduce the `[CTRL-SHIFT-U]` key sequence used to input any unicode character.

---

## Install the Gnome Tweaks and AutoKey Applications

Before we do anything else, we need to install two packages: `gnome-tweaks` and `autokey-gtk`. Of course, Fedora (and any modern Linux) makes this easy.

Install from the desktop UI:
1. Open the "Software" application
2. Search for "GNOME Tweaks"
3. Install
2. Search for "AutoKey"
3. Install

Install from the command line:
- For Fedora and EL8, RHEL8/CentOS8):  
  `sudo dnf install gnome-tweaks autokey-gtk -y`
- For Ubuntu:  
  `sudo apt install gnome-tweak-tool autokey-gtk`

Alternatively, you could have installed AutoKey-qt, but I have never used it.

## Enable and Designate a _Compose Key_

1. Open "Tweaks"
2. Select "Keyboard & Mouse"
3. Look for "Compose Key" and click on "Disabled"
4. Flip the switch from "OFF" to "ON"
5. Designate a compose key. I use "Caps Lock"  
   <span style="font-size: 75%;">_Note: whatever you choose, this setting will
   override any other use for that key._</span>

#### Enabling the _Compose Key_ for Other Environments

Are you a Microsoft or Apple user? That's beyond the scope of this document, but here's a good starting point: [5 Ways to Type a Dash](https://www.wikihow.com/Type-a-Dash).

Are you a Chromebook user? The Unicode Input Method works, but there is also a way to enable a _Compose Key_. Check out this extension: <https://chrome.google.com/webstore/detail/composekey/iijdllfdmhbmlmnbcohgbfagfibpbgba>. Good luck!


#### Use the _Compose Key_ to generate an Em Dash

I wrote a whole blog post on the topic of hyphens and dashes. I will let you cruise over there and read that: [Minuses, Hyphens and Dashes. Oh, My!](https://errantruminant.com/blog/dashes/)

_Note: You press and hold the _Compose Key_ until you type the entire the key sequence._

**<span style="font-family: monospace">en dash (–):</span>** &emsp; `[Compose Key]` `-` `-` `.`  
**<span style="font-family: monospace">em dash (—):</span>** &emsp; `[Compose Key]` `-` `-` `-`

Additionally, if you are writing in the AP-style, the _Compose Key_ can also be used to type that style of ellipsis.  
**<span style="font-family: monospace">AP-style ellipsis (…):</span>** &emsp; `[Compose Key]`&nbsp;`.`&nbsp;`.`

Now you can type things like (taken from one of my short stories):  
> _The sink was filled with dirty dishes—by her estimate, all the dishes._  
> .&nbsp;.&nbsp;. and .&nbsp;.&nbsp;.  
> _Often during the summer, they’d even wear matching sundresses which complimented their matching off-blond hair—hair that was often done-up just so—twirled up but with just the right bits freed from the rest framing their faces._  
>
> Notice that Chicago-style em dashes include no spaces on either side of the dashes. AP-style includes spaces.

My compose key is the `[CAPSLOCK]` key. But you can choose what you like. Just be careful. The capslock key is used by next to nothing so it is a safe bet.

## Use _AutoKey_ to Configure Hotkeys and Short Cuts

> With AutoKey we will be able to type specialized spaces and the Chicago-style ellipsis.

AutoKey is an application that records keystrokes so you can automate repetitive actions. We installed it earlier in this document.

#### Initial _AutoKey_ configuration

Open the application: Hit the `[SUPER]` key to bring up the Activities desktop and start typing `AutoKey`. Click and open the AutoKey application.

Ensure it runs in the background, always: Edit > Preferences and check _Automatically start AutoKey at login_.

Next we want to create hotkeys and shortcuts for ellipses and non-breaking spaces.

#### Configure seven phrases

I call these "short cuts". They will allow you to type `[CTRL]`&nbsp;`[F7]` and pull up a menu of characters to type.

I will not go into complete detail with how you configure AutoKey, but it's not rocket science. You can right-click on existing entries and rename them, click on them to edit them, etc. Or create new: New > Phrase

_Configure seven phrases .&nbsp;.&nbsp;._

> **Note1:** _Ensure you cut-n-paste the text values I give you. Otherwise, the invisible characters (non-breaking spaces) will not be copied over properly._  
> **Note2:** _Cut-n-paste the value between the brackets. Do not include the brackets._

1. Name: Ellipsis, AP (ascii)   
   Value in text window: […]
2. Name: Ellipsis, Chicago (ascii)  
   Value in text window: [. . .]
3. Name: Ellipsis, Chicago (html)  
   Value in text window: [.\&nbsp;.\&nbsp;.]
4. Name: Space, non-breaking (ascii)  
   Value in text window: [ ]
5. Name: Space, non-breaking (html)  
   Value in text window: [\&nbsp;]
6. Name: Space, non-breaking em-space (ascii)  
   Value in text window: [ ]
7. Name: Space, non-breaking em-space (html)  
   Value in text window: [\&emsp;]


**How to use:**

It may be confusing to figure out how to set them at first, but once you do, you can go into your nearest word processor or editor and type `[CTRL]`&nbsp;`[F7]` and a list of phrases will pop up up with a choice of spaces and ellipses. Select one and go! How nice!

#### Configure four hotkey scripts

> **Note:** _Remove any triple quotes (\`\`\`) if you see them in your cut-n-paste._

1. Name: &nbsp; Ellipsis, AP (ascii)  
   Hotkey value: &nbsp; `[CTRL]`&nbsp;`[SUPER]`&nbsp;`.`  
   Text window value:  
   ```
   OldClipboard=clipboard.get_clipboard()
   TextToType="…"
   clipboard.fill_clipboard(TextToType)
   keyboard.send_keys("<ctrl>+v")
   time.sleep(0.1)
   clipboard.fill_clipboard(OldClipboard)
   ```

2. Name: &nbsp; &emsp; Ellipsis, Chicago (ascii)  
   Hotkey value: &nbsp; `[SUPER]`&nbsp;`.`  
   Text window value (the script):
   ```
   OldClipboard=clipboard.get_clipboard()
   TextToType=". . ."
   clipboard.fill_clipboard(TextToType)
   keyboard.send_keys("<ctrl>+v")
   time.sleep(0.1)
   clipboard.fill_clipboard(OldClipboard)
   ```

3. Name: &nbsp; Space, non-breaking (ascii)  
   Hotkey: &nbsp; `[CTRL]`&nbsp;`[SHIFT]`&nbsp;`[SPACE]`  
   Text window value (the script):  
   ```
   OldClipboard=clipboard.get_clipboard()
   TextToType=" "
   clipboard.fill_clipboard(TextToType)
   keyboard.send_keys("<ctrl>+v")
   time.sleep(0.1)
   clipboard.fill_clipboard(OldClipboard)
   ```
4. Name: &nbsp; Space, non-breaking em-dash (ascii)  
   Hotkey: &nbsp; `[CTRL]`&nbsp;`[SHIFT]`&nbsp;`[SUPER]`&nbsp;`[SPACE]`  
   Text window value (the script):  
   ```
   OldClipboard=clipboard.get_clipboard()
   TextToType=" "
   clipboard.fill_clipboard(TextToType)
   keyboard.send_keys("<ctrl>+v")
   time.sleep(0.1)
   clipboard.fill_clipboard(OldClipboard)
   ```

**How to use:**  
_Anywhere in a document, if you want to add .&nbsp;.&nbsp;._
* Chicago-style ellipsis (. . .): &nbsp; `[SUPER]` `.`
* Non-breaking normal space ( ): &nbsp;  `[CTRL]`&nbsp;`[SHIFT]`&nbsp;`[SPACE]`  
  _Note, in many programs, this was already set as such._
* AP-styled ellipsis (…):  
  `[CTRL]`&nbsp;`[SUPER]`&nbsp;`.`  &emsp; -or-  &emsp; `[Compose Key]`&nbsp;`.`&nbsp;`.`
* Non-breaking normal space ( ): &nbsp;  `[CTRL]`&nbsp;`[SHIFT]`&nbsp;`[SUPER]`&nbsp;`[SPACE]`

Now you can type things like (takentaken from one of my short stories):
> _"Well . . . I . . ." Emily fidgeted and then looked down at the floor. "Of course I do, Mom."_
>
> Notice that Chicago-style ellipses are spaced out (with non-breaking spaces) and include spaces on either side of the ellipses. AP-style similarly adds spaces to each side of the ellipses but the ellipses themselves are compact.

## Other Useful Key Combinations

**non-breaking space ( ):**
  - `[Compose Key]`&nbsp;`[space]`&nbsp;`[space]`
  - `[CTRL]`&nbsp;`[SHIFT]`&nbsp;`[SPACE]` (LibreOffice and many others)
  - `[CTRL-k]`&nbsp;`[SPACE]`&nbsp;`[SPACE]` (vim in input mode)

**degree symbol (°):** &emsp; `[Compose Key]` `o` `o`  

**prime and double-prime (5′ 9″):**
- ***html version of both:*** &emsp; `5&prime;` and `9&Prime;`
- ***prime:*** &emsp;  `[CTRL-SHIFT-U]`&nbsp;`2`&nbsp;`0`&nbsp;`3`&nbsp;`2`
- ***double-prime:*** &emsp;  `[CTRL-SHIFT-U]`&nbsp;`2`&nbsp;`0`&nbsp;`3`&nbsp;`3`

#### _Compose Key_ characters

> Some internet denizen created this awesome _[Compose Key Cheatsheet](https://cheatography.com/davechild/cheat-sheets/ubuntu-compose-key-combinations/)_. It says it is for Ubuntu Linux, but that is incorrect. The _Compose Key_ combinations are universal for all Linuxes.

#### Unicode characters

Unicode characters are those ones you enter with `[CTRL-SHIFT-U]`. More specifically, you look up their unicode number (for example em dash is 2014) and you type `[CTRL-SHIFT-U]` (release) then `2`&nbsp;`0`&nbsp;`1`&nbsp;`4` (spacebar or enter).

> An excellent unicode (`[CTRL-SHIFT-U]`) reference can be found at fileformat.info: [spaces](https://www.fileformat.info/info/unicode/category/Zs/list.htm) and [hyphens and dashes](https://www.fileformat.info/info/unicode/category/Pd/list.htm).

## You should be set!

Now when you write you can input the appropriate typographical character for your prose. Gone are the days of -- for an en dash and --- for an em dash. No more three manual dots (...) when you really want a real ellipsis. You can now use 2-em dashes to properly format citations. You have just stepped up your game.

For further reading .&nbsp;.&nbsp;.
- [The Chicago Manual of Style](https://www.chicagomanualofstyle.org/) costs about $32. If you take your writing seriously, buy it. The 17th edition has a lot to say about .&nbsp;.&nbsp;.
  * Ellipses: beginning on p728, section 13.50
  * hyphens and dashes: beginning on p396, section 6.75
  * spaces: beginning on p408, section 6.119
- [The Associated Press (AP) Stylebook](https://www.apstylebook.com/) is only about $25 (paperback). If you write for the news media or wish to adopt it for your news-like blog, again, buy it! These style guides are worth their weight in gold. Professionalize your prose.
