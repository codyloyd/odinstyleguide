# The Odin Project Style Guide

This little document serves as a style guide and reference for people wanting to contribute new content to the curriculum.  It'll also include a brief overview of the Markdown syntax used. Truthfully, there isn't much to it, so this won't be too long.

## Outline for Lessons and Projects.

Most of the lessons and projects follow similar outlines.  Using the following outlines helps keep the curriculum cohesive, and lets new lessons feel familiar and comfortable for students.
### Lesson Outline
1. Intro
  - Title, then: Introductory material, usually not more than a couple paragraphs
2. Points to Ponder
  - A list of terms, and short questions used for review. This section is kind of a "this is what you're going to learn"
3. Your Assignment
  - numbered list of Resources to read or simple tasks to complete
4. Additional Resources
  - seems pretty obvious right?  Bulleted list of additional resources with links and simple descriptions

### Project Outline
1. Intro
  - title then: Introductory material, explanation of the project and any background info needed to understand the project.
2. The Project!
  - step-by-step instructions for completing the project!
3. Student Solutions
  - of course!

## Style Guide/Markdown Primer
As far as style goes, there isn't really too much to worry about, but there _are_ a couple of conventions to be aware of.  Markdown is an easy-to-use syntax for formatting text documents.  Markdown is most comfortable to use in your favorite text editor rather than a word processor, and the popular editors have syntax highlighting for it as well.

Headlines are designated with one or more `#` symbols.  The main title of a lesson or assignment should be marked with a single '#' while other titles of sections of the article should be marked with 2.  Any inner-sections (like the outline sections above) should have 3 or more.

Paragraphs should not be indented and are separated by a line break.

numbered lists in markdown are simple and are just written out literally using the number followed by a period.  Nested lists can be created by simply indenting the nested list.

Links in markdown are created by pairing brackets and parentheses like so:
```
[Display Text for the Link](www.urlforthelink.com)
```

Blocks of code included in the article are should be surrounded by three backticks (on either side) of the block.  To include syntax highlighting you need to specify the language you're using like so:
```
  ```language-ruby
    block of code goes here
  ```
```

Inline code snippets can be set apart by using a single backtick on either side.

## Additional Resources
* [A more thorough explanation of Markdown can be found here.](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
