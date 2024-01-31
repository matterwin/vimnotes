Vim Tutor

Escape/Normal Mode: esc
Insert mode: i
View mode: v


Undo: u
Redo: ctrl + r


Administrative:
	:w   = save
	:q   = exit
	:wq  = save and exit
	:q!  = quit without saving


File/Folder Navigator:
	gt   = next tab
	gT   = prior tab
	#gt  = numbered tab
	:ls  = list of file buffers


Movement: (normal mode)
	h   = left
	j   = down
	k   = up
	l   = right

	Big jumps
	{   = jump up paragraph
	}   = jump down paragraph

	b   = pull cursor back to first char of prev word
	w   = push cursor to first char of next word
	ge  = pull cursor back to last char of prev word
	e   = push cursor to end of current word

	g   = bring you top of page
	G   = bring you bottom of page
	:#  = bring you to certain line #

	0   = bring you to start of line
	$   = bring you to end of line


Movement: (Insert Mode)
	A   = insert at the end of a line
	I   = insert at the start of a line
	i   = insert before the cursor
	a   = insert after the cursor
	o   = insert below line
	O   = insert above line
	

Editing/Deletion: (notice deletion is the same as cut in vim)
	yy  = copy line
	y   = copy selected text in visual mode
	d   = cut selected text in visual mode
	x   = cut the char on which the cursor is on

	p   = paste on cursor line
	P   = paste on bottom line

	>   = shift left once
	<   = shift right once

	dd  = cuts line
	dw  = until the start of the next word, EXCLUDING its first character.
	de  = to the end of the current word, INCLUDING the last character.
	d$  = to the end of the line, INCLUDING the last character.
