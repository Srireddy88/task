# TASK 4: Version-Controlled DevOps Project with Git and Github
Building a version-controlled DevOps project using Git and GitHub.

## Tools Used
- Git
- GitHub


## Branches
![Screenshot 2025-04-12 181108](https://github.com/user-attachments/assets/0019e76d-f0da-4f19-b831-cb40c560e1c2)


## Commands Used

```bash
mkdir devops-project
cd devops-project
git init
```
# Add GitHub remote
git remote add origin https://github.com/Srireddy88/TASK-4.git
# Add app.py to main
```bash
echo "print('HELLO WORLD!!')" > app.py
git add .
git commit -m "python file"
git push origin main
```

# Create dev branch
```bash
git checkout -b dev
git push origin dev
```
# Create feature/new branch from dev
```bash
git checkout -b feature/new
git push origin feature/new
```
# Add tasks.md in feature/new
```bash
git add tasks.md
git commit -m "initial commit"
git push origin feature/new
```
![Screenshot 2025-04-12 181644](https://github.com/user-attachments/assets/8aee5c1e-bd1e-448b-b594-f4b363cc3887)

![Screenshot 2025-04-12 181440](https://github.com/user-attachments/assets/3b16bf9c-6181-4dbe-b2ca-ae0c56d80447)

# Pull request from feature/new to main and merge via GitHub
![Screenshot 2025-04-12 181302](https://github.com/user-attachments/assets/7b5e6eb5-545b-4129-907e-9ba099caca6a)
![Screenshot 2025-04-12 181355](https://github.com/user-attachments/assets/d084e67e-676f-4c52-ad54-2d354e92feb2)


# Add .gitignore to main
Added .gitignore directly in the repository.
![Screenshot 2025-04-12 181139](https://github.com/user-attachments/assets/db69402c-3881-4192-b904-d351ca572169)


