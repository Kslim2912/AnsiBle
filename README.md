# AnsiBle

Install OPENSSH ON SERVER
	sudo apt install openssh-server
INSTALL TMUX
	sudo apt install tmux	
	tmux attach - opens closed session
	tmux a - opens closed session
	CTRL D exit
	tmux = open tmux
OPEN MULTIPLE PANES:
	CTRL B = To give instructions to TMUX (Send Prexif)
	" - Horizantal split Panes
	% - Vertical Split Panes
	CTRL B and left arrow
Creating and Managing Windows
	CTRL B + C = Create new Windows
	CTRL B + P = Previous opened windos
	CTRL B + N = Next window
	CTRL B + Shift 7(&) = Kill Open Window
	CTRL B + X = Kill Open Window
	CTRL B + , = Rename Window
	CTRL B + $ = Rename Session
Creating and Switching Between Sessions
	CTRL B + D = Disconnect From tmux
	tmux list-sessions = Show open sessions running
	tmux ls = Show open sessions running
	tmux attach -t 1 (Enter) = Open Session 1
	CTRL B + $ = Rename Session
	tmux new -s "give session name" = Name the session of Tmux as you create and open 
	CTRL B + S = List open sessions

