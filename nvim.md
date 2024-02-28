# Useful Vim Commands

**Navigation:**

- **Moving Around:**
  - `h`: Move left
  - `j`: Move down
  - `k`: Move up
  - `l`: Move right
  - `w`: Move to next word
  - `b`: Move to previous word
  - `0`: Move to line beginning
  - `$`: Move to line end
  - `gg`: Move to file beginning
  - `G`: Move to file end
- **Scrolling:**
  - `Ctrl + u`: Scroll half page up
  - `Ctrl + d`: Scroll half page down
  - `Ctrl + b`: Scroll one page up
  - `Ctrl + f`: Scroll one page down
- **Jumping:**
  - `Ctrl + o`: Jump back
  - `Ctrl + i`: Jump forward

**Editing:**

- **Inserting:**
  - `i`: Insert at cursor
  - `I`: Insert at line beginning
  - `a`: Append after cursor
  - `A`: Append at line end
  - `o`: Open new line below
  - `O`: Open new line above
- **Deleting:**
  - `x`: Delete character
  - `dd`: Delete entire line
  - `dw`: Delete word
  - `d$`: Delete to line end
  - `d0`: Delete to line beginning
- **Copying and Pasting:**
  - `yy`: Yank (copy) line
  - `yw`: Yank word
  - `p`: Paste after cursor
  - `P`: Paste before cursor
- **Undo and Redo:**
  - `u`: Undo last change
  - `Ctrl + r`: Redo

**Searching and Replacing:**

- **Searching:**
  - `/pattern`: Search forward
  - `?pattern`: Search backward
  - `n`: Next search result
  - `N`: Previous search result
- **Replacing:**
  - `:%s/old/new/g`: Replace all 'old' with 'new' (entire file)
  - `:s/old/new/g`: Replace all 'old' with 'new' (current line)
  - `:s/old/new/gc`: Replace with confirmation

**Working with Files:**

- **Saving and Quitting:**
  - `:w`: Save changes
  - `:q`: Quit (close window)
  - `:q!`: Quit without saving
  - `:wq` or `ZZ`: Save and quit
  - `:x`: Save and quit (if changes made)
- **Opening and Closing:**
  - `:e filename`: Open a file
  - `:w filename`: Write to new file
  - `:x`: Save and quit
- **Tabs and Buffers:**
  - `:tabnew`: Open new tab
  - `:tabnext` or `gt`: Move to next tab
  - `:tabprev` or `gT`: Move to previous tab
  - `:tabclose`: Close current tab

**Visual Mode:**

- **Entering:**
  - `v`: Character-wise selection
  - `V`: Line-wise selection
  - `Ctrl + v`: Block-wise selection
- **Using:**
  - Navigate and perform operations on selected text:
    - `d`: Delete
    - `y`: Yank (copy)
    - `>`: Indent
    - `<`: Unindent
