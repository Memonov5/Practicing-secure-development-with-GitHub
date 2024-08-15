# secure.develop.task
Practicing secure development with GitHub
# Vulnerable Login Application Remediation

## Overview
This repository contains the remediation of common security vulnerabilities found in a simple web application. The following vulnerabilities have been addressed based on the OWASP Top Ten:

1. **Sensitive Data Exposure**: Removed the storage of username and password in `localStorage`.
2. **Cross-Site Scripting (XSS)**: Sanitized user input before inserting it into the DOM.
3. **Insecure Authentication**: Implemented a more secure authentication mechanism.
4. **Broken Access Control**: Added basic access control checks.

## Branches and Remediation Details

### `feature/remove-localstorage`
Removed the insecure storage of credentials in `localStorage`.

### `feature/sanitize-user-input`
Added a function to sanitize user input to prevent XSS attacks.

### `feature/secure-authentication`
Implemented a mock secure authentication mechanism.

### `feature/access-control`
Introduced basic access control checks to ensure only authenticated users can access certain content.

## How to Use
1. Clone the repository
2. Checkout the main branch
3. Open `index.html` in a browser to test the application
