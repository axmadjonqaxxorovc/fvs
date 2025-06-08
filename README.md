# Folder View System (FVS)

**Folder View System (FVS)** is a Python application that lets you interactively view and display the structure of directories and their files in a clean and visually appealing format. It includes features to enhance the experience, such as displaying folder structures, file names, and additional useful arguments for project information.


*If the version is outdated, some functions may not work properly. Please use the*

```
fvs -h
```
*command to check which functions are supported!*


---

## Features

- 📂 **Displays folder structures** and 📄 **files** in a neat, hierarchical format.
- 🌍 **Shows the current working directory**.
- 🧑‍💻 **Supports useful arguments**, such as `--help` for usage instructions.
- 💬 **Displays creator information** with the `--creator` argument.
- 🔄 **Provides an interactive terminal experience**.

---


## Prerequisites

Before you begin, ensure you have the following:

- **Python 3.6** or higher.
- **Git** (for cloning the repository).

To check if Git is installed, run:

```bash
git --version
```

If installed, you can install it using the following steps for your platform:

For Linux (Debian/Ubuntu):
```
sudo apt update
sudo apt install git
```
For macOS (using Homebrew):
```
brew install git
```
For Windows, download and install Git from git-scm.com.

Getting Started
Follow these instructions to set up the project on your local machine.

*Step 1: Clone the Repository*
Open your terminal and navigate to the folder where you want to clone the project (for example, ~/Desktop/Projects):
```
cd ~/Desktop
```
Clone the repository using Git:
```
git clone https://github.com/axmadjonqaxxorovc/fvs.git
```
Navigate to the cloned project directory:
```
cd fvs
```
Install fvs:
```
sudo dpkg -i fvs.deb
```
or
```
sudo dpkg -i fvs_updated_version.deb
```
     

**Adding fvs.exe to System PATH:**

*Move the fvs.exe file to a permanent directory:*

Example:
```C:\Programs\fvs\```

**Add the folder to your system PATH:**

- *Press Win + S and search for "Environment Variables".*

- *Open Environment Variables, and click Edit on the Path variable.*

- *Click New and paste the path where fvs.exe is located (for example, C:\Programs\fvs\).*

- *Click OK, OK, and Close all windows.*

**Important Note:**
*Avoid placing fvs.exe in the root folder (e.g., C:\fvs.exe).
Adding a file directly to the root folder (C:\) and then including that folder in the PATH can cause security and operational issues. It's recommended to place the file in a subdirectory like C:\Programs\fvs\ to ensure smooth operation and avoid potential risks.*

**Open a terminal and simply type:**

```fvs -p <path>```

*Your tool will now run from anywhere! 🎉*
