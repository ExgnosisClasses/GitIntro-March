# Introduction to git

---

## Class Logistics

- Class is from 8 to noon
- Your session will be either March 12 or March 14
- Ten-minute break about half-way through the session

#### Materials

- All materials are in this repository and are available until April 14, 2024 at this link  [Materials Repository](https://github.com/ExgnosisClasses/GitIntro-March)

- All materials are published under a creative commons or equivalent license that permits free sharing.
- We will be using the book "Pro-git" which is available on the git website in online or downloadable form. A copy is included here for your convenience

#### Rod Davison (Instructor)

![](images/RodDavison.png)

I have been involved in the technology industry for over 50 years, starting in 1972

- Academia (theoretical mathematics, linguistics, cognitive science)
- Artificial Intelligence R&D and product development
- Software Development
- Data Analytics – Social Research
- Market Research
- Project Manager
- Research Director
- Quality and Testing
- Business Analysis
- Consulting and training

I have worked with government agencies in Canada and the US, defence contractor and aerospace firms, major financial institutions (many years on Wall Street NYC)

---

## Introductions

Please introduce yourself briefly, we don't have a lot of time for this part. Please tell me:

- Name you prefer to be called in class if different from the one listed on the class list
- Your area of professions focus (developer, SRE, tester, BA, hardware engineer, etc.)
- Any experience you have with git or similar products.
- Any specific objectives for the class or specific items you want to learn.


## About the class

Because we have a lot of topics to cover in a short period of time, there will be no hands-on labs during the class.

Instead, the class will consist of some presentation and a lot of demos to illustrate the main points.

There is a git lab document that essentially describes the demos so that you can try them out for yourself after the class.

---


## Topics

1. Repositories
2. Three stage commits
3. Git under the hood
4. Understanding blobs, trees, commits and heads
5. Using aliases
6. File Operations
7. Undoing operations
8. Working with branches
9. Merging branches
10. Stashing
11. Other topics as requested.


---

### Git internals

Previous SCV systems were often developed during the 1980s and 1990s when computing power and storage were limited. This means the delta approach was more efficient for storing large documents with small changes across many versions.

One of the problems with distributed repositories is maintaining the integrity of the commites. With a centralized repository, this is not a problem since items are checked out on a file by file basis.

If the entire repo is checked out, mutilated and then pushed back to the central repo, it has the potential to corrupt and destroy everything.

By using a certificate signing approach, the signature for each commit incorporates the signature of the previous commit so that there is a way to prevent random, spurious or malicious commits.

