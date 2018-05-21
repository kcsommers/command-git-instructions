# Navigation Terminal
**cd** -> change directory
- cd ~ -> change directory to home
**ls** -> display short list of current directory content
**l** -> display complete file information in directory
**pwd** -> print/present working directory - where am I?
**open** -> open a file in default program or directory in finder

# File Manipulation
**man** -> will pull up manual for commands
- `man [command here]` -- will display info about command - q to exit
**|** -> pipe will execute command on left first then execute command on right
- `[command here] | [second command here]` - does not work for every command
**>** -> redirect output to a file
- `echo 'text to add' > [File Name]` - output directed into file  !!!Will overwrite what is there.
- `echo 'text to add' >> [File Name]` - output appended into file
**mkdir** create new directory from current position
**touch** create new file within current directory
**mv** -> move files
- `mv [current file name] [new file name]` -- will rename the file
- `mv [current file name] ./newdirectory/[new file name]` -- will move file and rename, directory must exist 
**rm** -> removes files or directories !!!scary cannot undo
- `rm [file name]` -- removes file from system
- `rm -r [directory name]` -- removes directory and all subsequent files 
**grep** -> will search through documents for strings
- `cat [file name] | grep 'string to search'` - will search contents of file and return string found
- `-n` -- will display line number of found string
- `-A [number here]` -- will display trailing number of lines specified
- `-B [number here]` -- will display preceding number of lines specified
**cat** -> reads file(s) and outputs to terminal
- `cat [file name]` - will display file contents
- `cat [file name] [file name]....` - will display file contents of all files selected in order

# Git commands
**git init** -> this will add a local git repository to a directory
**git status** -> show files that are untracked or tracked for next commit
**git add** -> will add files to staging for next commit
- `git add [file name]` - will add individual file ot staging
- `git add -A` - will add all files to staging
- `git add .` - will add all files to staging
**git commit** -> takes staged files and creates safe point / commit number
-`git commit -m 'enter in meaningful commit message'`
**git log** -> shows full log of all commits to master branch
**git push** -> sends commits to github