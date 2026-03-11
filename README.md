# PlanToggle
A simple Quaked Power Plan importer and Context Menu Switcher. Designed for swapping between 3 seprate power plans with ease and style. 

<img width="1920" height="512" alt="New Project" src="https://github.com/user-attachments/assets/83a8f626-7bb4-4c82-8445-792a810129a2" />

![GitHub Release Downloads](https://img.shields.io/github/downloads/QuakedK/PlanToggle/total) 

# Usage
Simply follow the quick and easy steps below ↓

1. Download [PlanToggle](https://github.com/QuakedK/PlanToggle/releases/download/Powerplanwindows/PlanToggle-V1.1.bat).
2. Right-click & run it as admin, everything else is automatic!

# Revert 

1. Open "Cmd" as admin and type the following.

**Remove Power Plan Context Menu:**
```
reg delete "HKCR\DesktopBackground\Shell\PowerPlan" /f
```

**Delete Power Plan Tools:**
```
rd /s /q "C:\Power Plans"
```
2. Click Windows Key + R and Paste ```powercfg.cpl``` into the run box.
3. Now you can remove the Quaked Power Plans by simply, clicking "Change Plan Settings" and clicking "Delete This Plan."
