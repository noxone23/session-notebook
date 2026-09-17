# Creating a Remote Repository

1. Go to github Profile/Repo and click new for a new repository
2. Choose owner and name and click Create repository
3. Copy the SSH (or HTTPS) repository URL shown on the next page and add it as the remote repository "origin" to our local folder(nickname) repository
4. git remote add origin <ssh link>
5. Check if the remote repository was successfully linked with the command:
6. git remote -v
7. A "fetch" and a "push" address should be printed to the terminal.
8. For every challenge in your nickname repository:
9. Use git add <challenge folder name> to stage the changes from this challenge.
   Commit these challenge files with git commit -m "<message>" and add a meaningful message, e.g., "add solution for html and the web - personal website".
   Use git push to push the new commit to your remote repository on GitHub. The first time you need to specify where you want to push to with the command git push -u origin main.
10. Repeat this for every challenge folder!
