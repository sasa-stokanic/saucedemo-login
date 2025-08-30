# BUG-001 — Login shows only “Username is required” when both fields are blank
**Severity:** Major | **Priority:** High  
**Environment:** Windows 11, Chrome 139, https://www.saucedemo.com/

## Preconditions
- User is on the Login page

## Steps to Reproduce
1. Navigate to https://www.saucedemo.com/
2. Leave **Username** blank
3. Leave **Password** blank
4. Click **Login**

## Expected Result
- Error should say: **“Username and password are required”** (both fields reported)

## Actual Result
- Error shows only: **“Epic sadface: Username is required”**

## Attachments
![Actual](../screenshots/login/BUG-001/actual.png)

## Links
- Related task in Jira: SDQA-001 (primer)
