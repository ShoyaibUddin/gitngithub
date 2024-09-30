# LWS এর থেকে প্রপ্ত বিষয় সমূহ

এই তিনটি বিষয় মনে রাখতে হবে।

1. Working Directory
2. Git Local Repository
3. Remote Directory

## Working Directory

- বর্তমান ডারেক্টটরি দেখার জন্য কমান্ড হলো

```
PWD (present working directory)
```

- নতুন ফাইল তৈরী করার জন্য কমান্ড হলো

```
touch readme.md
```

- একটি ফাইল এবং ডিরেক্টরি তালিকা দেখানোর জন্য।

```
ls
ls -a (hidden ফাইল দেখার জন্য)
```

## Git Repository

#### গিট এর কনফিগারেশন দেখার জন্য

```
git config --list
```

- গিট এর User Name and Email সেটাপ করার জন্য

```
git config --global user.name "shoyaib"
git config --global user.email "shoyaib@shoyib.com"
```

- গিট এর অবস্থা দেখার জন্য

```
git status
```

- গিট Install দেওয়ার জন্য

```
git init
```

git track করার দুইটি স্টেজ আছে.

1. আমি এই ফাইল বা এই ফোল্ডার গুলোকে ট্রাক করাতে চাই।

```
git add --all
git add file Name
git add . (present directory)

```

#### গিট কমিট

```
git commit -m "MyMessage"

```

### গিট History দেখার জন্য।

```
git log
git log --oneline
```

### গিট history back যাওয়ার জন্য।

```
git log --oneline
git reset --hard (id)
```

### গিট সমস্ত history back যাওয়ার জন্য।

```
git reflog
```

### কোন ফাইল রিমুভ করতে চাইলে

```
git rm fileneme
```

## Branching

### সব Branch দেখার জন্য

```
git branch --list
```

### নতুন ব্রঞ্চ তৈরী করতে

```
git branch BranchName
```

### এক ব্রঞ্চথেকে আর এক ব্রঞ্চযে যাওয়া

```
git switch BranchName
```

### এক ব্রঞ্চ কে অন্য ব্রঞ্চের সাথে এক করা

```
git merge BranchName
```

### কোন ব্রঞ্চকে ডিলিট করা

```
git branch -d branchName
git branch -D branchName

```

### কোন ব্রঞ্চকে নামকে মডিফাই করতে

```
git branch -m newBranchName

```

<<<<<<< Updated upstream
## git stash commit না করে লুকিয়ে রাখা

### stash করার জন্য

```
git stash

```

### কি লুকিয়ে রেখিছিলাম দেখার জন্য

```
git stash show -p

```

### stash গুলো দেখার জন্য

```
git stash list

```

### শেষ লুকানে জিনিস আনার জন্য

```
git stash pop
git stash apply id... ধরে আনার জন্য

```
=======
Main din
>>>>>>> Stashed changes
