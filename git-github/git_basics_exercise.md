# How to use Git/Github for web development teamwork: A basic exercise.

Simply follow the instructions in this brief manual. 

Keep in mind that Microverse encourages it's students to search for their own solutions online. If you don't know how to do something required by this exercise, try to google it first. If you still encounte trouble, feel free to contact your Practice Sessions Coordinator.

Before we begin, choose one teammate to be `Student A`, and another to be `Student B`. If you've already completed steps 1-3 feel free to skip them. Once you're ready, just follow these steps in order:

1. Both `A` and `B`: Create an account on [https://github.com/](https://github.com/).
2. Both `A` and `B`: Download and install `git`. Windows users can use [https://gitforwindows.org/](https://gitforwindows.org/). Linux users can use `sudo apt-get install git` instead.
3. Both `A` and `B`: Download and install `Visual Studio Code` from here: [https://code.visualstudio.com/download](https://code.visualstudio.com/download). This may take some time, so be patient.
4. Student `A`: Create a new github repository. If you've never done this before, google `How to create a new github repository`.
5. Student `A`: Add student `B` as a collaborator to your newly created repository. Again: use google here if you are unfamiliar with this process.
6. Student `B`: You should receive an e-mail with an invitation to become a collaborator. Open it, and accept the invitation on GitHub.
7. Both `A` and `B`: Clone the repository using the `git clone` command in terminal you installed on step `2`.
8. Both `A` and `B`: Once you've cloned the repo folder on your terminal, use the `cd your-repo-name` command to navigate into the repository folder. Just replace `your-repo-name` with the name you used to create the repository on github.
9. Both `A` and `B`: Use the `pwd` command to display the path where the project was saved in your computer.
10. Both `A` and `B`: Open the repo folder from that path in `Visual Studio Code`.
11. Student `A`: Add a file to the project named `index.html` with the content `Hello, World!` and save it.
12. Student `A`: Check `git status` command.
13. Student `A`: Back at your `git` terminal, enter the `git add .` command.
14. Student `A`: Check `git status` command again. Observe changes in the output.
15. Student `A`: Enter the `git commit -m "First commit"` command.
16. Student `A`: Enter the `git log` command. Your last commit should be on the list.
17. Student `A`: Enter the `git push` command. Enter your GitHub credentials if the terminal requires them.
18. Both `A` and `B`: Check the `github.com` page of the repo and note how the `index.html` file was added there.
19. Student `B`: Using your `git` terminal, enter the `git pull` command. This should add the `index.html` file created by `A` to your local clone of the project.
20. Student `B`: Enter the `git log` command. The last commit pulled from GitHub should be on the list.
21. Student `B`: Open the project on `Visual Studio Code`.
22. Student `B`: Add the line `How are you?` to `index.html`.
23. Student `B`: Just like `A` did before, use `git add .`, `git commit -m "Updated index"`, `git push`:
      - Note how your commit is added to history by checking the output `git log` command.
      - Note how the changes are added to the GitHub page.
24. Student `A`: Use `git pull` to apply the changes on your local clone.

Congratulations! Now you know how to collaborate together on a web development project!

Now use your new programming skills to move forward with the HTML/CSS project.

Cheers and Happy Coding :)!
