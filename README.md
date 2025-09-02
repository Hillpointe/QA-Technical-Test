# QA Engineer Technical Test - AutomationExercise

Welcome to your technical assessment! This test leverages [AutomationExercise](https://www.automationexercise.com/) a full-fledged practice site for QA automation and API testing.

---

##  Overview

**Goal:** Evaluate your hands-on skills in test automation, API validation, test case design, and bug documentation, replicating realistic QA workflows.

---

##  Test Sections & Tasks

### Section 1: UI Automation

Choose a number of the test cases provided on the _Test Cases_ page of the site (e.g., Register User, Login User, Contact Us, etc.)
- Write automated tests using your preferred tool (e.g., Cypress, Playwright, Selenium).
- Validate both success, error, and edge cases where applicable.
- Submit both:
  - Test scripts (clean, structured, maintainable)
  - A short README or comments explaining your approach.

### Section 2: API Testing

Review the API endpoints available on the **API Testing** section. Choose a few of them (e.g., Get All Products List, Verify Login, Search Product)
- Design and execute tests (via Postman, REST-assured, curl, etc.) covering:
  - Valid requests
  - Invalid parameters
  - Expected error codes and messages
- Submit:
  - Your test request(s)
  - Assertions or validations (e.g., status code, response body)
  - Any exploratory findings

### Section 3: Test Case Design

Design **3–5 additional test scenarios** not already listed on the site (e.g., complex user flows, negative edge cases). Provide:
- Feature or flow description
- Step-by-step test steps
- Expected outcomes
- Pre-conditions & cleanup

### Section 4: Bug Reports

Intentionally or unintentionally, you may encounter a bug during the above tasks. Capture one and write a bug report, including:
- Title
- Steps to reproduce
- Actual vs Expected result
- Severity & Priority
- Screenshots or logs (if any)

---

##  Deliverables Checklist

- UI test scripts (plus explanatory README/comments)  
- API tests (with assertions and summaries)  
- 3–5 added test cases in structured format  
- At least 1 bug report

---

##  Evaluation Criteria

| Category           | Focus                                  |
|-------------------|----------------------------------------|
| **Correctness**     | Scripts accurately validate UI/API     |
| **Coverage & Depth** | Edge cases and negative scenarios      |
| **Code Quality**     | Readability, structure, maintainability |
| **Thought Process** | Rationale & testing strategy clarity   |
| **Documentation**    | Clarity and completeness of extras     |
| **Bug Reporting**    | Clarity, reproducibility, completeness |

---

##  Tips & Notes

| Suggestion                        | Details |
|----------------------------------|---------|
| **Start simple**                   | Prioritize reliable, clear tests; add edge cases as time permits |
| **Reusable code**                  | Use setup, teardown,/or page object patterns |
| **Data handling**                 | Use test fixtures or dynamic data where needed |
| **Tool flexibility**               | Any modern framework is acceptable—Cypress, Playwright, Selenium, etc. |
| **Timeboxing**                     | If time runs short, prioritize script and documentation; denote any unfinished parts |

---

##  Helpful Resources

- **Test Cases list** from the site: detailed scenarios like “Register User”, “Search Product”, etc.
- **API Endpoints overview**: methods and expected responses (e.g., `GET /api/productsList`, `POST /api/verifyLogin`)

---

Once you’re done, please send a ZIP or link to a Git repo containing your work. We’ll review your approach thoroughly and follow up with feedback or a debrief if needed.

Good luck! Looking forward to seeing your testing strategies in action.
