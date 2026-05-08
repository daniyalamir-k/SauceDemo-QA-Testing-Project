# SauceDemo-QA-Testing-Project
Comprehensive Manual and Performance Testing for SauceDemo website.
Project Overview
This project focuses on the End-to-End Manual and Performance Testing of the SauceDemo (Swag Labs) e-commerce application. The goal was to validate functional stability and analyze backend performance bottlenecks using industry-standard tools.

 Tools & Environment
Testing Type: Manual Functional Testing, Negative Testing, Performance Testing.

Tools: Chrome DevTools (Network Panel, Waterfall Analysis, Lighthouse).

Documentation: MS Excel (Test Cases), MS Word (Bug Reports).

Environment: Windows 11 | Google Chrome (Latest Version).

 Performance Analysis Results
One of the key findings of this project was the significant performance discrepancy between user roles:

Standard User: Fully loaded in approximately 762ms (0.76s).

Performance Glitch User: Experienced a consistent delay, with load times reaching 5.49s.

Technical Evidence: Verified via Chrome DevTools Network logs, identifying high TTFB (Time to First Byte) as the primary backend latency issue.

Project Deliverables
You can review the detailed documentation below:

Test Cases Document: Includes positive and negative scenarios for Login, Product Cart, and Checkout flows.

Bug Report Document: Detailed bug logs with Steps to Reproduce, Severity/Priority, and Screenshots as evidence.

 Testing Scope
Functional Testing: Verified core features like "Add to Cart," "Sort by Price," and "Checkout Workflow."

Boundary/Negative Testing: Tested the system with invalid credentials and empty fields to ensure proper error handling.

Performance Benchmarking: Used the Network tab to monitor asset loading times and service worker efficiency.
