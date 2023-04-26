Instruction for situation when you are using codespace:
*as connection with the repo in codespace is initiated via web*
1. Create a repository "new-project" in github web UI.
2. Login to your Github account.
3. At the top right of any Github page, you should see a '+' icon. Click that, then select 'New Repository'.
4. Give a repository name "new-project" and click ok.
5. Then create a README.md where paste info from the task and name the commit "init" and press commit button.
6. Only then at the right top corner of the branch you can see code icon where you can chose codespace option.
7. When codespace open, in terminal put "git checkout -b development" to create new branch "development" and swithing to it.
8. Make changes to the README.md file by "vim README.md" and save with ":wq
9. After changes are done make a "git add" to put file to the stage state and be prepared to make commit.
9. After file is ready to commit make a commit to the development branch  with "git commit -m "add instruction" "
