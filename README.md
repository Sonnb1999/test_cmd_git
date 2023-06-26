<!-- # test git add 

git add . (update all code to git)
git commit -m 'this is commit' (this is commit)
git push (update code to git)
git push --force (update supper)
    reset git
    5b0690c HEAD@{0}: commit: this is 3
    fde3380 HEAD@{1}: commit: this is 2
    06ec0fa HEAD@{2}: commit: this is ok

    nếu muốn về head 2

git reset --hard HEAD~2 (delete head~0 and head~1)
git reset -- soft HEAD~2 (restore head~0-1 and not delete code)
git push --force

tạo nhánh (new branch)

git branch name_branch
git checkout -b name_branch
git push -u origin name_branch
or
git push -u remote name_branch
git push -u https://github.com/Sonnb1999/test_cmd_git.git update_1

add new branch and pull all code to new branch
git push --set-upstream origin updated_1
git merge name_branch


delete branch

// delete branch locally
git branch -d localBranchName

// delete branch remotely
git push origin --delete remoteBranchName
-->