# Drawz Poker League — Professional Admin v2

This version includes:

- Firebase administrator sign-in
- Live public standings
- Player add/edit/delete tools
- Tournament scheduling and editing
- Result entry with automatic player totals
- Announcement management
- Installable PWA support

## Deployment

Upload all website files to the root of the GitHub repository and commit them to `main`.
Netlify will redeploy automatically.

After confirming the administrator sign-in works, paste the contents of
`FIRESTORE-RULES.txt` into Firebase > Firestore Database > Rules and publish.

These rules allow public viewing but allow changes only by a signed-in Firebase
Authentication user. Keep only your administrator account in Firebase Authentication.
