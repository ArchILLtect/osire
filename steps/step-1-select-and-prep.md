## 🛠 Step 1: Select and Prep a RE Target

Here’s your mission breakdown:

---

### 🧩1. **Browse and Select an Issue**

Use GitHub to find an issue that meets the following criteria:

- Belongs to a public open-source repository
- Has a corresponding Pull Request that resolves it
- Is closed and marked as resolved/merged
- Preferably tagged `good first issue`, `first timers only`, or similar
- Has educational or practical value (code readability, documentation, logic, accessibility, etc.)

Recommended filters:

- [GitHub “good first issue” search](https://github.com/search?q=label%3A%22good+first+issue%22+state%3Aopen+archived%3Afalse&type=issues)
- Popular beginner-friendly repos like `freeCodeCamp`, `firstcontributions`, `30-seconds`, etc.

---

### 📝 2. Record Key Information

Once selected, document the following:

| Field | Description |
| --- | --- |
| Repository | Name and link to the GitHub repository |
| Issue Title | Brief description and link |
| Issue Number | e.g., #12345 |
| PR Title | Description and link to the resolving pull request |
| PR Number | e.g., #12346 |
| Tags/Labels | Any labels that may indicate complexity, scope, or category |
| Resolution Status | Confirm that the PR was merged and issue closed |

### 🔍 3. **Establish Context**

Answer or document:

- What was the **problem or bug** described in the issue?
- Was the issue **text-only**, code-related, UI-based, logic-based, or structural?
- Did the issue include discussion, screenshots, test failures, or reviewer comments?
- Is this an issue with **educational value**, meaning it can teach something about the repo’s architecture, testing, accessibility, etc.?

### 🧠 4. **Initial Hypothesis**

Before reading the PR or fix:

- What do you **think** the fix will involve?
- What areas of the codebase do you **suspect** are affected?
- What would *you* try if you were solving this from scratch?

*(This part helps with later comparison between your initial assumptions and the final solution in Step 2.)*

### 📸 5. **Create a Snapshot**

Clone your own copy:

- Fork and clone the repo locally
// TODO Clean this up with code blocks
- Create a tag for original "up-to-date" state (Ex. git tag uptodate-state)
- Be sure to push tag for later use: git push origin uptodate-state
- 
> 💡 Tip: At this point, if you are using GitPod, you may get an error like:
remote: Permission to <username>/freeCodeCamp.git denied to <username>.
fatal: unable to access 'https://github.com/<username>/freeCodeCamp.git/': The requested URL returned error: 403
[Push Failing in GitPod? Fix Authentication Errors](./docs/gitpod-authentication-help.md)
> 

- Checkout a commit **before** the PR was merged (use `git log` and `git checkout`)
- Create a tag for this "broken" state "up-to-date" state (Ex git tag broken-version-54910)

```bash
git tag broken-version-[issue#]
```

- “Make note of any files or areas of the codebase that appear relevant”

### 📝6. Deliverable for Step 1

Create a clear write-up or Canvas section that includes:

- All recorded metadata (issue/PR, repo, labels, etc.)
- A brief summary of the issue
- Your hypothesis or expectations
- Any prep work done (cloning repo, setting up environment, etc.)

[RE Log for Step 1 Template](re-log-for-step-1-template.md)

**✅ Final Checklist:**

- [ ]  Browse and Select an Issue
- [ ]  Record Key Information
- [ ]  Establish Context
- [ ]  Initial Hypothesis
- [ ]  Create a Snapshot