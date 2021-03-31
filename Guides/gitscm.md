# Guide for installing Git SCM

1.  Go to: <https://git-scm.com/>

1.  Download and install:

    A.  For PC:
    -  Run the installer and go through the installation wizard.

B.  For Mac:
- Open launcher and search “terminal”:

> <img src="media\image3.jpg" style="width:4.31008in;height:2.73034in" alt="Graphical user interface Description automatically generated" />

- In the terminal then type run `brew install git`:

> <img src="media\image4.png" style="width:4.86822in;height:2.34884in" alt="brew install git - KodigoSwift" />

1.  Launch the command prompt (PC) or stay inside the terminal (Mac) and run `git --version` to test the installation:

> <img src="media\image5.png" style="width:4.09743in;height:0.98616in" />
-  If it is working, move to **step 4**

-  If it is not working, send an email or post on the GitHub discussion board.

<!-- -->

4.  Set our identity to our GitHub username for Git by running:  
    `git config --global user.name "YOUR_GITHUB_USERNAME"`
- Remember to change `"YOUR_GITHUB_USERNAME"` to your actual GitHub Username and include the double quotes `" "`

1.  Now set your email to the email you signed up with GitHub by running :
`git config --global user.email YOUR@EMAIL.COM`
- Remember to change `YOUR@EMAIL.COM` to your actual GitHub email

<!-- -->

6.  Once finished, run the following to check your email and username:
`git config --list`

7.  If you had any issues, please check this documentation for more
    details or reach out for help.

8.  Now you are ready to clone a repository!