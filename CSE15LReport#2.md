# CSE 15L LAB Report #1 - Fnu Anu
## Part 1:
Below are the two screenshots of my code file:
![Image](CodePart1.png)
![Image](codeChatServer.png)


Then, I used javac and java command appropriately like such to open a server:
![Image](Terminalpart1.png)


Here are the two screenshots of me adding /add-message?s=<string>&user=<string> to the server url and here were the results:


1) Below I entered 'Hi' as message and 'Anu' (my name) as the user.
![Image](Firstpart1.png)


2) Secondly, I entered 'How are you' as the message and 'bro' as the user.
![Image](Bothpart1.png)
As a result, we saw that the string keeps being updated and saved even when we add more messages by different or various users.


For each of the two screenshots, describe:

**1st screenshot:**
1. Which methods in your code are called? `Main` method from `ChatServer` class in order to open the server and `handleRequest` method from `Handler` class is used to perform identified requests with message and user here similar to num being incremented in NumServer.
   
2. What are the relevant arguments to those methods, and the values of any relevant fields of the class? The relevant argument for main method was the port number being identified after `javac ChatServer` where after `ChatServer`, this `main` method is trying to identify the port number which in my case is 4000. The `port` from main method is one of the relevant fields that change based on the port number entered by the user, so the server number that the user is connected to will change accordingly. As for the `Handler` class, url of the server that we open in the browser is the parameter to handleRequest method where if certain patterns are found in queries, such special characters can be used to split apart the contents that we need. So the url would be different when I enter `/add-message?s=How are you&user=Bro` is different paramter than when I enter `/add-message?s=Hi&user=Anu`. The relevant field is `start` which is an empty string, but eventually gets updated and added with information of message and the user accordingly. 


3. How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why.

**2nd screenshot:**
1. Which methods in your code are called? `Main` method from `ChatServer` class in order to open the server and `handleRequest` method from `Handler` class is used to
2. What are the relevant arguments to those methods, and the values of any relevant fields of the class?
3. How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why.

   
### Part 2:
Using the command line, show with ls and take screenshots of:

The absolute path to the private key for your SSH key for logging into ieng6 (on your computer, an EdStem workspace, or on the home directory of the lab computer)
The absolute path to the public key for your SSH key for logging into ieng6 (this is the one you copied to your account on ieng6, so it should be a path on ieng6's file system)
A terminal interaction where you log into your ieng6 account without being asked for a password.


### Part 3: My Reflection on learning:
Something I had learned in Week 2 and Week 3 lab that I did not even knew was on how to open the server, make the handler requests or how to even write code to make the server perform some action like saving User and Message here. I also did not knew much on local computer terminal use and logging in using ieng6 to copy public key or without login, accessing private keys or even where the download files go or which path. In these two past weeks, I was able to use the skills about `cd`, `ls` and `cat` from week 1 into practical uses to perform other tasks, realizing the benefits and uses of those commands these past two weeks. 
