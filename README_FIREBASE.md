Firebase deploy instructions

1. Install Firebase CLI (if not installed):

```bash
npm install -g firebase-tools
```

2. Log in and select project:

```bash
firebase login
firebase use --add business-management-fc675
```

3. Deploy Firestore rules:

```bash
firebase deploy --only firestore:rules
```

4. (Optional) Deploy hosting if you configure it:

```bash
firebase deploy --only hosting
```

Notes:
- The project id used is `business-management-fc675`.
- Ensure you are logged in to the Firebase account that has access to that project.
