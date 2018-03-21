### Welcome to Software Carpentry

Before we begin, we ask that you complete this list to ensure that you have access to wi-fi, the etherpad, and that all software is installed.

* You should have received **two sticky notes**, one green (ready to go) and one red (having trouble), that you can use throughout the workshop to show the instructors and helpers if things are going well or if you encounter any trouble.  If you have difficulty with any portion of this list, please place a red sticky note on the top of your laptop to indicate you need assistance. Once the issue is resolved, please take down the red sticky note.  Once you successfully complete the list, please place the green sticky note on your laptop to indicate that you are ready to begin.

* Log-in to **eaglenet** network with your EUID. If you do not have an EUID, please place a red sticky note on your laptop and ask a helper for wifi credentials.

* Open the webpage http://bit.ly/swc031418 to access the **Etherpad**.  We will use this Etherpad to share links and snippets of code, take notes, ask and answer questions, and whatever else comes to mind. To start, please add yourself to the attendee list.

* If you have not downloaded any of the software used for these lessons, please go to the event page and follow the setup instructions at the bottom of the page: https://unt-carpentries.github.io/2018-03-14-unt-swc/. Once you have downloaded and installed the software, please go through the steps below to verify everything is working.

##### Open the bash shell

* Windows: Open a terminal by running the program Git Bash from the Windows start menu.
    * If you don't find Git Bash in your start menu, put your red sticky note on the top of your laptop.
* Mac: Open the Applications Folder, and in Utilities select Terminal.
* Linux: Open the Terminal program via the applications menu.  The default shell is usually Bash.  If you aren't sure what yours is, type `echo $SHELL`.  If the shell listed is not bash, type `bash` and press Enter to access Bash.

##### Check that git is installed

* In the terminal, type `git --version` to check that it is installed.  
    * If you receive an error message, put your red sticky note on the top of your laptop.

##### Check that Anaconda is installed

* In the terminal, type `python --version`. You should see the version of your Python program listed.
    * Mac and Linux: If you get an error or your version does not indicate "Anaconda", put your red sticky note on top of your laptop.
    * Windows: If you receive an error message about python not being found, do the following:
      * Open the Anaconda Prompt and enter the following to find the path of the Anaconda3 directory:
        ```
        where python
        ```
        The output should show a path similar to `C:\Users\Username\Anaconda3\python.exe`.
      * Convert that path by doing the following:
        * Replace all instances of `\` with `/`
        * Replace `C:` with `/c`
        * Replace `python.exe` with `Scripts/activate`
        
        So, for example, if you got `C:\Users\Username\Anaconda3\python.exe` from the previous step, you will use `/c/Users/Username/Anaconda3/Scripts/activate` for the next step.
      * Go back to the terminal and run the following command, replacing `[Anaconda path]` with the path you generated in the previous step.
        ```
        echo  "source [Anaconda path]" >> ~/.profile
        ```
        then open a **new** terminal and try typing `python --version` again.
    * If you still receive an error message, put your red sticky note on the top of your laptop.
* In the terminal, type `jupyter notebook` to run Jupyter Notebook. After a few seconds, text should appear in your terminal and Jupyter Notebook should pop up in a browser window. You can close the browser window and press `CTRL+C` in the terminal to exit the program.
    * If Jupyter Notebook doesn't open, put your red sticky note on the top of your laptop.

##### Check that nano is installed

nano is a basic editor and the default that instructors use in the workshop.
* In the terminal, type `nano`. If the nano program opens, use `CTRL+X` to exit.
    * If you are unable to open nano, put your red sticky note on the top of your laptop.

##### Complete the Pre-Workshop Survey
* Once everything is installed, please complete the pre-workshop survey if you have not already.  The link is available on the Etherpad.
