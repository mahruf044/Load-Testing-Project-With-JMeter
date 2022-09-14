# Load-Testing-Project-With-JMeter

## Load Testing of Reqres Website

### Project Includes:

1.**Jmx folder**:Contains jmx files for each concurrent request.

2.**Jtl folder**:Contains jtl files for each concurrent request

3.**Report folder**:Contains report for each concurrent request.

4.**reqres_Summary_report**:Text file of overall summarry report.


The requests were set using **JMeter** app and the test cases for different user had been run  in **CLI** mode and reports for each test cases had been also generated in
**CLI** mode.

## Check the summary reqres_Summary_report to get idea of the overall summary.

## Go to Reports folder and find each test case report of different Concurrent Request in different folder.Open the index.html(run it by browser) of each concurrent request's folder  test case's folder to get the detailed report of each tested concurrent request.

## Download jmx files from the jmx folder to test these on JMeter app.You can also download the jtl files from jtl folder to generate the report on CLI mode.

## Summaray Report:

I’ve completed performance test on frequently used API for reqres.in App. 
Test executed for the below mentioned scenario in server 103.86.197.3. 

50 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 5 And Total Concurrent API requested: 300.
100 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 10 And Total Concurrent API requested: 600.
115 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 11.5 And Total Concurrent API requested: 690.
120 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 12 And Total Concurrent API requested: 720.
123 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 12.3 And Total Concurrent API requested: 738.
125 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 12 And Total Concurrent API requested: 750.

While executed 125 concurrent request, found  1 request got connection timeout and error rate is 0.13%. 

Summary: Server can handle almost concurrent 744 API call with almost zero (0) error rate.

Please find the details report from the attachment and  let me know if you have any further queries. 
