# github_client

A new Flutter desktop project.

## Getting Started

- flutter config --enable-macos-desktop
- flutter create github_client
- cd github_client
- rm -r android ios web
- flutter run
- git init
- git add .
- git commit -m "My First Commit"
- git add remote origin git@github.com:username/repo.git
- git branch -M main
- git push -u origin main

### If ssh not config
- cd ~/.ssh
- ssh-keygen
- cat id_rsa.pub
- cat ~/.ssh/id_rsa.pub | pbcopy
- Add to github.com
- ssh -T git@github.com
