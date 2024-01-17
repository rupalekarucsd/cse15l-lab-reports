# Lab Report 1

## Rohan Upalekar

![Image](https://github.com/rupalekarucsd/cse15l-lab-reports/blob/main/cd-ss.png)

The cd command with no arguments resets the directory to the  home (main) directory. Regardless of the working directory (/home/lecture1 or /home/lecture1/messages) it'll always reset it to /home. We tried it with /home/lecture1/messages as the working directory. The output isn't an error.

The cd command with a path to a directory as an argument will set that directory as your current working directory. Bear in mind, you can only go one level up ie, cd lecture1, and then cd messages. If you try to directly go cd messages it'll say:


