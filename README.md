## git-branching excercise

1. Make a new folder called `Git-branching`
2. Make a new git repo inside the folder (make sure you're not in an existing repo). Use `git clone` command and clone [`git@github.com](mailto:git@github.com):WemaDev/git-branching-test.git` in the directory.
3. Create a new file called `<your_name>.txt` (leave it empty for now)
4. Add and commit the empty file, with the message "Added empty file"
5. Immediately make a new branch called `peace` and another branch called `hope` (both based on the `master` branch)
6. Move to the `peace` branch using the command to change branches.
7. In the `<your_name>.txt` file, add the following:
    
    ```
    HELLO <your_name>!
    
       /|       |\
    `__\\       //__'
       ||      ||
     \__`\     |'__/
       `_\\   //_'
       _.,:---;,._
       \_:     :_/
         |@. .@|
         |     |
         ,\.-./ \
         ;;`-'   `---__________-----.-.
         ;;;                         \_\
         ';;;                         |
          ;    |                      ;
           \   \     \        |      /
            \_, \    /        \     |\
              |';|  |,,,,,,,,/ \    \ \_
              |  |  |           \   /   |
              \  \  |           |  / \  |
               | || |           | |   | |
               | || |           | |   | |
               | || |           | |   | |
               |_||_|           |_|   |_|
              /_//_/           /_/   /_/
    ```
    
8. Add and commit the changes, with the commit message "Added image to file"
9. Move over to the `hope` branch using the command to change branches.
10.  Put the following text in  the `<your_name>.txt` file:
    
    ```
    HI <your_name>!
                       .     _,
                       |`\__/ /
                       \  . .(
                        | __T|
                       /   |
          _.---======='    |
         //               {}
        `|      ,   ,     {}
         \      /___;    ,'
          ) ,-;`    `\  //
         | / (        ;||
         ||`\\        |||
         ||  \\       |||
         )\   )\      )||
         `"   `"      `""
    ```
    
11. Add and commit the changes on the `hope` branch with the commit message "Added another image to file"-m 
12. Next, create a new branch based upon the `hope` branch called `love`
13. Move to the `love` branch
14. Edit the `<your_name>.txt` file so that it says `GOODBYE <your_name>!` at the top instead of
`HI <your_name>!` (leave the doe ascii-art alone)
15. Add and commit the change with the message "Added lovely content"
16. Run a git command to list all branches (you should see 4)
17. Merge the `love` branch to `hope` branch. Delete the `love` branch.
18. Merge `hope` branch to `peace` branch. Resolve any conflicts that may arise by accepting both changes.
19. Add and commit the change with the message “ added all changes”. Delete the `hope` branch.
20. While on the `peace` branch, rename it  `<your_name>-<Jira #>`. You can use `git branch -m <old_name> <new_name>`
21. Push your branch `<new_name>` to the remote repo. Use the commit template with Jira ticket number.
22. Create a pull request and merge your changes to main branch after review.
23. After merging, `pull` back the changes to update your local `main` branch.
24. Push the same code to your personal GitHub account. Create a repo called `git-branching`.