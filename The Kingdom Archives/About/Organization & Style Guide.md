This style guide exists to promote long-term consistency and clarity in how texts and other documents in this archive should be organized and formatted.
## Organization
- Texts are stored and organized within the `/Texts/` folder.
- Independent texts should always have their own folder
- When multiple texts are commonly attributed to or associated with the same biblical/historical figure (such as Baruch or Ezra), the folders for those texts should be grouped under a folder named after that figure
	- When texts are closely related and largely share the same text information, they may all be placed together in a common folder (such as for an associated figure) rather than having individual subfolders
- Every text/group of related texts should have an accompanying Text Info file in the format `"Text Info - Title.md"`, where `Title` is the name of the text.
- Text file/folder names should be derived from one of the more prominent titles attributed to a text
	- Prefer unabbreviated, succinct titles
	- Generally elide any definite article (*The*) at the start of the title
	- Include other common titles in the `aliases` property in the text's frontmatter
## Text Formatting
### Properties
Each text should include a couple of basic properties (formatted as YAML frontmatter) whenever possible:
- `aliases` — list of alternative titles for the text
- `translation` — name of the translation/translator for the text
### Headings
Each text should include the text's title styled as a Heading 1:
```markdown
# 1 Enoch
```
Sections of the text, which use Heading 2 styling, should be formatted as a numeric "Section #" and a formal section name, combined with an em dash with a space on either side:
```markdown
## Section 1 — The Book of the Watchers
```
Chapters, which use Heading 3 styling, should include the book title, immediately followed by the chapter number:
```markdown
### 1 Enoch 1
```
Verses, which use Heading 6 styling, should include the book title and chapter number, followed by a colon and the verse number:
```markdown
###### 1 Enoch 1:9
```
### Paragraphs
Paragraphs within a verse should be placed on separate lines (that is, separated by a new line character).