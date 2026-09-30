# starter-box

This is the tutorial repository to help you begin your journey in the Computer Science Club.

### Step-by-Step Instructions

> **Note:** Whenever you see `<your-username>`, replace it with your actual GitHub username (without the angle brackets).

1. **Fork & Clone**  
   Fork this repository to your personal GitHub account using the **Fork** button at the top of the page. Then, clone your fork locally:
   git clone [https://github.com/](https://github.com/)<your-username>/starter-box.git
 
2. **Create a Branch**: This is so you don't work directly on the main branch.
git checkout -b add-profile-<your-username>

3. **Duplicate the Template**: Use these commands in your command line.
Linux and macOS: cp members/_template.md members/<your-username>.md
Windows Powershell: Copy-Item members\_template.md members\<your-username>.md

4. **Fill it out, commit, and push**: Follow the following commands:
git add members/<your-username>.md
git commit -m "add: <your-username> profile card"
git push origin add-profile-<username>
