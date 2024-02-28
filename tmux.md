# Tmux: Your Terminal Multiplexing Masterclass

## Tmux in a Nutshell

- **Multiple Shells, One Screen:** Run multiple terminal sessions simultaneously.
- **Detachable and Persistent:** Detach and reattach to sessions without losing work.
- **Organize Your Workspace:** Split screen into windows and panes for efficiency.

## Getting Started

1. Start a session: `tmux`
2. Detach: `Ctrl + b` then `d`
3. Reattach: `tmux attach`

## Window Management

- Create window: `Ctrl + b` then `c`
- List windows: `Ctrl + b` then `w`
- Next window: `Ctrl + b` then `n`
- Prev window: `Ctrl + b` then `p`
- Rename window: `Ctrl + b` then `W`

## Pane Management

- Split horizontally: `Ctrl + b` then `%`
- Split vertically: `Ctrl + b` then `"
- Next pane: `Ctrl + b` then `o`
- Prev pane: `Ctrl + b` then `h`

## Bonus Tips

- Copy mode: `Ctrl + b` then `[`, select with arrows, `y` to copy.
- Kill window: `Ctrl + b` then `x`
- Kill session: `tmux kill-session -t <session_name>` (find name with `tmux ls`)

## Remember: Practice makes perfect!

Explore more at:

- https://tmuxcheatsheet.com/
- https://github.com/tmux/tmux  nvim.md
