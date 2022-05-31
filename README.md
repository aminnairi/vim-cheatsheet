# vim-cheatsheet

## Keybindings

## Command Mode

Command | Description
---|---
`:q` | Quit VIM
`:q!` | Quit VIM and discard changes
`:w` | Write the current edited buffer
`:wa` | Write all currently edited buffers
`:wq` | Write the current edited buffer and quit VIM
`:wqa` | Write all edited buffers and quit VIM

### Normal Mode

Keybind | Description
---|---
`ESC` | Quit the current mode to go back into `NORMAL` mode
`qa` | Begin a macro and register the keystrokes to the letter `a`
`q` | While in a macro, ends a macro
`w` | Go to the beginning of the next word
`e` | Go to the end of the next word
`ra` | Replace the character under the cursor by the letter `a`
`ta` | Move the cursor just before the next occurrence of the `a` character
`yy` | Copy the line
`u` | Undo the previous action
`i` | Go to `INSERT` mode
`o` | Append a new line after the cursor and go into `INSERT` mode
`p` | Paste anything copied by the `y` command
`a` | Go into `INSERT` mode and move the cursor after the character
`s` | Remove the character under the cursor and go into `INSERT` mode
`dd` | Delete the line under the cursor
`fa` | Move the cursor just under the next occurrence of the `a` character
`h` | Move the cursor one character before the current one
`j` | Move the cursor one line after the current one
`k` | Move the cursor one line before the current one
`l` | Move the cursor one character after the current one
`zz` | Move the screen so that the cursor gets in the middle of the screen
`x` | Delete the character under the cursor
`cc` | Delete all characters in the line under the cursor and go into `INSERT` mode
`v` | Go into `VISUAL` mode
`b` | Move the cursor to the beginning of the previous word
`n` | Go to the previous occurrence of a search
`ma` | Create a mark under the cursor and assign it to the `a` character
`@a` | Execute the macro registered in the `a` letter
`#` | Search the previous occurrence of the word under the cursor
`$` | Go to the end of the line under the cursor
`%` | Go to the matching character `(`, `)`, `[`, `]`, `{`, or `}`
`^` | Go to the first non-blank character of the line under the cursor
`#` | Search the next occurrence of the word under the cursor
`(` Go to the beginning of the paragraph
`)` Go to the beginning of the paragraph
`_` | Go to the first non-blank character of the line under the cursor
`[[` | Go to the beginning of the file
`]]` | Go to the end of the file
`{` | Go to the line before the beginning of a paragraph
`}` | Go to the line after the end of a paragraph
`;` | Go to the next occurrence a search after a `f`, `F`, `t` or a `T`
`'a` | Go to the mark under the `a` letter
`,` | Go to the previous occurrence a search after a `f`, `F`, `t` or a `T`
`.` | Repeat the previous action
`/` | Search a word from the cursor until the end of the file
`?` | Search a word from the cursor until the beginning of the file
`<` | Indent a line backward
`>` | Indent a line forward
`:` | enter in `COMMAND` mode
`~` | Toggle the case (upper or lower) of the character under the cursor
