# 🧪 Test Cases - AI Study Planner

This document lists different user scenarios tested in the workflow.

---

## ✅ Test Case 1: Study Progress

**Input:**
I studied ACN for 1 hour

**Expected Behavior:**

* Extract subject = ACN
* Extract hours = 1
* Compare with planned hours
* Ask reason if less than planned

**Result:**
✔ Passed

---

## ✅ Test Case 2: Completed Task

**Input:**
I completed DBMS

**Expected Behavior:**

* Mark subject as completed
* Update status in Google Sheets
* Send confirmation message

**Result:**
✔ Passed

---

## ✅ Test Case 3: Reason Handling

**Input:**
Reason for ACN: I was tired

**Expected Behavior:**

* Extract reason
* Update remark column
* Keep actual hours
* Send acknowledgment

**Result:**
✔ Passed

---

## ⚠️ Test Case 4: Partial Study

**Input:**
I studied DBMS for 1 hour (planned = 2)

**Expected Behavior:**

* Detect mismatch
* Ask reason
* Update after response

**Result:**
✔ Passed

---

## ❌ Test Case 5: Unknown Subject

**Input:**
I studied XYZ for 2 hours

**Expected Behavior:**

* Check if subject exists
* Handle gracefully

**Result:**
⚠️ Needs Improvement

---

## 🚀 Future Scenarios

* Handle typos (e.g., "DBM", "ACNN")
* Multiple subjects in one message
* Time formats ("2 hrs", "two hours")
* Daily summary generation
