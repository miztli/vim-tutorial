### Vim modes
  - Interactive mode (i)
  - Normal mode
  - Visual mode (v)

### Cursor
Move cursor using:
  - left -> h
  - right -> l 
  - up -> k
  - down -> j

### Navigate text
  - words -> w
  - beginning -> b
  - end -> e
  - jump n words -> 3w

### Insert text repeatedly
  -  With editor in normal mode, type: 
     3i + word + esc + enter

### Duplicate line
  - type: yy to copy all line
  - type: p to paste it anywhere

### Delete all line
  - type: D or dd

### Clear all line; to insert mode
  - type: S

### Find next text occurence
  -  With editor in normal mode, type:
     fo -> to find the next o
     3fo -> to find the third occurrence of o

### Go to matching parenthesis
  - Press: shift + % {"users":[{"id:1"},{"id":2}]}

### Go to start and end of line
  - start: 0
  - end: shift + %

### Find word under cursor
  - previous: #
  - next : *

### Begin / end of file
  - begin: gg
  - end: G
  - go to line: 4G

### Text search
  - type: / + word
    then press n to find next occurence

### Create a new line
  - press: O or o to insert a new line above or under respectively

### Remove character
  - remove left: x
  - remove rigth: X

### Replace letter under cursor without changing to interactive mode
  - move cursor to letter, press: r, and type new letter

### Delete words
  - type: dw, to delete word
  - type: d2w, to delete 2 words

### Repeat command
  - type: . to repeat previous command  

### Visual mode
  - type: v
  - select word: e
  - delete: d
  - copy: y
  - or paste: p

### Save, write, quit
  - save: :w
  - save and quit: :wq
  - quit: :q
  - quit without saving: q!

### Find and replace
  - Ask for confirmation: :%s/foo/bar/gc  
  - Do not ask for confirmation: :%s/foo/bar/g
  - To search only in the current line, remove: %

### Collapse
  - fold: zm
  - unfold: zn

### Comment
  - type: Ctrl+v, then
  - move cursor, then
  - type: Shift + i
  - type: // or ##, then
  - type:  ESC
