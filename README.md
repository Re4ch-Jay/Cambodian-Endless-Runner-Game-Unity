---

# **Unity Project Setup**

This repository contains a Unity project. Follow the steps below to set up the project on your local machine.

---

## **Prerequisites**

Before you begin, ensure you have the following installed:
- [Unity Hub](https://unity.com/download) and the required Unity version (specified in `ProjectSettings/ProjectVersion.txt`).
- [Git](https://git-scm.com/downloads) installed and configured.
- [Git LFS](https://git-lfs.github.com/) installed for handling large files.

---

## **Getting Started**

### **1. Clone the Repository**
Clone the repository to your local machine:
```bash
git clone https://github.com/username/repository.git
cd repository
```

---

### **2. Install Git LFS**
If you haven’t installed Git LFS, install it first:
```bash
git lfs install
```
Then, pull large files tracked by Git LFS:
```bash
git lfs pull
```

---

### **3. Open the Project in Unity**
1. Launch Unity Hub.
2. Click **Add**, then navigate to the cloned repository's folder.
3. Select the folder and open the project.

---

## **Repository Structure**

```
.
├── Assets/                # Game assets, scripts, and resources
├── Packages/              # Unity packages used in the project
├── ProjectSettings/       # Unity project settings
└── README.md              # Project setup instructions
```

---

## **Contribution Guidelines**

To contribute to this project:
1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request.

---

## **Common Issues**

### **1. Missing Assets or Prefabs**
Ensure you've pulled all large files with Git LFS:
```bash
git lfs pull
```

### **2. Unity Version Mismatch**
If you encounter compatibility issues, ensure you have the Unity version specified in `ProjectSettings/ProjectVersion.txt`.

---

## **License**
This project is licensed under the [MIT License](LICENSE).

---

