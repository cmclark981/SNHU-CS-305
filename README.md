# SNHU-CS-305
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Our client, Artemis Financial, is a financial consulting company. They develop finacial products for thier customers. Some of those products include retirement savings and investments. Artemis approached Global Rain to take the steps needed to ensure their software was utilizing the most current and effective secure practices available for their custom software. 

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I feel like I managed to perform well at code review and refactoring. In order to provide better security we need to be able to identify issues in the code and remedy those issues. Secure coding is necessary in order to protect the client's and the customer's data. A company that practices safe coding is more valuable and will gain a reputation for protecting data. This makes those types of companies a better investment and lends to a better reputation and trustworthiness. 

What about the process of working through the vulnerability assessment did you find challenging or helpful?

The most challenging part is identifying the false positives in the report. Parsing through the entire list and comparing it to the code base can be tedious. However, suppressing false reporting is important to the develpment team. Also, being familiar with vulnerabilities and taking action to correct those issues is part of using best practices in secure coding. 

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

The approach was fairly simple. Identifying the proper cryptography methods needed and implementing the appropriate algorithms within the code accomplished my goals. Adding error checking also helped increase the likelihood of finding any issues that were overlooked. I believe it will be necessary to understand how the various encryprition algorithms and how they affect system performance. In the future I will be sure to understand what limitations the system may have and not try to implement sercure code that would affect that. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

Running the code and having the system output a generic message and checksum value indicated whether the system was operating as intended or not. Running a dependency check after changes made, and after security measures were added, helped to identify any new vulnerabilities that may have been inadvertently added. 

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

Researching the NIST library and running Maven dependency checks was very helpful. 

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

The ability to generate self-signed SSL certificates in order to emulate a secure development environment would be something worth demonstrating to a potential employer. Having knowledge of DevSecOps and dependency checks would also be a valuable skill to add. 
