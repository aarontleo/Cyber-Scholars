# Cyber-Scholars
Information and Code relating to the NG UMBC CyberChallenge 

## Git / GitHub Tutorial
Tutorial on how to create and push changes to this GitHub repository:

### First, fork the original Cyber-Scholars repository to your GitHub account and create a local copy:
- In the top right corner of the repository page click:

   **"Fork"** 
   
   *This creates a copy of the Cyber-Scholars repository in your account*
- Inside of Linux, on the command-line type: 

   **git clone git@github.com[your-github-username]/Cyber-Scholars**
    
   *This creates a local copy of the Cyber-Scholars repository for you to make changes on without affecting the original            master*
- On the command-line change into the Cyber-Scholar local repository: 

    **cd ~/Cyber-Scholars**
- On the command-line add a connection back to my original Cyber-Scholars repository: 

    **git remote add aarontleo git://github.com/aarontleo/Cyber-Scholars**

### You are now able to make changes to any files you like

### After saving your changes in your files you will want to add those files, commit them to your repository, and push them back to your GitHub repository, for that process follow these steps:
- First, pull any changes that have already been made to the master repository:

   **git pull master aarontleo**
   
- Push those changes to your forked GitHub repository:

   **git push**
    
- Add all the files you have saved to be commited (AKA Staging):

   **git add***
- Commit those files so they are "saved" to your repository, you should add a descriptive message about the changes you made:
    
   **git commit -m "insert descriptive message about changes here"**
- Push those changes to your GitHub repository:

   **git push**
    
### Finally you will want to create a pull request to push your changes back to the original Cyber-Scholars repository from your forked Cyber-Scholars copy:
- On your forked Cyber-Scholars repository GitHub page, at the top of the page click:

   **Pull Request**
- This will show your forked repository and the original Cyber-Scholars repository, then click:

   **Create Pull Request**
    
   *Give it a title, infomration about the changes you made and click **Create Pull Request** again*
