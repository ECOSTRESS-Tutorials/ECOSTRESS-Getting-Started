> *This tutorial will show you how to contribute to the ECOSTRESS
> tutorials GitHub by forking a repository, cloning it to your local
> machine, committing your suggested changes, pushing your changes back,
> and submitting a pull request. This allows for greater collaboration
> among the broader ECOSTRESS community. This tutorial is for Windows
> computers.*

# Table of Contents

[Prerequisites](#prerequisites)

[What is a forking?](#what-is-a-forking)

[Creating a Fork](#creating-a-fork)

[What is Git?](#what-is-git)

[Installing Git](#installing-git)

[What is a cloning?](#what-is-a-cloning)

[Cloning the Forked Repository](#cloning-the-forked-repository)

[What is a committing?](#what-is-a-committing)

[Making and Committing Edits](#making-and-committing-edits)

[What does it mean to push changes?](#what-does-it-mean-to-push-changes)

[Pushing Changes to the Forked Repository](#pushing-changes-to-the-forked-repository)

[What is a pull request?](#what-is-a-pull-request)

[Creating a Pull Request](#creating-a-pull-request)

# Prerequisites

To follow along with this tutorial, you must have a GitHub account. If
you do not have one, you must create one before proceeding with this
tutorial. Also, make sure you have Visual Studio Code downloaded on your
computer. If you need help installing it, go to
<https://ecostress.jpl.nasa.gov/tutorials> and follow along with the
provided tutorial.

# What is a forking?

Forking creates a personal copy of someone else’s repository on your
GitHub account. Think of a repository like a project folder containing
all relevant documents. We need to fork when we want to make changes to
a repository to later send back for review. The forked repository will
live in your personal GitHub and will be separate from the original
repository that you got it from. Any changes made in the original will
not change your fork unless you explicitly update it.

## Creating a Fork

1.  Start by **logging in** to your GitHub account and going to the
    **repository** that you would like to modify. You can view all the
    different ECOSTRESS tutorials repositories at
    <https://github.com/orgs/ECOSTRESS-Tutorials/repositories>. For this
    tutorial, I am going to use the ECOSTRESS-Single-Cloud-Mask
    repository because I found a typo there that I want to suggest a fix
    for.

<img src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image1.png"
style="width:6.53394in;height:2.67361in" />

2.  Once you are on the repository page, click **Fork** in the top
    right.

<img src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image2.png"
style="width:6.06667in;height:0.77778in" />

3.  Click on the dropdown under **Owner** and select your GitHub
    username. It may automatically be selected for you. If you do not
    see it as an option, make sure you are logged into GitHub.

**Example**: My username is CarolineBaumannJPL

<img src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image3.png"
style="width:5.09028in;height:1.99256in" />

4.  By default, the **Repository name** will be listed as the same name
    as the repository you are trying to fork. If you would like, you can
    modify this name. However, most of the time we can leave it as is.

<img src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image4.png"
style="width:5.21528in;height:1.08768in" />

5.  The **Description** will also be the same as the description of the
    repository that you are forking. If you want to change it, you can
    do that now.

<img src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image5.png"
style="width:5.28853in;height:0.58824in" />

6.  By default, **Copy the main branch only** is selected. Most of the
    ECOSTRESS tutorials only have a main branch, so it is okay to
    **leave this as is**. However, if there are sub-branches that you
    would like to include, you may choose to uncheck this box.

<img src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image6.png"
style="width:5.34028in;height:0.62189in" />

7.  Finally, click the green **Create Fork** button. This will take you
    to your new forked repository.

<img src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image7.png"
style="width:1.26363in;height:0.57375in"
alt="A green and white sign Description automatically generated with low confidence" />

# What is Git?

While GitHub is an online platform used to share Git repositories, Git
itself is a tool used for tracking changes in code and collaborating on
projects. Installing Git on Windows computers allows us to use Git
commands in order to manage our code locally and sync it with GitHub.

## Installing Git

1.  Next, we need to install git. Go to <https://git-scm.com/> or search
    the web for Git and click on the first link. Click on the button
    that says **Download for Windows**.

<img src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image8.png"
style="width:3.08333in;height:2.41269in"
alt="A picture containing text, monitor, electronics, display Description automatically generated" />

2.  Then, on the new page, select **Click here to download**. A download
    should begin.

<img src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image9.png"
style="width:5.8557in;height:1.02083in"
alt="Text Description automatically generated" />

3.  In your downloads folder**, double click** on the download to open
    it. It may ask you to **allow this app to make changes to your
    device** in which you can select **yes**.

> <img
> src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image10.png"
> style="width:2.54202in;height:0.56952in"
> alt="Shape Description automatically generated" />

4.  In the installer window that pops-up, select **Next**. You can
    continue to select **Next** through all the windows to accept the
    default options until you get to a page that says **Install**.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image11.png"
style="width:3.20106in;height:2.44444in"
alt="Graphical user interface, text, application, email Description automatically generated" />

5.  Click **install** and allow Git to install.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image12.png"
style="width:3.19444in;height:2.44361in"
alt="Graphical user interface, text, application, email Description automatically generated" />

6.  When you get to this final page, select **Finish**.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image13.png"
style="width:3.17823in;height:2.42361in"
alt="Graphical user interface, text, application Description automatically generated" />

# What is a cloning?

Cloning is the process of copying a repository from yours or someone
else’s GitHub to your local machine (i.e. computer). This makes it easy
to work with locally for testing, editing, and development. The changes
you make in your cloned repository will only exist on your computer
until you chose to push them back to GitHub. We need to clone the
repository we just forked so we can make edits and later suggest them
back to the original project.

## Cloning the Forked Repository

1.  Start by opening **Git Bash**, which is what we just downloaded. You
    can do this by typing **Git Bash** into the **Start Menu** next to
    the **Windows logo** and pressing enter**.**

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image14.png"
style="width:2.72529in;height:0.49768in"
alt="Graphical user interface, application Description automatically generated" />

2.  We need to set the directory to the place on your computer where we
    want the clone of this repository to exist. For me, I want this in
    the documents folder, so I am going to **copy the path** to my
    documents folder.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image15.png"
style="width:4.96726in;height:3.18056in" />

3.  Then, in **Git Bash**, type **cd** followed by the **path** to where
    you want the clone to be saved. Press **Enter** to run it. Leave the
    Git Bash window open.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image16.png"
style="width:2.73611in;height:0.98995in" />

4.  Next, go to your browser and make sure you are on the forked
    repository page that you just created. Click the green **\<\> Code**
    button.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image17.png"
style="width:5.63889in;height:1.93799in" />

5.  In the drop down you will see three options: **HTTPS**, **SSH**, and
    **GitHub CLI**. HTTPS is the most beginner friendly, so we are going
    to use that. However, you can use one of the other options if you
    are more comfortable with them. While on the **HTTPS** option, click
    the **clipboard** icon to **copy** the URL.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image18.png"
style="width:4in;height:3.65752in" />

6.  Go back to your Git Bash window, type **git clone,** and paste the
    URL you copied from GitHub. Press **Enter** to run it. Now you
    should have a clone of the repository on your local machine.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image19.png"
style="width:5.03472in;height:0.98973in" />

7.  Next, lets change the directory to our new cloned repository by
    typing **cd** followed by the path to the repository folder on your
    computer. Press **Enter** to run it.

> **Example:**
>
> <img
> src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image20.png"
> style="width:4.10417in;height:0.26776in" />

8.  Finally, we need to let Git Bash know what our GitHub username and
    email is. In order to do this we need to initialize Git by typing
    **git init** and pressing **Enter** to run it.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image21.png"
style="width:4.39583in;height:0.50305in" />

9.  First, type the command **git config user.name "Your User Name"**
    into Git Bash, replacing “Your User Name” with whatever your user
    name is. Press **Enter** to run.

**Example:**

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image22.png"
style="width:4.88889in;height:0.36562in" />

10. Then, type **git config user.email "your-email@example.com"** and
    replace “your-email@example.com” with whatever email you created
    your account with. Press **Enter** to run.

**Example:**

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image23.png"
style="width:5.01325in;height:0.47222in" />

# What is a committing?

Now that we have a clone of our forked repository, we can make whatever
edits we want. Once these edits are made, we need to commit them, or
save the changes to our local repository. Every time we commit changes,
we leave a message describing what we edited. This allows us to track
changes and versions of our work so we can go back if we ever need to.

## Making and Committing Edits

1.  Open **Visual Studio Code**. Select **File \> Open Folder…** and
    open the folder of the cloned repository that you made in the
    previous section.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image24.png"
style="width:2.98977in;height:2.53472in" />

2.  Once the folder is open, you will see all the files from that
    repository in the **EXPLORER** pane. Click on the file you want to
    edit to **open it**. For example, I noticed a typo in the Read Me
    file, so I am going to click on that one to open it.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image25.png"
style="width:2.34028in;height:2.36075in" />

1.  Alternatively, you can add an entirely new file to the folder by
    hovering your mouse over the folder name in the EXPLORER tab and
    selecting the **New File** icon.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image26.png"
style="width:2.55556in;height:0.85333in" />

3.  Make the **changes** that you would like in the document you opened.
    You can open and edit as many documents as you would like. Once you
    are done making edits, make sure to select **File \> Save** to save
    your edits. The next step will not work unless your edits are saved.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image27.png"
style="width:2.36806in;height:2.71832in" />

**Tip**: If you have unsaved edits in any of your files, a blue number
will appear next to the file icon in the top left with the number of
saves that need to be made. Once you have saved everything, this number
will disappear, and you know you are good to proceed to the next step.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image280.png"
style="width:0.53148in;height:0.54666in"
alt="Graphical user interface, application Description automatically generated" />

4.  Once all your edits are saved, a blue circle with a number will
    appear on the **Source Control** icon. The number will correlate
    with the number of changes you made. Click on the Source Control
    icon to open the **Source Control panel**.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image29.png"
style="width:0.52227in;height:0.53885in"
alt="Icon Description automatically generated with medium confidence" />

5.  In the new panel, look for the dropdown that says **Changes**. If
    you hover your mouse over this, a plus sign will appear. Click the
    plus sign to **Stage** your changes. Staging your changes just means
    that you want to include them in the next version of the project. We
    stage our changes to later be committed back to the repository.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image30.png"
style="width:2.59722in;height:1.83467in" />

1.  Alternatively, if you want to stage just **some** changes, but not
    all, you can hover over individual files under **Changes** and
    select the plus sign to add just that file’s changes to the **Staged
    Changes**. In my case, I only made one change, but if you made
    multiple changes, this is how you can decide which ones you want to
    commit.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image31.png"
style="width:2.47222in;height:0.54248in" />

6.  At the top of the panel, you should see a box that says **Message**.
    Here is where you need to type your commit message. A commit message
    is just a brief description of the changes that you made in order to
    remind you and others of what is different in this version compared
    to the previous one. Based on your change, type in your brief
    message.

**Example:**

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image32.png"
style="width:2.48408in;height:2in" />

7.  Finally, press the blue **Commit** button. By pressing commit, you
    are saving your staged changes as a new version in your local cloned
    repository.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image33.png"
style="width:2.5615in;height:2.00694in" />

# What does it mean to push changes?

Previously, we forked a repository to our own GitHub, cloned it to our
computer, and made and committed edits to the clone on our computer.
Now, we need to push our changes, which means we save the changes we
made on our local computer to our forked online GitHub repository.

## Pushing Changes to the Forked Repository

1.  There are multiple ways to push changes to a forked repository. One
    way is using the command **Git Push**, however if it is just you
    making changes, the easiest thing to do is just press the blue
    **Sync Changes** button in Visual Studio Code that shows up when you
    commit changes.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image34.png"
style="width:2.20139in;height:1.25147in" />

2.  You may get a pop up warning saying that **This action will pull and
    push commits from and to “origin/main”.** You can press **OK**.
    Furthermore, if a pop-up shows up asking you to log into GitHub, you
    can follow those steps to do so.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image35.png"
style="width:3.16667in;height:0.94865in" />

3.  Open a **web browser** and go to the **GitHub** page with your
    **forked** repository. Double check to make sure that **all
    changes** were made.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image36.png"
style="width:4.83558in;height:1.91667in" />

# What is a pull request?

The final part of this tutorial is creating a pull request. A pull
request is a way to suggest changes back to the original repository that
we created our fork from. This allows the owners of the ECOSTRESS
tutorials repository be able to review your changes and decide if they
want to implement them in the main repository.

## Creating a Pull Request

1.  In a browser window, open the **forked repository** on your
    **GitHub** account.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image37.png"
style="width:5.98432in;height:3.10417in" />

2.  You should see a message at the top that has a dropdown that says
    **Contribute**. Click the dropdown and then select **Open Pull
    Request**.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image38.png"
style="width:5.44757in;height:2.0625in" />

1.  Alternatively, at the top of the page, **click** on the option that
    says **Pull requests.** On the new page, click the green **New pull
    request** button.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image39.png"
style="width:5.59071in;height:1.04344in" />

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image40.png"
style="width:5.60417in;height:1.02003in" />

3.  A new page titled **Comparing changes** should appear. At the top,
    you will see two sections with dropdowns. The first represents the
    main tutorial repository where you want to suggest changes. Make
    sure the **base repository** listed is the original one that you
    first created your fork from. The next drop down should say **base:
    main**, with “base” for the repository and “main” for the branch. If
    you are working with a branch **other than main**, you should have
    that listed after the colon.

**Example:**

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image41.png"
style="width:6.50066in;height:1.22222in" />

4.  The second section represents your forked repository that you made
    changes to. The first drop down should say **head repository** with
    your personal forked repository listed after it. The second drop
    down should say **compare: main**. It is most likely that your
    branch will be **main**, but if you are working with another one,
    make sure to select the correct one from the dropdown.

**Example:**

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image42.png"
style="width:6.23565in;height:0.68056in" />

5.  The first text box is the **title** of your request. This should
    **automatically** generate based on your **commit message**, however
    if you want to change it you can do that now.

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image43.png"
style="width:2.05053in;height:0.90019in" />

6.  Under **Write** you should see a text box that says **Leave a
    comment**. Here you can type out a longer and more detailed message
    of the changes you made.

**Example:**

<img
src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image44.png"
style="width:4.64213in;height:1.3125in" />

7.  When you are done, press the green **Create pull request** button.

> <img
> src="10-Suggesting_Edits_to_GitHub-Windows_images/media/image45.png"
> style="width:2.43685in;height:0.49206in"
> alt="Graphical user interface Description automatically generated with low confidence" />

Now you have made your pull request! Your suggestions will be reviewed
by the current owner of the ECOTRESS tutorials GitHub. Thank you for
contributing!
