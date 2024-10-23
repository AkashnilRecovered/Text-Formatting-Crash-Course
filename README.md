# Text Formatting Crash Course
This crash course has got the various formatting you can use on GitHub. Feel free to come back to this repository if you want to copy these.

## Table of Contents
(SOON)

## Text Formatting Level 1
### Italics
To make italic text, first apply an asterisk (*) between the first and last letter of your word.
Example: 
```
*italic text*
```
Output: *italic text*
### Bold & Bold with Italics
To make bold text, first apply two asterisks (**) between the first and last letter of your word.
Example:
```
**bold text**
```
Output: **bold text**

To make bold with italics text, first apply three asterisks (***) between the first and last letter of your word.
Example:
```
***bold with italics text***
```
Output: ***bold with italics text***
### Strikethrough and Bold with Strikethrough & Italics with Strikethrough
To make a strikethrough, first apply two tildes (~~) between the first and last letter of your word.
Example:
```
~~strikethrough text~~
```
Output: ~~strikethrough text~~

To make bold text with strikethrough, first apply two asterisks and tildes (**,~~) between the first and last letter of your word.
Example: 
```
**~~bold and strikethrough text~~**
```
Output:
**~~bold and strikethrough text~~**

To make italic text with strikethrough, first apply one asterisk and two tildes (*, ~~) between the first and last letter of your word.
Example:
```
*~~italic and strikethrough text~~*
```
Output: *~~italic and strikethrough text~~*
### Bold and nested italic
To make bold and nested italic, first apply two asterisks (**) at the first and last letter of your sentence, then apply two underscores (__) at the beginning and end of the desired word of your sentence.
Example:
```
**I had a _wonderful_ time on Discord**
```
Output: **I had a _wonderful_ time on Discord**
### Subscript and Superscript
To make your text below your sentence, first apply `<sub>` at the beginning of desired word of your sentence and `</sub>` at the end of the word of your sentence.
Example:
```
I had a <sub>wonderful</sub> time on Discord
```
Output: I had a <sub>wonderful</sub> time on Discord

To make your text above your sentence, first apply `<sup>` at the beat the beginning of desired word of your sentence and `</sup>` at the end of the word of your sentence.
Example:
```
I had a <sup>wonderful</sup> time on Discord
```
Output: I had a <sup>wonderful</sup> time on Discord
> [!NOTE]
> Two backticks (``) were added between `<sub>` and `< /sub >` and `< sup >` and `< /sup >` for no clashing between sentences of the steps.
## Text Formatting Level 2
### Quoting text
You can quote your text by applying greater than symbol (>) at the beginning of your sentence.
Example:
```
> I had a wonderful time on Discord
```
Output:

> I had a wonderful time on Discord
### Color models
To call out color models in your text, you can add color codes like `#ffffff` or `#000000` using backticks and a hashtag. (Might not work in README, only pull requests, disscussions, issues.)
Example:
```
The color for white is `#ffffff` and the color of black is `#000000`
```
Output: The color for white is `#ffffff` and the color of black is `#000000` (yes, it doesn't show the color next to it on a readme)

Color: HEX, RGB, HSL

Syntax:

For HEX: `#RRGGBB`

For RGB: `rgb(R,G,B)`

For HSL: `hsl(H,S,L)`

Example for given syntaxes:

HEX: `#0969DA`

RGB: `rgb(9, 105, 218)`

HSL: `hsl(212, 92%, 45%)`

