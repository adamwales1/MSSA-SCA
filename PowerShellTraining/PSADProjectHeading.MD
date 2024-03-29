# PowerShell Projects

## What is required

- You need to run these projects from the **"AZ-040T00 Automating Administration with Windows PowerShell [No Azure Pass Required], Labs 1-8"**
- You need to create a new PowerShell module per project
- You need to make the modules load automatically when you go to launch the function that you have built
- You need to make sure that there is Comment-Based-Help provided for each of the functions
- You need to complete at least on of these projects today.

## Hints

- Get-Command 
  - This will help you find the command you need based on its name of module
- Get-Help
  - This will help you discover how to execute the command you have found and which parameters are included in this command
- Get-Member 
  - This will show you what was the output of a command
- Where-Object 
  - This will only show objects that fit a criteria
- ForEach or Foreach-Object 
  - These will help you perform some actions against each of the objects in an array
- if   
  - Will allow code to execute only if a condition is $true

[Go to Project 1](PSADProject1.md#create-new-users-in-active-directory-from-a-csv-file)<br>
[Go to Project 2](PSADProject2.md#restore-an-accidently-deleted-ad-user-account-from-the-recycle-bin)<br>
[Go to Project 3](PSADProject3.md#find-all-direct-and-indirect-groups-an-ad-user-is-a-member-of)<br>
