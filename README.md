# Vim Cheat Sheet

---

## MODES
- **Esc**: Enter Normal mode.
- **i**: Enter Insert mode.
- **v**: Enter Visual mode.
- **:**: Enter Command-line mode.

---

## FILE OPERATIONS
- `:w`: Save file.
- `:q`: Quit.
- `:wq`: Save and quit.
- `:q!`: Quit without saving.
- `:e filename`: Open a file.
- `:x`: Save and quit (same as `:wq`).

---

## NAVIGATION
### Move by Character
- `h`: Left.
- `l`: Right.
- `j`: Down.
- `k`: Up.

### Move by Word
- `w`: Next word.
- `b`: Previous word.
- `e`: End of the current/next word.

### Move by Line
- `0`: Start of the line.
- `^`: First non-whitespace character.
- `$`: End of the line.

### Move by Paragraph
- `{`: Beginning of the previous paragraph.
- `}`: Beginning of the next paragraph.

### Move by Screen
- `Ctrl + u`: Half-screen up.
- `Ctrl + d`: Half-screen down.
- `Ctrl + b`: Full-screen up.
- `Ctrl + f`: Full-screen down.

### Move to Specific Lines
- `gg`: First line of the file.
- `G`: Last line of the file.
- `:n`: Go to line `n`.

---

## EDITING
### Insert Text
- `i`: Insert before the cursor.
- `a`: Insert after the cursor.
- `o`: Open a new line below.
- `O`: Open a new line above.

### Delete
- `x`: Delete a character.
- `dd`: Delete the current line.
- `dw`: Delete a word.
- `d$`: Delete to the end of the line.

### Undo/Redo
- `u`: Undo.
- `Ctrl + r`: Redo.

### Copy/Paste
- `yy`: Copy (yank) the current line.
- `yw`: Yank a word.
- `p`: Paste after the cursor.
- `P`: Paste before the cursor.

### Replace
- `r<char>`: Replace the current character with `<char>`.
- `R`: Enter Replace mode.

---

## VISUAL MODE
- `v`: Start visual selection.
- `V`: Start line selection.
- `Ctrl + v`: Start block (column) selection.
- `d`: Delete selected text.
- `y`: Yank (copy) selected text.

---

## SEARCH AND REPLACE
- `/pattern`: Search for `pattern`.
- `n`: Repeat the search forward.
- `N`: Repeat the search backward.
- `:s/old/new`: Replace the first occurrence of `old` with `new` in the current line.
- `:s/old/new/g`: Replace all occurrences in the current line.
- `:%s/old/new/g`: Replace all occurrences in the entire file.
- `:%s/old/new/gc`: Replace all with confirmation.

---

## WINDOW MANAGEMENT
- `:split`: Split horizontally.
- `:vsplit`: Split vertically.
- `Ctrl + w w`: Switch between windows.
- `Ctrl + w q`: Close the current window.
- `Ctrl + w o`: Close all other windows.

---

## BUFFER MANAGEMENT
- `:e file`: Open a file in a new buffer.
- `:ls`: List all buffers.
- `:b n`: Switch to buffer `n`.
- `:bd`: Close the current buffer.

---

## EXTRAS
- `:set number`: Show line numbers.
- `:set relativenumber`: Show relative line numbers.
- `:syntax on`: Enable syntax highlighting.
- `:set hlsearch`: Highlight search results.
- `:set nohlsearch`: Turn off search highlights.

---

## EXITING HELP
- `:q`: Exit help.

---

**Enjoy editing with Vim!** 😊
