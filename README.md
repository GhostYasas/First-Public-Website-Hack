# First-public-website-hack
My first successful public website penetration test. Full admin access, real impact, responsible disclosure.

# The Silent Door

### A Real-World Web Application Security Journey

---

Sometimes the most dangerous vulnerability isn’t a complex zero-day.  
It’s a door that was never locked.

This repository documents a short but intense authorized penetration testing engagement I conducted in September 2026 against a production educational web application. What started as a routine black-box assessment quickly turned into one of the most critical findings I’ve encountered so far.

---

## The Discovery

During the assessment, I gained full administrative access to the application’s backend management system. From there, complete visibility into student applications, academic records, selection dashboards, and internal reports became possible.

What made this particularly serious was the nature of the data involved — personal information of students.

---

## Visual Evidence

### Behind the Admin Panel

![Dashboard Overview](P%20Screenshots/admin1.png)

![Stream & Selection Metrics](P%20Screenshots/admin2.png)

![Application Listing](P%20Screenshots/admin3.png)

![Official Student Report](P%20Screenshots/admin4.png)

### Technical Evidence

![Internal Infrastructure Leak](P%20Screenshots/report1.png)

![Open Redirect Proof](P%20Screenshots/report2.png)

![Module Enumeration](P%20Screenshots/report3.png)

![Evidence Integrity Check](P%20Screenshots/report4.png)

---

## Key Findings at a Glance

| Severity  | Count | Summary |
|-----------|-------|--------|
| Critical  | 1     | Full administrative access obtained |
| High      | 1     | Internal infrastructure details exposed |
| Medium    | 5     | Open redirect, information disclosure, CSRF, user enumeration |
| Low       | 4     | Missing security headers & weak cookie attributes |

---

## The Journey

- Started with pure black-box testing (no credentials provided)
- Identified the underlying technology stack
- Discovered a critical authentication weakness that allowed complete administrative control
- Mapped additional medium and low severity issues
- Documented everything with proper evidence and hashes
- Privately reported all findings to the organization

The organization responded quickly. All critical and high severity issues were fixed.

---

## Lessons

The most important reminder from this engagement:

> Never underestimate the power of default or weak credentials.  
> They remain one of the simplest yet most devastating attack vectors.

Security is not only about complex exploits. Sometimes it’s about checking the doors that everyone assumes are locked.

---

## Disclaimer

- This was a fully authorized engagement.
- No data was modified, deleted, or extracted.
- All critical issues have been remediated.
- Shared here purely for educational and awareness purposes.

---

**Security Researcher**  
Yasas Dulanjan  
September 2026
