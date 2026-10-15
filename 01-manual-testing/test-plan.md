# Test Plan – Automation Exercise

## 1. Objective
Verify the main functions of the Automation Exercise demo e-shop from the
customer's point of view, find and report defects, and practice the full
testing process (planning, test design, execution, reporting).

## 2. Scope
### In scope
- Home page and product listing
- Product detail, product search, categories and brands
- Cart (add / remove products)
- User account: sign up, login, logout, delete account
- Checkout and order placement (test payment only)
- Contact Us form
- Product review
- API endpoints listed on the site's "APIs list" page
- Basic database testing on a sample e-shop database (separate exercise)

### Out of scope
- Real payments
- Performance, load and security testing
- Advertisements displayed on the site
- Mobile devices and browsers other than Chrome

## 3. Test Environment
- URL: https://automationexercise.com
- OS: Windows 11 Home, version 25H2
- Browser: Google Chrome 145.0.7632.109
- Test data: fictitious user accounts (no real personal data)

## 4. Tools
- Google sheet – test cases and test execution results
- Postman – API testing
- PostgreSQL + pgAdmin – database testing
- Git + GitHub – version control and publishing results

## 5. Test Approach
- Exploratory testing to get to know the application
- Manual functional testing based on written test cases
  (positive and negative scenarios)
- API testing in Postman (status codes, response content)
- SQL queries to check data quality in a sample database

## 6. Risks
- The application is public and may change or be unavailable at any time
- Ads and pop-ups may interfere with testing
- Shared public environment – data created by other users may affect results

## 7. Deliverables
- Test plan (this document)
- Test cases and execution results (Excel)
- Bug reports with screenshots
- Postman collection
- SQL scripts and queries