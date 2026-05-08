# SauceDemo-QA-Testing-Project
This project demonstrates comprehensive Quality Assurance testing of the SauceDemo web application, including Manual Testing, Functional Testing, UI Validation, Bug Reporting, and Performance Testing to ensure application reliability, usability, and performance efficiency.


**Project Overview**


This project focuses on the End-to-End Manual and Performance Testing of the SauceDemo (Swag Labs) e-commerce application. The goal was to validate functional stability and analyze performance bottlenecks using industry-standard tools.

 **Tools & Environment**

 
**Testing Type:**

Manual Testing, Functional Testing, Negative Testing, Performance Testing.

**Tools:** 

Chrome DevTools

**Documentation:**

MS Excel (Test Cases), MS Word (Bug Reports).

**Environment:**

Windows 11 | Google Chrome (Latest Version).

**Performance Analysis Results**

One of the key findings of this project was the significant performance between user roles:

**Standard User**:

Fully loaded in approximately 762ms (0.76s).

**Performance Glitch User:**

Experienced a consistent delay, with load times reaching 5.49s.

**Technical Evidence:** 

Verified via Chrome DevTools Network logs, identifying high TTFB (Time to First Byte) as the primary backend latency issue.

**Project Deliverables**

You can review the detailed documentation below:

**Sauce-Demo Test Cases Document:**

Includes positive and negative scenarios for Login, Product Cart, and Checkout flows.

**Bug Report Document:** 

Detailed bug logs with Steps to Reproduce, Severity/Priority and suggested fixes.

 **Testing Scope**
 
**Functional Testing:** Verified core features like "Add to Cart," "Sort by Price," and "Checkout Workflow."

**Boundary/Negative Testing:** Tested the system with invalid credentials and empty fields to ensure proper error handling.

**Performance Benchmarking:** Used the Network tab to monitor asset loading times and service worker efficiency.
