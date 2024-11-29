# GitHub Tutorial Project

Welcome to the **GitHub Tutorial Project**! This repository is designed to teach participants how to use Git and GitHub by contributing to a collaborative project. Follow the tasks below to practice essential Git and GitHub concepts.

## Repository Structure

```plaintext
├── .gitignore
├── contributors/
│   ├── contributors-list.md
│   ├── username.md
├── doc/
│   ├── git_commands.md
│   ├── git_keywords.md
└── README.md
```

### File Descriptions

1. **`.gitignore`**: Specifies files and directories to ignore in the repository.
2. **`contributors/`**: Directory containing:
   - `contributors-list.md`: A file listing the names and GitHub usernames of all participants.
   - `your-github-username.md`: A file for each participant to describe themselves briefly.
3. **`doc/`**: Directory containing:
   - `git_commands.md`: A file for participants to collaboratively document Git commands.
   - `git_keywords.md`: A file for participants to define and explain Git-related concepts.
4. **`README.md`**: This guide to help participants understand the repository and tasks.

---

## Tasks for Participants

### Task 1: Clone This Repository
1. Clone this repository to your local machine:
   ```bash
   git clone git@github.com:BHLucca-tutorials/git_tutorial
   cd github-tutorial
   ```

### Task 2: Add Your Details to `contributors/contributors-list.md`
- Open `contributors/contributors-list.md`.
- Add a new line with your name and GitHub username in the following format:
  ```plaintext
  - Your Name @your-github-username
  ```
- Example:
  ```plaintext
  - Jane Doe @JDoe-1z21
  ```

---

### Task 3: Create Your Personal `username.md` File
1. Navigate to the `contributors/` directory.
2. Create a new file named `your-github-username.md`.
3. Add a brief description of yourself, including:
   - Your name
   - Your GitHub username
   - A fun fact or your favorite programming language
   - Whatever you like to share with other participants
4. Example JDoe-1z21.md:
   ```markdown
   # Jane Doe

   ## Overview
   Say hi! 

   ## Other custom section
   **Fun Facts:**
   - I love *coffee* and coding in Python on weekdays!
   - I love *tea* and writing Poems on weekends!
   

   Looking forward to collaborating with everyone!

   ## Contact
   @JDoe-1z21.md
	
   ```

---
### Taks 4:
So far you directly pushed on main branch, it is time to start doing things in the right way!
Start a new branch for your next push!
   ```bash
   $ git branch whathevernemyoulike
   $ git checkout whatevernameyoulike
   ```

After your next commits create a pull requests for pushing your changes to main branch!

---
### Task 5: Document Git Commands in `doc/git_commands.md`
1. Open `doc/git_commands.md`.
2. Add at least one Git command, its usage, and an example in the following format:
   ```markdown
   This commands move changes from the working-tree to staging area ready for commit.
   - git add -A add *all* files (new, modified, deleted)
   - git add -u *updates* only modified and deleted (it does not include new files)
   - git add .  add all the content from the current dir and subdirs recursevly (does not include deleted files)


   ```bash example:
   $git add <filename>
   ```
   ```

3. You can document additional commands if you'd like!

---

### Task 5: Define Git Keywords in `doc/git_keywords.md`
1. Open `doc/git_keywords.md`.
2. Add at least one Git-related keyword or concept, its definition, and a brief explanation. Use this format:
   ```markdown
   ## BRANCH
   A branch refers to the splitting of a repository into parallel lines of development.
   Each branch allows for independent changes and commits, enabling developers to work on new features, bug fixes, or experiments without affecting the main codebase.
   ```
3. You can add as many keywords or concepts as you wish to enrich the file.

---

## Additional Notes
- **Code of Conduct**: Please be respectful and collaborative while contributing.
- **Support**: If you have any questions or issues, feel free to open an issue in the repository.

---

Happy learning and contributing! 🚀
