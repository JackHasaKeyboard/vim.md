### Normal mode
|           |       |                                | 
|-----------|-------|--------------------------------| 
| u         |       | Undo                           | 
| U         |       | Undo (specific to line)        | 
| Ctrl      | r     | Redo                           | 
| .         |       | Repeat last command            | 
| [no]      | [cmd] | Executecommand number of times | 
| Space     |       | Move cursor right              | 
| Backspace |       | Move cursor left               | 
| Z         | Z     | Saveand quit                   | 
| Z         | Q     | Quit                           | 

|   |   |   |                  |
|---|---|---|------------------|
| z | = |   | Suggest spelling |
| z | g |   | Add to dict      |
| z | u | g | Undo add to dict |

|   |      |   |                |
|---|------|---|----------------|
| g | a    |   | Word definiton |
| g | Ctrl | g | Word count     |

### Navigation
|      |        |                                                                         |
|------|--------|-------------------------------------------------------------------------|
| h    |        | Move cursor left                                                        |
| j    |        | Move cursor down                                                        |
| k    |        | Move cursor up                                                          |
| l    |        | Move cursor right                                                       |
| w    |        | Move forwards to the start of a word                                    |
| W    |        | Move forwards to the start of a word (not excluding punctuation)        |
| e    |        | Move forwards to the end of a word                                      |
| E    |        | Move forwards to the end of a word (not excluding punctuation)          |
| b    |        | Move backwards to the start of a word                                   |
| B    |        | Move backwards to the start of a word (not excluding punctuation)       |
| n    |        | Next occurence of search                                                |
| N    |        | Previous occurence of search                                            |
| *    |        | Next occurence of word under cursor                                     |
| #    |        | Previous occurence of word under cursor                                 |
| }    |        | Move to next paragraph/function block                                   |
| {    |        | Move to previous paragraph/function block                               |
| f    | [char] | Move to the next char on the current line after the cursor              |
| F    | [char] | Move to the next char on the current line before the cursor             |
| t    | [char] | Move to before the next char on the current line after the cursor       |
| T    | [char] | Move to before the previous char on the current line after the cursor   |
| %    |        | Move to matching parenthesis                                            |
| ^    |        | Move to the first non-blank character of line                           |
| $    |        | Move to line end                                                        |
| 0    |        | Move to line start                                                      |
| [    | [      |  Move to function start                                                 |
| [    | {      |  Move to block start                                                    |
| g    | _      | jump to the last non-blank character of the line                        |
| g    | g      | Go to the first line of the document                                    |
| G    |        | Go to the last line of the document                                     |
| [no] | G      | Go to line                                                              |
| [no] | \|     | Go to column                                                            |
| z    | z      | Move window to top of cursor                                            |
| z    | t      | Move window to center of cursor                                         |
| z    | b      | Move window to bottom of cursor                                                                                         |

|      |   |                         |
|------|---|-------------------------|
| Ctrl | b | Scroll down a page      |
| Ctrl | f | Scroll up a page        |
| Ctrl | d | Scroll down half a page |
| Ctrl | u | Scroll up half a page   |
| Ctrl | y | Scroll down a line      |
| Ctrl | e | Scroll up a line        |

`<no>` Go to line no

### Editing
|     |                                          |
|-----|------------------------------------------|
| i   | Enter insert mode before cursor          |
| a   | Enter insert mode after cursor           |
| I   | Enter insert mode at beginning of line   |
| A   | Enter insert mode at ending of line      |
| o   | Create new line below, enter insert mode |
| O   | Create new line above, enter insert mode |
| s   | Delete character, enter insert mode      |
| s   | Delete character, enter insert mode      |
| x   | Delete character                         |
| X   | Delete character to left of cursor       |

|   |                              |
|---|------------------------------|
| J | Join line with previous line |

|   |   |   |                                                  |
|---|---|---|--------------------------------------------------|
| " | _ | d | Black hole, delete without inserting in register |

### Motions and Text objects
|        |        |        |                                                     |
|--------|--------|--------|-----------------------------------------------------|
| d      |        |        | Delete                                              |
| c      |        |        | Change                                              |
| y      |        |        | Yank                                                |
| v      |        |        | View                                                |
|        | i      |        | In (discluding surrounding characters)              |
|        | i      |        | Around (including surrounding characters)           |
|        | t      |        | 'Til (discluding character)                         |
|        | f      |        | Find (including character)                          |
|        | g      |        | Line number                                         |
|        |        | w      | Word                                                |
|        |        | W      | Word (including punctuation and special characters) |
|        |        | s      | Sentence                                            |
|        |        | t      | Tag                                                 |
|        |        | <      | Tag                                                 |
|        |        | >      | Tag                                                 |
|        |        | '      | Single quotes                                       |
|        |        | "      | Double quotes                                       |
|        |        | `      | Backticks                                           |
|        |        | p      | Parameter                                           |
|        |        | [      | Braces                                              |
|        |        | ]      | Braces                                              |
|        |        | (      | Brackets                                            |
|        |        | )      | Brackets                                            |
|        |        | {      | Paragraph                                           |
|        |        | {      | Next Paragraph                                      |
|        |        | }      | Previous Paragraph                                  |
|        |        | "      | Double quotes                                       |
|        |        | '      | Single quotes                                       |
|        |        | `      | Backticks                                           |

### Insert mode
| Key | Effect            |
|-----|-------------------|
| ←   | Move cursor left  |
| ↓   | Move cursor down  |
| ↑   | Move cursor up    |
| →   | Move cursor right |

|      |   |       |   |                                                  |
|------|---|-------|---|--------------------------------------------------|
| Ctrl | o | [cmd] |   | Temporarily enter normal mode to execute command |
| Ctrl | n | Ctrl  | p | Complete word                                    |
| Ctrl | x | l     |   | Complete line                                    |
| Ctrl | t |       |   | Indent                                           |
| Ctrl | d |       |   | Un-indent                                        |
| Ctrl | r | x     |   | Paste register x contents                        |

|     |                  |
|-----|------------------|
| Esc | Exit insert mode |

### Visual mode
|      |   |                                |
|------|---|--------------------------------|
| Ctrl | v | Enter visual block mode        |
| v    |   | Enter visual mode              |
| V    |   | Enter visual mode, select line |

|      |     |                                          |
|------|-----|------------------------------------------|
| ~		 |     | Switch case														  |
| u    |     | Make lowercase                           |
| U    |     | Make uppercase                           |
| d		 |     | Delete																	  |
| c		 |     | Change																	  |
| y		 |     | Yank																		  |
| >		 |     | Shift right														  |
| <		 |     | Shift left															  |
| !		 |     | Filter through external command				  |
| =		 |     | Filter through 'equalprg' option command |
| g 	 | q   | Format lines to 'textwidth' length			  |
| Ctrl | a   | Increment number under the cursor        |
| Ctrl | x   | Decrement number under cursor            |

#### Clipboard
|     |     |                                            |
|-----|-----|--------------------------------------------|
| y   | y   | Yank (copy) a line                         |
| p   |     | Put (paste) the clipboard after cursor     |
| P   |     | Put (paste) before cursor                  |
| d   | d   | Delete (cut) a line                        |
| x   |     | Delete (cut) current character             |
| X   |     | Delete previous character (like backspace) |

### Command-line mode
#### Files
`e`      Edit, open file or create new one
`sp`     Edit, open file or create new one in split
`vs`     Edit, open file or create new one in split (vertically)
`w`	     Write
`saveas` Write as
`q`      Quit
`wq`     Write and quit
`x`      Write and quit
`a`      Append on the end to apply to all buffers
`o`      Open

|   |   |       | 
|---|---|-------| 
| w |   | Write | 
|   | q | Quit  | 

|      |   |                |
|------|---|----------------|
| Ctrl | g | Show file info |

|               |     |           |                                                                    | 
|---------------|-----|-----------|--------------------------------------------------------------------| 
| `[no]`        |     |           | Execute on line number                                             | 
| `[no],[no]`   |     |           | Execute on range of line numbers                                   | 
| `.`           |     |           | The current line                                                   | 
| `$`           |     |           | The last line in the file                                          | 
| `%`           |     |           | The whole file. The same as 1,$                                    | 
| `'t`          |     |           | Position of mark "t"                                               | 
| `/pattern[/]` |     |           | The next line where text "pattern" matches.                        | 
| `?pattern[?]` |     |           | The previous line where text "pattern" matches                     | 
| `\/`          |     |           | The next line where the previously used search pattern matches     | 
| `\?`          |     |           | The previous line where the previously used search pattern matches | 
| `\&`          |     |           | The next line where the previously used substitute pattern match   | 
|               | `s` |           | Substitute                                                         | 
|               | `g` |           | Go to lines                                                        | 
|               |     | `.`       | Any character except new line                                      | 
|               |     | `\s`      | Whitespace character                                               | 
|               |     | `\S`      | Non-whitespace character                                           | 
|               |     | `\d`      | Digit                                                              | 
|               |     | `\D`      | Non-digit                                                          | 
|               |     | `\x`      | Hex digit                                                          | 
|               |     | `\X`      | Non-hex digit                                                      | 
|               |     | `\o`      | Octal digit                                                        | 
|               |     | `\O`      | Non-octal digit                                                    | 
|               |     | `\h`      | Head of word character                                             | 
|               |     | `\H`      | Non-head of word character                                         | 
|               |     | `\p`      | Printable character                                                | 
|               |     | `\P`      | Like \p but excluding digits                                       | 
|               |     | `\w`      | Word character                                                     | 
|               |     | `\W`      | Non-word character                                                 | 
|               |     | `\a`      | Alphabetic character                                               | 
|               |     | `\A`      | Non-alphabetic character                                           | 
|               |     | `\l`      | Lowercase character                                                | 
|               |     | `\L`      | Non-lowercase character                                            | 
|               |     | `\u`      | Uppercase character                                                | 
|               |     | `\U`      | Non-uppercase character                                            | 
|               |     | `.`       | Any character except new line                                      | 
|               |     | `\s`      | Whitespace character                                               | 
|               |     | `\S`      | Non-whitespace character                                           | 
|               |     | `\d`      | Digit                                                              | 
|               |     | `\D`      | Non-digit                                                          | 
|               |     | `\x`      | Hex digit                                                          | 
|               |     | `\X`      | Non-hex digit                                                      | 
|               |     | `\o`      | Octal digit                                                        | 
|               |     | `\O`      | Non-octal digit                                                    | 
|               |     | `\h`      | Head of word character                                             | 
|               |     | `\H`      | Non-head of word character                                         | 
|               |     | `\p`      | Printable character                                                | 
|               |     | `\P`      | Like \p but excluding digits                                       | 
|               |     | `\w`      | Word character                                                     | 
|               |     | `\W`      | Non-word character                                                 | 
|               |     | `\a`      | Alphabetic character                                               | 
|               |     | `\A`      | Non-alphabetic character                                           | 
|               |     | `\l`      | Lowercase character                                                | 
|               |     | `\L`      | Non-lowercase character                                            | 
|               |     | `\u`      | Uppercase character                                                | 
|               |     | `\U`      | Non-uppercase character                                            | 
|               |     | `*`       | Matches 0 or more of the preceding characters[comma] ranges or metacharacters .* matches everything including empty line | 
|               |     | `\+`      | Matches 1 or more of the preceding characters...                                                                         | 
|               |     | `\=`      | Matches 0 or 1 more of the preceding characters...                                                                       | 
|               |     | `\{n,m}`  | Matches from n to m of the preceding characters...                                                                       | 
|               |     | `\{n}`    | Matches exactly n times of the preceding characters...                                                                   | 
|               |     | `\{,m}`   | Matches at most m (from 0 to m) of the preceding characters...                                                           | 
|               |     | `\{n,}`   | Matches at least n of of the preceding characters...                                                                     | 
|               |     | `\{-}`    | Matches 0 or more of the preceding atom[comma] as few as possible                                                        | 
|               |     | `\{-n,m}` | Matches 1 or more of the preceding characters...                                                                         | 
|               |     | `\{-n,}`  | Matches at lease or more of the preceding characters...                                                                  | 
|               |     | `\{-,m}`  | Matches 1 or more of the preceding characters...                                                                         | 
|               |     | `&`       | The whole matched pattern                                                                                                | 
|               |     | `\L`      | The following characters are made lowercase                                                                              | 
|               |     | `\0`      | The whole matched pattern                                                                                                | 
|               |     | `\U`      | The following characters are made uppercase                                                                              | 
|               |     | `\1`      | The matched pattern in the first pair of \(\)                                                                            | 
|               |     | `\E`      | End of \U and \L                                                                                                         | 
|               |     | `\2`      | The matched pattern in the second pair of \(\)                                                                           | 
|               |     | `\e`      | End of \U and \L                                                                                                         | 
|               |     | `\r`      | Split line in two at this point                                                                                          | 
|               |     | `\9`      | The matched pattern in the ninth pair of \(\)                                                                            | 
|               |     | `\l`      | Next character made lowercase                                                                                            | 
|               |     | `~`       | The previous substitute string                                                                                           | 
|               |     | `\u`      | Next character made uppercase                                                                                            | 

|   |                                     |
|---|-------------------------------------|
| n | Repeat search in same direction     |
| N | Repeat search in opposite direction |

#### File explorer
`e` Open integrated file explorer
`Sex`	Splitwindow and open integrated file explorer
`browse` e Graphical file explorer
`ls`	Listbuffers
`cd` Move to parent directory
`args`	Listfiles
`args` Open file list
`grep` expression Returns a list of .php files contening expression
`gf`	Openfile name under cursor

#### Buffers
|   |   |                 | 
|---|---|-----------------| 
| b | n | Next buffer     | 
| b | p | Previous buffer | 

#### Tabs
`tabnew` Create a new tab
`gt` Show next tab
`gT` Show previous tab
`tabfirst` Show first tab
`tablast` Show last tab
`tabm` <n>Rearrange tabs
`tabdo` Execute a command in all tabs
`tab ball` Puts all open files in tabs /ball  /tabdo
`s` /s
`foo` /foo
`bar` /bar
`g` /g /n
`position` /position

`help` Help

|   |                   |
|---|-------------------|
| ↑ |  Previous command |
| ↓ |  Next command     |

|      |   |                                                      |
|------|---|------------------------------------------------------|
| Ctrl | f | Open command-line buffer and history as regular file |

### Windows and splits
|      |   |   |                            |
|------|---|---|----------------------------|
| Ctrl | w | w | Put cursor in next window  |
| Ctrl | w | h | Put cursor in left window  |
| Ctrl | w | j | Put cursor in below window |
| Ctrl | w | k | Put cursor in above window |
| Ctrl | w | l | Put cursor in right window |

|      |      |   |   |                                       |
|------|------|---|---|---------------------------------------|
| Ctrl | w    | . |   | Gives the same size to all windows    |
| Ctrl | w    | + |   | Resize viewport                       |
| Ctrl | w    | - |   | Resize viewport                       |
| Ctrl | w    | = |   | Resize viewport                       |
| Ctrl | w    | _ |   | Resize viewport                       |
| [no] | Ctrl | w | + | Add number of lines to current window |

|      |   |   |                            |
|------|---|---|----------------------------|
| Ctrl | w | s | Split windows horizontally |
| Ctrl | w | v | Split windows vertically   |
| Ctrl | w | w | Switch between windows     |
| Ctrl | w | q | Quit a window              |

|      |   |   |                                                               | 
|------|---|---|---------------------------------------------------------------| 
| Ctrl | w | r | Swap top/bottom or left/right split                           | 
| Ctrl | w | t | Break out current window into a new tabview                   | 
| Ctrl | w | o | Close every window in the current tabview but the current one | 

`sview` Split (readonly mode)
`hide`	Close current window
`nly`   Close all windows except current
`b 2`   Open #2 in this window

### Marks
|   |       |                           |
|---|-------|---------------------------|
| m | [a-z] | Set mark                  |
| m | [A-Z] | Set global mark           |
| ` | [a-z] | Move to position [a-z]    |
| ' | '     | Move to previous position |

### Macros
|     |        |                      |
|-----|--------|----------------------|
| q   | [a-z]  | Record macro         |
| q   |        | Stop recording macro |
| q   | [char] | Execute macro        |
| @   | @      | Rerun last run macro |

### Registers
`reg` Show registers

|     |       |     |                            |
|-----|-------|-----|----------------------------|
| "   | [a-z] | y   | Yank into register         |
| "   | 0     | p   | Paste contents of register |

### Folds
|     |     |             |
|-----|-----|-------------|
| z   | f   | Create fold |
| z   | a   | Toggle fold |

|   |     |     |   |                         |
|---|-----|-----|---|-------------------------|
| z | f   | [M] |   | Create fold of movement |
| : | [R] | f   | o | Create folder for range |

|     |     |                              |
|-----|-----|------------------------------|
| z   | o   | Open fold under cursor       |
| z   | c   | Close fold under cursor      |
| z   | R   | Open all folds under cursor  |
| z   | M   | Close all folds under cursor |
| z   | c   | Close fold                   |
| z   | O   | Open fold recursively        |

|   |   |                                    |
|---|---|------------------------------------|
| z | d | Delete fold under cursor           |
| z | E | Delete all folds in window         |
| z | C | Close fold recursively             |
| [ | z | Move to start of current open fold |
| ] | z | Move to end of current open fold   |
| z | j | Move down to start of next fold    |
| z | k | Move up to end of previous fold    |

### Notes
C-v allows you to enter control characters
Vim is a language
Commands in the command-line can be escaped to the shell with a bang (!)
Uppercase commands are often more extreme versions of their lowercase counterparts, eg. I and A will insert at the beginning and end of a line rather than before and after the cursor
Vim uses appreviations
Vim has remarkably comprehensive documentation installed into the program, access it with the `help` command
Vim matches with "smart case" by default, meaning lowercase searches are case-insensitive and uppercase are case-sensitive
