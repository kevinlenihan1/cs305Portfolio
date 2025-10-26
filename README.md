# cs305Portfolio
Module 8's portfolio assignment

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial services company that helps clients manage investments and personal financial data. Their main goal was to modernize their systems and move toward cloud services without exposing sensitive customer information. They needed secure communications, protection against cyber threats, and strong encryption methods to ensure their data remained confidential and tamper-proof.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I was able to clearly identify security weaknesses across the application and explain their severity. My manual review covered multiple Java files, highlighting missing validation, hardcoded credentials, and unprotected endpoints. Coding securely is vital because it prevents data leaks, system compromises, and loss of customer trust. All of which are especially damaging for a financial company. By applying secure coding principles early, Artemis Financial can maintain both compliance and customer confidence.

Which part of the vulnerability assessment was challenging or helpful to you?

The hardest part was analyzing dependencies and understanding where vulnerabilities could exist in third-party libraries. Even though I couldn’t run an automated dependency scan at the time, studying how OWASP Dependency-Check works helped me understand how important it is to automate security checks. The most helpful part was manually going through each file, it forced me to understand how input flows through the application and how poor validation can lead to attacks like XSS or SQL injection.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?


How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After reviewing and refactoring the code, I checked that the application could still build and run without errors. I verified that endpoints responded correctly while limiting access to sensitive paths. Reviewing the mitigation plan helped confirm that security improvements didn’t interfere with functionality and that new vulnerabilities weren’t introduced in the process.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?


Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show this report as proof that I can analyze code for vulnerabilities, interpret risk severity, and design mitigation plans that align with real-world frameworks like OWASP. It demonstrates a full workflow  from identifying problems to proposing secure, functional solutions, which is a key skill for any developer or security engineer.