> [!NOTE]
> - A supported color model cannot have any leading or trailing spaces within the backticks.
> - The visualization of the color is only supported in issues, pull requests, and discussions.
### Text linking
To apply text linking (having a link in the text), apply brackets ([]) between the beginning and end of the words and brackets 2 (()) between the beginning and end of the link.
Example:
```
[Link to my GTA SA Modpack](https://github.com/AkashnilRecovered/AkashnilRecovered)
```
Output: [Link to my GTA SA Modpack](https://github.com/AkashnilRecovered/AkashnilRecovered)
### Header linking
To apply header linking, apply brackets ([]) between the beginning and end of the words and brackets 2 (()) between the beginning and end of the link. The link must have a hashtag at the beginning.
Example:
```
[Table of Contents](#table-of-contents)
```
Output: [Table of Contents](#table-of-contents)
### Lists
To make lists, you can use these keywords: *,-,+
Example: 
```
* Discord
- Spotify
+ Microsoft
```
Output:
* Discord
- Spotify
+ Microsoft

You can order your list by using numbering system. 
Example:
```
1. Discord
2. Spotify
3. Microsoft
and so on
```
Output:
1. Discord
2. Spotify
3. Microsoft

and so on
### Nested Lists (from Github Documentation)
You can create a nested list by indenting one or more list items below another item.

To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like Visual Studio Code, you can align your list visually. Type space characters in front of your nested list item until the list marker character (- or *) lies directly below the first character of the text in the item above it.
Example:
```
1. First list item
   - First nested list item
     - Second nested list item
```
> [!NOTE]
> In the web-based editor, you can indent or dedent one or more lines of text by first highlighting the desired lines and then using Tab or Shift+Tab respectively.

Output:
1. First list item
   - First nested list item
     - Second nested list item

To create a nested list in the comment editor on GitHub, which doesn't use a monospaced font, you can look at the list item immediately above the nested list and count the number of characters that appear before the content of the item. Then type that number of space characters in front of the nested list item.

In this example, you could add a nested list item under the list item 100. First list item by indenting the nested list item a minimum of five spaces, since there are five characters (100. ) before First list item.
Example:
```
100. First list item
     - First nested list item
```
Output:

100. First list item
     - First nested list item

You can create multiple levels of nested lists using the same method. For example, because the first nested list item has seven characters (␣␣␣␣␣-␣) before the nested list content First nested list item, you would need to indent the second nested list item by at least two more characters (nine spaces minimum).

Example:
```
100. First list item
     - First nested list item
       - Second nested list item
```
Output:

100. First list item
     - First nested list item
       - Second nested list item
### Task lists (from Github Documentation)
To create a task list, preface list items with a hyphen and space followed by [ ]. To mark a task as complete, use [x].
Example:
```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```
Output:

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

If a task list item description begins with a parenthesis, you'll need to escape it with \:

- [ ] \(Optional) Open a followup issue
### Footnotes (from Github Documentation)
You can add footnotes to your content by using this bracket syntax (example):
```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
```
The footnote will render like this (output):

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference. (From Footnote)
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line. (From Footnote)

> [!NOTE]
> The position of a footnote in your Markdown does not influence where the footnote will be rendered. You can write a footnote right after your reference to the footnote, and the footnote will still render at the bottom of the Markdown. Footnotes are not supported in wikis.
### Alerts (github only)
Alerts are a Markdown extension based on the blockquote syntax that you can use to emphasize critical information. On GitHub, they are displayed with distinctive colors and icons to indicate the significance of the content.

Use alerts only when they are crucial for user success and limit them to one or two per article to prevent overloading the reader. Additionally, you should avoid placing alerts consecutively. Alerts cannot be nested within other elements.

To add an alert, use a special blockquote line specifying the alert type, followed by the alert information in a standard blockquote. Five types of alerts are available (examples):
```
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```
Output of Note: 

> [!NOTE]
> Useful information that users should know, even when skimming content.

Output of Tip:

> [!TIP]
> Helpful advice for doing things better or more easily.

Output of Important:

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

Output of Warning:

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

Output of Caution:

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

### Hiding embed of links (works on Discord)
To hide the embed sent automatically with the link, add < at the beginning of the link and > at the end of the link
Example:
```
<www.google.com>
```
Output: <www.google.com> (yeah i told you)

<p align="center">The end</p>
