# CSE 15L LAB Report #4 - Fnu Anu
## Step 4: Log into ieng6 
(STEP 1-3 were not asked to be included since it is just deleting the reportory and setting up)

The image below shows my input `ssh fanu@ieng6.ucsd.edu <enter>` into the terminal and its long output. Here:

![Image](LoggingIn.png)


Keys Pressed: `ssh fanu@ieng6.ucsd.edu <enter>` I was trying to log into my ieng6 account so I used this command in the terminal to access my account and use `<enter>` key press to get a bunch of lines about log in time, last login, notice, suggestions and other things until I was ready to clone lab7.

Summary of Commands: The command I used here was ssh which is to provide secure connection between 2 computers and access contents and so forth.

Effect of Key Presses: `<enter>` key press was needed to allow me to process that command in terminal.

### Step 5: Clone your fork of the repository from your Github account (using the SSH URL)

In the image below, you can see that I used `rm -rf lab7` to remove the lab7 from ieng6 account so to repeat the steps for this report. 

Then, you can see my input, `git clone git@github.com:fnuanu1/lab7.git <enter>` and its output saying that the repository was cloned successfully. Here:

![Image](removeClone.png)


Keys Pressed: On webpage, I did `<ctrl+c>` ssh url, switched back to VS Code terminal and I typed `git clone <ctrl+v> <enter>` From `ctrl+v`, this was outputted on that same command line in the teminal: `git@github.com:fnuanu1/lab7.git`. Here, I was trying to `git clone` the forked repository using the ssh url gotten from github webpage and then typed my `git clone` command & pasted the url.

Summary of Commands: I had already used `rm -rf lab7` to forcefully remove `lab7` from my previous attempts on my `ieng6` account. Mainly, I used `git clone` command to clone the repository from my github webpage account.

Effect of Key Presses: Here, I used `<ctrl+c>` to copy url, `<ctrl+v>` to paste/drop url into terminal and `<enter>` to make the command line processed in terminal. The effect of this is less time being wasted on my end to type in url tediously for any errors.

#### Step 6: Run the tests, demonstrating that they fail

The image for this step shows my commands prior to running through `bash test.sh <enter>` like `ls`, and `cd` commands to get into right directory and so forth to do the next few steps. This also shows the output when I run bash first without making any changes that two tests were ran and one of the two ran failed. Here:

![Image](bash1.png)


Keys Pressed: typed `ls <enter>` to list the directories or files to see if lab7 was cloned properly, typed `cd lab7 <enter>` to change directories to `lab7`, typed `bash test.sh <enter>` to run the command lines bashscript written in test.sh, which is pretty much compiling and running the java tests on the code.

Summary of Commands: In this step, I used three different commands, `ls`, `cd` and `bash` where `ls` - to confirm lab7 being cloned as listed in as the output. I changed directories into `lab7` directory and then run the `tets.sh` file which is ran by `bash command`.

Effect of Key Presses: As for the key presses here, I only used <enter> which is to process the command lines including `ls` to `cd` to `bash` commands as I type them into the terminal and use <enter> key press so to access and run the test files to see if tests failed or passed in this scenario.

##### Step 7: Edit the code file to fix the failing test

When I input, `vim ListExamples.java <enter>`, no input was directly made into the terminal. However, another textbox opened with the contents of the file I vimmed which was `ListExamples.java` and here I made changes by activating insertion mode and then saving and exit through `cl` text and `<esc> <shift + ;> wq> <enter>`. Here:

![Image](vim.png)


This picture is the before-math like before any changes were made:

![Image](vimFile.png)


This picture is the after-math like after all changes were made except I still have to press `<enter>` to confirm and exit after typing `<esc> <shift + ;> wq>`. I also noticed that when I press `<esc> <shift+;>`, no matter where the cursor was, the cursor moved to the end of file and allowed me to type `wq` to save and exit. By the way, `<shift+;>`equates to `:`. After, it will allow me to go back to the terminal and do next steps. Here:

![Image](after1.png)


