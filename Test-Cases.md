# Test Cases

## TC-01: Drag & Drop Functionality
**Steps:**
1. Drag items from source area to drop zone
2. Click "Add Item"
3. Attempt to drag newly created item

**Expected Result:**
- All items should be draggable

**Actual Result:**
- Newly created item is not draggable

**Status:** Fail

---

## TC-02: Delayed Element Appearance
**Steps:**
1. Click "Show Delayed Element"
2. Wait 5 seconds

**Expected Result:**
- Element appears after delay

**Actual Result:**
- Element appears successfully

**Status:** Pass

---

## TC-03: AJAX Data Loading
**Steps:**
1. Click "Load AJAX Data"

**Expected Result:**
- Data loads dynamically without page refresh

**Actual Result:**
- Data loaded successfully

**Status:** Pass

---

## TC-04: Lazy Loading Images
**Steps:**
1. Scroll down the page

**Expected Result:**
- Images load when entering viewport

**Actual Result:**
- Images load correctly, minor scroll lag observed

**Status:** Pass with observations

---

## TC-05: File Upload & Processing
**Steps:**
1. Upload valid Excel file
2. Download processed file

**Expected Result:**
- File processed successfully with transformed data

**Actual Result:**
- File processed correctly

**Status:** Pass
