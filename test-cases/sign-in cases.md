# Login Feature – Test Cases

## Preconditions
- User is on the login page  
- User account exists  

---

## TC-LOGIN-001  
**Objective:** Verify login with valid credentials.  

**Steps:**  
1. Navigate to login page  
2. Enter valid username  
3. Enter valid password  
4. Click Login button  

**Expected Result:**  
User is redirected to the homepage / dashboard.  

---

## TC-LOGIN-002  
**Objective:** Verify login with invalid password.  

**Steps:**  
1. Navigate to login page  
2. Enter valid username  
3. Enter invalid password  
4. Click Login button  

**Expected Result:**  
Error message displayed for invalid credentials.  

---

## TC-LOGIN-003  
**Objective:** Verify login with invalid username.  

**Steps:**  
1. Navigate to login page  
2. Enter invalid username  
3. Enter valid password  
4. Click Login button  

**Expected Result:**  
Error message displayed for invalid credentials.  

---

## TC-LOGIN-004  
**Objective:** Verify login with empty fields.  

**Steps:**  
1. Navigate to login page  
2. Leave username blank  
3. Leave password blank  
4. Click Login button  

**Expected Result:**  
Validation message displayed requesting required fields.  

---

## TC-LOGIN-005  
**Objective:** Verify login with valid username and empty password.  

**Steps:**  
1. Navigate to login page  
2. Enter valid username  
3. Leave password blank  
4. Click Login button  

**Expected Result:**  
Validation message displayed for missing password.  

---

## TC-LOGIN-006  
**Objective:** Verify login with empty username and valid password.  

**Steps:**  
1. Navigate to login page  
2. Leave username blank  
3. Enter valid password  
4. Click Login button  

**Expected Result:**  
Validation message displayed for missing username.  

---

## TC-LOGIN-007  
**Objective:** Verify login with invalid username and empty password.  

**Steps:**  
1. Navigate to login page  
2. Enter invalid username  
3. Leave password blank  
4. Click Login button  

**Expected Result:**  
Validation message displayed for missing fields and invalid credentials.  

---

## TC-LOGIN-008  
**Objective:** Verify login with empty username and invalid password.  

**Steps:**  
1. Navigate to login page  
2. Leave username blank  
3. Enter invalid password  
4. Click Login button  

**Expected Result:**  
Validation message displayed for missing username and invalid credentials.  

