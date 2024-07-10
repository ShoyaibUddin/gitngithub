# GitHub

## Topic

- add, commit, push on github
- pull
- how to create issues
- branch and merging
- resolve merge conflict
- ssh key
- basic commands
- collaboration
- github pages
- git merge vs git rebase

### 1. remot repository check

```
git remote -v
```

```
git push
git pull
```

## git Issues

Issue তৈরী করে তারপরে সেটিং থেকে collaboration add করা

- collaboration
- label

### Collaboration

আপনাকে কোন প্রজেক্টে এ্যড করা হলে তখন আপনি Collaboration করতে পারবেন।

### Contribution

এটার জন্য আপনাকে (fork => clone) করতে হবে

> fork = 3rd party repo => own github => git clone করে নিজের পিসিতে নামিয়ে কাজ করতে হবে।

## branch and merging

### branch

```
git branch
git chckout -b newbranch
git branch devlopment
git checkout devlopment
```

### merging

```
git checkout main
git merge devlopment
```

merge prectice
**ref: get-school.github.io**

Type of merge

- Fast-forward merge. (two way merge)
- Three way merge

[Example Ref ](https://youtu.be/LPuTX9qfYNk?list=PLgH5QX0i9K3pShEf_RCcVqPKxFm7sOLVD&t=4099)

# resolve merge conflict

[Resolve marge request on github](https://youtu.be/prsZFP2UoDg?list=PLgH5QX0i9K3pShEf_RCcVqPKxFm7sOLVD&t=3077)

```

```

## ssh key (Secure Socket Shell)

- ssh key generate key
- ssh public key add to github

```
ssh-keygen -t ed2525519 -C "youremail"
```

[Example Ref](https://youtu.be/prsZFP2UoDg?list=PLgH5QX0i9K3pShEf_RCcVqPKxFm7sOLVD&t=1137)

## github page

এটার মাধ্যমে কোন একটা প্রজেক্টকে লাইভ দেখতে পারব।

Repo => Settings => Branch একটা ব্রাঞ্চ দেখাতে হবে তারপর লাইভ লিং এর জন্য অপেক্ষা করতে হবে।

# Git Advance topic

- git merge vs git rebase
- GitHub Action
- git flow / github flow, Trunk basked devolopment
- rewriting history: git reflog, git filter-branch, git cherry-pik
- Performance and Optimization: Shallow clones, Partial clones

## Undo Changes

> **wrok flow** Working directory => stagging area => local ripo => remote ripo

#### Working directory Undo

[ref](https://youtu.be/TSxLhTrj6GI?list=PLgH5QX0i9K3pShEf_RCcVqPKxFm7sOLVD&t=964)

```
git checkout --file name
git checkout -- . (all file discard)
```

#### Staging area Undo

```
git reset HEAD . (all file unstage)
```

#### Stage + Working area Undo

```
git reset --hard HEAD . (discard from Staging & unstaging)
```

#### Commit Undo

> git --log online

> git commit --amend

কমিট ম্যসেস পরিবর্তন করা জন্য
[git commit --amend ](https://youtu.be/TSxLhTrj6GI?list=PLgH5QX0i9K3pShEf_RCcVqPKxFm7sOLVD&t=1776)

> এটার মাধ্যমে শুধু মাত্র ম্যসেস পারিবর্তন না যেকোন ফাইলকে ও যুক্ত করা যায়।

```
git revert HEAD (undo a latest commit)
git reset --hard #commit id


```

[Ex](https://youtu.be/TSxLhTrj6GI?list=PLgH5QX0i9K3pShEf_RCcVqPKxFm7sOLVD&t=2321)

> revert history মেইটেইন করে এটা ব্যবহার করা উত্তম

> কিন্তু reset history মেইটেইন করে না ।

#### Push Commit Undo

```
git revert #commit id ( then push)
git push --force (Dengerous commit)
```
