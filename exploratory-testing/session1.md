# Exploratory Testing Session 1

## Application
SauceDemo (https://www.saucedemo.com/)

## Date
2026-06-21

## Tester Goal (Charter)
Explore login functionality and identify usability or functional issues.

---

## Areas Tested
- Login page UI
- Username and password validation
- Login error handling
- Button behavior

---

## Test Approach
- Enter valid credentials
- Enter invalid credentials
- Leave fields empty
- Try special characters
- Rapid clicking Login button

---

## Findings

### 1. No clear validation when fields are empty
- When username and password are empty and login is clicked, error message is generic.
- Could be improved to show field-specific validation.

---

### 2. Login error message consistency
- Error message appears, but styling is not very noticeable.
- UX improvement needed for better visibility.

---

### 3. Button behavior under fast clicks
- Multiple rapid clicks on Login button do not show debouncing.
- System should prevent multiple submissions.

---

## Risks
- Poor UX may confuse users during login failure
- No input validation guidance increases user errors

---

## Conclusion
Login module works functionally but has UX and validation improvements needed.
