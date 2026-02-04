# FUTURE_CS_03  
## API Security Risk Analysis – JSONPlaceholder

This repository contains **Task 3** of the **Cyber Security Internship by Future Interns (2026)**.

The task focuses on performing a **security risk analysis of public APIs** using Postman, identifying **common API security weaknesses**, and documenting findings in a **professional, business-friendly report**.

---

## 🎯 Task Objective

The objective of this task is to:

- Analyze publicly available API endpoints  
- Identify common API security risks  
- Detect missing or weak authentication and authorization controls  
- Observe excessive data exposure in API responses  
- Identify missing rate-limiting and input validation  
- Document findings with clear remediation recommendations  

This task emphasizes **API security assessment and risk analysis**, not exploitation.

---

## ⚠️ Scope & Ethics

✔ Public API endpoints only  
✔ Read-only analysis and safe request testing  
✔ No exploitation or denial-of-service attempts  
✔ No modification of real user data  

All testing was conducted **ethically for learning purposes**.

---

## 🔧 Tools Used

| Tool | Purpose |
|----|----|
| Postman | Sending HTTP requests and analyzing API responses |
| GitHub | Documentation and project hosting |

---

## 🌐 Web API Examined

- **API Name:** JSONPlaceholder  
- **Base URL:** https://jsonplaceholder.typicode.com  
- **API Type:** Public demo REST API  

### Endpoints Tested
- `GET /posts`
- `GET /users`
- `GET /comments`
- `POST /posts`

---

## 🔍 API Testing Methodology

The following approach was used during the analysis:

1. Sent GET and POST requests using Postman  
2. Checked whether endpoints require authentication  
3. Reviewed API responses for excessive data exposure  
4. Tested data creation without authentication  
5. Observed input validation behavior  
6. Performed basic checks for rate-limiting  
7. Classified identified risks  
8. Documented findings with remediation suggestions  

---

## 🚨 Identified API Security Risks

The following security risks were identified during testing:

- Open and unauthenticated API endpoints  
- Exposure of user-related data without access control  
- Missing authentication and authorization mechanisms  
- Lack of rate-limiting controls  
- Weak or missing input validation  
- Potential misuse due to unrestricted API access  

---

## 📊 Risk Classification Summary

| Risk Area | Risk Level |
|---------|-----------|
| Open Endpoints | Medium |
| Excessive Data Exposure | Medium |
| Missing Authentication | Medium |
| Missing Authorization | Medium |
| Missing Rate Limiting | Medium |
| Weak Input Validation | Low–Medium |

---

## 🛠 Recommendations

- Implement authentication mechanisms such as API keys or OAuth  
- Apply proper authorization checks for sensitive endpoints  
- Limit data returned in API responses  
- Enforce rate-limiting to prevent abuse  
- Validate and sanitize user input  
- Monitor API usage and log suspicious activity  

---

## 📄 Deliverables

- 📘 API Security Risk Analysis Report (PDF)  
- 📸 Postman request and response screenshots  
- 📝 Documentation of identified risks and recommendations  

---

## ✅ Task Status

✔ API endpoints tested using Postman  
✔ Security risks identified and classified  
✔ Business-friendly explanations provided  
✔ Remediation recommendations documented  
✔ Professional report created  

**Task 3 – Completed**

---

## ⚠️ Disclaimer

This project was completed **strictly for educational purposes** as part of the Future Interns Cyber Security Internship.  
No exploitation or malicious activity was performed.

---

## 👤 Author

**Name:** *[Your Name]*  
**Internship:** Cyber Security Intern – Future Interns (2026)