Keys Pressed: typed `vim ListExamples.java <enter>` and then file's contents opened, `<down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down><down> <down> <down>` (19 times to get my cursor to the right position of error), typed `cl` as text and then insert mode was activated, so I changed `index1` to `index2` by <delete> or backspacing the last character `1` to swap it with `2` for variable `index2`, and finally, I hit `<esc> <shift ;> wq <enter>`. By the way, <shift+;> will output `:`.

Summary of Commands: Here, I used `vim` command to get into the file, ListExamples.java and edit it to correct code. In vimmed file, I used down arrows to get to correct location. Then I typed `cl` to activate `insert` mode in vim and correct the actual index. After being done, I used shift+; and then type wq and <enter> to allow this action to be processed so that the changes are saved and quitted back to terminal where it was left off as.

Effect of Key Presses: I think the only special key I pressed was `<down>` and `<shift+;>` which allowed me to get the cursor to wherever I want to make changes. In general, I realized that I can also click anywhere here directly just like in a file wherever I want to make changes. The `<shift+;>` is essential to be able to write the combination of wq which is to save and quit the vim command.

**Step 8: Run the tests, demonstrating that they now succeed**

Once again, I attempt to run `bash` again and this time, all tests had passed as seen below after changes we made earlier. Here:

![Image](bash2.png)


Keys Pressed: typed `bash test.sh <enter>` to re-run the command lines bashscript written in test.sh of lab7; same bashscript (no changes made) as in step 6.

Summary of Commands: `bash` command is used here to run the same set of commands written in this script file of test.sh except we don't have to cd into `lab7` prior to running bash since we are already in this directory.

Effect of Key Presses: <enter> key press was used here after `bash test.sh` was typed so to make the commands actually be run and we learn if all tests were passed, which was yes as shown in the image.

**Step 9: Commit and push the resulting change to your Github account (you can pick any commit message!)**

The image below shows that I tried inputting `git add . <enter>` to stage the files, but no message output or error was directly outputted so I continued. Here:

![Image](gitadd.png)


The image below shows that I inputted `git commit -m "done"` and some information about myself were being confirmed or outputted back at me in the terminal. Here:

![Image](gitcommit.png)


Lastly, I input `git push` to which I got more information spit back at me about information being transported in all packs and so forth to the remote repository and therefore, confirmed that it was successful. Here:

![Image](gitpush.png)


Keys Pressed: typed `git add . <enter>` to stage files, Next line: typed `git commit -m "done" <enter>` (to take snapshot of changes that were saved and made), Next line: `git push <enter>` (pushes the local repository to remote one - the one on our github webpage).

Summary of Commands: There are 3 various types of git commands we used here as desribed above. We used `git add .` to stage files, meaning that you are telling the terminal or preparing to push permanent changes to the repository's files. The `git commit -m "done" <enter>` is the command where "done" is the comment made when the git push is successfully made. Regardless, the said comment input, "done", is returned right after I entered this command line and then information about me as in who will be pushing out these changes is returned as a confirmation way of your identity. Then, lastly, `git push` is used to make any changes to the remote repository as well, which is the one we forked on our account's github webpage.

Effect of Key Presses: <enter> was the special key press that I used other than typing all these details so multiple commands were responsible for processing and saving content changes as part of this step.

**Final Screenshot of "done" message on github webpage:**

The image below also confirms a successful git push as "done" comment shows up when I refreshed the webpage to see if the changes were updated on the remote account, which is a yes here as seen. Here:

![Image](final.png)


**Overall Command Summary and Key Presses Effect:** The commands like `git add`, `git commit`, `git push`, `ls`, `cd`, `pwd`, `ssh`, `git clone`, `bash` and `vim`. As described above the details or summary of each of these commands, we overall used these commands to access account, clone respositories, access directories, change contents of the file, run the tests and push out those changes. The effect of Key Presses in general seems to shorten the time I spent typing each character so here, I realized that just like I used `<ctrl+c>` and `<ctrl+v>`, I must use other key presses to help me shorten the time it takes for me to complete a possible change in vim or in terminal so I should get in the habit of using `<tab>` and other shortcuts. Most of the time, I was just using `<enter>`, which allows the command line to be inputted and an output is produced accordingly through any of these commands used.
