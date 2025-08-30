    # Test Case: TC-004 — Verify login with blank username and valid password
    **Module:** Login (SauceDemo)  
    **Priority:** High  |  **Type:** Functional  |  **Status:** Pass  
    **Environment:** Windows 11, Chrome 139, https://www.saucedemo.com/

    ## Preconditions
    - User is on the Login page

    ## Steps
    1. Open https://www.saucedemo.com/
2. Leave **Username** blank
3. Enter **secret_sauce** into Password
4. Click **Login**

    ## Expected Result
    - Login fails; user remains on the Login page
- Error: **“Epic sadface: Username is required”**

    ## Actual Result
    - System displays: **“Epic sadface: Username is required”**

    ## Evidence
    ![Screenshot](../screenshots/login/TC-004/actual.png)
