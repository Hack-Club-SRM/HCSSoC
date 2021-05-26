![Header](assets/Header.png)
# Project Application
## Important Dates
| Date | Header | Description |
| ----- | -------- | -------- |
| 28th May | Project Application Starts | Mentors and Organizations start submitting their project proposals. |
| 7th June | Project Application Deadline | Hard deadline for submitting Project Application Proposal. |
| 9th June | Projects Announced | Projects shortlisted for HCSSoC will be announced. |

## Submitting Project Application
Follow these steps to successfully submit your Project Application!

1. Clone this repository.
   `git clone https://github.com/Hack-Club-SRM/HCSSoC.git`
2. Head over to the `project_proposals` folder.
3. Create a new branch with your GitHub Username as the name of the branch.
   `git branch username`
   In case you are trying to submit more than one proposal, follow the format below and increment the value with each submission.
   `git branch username-1`
4. Switch your branch before making any changes so it's easier for you to make the submission.
   `git checkout username` (just replace username with the name of your branch)
5. Inside the `project_proposals` folder, checkout `sample.md`. Copy the contents of the file.
6. Create a new file of the following format:
   `username - Name of Project.md`
   Paste the contents of `sample.md` and make changes according to your preferences. 
7. After you are through with making changes to your Application, push the file to your branch.
   `git add .` or `git add (name of your file)`
   `git commit -m "Application - Name of Project"`
   `git push origin (name of branch)`
8. Create a **Pull Request** and fill out all the details. 

#### If your Application is shortlisted, your Pull Request will be merged and our Team will get in touch with you.

If you face any difficulties with the submission of your Project Application, open an **Issue** and we'll try our level best to help you out at the earliest.