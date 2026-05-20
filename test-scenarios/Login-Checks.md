# Login Page Testing Checks

## 1. Functional Checks

- Verify login with valid credentials.
- Verify login with correct email and incorrect password.
- Verify login with incorrect email and correct password.
- Verify login with invalid email and invalid password.
- Verify login with empty email and password fields.
- Verify login with empty email field.
- Verify login with empty password field.
- Verify successful login redirects user to dashboard/home page.
- Verify login with email case sensitivity.
- Verify login with special characters in input fields.
- Verify behavior after multiple failed login attempts.

---

## 2. Validation Checks

- Verify email field accepts only valid email format.
- Verify login with spaces before email.
- Verify login with spaces after email.
- Verify password below minimum allowed length.
- Verify password exceeding maximum allowed length.
- Verify login using only whitespace inputs.

---

## 3. UI Checks

- Verify placeholders are visible and correct.
- Verify input fields and login button alignment.
- Verify error messages display correctly.
- Verify password visibility (eye toggle) works properly.
- Verify button text and labels are visible.
- Verify UI remains aligned across screen sizes.

---

## 4. Compatibility Checks

- Verify login functionality on mobile devices.
- Verify login functionality on desktop devices.
- Verify login across different browsers.

---

## 5. Performance Checks

- Verify login behavior under slow internet conditions.
- Verify response on multiple rapid clicks of login button.
- Verify page load time is acceptable.

---

## 6. Security Checks

- Verify SQL injection attempts are blocked.
- Verify script injection (XSS) is prevented.
- Verify password is masked while typing.
- Verify sensitive information is not exposed in URL.
- Verify login API does not expose confidential data.

---

## 7. Session Checks

- Verify session persists after successful login and page refresh.
- Verify user is logged out properly.
- Verify browser back button behavior after logout.
- Verify session timeout handling.
- Verify user remains authenticated during active session.