# 1.1.3 – Authentication and Password Attacks

## Lesson Objective(s):
- Define database as a collection of data organized for efficient organization and retrieval.
- Explain 3 password guessing attack methods that use database information.

## Guiding Question(s):
- How can databases be used in password guessing attacks?

### Lecture Notes
> From the course notes reviewed in class, take note on the material from this lesson as it relates to the Lesson Objectives and Guiding Question(s):

What  is a database? A database is any collection of data, or information, that is specifically organized for rapid search and retrieval by a computer. 
Dictionary brute force tries to access one account by trying lots of different passwords. Password spraying uses one password and tries it on lots of accounts. 

- A person claims to be a user but cannot authenticate.
- They are then asked to provide a different value like the answer to a security question.
- Note that does not get them into the account.

- Passphrase: A string of words provides more protection than a strong password BUT users are resistant to typing and it is not mobile device friendly.

- Most common method of safely storing passwords is to HASH the password. Hashing is intended as a one-way conversion. Once the algorithm is processed, the hashed password is stored by the system. Authentication happens when a hashed password is compared agaibst the orginial hash stored by the system - this will confirm that you have the correct original plaintext.

### Application / Personal Research / Summary
> In your own words, write a summary of this lesson and connect it to yourself and the real-world. If needbe, do a rapid research on the topic to help with you summary

...

### Vocabulary
> Include the vocabulary word(s) from this lesson with a defintion

Credentials: username + password pair used for authentication
Credential Stuffing: Trying usernames/password from a breach in order to gain access to user accounts.
