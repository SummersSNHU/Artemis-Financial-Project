# Artemis-Financial-Project

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a consulting company that develops individualized financial plans for their customers. They wanted to make sure thier software is secure and up to date.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I ran the OWASP plugin to identify any vulnerabilites. Doing so pointed out out of date software that left Artemis Financial's software vulnerable. I updated the out of date libraries an eliminated holes in there security. It is important to use up to date libraries do code securely. This will keep the company doing well by making data breaches less likely.

What part of the vulnerability assessment was challenging or helpful to you?

I had never worked with any vulnerabilty plugin before. Learning to read the .pom file was difficult for me.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I added a certificate to the site. This allowed for HTTPS. In the future I will use the current version of the OWASP plugin to identify vulnerabilities.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After refactoring the code, I ran the OWASP plugin again. Once I found the project was secure, I did a manual code review. I looked at each file to make sure I was following standard practices.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I used a lot of outside resources for this project. The provided material was good, but I needed more. I watched a lot of YuoTube videos, as well as utilized the drop in, drop out tutoring provided.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I can use this asignment to show that I can generate a self-signed certificate for testing purposes. I can also show them I was able to identify and patch vulnerabilities in a java program.
