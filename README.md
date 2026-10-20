Some simple steps for working in github:

These instructions should be carried out in command line. If you are not familiar, come chat with me and we can figure it out together! GitHub desktop is another option with GUI.

1. Clone the repo (once): git clone git@github.com:jmelanson98/REX_2026
2. Before starting work, get the latest: git checkout main then git pull
3. Make a branch: git checkout -b yourname/short-description
4. Do your work, then: git add . and git commit -m "Describe what you changed"
5. Push the branch: git push -u origin yourname/short-description
6. On GitHub (in web browser), click the Compare & pull request banner that appears, write a short description, and submit.
Wait for review. If you request changes, they commit more to the same branch and push again; the PR updates automatically.
