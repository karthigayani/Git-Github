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

### 4. Graphical user interface with out using comment prompt with the help of vs code tool

1. add & commit using VS code tool.

- VS code -> File Explorer -> Source code -> (M-Indicates modified) (Instead of using git add .) -> point the curser on changes -> You can see "+" symbol -> files are changed to staged changes ->(Instead of using git commit -m "your msg") In the message type your msg -> and then press on Tick button.

2. Finding the commit history using VS code toll.

- VS code -> File Explorer -> (at the bottom) -> Time line -> It opens a window -> and list all the commits of the file -> click on the commits to see the changes.

### 5. Git vs Github

- Git -> Local Storage (Local System) You can Use it only in the same system.
- Github -> Cloud Storage (Server) You can Use it anytime anywhere.

1. How to push into Github ?

- Sign up if you don't have account.
- Sign in -> Right Hand Side You can see "+" Symbol behind your profile -> Click on it -> select New repository -> Name the repository -> Select Private or Public as you want -> click on Create Repository.
- Now you can see more options like
  i) Create a new file
  ii) Upload an existing file
  iii) …or push an existing repository from the command line
  - and so on....
- We always go for 2nd and 3rd option.

2. Upload an existing file -> You can Drag or choose your file from your system.
3. Or You can push from command line step by step in your commant prompt
   Steps:
   - git<space>add<space>dot (Press Enter) -> git<space>commit<space>-m<space>"Your msg"(Press Enter) -> copy paste the first command line from your repository (Press Enter) -> copy paste the Second command line from your repository (Press Enter) -> copy paste the Third command line from your repository (Press Enter)
   - Your files are uploaded and the github shows every commits of your file.
   - You can click on the commits and click on code symbol "<>" to see the changes made.

### 6. Github Desktop

- Github Desktop Tool -> Used to sync local system with github.
- Google search -> Github desktop -> open first link -> download software based on your OS -> You get a tool -> login with your github account -> Open git init folder from local system through Github desktop tool

### Opening git init folder from local system through Github desktop tool

- Open Github desktop tool -> (Select) Add an Existing Repository -> choose the path of the folder -> (Select open ) click on Add repository -> your Folder get opened in desktop tool -> You can click on fetch origin option to fetch the changes -> Under current repository -> You can see history -> Click on history -> It shows all the commits of the folder.

### How to add files and commit in github desktop tool

- Made changes in your files in the VS code
- You can see the tick mark in the changes under Current Repository in your github desktop tool.
- You can also select Which file changes you want to commit.
- Also at the left bottom their is a summary box. Enter your Msg and click on Commit to main.
- In this step Your commits are saved as version in your local system.
- Once Your commits are completed You can see push to origin option behind current branch. Click on it. Now your files are updated in github.
- Now the push to orgin option changed into fetch orgin.

### 7. What is Branch in Git Version management ?

- When you create a repository "main branch" will automatically created. You can commit "n" no.of times. This is only Good for (single user) when you only doing the whole project.
- But this way is not good for (multiple user) / group project.
- Why because you cann't identify the commits properly.
- So to avoid this issue get the copy of main branch and named as "for eg: feature 1(eg:Home) , feature 2(eg:About), feature 3(eg:contact)... make changes and then merge it one by one.
- This features are branch.

1.  merge feature 1 with main branch run it/ check it out the output ok or not.
2.  Then merge feature 2 with (main branch & feature 1) run it/ check it out the output ok or not.
3.  Then merge feature 3 with (main branch & feature 1 & feature 2) run it/ check it out the output ok or not.

### Single User

- Main -> Feature -> Main

### Multiple User

- Main ->

1.  Feature 1 -> (Feature 1 Merge with Main) -> Testing taking place
2.  Feature 2 -> (Feature 2 Merge with Main) -> Testing taking place
3.  Feature 3 -> (Feature 3 Merge with Main) -> Testing taking place

- Main (Final Product)

### In Companies

- Main -> Stage (Client/Senior) -> Dev (Developer) ->
- Feature.1 -> (Feature.1 Merge with Dev) -> Testing taking place
- Feature.2 -> (Feature.2 Merge with Dev) -> Testing taking place
- Feature.3 -> (Feature.3 Merge with Dev) -> Testing taking place
- Feature.4 -> (Feature.4 Merge with Dev) -> Testing taking place
- Feature.5 -> (Feature.5 Merge with Dev) -> Testing taking place
- (Final Dev) -> (Final Dev Merge with Stage) Stage -> Testing taking place -> (Final Stage Merge with Main)-> Testing taking place -> Main (Final Product)

### How to create Branch in Desktop tool:
