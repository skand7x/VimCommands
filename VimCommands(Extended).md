# Vim Commands Reference (Extended)

## 📦 Plugin & Advanced Commands

### Plugin: NERDTree

| Command         | Description                     |
| --------------- | ------------------------------- |
| :NERDTreeToggle | Toggle NERDTree file explorer   |
| :NERDTreeFind   | Reveal current file in NERDTree |

### Plugin: Telescope (Fuzzy Finder)

| Command                | Description       |
| ---------------------- | ----------------- |
| :Telescope find\_files | Fuzzy find files  |
| :Telescope live\_grep  | Live grep search  |
| :Telescope buffers     | List open buffers |
| :Telescope help\_tags  | Search help       |

### Plugin: vim-fugitive (Git Integration)

| Command  | Description                |
| -------- | -------------------------- |
| :Git     | Open Git command interface |
| :Gstatus | Show Git status            |
| :Gdiff   | View diffs                 |
| :Gblame  | Show Git blame             |
| :Glog    | Show commit log            |

### Plugin: CoC (Conquer of Completion)

| Command           | Description             |
| ----------------- | ----------------------- |
| :CocInstall <ext> | Install extension       |
| :CocUpdate        | Update all extensions   |
| :CocCommand       | List available commands |
| gd                | Go to definition        |
| gy                | Go to type definition   |
| gr                | List references         |
| gi                | Go to implementation    |
| K                 | Show documentation      |
| <leader>rn        | Rename symbol           |

### Plugin: Lualine / Airline (Status Line)

| Command        | Description    |
| -------------- | -------------- |
| :AirlineToggle | Toggle Airline |
| :LualineReload | Reload Lualine |

### Advanced Vim Concepts

#### Registers

| Command | Description           |
| ------- | --------------------- |
| "xy     | Yank into register x  |
| "xp     | Paste from register x |
| :reg    | List all registers    |

#### Macros

| Command | Description                          |
| ------- | ------------------------------------ |
| q\[a-z] | Start recording into register \[a-z] |
| @a      | Play macro in register a             |
| @@      | Repeat last macro                    |

#### Marks

| Command  | Description                           |
| -------- | ------------------------------------- |
| m\[a-z]  | Set mark \[a-z] at cursor             |
| '\[a-z]  | Jump to line of mark                  |
| \`\[a-z] | Jump to exact cursor position of mark |

#### Autocommands

| Command                        | Description               |
| ------------------------------ | ------------------------- |
| :autocmd BufWritePre \*.py ... | Run on save for .py files |
| :autocmd!                      | Clear autocommands        |

#### Mapping Keys

| Command                                      | Description                   |
| -------------------------------------------- | ----------------------------- |
| :map <F5> \:w<CR>:!python %<CR>              | Map F5 to save and run Python |
| :nmap <leader>ff \:Telescope find\_files<CR> | Map leader+ff to Telescope    |

> 💡 Tip: Combine these commands in your `.vimrc` or `init.vim`/`init.lua` for custom workflows.

---

