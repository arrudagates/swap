# swap
Swap files or directories between each other

Syntax: `swap [file/dir] [file/dir]`

Example with directories:

```zsh
➜  ~/test ls dir1
file1
➜  ~/test ls dir2
file2
➜  ~/test swap dir1 dir2
➜  ~/test ls dir1
file2
➜  ~/test ls dir2
file1
```

Example with files:

```zsh
➜  ~/test cat file1
1
➜  ~/test cat file2
2
➜  ~/test swap file1 file2
➜  ~/test cat file1
2
➜  ~/test cat file2
1
```
