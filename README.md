# Homework Assignment #1
## KIEI-924 Fall 2018

### Guidelines for submission

1. From your Cloud9 IDE, grab this repository:

```
cd ~/environment
git clone https://github.com/kiei924-fall18/hw2
cd hw2
./cleanup
```

This will create a directory called `hw2` in your Cloud9 IDE.

2. Complete the homework per the instructions in the `hw2.rb` file.

3. Commit and publish your `hw1` repository to your GitHub account:

  - From GitHub.com, click "New" next to "Repositories". Call it `hw1` and accept the defaults. Be sure to keep the repository *public*.

  - Enter these commands from within your `hw1` directory on Cloud9:

  ```
  git init
  git add .
  git commit -m "commit hw1"
  git remote add origin git@github.com:<your GitHub username>/hw1.git
  git push -u origin master
  ```

If everything went right, you should now see your completed homework at `https://github.com/<your GitHub username>/hw1`