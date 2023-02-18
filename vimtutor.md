### Vim Command

### Inserting  
`i, I, a, A, o, O`

i : From current cursor  
I : From first place of current line  
a : From next to the current cursor.  
A : From last place of current line.  
o : From first place of one previous line.  
O : From first place of one next line.  

### Goto without Inserting  
`0, ^, $, w, e, b, B, gg, G`
0 : Goto first place of current line.  
^ : Goto first place of current line.  
$ : Goto last place of current line.  
w : Goto first place of next word.  
e : Goto last place of next word.  
b : Goto first place of previous word.  
B : Goto last place of previous word.  
gg : Goto first place of first line of the current file.  
G : Goto first place of last line of the current file.  
  
- w,e,b,B can be preceeded with numbers so it does the task accordingly.  


### Deletion  
`dw, de, d$, `
  
dw : delete until the start of the next word.  
de : delete to the end of the current word.  
d$ : delete to the end of the line.  
