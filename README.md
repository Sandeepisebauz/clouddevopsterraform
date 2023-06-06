# clouddevopsterraform
Place holder for DevOps
Day1: Added a note for main branch commit
Day1: Steps to perform proper git workflow
      Step1: git checkout main
      Step2: git pull
      Step3: git checkout -b <branch_name>
             example: git checkout -b task1
      Step4: Update the file/add new file
      Step5: git add <file_name1>, ...<file_nameN>
      Step6: git commit -m "message"
      Step7: git push -u origin <branch_name>
             example: git push -u origin task1
      Step8: Create PR (pull request) via github.com and if the PR is good, merge to main branch
      Step9: Once PR is merged, run the below steps
             git checkout main
             git pull
             git checkout -b <another branch>
      Step10: Follow step4 to Step9