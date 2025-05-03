## Assignment 10: "I Screwed Up, Now What?" Recovery 🚑

### ✅ Task Summary:
- Created a branch named `experiment`.
- Added three commits to `todo.txt`: `"Try this"`, `"Nope"`, and `"Maybe"`.
- Rebased `experiment` onto `main` for a cleaner history.
- Then decided to reset back to the first commit (`Try this`).
- Force pushed the reset branch to GitHub.

---

### 📝 Rebased `git log --oneline` (Before Reset):

9a1b7c8 Maybe
9e2062c Nope
eb89599 Try this
22e73c9 (origin/main, main) Resolve merge conflict: Were both the best, ugh
... (other older commits)

---

### 📦 Final Branch State on GitHub (After Reset):

eb89599 (HEAD -> experiment) Try this

---

### 🧠 Real-World Vibes:
This simulates experimenting in a feature branch, cleaning up with a rebase, but then deciding it’s not worth it — so we just kept the first good idea. Classic dev move. 😅

Once you’ve updated your README.md with the above, just run:

git add README.md
git commit -m "Add Assignment 10 summary and deliverables"
git push origin experiment
