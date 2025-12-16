# Web Application Pentest Report – Improper Session Termination

## Description
The application continues to allow access to previously viewed user data even after the user has logged out.  
For example, sensitive pages remain accessible when navigating back in the browser, indicating that the logout process does not fully terminate the user session.

---

## Impact
An unauthorized third party may gain access to sensitive user data despite the user intentionally ending the session.  
This can lead to privacy violations, especially when the application is accessed from shared or public devices.

---

## Recommendation
After logout, the application should fully invalidate the user session and ensure that access to sensitive data requires re-authentication.  
Protected pages should not be accessible after logout, including through browser navigation or page refresh.
