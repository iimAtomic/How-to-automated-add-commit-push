# HOW TO AUTOMATE ADD-COMMIT-PUSH

![Lazy Goku](https://vectorified.com/images/dragon-ball-icon-39.png)

This is an easy method to automate your pushes at the end of the day if you're as forgetful as I am.

## Installation

Download this code and open it, in the `index.bat` file, you need to make the following changes:

```bash
git add .
git commit -m "YOUR_COMMIT_MESSAGE %DATE%"
git push origin YOUR_BRANCH
```

## Usage on windows

:zap:Open Task Scheduler: Find Task Scheduler in the Start menu and open it.

:zap:Create a task: Click Create task in the right pane. Give your task a name,
    choose Run whether the user is logged in or not, and configure it to run your batch script.
    Under the Triggers tab, click New and set it to trigger on time
    desired every day.

:zap:Action: Under the Actions tab, add a new action to start a program, and select your
    batch script.

## Notes Importantes :

:zap:Git Authentication: Make sure your system can push to your repository without manual intervention.
          This may require configuring authentication by
          SSH key or using a credential manager for Git.

:zap:Security: Keep in mind the security implications of leaving a script
          have access to your Git repositories.
          
:zap:Automating these tasks can save you time and ensure regularity in your commitments.
          Git, but use it wisely, especially on shared projects where automatic commits
          can disrupt the team's workflow.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.


## License
OPEN  SOURCE
