# 04-rummy-admin
Separate Admin-only web application. Uses `/api/admin/**`; never shares the mobile application bundle. The generic JSON forms are intentionally implementation-oriented so every backend configuration field remains accessible while specialized UX can be layered on top.

Admin cannot manipulate hands/cards/shuffle/outcomes. Sensitive actions remain permission checked and audited by the backend.
