---
title: Testing - test cases
layout: default
---

### Requirement / Story / Correctness statement:

“Allow the appropriate user to select a date sometime in the future and save it to their account when logged in”

A single test could make this pass. It may look like it is saved. 
Now use the word “unless” to generate all the problems that could arise and test for those.

- it does not save at all
- it saves an incorrect format 
- it was saved to the wrong or multiple accounts
- a past date can be selected 
- a past date is saved
- the wrong user type can select a date
- an inappropriate error message appears
- the app crashes
- etc