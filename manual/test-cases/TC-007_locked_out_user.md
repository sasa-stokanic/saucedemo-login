    # Test Case: TC-007 — Verify login with locked out user
    **Module:** Login (SauceDemo)  
    **Priority:** High  |  **Type:** Functional  |  **Status:** Pass  
    **Environment:** Windows 11, Chrome 139, https://www.saucedemo.com/

    ## Preconditions
    - User is on the Login page

    ## Steps
    1. Open https://www.saucedemo.com/
2. Enter **locked_out_user** into Username
3. Enter **secret_sauce** into Password
4. Click **Login**

    ## Expected Result
    - Login fails; user remains on the Login page
- Error: **“Epic sadface: Sorry, this user has been locked out.”**

    ## Actual Result
    - System displays: **“Epic sadface: Sorry, this user has been locked out.”**

    ## Evidence
    ![Screenshot](../screenshots/login/TC-007/actual.png)
