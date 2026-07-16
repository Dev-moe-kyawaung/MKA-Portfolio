# Security Policy

## Supported Versions

We actively maintain and provide security updates for the following versions:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

We take security seriously. If you discover a security vulnerability, please follow these steps:

### 🔒 Private Disclosure

**DO NOT** create a public GitHub issue for security vulnerabilities.

Instead, please report security issues via:

1. **Email**: moekyawaung@programmer.net
   - Subject: [SECURITY] Brief description
   - Include detailed description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if any)

2. **Telegram**: @moekyawaung (for urgent issues)

### ⏱️ Response Timeline

- **Initial Response**: Within 48 hours
- **Status Update**: Within 7 days
- **Fix Deployment**: Within 30 days (depending on severity)

### 🎖️ Recognition

We maintain a security hall of fame for responsible disclosure:

- Your name/handle will be credited (unless you prefer anonymity)
- Listed in CHANGELOG.md and security advisories
- Public acknowledgment after fix is deployed

## Security Best Practices

### For Users

1. **Keep Updated**: Always use the latest version
2. **Verify Source**: Only download from official repository
3. **Report Issues**: Report any suspicious behavior
4. **Secure Deployment**: Use HTTPS for all deployments

### For Contributors

1. **Code Review**: All PRs undergo security review
2. **No Secrets**: Never commit API keys, passwords, or tokens
3. **Input Validation**: Always validate user inputs
4. **Dependencies**: Keep dependencies updated
5. **XSS Prevention**: Sanitize all user-generated content

## Known Security Considerations

### Current Implementation

This is a static website with:
- ✅ No backend authentication
- ✅ No user data storage
- ✅ Client-side form validation only
- ✅ External CDN dependencies

### Recommendations for Production

If you fork this project for production use:

1. **Forms**: Implement server-side validation
2. **Contact Form**: Add CSRF protection and rate limiting
3. **Analytics**: Review privacy implications
4. **Third-party**: Audit all external dependencies
5. **Content Security Policy**: Implement strict CSP headers

## Security Features

### Implemented

- ✅ HTTPS enforcement (via GitHub Pages)
- ✅ No inline JavaScript (CSP-ready)
- ✅ Input sanitization in forms
- ✅ No eval() or dangerous functions
- ✅ Secure external links (rel="noopener")
- ✅ XSS protection measures

### Planned

- [ ] Content Security Policy headers
- [ ] Subresource Integrity (SRI) for CDN resources
- [ ] Rate limiting for forms
- [ ] CAPTCHA for contact form
- [ ] Server-side form handling

## Vulnerability Disclosure Policy

### Scope

**In Scope:**
- Cross-Site Scripting (XSS)
- Code injection vulnerabilities
- Authentication/authorization issues (if implemented)
- Sensitive data exposure
- Security misconfigurations

**Out of Scope:**
- Social engineering attacks
- Physical attacks
- Denial of Service (DoS)
- Issues in third-party dependencies (report to them directly)
- Issues requiring extensive user interaction
- Clickjacking on pages without sensitive actions

### Safe Harbor

We will not pursue legal action against security researchers who:
- Make good faith efforts to comply with this policy
- Avoid privacy violations and data destruction
- Do not exploit vulnerabilities beyond demonstration
- Report vulnerabilities promptly

## Contact

For security concerns:
- **Email**: moekyawaung@programmer.net
- **Telegram**: @moekyawaung
- **Response Time**: Within 48 hours

For general issues:
- Create a GitHub issue
- Email for non-urgent matters

---

**Last Updated**: January 15, 2025

Thank you for helping keep this project and its users safe!
