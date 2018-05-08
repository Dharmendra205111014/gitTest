# gitTest
Repo to test git commands

# Test commands

## log format
    `
    Decorate
    git log --stat or git log -p [Log with diff]
    git log --oneline --graph --decorate --all

    Filter
    git log -3
    git log --after="yesterday" || git log --after="dd-MM-yyyy"
    git log -- FILE1 FILE2 [To get log for given files]
    git log --grep="commit message"
    git log --author="author1\|author2"
    git log --merges && git log --no-merges
    git log -p -- FILE1 FILE2

    git tag XX.XX.XX [To create tag]
    git push origin XX.XX.XX [To push one tag]
    git push --tags [To push all tags]
    git tag --list  or git tag -l [To see list of tags]
    git push --delete origin tagname [To delete tag]
    git push origin :tagname and git tag --delete tagname [To delete tag]
    `
