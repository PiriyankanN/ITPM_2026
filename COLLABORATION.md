# 🤝 Team Collaboration Guide - ITPM 2026

Welcome to the Student Living Assistant repository! To ensure smooth collaboration among our 4 team members, please follow this branching and contribution guide.

## 👥 Responsibilities & Branches

| Member | Responsibility | Dedicated Branch |
| :--- | :--- | :--- |
| **Nitharshika** | Room & Accommodation System | `Nitharshika/Rooms` |
| **Ashwini** | Inquiry & Support System | `Ashwini/Inquiries` |
| **Piriyankan** | Food & Dining Services | `Piriyankan/Food` |
| **Mubin** | Transit & Bus Scheduling | `Mubin/Bus` |

## 🚀 Workflow Instructions

### 1. Getting Started
Before starting your work, ensure you are on your specific branch:
```bash
# Switch to your branch
git checkout <YourName>/<Feature>

# Example for Nitharshika
git checkout Nitharshika/Rooms
```

### 2. Saving Your Work
Commit your changes frequently with descriptive messages:
```bash
git add .
git commit -m "feat: added room filtering logic"
git push origin <YourName>/<Feature>
```

### 3. Syncing with the Main Project
If someone else has merged their work into `main`, you should sync your branch:
```bash
# Get the latest main branch
git checkout main
git pull origin main

# Switch back to your branch and merge main into it
git checkout <YourName>/<Feature>
git merge main
```

### 4. Merging into Main
When your feature is complete and tested:
1. Push your branch to GitHub.
2. Create a **Pull Request (PR)** on GitHub from your branch to `main`.
3. Wait for the team to review before merging.

## ⚠️ Important Rules
- **NEVER** push directly to the `main` branch.
- **NEVER** push your `.env` or `node_modules`. (The `.gitignore` should handle this automatically).
- **Run `npm install`** if you see new dependencies added in a pull.

Happy Coding! 🚀
