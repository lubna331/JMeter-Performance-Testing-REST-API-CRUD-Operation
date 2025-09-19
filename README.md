# JMeter-Performance-Testing-REST-API-CRUD-Operation
## Project Overview
This project demonstrates **API testing and performance analysis** using **Apache JMeter**.  
The test plan covers **CRUD operations**, **authentication**, and **response validations**, along with performance reporting.  
The goal was to validate API correctness and measure system performance under different loads.  

---

## Tools & Technologies
- Apache JMeter 5.6.3  
- REST APIs (CRUD endpoints)  
- JSON Extractor, HTTP Header Manager, Auth Manager

## Test Scenarios
1. **Authentication** – Login request with valid credentials.  
2. **CRUD Operations** –  
   - Create: POST request to add a resource.  
   - Read: GET request to fetch resource.  
   - Update: PUT/PATCH request to modify resource.  
   - Delete: DELETE request to remove resource.  
3. **HTTP Header Manager** – Managed headers (Content-Type, Authorization).  
4. **JSON Extractor** – Captured dynamic values (IDs, tokens) from responses.  
5. **Assertions & Validation** – Verified response codes and body data.

## Reports & Results
- **View Results Tree** → Debugged API requests and responses.  
- **Aggregate Report** → Measured response time, throughput, and error %.  

## Learnings
- Designed end-to-end API test plans in JMeter.  
- Implemented authentication and dynamic data handling with extractors.  
- Analyzed performance metrics using aggregate reports and HTML dashboards.  
- Validated CRUD functionality with assertions.  
