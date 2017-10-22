# Bash-Tutorial
A cheat sheet for bash

`pwd` prints working directory
`ls` lists contents of current directory
`ls -l` list contents of current directory with extra details
`ls -a` list hidden files too
`ls /home/user/*.txt` lists all files ending with `.txt` inside `/home/user`

`cd` or `cd ~` change directory to your home directory
`cd folder1/folder2/` change directory to `folder2` inside `folder1`

`mkdir mydir` create a new directory named `mydir`
`rmdir mydir` remove directory `mydir`

`touch myfile` create or update a `myfile`

`cp myfile myfile2` copy `myfile` into `myfile2`
`cp -r mydir mydir2` copy `mydir` into `mydir2` (creates new directory if it doesn't exist)

`rm myfile` removes `myfile`
`rm -rf mydir` removes `mydir` and all its contents

`mv myfile mydir/` moves `myfile` into `mydir`
`mv myfile newfile` renames `myfile` to `newfile`
`mv mydir newdir` renames `mydir` to `newdir`

`cat file` outputs the contents of `file`
`cat > file` places standard input into `file` (`^c` to end)
`head file` output first 10 lines of `file`
`tail file` output last 10 lines of `file`
`tail -f file` output contents of `file` as it grows (`^c` to exit)

`nano` opens a terminal editor
`nano newfile` opens newfile for editing

`echo text` prints text on the screen
`echo text >> newfile` creates `newfile` with text

