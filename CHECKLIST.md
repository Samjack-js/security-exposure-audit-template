# Security Exposure Audit Checklist

## 1. Scope

- [ ] Domain confirmed
- [ ] Subdomains confirmed
- [ ] Authorization received
- [ ] Out-of-scope items listed
- [ ] Testing limits defined
- [ ] Contact person defined

## 2. HTTPS / TLS

- [ ] HTTPS enabled
- [ ] HTTP redirects to HTTPS
- [ ] Certificate valid
- [ ] No obvious mixed content
- [ ] No expired certificate

## 3. Security Headers

- [ ] Strict-Transport-Security
- [ ] Content-Security-Policy
- [ ] X-Frame-Options or frame-ancestors
- [ ] X-Content-Type-Options
- [ ] Referrer-Policy
- [ ] Permissions-Policy

## 4. Public Exposure

- [ ] Directory listing checked
- [ ] Backup files checked
- [ ] Exposed config files checked
- [ ] Public admin panels noted
- [ ] Technology versions reviewed
- [ ] Error messages reviewed

## 5. Forms and Inputs

- [ ] Contact forms identified
- [ ] Search fields identified
- [ ] Login forms identified
- [ ] File uploads identified
- [ ] Reflected input checked safely
- [ ] Validation behavior documented

## 6. Reporting

- [ ] Findings documented
- [ ] Evidence captured
- [ ] Impact explained
- [ ] Severity assigned
- [ ] Recommendations provided
- [ ] Retest option noted
