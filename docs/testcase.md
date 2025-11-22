| Test Case ID | Test Case Description                                      | Acceptance Criteria |
|--------------|------------------------------------------------------------|---------------------|
| **TC-01**    | Login with valid email and valid password                  | User is successfully logged in and redirected to dashboard. |
| **TC-02**    | Login with invalid email format                            | Error: "Invalid email format". |
| **TC-03**    | Login with correct email but incorrect password            | Error: "Incorrect email or password". |
| **TC-04**    | Login with empty email field                               | Error: "Email is required". |
| **TC-05**    | Login with empty password field                            | Error: "Password is required". |
| **TC-06**    | Login with both fields empty                               | Error: "Email and password required". |
| **TC-07**    | Login with unregistered email                              | Error: "User not found". |
| **TC-08**    | Login with password less than minimum length               | Error: "Password must be at least 8 characters". *(Password policy: min 8 characters)* |
| **TC-09**    | Login with leading/trailing spaces in email                | Email is trimmed automatically; login succeeds if credentials are valid. |
