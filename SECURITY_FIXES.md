# SECURITY_FIXES.md

## 🔐 Secrets Removed

1. Removed hardcoded DB password from `index.js`.
2. Replaced it with environment variable: `process.env.DB_PASSWORD`
3. Added `.env` file (not tracked in Git).
4. Deleted `secrets.txt` file with AWS secret key.
5. Moved secrets to GitHub Actions → Secrets tab.
