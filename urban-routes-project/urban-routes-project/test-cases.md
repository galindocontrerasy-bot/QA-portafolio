# Test Cases – Urban Routes

## 📌 Test Case Structure

Each test case includes:
- Test Case ID
- Title
- Preconditions
- Steps
- Expected Result
- Actual Result
- Status

---

## 🧪 Sample Test Cases

### TC-UR-01
**Title:** Verify valid address input  
**Precondition:** User is on main booking page  
**Steps:**
1. Enter a valid pickup address
2. Enter a valid destination
3. Click “Search”

**Expected Result:** System displays available routes  
**Actual Result:** System displays available routes  
**Status:** Passed

---

### TC-UR-02
**Title:** Verify invalid input in destination field  
**Precondition:** User is on main booking page  
**Steps:**
1. Enter special characters in destination field
2. Click “Search”

**Expected Result:** Validation error message appears  
**Actual Result:** System allows invalid characters  
**Status:** Failed
