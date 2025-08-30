    # Test Case: TC-005 — Verify login with valid username and blank password
    **Module:** Login (SauceDemo)  
    **Priority:** High  |  **Type:** Functional  |  **Status:** Pass  
    **Environment:** Windows 11, Chrome 139, https://www.saucedemo.com/

    ## Preconditions
    - User is on the Login page

    ## Steps
    1. Open https://www.saucedemo.com/
2. Enter **standard_user** into Username
3. Leave **Password** blank
4. Click **Login**

    ## Expected Result
    - Login fails; user remains on the Login page
- Error: **“Epic sadface: Password is required”**

    ## Actual Result
    - System displays: **“Epic sadface: Password is required”**

    ## Evidence
    ![Screenshot](../screenshots/login/TC-005/actual.png)
