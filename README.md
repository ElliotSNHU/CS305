# CS305
Software Security

1.) Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The client, Atermis Financial deals with fincancial accounts and customer information. The client was looking to increase the security of their web application that already existed.

2.) What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I used techniques learned from the course material to identify false positives in the vulnerability report. I suppressed these false positives and updated any versions that were out of date. Coding securely is important because of the sensitive data that the program handles. Being secure adds wellbeing to a company because it builds trust with their customers. Many complanies deal with vast amounts of data that can be harmful to the individual if that data is intercepted.

3.) What part of the vulnerability assessment was challenging or helpful to you?

The vulnerability assessment was helpful for me to highlight all the potential avenues for data loss. I was surprised that a simple program had the potential for that many issues.

4.) How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

A tool like the dependency assessment was very useful to begin to identify vulnerabilities. I reviewed the vulnerabilities to determine if they needed to be suppressed or acted upon. I checked plugin versions and updated any that required it. I added a checksum to the web server and a certifcate to ensure it was validated and using https. 

5.) How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

Running the depency check after making changes and comparing the results was useful to confirm nothing changed negatively. A test case was already in place, but more test cases would be useful to check that all angles of your code are covered. Having strict guidelines is important to ensure techniques like injection cannot occur. 

6.) What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The maven dependency check was useful, resources such as stackoverflow allowed me to reference syntax that I have yet to engrain in my memory. 

7.) Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

This assignment shows I have a foundational understanding of server authenticity and security. I have shown in this project that I understand how to create security measures that can benefit the company and keep their information secure. Proper documentation, clean coding, and adhering to high standards of security are paramount when dealing with software security. The field is always expanding and new vectors of attack lay around the corner. 


