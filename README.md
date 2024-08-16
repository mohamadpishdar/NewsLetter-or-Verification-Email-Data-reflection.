# NewsLetter-or-Verification-Email-Data-reflection.


Some implementations of the newsletter or email confirmation service receive information from the user when completing the registration form and repeat it (or part of it) in the email sent to the users. This issue can be exploited by cyber attackers in such a way that they fill out the registration form or newsletter with the email of the victim user in a targeted manner. In this process, reflective parts are filled with malicious text and URL addresses so that the user receives it as an email and thinks that it is from a valid organization sending the email.

In general, injecting unexpected information to abuse or deceive users can be negative for a system and cause abuse of users' trust in the system. In this type of vulnerability, the information in the registration form or newsletter registration, such as name and surname, is repeated in the email officially sent by the system. This information must not transmit anything that could compromise the security of the victim user. Things like malicious URL addresses with the purpose of directing the user to malicious sites are among these things.

Attack Scenario: 1- a Man in the middle attacker can request a friend to sign up in the vulnerable System. 2- The target user will sign up, and the attacker will stop his request in the network. 3- the attacker will sign up with his email and inject the malicious link and text. 4. Target users will receive a verification email that includes injected text and URL. The target user checks the sender, and everything is correct (the vulnerable official email system sends the email). 5. the user will click on the malicious link. 6- in the malicious link, the credential can be stolen.


In this page, I will add some public bug bounties or Bug reports related to this matter
