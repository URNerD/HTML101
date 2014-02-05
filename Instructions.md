This will be a day where you accomplish (or at least attempt) a ton! Take it easy, be patient with yourself and talk with your partner. It’s ok if you find it challenging – even very challenging. Just help me understand what you need help understanding…

# HTML101 Instructions

### Set up a GitHub account

1.	Find a programming partner and log on.
2.	Create an account for yourself on GitHub (github.com). GitHub is a “social networking site” for programmers.
3.	Send me an e-mail (douglas.urner@highlineschools.org) with your username.
4.	Create a new Repository (aka repo) and give it a name you like – I called mine HTML101.
5.	Give it a description of some sort (this will become the README file).
6.	Then, check the “initialize repository” box, and then click on the green Create Repository button at the bottom.
7.	If you forget to check the box, you will get to dive deeper into get than you might have wanted, but it will be just fine. Or you can start over.
6.	Note the “HTTPS clone URL” box on the right hand side of the window – you’ll want it later.

### Create a Source directory on the Mac

7.	Start up the program Terminal.
8.	Go to your home directory (type the command cd).
9.	Make a new directory called “Source” (mkdir Source).
10.	Go there (cd Source).

### Clone the git repository you created

11.	Go back to the GitHub window in your browser and get a copy of the URL (type Command-C or use the clipboard button).
12.	Get a clone of your repository (git clone Command-V). Typing Command-V pastes the URL you just copied. When you hit enter magic happens and you get a copy of the files from GitHub.

### Meet the Unix / Linux / Mac command line

13.	Use the ls command, and ls –l to see what just happened.
14.	Now take some time to make peace with a text editor. This part will take some time, but you need to be able to create a “plain text” file and programs like Word can’t do that without a lot of griping… There are several, in rough order of pain (and power):
  *	TextEdit – this is the "standard" Mac editor/wordprocessor, you'll need to make sure that you are saving a plain text file (not Rich Text) and that you give the file an extention of .html. By default, the Mac hides extentions. There is a checkbox in the file save dialog that makes the extention visible.
  *	PhpStorm – is an IDE, an integrated development environment. That's a fancy way of saying that it is kind of complicated, but once you get past the complications it is very helpful because it "understands" programming languages and processes. For example it knows how to talk with git.
  *	vi – pronounced "vee eye," is the "standard" Unix (or UNIX if you must) text editor. It was originally written before the days of WYSIWYG word processors. It is a modal editor. In command mode what you type moves the cursor and gives other commands to edit text. In insert mode what you type becomes part of the file. You should try it out, it is a useful part of a web developer's toolkit. Vi is the mortal enemy of emacs.
  *	emacs – is another "old" text editor. Unlike vi, emacs is not modal. You are always in "insert mode," to issue commands you use modifier keys as you type. For example control-f (or C-f) moves the cursor forward (to the right) one character, C-b goes backwards, C-n goes down to the next line, and C-p goes up to the previous line. If you'd like to stir things up announce to a group of Unix people that "emacs is the best editor ever." If someone takes the bait, sit back and watch (http://xkcd.com/378).
15.	The things you have to be able to do right now are create a new file, type some text into it and save it. The rest comes later…

### Start the basic HTML tutorial

16.	Go to the tutorial at: http://htmldog.com/guides/html/beginner and get started.
17.	Add your file to git (git add file-name).
18.	After each step commit (git commit –a –m “name of step here”), and then push (git push) your changes. The first time you push you’ll be asked for your username and password.

If you get to here you are amazing and have accomplished a ton!
