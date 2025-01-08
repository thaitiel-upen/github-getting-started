# **HTML Exercise: Hello World**
---
## Exercise 1: Learn the basics of Github and git

### **Objective**
- Learn the basics of Git and GitHub.
- Create and modify a simple HTML file.
- Personalize a "Hello World" webpage with your name.
---

#### **Instructions**

1. **Clone Your Repository**
   - Open your terminal or Git Bash and clone the repository:
     ```bash
     git clone <your-repo-url>
     cd <your-repo-folder>
     ```

2. **Locate the `index.html` File**
   - In the repository, you’ll find a file named `index.html`.

3. **Edit the `index.html` File**
   - Open `index.html` in a code editor (e.g., VS Code) or directly on GitHub.
   - Modify the file to include the following structure:
     ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>Hello World</title>
     </head>
     <body>
         <h1>Hello, World!</h1>
         <h1>My name is [Your Name]</h1>
     </body>
     </html>
     ```
   - Replace `[Your Name]` with your actual name.

4. **Save Your Changes**
   - Save the `index.html` file after editing.

5. **Stage and Commit Your Changes**
   - Stage the changes to the HTML file:
     ```bash
     git add index.html
     ```
   - Commit the changes with a descriptive message:
     ```bash
     git commit -m "Added Hello World with my name"
     ```

6. **Push Your Changes to GitHub**
   - Push your changes to the repository:
     ```bash
     git push origin main
     ```

7. **Verify Your Changes**
   - Go to your GitHub repository in the browser.
   - Ensure the `index.html` file has been updated with your personalized message.

8. **Optional: Open the File in a Browser**
   - Open the `index.html` file in a browser to see your "Hello World" page.

---
# Exercise 2: Collaborate on a Shared Project

### Goal
Learn how to work with branches, create pull requests, and merge changes to collaborate using Git and GitHub.

---

## Instructions

### Step 1: Create a New Branch
1. Open your terminal and navigate to the cloned repository.
2. Create a new branch named `feature/add-hobbies`:
```bash
   git checkout -b feature/add-hobbies
```
### Step 2: Edit the HTML File
1. Open the index.html file in your code editor.
2. Add the following section below the "About Me" section:
   
```
<h2>My Hobbies</h2>
<ul>
    <li>Reading</li>
    <li>Coding</li>
    <li>Gaming</li>
</ul>
```
###  Step 3: Commit the Changes
1. Save the file and return to your terminal.
2. Stage and commit the changes:

```bash
git add index.html
git commit -m "Added hobbies section"
```
###  Step 4: Push the branch

```bash
git push -u origin feature/add-hobbies
```

###  Step 5: Create a Pull Request
1. Go to the GitHub repository in your browser.
2. You’ll see an option to create a pull request for the branch you just pushed. Click Compare & pull request.
3. Add a title (e.g., "Added hobbies section") and a brief description of the changes.
4. Click Create pull request.

This will be the submission step for feedback from teacher or one of your peers, wait for feedback and approval of the pull request.
