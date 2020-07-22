# Revisions and the Cloud
GIT Remote &amp; Local - Add, Commit &amp; Push

## What is GIT?

- Version Control System
- Creates a snapshot of the file and stores a reference to it.
- Will always detect file corruption or loss of information in transit.
- Allows for collaboration with multiple developers

## Commit

- "save as", creates a new snapshot on file timeline.
- Each time you save a changed version of your project.
- Create a notation of what was changed.

## GitHub

- Online Storage (Cloud).
- Able to share code with others (collaboration).

## Files can be classified into three main states: committed, modified and staged:

1. Committed - securely saved in local database
1. Modified - changed but not committed
1. Staged - flagged change, version to be committed

## Process of "Clone & Download" and "Add, Commit & Push"

1. Initiate **clone** on GitHub "clone with HTTPS".
1. Open Terminal
1. Check Directories
   - cd documents
   - cd projects
   - cd codefellows
   - cd 102

## *If directory is unavailable, use command "mkdir" to create it*

1. git clone "paste repo address"
1. Open VSC, use command **code .**

## You are now able to work on repository locally

- To check status of file, use command **git status**

1. git add "filename"
1. git commit -m "notation of changes made"
1. git push origin master

## Additional Helpful Commands

- git pull origin master (download current committed file to local directory. **previous version must be deleted**
- git remote -v (to verify origin)
