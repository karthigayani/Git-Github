### 1. What is Git ? How to install it ?

1.  Git -> Git is a version control system
2.  It is a website which stores project codes from the beginning to end as a version. So that you can take it whenever you want.

3.  Download Git as per your windows.
4.  How to check whether the git is installed or not ?
5.  Git version check command type -> git --version git<space>--version, put it in your command prompt.
6.  If it is installed, it shows the git version.

### 2. Basic commands in git.

1. If you want to check your knowledge about git,

- Google -> eachonetechone.co.in -> enter the form -> choose the subject -> you will get email -> click on the link in email -> it ask interview questions -> answer it and press submit -> course completed certificate generated -> you can share it in linkedin.

2. How to make the files comes under version control system ?

- " git init " -> git<space>init
- The git init command creates a new Git repository. It can be used to convert an existing, unversioned project to a Git repository or initialize a new, empty repository. Most other Git commands are not available outside of an initialized repository, so this is usually the first command you'll run in a new project.
- After initializing create a file, it shows green color. means it is going to be tracked.

3. How to add files to git ?

- " git add . " -> git<space>add<space>dot -> dot means you are adding all the files to git.
- files automatically changed to green color
- Then in command prompt type -> git commit -m "Your msg" git<space>commit<space>-m<space>"inside double quotes type your msg" then press enter.
- git commit -m "msg" -> This command represent the version/checkpoint of the project. You can make "n" number of version based on changes.

### 3. Continuous work flow in git

1.  Change the codes what ever you want in the files
2.  file/files automatically changed to orange color (That means you made some changes in your file/files)
3.  hen in command prompt type -> " git add . " -> git<space>add<space>dot and then press enter.
4.  Then in command prompt type -> git commit -m "Your msg" git<space>commit<space>-m<space>"inside double quotes type your msg" then press enter.
5.  File/Files color changed into white -> means files are updated in git.

### Again edit your code

1.  Edit what ever you want add, remove, edit Git saves every action of your edit.
2.  Add & commit as mention above.

- Blue line -> Indicates "changes made already commited line".
- No line -> Indicates "There is no changes in the line".
- Green line -> Indicates "New line added".

### How to get the full history of your commits

- " git log " -> git<space>log -> to get the full history of your commits.
- Note : Read your history in reverse order. ie., from bottom to top.

1. How to see the changes made in commit ?

- " git diff 89a06ffce8966e8899000eb95b8422e9987ea631 44c0acd95ee632d47d5df425d41d48fd28c8cbda " -> git<space>diff<space>old commit<space>new commit and then press enter.

### 4. Graphical user interface
