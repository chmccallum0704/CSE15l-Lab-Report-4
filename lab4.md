# Lab 4: Vim (Week 7)
Caitlin McCallum

## Step 1: Log into ieng6

Keys Pressed: `<up><enter> cs15lwi24<enter>`

Reason: The `ssh chmccallum@ieng6-201.ucsd.edu` command was 1 up in the history, so I used the up arrow to access it. I then typed `cs15lwi24` in order to begin work for this course.

## Step 2: Clone your fork of the repository from your Github account (using the SSH URL)

Keys Pressed: `git<space>clone<command + v><enter>`

Reason: I used the `git clone` command with my SSH Url which I copied then pasted from my browser. I then pressed `enter` to execute command.

## Step 3: Run the tests, demonstrating that they fail

Keys Pressed: `ls<enter>cd<space>lab7/<enter>bash<space>te<tab>`

Reason: I entered the `ls` command to view the contents of my current working directory, then `enter` to execute the command. I then entered `cd lab7/` to change directories to the appropriate one in order to run the `test.sh` bash script. I then used the `tab` key to autofill the file name `test.sh`.

## Step 4: Edit the code file to fix the failing test

Keys Pressed:  `ls<enter>vim<space>List<tab>.java<enter>kkkkkexi2<esc>:wq<enter>`

Reason: I entered the `ls` command to view the contents of my current working directory, then `enter` to execute the command. I then used the `vim` command on `ListExamples.java`, using `tab` to autofill the file name after `List` in order to edit the `ListExamples.java` file using vim, I then pressed `enter` to execute. The keys `kkkkk` were pressed once I was in the vim interface in order to move the cursor up by 5 lines. The `e` key press brought my cursor to the end of the first word `index1`. `xi2` are the keys I pressed to cut the character my cursor was on, then insert using `i` a 2. These keystrokes allowed my to fix the code found in `ListExamples.java`.

## Step 5: Run the tests, demonstrating that they now succeed

Keys Pressed: `<up><up><up><up><enter>`

Reason: the `bash test.sh` command was 4 up in the history, so I used the up arrow to access it and `enter` to run it.

## Step 6: Commit and push the resulting change to your Github account

Keys Pressed: git<space>status<enter>git<space>add<space>Li<tab><enter>git<space>commit<space>-m<space>"fixed<space>code<space>for<space>merge"<enter>git<space>push<space>origin<space>main<enter>

Reasoning: I entered `git<space>status` in order to confirm that I had uncommited changes from editing the `ListExamples.java` file. I then used the `git<space>add<space>Li<tab><enter>` to add my edited `ListExamples.java` file to commit, note that `tab` was entered after `Li` in order to autofill the file name. I then entered git<space>commit<space>-m<space>"fixed<space>code<space>for<space>merge"<enter>` in order to commit my saved file with the message "fixed code for merge". The final command block `git<space>push<space>origin<space>main<enter>` was used to push my commit to gitHub.
