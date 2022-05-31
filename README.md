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
`W` | Go to the beginning of the next whitespace separated character
`e` | Go to the end of the next word
`E` | Go to the end of the next whitespace separated word
`ra` | Replace the character under the cursor by the letter `a`
`R` | Go into `REPLACE` mode
`ta` | Move the cursor just before the next occurrence of the `a` character
`Ta` | Move the cursor just before the previous occurrence of the `a` character
`yy` | Copy the line
`Y` | Copy the line
`u` | Undo the previous action
`U` | Redo the previously undone action
`i` | Go to `INSERT` mode
`I` | Move the cursor to the first non-whitespace character of the line under the cursor and go into `INSERT` mode
`o` | Append a new line after the cursor and go into `INSERT` mode
`O` | Append a new line before the cursor and go into `INSERT` mode
`p` | Paste anything copied by the `y` keybind after the cursor
`P` | Paste anything copied by the `y` keybind before the cursor
`a` | Move the cursor after the character under the cursor and go into `INSERT` mode
`A` | Move the cursor after the last character of the line under the cursor and go into `INSERT` mode
`s` | Remove the character under the cursor and go into `INSERT` mode
`S` | Delete all characters of the line under the cursor and go into `INSERT` mode
`dd` | Delete the line under the cursor
`dta` | Delete all character from the cursor until the character before the next `a` character
`dTa` | Delete all character from the cursor until the character before the previous `a` character
`dfa` | Delete all character from the cursor until the next `a` character
`dFa` | Delete all character from the cursor until the previous `a` character
`diw` | Delete all characters of a word independently of the position of cursor in the word
`D` | Delete all character from the cursor until the end of the line
`fa` | Move the cursor just under the next occurrence of the `a` character
`Fa` | Move the cursor just under the previous occurrence of the `a` character
`h` | Move the cursor one character before the current one
`H` | Move the cursor under the first line of the screen
`j` | Move the cursor one line after the current one
`J` | Join the line under the cursor and the next one
`k` | Move the cursor one line before the current one
`K` | Open the `man` command for the word under the cursor
`l` | Move the cursor one character after the current one
`L` | Move the cursor under the last line of the screen
`zz` | Move the screen so that the cursor gets in the middle of the screen
`ZZ` | Write all buffers and close VM
`x` | Delete the character under the cursor
`X` | Delete the character before the cursor
`cc` | Delete all characters in the line under the cursor and go into `INSERT` mode
`cta` | Delete all character from the cursor until the character before the next `a` character and go into `INSERT` mode
`cTa` | Delete all character from the cursor until the character before the previous `a` character and go into `INSERT` mode
`cfa` | Delete all character from the cursor until the next `a` character and go into `INSERT` mode
`cFa` | Delete all character from the cursor until the previous `a` character and go into `INSERT` mode
`ciw` | Delete all characters of a word independently of the position of cursor in the word and go into `INSERT` mode
`C` | Delete all characters from the cursor until the end of the line and go into `INSERT` mode
`v` | Go into `VISUAL` mode
`V` | Go into `VISUAL LINE` mode
`b` | Move the cursor to the beginning of the previous word
`B` | Move the cursor to the beginning of the previous whitespace separated word
`n` | Go to the next occurrence of a search
`N` | Go to the previous occurrence of a search
`ma` | Create a mark under the cursor and assign it to the `a` character
`M` | Move the cursor to the middle of the screen
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
