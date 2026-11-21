# DevOps Practices and CI/CD Pipelines

**Name:** G S Koushik
**USN:** NB25CSE113
**Assigned Case Study:** Question 3 – DevOps Practices and CI/CD Pipelines

---

## 1. Introduction to DevOps

DevOps comes from two words: **Development (Dev)** and **Operations (Ops)**. It is a way of working in which the people who write the software and the people who run it on servers work as one team instead of separate groups.

DevOps is based on automation, shared responsibility, quick feedback and small, frequent releases.

**Example:** An online shopping company keeps updating its app with new features such as offers, wishlist and delivery tracking. Because testing and deployment are done by hand, every release is slow and mistakes reach customers. DevOps automates these steps so updates go out quickly and safely.

---

## 2. Meaning of Continuous Integration and Continuous Delivery/Deployment

**Continuous Integration (CI):**
- Every developer merges code into the main GitHub repository many times a day.
- Each merge automatically starts a build and runs the tests.
- Mistakes and merge conflicts are found within minutes, not weeks later.

**Continuous Delivery (CD):**
- Code that passes CI is automatically packaged and kept ready to release at any time.
- Sending it to the live server needs one manual approval (a button click).

**Continuous Deployment:**
- Code that passes every automated check goes to the live server automatically.
- There is no manual approval step.

---

## 3. CI/CD Pipeline Stages

The CI/CD pipeline has the following stages:

1. **Code:** Developers write the new feature (e.g. a "Buy Now" button) and push it to a shared repository on GitHub.
2. **Build:** A CI tool such as GitHub Actions or Jenkins compiles the code and creates a runnable package.
3. **Test:** Automated unit, integration and UI tests check the new build for bugs.
4. **Release:** The tested build is stored as a version-numbered package, ready to go live.
5. **Deploy:** The package is put on the production server so customers can use it.
6. **Monitor:** Tools watch errors, speed and failed payments, and send feedback to developers.

---

## 4. Explanation of Build, Test and Deployment

**Build:**
- Turns source code into a working application package.
- Runs on a clean server every time, so all builds are the same.
- Example: after adding a "Buy Now" button, a new version of the shopping app is built automatically.

**Test:**
- Runs test cases without a human tester.
- Checks important features: sign-up, search, add to cart, coupon discount and checkout.
- If any test fails, the pipeline stops and the developer is told immediately.

**Deployment:**
- Copies the tested version to the servers using scripts, not manual steps.
- Can update the app with no downtime and roll back to the old version if a problem appears.
- Example: customers see the new "Buy Now" button within minutes of the code being approved.

---

## 5. Three Benefits of Automation

1. **Speed:** Updates reach customers in minutes or hours instead of days, because no one waits for manual testing or deployment.
2. **Fewer Mistakes:** The same automated steps run every time, so forgotten steps and wrong settings are avoided, and bugs are caught before release.
3. **Reliability:** Small, frequent releases with quick rollback keep the shopping site stable and customers happy.

---

## 6. CI/CD Pipeline Diagram

```mermaid
flowchart TD
    A[CODE] --> B[BUILD]
    B --> C[TEST]
    C --> D[RELEASE]
    D --> E[DEPLOYMENT]
    E --> F[MONITOR]
    F --> G[Continuous Feedback]
    G --> A
```

**Pipeline Flow:**

```
        CODE
          |
          v
        BUILD
          |
          v
        TEST
          |
          v
       RELEASE
          |
          v
     DEPLOYMENT
          |
          v
       MONITOR
          |
          v
  Continuous Feedback
          |
          +----------> CODE
```

---

## Conclusion

Manual testing and deployment were slowing down the online shopping application and causing errors. Using DevOps and a CI/CD pipeline, every change is built, tested, released, deployed and monitored automatically. This gives the company faster updates, fewer errors and a more reliable application for its customers.
