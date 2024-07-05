# New Project

## Init a new project repository
1. Create a new folder "new-project" and goto this folder
   ```
   cd new-project
   ```
2. Initialize the repository
   ```
   git init
   ```
3. Create a new file README.md
4. Prepare the file to commit
   ```
   git add README.md
   ```
5. Commit changes with the comment "init"
   ```
   git commit -m 'init'
   ```
6. Create a remote repository in github using the link https://github.com/new
7. And right after that you will be able to add the remote URL to your local git repository with git remote add origin <git@github.com:OWNER-NAME/new-project.git>
   ```
   git remote add origin git@github.com:helga-cheberakha/new-project.git
   ```
8. Push changes to the remote
   ```
   git push origin main
   ```
9. Create a new branch "development" and switch to this new branch
   ```
   git checkout -b development
   ``` 
10. Add all required content to the README.md file and prepare the file to commit
   ```
   git add README.md
   ```
11. Commit changes with the comment
   ```
   git commit -m 'Added a full steps description to the README.md'
   ```
12. Push changes to the remote to the branch "development"
   ```
   git push origin development
   ```
13. Switch back to the "main" branch
   ```
   git checkout main
   ```
14. Merge the branch "development" into the branch "main"
   ```
   git merge development
   ```
15. Push changes to the remote to the main branch
   ```
   git push origin main
   ```
