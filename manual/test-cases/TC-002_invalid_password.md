    # Test Case: TC-002 — Verify login with valid username and invalid password
    **Module:** Login (SauceDemo)  
    **Priority:** High  |  **Type:** Functional  |  **Status:** Pass  
    **Environment:** Windows 11, Chrome 139, https://www.saucedemo.com/

    ## Preconditions
    - User is on the Login page

    ## Steps
    1. Open https://www.saucedemo.com/
2. Enter **standard_user** into Username
3. Enter an **invalid** password (e.g., `wrongpass`)
4. Click **Login**

    ## Expected Result
    - Login fails; user remains on the Login page
- Error: **“Epic sadface: Username and password do not match any user in this service”**

    ## Actual Result
    - System displays: **“Epic sadface: Username and password do not match any user in this service”**

    ## Evidence
    ![Screenshot](../screenshots/login/TC-002/actual.png)
