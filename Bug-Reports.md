# Bug Reports

## BUG-01: Form submits with empty required fields
**Severity:** High 
**Priority:** High 

**Steps to Reproduce:**
1. Open the form inside iFrame
2. Leave required fields empty
3. Click Submit

**Expected Result:**
- Validation error message displayed

**Actual Result:**
- Form submitted successfully

---

## BUG-02: Unsupported file upload returns server error
**Severity:** High 
**Priority:** High 

**Steps to Reproduce:**
1. Upload unsupported file format

**Expected Result:**
- User-friendly validation message

**Actual Result:**
- Server returns 500 Internal Server Error
