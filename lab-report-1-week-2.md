# Lab Report 1 - Week 2 - Mohak Vaswani

In this Lab Report, I am going to describe how we can log onto our course specific account _ieng6_ and run some basic **ssh** and **scp** commands. I am going to be describing 6 steps, with detailed description and screenshots for each step.

## _Step 1 - Installing VScode_

The first step is Installing VScode. You can download VScode at [this](https://code.visualstudio.com/download) link. 

Clicking the link will redirect you to the page to download VScode as per your operating system requirement.
Once downloaded, install and run VScode, and you should see a basic screen as shown:

![image](./Lab-report-1-materials/VScode-intial.png)

## _Step 2 - Remotely Connecting_

# Step 2.1 - Finding your login details

Find your course specific account at [this](https://sdacs.ucsd.edu/~icc/index.php) link.

* Click on the link, it should prompt you to login
* Your account username should look something like `cs15lsp22zz` where `zz` are the unique character in your course specific account
* You might want to reset your password before you move forward which can be done through [this](./Lab-report-1-materials/How-to-Reset-your-Password.pdf) document.

# Step 2.2 - Opening a new terminal

Open up Visual Studio Code. On the toolbar at the top of your screen, you should see an option for **Terminal**. Click on it and select **New Terminal**. This will open up a brand new terminal on your VScode

# Step 2.3 - Connecting to Remote machine

* In your terminal, type the following command `ssh cs15lsp22zz@ieng6.ucsd.edu` and click enter
* If you are doing this for the first time, it will prompt you to veryfiy the authenicity of the remote machine you are connecting to, type **yes** and press enter
* Now it will prompt you to enter your password
* After entering your password your screen should look as follows

![image](./Lab-report-1-materials/ssh-login.png)

## _Step 3 - Trying some commands_

Now let us try running some of basic commands while we are connected to our remote machine. Some of the basic commands you can try are:
* `ls` --> Lists all files
* `cd <directory name>` --> Changes the directory to mentioned directory
* `ls -a` --> Lists all hidden files
* `cat <location/filename>` --> used to concatenate files

Following is a screenshot of me running some basic commands on my terminal

![image](./Lab-report-1-materials/basic-commands.png)

## _Step 4 - Moving files with scp__



