# Create-New-Project-On-GitHub-from-LapTop-Or-PC-With-CommandLine-369
ALL CommandLine for gitHub
- Step -1:
    - Download GIT and Install : https://git-scm.com/downloads
- Step -2:
    - Git cua Tui (https://github.com/dolathanchuong?tab=repositories)
    - 0. DownLoad and Install: https://cli.github.com/
    - 1. Open CMD:
        - input :
            - gh auth login
            - gh repo create
            - cd banhmiChaySG
            Open folder nay Len Va Paste Project Vao
            - git checkout banhmiChaySG
            - git add .
            - git commit -am "Description File Or Project Commit to Git"
            - git push origin main
- Step -Orther:
    - git remote set-url origin https://github.com/dolathanchuong/banhmiChaySG369.git

``` LINK HOME CommandLine GitHub
    * link : https://cli.github.com/manual/gh_gist_clone
    * Clone: gh repo clone dolathanchuong/CommanderGraphQL
```

``` Command Line Execute for CLI:
    --https://cli.github.com/manual/gh_repo_rename 
    **$$$$$$$$$$$$$$$$$$$$$$$$__Get branchs__New Branch from Exists Branch__$$$$$$$$$$$$$$$$$$$$$$$
    cmd: git branch -->>get All branch
    cmd: git checkout -b <new-branch><existing-branch> -->> Create new Branch from Exists BranchMain(Example: git checkout -b DataLoader369 GraphQL369)
    cmd: git checkout DataLoader369 -->>Switching branches
    cmd: git commit -am "Your message" -->> View current Branch
    cmd: git checkout GraphQL369
    cmd: git merge --no-ff DataLoader369 -->>merge to new branch
    cmd: git push origin DataLoader369 -->> Push to git
    cmd: git fetch origin
    cmd: git merge origin/DataLoader369
    cmd: git rebase origin/DataLoader369
    cmd: git pull origin DataLoader369
    --Change content in file
    cmd: git add . (note : git add path/to/customer-file.ext  # Stage the specific file)
    cmd: git commit -am "change txt 123" (note: if error ==> git branch -u origin/main)
    cmd: git push origin DataLoader369

    https://github.com/CloudKlabauter/HotChocolateWorkshop/blob/main/challenges/03-schema-design-approaches/README.md
```