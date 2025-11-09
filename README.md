A quick reference for the most useful commands and keystrokes in Neovim / LazyVim.

Perfect for daily use as you build muscle memory.

---

## 🪄 Modes

| Mode | How to Enter | Purpose |
| --- | --- | --- |
| **Normal** | `Esc` | Navigate, run commands |
| **Insert** | `i` | Type/edit text |
| **Visual** | `v` | Select text |
| **Command-line** | `:` | Execute commands (`:w`, `:q`, etc.) |
| **Terminal** | `:terminal` | Open shell inside Neovim |

---

## 📂 Files & Buffers

| Action | Command / Keys |
| --- | --- |
| Open file | `:e filename` |
| Open file explorer (Neo-tree) | `<space> e` |
| Create new file | `:e newfile.txt` |
| Save file | `:w` |
| Save all files | `:wa` |
| Quit file | `:q` |
| Quit without saving | `:q!` |
| Save & quit | `:wq` |
| Reload file | `:e!` |
| List open buffers | `:ls` or `<space> b b` |
| Switch buffer | `:b<number>` or `<space> b b` |
| Close buffer | `:bd` |
| Delete file (from file tree) | Highlight → `d` |
| Rename file (from file tree) | Highlight → `r` |
| Move file (from file tree) | Highlight → `m` |

---

## ✏️ Editing Text

| Action | Command / Keys |
| --- | --- |
| Insert mode | `i` |
| Append at end of line | `A` |
| Delete character | `x` |
| Delete word | `dw` |
| Delete line | `dd` |
| Copy (yank) line | `yy` |
| Paste | `p` |
| Cut (delete + copy) | `dd` |
| Undo | `u` |
| Redo | `Ctrl + r` |
| Select text | `v` then move cursor |
| Copy selection | `y` |
| Delete selection | `d` |
| Replace one character | `r` then new character |
| Replace selection | `R` then type text |
| Join lines | `J` |
| Indent line right | `>>` |
| Indent line left | `<<` |
| Comment line (LazyVim) | `gcc` |

---

## 🧭 Navigation

| Action | Command / Keys |
| --- | --- |
| Move left | `h` |
| Move down | `j` |
| Move up | `k` |
| Move right | `l` |
| Jump word forward | `w` |
| Jump word backward | `b` |
| Go to start of line | `0` |
| Go to end of line | `$` |
| Go to top of file | `gg` |
| Go to bottom of file | `G` |
| Go to line number | `:42` |
| Page up | `Ctrl + u` |
| Page down | `Ctrl + d` |
| Center cursor on screen | `zz` |

---

## 🔍 Search & Replace

| Action | Command |
| --- | --- |
| Search for word | `/word` then `Enter` |
| Next search result | `n` |
| Previous result | `N` |
| Replace word (one file) | `:%s/old/new/g` |
| Confirm each replace | `:%s/old/new/gc` |
| Case-sensitive search | `\\C` at end of search |

---

## 🔄 Window & Split Management

| Action | Command / Keys |
| --- | --- |
| Vertical split | `:vsplit` or `<leader> |
| Horizontal split | `:split` or `<leader> -` |
| Close split | `:close` |
| Move between splits | `Ctrl + w + (h/j/k/l)` |
| Resize split | `Ctrl + w` then `<` or `>` or `+` or `-` |
| Equalize splits | `Ctrl + w =` |

---

## ⚡ LazyVim Shortcuts

| Action | Keys |
| --- | --- |
| Find file | `<space> f f` |
| Live grep | `<space> f g` |
| Recent files | `<space> f r` |
| Buffers list | `<space> b b` |
| Toggle file explorer | `<space> e` |
| Open LazyGit | `<space> g g` |
| Preview git diff | `<leader> g p` |
| Git blame line | `<leader> g b` |
| Format file | `<leader> c f` |
| Rename variable | `<leader> r n` |
| Show LSP hover docs | `K` |
| Code actions | `<leader> c a` |

---

## 🧩 Misc

| Action | Command / Keys |
| --- | --- |
| Open command palette | `<space> s` |
| Toggle terminal | `<leader> t t` |
| Exit terminal mode | `Ctrl + \\` then `Ctrl + n` |
| Show keymaps popup | Hold `<space>` |
| Check keybindings | `:map` |
| Open config | `:e ~/.config/nvim/init.lua` |
| Reload config | `:source %` |
| Show all plugins | `:Lazy` |
| Update plugins | `:Lazy update` |
| Profile performance | `:Lazy profile` |

---

## 🧱 Git Essentials (LazyVim + LazyGit)

| Action | Keys |
| --- | --- |
| Open LazyGit | `<space> g g` |
| Stage file | `a` (inside LazyGit) |
| Commit | `c` |
| Push | `P` |
| Pull | `p` |
| Quit LazyGit | `q` |
| Inline diff signs | shown in gutter (Gitsigns) |
| Next hunk | `]h` |
| Previous hunk | `[h` |

---

## 🚨 Panic Zone

| Need | Do this |
| --- | --- |
| Something’s wrong | `Esc` (a few times) |
| Exit without saving | `:q!` |
| Save and quit all | `:wqa` |
| Kill all splits | `:qa!` |
| Close buffer | `:bd` |

---

## 🧠 Pro Tip

Press and **hold `<space>`** at any time to open **which-key**, which shows *all available shortcuts and their descriptions* — like a built-in command cheat sheet.

---
