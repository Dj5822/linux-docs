## Stage 1: Basic survival
```
i       insert
Esc     normal mode
:w      save
:q      quit
:wq     save + quit
:q!     discard
```

## Stage 2: Stop using arrow keys/mouse
```
h j k l     move
w           next word
b           previous word
0           start of line
$           end of line
gg          top of file
G           bottom of file
```

## Stage 3: Editing efficiently
```
dd          delete line
yy          copy line
p           paste
x           delete character
u           undo
Ctrl+r      redo

dw          delete word
cw          change word
d$          delete to end of line

d = delete
c = change
y = yank

w = word
$ = end of line
} = paragraph
```

## Stage 4: Search and replace
```
/foo = search for foo

n = next match
N = previous match

:%s/old/new/g = replace old with new
```

