# La Bouquinerie Web Application Testing Assignment

## Objective
Evaluate the candidate's ability to design, implement, and execute manual and automated test cases for the [La Bouquinerie](http://labouqinnerie.com/) website.

## Assignment Description
You are tasked with testing the [La Bouquinerie](http://labouqinnerie.com/) website, focusing on key functionalities. The application has the following functionalities:
1. Home Page
2. Book Listings
3. Book Details Page
4. Add to Cart
5. Checkout Process (You do not need to complete a real purchase; just go as far as possible)

## Tasks

### 1. Manual Testing
Design a comprehensive set of test cases for the "Book Listings" and "Book Details Page" functionalities. Document your test cases in a spreadsheet or document format. Include the following details for each test case:
- Test Case ID
- Test Description
- Pre-conditions
- Test Steps
- Expected Results
- Actual Results (Leave blank for now)

### 2. Bug Reporting
Perform manual testing based on the test cases you designed. Identify and document any bugs you encounter during testing. Use the following format for each bug:
- Bug ID
- Bug Description
- Steps to Reproduce
- Expected Results
- Actual Results
- Severity (Critical, Major, Minor)

### 3. Automation Testing
Write an automated test script to verify the "Add to Cart" functionality using Selenium WebDriver (or any other preferred automation tool). The script should:
- Navigate to the book listings page
- Select a book and go to the book details page
- Add the book to the cart
- Verify that the book is added to the cart successfully

### 4. Performance Testing
Design a basic performance test plan for the "Book Listings" functionality. Specify the key performance metrics you would measure (e.g., response time, throughput). Explain the tools and methods you would use to conduct the performance test (no need to execute the test, just the plan).

### 5. Exploratory Testing
Conduct exploratory testing on the "Checkout Process". Note any issues, inconsistencies, or potential areas of improvement you encounter. Document your findings in a brief report.
You can pass a payment using this test card
- **Card Number:** `5440212711111110`
- **Expiration:** `12/26`
- **CVV:** `665`

## Submission
1. Fork this repository to your GitHub account.
2. Create a new branch with your name (e.g., `john-doe-testing-assignment`).
3. Add the following files to the repository:
   - `manual_test_cases.xlsx` or `manual_test_cases.docx`: The manual test cases document.
   - `bug_reports.md`: Bug reports.
   - `automation_script/`: Directory containing the automated test script and any supporting files.
   - `performance_test_plan.md`: The performance test plan document.
   - `exploratory_testing_report.md`: The exploratory testing report.
4. Include a `README.md` file in the `automation_script/` directory explaining how to run the automated test script and any assumptions or considerations you made during the assignment.
5. Create a pull request to the original repository.

### Evaluation Criteria
- **Completeness:** All parts of the assignment are completed and submitted as requested.
- **Test Case Quality:** Test cases are well-written, comprehensive, and cover both positive and negative scenarios.
- **Bug Reports:** Bug descriptions are clear and detailed, with reproducible steps.
- **Automation Script:** The script is functional, well-structured, and follows best practices for code quality and readability.
- **Performance Test Plan:** The plan is realistic, detailed, and demonstrates a good understanding of performance testing concepts.
- **Exploratory Testing Report:** Findings are clearly documented, and insightful observations are made.
- **Documentation:** All documentation is clear, concise, and well-organized.

Good luck, and we look forward to reviewing your submission!
