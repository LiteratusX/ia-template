This package uses the official iA Writer template-bundle structure: an `.iatemplate` directory containing `Contents/Info.plist` and HTML/CSS/JavaScript resources. It is designed for APA 7 student papers rather than professional journal manuscripts.

## Files

- `APA7-Student.iatemplate.zip`: Installable template archive.
- `APA7-Student-Starter.md`: Duplicate this file for each paper, then edit the bracketed fields.

## Installation

### macOS

1. Unzip `APA7-Student.iatemplate.zip`.
2. Double-click `APA7-Student.iatemplate` in Finder, or add it through iA Writer Settings/Preferences → Templates.
3. Open the starter Markdown file and select **APA 7 Student** in Preview or during PDF/print export.

### iPhone or iPad

Send `APA7-Student.iatemplate.zip` by AirDrop or open it from Files, Mail, Safari, or iCloud Drive, then choose iA Writer.

### Windows

In iA Writer, choose File → Install Template and select `APA7-Student.iatemplate.zip`.

## What the template formats

- US Letter print layout with 1-inch margins.
- Times New Roman, 12 pt.
- Double-spaced body text.
- 0.5-inch first-line paragraph indents.
- Page numbers at the upper right, including the title page.
- APA heading Levels 1-5 mapped to Markdown headings `#` through `#####`.
- Block quotations and lists.
- Markdown tables with APA-style horizontal rules.
- Automatic new page and 0.5-inch hanging indents beneath a Level 1 `# References` heading.
- Optional abstract and keywords classes.
- Figure and table number/title/note helper styles.
- Dark Preview support; print/PDF output remains black on white.

## Heading map

- `# Heading` → APA Level 1: centered, bold.
- `## Heading` → APA Level 2: flush left, bold.
- `### Heading` → APA Level 3: flush left, bold italic.
- `#### Heading` → APA Level 4: indented, bold, run-in.
- `##### Heading` → APA Level 5: indented, bold italic, run-in.

For Levels 4 and 5, put the paragraph in the next Markdown paragraph. The export script joins the heading and paragraph visually.

## References

Write `# References` exactly. Put each reference in its own paragraph and separate references with a blank line. The template starts the section on a new page and applies hanging indents. It does not generate, alphabetize, or verify citations.

## Tables

For automatic label styling, use this order immediately before a Markdown table:

```markdown
Table 1

*Descriptive Title of the Table*

| Variable | M | SD |
|---|---:|---:|
| Example | 1.00 | 0.25 |

Note. Explain abbreviations or significance markers here.
```

## Figures

Use the same sequence with `Figure 1`, an italicized title, the image, and an optional `Note.` paragraph.

## Important limitations

- iA Writer templates format rendered Markdown; they are not citation managers. Continue using Zotero or another reference manager to generate and verify citations.
- The editable student title page is stored in the starter Markdown file because iA Writer's native template variables expose the document title, author, date, and page number, but not course number, instructor, institutional affiliation, or assignment due date.
- Headers and footers appear in printed documents and PDF exports; they may not appear as part of the ordinary document body in Preview.
- Instructor, department, thesis, or journal requirements override this general APA 7 student-paper layout.

## Sources

- iA Writer template format: https://github.com/iainc/iA-Writer-Templates
- APA Publication Manual, 7th edition: https://www.apa.org/pubs/books/publication-manual-7th-edition-paperback
- APA instructional aids: https://apastyle.apa.org/instructional-aids
