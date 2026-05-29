# API Security Risk Analysis – Future Interns Task 3

## Overview

This project contains an API Security Risk Analysis conducted as part of the Future Interns Cyber Security Internship Program.

The assessment focused on identifying common API security risks in public/demo APIs using safe and ethical testing methods.

The analysis included:

* authentication review
* public endpoint analysis
* response inspection
* security header analysis
* rate limiting observations
* excessive data exposure assessment

---

## Objective

The objective of this project was to:

* analyze public APIs
* identify API security risks
* assess authentication and access controls
* evaluate API responses and headers
* provide remediation recommendations
* document findings professionally

---

## APIs Tested

The following public/demo APIs were used for testing:

### ReqRes API

Used for:

* authentication analysis
* security header inspection
* authorization behavior review

### JSONPlaceholder API

Used for:

* public endpoint testing
* excessive data exposure analysis
* response inspection
* rate limiting observations

---

## Tools Used

* Postman
* Google Chrome
* Browser DevTools
* GitHub
* Markdown Documentation

---

## Testing Methodology

The following methodology was followed during the assessment:

1. Reviewed API documentation
2. Tested endpoints using Postman
3. Inspected API responses
4. Analyzed authentication requirements
5. Reviewed HTTP security headers
6. Observed rate limiting behavior
7. Documented identified risks
8. Suggested remediation strategies

---

## Key Findings

| Finding                            | Severity      |
| ---------------------------------- | ------------- |
| Authentication Enforcement Present | Informational |
| Public Endpoint Accessibility      | Medium        |
| Excessive Data Exposure            | Medium        |
| Missing Rate Limiting              | High          |
| Security Headers Implemented       | Informational |

---

## Detailed Security Observations

### Authentication Enforcement

The ReqRes API properly enforced API authentication using API keys and rejected unauthorized requests with `401 Unauthorized` responses.

### Public Endpoint Accessibility

JSONPlaceholder endpoints allowed unrestricted public access without authentication requirements.

### Excessive Data Exposure

API responses exposed user-related data including:

* email addresses
* IDs
* metadata
* comments

### Missing Rate Limiting

No visible request throttling or API rate limiting mechanisms were observed during repeated requests.

### Security Headers

The ReqRes API implemented several recommended security headers including:

* Strict-Transport-Security
* X-Content-Type-Options
* Referrer-Policy
* Cross-Origin policies

---

## Recommendations

Recommended security improvements include:

* implementing authentication on sensitive endpoints
* applying rate limiting controls
* minimizing unnecessary response data
* conducting regular API security audits
* following OWASP API Security Top 10 guidelines

---

## Ethical Notice

This project was conducted strictly for educational and internship purposes using publicly available demo APIs.

No exploitation, bypass attempts, denial-of-service activity, or malicious actions were performed.

All testing was limited to safe and authorized interactions.

---

## Project Structure

```bash
FUTURE_CS_03_API_SECURITY_ANALYSIS/
│
├── README.md
├── findings/
│   └── risk_summary.md
│
├── Screenshots/
│   ├── reqres_401.png
│   ├── jsonplaceholder_posts.png
│   ├── jsonplaceholder_comments.png
│   └── headers_analysis.png
│
├── postman_collection/
│   └── FutureInterns_API_Security_Analysis.json
│
└── report/
    └── API_Security_Risk_Analysis_Report.pdf
```

---

## Skills Demonstrated

* API Security Analysis
* Authentication Review
* HTTP Header Inspection
* Risk Assessment
* Security Documentation
* SaaS Security Concepts
* OWASP API Security Awareness

---

## Author

Sahil Sharma
Cyber Security Intern – Future Interns
