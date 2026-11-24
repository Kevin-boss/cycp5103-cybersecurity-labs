# Redaction checklist (run before every commit)

- [ ] No passwords, app passwords, API keys, tokens, OTPs (revoke anything that ever appeared in a screenshot)
- [ ] No phone numbers or personal email addresses
- [ ] No third-party IP addresses or hostnames you are not authorised to test
- [ ] Your own public IP / ISP blurred in leak-test screenshots
- [ ] No device serials, MAC addresses, usernames of real people
- [ ] Raw screenshots kept in `raw-screenshots/` (git-ignored); only edited copies in `evidence/`
- [ ] No lecturer PDFs or copied course text; write in your own words
- [ ] No live phishing URLs (use example.com)
- [ ] `git status` and `git diff --staged` reviewed
- [ ] Scope statement present in the lab README
