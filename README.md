# poweshell-profile

two locations 

`C:\Users\Gaizka\Documents\WindowsPowerShell\Microsoft.PowerShell_profile.ps1` and `C:\Users\Gaizka\Documents\PowerShell\Microsoft.PowerShell_profile.ps1`

```
Import-Module posh-git
Import-Module posh-alias

function prompt { "> " }

Add-Alias add 'git add'
Add-Alias status 'git status'
Add-Alias push 'git push'
Add-Alias pull 'git pull --rebase'
Add-Alias commit 'git commit'
Add-Alias checkout 'git checkout'
Add-Alias branch 'git branch'
Add-Alias merge 'git merge'
Add-Alias switch 'git switch'
Add-Alias restore 'git restore'
Add-Alias log 'git log'
Add-Alias diff 'git diff'
Add-Alias rebase 'git rebase'
Add-Alias stash 'git stash'
Add-Alias reset 'git reset'
Add-Alias grep findstr
```
