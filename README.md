# FUTURE_CS_03
API Security Risk Analysis using Postman to identify authentication weaknesses, data exposure risks, and API security issues as part of the Future Interns Cyber Security Internship.
# API Security Risk Analysis

## Future Interns – Cyber Security Internship

### Author
Ruchith Pathani

## Introduction

This project was completed as part of the Future Interns Cyber Security Internship Program.

The objective of this task was to analyze publicly accessible APIs and identify potential security risks. API testing was performed using Postman to examine API responses, exposed data, authentication mechanisms, and security controls.

---

## Tools Used

- Postman
- Kali Linux
- Public Test APIs
- Browser Developer Tools
- GitHub

---

## APIs Tested

### Users API
https://jsonplaceholder.typicode.com/users

### Posts API
https://jsonplaceholder.typicode.com/posts

---

## Activities Performed

- API Endpoint Testing
- Response Analysis
- Header Inspection
- Data Exposure Assessment
- Security Risk Identification
- Documentation and Reporting

---

## Security Findings

### 1. Lack of Authentication Controls
**Risk Level:** High

The API endpoints were accessible without authentication.

### 2. Data Exposure
**Risk Level:** Medium

User-related information such as names, emails, and addresses were exposed in API responses.

### 3. Missing Rate Limiting
**Risk Level:** Medium

No visible request throttling mechanism was observed.

### 4. Header Security Review
**Risk Level:** Low

API security headers should be reviewed regularly.

---

## Risk Assessment Summary

| Vulnerability | Risk Level |
|--------------|------------|
| Lack of Authentication | High |
| Data Exposure | Medium |
| Missing Rate Limiting | Medium |
| Header Security Review | Low |

---

## Security Recommendations

- Implement Authentication (JWT/OAuth)
- Apply Authorization Controls
- Limit Sensitive Data Exposure
- Enable API Rate Limiting
- Secure API Headers
- Monitor API Activity
- Perform Regular Security Assessments

---

## Learning Outcomes

- API Security Testing
- Postman Usage
- API Response Analysis
- Data Exposure Assessment
- Security Risk Identification
- Cybersecurity Documentation

---

## Conclusion

This project demonstrated how APIs can expose information if proper security controls are not implemented. The assessment highlighted authentication weaknesses, data exposure risks, and the importance of API security best practices.

---

**Ruchith Pathani**  
Cyber Security Intern  
Future Interns
