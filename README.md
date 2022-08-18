# Test Case Samples 

Below are some Test Case samples I wrote while studying. [Here you can access my Test Case template](https://docs.google.com/spreadsheets/d/1PXMJ9zN5OLlEiRT2pXTzPxeUIP524yQnogCH3p-wWCQ/edit#gid=0)

---

**Test Objective**: Test the login by using correct credentials.

**Steps to reproduce:**
1. Go to www.linkedin.com
2. Add correct username & password
3. Observe if user can login

**Expected Result**: User should be able to login

**Test Data**: User: test & Pass: 123

---

**Test Objective**: Test the login by using incorrect credentials.

**Steps to reproduce:**
1. Go to www.linkedin.com
2. Add incorrect username & password
3. Observe if user can login

**Expected Result**: User should not be able to login

**Test Data**: User: test & Pass: 1234

---

**Test Objective**: Test "Remember me" functionality by checking the box.

**Steps to reproduce:**
1. Go to www.linkedin.com
2. Add correct username & password and check "Remember me" box
3. Observe if user can login
4. After login, exit your browser, and come back again to www.linkedin.com and check if you are still logged in 

**Expected Result**: Credentials should be saved and user won't have to enter them again 

**Test Data**: User: test & Pass: 123

---


**Test Objective**: Test if search functionality shows the results.

**Steps to reproduce:**
1. Go to emag.ro
2. Type a product in the search bar
3. Observe if results for your product are shown

  **Expected Result**: A new page showing products that you searched for will open up

**Test Data**: Televizor

---

**Test Objective**: Test if search functionality still works with non-existent products on our website.

**Steps to reproduce:**
1. Go to emag.ro
2. Type a product that doesn't exist in our offer in the search bar
3. Observe if search still works and some other products are shown

**Expected Result**: When you type a product in the search box that doesn't exist in our offer, search should still work and other products suggestions should show up  instead

**Test Data**: Nurofen
