# Secure Document Access System

Secure docs app with register, login, role-based access

## What Works
- Register with Name, Email, Password, Role (Viewer/Manager)
- Login with validation
- Dashboard shows Welcome + Role
- Manager can create documents, Viewer can only view
- Logout and role-based access control

## How to Run
1. Clone: `git clone https://github.com/bodapatipriyanka001-droid/secure-document-access-system`
2. Open `index.html` in browser
3. Login: `admin@sec.com / admin123`

## Live Demo
https://bodapatipriyanka001-droid.github.io/secure-document-access-system/

## AI Tools Used
Used Claude and Meta AI for UI and logic, fixed role checks and validation myself.

## What AI Got Wrong
AI gave auth without page-level protection. I added redirect and role enforcement. Shortened description to 160 chars.

## What is Not Done
Server-side enforcement, audit trail, tests, real database - currently using localStorage. Will add backend later.
