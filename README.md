# Git/Github tutorial

Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. 


GitHub provides hosting for software development version control using Git.


A REPOSITORY (repo) is a directory or storage space where your projects can live.
  - you can initialize a repo in an existing directory
      - go to that direcorty; type: 'git init'
  - you can clone an existing repo from elsewhere

- you can use the 'git status' command to see which files git knows exist.

A CLONE is used to point to an existing repo and make a clone/copy of that repo at in a new directory, at another location.
  - git clone <url>


A COMMIT is is a record of what files you have changed since the last time you made a commit. 
  -you make changes to your repo (e.g. adding/modifying files) and then tell git to put those files into a commit
  - allow you to go back to the state of a project at any point
  - use the 'git add <filename>' command to add files to staging enviornment (aka index)
  -then you can tell git to package them into a commit using 'git commit' command 
  
BRANCHES allow you to move back and forth between states of a project.
  - git keeps track of which commit you branched off of 

A push is used to upload local repository content to a remote repository.

A pull is used to update the local version of a repository from a remote one. 

A Merge will combine multiple sequences of commits into one unified history

Merge Conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.

A Fetch downloads commits, files, and refs from a remote repository into your local repository.

A Remote a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service.
