# Login Page Mock

## ASCII Wireframe

```
┌─────────────────────────────────────┐
│                                     │
│         Stock Analyzer              │
│                                     │
│    ┌───────────────────────────┐   │
│    │                           │   │
│    │    LOGIN TO YOUR ACCOUNT  │   │
│    │                           │   │
│    ├───────────────────────────┤   │
│    │                           │   │
│    │  Email                    │   │
│    │  ┌─────────────────────┐  │   │
│    │  │ user@example.com    │  │   │
│    │  └─────────────────────┘  │   │
│    │                           │   │
│    │  Password                 │   │
│    │  ┌─────────────────────┐  │   │
│    │  │ ••••••••••••••      │  │   │
│    │  └─────────────────────┘  │   │
│    │                           │   │
│    │  ┌─────────────────────┐  │   │
│    │  │    SIGN IN          │  │   │
│    │  └─────────────────────┘  │   │
│    │                           │   │
│    │  Don't have an account?   │   │
│    │  [Sign Up]                │   │
│    │                           │   │
│    └───────────────────────────┘   │
│                                     │
└─────────────────────────────────────┘
```

## Interaction Flow
1. User opens the login page
2. User enters email in the email field
3. User enters password in the password field
4. User clicks "Sign In" button
5. System validates credentials
6. On success: Redirect to dashboard/home page
7. On failure: Display error message and allow retry
8. User can click "Sign Up" to go to registration page

## Key Elements
- Email input field with validation
- Password input field with masked display
- Sign In submit button
- Sign Up link for new users
- Responsive design for mobile and desktop
