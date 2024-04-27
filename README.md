# SNHU-CS-305

- Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financials is a consulting company that handles sensitive customer financial data. They requested a review and update of their application's security to ensure that it met with industry standards and protected their customers.

- What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
Identifying Artemis Financials' requirements was one of my most effective steps in the project. It is easy to understand why a company such as Artemis Financials would be concerned for their software security. Best practices help to ensure that data is protected from exposure and the software is protected from various types of attacks.

- What part of the vulnerability assessment was challenging or helpful to you?
The initial vulnerability assessment, while somewhat difficult to interpret, provides a baseline understanding of what types of vulnerabilities are highly common in the frameworks we used, as well as whether or not there was anything we could do about them. Having this knowledge inspires confidence in the overal security of the project. 

- How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
We were able to introduce cryptography and SSL, as well as the requisite keystore and certificate that help to protect communications, and followed best practices in relation to exception handling and data encapsulation. Tools such as the Maven dependency check are extremely valuable for projects with a significant quantity of dependencies, but the resources it pulls from, such as the NISt, are still valuable and usable in different scenarios.

- How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
In this specific project, the dependency check provided through Maven was our guide for vulnerability assessment. Through multiple runs of the check, we can verify that any code refactoring did not introduce vulnerabilities.

- What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Official documentation for the tools and frameworks we used, such as Spring, as well as the dependency check plugin provided by Maven, were extremely helpful in maintaining best practices.

- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
Again, I would like to recognize my interpretation of Artemis Financials' requirements and the areas of security that should be addressed in relation to them. It is a critical component of software security to have an understanding of what the software is expected to do in order to introduce protections for those functions.
