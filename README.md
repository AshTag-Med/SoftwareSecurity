# SoftwareSecurity
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a financial institution who wanted to provide secure avenure to condunct financial transactions in a global market. They wanted to ensure that the API they had designed was secure.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
One aspect of the vulnerability assessment which went well was the threat detection, mainly thanks to the dependecy check plugin that was available. Having secure code builds trust for the client's customer base as well as protect then from a financial and legal standpoint too. 

Which part of the vulnerability assessment was challenging or helpful to you?
Identifying the false positives, which we had to do later on, was very difficult as some of the issues could be secured and fixed with some updates. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Adding input validation was a huge factor which was initially overlooked which was added. Followed by encapsulating specific code in private functions as well as exception handling to avoid data leaks. 

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
We reran the initial tests to see that no vulnerabilities were detected. I also did a manual code review of the code base to see if there was any spots of identifiable weakness. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The maven dependency check was something I have never used before since most of the projects I have worked on were local and small scale and not used in a corporate setting. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
This assignment specifically helped me gain a better understanding of normal secure coding practices, those mainly involving error handling and input validation. I had overlooked these in some of the other projects I had done, and will incorporate moving forward in my work. 
