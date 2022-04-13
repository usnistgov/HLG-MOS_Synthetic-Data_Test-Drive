# HLG-MOS_Synthetic-Data_Test-Drive

### REPORTS SUBMISSION GUIDELINES FOR THE TEAMS

#### 1. Clone this repository to your device
>`git clone https://github.com/usnistgov/HLG-MOS_Synthetic-Data_Test-Drive.git`


#### 2. Navigate to the newly created `HLG-MOS_Synthetic-Data_Test-Drive` directory
> `cd HLG-MOS_Synthetic-Data_Test-Drive`


#### 3. Create a new git branch with your team's name  
>`git branch -b submission/{team's name}_team`

Example:  

> `git branch -b submission/abc_team`


#### 4. Adding submission files:
  * Your team's submission folder already exists at path `data/` in this repository.  
    >For example, team abc's submission folder is `data/abc/`
  * Using your device's file-system, paste your team's submission files into your team's submission folder.
  * NOTE:
    * ***Add each file individually and do not package all your team's submission files into one zip or tar file.***
    * ***Allowed file types: 'r', 'py', 'ipynb','pdf', 'csv', 'jpg', 'png', and 'mp4'.***

#### 5. Committing submission files to your team's git branch.
  * Use `git add ` command to stage all of your team's submission files
    > `git add data/{team's name}/.`
    
    Example:

    > `git add data/abc/.`
  
  * Use `git commit` command to commit your team's submission files.
    > `git commit -m 'data submission: team abc'`  
    
    NOTE: You can add any commit message after `-m` flag in the above command, but preferably with prefix ***'data submission'***.

#### 6. Pushing your team's submission data to Github Repository.
  * Use `git push ` command to push your branch to the remote github repository
    > `git push origin {your team's git branch-name}`
    
    Example:

    > `git push origin submission/abc_team`


#### ***RESOLVING ERRORS:***
  * All file types other than 'r' and 'py', are saved to the repository using GIT-LFS
  * In case you see errors related to GIT-LFS, first make sure GIT-LFS is installed on your device by using command:
    > `git lfs -v`  
    
    GIT-LFS is considered installed if the above command returns a version number.
  * Above command resulting in an error could mean that the GIT-LFS is not installed on your device. To install GIT-LFS
    follow instructions on the [GIT-LFS official installation page](https://github.com/git-lfs/git-lfs/wiki/Installation)