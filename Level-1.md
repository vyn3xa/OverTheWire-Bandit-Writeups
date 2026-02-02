# Bandit: Level 1

**Goal:** Access the password located in the file named.

**Solution Steps:**

1 - When we inspect the directory using the ls command, we see a single file: `-`

2 - We need to prove to the terminal that this is a "file path." If we try the classic method and type `cat -`, the terminal does not recognize the dash as a filename; instead, it treats it as a special command parameter and fails to display the file's content. So we add `./` to the beginning of the filename and use the command `cat ./-`. When we add `./` at the beginning, it prevents the filename from being interpreted as a parameter. It indicates that it is a file.

**Critical Note:** When interacting with files in Linux, using a Relative Path (such as ./-) for filenames that start with special characters prevents the terminal from getting confused.
