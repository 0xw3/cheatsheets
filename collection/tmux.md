# Tmux Cheat Sheet

## Session Management
- `tmux new -s [session-name]`: create a new session with a name
- `tmux attach -t [session-name]`: attach to an existing session
- `tmux switch -t [session-name]`: switch to an existing session
- `tmux list-sessions`: list all sessions
- `tmux detach`: detach from the current session
- `tmux kill-session -t [session-name]`: kill an existing session

## Window Management
- `Ctrl-b c`: create a new window
- `Ctrl-b ,`: rename the current window
- `Ctrl-b n`: move to the next window
- `Ctrl-b p`: move to the previous window
- `Ctrl-b w`: list all windows
- `Ctrl-b &`: kill the current window

## Pane Management
- `Ctrl-b %`: split the current pane vertically
- `Ctrl-b "`: split the current pane horizontally
- `Ctrl-b o`: switch to the next pane
- `Ctrl-b ;`: toggle between the current and previous pane
- `Ctrl-b x`: kill the current pane

## Miscellaneous
- `Ctrl-b d`: detach from the current session
- `Ctrl-b ?:` show a list of all tmux keybindings
- `Ctrl-b t`: show the time in the status line
- `Ctrl-b [`: enter copy mode to scroll through the buffer
- `Ctrl-b ]`: paste the contents of the buffer

