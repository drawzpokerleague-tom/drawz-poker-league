# Drawz Poker League — Firebase Live Update

This release connects the public website to the Firebase Cloud Firestore `players` collection.

## What is live now
- The Players and Standings pages load the `players` collection in real time.
- The existing Admin > Add Player form adds a player directly to Firestore.
- Updates made in Firebase appear on every visitor’s device without redeploying.

## Upload
Upload every file in this folder to the root of the GitHub repository and replace the existing files. Commit directly to `main`. Netlify will deploy automatically.

## Important
Firestore test-mode rules expire. Before inviting the public to create accounts or edit data, add Firebase Authentication and secure Firestore rules.
