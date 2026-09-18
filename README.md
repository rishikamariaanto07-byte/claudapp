# VITZON MVP

`vitzon-mvp.html` is an interactive, dependency-free implementation of the approved P1 scope. Open it in a modern browser. It persists demo actions in that browser's local storage.

Included: listing creation/discovery, private favorites, participant-only-style contact requests, Lost & Found reports, client validation, and responsive views.

For production, connect the UI to Firebase Authentication, Cloud Firestore, and Cloud Storage; deploy `firestore.rules` and `storage.rules`; then replace the local browser storage adapter with authenticated backend calls. The rules are designed to make ownership and participant checks enforceable server-side.

Intentionally excluded: real-time chat, notifications, verification badges, campus communities, advanced full-text search, price history, and other P2/P3 items.
