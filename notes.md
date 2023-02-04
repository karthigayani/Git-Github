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

- create an empty folder in desktop -> open vs code -> File -> Open folder -> terminal -> " git<space>init".
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
3.  Then in command prompt type -> " git add . " -> git<space>add<space>dot and then press enter.
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

- VS code -> File Explorer -> Source code -> (M-Indicates modified) (Instead of using git add .) -> point the curser on changes -> You can see "+" symbol click on it-> files are changed to staged changes ->(Instead of using git commit -m "your msg") In the message tex box type your msg -> and then press on Tick button.

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

Open Desktop tool -> at the top menu bar You can see "Branch button" -> Click on it -> Select "New Branch" -> Name the branch based on the application/feature of your project -> click on "Create Branch"-> Your branch created (You can see it in current branch) -> Then click on "publish branch"-> Make changes in current files or create new file/files -> then commit it with msg (saved in local system)-> Then click on push origin (In this step your files are Saved in cloud)

- You can see the difference by clicking on commits option in github -> Select the branch from main -> click on code button.
- You can also see it in desktop tool by selecting the branch under current branch-> Click on History -> You can see the all commits of your project.

### 9. What is Pull Request ?

- Requesting your branch project merge with main project.

### How to give pull request ?

- After creating a branch and push into orgin -> You can see "Create Pull Request" Under "No Local changes" dialogue box -> Click on it -> it will redirect to the github repository pull request page -> under "Open a pull request" dialogue box you can see the option with drop down list and arrow mark -> Here you can select your branch and You can select pull request against the branch (It may be a main or sub-branch) -> Then click on "Create Pull Request" -> Now click on project repository link -> You can see No.of Pull request made -> Click on it -> then click on "your pull request file" -> It will redirect to the pull request file page -> Here you can See the No. of commit , files changed , checks ... -> check the commits and changes -> come back and click on "Merge Pull Request" -> Then click on "Confirm merge" -> Now the requested branch merged into the particular sub-branch/main. Now you can delete the branch if needed.
- If you want to check whether the branch merged or not means, open the project repository link -> check your files/changes merged or not.
- now go to github desktop tool -> under current branch select "main" -> click on "fetch orgin" -> after fetching it shows pull orgin -> Then click on "Pull origin" -> Now the merged branches(Pull requested brances) are saved in local system too.
- Now go to your VS code You can see the files/changes are merged in main project.

### 10. What is merge conflict ?

- Merge conflict occurs in team project.
- when two or more person made the changes in same file, same line. Why because while merging github get confused which one to store. Hence Merge conflict taking place.
- It Can be solved with the help of human resource only.
- For eg:
  - Main ->
  - feature 1 (made Changes in same file(index.html) at the same line)
  - feature 2 (made Changes in same file(index.html) at the same line)
  - feature 1 merge with Main, But feature 2 get merge conflict, because the file has been already stored. So git get confused which one to store and through Merge conflict error.
  - Here the human have to decide which one to store either feature 1 or feature 2 or both the features 1 & 2.

### How to solve Merge conflict ?

- For eg:
- Create branch 1 from main project -> click on "publish branch" -> made changes in the file -> commit -> push to origin -> create pull request -> Merge Pull request -> commit.

- Create branch 2 from main project -> click on "publish branch" -> made changes in the same named file at the same line -> commit -> push to origin -> create pull request -> It shows "Can't automatically merge" -> Click on "create pull request" -> It shows "The branch has conflict that must be resolved" (and also shows the file name)

- Now it can be resolved by 2 methods.

1.  github
2.  github desktop tool with VS Code (Best way)

- Open desktop tool -> Select "Main" in current branch -> at the history behind changes, select which branch you want to merge (In the history)-> It shows error "Their will be .... conflicted line when merging" at the left bottom of the page -> Select "merge into admin" -> It shows pop-up menu (with msg) -> click open in VS code option -> Vs code shows the differences and also options like "Accept Current Change | Accept Incoming Change | Accept Both Changes | Compare Changes" -> Select which one you want -> and Save it (ctrl + S)
- Then go to desktop tool -> the pop-up shows no conflicts remaining with green tick -> Now click on "Commit Merge".
- Now you can push the branch 2 to the main by clicking on "Push to Origin".
- Open github -> click on Pull request button -> check whether the Pull request solved or not.

### What is Git ignore ?

- It is used to avoid accessing the codes/files/folder while publishing. (For eg : Password or API links etc...)
- It is mainly used for security purpose.

### How to apply git ignore ?

- For eg:
- create file(eg: secret.js) -> Enter the data's -> Now create (.gitignore) file in the same folder -> Enter the files/folder (enter file name with extension eg:secret.js) You want to make avoid accessing from others -> Now the selected file color changed into grey.
- Go to desktop tool -> enter some msg and "Commit it" -> click on "Push to origin" .
- If someone wants to run the program means you have to share that secret file/folder offline.
