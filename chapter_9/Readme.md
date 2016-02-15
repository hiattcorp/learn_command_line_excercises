#Chapter 9 Questions

##Can you touch blah.txt?

####touch blah.txt

##Let's create foo.txt.

####touch foo.txt

##Explain what happens of you touch an existing file.

####It changes the timestamp on the file. Here are two outputs for the same file I used teh touch cammand on at different times:

####-rw-r--r--  1 jerinhiatt  staff    0 Feb 15 11:24 foo.txt
####-rw-r--r--  1 jerinhiatt  staff    0 Feb 15 11:26 foo.txt

##Do More Question
###Make a directory, change to it, and then make a file in it. Then change one level up and run the rmdir command in this directory. You should get an error. Try to understand why you got this error.

####The error is: irectory not empty
####This occurs becasue you just created a file in that directory

