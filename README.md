Vim Tutor

Escape/Normal Mode: esc
Insert mode: i
View mode: v


Undo: u
Redo: cntr + r


Movement: (normal mode)
	h - left
	j - down
	k - up
	l - right

	Big jumps
	{ - jump up paragraph
	} - jump down paragraph

	b  - pull cursor back to first char of prev word
	w  - push cursor to first char of next word

	ge - pull cursor back to last char of prev word
	e  - push cursor to end of current word

	g  - bring you top of page
	G  - bring you bottom of page
	:# - bring you to certain line #


Movement: (Insert Mode)
	A - insert at the end of a line
	I - insert at the start of a line
	i - insert before the cursor
	a - insert after the cursor
	o - insert below line
	O - insert above line
	

Copy/Paste: (notice deletion is the same as cut in vim)
	p - paste on cursor line
	P - paste on bottom line

	d - cuts line
	d motions


Deletion: d motion

	d      - is the delete operator.
	motion - is what the operator will operate on (listed below).

	A short list of motions:

	w - until the start of the next word, EXCLUDING its first character.
	e - to the end of the current word, INCLUDING the last character.
	$ - to the end of the line, INCLUDING the last character.