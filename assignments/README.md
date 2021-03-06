To submit an assignment:

1. Update your private repository to get the assignment files:
  ```
  cd [my_repo_name]
  git pull
  ```
  This will create a new directory, e.g., `assignment0`.

2. Do the homework, adding and modifying files in the assignment directory. **Commit often!**

3. Before the deadline, push all of your changes to GitHub. E.g.:
  ```
  cd assignment 0
  git add *
  git commit -m 'homework completed'
  git push
  ```

4. Double-check that you don't have any outstanding changes to commit:
  ```
  git status
  # On branch master
  nothing to commit, working directory clean
  ```

5. Double-check that everything works, by cloning your repository into a new directory and executing all tests.
  ```
  cd 
  mkdir tmp
  cd tmp
  git clone https://github.com/iit-cs429/[your_iit_id]
  cd [your_iit_id]/assignments/assignment0
  [...run any relevant scripts/tests]
  ```
