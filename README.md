# 📘 Esoft Practicals System

### 🔹 Project Name: `Esoft-Practicals-System`

---

## 📝 Description

**Esoft Practicals System** is a desktop application currently being used at **Esoft Piliyandala**.  
It allows students to view, manage, and print their PDF practical files easily.  
The system simplifies academic file access and supports additional features for an improved learning experience.

---

## 🛠️ Built With

- **Programming Language**: C#
- **Platform**: Windows Desktop Application
- **Framework**: .NET Framework
- **Third-party Tools**: Guna UI2 , Adobe Acrobat
---

## 💾 Installation Guide

Follow these steps to install the system:

1. **Download** the folder named `Esoft Practical`.
2. Open the `Esoft Practical` folder.
3. Go inside the `Debug` folder located within it.
4. Double-click on the file named `Esoft Practical.msi`.
5. On the welcome screen, click **Next**.
6. Browse and select the location where you want to install the software.
7. Click **Next** to proceed.
8. Confirm the installation by clicking **Next** again.
9. Wait until the installation completes.
10. Once installed, you can open the system using the **desktop shortcut**.

> ✅ Make sure you have a supported version of Windows and the required .NET Framework installed.

![Desktop Shortcut](https://drive.google.com/uc?export=view&id=1BrRzJPi_LNFMi0IAtSNqiAJt4asskWX3)

---

## ✅ Features

- 🔐 **Create Account** – New users can create their own account easily.
- 🔓 **Login to Account** – Secure login functionality for registered users.
- 📄 **Practicals Tab** – View and access PDF files for each practical lesson.
- 📘 **Tutorials Tab** – Access relevant PDF tutorials categorized by lesson.
- 🗂️ **RAR Tab** – Lock and store completed practicals for organized reference and safety.

---

## 🔐 Create Account

![Create Account Page](https://drive.google.com/uc?export=view&id=1Fb8tCMPEGa-4pvYRY2bKENpcK7WgMRIV)

The **Create Account** feature allows users to register and automatically creates a folder structure for their practicals.

### 🧾 Input Fields

- **First Name**
- **Last Name**
- **Registration Number** – Must be 8 digits.
- **Batch Number** – Must be 3 digits.
- **Course Category** – A dropdown (ComboBox) with options:
  - `CIT`
  - `DITEC`
  - `Di(EXT)`

### 🔘 Buttons

- **Create Account**  
  - Once clicked, a folder is automatically created in the following structure:

    ```
    D:\Practicals\[Course Category]\[Course Category] [Batch Number]\[Registration Number] [First Name] [Last Name]\

    ```

  - Based on the selected course, a predefined set of lesson folders and subfolders are generated inside the user folder.

- **Back to Login**  
  - Navigates the user back to the login screen.

---

### 📂 Folder Structure Generation

The folder structure varies depending on the selected **Course Category**:

#### If `DITEC` is selected:
- All 10 lessons and their related subfolders will be created.

#### If `CIT` is selected:
- Only lessons 1 to 6 will be created.

#### If `Di(EXT)` is selected:
- Only lessons 7 to 10 will be created.

---

## 🗂️ Example Folder Tree (DITEC)

```plaintext
D:\Practicals\DITEC\DITEC 001\12345678 Methum Minsuka\
├── 1. Information Technology
│   └── 1.1
│       ├── 1.1.1
│       └── 1.1.2
├── 2. Enhancing Productivity With MS Office
│   ├── 2.1
│   │   ├── 2.1.1
│   │   └── 2.1.2
│   ├── 2.2
│   │   ├── 2.2.1
│   │   ├── 2.2.2
│   │   ├── 2.2.3
│   │   └── 2.2.4
│   ├── 2.3
│   │   ├── 2.3.1
│   │   ├── 2.3.2
│   │   ├── 2.3.3
│   │   └── 2.3.4
│   ├── 2.4
│   │   ├── 2.4.1
│   │   └── 2.4.2
│   ├── 2.5
│   │   ├── 2.5.1
│   │   ├── 2.5.2
│   │   └── 2.5.3
│   ├── 2.6
│   │   ├── 2.6.1
│   │   ├── 2.6.2
│   │   └── 2.6.3
│   ├── 2.7
│   │   ├── 2.7.1
│   │   ├── 2.7.2
│   │   ├── 2.7.3
│   │   └── 2.7.4
├── 3. Computer Hardware
├── 4. Network Technology
├── 5. Internet, Email and Web Designing
│   ├── 5.1
│   │   ├── 5.1.1
│   │   ├── 5.1.2
│   │   ├── 5.1.3
│   │   ├── 5.1.4
│   │   ├── 5.1.5
│   │   └── 5.1.6
│   ├── 5.2
│   ├── 5.3
├── 6. Graphics and Multimedia
│   ├── 6.1
│   ├── 6.2
│   └── 6.3
├── 7. Software Engineering
│   └── 7.1
├── 8. Python Programming
│   ├── 8.1
│   ├── 8.2
│   └── 8.3
├── 9. Database Concepts
│   ├── 9.1
│   │   ├── 9.1.1
│   │   └── 9.1.2
│   └── 9.2
│       ├── 9.2.1
│       └── 9.2.2
└── 10. Programming With C#
    ├── 10.1
    ├── 10.2
    ├── 10.3
    ├── 10.4
    └── 10.5
```

---

## 🔓 Login Page

![Login Page](https://drive.google.com/uc?export=view&id=1K8pfkw4IEhfxLYm-jCP2HJZXnop16f37)

The Login page includes:

- `First Name`
- `Last Name`
- `Registration Number`
- `Batch Number`
- `Course Category` (CIT / DITEC / Di(EXT)) - Combo Box
- **Login** button
- **Create Account** button
### 🔸 Login Flow:
- When you click **Login**, the system checks if a folder matching your details exists in:
  
  If it exists  
  ➝ You are successfully logged in.  
  
  If not  
  ➝ Login fails.

---

## 📄 Practicals & 📘 Tutorials Tabs

![Practicals & Tutorials Tabs](https://drive.google.com/uc?export=view&id=1xO8ZTjgIDtle_BWHwvaKsuvkjI4P0skD)

Once you're logged in, you will see Three main tabs:

- **Practicals Tab**
- **Tutorials Tab**
- **RAR Tab**

### 🔸 Interface Elements: Practicals Tab & Tutorials Tab

- 🏷️ **Label**  
  Displays your **Name**, **Registration Number**, and **Course Info**.  
  When clicked, it **automatically copies the full folder path** of your account to the clipboard.

- 🔘 **Log Out Button**  
  Returns you to the **Login Page** immediately upon clicking.

- 👁️ **View Button**  
  Based on the selected **Course Category**, a list of practical or tutorial lessons is shown.  
  Each lesson has a **View** button to open its related **PDF file**.

> ✅ This structure helps users quickly navigate to and access required learning materials with ease.

---

## 🗂️ RAR Tab

![RAR Tab](https://drive.google.com/uc?export=view&id=1xoipHAJnSr4cvEhn4gy7xKfzH28S462k)

The **RAR Tab** allows students to lock and archive their completed practical work using WinRAR.  
Buttons are dynamically displayed based on the selected **Course Category**.


### 🔸 How it Works:

For example, if you selected the course `DITEC`, you may see buttons like:

- `1. Information Technology`
- `1.1`
- `1.1.1`
- `1.1.2`

Each button corresponds to a folder created for that specific practical lesson.

### 🗂️ RAR Button Behavior:

- When you click a button:
  - The system locates the relevant folder within your user directory.
  - The folder is then compressed and password-protected using **WinRAR**.
  - This ensures your completed practicals are **locked** and **preserved** from modification.

> 🛡️ Helps maintain academic integrity by securing finished work before submission.

---
