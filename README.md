# Firebase_Guide
## Firebase Authentication
- Most apps want to know the user's identity.
- Knowing the user's identity allows the app to securely store data in the cloud and provide a consistent personalized experience to the user.
- Firebase Authentication provides backend services, easy-to-use SDKs, and ready-made UI libraries to authenticate users in your app.
- It supports popular authentication methods such as password, phone number, Google, Facebook, and Twitter.
- It integrates with other Firebase services and uses standards like OAuth 2.0 and OpenID Connect, making it easy to integrate with custom backends.
- By default, authenticated users can read and write data in Realtime Database and Cloud Storage.
  - Administrators can control users' access permissions through Firebase Database Rules and Storage Security Rules.

### Key Features

#### Using FirebaseUI Auth

1. Set up sign-in methods
2. Customize the Sign-in UI
3. Use FirebaseUI to handle the sign-in flow

#### Using the Firebase Authentication SDK

1. Set up sign-in methods
2. Implement the sign-in UI flow
3. Provide the user's credentials to the Authentication SDK

### Firebase Authentication Console Guide

<img width="1300" alt="auth3" src="https://github.com/Ghostlun/Firebase_Guide/assets/40644178/c105ad7f-0629-4132-9e2a-218fa6b73dec">

#### User Management


- **Identifier**: This column shows the user's email or phone number used for authentication.
- **UID**: The Unique Identifier (UID) is a unique code assigned to each user. This is used internally to identify users across various Firebase services.
- **Provider**: This shows the authentication provider used by the user, such as Email/Password, Google, Facebook, Twitter, etc.
- **Created At**: This column indicates the date and time when the user account was created.
- **Signed In At**: This column shows the most recent date and time when the user signed into the app.

### Actions

- **Edit User**: You can edit user details, including email, password, and profile information.
- **Delete User**: This option allows you to permanently remove a user from your Firebase project.
- **Send Email Verification**: For email/password sign-in methods, you can send a verification email to the user.
- **Reset Password**: You can send a password reset email to the user.
- **Add User**: Allows you to manually add a new user to your project, specifying their email, password, and other optional profile information.

These features make it easier to manage your application's users and ensure secure authentication and authorization processes.

