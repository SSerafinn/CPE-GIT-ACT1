
# ACTIVITY 1 — HANDS-ON PRACTICE (LOCAL REPOSITORY)

---

## Activity Overview

In this activity, you will:

* Create a small multi-file website project
* Initialize a local Git repository
* Make logical and organized changes
* Create clear and descriptive commit messages
* Review your commit history
* Submit your finished project as a `.zip` file

You are NOT required to create a GitHub account.

---

## PART 1 — Project Setup

### Instructions

1. Create a new folder named:

```
website-activity
```

2. Inside this folder, initialize it as a Git repository.

3. Inside the project folder, create the following files:

```
index.html
about.html
styles.css
script.js
```

4. Create a folder named:

```
assets
```

---

## PART 2 — Create Initial Website Files

### index.html

Create the file with this content:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>My Site</title>
    <link rel="stylesheet" href="styles.css" />
    <script defer src="script.js"></script>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>Welcome to my site.</p>
    <a href="about.html">About</a>
  </body>
</html>
```

---

### about.html

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>About</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>About</h1>
    <p>This is the about page.</p>
    <a href="index.html">Home</a>
  </body>
</html>
```

---

### styles.css

```css
body { font-family: system-ui, sans-serif; margin: 2rem; }
h1 { font-size: 2rem; }
a { text-decoration: none; }
```

---

### script.js

```javascript
document.addEventListener('DOMContentLoaded', () => {
  console.log('Site loaded');
});
```

---

## PART 3 — First Commit

After creating all files:

* Stage all files
* Create your first commit

### Commit Message Format:

```
Initialize project with base HTML, CSS, and JS files
```

---

## PART 4 — Make Logical Changes (Separate Commits Required)

You must commit each change separately.

---

### Change 1 — Add Subtitle

In `index.html`, add this below `<h1>`:

```html
<h2>A tiny personal site</h2>
```

Commit Message:

```
Add subtitle to index page
```

---

### Change 2 — Add Navigation Bar

Add this navigation section to BOTH `index.html` and `about.html`:

```html
<nav>
  <a href="index.html">Home</a> ·
  <a href="about.html">About</a>
</nav>
```

Commit Message:

```
Add navigation links to both pages
```

---

### Change 3 — Add Hover Style

In `styles.css`, add:

```css
a:hover { text-decoration: underline; }
```

Commit Message:

```
Add hover underline style for links
```

---

### Change 4 — Add Console Greeting

In `script.js`, add:

```javascript
console.log('Hello from Activity 1');
```

Commit Message:

```
Add extra console greeting for activity testing
```

---

## PART 5 — Diff Practice

Add the following:

### In `index.html`

```html
<p>This site will grow as I learn Git.</p>
```
Run diff command to see file changes
```bash
git diff --staged
```
Commit separately with:

```
Add learning note to index page
```

---

### In `about.html`

```html
<p>I am practicing Git by making small, focused commits.</p>
```
Run diff command to see file changes
```bash
git diff --staged
```
Commit separately with:

```
Add practice note to about page
```
---

## PART 6 — Multi-Line Commit (Major Improvement)

Improve accessibility by adding a focus style in `styles.css`:

```css
a:focus {
  outline: 2px solid blue;
}
```

Create a multi-line descriptive commit message:

Title:

```
Improve link accessibility
```

Body:

```
Add visible focus outline for links.
Improves keyboard navigation and accessibility.
```

---

## PART 7 — Review History

Before submission:

* Check your commit history
* Ensure each logical change has its own commit
* Ensure commit messages are clear and meaningful

You should have **at least 7 commits**.

---

# FINAL SUBMISSION INSTRUCTIONS

Since you do not have GitHub accounts:

### Step 1 — Verify

Your project folder should look like this:

```
website-activity
 ├── .git
 ├── index.html
 ├── about.html
 ├── styles.css
 ├── script.js
 └── assets
```

---

### Step 2 — Compress

Right-click the folder:

```
website-activity
```

Select:

```
Send to → Compressed (zipped) folder
```

This will generate:

```
website-activity.zip
```

---

### Step 3 — Submit

Submit the `.zip` file


---

