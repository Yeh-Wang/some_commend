# MyTest

## Basical Git CMD

* `git init`  
  Create a new repository locally.
* `git clone [remoteurl]`  
Clone a remote repository to local.
* `ssh-keygen -t [rsa/ecdsa/ed25519] -C    "youremail@example.com"`  
  `eval "$(ssh-agent -s)"`  
  `ssh-add ~/.ssh/id_[rsa/ecdsa/ed25519]`  
Config local and remote ssh connections: Generate a key and add it to the agent.Then you should add the key to your remote repository deploy keys.
* `git remote add origin <remote_url>`  
Connect local repository with remote repository('origin' replaces the following url).
* `git add .`  
  `git status`  
  `git commit`  
Track new files and stage them;  
view file status;  
Submit the file to the local repository.  
* `git push origin [remoteRepository(main/master...)]`  
Sync local repository files to remote repository.  
* `git fetch <remoteurl>`  
Updating files from remote repository that local repository doesn't have.  
