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
