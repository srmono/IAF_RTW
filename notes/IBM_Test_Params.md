In IBM Rational Performance Tester (RPT), Rational Integration Tester (RIT), and Rational Functional Tester (RFT), each tool is used for specific types of testing, and each offers different parameters for testing and analysis. Here’s a breakdown of the parameters you can test and analyze in each tool:

### 1. **IBM Rational Performance Tester (RPT)**
   **RPT** is primarily used for **performance testing** of web-based and server-based applications. It helps you simulate loads and analyze performance metrics.
   
   **Parameters you can test:**
   - **Response time**: Time taken by the system to respond to a request.
   - **Throughput**: The number of transactions processed by the system in a given time frame.
   - **Concurrent users/Virtual users**: Simulating multiple users to test the scalability.
   - **Transaction count**: The number of successful or failed transactions.
   - **Page load time**: Time taken for pages in the application to load.
   - **Network latency**: Delays in the network affecting system performance.
   - **CPU/Memory utilization**: System resources consumed during the test.

   **Parameters you can analyze after the test:**
   - **Response time analysis**: Distribution of response times, slowest/fastest transactions.
   - **Error rates**: Percentage or count of failed transactions.
   - **Server utilization metrics**: CPU and memory consumption under different load conditions.
   - **Bottleneck identification**: Pinpointing where performance degrades, whether due to server, network, or application code.
   - **Transaction throughput**: Number of successful transactions processed over time.

### 2. **IBM Rational Integration Tester (RIT)**
   **RIT** is used for **integration testing** in service-oriented architecture (SOA), middleware, and API testing. It focuses on verifying that different components and systems work together correctly.

   **Parameters you can test:**
   - **API requests/responses**: Ensuring the correct functioning of APIs.
   - **Data integrity**: Verifying that data is passed correctly between systems.
   - **SOAP/REST services**: Testing web services for functional correctness.
   - **Message queues and topics**: Testing interactions in messaging systems like IBM MQ.
   - **Service virtualization**: Simulating parts of the system that may be unavailable or incomplete.
   - **Business rules validation**: Ensuring the correct implementation of business logic.
   
   **Parameters you can analyze after the test:**
   - **Test coverage**: Percentage of functionality covered in integration tests.
   - **Message validation results**: Checking if messages passed between systems adhere to expected formats and schemas.
   - **Service response times**: Analyzing delays in service interactions.
   - **Pass/Fail results**: Identifying successful versus failed API or service interactions.
   - **Error diagnostics**: Detailed analysis of any failures, such as incorrect data formats or unexpected system responses.

### 3. **IBM Rational Functional Tester (RFT)**
   **RFT** is primarily used for **functional and regression testing** of GUI-based applications. It helps automate test cases for functional correctness across various platforms.

   **Parameters you can test:**
   - **Functional correctness**: Ensuring that the application behaves as expected under different inputs and conditions.
   - **UI automation**: Automating interaction with user interfaces, including buttons, forms, and dropdowns.
   - **Cross-browser/platform testing**: Testing the same functionality across different browsers or devices.
   - **Data-driven testing**: Executing tests with multiple sets of data.
   - **Regression testing**: Verifying that new code changes do not break existing functionality.

   **Parameters you can analyze after the test:**
   - **Test result logs**: Detailed execution logs showing which tests passed or failed, along with error messages and screenshots.
   - **Error diagnostics**: Detailed reports of test failures, including the exact steps and screenshots of the application at failure points.
   - **Code coverage**: Measure of how much of the application's code or features were exercised during testing.
   - **Test run comparison**: Comparing test results across multiple test runs to identify trends or recurring issues.
   - **Performance metrics**: Although not as detailed as RPT, you can monitor some performance aspects like the speed of specific actions or workflows during functional testing.

### Summary of key parameters:

| Tool            | Test Parameters                                       | Post-Test Analysis Parameters                                     |
|-----------------|-------------------------------------------------------|-------------------------------------------------------------------|
| **RPT**         | Response time, Throughput, Virtual users, CPU/memory, Transaction count, Page load time, Network latency | Response time distribution, Error rates, Server utilization, Bottleneck identification, Transaction throughput |
| **RIT**         | API requests/responses, Data integrity, SOAP/REST services, Service virtualization, Message queues | Test coverage, Message validation, Service response times, Pass/fail results, Error diagnostics |
| **RFT**         | Functional correctness, UI automation, Data-driven testing, Cross-browser/platform testing | Test result logs, Error diagnostics, Code coverage, Test run comparison, Performance of workflows |

Each tool targets different aspects of software quality (performance, integration, and functional correctness) and provides specific metrics that help in analyzing the effectiveness and reliability of the system being tested.