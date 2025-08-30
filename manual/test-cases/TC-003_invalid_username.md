    # Test Case: TC-003 — Verify login with invalid username and valid password
    **Module:** Login (SauceDemo)  
    **Priority:** High  |  **Type:** Functional  |  **Status:** Pass  
    **Environment:** Windows 11, Chrome 139, https://www.saucedemo.com/

    ## Preconditions
    - User is on the Login page

    ## Steps
    1. Open https://www.saucedemo.com/
2. Enter an **invalid** username (e.g., `wronguser`)
3. Enter **secret_sauce** into Password
4. Click **Login**

    ## Expected Result
    - Login fails; user remains on the Login page
- Error: **“Epic sadface: Username and password do not match any user in this service”**

    ## Actual Result
    - System displays: **“Epic sadface: Username and password do not match any user in this service”**

    ## Evidence
    ![Screenshot](../screenshots/login/TC-003/actual.png)
