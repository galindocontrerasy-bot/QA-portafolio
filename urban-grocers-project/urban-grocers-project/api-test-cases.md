# API Test Cases – Urban Grocers

## TC-UG-01

**Title:** Verify successful product retrieval  
**Endpoint:** GET /products  
**Precondition:** API server running  

**Steps:**
1. Send GET request to /products endpoint
2. Observe status code
3. Validate response body structure

**Expected Result:**
- Status code 200
- JSON response with product list

**Actual Result:** Status code 200, valid JSON returned  
**Status:** Passed

---

## TC-UG-02

**Title:** Verify error when product ID does not exist  
**Endpoint:** GET /products/{invalid_id}

**Steps:**
1. Send GET request with invalid ID
2. Observe status code

**Expected Result:**
- Status code 404
- Error message returned

**Actual Result:** Status code 500  
**Status:** Failed
