# Performance Testing Projects (JMeter)

This repository contains hands-on JMeter projects and example tasks created during performance testing practice and training.  
Each `.jmx` file demonstrates a specific JMeter concept such as JSON extraction, API testing, thread groups, controllers, timers, and more.

---

## 📂 Contents

| File / Task | Description |
|-------------|-------------|
| **Task 1 - JSON Extractor.jmx** | Demonstrates extraction of JSON values from API responses for use in subsequent requests. |
| **Task 2 - HTTPS Script Recorder.jmx** | Captures and records HTTP/HTTPS traffic to create test scripts automatically. |
| **Task 3 - If Controller.jmx** | Shows conditional execution of samplers using If Controller logic. |
| **Task 4 - REST API.jmx** | Example of testing REST APIs including GET, POST requests, and validating responses. |
| **Task 5 - Stepping Thread Group & Ultimate Thread Group.jmx** | Demonstrates advanced thread group configuration for realistic load and ramp-up scenarios. |
| **Task 6 - Timers.jmx** | Illustrates usage of JMeter timers (Constant, Gaussian, Poisson) to control user pacing. |
| **Task 7 - If Controller (Task 7).jmx** | Another example of conditional execution for dynamic workflow testing. |
| **Task 8 - HTTPS Script Recorder (Task 8).jmx** | Additional example of recording HTTP/HTTPS traffic for different test scenarios. |
| **HTTP Config elements.jmx** | Examples of JMeter configuration elements such as CSV Data Set, HTTP Header Manager, and User Defined Variables. |
| **Assertions and Listeners.jmx** | Shows use of response assertions and listeners like Summary Report, Aggregate Report, and View Results Tree. |
| **Basic Authentication.jmx** | Demonstrates HTTP Basic Authentication setup for protected endpoints. |
| **Correlation.jmx** | Example of extracting dynamic values (tokens, session IDs) using Regular Expression Extractor for correlated requests. |
| **Counter.jmx** | Shows implementation of counters to dynamically manage iteration values across samplers. |
| **Distributed Testing.jmx** | Setup for distributed load testing using multiple JMeter slave nodes. |
| **Function Helper.jmx** | Demonstrates use of JMeter functions (random numbers, timestamps, properties, etc.). |
| **SMTP Sampler.jmx** | Example of sending emails using JMeter SMTP sampler. |
| **WebDriver Sampler.jmx** | Demonstrates GUI-based performance testing using WebDriver Sampler. |
| **Workload Modelling.jmx** | Illustrates creating realistic workload models with thread groups, ramp-up, and scheduler settings. |
| **jp@gc - Ultimate Thread Group.jmx** | Example of the Ultimate Thread Group plugin for advanced load testing scenarios. |

---

## 🧰 Tools and Environment
- **Apache JMeter** (v5.x)  
- **Java 8+**  
- Optional: **BlazeMeter plugin** for cloud testing  
- Optional: **Grafana / InfluxDB** for dashboard reporting

---

## 📊 How to Use
1. Clone or download this repository.  
2. Open any `.jmx` file in **Apache JMeter**.  
3. Customize endpoints, credentials, or data files as needed.  
4. Run the test and view results in listeners or dashboard reports.

---

## 📘 Notes
- All examples are for **learning and demonstration purposes**.  
- No live systems or confidential endpoints were tested.  
- Screenshots of results, logs, or HTML reports can be included in the `Results/` folder to help reviewers visualize performance metrics.

---
*Author: Disha Ramesh*

