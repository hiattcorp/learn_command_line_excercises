#Chapter 21 Questions

>What is your shell set to?

###Jhis-MacBook-Pro:chapter_21 $ echo $SHELL
###/bin/bash

>What directory are you in (don't use pwd this time)?

###Jhis-MacBook-Pro:chapter_21 $ echo $PWD
###/Users/jerinhiatt/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_21

>What is your home directory set to?

###Jhis-MacBook-Pro:chapter_21 $ echo $HOME
###/Users/jerinhiatt

>Can you set your environment to have DEBUG set to true?

###I could not find this in the command line crash course book unless I just missed it completely. I found the info on www.schrodinger.com.
 
### The way to do it is:
```
export debug = true
```

>To change path you would do something similar. Below is an example

```
export PATH=$PATH:/usr/local/database/bin
```
