Google Load Test using Apache JMeter

Overview
This project demonstrates a basic load test on the Google homepage using Apache JMeter.

Test Details

Tool: Apache JMeter 5.6.3
Website: https://www.google.com/
Method:** GET
Users:** 10
Ramp-Up Time:** 5 Seconds
Loop Count:** 1

Test Steps

Created a Thread Group with 10 users.
Added an HTTP Request to the Google homepage.
Executed the test.
Recorded the test results in a CSV file.

Expected Result

HTTP Response Code: **200 OK**
All requests should be successful.
No errors during execution.

Files

`google_load_test.jmx` – JMeter Test Plan
'google-page_test.jmx' - JMeter Test Plan
`google_test_results.csv` – Test Results
`README.md` – Project Documentation
