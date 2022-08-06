# first-git-project
1. to change from https connection to ssh connection, we need to change url in config file(this is present in project working folder/.git/)
   command is: " git remote set-url origin git@github.com:lwar1991/first-git-project.git"
   for push url : git remote set-url --push origin git://.....
2. to push: git push -u origin
3. to commit: git commit -m "message" {<filename> or leave blank for all files}
4.to generate ssh key to connect to remote github:command: ssh-keygen
5. if u make a git init in a subfolder of existeing git running folder, u cannot commit.. it will give some error. then u need to stop or remove git in that subfolder
  --search fpr htat command: " rm -rf .git "---- remove .git folder
