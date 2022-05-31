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
`:%s/cat/dog/g` | Replace all occurrences of the word `cat` by the word `dog` in the entire buffer
`:%s/cat/dog/gc` | Replace with confirmation all occurrences of the word `cat` by the word `dog` in the entire buffer
`:find Main.elm` | Find the file `Main.elm` in the current working directory
`:edit Main.elm` | Open the `Main.elm` file for editing in the current buffer
`:buffer index.html` | Switches to the `index.html` file for editing in the current buffer

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
`U` | Undo latest change on the line
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
`D` | Delete all characters from the cursor until the end of the line
`fa` | Move the cursor just under the next occurrence of the `a` character
`Fa` | Move the cursor just under the previous occurrence of the `a` character
`ga` | Display the ASCII, octal and hexadecimal value of the character under the cursor
`gd` | Go to local definition of the variable under the cursor
`gd` | Go to local definition of the variable under the cursor
`ge` | Move the cursor to the beginning of the previous word
`gf` | Open the file under the cursor for editin in the current buffer
`gg` | Move the cursor to the top of the buffer
`gi` | Move the cursor to the location of where the previous insertion has ended
`gn` | Move the cursor to the next search and go into `VISUAL` mode
`gt` | Move to the next tab
`guiw` | Lowercase a word
`gUiw` | Uppercase a word
`gw` | Format the selected lines and go back to the original position
`gv` | Go into the previous lines selected in `VISUAL` mode 
`G` | Go to the end of the buffer
`h` | Move the cursor one character before the current one
`H` | Move the cursor under the first line of the screen
`j` | Move the cursor one line after the current one
`J` | Join the line under the cursor and the next one
`k` | Move the cursor one line before the current one
`K` | Open the `man` command for the word under the cursor
`l` | Move the cursor one character after the current one
`L` | Move the cursor under the last line of the screen
`zz` | Move the screen so that the cursor gets in the middle of the screen
`zt` | Move the screen so that the cursor gets in the top of the screen
`zb` | Move the screen so that the cursor gets in the bottom of the screen
`ZZ` | Write all buffers and close VM
`x` | Delete the character under the cursor
`X` | Delete the character before the cursor
`cc` | Delete all characters in the line under the cursor and go into `INSERT` mode
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
`$` | Move the cursor to the end of the line
`%` | Move the cursor to the matching character `(`, `)`, `[`, `]`, `{`, or `}`
`^` | Move the cursor to the first non-blank character of the line
`#` | Move the cursor to the previous occurrence of the word under the cursor
`*` | Move the cursor to the next occurrence of the word under the cursor
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
`==` | Indent the line under the cursor
`CONTROL-q` | Go into `VISUAL BLOCK` mode
`CONTROL-x` | Decrement the the number under the cursor by 1
`CONTROL-e` | Scroll up one line
`CONTROL-r` | Redo latest change
`CONTROL-y` | Scroll down one line
`CONTROL-u` | Scroll up one half-screen
`CONTROL-i` | Go to the next cursor jump
`CONTROL-o` | Go to the previous cursor jump
`CONTROL-d` | Scroll down one half-screen
`CONTROL-a` | Increment the the number under the cursor by 1
`CONTROL-v` | Go into `VISUAL BLOCK` mode
