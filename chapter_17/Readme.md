#Chapter 17 Questions


>Can you show me all the files in slash temp slash foo?

###cd /tmp
###find . -name "*.*" -print | less

>What log files are in your log directory?

###find . -name "*.log" -print | less

