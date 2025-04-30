# RE Issue Pre-Fix Log (#54910)

## 📌 Project: freeCodeCamp

## 📅 Started: April 18, 2025

---

## ✅ Fix Summary:

- **Issue Title:** Inconsistent uses of "a" and "an"
- **Issue #:** [#54910](https://github.com/freeCodeCamp/freeCodeCamp/issues/54910)
- **PR #:** [#54915](https://github.com/freeCodeCamp/freeCodeCamp/pull/54915)
- **Labels:** `first timers only`, `scope: curriculum`, `platform: learn`
- **Fixed by:** `VP-66`
- **Date Closed:** May 22, 2024

---

## 🔍 Description of Issue:

The curriculum had inconsistent article usage — switching between "a src attribute" and "an src attribute." The inconsistency occurred across multiple challenge descriptions.

---

## 🧠 Understanding the Fix:

All instances of "an src" were changed to "a src" for consistency. This follows the logic that "src" is pronounced "source" (not "ess-are-see"), so it takes "a".

---

## 🧩 Files Affected:

- [`5dc24073f86c76b9248c6ebb.md`](https://github.com/freeCodeCamp/freeCodeCamp/blob/main/curriculum/challenges/english/14-responsive-web-design-22/learn-html-by-building-a-cat-photo-app/5dc24073f86c76b9248c6ebb.md)
- [`5dfa30b9eaeac3f48c63004d.md`](https://github.com/freeCodeCamp/freeCodeCamp/blob/main/curriculum/challenges/english/14-responsive-web-design-22/learn-html-by-building-a-cat-photo-app/5dfa30b9eaeac3f48c63004d.md)
- [`5dfb6250eaeca3f48c6300b2.md`](https://github.com/freeCodeCamp/freeCodeCamp/blob/main/curriculum/challenges/english/14-responsive-web-design-22/learn-html-by-building-a-cat-photo-app/5dfb6250eaeca3f48c6300b2.md)
- [`5efada803cbd2bbdab94e332.md`](https://github.com/freeCodeCamp/freeCodeCamp/blob/main/curriculum/challenges/english/14-responsive-web-design-22/learn-html-by-building-a-cat-photo-app/5efada803cbd2bbdab94e332.md)
- [`655dc43318591b975cdfe2d8.md`](https://github.com/freeCodeCamp/freeCodeCamp/blob/main/curriculum/challenges/english/15-javascript-algorithms-and-data-structures-22/learn-basic-string-and-array-methods-by-building-a-music-player/655dc43318591b975cdfe2d8.md)
- [`65606d0666e118ba86162be.md`](https://github.com/freeCodeCamp/freeCodeCamp/blob/main/curriculum/challenges/english/15-javascript-algorithms-and-data-structures-22/learn-basic-string-and-array-methods-by-building-a-music-player/65606d0666e118ba86162be.md)
- [`65606ed6ea2baca053327e9b.md`](https://github.com/freeCodeCamp/freeCodeCamp/blob/main/curriculum/challenges/english/15-javascript-algorithms-and-data-structures-22/learn-basic-string-and-array-methods-by-building-a-music-player/65606ed6ea2baca053327e9b.md)

---

## 🔍 *Fix Prediction:*

*Your best guess at what the fix will be and why.*

---

## 💡 What I Learned:

- Even tiny wording inconsistencies matter in professional documentation
- How to locate and trace markdown challenge files
- How small but focused PRs work in large open-source projects like fCC
- I can now use this fix as a reference for making my own contributions!