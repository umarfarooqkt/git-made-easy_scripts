# Bash git life made easy scripts 
 
These bash scripts will make your git experience a deliciouse piece of chocolate fudge cake :)

 * Read the whole instrictions before starting
 *Warning some these scripts are incompatible with windows, 
 *well you can try to set them up but you will be running into some trouble shooting issues 

To set up these scripts follow the steps 

1. Simply write them in a editor of your choice or download them.

2. Change their permissions by running the command $chmod 755 for the files. 
   I fyou are doing this step in /bin then you need to add sudo 
   e.g $sudo chmod 755 filenamegoeshere

3. Make sure you placed all your scripts in /bin. You can get to your bin 
   in linux by running  the commad $cd /bin remember you might have to 
   launch your editor or other commands with $sudo in bin, Since you 
   need permission to edit stuff
   in bin.

4. You may also wanna add the line ( export PATH="$PATH:$HOME/bin" ) to 
   your .bashrc to make sure the scripts run because there's a chance 
   bin isnt in your path as of yet. .bashrc can be accessed but doing 
   $gedit .bashrc 
   (as it's usually a hidden file at the start of the terminal can find it using $ls -a)

5. after this point your scripts are almost ready to go. But you need 
   a folder for your git projects that has /git_root set in its path. 
   To do this just run the recently added script git_root, you need 
   to provide the script with the name you wanna set your project folder 
   e.g $git_root git  now the you have folder named git 
   where your git projects should be and your scripts will work in this directory.
