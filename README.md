
# Startup API Testing – Postman

Manual API testing project for a startup e-commerce platform.

## 🔧 Tools Used

- Postman
- Chrome DevTools
- REST API
- JSON
- GitHub

---

## 🧪 Testing Activities

- API request validation
- Response verification
- Status code analysis
- Authentication testing
- Error handling validation
- Backend response analysis
- Negative testing
- Endpoint validation

---

## 📌 Tested Status Codes

| Status Code | Meaning |
|---|---|
| 200 | OK |
| 201 | Created |
| 204 | No Content |
| 401 | Unauthorized |
| 404 | Not Found |
| 502 | Bad Gateway |

---

## 🐞 Sample Bugs Found

- Broken API endpoints
- Incorrect routing
- Unauthorized access issues
- Validation failures
- Repeated 502 server errors
- Empty responses (0 B)
- API/frontend mismatch

---

## 📂 Repository Structure

```bash
collections/       -> Postman collections
environments/      -> Postman environments
screenshots/       -> API response screenshots
bug-reports/       -> API bug documentation
test-scenarios/    -> API test scenarios
```

---

## ✅ Sample Postman Tests

```javascript
pm.test("Status is 200", function () {
    pm.response.to.have.status(200);
});

pm.test("Response time is less than 500ms", function () {
    pm.expect(pm.response.responseTime).to.be.below(500);
});
```

---

## 🚀 Project Goal

To practice real-world API testing workflows using Postman and manual QA methodologies in a startup environment.
