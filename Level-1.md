Bandit: Level 1
When we look at the directory with the ls command, we see a single file named: -. If we type cat - using the classic method, the terminal does not recognize this dash as a filename; instead, it treats it as a special command parameter and fails to display the file content.

We need to prove to the terminal that this is a "path." To do this, we use the cat ./- command by adding the ./ symbols, which represent our current directory, to the beginning of the filename.

Critical Note: When interacting with files in Linux, using a Relative Path (like ./-) for filenames that start with special characters prevents the terminal from getting confused.
