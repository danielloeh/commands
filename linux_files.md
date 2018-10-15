# Linux Commands

## Search  

## Content

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

## Files
* Find recursivly in files, maching a certain type
`grep -r --include="*.java" 'RUN_JOBS' ./`

### List file size
* Lists *disk usage* recursivly and orders by the numberic value
`du -h . | sort -n`


## Vim

* Jump to line
`:1500` 

* Flip lines
cmd mode: `ddp`

* Beginning - End of the line
cmd mode: `0` - `$`

* Beginning/End of the file
cmd mode: `gg` - `G`
