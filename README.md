# SystemSecutiryAssesment
software security report detailing software concerns

## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

  In this project, Artemis Fiancial wanted to have their codebase reviewed to adress security concerns. They wanted to run denpendency reports, incorperate and recommend and algorithim cypher, manual codebase review, https protocol implementation, and have self-generated certificates.
  
## What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I really enjoyed the dependency check as well as cypher deployment. routing is somemthing I have used in previous projects and was fun and interesting to learn java deployment with spring and secure server integration using CA's. Coding securly is instrumental in providing a safe platform for customers and users. Customers need to be confident in the protection of their information. Companies also retain a fair amount of private information regarding themselves and their business. Private information needs to always be protected and secured so it cannot be stolen. Adding software security will protect the company and its users from malicious intentions, and therefore will provide a more promising and protected experience from the company to the customers.

## What part of the vulnerability assessment was challenging or helpful to you?

  I found it hard to implement my self-generated CA and had to modify xml to get the desired results. I also found there are multiple tools besides just the keytool.exe file that can help generate these CA's.
  
## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

  Proper error handling can always be incoperated at numerous levels in an application. This helps protect from infiltrators trying to access certain content without permissions or modify database with querries usiing unprotected/limited characters. I would always use dependency checks and manual code review where assessing vulnerabilities. Dependency checks can help recognize known issues with dependencies (especially older verisons) which can help you implement certain error handling and descision branching to mitigate these concerns. Manual code review is always crucial because without testing and running the program it can sometimes be hard to see some of the areas where the application security is weak.
  
## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  I was able to implement error handling and updates to the dependencies used. This created some false positives in the dependency report, but reduced known exploits dramatically. Dependency reports can be used to check for new introduced vulnerabilites as different versions of different packages have different known exploits.
  
## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Learning the ins and outs of Spring is something I have taken from this course and want to become more proficient in. With a MERN stack background there are similarities in setup and I feel like I could get a lot stronger in Spring with Maven testing. Generating CA's is also a newer concept that I alsobelieve I can use further in java development as it is crucial for runninig https protocol.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

  I would show future employers encryption and implementation of hashing. I would also show them the routing in java as well as running a proper dependency report. These tool are crucial in applicaiton development.
