# **HTML Exercise: Hello World**

### **Objective**
- Learn the basics of Git and GitHub.
- Create and modify a simple HTML file.
- Personalize a "Hello World" webpage with your name.

---

### **Instructions**

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
