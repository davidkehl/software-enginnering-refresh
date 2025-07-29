# **Week 1: Core Foundations & Setup**

**Goal:** Establish a solid base with tools, Git, JavaScript fundamentals, and daily DSA practice. By the end of this week, you will have:

- A fully configured dev environment
- Basic fluency in JavaScript & TypeScript
- Comfort with Git & GitHub workflows
- Completed your first coding exercises & mini project
- Solved beginner DSA problems on LeetCode

---

## **Daily Breakdown**

### **Day 1: Environment Setup & Git Basics**

**Topics:**

- Install VS Code, Node.js, Python, Git, Docker Desktop
- Sign up for GitHub, LeetCode, Vercel/Render
- Configure Git & SSH keys
- Learn CLI basics (cd, ls, mkdir, rm, mv, cp)

**Tasks:**

1. Push a simple JS and Python “Hello World” to a GitHub repo.
2. Create a folder structure for your learning journey (e.g., `/week1/dsa`, `/week1/projects`).

**Knowledge Checks (10):**

1. What is the difference between `git add` and `git commit`?
   - `git add` stages changes (prepares them for a commit). `git commit` records those staged changes in a local repo with a snapshot.
2. How do you generate and add an SSH key to GitHub?
   - Open terminal and run the following command `ssh-keygen -t ed25519 -C "your_email@example.com"`. Choose a location to save the key and optionally set a password. Then open the public key file and copy its entire context of the file. Log into GitHub and go to your profile and click SSH and GPG keys in the sidebar. In the title field provide a name and in the key field enter the key you copied earlier and click add SSH key
3. What command shows your current Git branches?
   - `git branch` will show your current Git branches
4. What does `rm -rf` do?
   - Recursively and forcefully removes files and directories without confirmation. Dangerous command as it deletes permanently
5. How do you list all files, including hidden ones, in Linux?
   - `ls -a`
6. Explain the difference between HTTPS and SSH Git URLs.
   - SSH uses key pairs for authentication and HTTPS uses usernames and passwords. SSH is considered to be more secure
7. What does `git log` display?
   - The history of committed changes in a Git repo.
8. How do you clone a repository to a specific folder?
   - `git clone <repo_url> <target_folder>`
9. What is the difference between `pwd` and `ls`?
   - `pwd` tells you the direct path of where the file is in a system, kind of like gps. `ls` lists all of the files and directories within the current directory,
     like looking around to see what is in the room you are in
10. Why should you commit often with clear messages?
    - It enhances code maintainability, facilitates collaboration, and allows for easier debugging.

**Mini Project:**

- Create a GitHub repo: `learning-week1`
- Add a `README.md` with your name and goals
- Include your Hello World JS and Python scripts

---

### **Day 2: JavaScript Fundamentals I**

**Topics:**

- Variables (`let`, `const`, `var`)
- Data types: string, number, boolean, null, undefined, object
- Basic operators and expressions
- Conditionals (`if`, `else`, `switch`)

**Tasks:**

- Write a script that asks for a user’s name and greets them.
- Write a function that returns whether a number is even or odd.

**DSA Practice (LeetCode – Easy):**

1. Two Sum
2. Palindrome Number

**Knowledge Checks (10):**

1. Difference between `let`, `const`, and `var`?
2. How does `==` differ from `===` in JavaScript?
3. What is `NaN` in JavaScript?
4. What does `typeof null` return and why?
5. Write a ternary operator example for checking if a number is positive.
6. What is the output of `console.log([] == false)` and why?
7. What happens if you declare a variable without `var`, `let`, or `const`?
8. What is the difference between primitive and reference types?
9. Explain truthy and falsy values in JavaScript.
10. Predict the output: `console.log(1 + '1')`

---

### **Day 3: JavaScript Fundamentals II**

**Topics:**

- Functions: declaration, expression, arrow functions
- Loops: `for`, `while`, `for…of`, `for…in`
- Arrays: `push`, `pop`, `map`, `filter`, `reduce`

**Tasks:**

- Implement a function to reverse a string.
- Implement a function to find the max number in an array.

**DSA Practice (LeetCode – Easy):**

1. Remove Duplicates from Sorted Array
2. Merge Two Sorted Lists

**Knowledge Checks (10):**

1. Write an arrow function to square a number.
2. Difference between `for…of` and `for…in` loops?
3. What does `array.map()` return?
4. Explain the difference between `array.filter()` and `array.forEach()`.
5. What is the purpose of `array.reduce()`?
6. How do you copy an array without referencing it?
7. Predict output: `[1,2,3].map(x => x * 2)`
8. Predict output: `[1,2,3].filter(x => x > 2)`
9. How do you check if a variable is an array?
10. Why is `const` often preferred for arrays even if they are mutated?

---

### **Day 4: TypeScript Basics & First Mini Project**

**Topics:**

- Adding TypeScript to a Node.js project
- Types: string, number, boolean, any, void
- Interfaces & type aliases
- Optional properties and function typing

**Tasks:**

1. Convert your JS functions from Day 2 & 3 into TypeScript.
2. Create an interface `Person` with `name` and `age`, and write a function to greet a person.

**DSA Practice (LeetCode – Easy):**

1. Best Time to Buy and Sell Stock
2. Valid Parentheses

**Mini Project:**

- **Personal Portfolio Skeleton**

  - Create a simple static page with HTML/CSS
  - Add a short bio and links to your GitHub
  - Deploy to Vercel

**Knowledge Checks (10):**

1. How do you define a variable with a type in TypeScript?
2. What is the difference between `interface` and `type`?
3. Can TypeScript infer types automatically?
4. What is the purpose of the `any` type?
5. How do you define a function that returns `void`?
6. What does `strict` mode in TypeScript enforce?
7. How do you compile TypeScript into JavaScript?
8. Explain the use of optional properties in interfaces.
9. How do you annotate array types in TypeScript?
10. Why is TypeScript preferred in large codebases?

---

### **Day 5: Review, Git Workflow, and DSA Focus**

**Topics:**

- Branching and merging in Git
- Pull requests and code review simulation
- Revisit all JavaScript & TypeScript concepts

**Tasks:**

1. Create a `week1-review` branch on your repo
2. Add all exercises and projects from this week
3. Open a pull request and self-review your code
4. Merge to `main`

**DSA Practice (LeetCode – Easy):**

1. Maximum Subarray
2. Valid Anagram

**Knowledge Checks (10):**

1. What command creates a new branch in Git?
2. How do you switch to another branch?
3. What is a pull request?
4. Difference between merge and rebase?
5. What is a code review and why is it important?
6. Explain how to resolve a merge conflict.
7. How can you undo your last commit?
8. What does `git status` show you?
9. Why should feature branches be used?
10. What does `git fetch` do?

---

### ✅ **End of Week 1 Deliverables**

1. GitHub repo with all exercises and a clean commit history
2. Personal portfolio skeleton deployed to Vercel
3. At least **10 LeetCode Easy problems solved**
4. Written answers to 50+ knowledge check questions

Next week, we’ll dive deeper into **JavaScript objects, DOM, ES6 modules, and more DSA**.
