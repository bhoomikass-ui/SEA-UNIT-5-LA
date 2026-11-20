# Open-Source Software Engineering

**Name:** Chethan Gowda KM
**USN:** N26UGLAT10496
**Case Study:** Open-Source Software Engineering

## 1. Introduction to Open-Source Software Engineering

Open-Source Software Engineering is a software development approach in which the source code of software is
publicly available for users and developers to view, modify, improve, and distribute according to its license.

It allows developers from different locations to work together and contribute to a common software project.

Platforms such as GitHub are widely used to host open-source projects, manage source code, track changes, and
collaborate with other developers.

In this case study, a group of developers is working on an open-source Library Management System hosted on GitHub.
A student identifies that the project does not have proper documentation explaining how users can issue and return books.

To solve this problem, the student can contribute by improving the project's documentation and submitting the changes
through a Pull Request on GitHub.

## 2. Importance of Contributing to Open-Source Projects

Contributing to open-source projects is important because it helps improve software quality and encourages
collaboration among developers.

The major advantages are:

1. **Knowledge Sharing:** Developers can learn from the source code and experience of other developers.
2. **Skill Development:** Students can improve their programming, debugging, documentation, and teamwork skills.
3. **Software Improvement:** Contributions help identify errors, add new features, and improve existing documentation.
4. **Community Collaboration:** Developers from different locations can work together on the same project.
5. **Real-World Experience:** Students gain practical experience using professional tools such as Git and GitHub.
6. **Transparency:** Publicly available source code allows developers to understand how the software works.

## 3. Steps to Fork a Repository

Forking is the process of creating a personal copy of another developer's repository under your own GitHub account.

The student can follow these steps:

### Step 1: Open GitHub

- Visit https://github.com.
- Log in using your GitHub account.
- Open the Library Management System repository.

### Step 2: Fork the Repository

- Click the **Fork** button available on the repository page.
- Select your GitHub account as the owner.
- Keep the repository name unchanged or use the required name.
- Click **Create fork**.

A copy of the original repository will now be available under the student's GitHub account.

### Step 3: Open the Forked Repository

- Navigate to your GitHub profile.
- Open the forked Library Management System repository.
- You can now make changes to your personal copy without directly modifying the original repository.

## 4. Creating or Modifying a Documentation File

After forking the repository, the student can improve the documentation by creating or modifying a Markdown file.

For example, the student can create a file named:

`Book_Issue_Return_Guide.md`

The documentation should explain the following procedures.

### A. Book Issuing Process

1. Open the Library Management System.
2. Log in using valid student credentials.
3. Navigate to the available books section.
4. Search for the required book.
5. Select the book and click the Issue Book option.
6. The system records the book issue details.
7. The student receives confirmation of successful book issuance.

### B. Book Returning Process

1. Log in to the Library Management System.
2. Navigate to the My Issued Books section.
3. Select the book that needs to be returned.
4. Click the Return Book option.
5. The system updates the book status.
6. The returned book becomes available for other students.

### C. Importance of Documentation

- Helps users understand how to operate the system.
- Reduces confusion while issuing and returning books.
- Makes the software easier to use.
- Helps new developers understand the project.
- Reduces the need for additional support.

## 5. Committing Changes and Submitting a Pull Request

After creating or modifying the documentation, the student must save the changes and submit them to the original repository.

### Step 1: Commit Changes

- Open the newly created documentation file.
- Review the content for spelling and formatting errors.
- Click **Commit changes**.
- Enter a suitable commit message.

Example commit message:

`Added book issue and return documentation`

- Select the option to commit directly to the fork's main branch.
- Confirm the commit.

A commit saves the changes and records them in the repository's history.

### Step 2: Create a Pull Request

A Pull Request (PR) is a request to merge changes from a forked repository into the original repository.

To create a Pull Request:

1. Open the student's forked repository.
2. Click **Contribute**.
3. Select **Open pull request**.
4. Verify that the base repository is the original Library Management System repository.
5. Verify that the head repository is the student's forked repository.
6. Enter a suitable title.

Example:

`Added Book Issue and Return Documentation`

7. Write a short description explaining the documentation changes.
8. Click **Create pull request**.

### Step 3: Review and Merge

- The project maintainer reviews the submitted Pull Request.
- The maintainer checks the documentation for correctness and completeness.
- If the changes are acceptable, the maintainer clicks **Merge pull request**.
- The contribution becomes part of the original repository.

Thus, the student successfully contributes to the open-source project.

## 6. Benefits of Collaborative Software Development

Collaborative software development allows multiple developers to work together on a common project.

The major benefits include:

1. **Improved Software Quality:** Multiple developers review and improve the code and documentation.
2. **Faster Development:** Different contributors can work on different tasks simultaneously.
3. **Knowledge Sharing:** Developers exchange ideas, techniques, and experiences.
4. **Error Detection:** Code reviews and testing help identify mistakes.
5. **Better Documentation:** Contributors can improve instructions and explanations for users.
6. **Community Support:** Developers can receive feedback and suggestions from other contributors.

## 7. GitHub Contribution Workflow Diagram

The following diagram represents the complete open-source contribution process using GitHub.

```text
       +---------------------------+
       | Original GitHub Repository|
       |   Library Management      |
       |         System            |
       +---------------------------+
                    |
                    v
       +---------------------------+
       |     Student Forks         |
       |       Repository          |
       +---------------------------+
                    |
                    v
       +---------------------------+
       |   Student Opens Forked    |
       |        Repository         |
       +---------------------------+
                    |
                    v
       +---------------------------+
       |  Creates/Modifies         |
       |  Documentation File       |
       +---------------------------+
                    |
                    v
       +---------------------------+
       |     Commit Changes        |
       |    to Student's Fork      |
       +---------------------------+
                    |
                    v
       +---------------------------+
       |    Create Pull Request    |
       |   to Original Repository  |
       +---------------------------+
                    |
                    v
       +---------------------------+
       |   Maintainer Reviews      |
       |       Changes             |
       +---------------------------+
                    |
                    v
             +-------------+
             |   Approved? |
             +-------------+
                /       \
              No         Yes
              |           |
              v           v
       +-------------+  +------------------+
       | Request     |  | Merge Pull       |
       | Changes     |  | Request          |
       +-------------+  +------------------+
              |           |
              v           v
       +-------------+  +------------------+
       | Student     |  | Contribution     |
       | Updates PR  |  | Added to Original|
       +-------------+  | Repository       |
              |         +------------------+
              +-----> Review Again
```

## 8. Conclusion

Open-Source Software Engineering encourages developers to work together to create, improve, and maintain
software applications.
In the given Library Management System case study, the student identifies missing documentation related
to issuing and returning books.

By following the GitHub contribution workflow, the student can fork the original repository, create or
modify a documentation file, commit the changes, and submit a Pull Request for review.

After approval by the project maintainer, the changes are merged into the original repository.

Thus, open-source contributions improve software documentation, encourage collaboration, develop
practical skills, and help create better software for the community.
