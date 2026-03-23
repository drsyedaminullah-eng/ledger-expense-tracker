Ledger — Secure Expense Tracker
Built for the AP Cybersecurity / Senior STEM Capstone Vibe Coding Competition.
Ledger is a personal finance tracker that lets users securely register, log in, and track their daily expenses by category. The entire app runs in a single HTML file — no server, no setup, just open and go.
Security Features

Password Hashing — passwords are hashed with SHA-256 + a random salt using the browser's built-in Web Crypto API. Plain text passwords are never stored anywhere.
Input Sanitization — all user-generated text is sanitized with DOMPurify and rendered via textContent (not innerHTML) to prevent XSS attacks.

How to Run
Download expense-tracker.html and open it in any browser. That's it.
Tech Stack

Vanilla HTML / CSS / JavaScript
DOMPurify 3.0.6 (XSS sanitization)
Web Crypto API (password hashing)
