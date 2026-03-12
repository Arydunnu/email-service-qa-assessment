# Email Micro-Service
## Overview
This repository contains QA documentation for testing the Email Micro-Service.

Contents include:

- Test Strategy
- Automated API tests
- Sample bug reports
- Execution screenshots

## Functional Tests Automation for EMS

Automated using **Postman Collection Runner**.

Test scenarios covered:

- Valid request returns **202 Accepted**
- Missing `to` field returns **422 Unprocessable entity**
- Invalid email format returns **400 Bad Request**
- Queue full scenario returns **503 Service Unavailable** (documented approach)

## How to Run Tests

1. Import Postman collection
2. Set environment variable `base_url`
3. Run using Collection Runner

## Tools Used

- Postman
- GitHub
