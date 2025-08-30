    # Test Case: TC-001 — Verify successful login with valid credentials
    **Module:** Login (SauceDemo)  
    **Priority:** High  |  **Type:** Functional  |  **Status:** Pass  
    **Environment:** Windows 11, Chrome 139, https://www.saucedemo.com/

    ## Preconditions
    - User is on the Login page

    ## Steps
    1. Open https://www.saucedemo.com/
2. Enter **standard_user** into Username
3. Enter **secret_sauce** into Password
4. Click **Login**

    ## Expected Result
    - User is redirected to `/inventory.html`
- The Inventory page is visible (title **Products**)

    ## Actual Result
    - User lands on `/inventory.html`
- Inventory page loaded successfully

    ## Evidence
    ![Screenshot](../screenshots/login/TC-001/step4.png)
