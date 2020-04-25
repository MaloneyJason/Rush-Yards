# Rush-Yards

### Useful git commands
```git
\\ To update a branch with your new code...
git add . \\ '.' for everthing, or you can specify a file
git commit -m "your comment here" 
git push \\ push your code to the branch
```

```git
\\ To create a feature branch and push to it
git checkout -b branchName
git add . 
git commit -m "your comment here"
git push --set-upstream origin branchName
```

```git
\\ To checkout an existing branch, make edits, and push
git checkout branchName
git pull \\ just in case
git add . 
git commit -m "your comment here"
git push
```
To merge your feature code to the master branch, use the UI. 
* Navigate to the feature branch in the UI
* Click on compare and pull
* Add reviewer 

![example](https://raw.githubusercontent.com/MaloneyJason/Rush-Yards/readMeExample/PulRequestExample.PNG?token=AIBNHRF3FHXNJGHSS7OSZCK6USOVY)]
