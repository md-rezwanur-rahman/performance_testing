# performance_testing
This project demonstrates performance testing using Apache JMeter for a booking system. The test plan includes creating, updating, and deleting bookings while handling authentication using tokens.


Features Tested
Create Booking (POST)  Simulates creating a new booking.
Update Booking (PUT & PATCH)  Modifies booking details using a token.
Delete Booking (DELETE)  Removes a booking.
Token Generation (POST) Generates authentication tokens for secured endpoints.

Tools & Technologies
Apache JMeter  Used for scripting and executing performance tests.
JMX File  Contains the test plan configuration.
JTL File  Logs test execution results.
HTML Report  Provides a detailed summary of test results.

Project Files

booking_t100.jmx - JMeter test plan file.
booking_t100.jtl - Execution log for test results.
booking_t100_report.html(index.html) - Performance report in HTML format.