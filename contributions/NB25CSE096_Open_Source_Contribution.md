# Open-Source Software Engineering
## Case Study: Improving Documentation in an Open-Source Library Management System

**Student Name:** Devansh Singh  
**USN:** NB25CSE096  
**Department:** Computer Science and Engineering  
**Subject:** Software Engineering  
**Assigned Case Study:** Question 4 – Open-Source Software Engineering  

---

## 1. Introduction

Open-source software is software whose source code is made available under a licence that permits people to use, inspect, modify and redistribute it according to the licence conditions. Such projects are commonly developed with the help of contributors who collaborate through platforms such as GitHub.

A contribution does not always have to involve writing new program code. Improving a user guide, correcting unclear instructions, reporting an issue or updating examples can also make an open-source project more useful. This case study focuses on improving the documentation of a Library Management System.

## 2. Understanding the Problem

The project considered in this case study is an open-source Library Management System. Its documentation does not clearly explain the process that a user should follow to issue a book or return it.

When instructions for these everyday operations are missing or difficult to understand, users may struggle to complete tasks correctly. They may also need to ask for help repeatedly. The project would therefore benefit from a short, well-organised guide describing the two processes.

**Problem statement:** The Library Management System needs clearer user documentation for book issue and book return operations.

## 3. Proposed Documentation Improvement

The proposed contribution is to add or improve a Markdown user-guide section that describes the book issue and return procedures in simple language. The instructions should be checked against the actual application before they are treated as final documentation.

### 3.1 Book Issue Procedure

A typical book issue process may include the following steps:

1. Open the Library Management System and sign in with an authorised account.
2. Navigate to the book catalogue or search section.
3. Find the required book using its title, author or category.
4. Check whether the selected book is available for issue.
5. Select the book and submit the issue request according to the library's rules.
6. Review the confirmation details, including the issue date and due date, if displayed.

### 3.2 Book Return Procedure

A typical return process may include these steps:

1. Sign in to the Library Management System.
2. Open the section that displays currently issued books or borrowing records.
3. Locate the book that needs to be returned.
4. Follow the system's return instructions and hand over the physical book if required by the library.
5. Check that the borrowing record has been updated to show the return.
6. Review any overdue information or fine details displayed by the system.

> **Verification note:** The steps above are a general documentation example, not confirmed instructions for a particular software interface. Before contributing them to a real project, inspect that project's screens, terminology, permissions and library rules, and adjust the guide to match the actual behaviour.

## 4. How the Contribution Is Made Through GitHub

GitHub supports collaborative development by allowing contributors to propose changes to a project without directly modifying the original repository. The contribution process for this case study follows these stages:

1. **Find the project repository:** Open the original Library Management System repository and read its README and contribution guidelines.
2. **Fork the repository:** Create a personal copy of the project under the contributor's GitHub account.
3. **Prepare the documentation:** In the fork, create or update the appropriate Markdown file with the verified book issue and return instructions.
4. **Commit the update:** Save the file as a commit with a meaningful message, for example, `Document book issue and return procedures`.
5. **Open a Pull Request:** Propose the commit from the personal fork to the original repository's target branch. Explain the purpose of the documentation change in the PR description.
6. **Respond to review:** The maintainer may review the proposed change and request corrections. Update the contribution when necessary and wait for the maintainer to decide whether to merge it.

### 4.1 GitHub Contribution Flow

```text
Original project repository
          |
          v
   Fork the repository
          |
          v
 Create or update Markdown guide
          |
          v
    Commit the changes
          |
          v
      Open Pull Request
          |
          v
 Maintainer review and feedback
          |
          v
    Merge when accepted
```

## 5. Why Open-Source Contributions Matter

Documentation is an important part of a software project because it helps people understand and use the application. A clear guide for issuing and returning books can:

- **Make the software easier to use:** Users can follow a consistent set of instructions.
- **Reduce confusion:** Clear steps can prevent common misunderstandings about borrowing and returning books.
- **Share project knowledge:** Important usage information is available to users instead of remaining with a few individuals.
- **Support collaboration:** Contributors and maintainers can discuss improvements and review proposed changes.
- **Help new contributors learn:** Students gain practical experience with repositories, commits, branches and pull requests.

## 6. Benefits of Collaborative Software Development

1. **Different perspectives:** Contributors may notice unclear areas or missing information that others have overlooked.
2. **Review and quality checks:** A maintainer or another contributor can identify errors and suggest clearer wording.
3. **Shared workload:** Different people can work on separate documentation sections, issues or features.
4. **Traceable changes:** Commits and pull requests record what was proposed and provide a history of the work.
5. **Community-driven improvement:** Users and developers can help maintain the project over time.

## 7. Challenges and Good Practices

A new contributor may initially find an unfamiliar repository difficult to understand. The project may also have its own documentation format, naming conventions or contribution rules. If multiple people edit the same file, their changes may conflict. A pull request may also receive review comments that require revision.

These challenges can be handled by reading the README and contribution guidelines first, checking existing documentation for style, keeping the change focused, using a clear commit message and explaining the purpose of the pull request. The contributor should verify every instruction against the actual application and respond constructively to review feedback.

## 8. Conclusion

Improving documentation is a useful form of open-source contribution because it helps people understand and operate software more confidently. In this Library Management System case study, the proposed improvement is a user guide for issuing and returning books. By preparing a Markdown file, making the change in a fork, committing it and submitting a pull request, a student can participate in a practical collaborative development workflow. The contribution can be accepted after the project maintainer reviews it.

## 9. References

1. Software Engineering assignment instructions supplied for the Unit 5 Open-Source Contribution Project, Question 4.
2. GitHub Documentation – About pull requests: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests
