# HLG-MOS_Synthetic-Data_Test-Drive

### DATA SUBMISSION GUIDELINES FOR THE TEAMS
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
  * Using your device's file-system, paste your team's submission files into your teams' submission folder.
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
  * Use `git push ` command to push your branch to remote repository
    > `git push origin {your team's git branch-name}`
    
    Example:

    > `git push origin submission/abc_team`

