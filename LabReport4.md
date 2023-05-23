Step 4:
Log into ieng6
  Open the VS code and new terminal. //screenshot
  Keys pressed: `ssh<space>cs15lsp23zz@ieng6.ucsd.edu<enter>`, where zz is unique numbers you can find in your github profile //screenshot 
  

Step 5:
Clone your fork of the repository from your Github account
 In the github when you open your repository, you press `code` and then press `SSH`. You'll see the link that you need to copy and paste in the terminal. 
 //screenshot
 Keys pressed in terminal: `git<space>clone<space>git@github.com:zshakirova/lab7.git<enter>`

 
Step 6:
Run the tests, demonstrating that they fail
To do this you need to go inside the lab7 and then run tests.
  Keys pressed: `cd<space>lab7<enter>`
`bash<space>test.sh<enter>`
//screenshot

Step7:
Edit the code file to fix the failing test
Keys pressed: `vim<space>ListExamples.java<enter>`
  `/change<enter>jllxi2<escape>:wq<enter>`
Step 8:
Run the tests, demonstrating that they now succeed
`bash<space>test.sh<enter>`
Step 9:
Commit and push the resulting change to your Github account (you can pick any commit message!)
Keys pressed: `git<space>commit<space>ListExamples.java<enter>`, I typed `changed<space>line<space>44<space>index1<space>to<space>index2<enter>` 
then to exit and save the commit press `:wq<enter>`
To push resulting change i pressed `git<space>push<enter>`
