# Bug Reports – Urban Grocers API

## BUG-UG-01

**Title:** API returns 500 instead of 404 for non-existent product ID  
**Environment:** Postman / Local Environment  

**Steps to Reproduce:**
1. Send GET request to /products/99999
2. Observe response

**Expected Result:** Status code 404 with error message  
**Actual Result:** Status code 500 Internal Server Error  

**Severity:** Critical  
**Priority:** High
