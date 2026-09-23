# Windows Activation Guide: Microsoft Activation Scripts (MAS)

A detailed guide for activating Windows using the **Microsoft Activation Scripts (MAS)** project on GitHub. This covers both the recommended PowerShell method and the traditional offline script method.

> **Note:** MAS is an open-source project. Using it bypasses official licensing. Home users rarely face consequences, but businesses are advised against it due to audit and legal risks.

---

## 🚀 Method 1: PowerShell (Recommended)

The most straightforward method. Works on **Windows 8.1, 10, and 11**. No manual file downloads required.

### Step 1: Open PowerShell

- Click the **Start Menu**
- Type `PowerShell` and open it
- Running as Administrator is *not* required for this method

### Step 2: Execute the Command

Copy and paste the following into PowerShell, then press **Enter**:

```powershell
irm https://get.activated.win | iex