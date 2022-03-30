Questions to digest through and answer (please write corresponding Github command for this):

We have 2 big branch call master (to hold test features for test site) & production.

**Q1:** _(Ap & Ev) When we are creating new feature, what branch should we based on and why?_

**Answer:** When we create a new feature we should base it on the production branch. Because, a new feature of a product should begin from production. And assuming that the master branch has some features that have not been fixed yet, we can not checkout from that one.

**Q2:** _(Ap) If we have a feature branch that haven't been merged to production and that branch have bug, what course of action are you going to do with Git to before resolving the bug?_

**Answer:**

**Q3:** _(Ap & Ev) If someone accidentally merge a feature (feature/delete-user) onto production and have a list of commitId ended with (0492978, fc9348c, k101100), then another commit (a1fsas8) is added on top of the production branch. How do we remove that merged feature?_

**Answer:**
