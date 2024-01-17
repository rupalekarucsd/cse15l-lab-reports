# Lab Report 1

## Rohan Upalekar

![Image](https://github.com/rupalekarucsd/cse15l-lab-reports/blob/main/cd-ss.png)

The cd command with no arguments resets the directory to the  home (main) directory. Regardless of the working directory (/home/lecture1 or /home/lecture1/messages) it'll always reset it to /home. We tried it with /home/lecture1/messages as the working directory. The output isn't an error.

The cd command with a path to a directory as an argument will set that directory as your current working directory. Bear in mind, you can only go one level up ie, cd lecture1, and then cd messages. If you try to directly go cd messages it'll say:

`[user@sahara ~]$ cd messages`

`bash: cd: messages: No such file or directory`

When running command, we are always in a directory that is one out of the other (ie cd messages is ran in /home/lecture1 and cd lecture1 is ran in /home). 

The cd command with a path to a file as an argument throws an error. Regardless of what working directory you're in, you cannot cd into a file. Cd stands for change directory not file. To go back to the original home directory cd works out, but cd.. will take you out one level.

![Image](https://github.com/rupalekarucsd/cse15l-lab-reports/blob/main/ls-ss.png)

