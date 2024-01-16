# CSE 15L LAB Report #1 - Fnu Anu

## `cat` Command:

**Example 1**: `cat` with a path to a directory:
   
WD: `/home/` 
 
![Image](cat-directory.png)

 Explanation - When we put the argument `./lecture1/messages` into the `cat` command when we were in home directory originally, path leads to `lecture1` directory inside home and then `messages` directory inside the `lecture1` directory. It outputted an error saying that what the path led to is a dircetory that the `cat` command is not expecting as an argument. I believe I got this output because the `cat` command is supposed to read contents of files which is not possible if it is led to a directory where there can be multiple files stored so the `cat` command does not have much autonomy to choose which file it wants to read, if all or what specifically the user wants the command to access within the said directory or if the user even wanted that. Due to ambiguity, the `cat` command threw an error.

 Error or not - This is an error since the argument points to the fact that the argument led to a directory (or folder) where it does not exactly where to go or which file the user wants it to access and return the contents of so since the `messages` is a directory, it simply throws an error to let user know that the input might be wrong or the user's expectations are not specified enough.

**Example 2**: `cat` with a path to a file:
   
WD: `/home/`
 
![Image](cat-filePath.png)

Explanation - For this example, I inputted a path to a file from `home` directory to an existing directory inside `home` directory called `lecture1` which is further pathed to `messages` directory to further refer to a `.txt` file name called `en-us.txt`. I use a single line, `./lecture1/messages/en-us.txt` to connect all these paths to get to my said file and the output is simply returning the contents that had been stored in my file, `en-us.txt`, which simply stored `Hello World!` so that was what was returned. I probably got this output because the command reads the contents of the file when inputted a file name or a path to a file.

Error or not -  Not an error!

**Example 3**: `cat` with no args:

WD: `/home/`

![Image](cat-noArgs.png)

Explanation - I was in the `home` directory when I had entered `cat` command with no arguments. In response, the terminal became a little interactive where the terminal prompt disappeared and everytime I had entered any input, it simply copied and returned my input, possibly because it is waiting for me to enter an argument after not receiving any argument in the `cat` command initially. This is how I ended up entering a '?' only to receive a '?' back as well as 'Hello Buddy' exactly how I had entered it probably because `cat` command reads the contents of the files when the file names are inputted which in this case, it hadn't received in this case at all so it created another way for the user to interact with it.
 
Error or not - Not an Error!

___


### **`cd` Command:**
**Example 1**: `cd` with a path to a directory:
   
WD: `/home/`

![Image](cd-directory.png)

Explanation - For this example, I used `lecture1` as my argument in `cd` command where I am in home originally, but it changes my working directory to '/home/lecture1' where `lecture1` is a directory existing within my `home` directory. I got this output because my inputted path (argument) was a directory that the `cd` command had been able to process.
 
Error or not - Not an error!
   
**Example 2**: `cd` with a path to a file:

WD: `/home/lecture1/messages`

![Image](cd-filePath.png)

Explanation - For this example, I am directly in `messages` which contains a few `.txt` files so when I used `./en-us.txt` to see if the cd would allow me to go more specific than a directory, but it simply ended up throwing the error how the file that was inputted does not lead to directory to change to. I probably got this output since this command is supposed to change directories which can certainly not happen if I lead it to a file.
 
Error or not - Error because the path leading to the file, `en-us.txt`, is not exactly a directory for the command to help change to so it throws an error saying that it is not what something it was expecting.

**Example 3**: `cd` with no args: 

WD: `/home/lecture1`

![Image](cd-noArgs.png)

Explanation - When we put in cd with no arguments, the default for `cd` command is to return to `home` directory so that is why I got back to `home` directory even though I was inside the `lecture1` directory existing inside the `home` directory.
 
 Error or not - Not an Error!
 
 ___
   

#### **`ls` Command:**
**Example 1**: `ls` with a path to a directory:

WD: `/home/`

![Image](ls-directory.png)
 
Explanation - For this example, I used a path to another directory existing within `home` directory, known as `lecture1`. My output was all the files existing in that directory like `Hello.class`, `Hello.java`, `messages` and `README`. I also noticed that it did not went into the specific files that `messages` folder contained, just the names of files or directories that `lecture1` directory contains without going into even more paths of the directories existing within it. I think I got this output from inputting a directory path because `ls`'s job is to list the files and directories so leading it to a directory will allow it the access to name the files inside it for me.
 
Error or not - Not an error!

**Example 2**: `ls` with a path to a file:

WD: `/home/lecture1/messages`

![Image](ls-filePath.png)

Explanation - The `en-us.txt` is the name of `txt` file that exists inside the messages along with other `txt` files like `punjabi.txt` and others. When I entered the path to a file name, `./en-us.txt`, as the argument, it just returns the file name that was entered since there is no other files or directory that `ls` can detect within that file.
 
Error or not - Not an Error!

**Example 3**: `ls` with no args:
   
WD: `/home/`

![Image](ls-noArgs.png)

Explanation - When we enter `ls` command with no arguments, it returns the two folders' name, `lecture1` and `directory2`, that exist in the `home` directory. I got this output because the `ls` command is supposed to list the files or directories that exist under the `home` directory when I don't put any arguments.
  
Error or not - Not an Error!

___
   
