# SoftwareSecurityPortfolio

**Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?**
The client, Artemis Finacial, wanted to apply the most current and effective software security to modernize their operations and guarentee success of their custom software. They wanted to add a file verification step to the web application to secure communications.

**What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?**
I found that using the JSSE Cipher Suite with the standard name of TLS_EDCHE_RSA_WITH_AES_128_CBC_SHA to be best suited for transaction but not just finanical transactions. It is important to securely code so that you can ensure that your users and your companies information is kept away from eavedroppers and others who may intend to do your company or yourself harm. If a company does not have solid software security and they put valuable information out online or through their application they could not only be endangering their wellbeing but their companies financial future as well. So, the value software security adds to a company is invaluable and should be taken seriously.

**What about the process of working through the vulnerability assessment did you find challenging or helpful?**
The part I found most challenging was determining what was a true vulenrability and what was only a vulenrability due to a coding error. I had to recheck code to make sure it was doing what it was intended to do and in the correct manner so that I could ensure that when I ran a dependency check for vulnerabilities that the vulnerabilities that were found were due to a conflict within the code itself and not because of a error made by me.

**How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?**
The first thing I did was determine whether I had accomplished what the client wanted from me. Secondly, I would want to make sure that not only did the security measures work but were affective as well. In the future I would need to be better at testing the program code and making sure that any concerned area was throughly addressed and vetted to ensure I had taken all neccessary steps to secure the system.

**How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?**
Once I refactored the code I simple re-ran the dependency check to see if I had introduced any new vulernabilities.

**What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?**
When I employed the use of Java Keytool. I could see that understanding what each command is and how to use it would be extremely helpful for my future.

**Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?**
Knowing I was able to find an appropriate cipher for the client, Artemis Financial, that dealt with transactions securely I would say that obtaining a checksum value with the use of the SHA-256 cipher would what I chose to showcase to a future employer.
