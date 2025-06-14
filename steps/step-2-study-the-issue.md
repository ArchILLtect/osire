## 🛠 Step 2: Study the Issue

Here’s your mission breakdown:

---

### 🧩 1. **Read the PR Description**

Check pull request to see:

- What the author said they changed
- Why those changes addressed the issue

---

### 🧪 2. **Compare File Changes**

Click on the “Files changed” tab in the PR and:

- Look at **which files** were modified
- Focus on **lines where the error exists**
- Try to spot a pattern.

### 🧠 3. **Identify the Fix Type**

Decide what kind of fix this was:

- [ ]  Bug fix?
- [ ]  Content correction?
- [ ]  Functional change?
- [ ]  Accessibility, formatting, other?

### 📚 4. **Summarize the Fix Logic**

Write a short summary like:

> “The fix involved standardizing article usage (‘a’ vs. ‘an’) based on whether the following word began with a vowel sound. A few inconsistencies were corrected in the curriculum markdown files.”
> 

### 🔍 5. **Locate One Example**

Pick one of the changes and answer:

- What was the original text?
- What is the new text?
- Why is the new one correct?

### 🏷️ 6. **Tag the Broken State** (if not done in Step 1.5)

Add a Git tag to mark this point in history before you apply any changes:

```bash
git tag broken-version-[issue#]
git push origin broken-version-[issue#]
```

This allows you to easily return to this exact moment later by running:

```bash
git checkout broken-version-[issue#]
```

> 📌 Why this helps: Tagging creates a permanent snapshot of the broken state—perfect for future reference, comparisons, or documenting your workflow clearly in the final project.
> 

### 🌿 7. **Create a Fresh "Pre-Fix” Branch**

To protect the original state of the code before you apply any changes, create a new branch from the latest version *before the fix was merged.*

```bash
git checkout -b reverse-fix-[issue#]
```

This gives you a clean workspace for your reverse-engineered fix, and ensures you can always return to the "unfixed" version if needed.

> 💡 Tip: Use a clear, descriptive branch name (e.g., fix-type-[issue#]) to keep your workflow tidy and easy to navigate.
> 

### 📄 8. Complete the Pre-Fix Log

[RE Issue Pre-Fix Log Template](/logs/re-issue-pre-fix-log-template.md)

---

**✅ Final Checklist:**

- [ ]  Analyze the fix
- [ ]  Summarize fix logic
- [ ]  Identify examples
- [ ]  Create a fresh **"reverse-fix" branch**
- [ ]  Tag the broken state
- [ ]  THEN proceed to Step 3 (apply fix)