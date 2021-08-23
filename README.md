## Example of Working with Remotes

Use Case: You have a repository on your computer containing
some code. How do you copy this repository to Github?

0. Create an empty repository on Github for your code.
   - copy the URL that Github shows you.

1. (On your computer) Add a remote to your local repository
   ```
   $ git remote add origin git@github.com:sirateek/example.git
   ```

2. Push some work **and** tell git to use thuis as the "default" **upstream** repository:
   ```
   $ git push --set-upstream <Remote> <Branch>
   ```


### Git Branches

