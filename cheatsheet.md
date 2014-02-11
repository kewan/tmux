Commands
========

`
tmux new -s session-name  
tmux a -t session-name  
tmux ls  
tmux kill-session -t session-name
`

Shortcuts
=========

All with leader of Ctrl-b

`?` help  

Session management
------------------

`s` list sessions  
`$` rename current session  
`d` detach from current session  

Windows
-------

`c` create a new window  
`,` rename current window  
`w` list windows  
`%` split horizontally  
`"` split vertically  
`n` change to the next window  
`p` change to the previous window  
`0 to 9` select window 0-9  

Panes
-----

`%` create a horizontal pane  
`"` create a vertical pane  
`q` show pane numbers  
`o` toggle between panes  
`}` swap with next pane  
`}` swap with previous pane  
`!` break the pane out of window  
`x` kill the current pane

References
==========

http://www.danielmiessler.com/study/tmux/
