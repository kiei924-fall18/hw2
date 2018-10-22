# Homework Assignment #1
## KIEI-924 Fall 2018

### Guidelines for submission

From your Cloud9 IDE, grab this repository:

```
cd ~/environment
git clone https://github.com/kiei924-fall18/hw2
cd hw2
./cleanup
```

This will create a directory called `hw2` in your Cloud9 IDE.

Complete the homework per the instructions in the `hw2.rb` file.

Commit and publish your `hw2` repository to your GitHub account:

  - From GitHub.com, click "New" next to "Repositories". Call it `hw2` and accept the defaults. Be sure to keep the repository *public*.

  - Enter these commands from within your `hw2` directory on Cloud9:

  ```
  git init
  git add .
  git commit -m "commit hw2"
  git remote add origin git@github.com:<your GitHub username>/hw2.git
  git push -u origin master
  ```

If everything went right, you should now see your completed homework at `https://github.com/<your GitHub username>/hw2`

If you need to make changes to your submission, you can simply make the changes, and issue these three commands:

```
git add .
git commit -m "commit hw2"
git push
```

This is the equivalent of "commit and publish" using the GitHub desktop app.