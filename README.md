# An Introduction to JMeter

This course provides a simple overview of using JMeter.

## What performance test tools do (and how do they work)?
Solve the problem of how to create the behaviour of large numbers of users without having lots of users or their devices (browsers/smartphones/IoT devices)

Usually work by replacing the browser or smartphone with a simpler client which creates the same (usually HTTP) traffic.

## Creating Test Plans

Create test plans using 
- JMeter Recorder 
- manually
- importing cURL/HAR

### A simple example
Apply to volunteer at:
https://volunteer-example.herokuapp.com/

Examples:
[manual example](.\plans\apply_to_volunteer_manual.jmx)
[trace example](.\plans\apply_to_volunteer_from trace.jmx)

### Which approach works best?
Recording tools hampered by technologies designed to prevent security attacks.
Manual approach best promotes understanding but requires care
Exporting and converting HAR/cURL reasonable compromise

### Using templates
Look at how templates can help.

## Introduction to JMeter components

Learn about the key components that make up JMeter. This comprises looking at controllers, samplers, listeners, pre & post processors, assertions, timers and functions.

## Introduction to Other Helper Tools

How tools like Charles, Fiddler and in-built browser developer tools can help create tests.


## Understanding Correlations

Learn how to capture, store and return dynamic values.


## Using Data in Tests

Find out how to use CSVs to drive tests as well as other data sources.
The importance of being able to trace data

## Designing and Running Tests

Learn about different test types and learn how to design and execute peak, soak, stress, spike and other test patterns.


## Analysis and Reporting 

Capture results and create HTML reports. Introduce other reporting options.


## Useful links

### to make jmx files from har files
https://converter.blazemeter.com/

### json primer
https://jsonpath.com/
https://jmespath.org/tutorial.html

### Regular expression cheatsheet
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet

### Downloading Jmeter
https://jmeter.apache.org/download_jmeter.cgi

### User manual
https://jmeter.apache.org/usermanual/index.html