#  Running the Executables (Mac & Windows Guide)

## 📘 Reverse Coding — Tutorial Video (Must Watch Before Contest)

I’ve created a short tutorial video explaining **Reverse Coding**, how **Round 1** works**,** and what kind of questions to expect.

👉 **Please watch it before the contest** — it will give you a clear understanding of the format and help you perform better.

### 🎥 Tutorial Videos
- **Reverse Coding & Round 1 Overview:**  
  https://youtu.be/9GlFC4NvSfY

- **MacOS Tutorial for Binary Files:**  
  https://youtu.be/7Sp6-f7Jw4Y


This contest contains several **reverse-coding problems**, each with a provided executable simulator.
Use these executables to test your own inputs and understand the hidden logic behind each problem.

Below are the instructions to run the files on **macOS** and **Windows**.

---

# **Windows Instructions**

Windows executables are provided as `.exe` files.

### **To run:**

Simply double-click the file, or run from Command Prompt:

```cmd
./filename.exe
```

Example:

```cmd
./rotator.exe
```

✔ No extra permissions needed.

---

# **macOS Instructions (VERY IMPORTANT)**

macOS blocks downloaded executables by default (shows “Permission Denied” or “Developer cannot be verified”).
Follow these steps to fix it **for the entire folder** containing the executables.

### **1. Open Terminal inside the folder**

Right-click → **New Terminal at Folder**
(or `cd` into the folder manually)

###  **2. Give execute permissions to all files**

```bash
chmod -R +x ./
```

### **3. Remove the quarantine flag from the whole folder**

```bash
xattr -dr com.apple.quarantine ./
```

This is the step that tells macOS:
**“These files are safe; allow them to run.”**
**Summary of the code**
```
chmod -R +x ./
xattr -dr com.apple.quarantine ./
```

### **4. Run any executable**

Example:

```bash
./rotator
```

---

# ❗ If macOS still blocks the file

Go to:

**System Settings → Privacy & Security**
Scroll down and click **“Allow Anyway”** for the blocked app.

Then run it again.

---

#  You're Ready!

You can now run all simulator executables for:

* Rotating Cipher Printer
* Saitama Power Predictor
* Hidden Numbers
* Soul of the Number
* Jump Energy Calculator
* And other contest tasks

Use them to test custom inputs, observe behavior, and decode the hidden rules.

Just tell me!
