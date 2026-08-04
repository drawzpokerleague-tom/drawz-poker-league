# Drawz Poker League — Admin Login Update

This update adds:

- Firebase email/password administrator sign-in
- An admin-only player editor
- Add, edit, and delete player controls
- Public read-only standings
- A Firestore rules file named `FIRESTORE-RULES.txt`

## Deployment order

1. Upload the website files to the GitHub repository and let Netlify publish them.
2. Test signing in on the Admin page.
3. In Firebase > Firestore Database > Rules, paste the contents of
   `FIRESTORE-RULES.txt` and publish them.

Do not upload `FIRESTORE-RULES.txt` expecting Netlify to apply it automatically.
It is included as a reference for the Firebase Rules editor.
