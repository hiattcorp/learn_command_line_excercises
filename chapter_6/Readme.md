#Chapter 6 Questions

##What's in the tmp directory?

cd tmp
ls
the stuff directory is listed in tmp

##Can you show me what files are in that directory?

cd stuff
ls
the things directory is listed in tmp

##What files are in your home directory?

cd ~/
ls

Applications    Downloads       Pictures        workspace
BitTorrent Sync Library         Public
Desktop         Movies          sample_app
Documents       Music           untitled folder

##What's in slash temp?

cd /tmp

KSOutOfProcessFetcher.502.sAglCyxY5lzPoNgfmEvv-ZqGl-w=
com.apple.launchd.7urkhrJZzu
com.apple.launchd.luseJq1giM

#Do More

##Describe what the ls-lR command does

This command combines the -l and -R commands and lists all the sub directories in a file and their details. This is the result I got in the tmp file.

total 0
drwx------  3 jerinhiatt  wheel  102 Feb 14 19:52 KSOutOfProcessFetcher.502.sAglCyxY5lzPoNgfmEvv-ZqGl-w=
drwx------  3 jerinhiatt  wheel  102 Feb 13 15:37 com.apple.launchd.7urkhrJZzu
drwx------  3 jerinhiatt  wheel  102 Feb 13 15:37 com.apple.launchd.luseJq1giM

./KSOutOfProcessFetcher.502.sAglCyxY5lzPoNgfmEvv-ZqGl-w=:
total 320
-rwx------  1 jerinhiatt  wheel  163472 Feb 14 19:52 ksfetch

./com.apple.launchd.7urkhrJZzu:
total 0
srw-rw-rw-  1 jerinhiatt  wheel  0 Feb 13 15:37 Render

./com.apple.launchd.luseJq1giM:
total 0
srw-rw-rw-  1 jerinhiatt  wheel  0 Feb 13 15:37 Listeners

