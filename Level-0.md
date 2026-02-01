# Bandit: Level 0

**Goal:** Establish the initial SSH connection to the server and find the first level password.

**Solution Steps:**

1 - Upon logging into the server, we automatically start in the home directory.
I used 'ls' command to see which files are located here. The output shows that only the readme file exists.

2 - To reveal the hidden password inside the file, we run the 'cat readme' command.
