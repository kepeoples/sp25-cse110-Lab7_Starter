## Check Your Understanding

**1) Where would you fit your automated tests in your Recipe project development pipeline?**  
**Answer:** Within a GitHub action that runs whenever code is pushed.  This helps automatically check that the code still works after every change. It prevents bugs and saves time by 
avoiding manual testing every time. 

**2) Would you use an end to end test to check if a function is returning the correct output?**  
**Answer:** No. E2E tests are meant to simulate how a user interacts with the entire application. To check if a single function works correctly, unit tests are more appropriate.

**3) What is the difference between navigation and snapshot mode?**  
**Answer:**  
Navigation mode audits the page from the moment it begins loading, giving a full performance picture including metrics like load time and interactivity. Snapshot mode only analyzes the current state of the page as-is, which is useful for checking accessibility but does not measure JS performance or dynamic content loading.

**4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.**
**Answer:**  
1. Optimize image sizes to improve page load speed.  
2. Add descriptive `alt` text to images for better accessibility.  
3. Eliminate unused JavaScript and CSS to enhance performance and reduce load time.

