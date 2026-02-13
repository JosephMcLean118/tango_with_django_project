# Chapter Tests

## ⚠️ Important

Tests for each chapter are tied to the specific commit where that chapter was completed.

You **must checkout to the correct commit** before running that chapter’s tests.  
If you do not, the tests will fail. This occurs because of the changes made to the
program as you go through each chapter

**For testing Chapters 5 and 6, please use the commit with message "fix" and not anything else**

---

## Running Tests for a Chapter

1. Find the commit associated with the chapter.
   ```bash
   git log --oneline
   
2. Checkout to that commit:

   ```bash
   git checkout <commit-hash>

3. Run the test for that chapter:
   ```bash
   python manage.py test rango.tests_chapterNUMBER
   
4. Return to main branch one test has been run
   ```bash
   git checkout main
   
