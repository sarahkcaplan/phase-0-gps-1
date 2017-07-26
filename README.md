# phase-0-gps-1
1  git clone https://github.com/agrzegorek/phase-0-gps-1.git
# download clone of code
    3  cd phase-0-gps-1/
# cd - change directory
    4  touch awesome_page.md
# touch create file
    8  git add awesome_page.md
# git add: prepares files for adding/staging
    9  git commit -m "created awesome page"
#git commit -m: Actually making the save with message
   10  git status
# checks the status of git
   11  git push origin master
# git push: pushing changes up to origin 
   13  git checkout -b add-command-log
# git checkout -b: creates a new branch
   14  git status --help
# --help: opens man page for whatever command is before it
   16  subl . README.md
# ls: lists what is in the directory
   17  history