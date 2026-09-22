# FRC-11243
Code, CAD, etc. for Las Lomas High School's FRC Team

## Instructions:

- Create a new folder on your computer. I'd recommend creating a "projects" folder for all your different coding projects, at your root directory (this is what I do).
- install git, if you don't already have it.
   - Macs: "brew install git"
   - Windows: Download it from the installer.
- Open a terminal and navigate to this folder using "cd”.
- Paste this command in the directory to set up this GitHub repo:
  "git clone https://github.com/FRC-11243/FRC-11243.git"

## How to use this repo
- When working on code, always start by pulling the latest changes using "git pull". Make sure you pulled from the main branch; you can check this with "git branch”.
- Always use a different branch than main; this way, your changes don't affect anyone else before they're peer-reviewed. Create a new branch for every new feature, like Jake_comms.
- When you think your code is ready, create a pull request (pr) to main. Then get someone to review and merge it.

## Things to keep in mind
- Commit, commit, commit! Commit your code frequently. Don't accidentally delete your code and have your last commit be 3 hours ago.
- Use detailed messages. If you 10 commits titled latest changes, or test, or ".", you, nor anyone else will have no idea what to do with that.
- Stuck? git can be very confusing. It's not a bad idea to ask a llm for help if you're stuck, but make sure you realize that these commands have the power to screw a lot up, so be careful.

## Practice 
- Inside of the folder test_prs, create a new text file with your name(ex "jake.txt")
- Insde of the file, just put "test pr"
- Use "git branch yourname_first_pr". This creates a new branch separate from others work for you to work on
- use "git add .", "git commit -m"my first pr"", and then git push -u origin {the name of your branch}

### Example
- git branch jake_first_pr
- git add jake.txt
- git commit -m"my first pr"
- git push -u origin jake_first_pr
