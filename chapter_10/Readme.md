#Chapter 10

##English Questions

>Can you copy the foo.txt file to slash temp?  (Create foo.txt first...)

Yes:
echo 'test' > foo.txt
cp foo.txt /tmp
cd /tmp
Result is this
Jhis-MacBook-Pro:tmp $ ls
KSOutOfProcessFetcher.502.sAglCyxY5lzPoNgfmEvv-ZqGl-w=
com.apple.launchd.7urkhrJZzu
com.apple.launchd.luseJq1giM

>Can you copy .bash_profile in your home directory to the current directory?

Yes, I used this command while I was in the workspace directory and it worked.

cp .bash_profile ~/workspace

##Do More

>Use the cp -r command to copy more directories with files in them.

This command copies the contents of one folder into another folder.

>Copy a file to your home directory or desktop.

I tried this command and it worked. cp Otherfile.txt ~/

>Find these files in your graphical user interface and open them in a text editor.

In the same way that I would cd into these, I can follow the same path and get to these through the finder.

>Notice how sometimes I put a / (slash) at the end of a directory? That makes sure the file is really a directory, so if the directory doesn't exist I'll get an error.

I tested this and this is the error I recieved:

Jhis-MacBook-Pro:chapter_5 $ cd Readme.md/
bash: cd: Readme.md/: Not a directory

##Robocopy Explanation

Robocopy means robust file copy, it was a command that also copy full files.

