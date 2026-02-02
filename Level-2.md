* Goal: * Obtaining the password from a file located in the main directory that has spaces in its filename.

* Solution Steps: *

1 - Use the `ls` command to view the file in the directory. You will see a file whose name has "--" characters at both the beginning and the end.

2 - The file name starts with --. Therefore, using `cat filename` will not work, because the terminal might mistake it for a command parameter. To prevent this, we need to specify the file path as `./`.

3 - To preserve the integrity of spaces in the file name, we need to enclose the name in quotation marks. 
The command to be used will be: `cat ./"--spaces in this filename--"`
