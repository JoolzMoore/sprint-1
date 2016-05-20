command-line.md

The command line, what is it?

Apple Macs run on Linux and have an in-built interface called the terminal. The terminal is also called 'the console',  'a shell',  the 'command line' and 'the command prompt'.
It is a sophisiticated tool to edit without all the bells and whistles of a normal interface, so there's no searching for applications and/or menu items. To use the terminal we use the a command language interpreter (CLI), also known as a command-line user interface, console and also known as a character user interface (CUI).  The user (or client) issues commands to the terminal in the form of successsive  lines l of text. The command line via the terminal is the way to reach the processing power within your computer, it is faster and more powerful, but requires finding out what the commands are. These lines of code, has  it’s own different language, and sometimes the dollar symbol ‘$’ will show the beginning of a command line. The dollar symbol simply means that the rest of the line is a command, rather than a sentence. Also you may notice the text you've copied from a web page using Ctrl + C won't paste in with ctrl+V. But  you don't have to type in all those nasty commands and filenames? Just use ctrl+shift+V for pastes into the terminal. As the command -line language is very powerful, and it can prove to be a big risk for the uninitiated - as you have the capability to instruct the computer to do almost anything! So if you instruct the computer to erase all your data - it will then proceed to do it. Therefore command lines are not to be used in an experimental way, and it's a good idea to research and comprehend what scommands do what -  especially if the command involves changing or removing files. The command line can do countless commands such as changing the syntax type for a current document, installling plug-ins, searching for snippets and things like  renaming 100+ files in a directory can be done in less than a minute. When you type a command in terminal, it's esxecuted in your current location, unless you specify otherwise.

~
The tilde symbol stands for your home directory

cd
To change your location, use cd followed by the path of the location you want to move to.

cd ~/
To return to the default, type cd ~/ and your location will change from wherever you are to your Home directory.d: The cd command will allow you to change directories. When you open a terminal you will be in your home directory. To move around the file system you will use cd. Examples:
To navigate into the root directory, use "cd /"
To navigate to your home directory, use "cd" or "cd ~"
To navigate up one directory level, use "cd .."
To navigate to the previous directory (or back), use "cd -"

cp
The cp command will make a copy of a file for you. Example: "cp file foo" will make an exact copy of "file" and name it "foo", but the file "file" will still be there. If you are copying a directory, you must use "cp -r directory foo" (copy recursively). (To understand what "recursively" means, think of it this way: to copy the directory and all its files and subdirectories and all their files and subdirectories of the subdirectories and all their files, and on and on, "recursively")

control- C
And you can interrupt a command by pressing Control-C.

defaults write com.apple.screencapture name "file-name"; killall SystemUIServer
This changes the default name for screenshots. Replace the-file-name with whatever you like and screenshots will now be given that name followed by the date and time.
escape
To see a list of available commands, hold down the Escape key and then press 'y' when asked if you want to display a specific number of possibilities. 

factor
for mathematical output. This command outputs all the possible factors of a given number.

lp
command used to print files.

ls
View a list of the files and folders in your current location.

ls ~
will show you the files that are in your home directory.

man
The man command is used to show you the manual of other commands. Try "man man" to get the man page for man itself!

mkdir
The mkdir command will allow you to create directories. Example: "mkdir music" will create a directory called "music".

mkdir -p
This command allows you to create all directories up to and including the last one... so that you don't have to make one directory at a time.

mv
The mv command will move a file to a different location or will rename a file. Examples are as follows: "mv file foo" will rename the file "file" to "foo". "mv foo ~/Desktop" will move the file "foo" to your Desktop directory, but it will not rename it. You must specify a new file name to rename a file.

pwd: The 'pwd' command will allow you to know in which directory you're located (pwd: stands for "print working directory").

rev
For a bit of fun “rev” means reverse., and so it  reverses every string or command line given to it!

rm
Use this command to remove or delete a file in your directory.

rmdir
The rmdir command will delete an empty directory. To delete a directory and all of its contents recursively, use rm -r instead.

scp
for copying files from server to server

subl.
to enable work with files on the command line. This can be used to open files and projects in Sublime s

command line shortcuts:
q
quits window

up arrow + return or Ctrl + P
Re-run previous commands without re-typing them by using the up arrow on the keyboard to navigate to the command and then pressing Return. It scrolls through the commands you've entered previously.

Down Arrow or Ctrl + N
Takes you back to a more recent command.

tab
A very useful feature. It autocompletes any commands or filenames, if there's only one option, or else gives you a list of options.

Ctrl + R
Searches for commands you've already typed. When you have entered a very long, complex command and need to repeat it, using this key combination and then typing a portion of the command will search through your command history. When you find it, simply press Enter.

Ctrl + A or Home
Moves the cursor to the start of a line.

Ctrl+ E or End
Moves the cursor to the end of a line.

Esc + B
Moves to the beginning of the previous or current word.

Ctrl + K
Deletes from the current cursor position to the end of the line.

Ctrl + U
Deletes from the start of the line to the current cursor position.

Ctrl + W
Deletes the word before the cursor.

Alt + B
Goes back one word at a time.

Alt + F
Moves forward one word at a time.

Alt + C
Capitalizes letter where cursor is and moves to end of word.
!!
Repeats the line last entered at the shell. See history command for previous commands.

!$
Repeats the last argument for the command last used. See history command for previous commands.

reset
Resets the terminal if terminal screen is not displaying correctly.

shutdown -h now
Remotely or locally shuts the system down.
