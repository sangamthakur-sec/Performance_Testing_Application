Tool: JMeter

JMeter discovers the maximum number of concurrent users that a website can handle and provides a variety of graphical analyses of performance reports.
• Load Testing: Modeling the expected usage by simulating multiple user access to the Web services concurrently
• Stress Testing: Every web server has a maximum load capacity. When the load goes beyond the limit, the webserver starts responding slowly and produces errors. The purpose of stress testing is to find the maximum load the webserver can handle.


Steps To run:

Download the JMeter setup from below URL:
https://jmeter.apache.org/download_jmeter.cgi https://mirrors.estointernet.in/apache//jmeter/binaries/apache-jmeter-5.4.1.zip

Steps:
1.	Extract the folder and put it in any specific location(eg. C:\apache-jmeter-5.3)
2.	Open CMD
3.	Change directory to Bin folder (e.g: CD C:\apache-jmeter-5.3\bin)
4.	Run the below command to execute a script.
jmeter -n -t D:\Application_Data\Jmeter_Practice\Nopcommerce_Test.jmx -l D:\Application_Data\Jmeter_Practice\Nopcommerce_Test.csv -e -o D:\Application_Data\Jmeter_Practice\Nopcommerce_Test_HTML -Juser=10 -Jrampup=1

Note: You Can change -Juser value with no. of users. And Jrampup value based on load arrives on a website 

Results: 
1.	CSV file generated with details response time
2.	HTML dashboard report will also generate to view result in detail.
