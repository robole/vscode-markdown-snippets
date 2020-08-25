# Markdown Snippets

![Extension file size in bytes](https://img.shields.io/static/v1?logo=visual-studio-code&label=made%20for&message=VS%20Code&color=0000ff)
![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/robole.markdown-snippets?logo=visual-studio-code&color=ffa500)
![Extension file size in bytes](https://img.shields.io/static/v1?logo=visual-studio-code&label=size&message=11KB&color=008000)
![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/robole.markdown-snippets?logo=visual-studio-code&color=yellow)
![Built with](https://img.shields.io/static/v1?label=built%20with&message=good%20vibrations&color=violet)

Markdown snippets for Extended Markdown syntax.

![insert table](/img/table.gif)

To insert a snippet, you can just type one of the prefixes, and you will be offered a completion suggestion; or you can open the Command Palette (`Ctrl+Shift+P`) and run the command "Insert Snippet", which presents you with a list to choose from.

If you would like to have shortcuts associated with these snippets, install the complementary extension [Markdown Shortcuts](https://marketplace.visualstudio.com/items?itemName=robole.markdown-shortcuts).

<a href="https://marketplace.visualstudio.com/items?itemName=robole.markdown-shortcuts"><img src="img/markdown-shortcuts-logo.png" alt="markdown shorcuts logo" style="display:block;margin:0 auto"></a>

I have included [a list of the built-in snippets](#default-snippets) below for reference. They are not documented in the VS Code docs.

## Extended Snippets

View the [source file](https://github.com/robole/vscode-markdown-snippets/blob/master/snippets/snippets.code-snippets).

For most of the snippets, if text is selected it is wrapped by the snippet. If no text is selected, the cursor is placed at a point in the snippet to enter text.

| Name                   | Prefix        | Body                                                                                                                      |
|------------------------|---------------|---------------------------------------------------------------------------------------------------------------------------|
| Insert heading level 1 | heading1      | Makes selected text a level 1 heading.                                                                                    |
| Insert heading level 2 | heading2      | Makes selected text a level 2 heading.                                                                                    |
| Insert heading level 3 | heading3      | Makes selected text a level 3 heading.                                                                                    |
| Insert heading level 4 | heading4      | Makes selected text a level 4 heading.                                                                                    |
| Insert heading level 5 | heading5      | Makes selected text a level 5 heading.                                                                                    |
| Insert heading level 6 | heading6      | Makes selected text a level 6 heading.                                                                                    |
| Insert strikethrough   | strikethrough | Makes selected text a strikethrough fragment.                                                                             |
| Insert table           | table         | Insert a table with 2 rows and 3 columns. You can tab through each cell   to edit the text.                               |
| Insert 2x1 table       | 2x1table      | Insert a table with 2 rows and 1 column. You can tab through each cell to   edit the text.                                |
| Insert 3x1 table       | 3x1table      | Insert a table with 3 rows and 1 column. You can tab through each cell to   edit the text.                                |
| Insert 4x1 table       | 4x1table      | Insert a table with 4 rows and 1 column. You can tab through each cell to   edit the text.                                |
| Insert 5x1 table       | 5x1table      | Insert a table with 5 rows and 1 column. You can tab through each cell to   edit the text.                                |
| Insert 2x2 table       | 2x2table      | Insert a table with 2 rows and 2 columns. You can tab through each cell   to edit the text.                               |
| Insert 3x2 table       | 3x2table      | Insert a table with 3 rows and 2 columns. You can tab through each cell   to edit the text.                               |
| Insert 4x2 table       | 4x2table      | Insert a table with 4 rows and 2 columns. You can tab through each cell   to edit the text.                               |
| Insert 5x2 table       | 5x2table      | Insert a table with 5 rows and 2 columns. You can tab through each cell   to edit the text.                               |
| Insert 2x3 table       | 2x3table      | Insert a table with 2 rows and 3 columns. You can tab through each cell   to edit the text.                               |
| Insert 3x3 table       | 3x3table      | Insert a table with 3 rows and 3 columns. You can tab through each cell   to edit the text.                               |
| Insert 4x4 table       | 4x3table      | Insert a table with 4 rows and 3 columns. You can tab through each cell   to edit the text.                               |
| Insert 5x5 table       | 5x5table      | Insert a table with 5 rows and 5 columns. You can tab through each cell   to edit the text.                               |
| Insert task list       | task list     | Insert  a task list with 2 tasks.   You can tab through item to set the status (complete/incomplete) and edit the   text. |

## Default Snippets

This is just for reference. You **do not need to install this extension to use these**.

View the [source file](https://github.com/microsoft/vscode/blob/f74e473238aca7b79c08be761d99a0232838ca4c/extensions/markdown-basics/snippets/markdown.code-snippets).

For most of the snippets, if text is selected it is wrapped by the snippet. If no text is selected, the cursor is placed at a point in the snippet to enter text.

| Name                     | Prefix           | Description                                                                                                                   |
|--------------------------|------------------|-------------------------------------------------------------------------------------------------------------------------------|
| Insert bold text         | bold             | Makes the selected text  a bold   fragment.                                                                                   |
| Insert code              | code             | Makes the selected text an inline code fragment.                                                                              |
| Insert fenced code block | fenced codeblock | Makes the selected text a fenced code block. You specify the language in   first tab stop, and the code in the next tab stop. |
| Insert heading           | heading          | Makes the selected text a level 1 heading.                                                                                    |
| Insert horizontal rule   | horizontal rule  | Insert a horizontal rule and a line break.                                                                                    |
| Insert image             | image            | Insert an image with the   selected text as the alternative text, the next tab stop is the URL.                               |
| Insert italic text       | italic           | Makes selected text  an italic   fragment.                                                                                    |
| Insert link              | link             | Insert a link with the selected   text as the link text, the next tab stop is the URL.                                        |
| Insert ordered list      | ordered list     | Insert an ordered list with 3 items, which you can tab through and edit   the text.                                           |
| Insert quoted text       | quote            | Makes the selected text a block quote.                                                                                        |
| Insert unordered list    | unordered list   | Insert an unordered list with 3 items, which you can tab through and edit   the text.                                         |
