# VimCommands
A list of all Vim commands.

## Movement Commands

| Command | Description                     |
|---------|---------------------------------|
| h       | Move left                       |
| l       | Move right                      |
| j       | Move down                       |
| k       | Move up                         |
| w       | Jump to start of next word      |
| b       | Jump to beginning of word       |
| e       | Jump to end of word             |
| 0       | Jump to beginning of line       |
| ^       | Jump to first non-blank char    |
| $       | Jump to end of line             |
| gg      | Go to top of file               |
| G       | Go to bottom of file            |
| :n      | Go to line n                    |

## Inserting Text

| Command | Description                     |
|---------|---------------------------------|
| i       | Insert before cursor            |
| I       | Insert at beginning of line     |
| a       | Append after cursor             |
| A       | Append at end of line           |
| o       | Open new line below             |
| O       | Open new line above             |

## Editing Text

| Command | Description                     |
|---------|---------------------------------|
| x       | Delete character under cursor   |
| dd      | Delete current line             |
| dw      | Delete word                     |
| d$      | Delete to end of line           |
| u       | Undo                            |
| Ctrl + r| Redo                            |
| yy      | Yank (copy) line                |
| p       | Paste after cursor              |
| P       | Paste before cursor             |
| r       | Replace character               |
| cw      | Change word                     |
| cc      | Change entire line              |

## Visual Mode

| Command | Description                     |
|---------|---------------------------------|
| v       | Start visual mode (char-wise)   |
| V       | Start visual mode (line-wise)   |
| Ctrl + v| Start block visual mode         |
| y       | Yank selection                  |
| d       | Delete selection                |
| >       | Indent selection                |
| <       | Unindent selection              |

## Searching

| Command | Description                     |
|---------|---------------------------------|
| /word   | Search forward for 'word'       |
| ?word   | Search backward for 'word'      |
| n       | Repeat last search              |
| N       | Repeat last search in reverse   |

## File Operations

| Command   | Description                     |
|-----------|---------------------------------|
| :w        | Save (write) file               |
| :q        | Quit                            |
| :wq       | Save and quit                   |
| :q!       | Quit without saving             |
| :e file   | Open another file               |
| :sav file | Save as another file            |

## Buffers, Windows & Tabs

| Command    | Description                      |
|------------|----------------------------------|
| :ls        | List buffers                     |
| :b n       | Switch to buffer n               |
| :sp file   | Horizontal split with file       |
| :vsp file  | Vertical split with file         |
| Ctrl + w w | Switch between splits            |
| :tabnew    | Open new tab                     |
| gt         | Go to next tab                   |
| gT         | Go to previous tab               |

## Miscellaneous

| Command | Description                          |
|---------|--------------------------------------|
| :set nu | Show line numbers                    |
| :set rnu| Show relative line numbers           |
| :syntax on | Enable syntax highlighting        |
| :noh     | Clear search highlights             |
| .        | Repeat last change                  |

---

> ✅ This list includes essential commands. Vim has hundreds more, especially when plugins or advanced configuration are considered.
