# 📘 Markdown Guide for QA Documentation

This file explains how Markdown works and how to use it to write test documentation in a clear and organized way.

---

## 📑 Table of Contents
- [Headings](#headings)
- [Bold and Italic](#bold-and-italic)
- [Lists](#lists)
- [Links](#links)
- [Images](#images)
- [Blockquotes](#blockquotes)
- [Tables](#tables)
- [Checklists](#checklists)
- [Emojis](#emojis)
- [Code Blocks](#code-blocks)
- [Internal Links](#internal-links)
- [Tips for QA Documentation](#tips-for-qa-documentation)

---

## 🧩 Headings

Use `#` to create titles. More `#` means smaller size.

```markdown
# Title 1
## Title 2
### Title 3
#### Title 4
```
**Bold text** or *Italic text*

---

List

- Step one
- Step two
- Step three

---

Order List
1. Open the browser
2. Go to the login page
3. Enter credentials

---

Links and Internal Links:

[Visit GitHub](https://github.com)

[Go to Headings](#headings)

---

Images:

![Login Page](https://example.com/login.png)

---

BLockquotes

> This test must be executed before release.

---

Tables

| Test Case ID | Description         | Status  |
|--------------|---------------------|---------|
| TC_LOGIN_001 | Login with valid data | Passed  |
| TC_LOGIN_002 | Login with wrong password | Failed |

---

Check List

- [x] Test login with valid credentials
- [ ] Test login with empty fields
- [ ] Test login with wrong password

---

Code Blocks

1. Open browser
2. Go to https://example.com
3. Enter username and password
4. Click "Login"

---

