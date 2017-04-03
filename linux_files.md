# Linux Commands

## Search  

* Find in file
`grep "some term" <file>`

* Find unique lines
`unique -u <file>` 

* Count occurences in file
`grep -o 'needle' <file> | wc -l`

* Get first x chars in file
`head -c 8 <file>`

* Find pattern in file with chars before and after
`grep -E -o ".{0,10}myString.{0,10}" <file>` 


## Vim

* Jump to line
`:1500` 
