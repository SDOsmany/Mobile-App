# Mobile-App
Simple mobile app to git started ;)




## Quick Setup

1. Clone the repository

    ` git clone https://github.com/SDOsmany/Mobile-App.git `
    
    **Note : this will clone all the files in this repo to the path(directory) you are on in the git terminal
2. Create a ` .gitignore ` file to ingore changes to files we don't need to keep track of

    ` touch .gitignore `
    
3. Create an environment varaible file

    ` touch .env `
    
    
    
## Git Workflow 

![ndcworkflow](https://user-images.githubusercontent.com/26397102/116148813-00512800-a6a7-11eb-9624-cd81f11d3ada.png)


Folder/branch organization should follow this convention:

`main`
- no test features
- 100% stable and usable by any lab members 
- *no direct commits*

`->dev`
- Up to date development branch with properly tested/reviewed features 
- *no direct commits*

`-->dev-feature-[featureName]`
- Ongoing development and testing of feature to be pull requested into `dev` 
- *no direct commits*

`--->dev-feature-[featureName]-[yourName]`
- *only* branch available for personal development, must be branched off of `-->dev-feature-[featureName]` branch
- Merged into `-->dev-feature-[featureName]` after pull-request (code review)


## Reminders
1. only push directly (without code review) to dev-feature-[featureName]=[yourName]
2. Must initiate pull request (and assign at least one person) for any higher-level branch
3. Mandatory code review by one person for all pull requests 
