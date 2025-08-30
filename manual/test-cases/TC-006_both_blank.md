    # Test Case: TC-006 — Verify login with both fields blank
    **Module:** Login (SauceDemo)  
    **Priority:** High  |  **Type:** Functional  |  **Status:** Pass  
    **Environment:** Windows 11, Chrome 139, https://www.saucedemo.com/

    ## Preconditions
    - User is on the Login page

    ## Steps
    1. Open https://www.saucedemo.com/
2. Leave **Username** blank
3. Leave **Password** blank
4. Click **Login**

    ## Expected Result
    - Login fails; user remains on the Login page
- Error should indicate both fields are required (e.g., **“Username and password are required”**)

    ## Actual Result
    - System displays: **“Epic sadface: Username is required”** (only username shown)

    ## Evidence
    ![Screenshot](../screenshots/login/TC-006/actual.png)
