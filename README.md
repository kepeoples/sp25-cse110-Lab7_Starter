## Check Your Understanding

**1) Where would you fit your automated tests in your Recipe project development pipeline?**
**Answer:** Within a GitHub action that runs whenever code is pushed.  This helps automatically check that the code still works after every change. It prevents bugs and saves time by 
avoiding manual testing every time. 

**2) Would you use an end to end test to check if a function is returning the correct output?**
**Answer:** No. E2E tests are meant to simulate how a user interacts with the entire application. To check if a single function works correctly, unit tests are more appropriate.
