
# Payment API Test Scenarios

| ID | Scenario | Expected Result |
|---|---|---|
| TS-01 | Activate bonus with valid request | Bonus activated successfully |
| TS-02 | Save valid card details | Card saved |
| TS-03 | Send request without token | 401 Unauthorized |
| TS-04 | Invalid endpoint request | 404 Not Found |
| TS-05 | Server failure simulation | 502 Bad Gateway |
| TS-06 | Empty request body | Validation error |
