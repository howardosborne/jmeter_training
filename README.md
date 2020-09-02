# Performance Testing with JMeter

This course provides a simple overview of using JMeter.

## What performance test tools do (and how they work)
Solve the problem of how to create the behaviour of large numbers of users without having lots of users or their devices (browsers/smartphones/IoT devices)

Usually work by replacing the browser or smartphone with a simpler client which creates the same (usually HTTP) traffic.

What are the potential issues with this approach?

How can they be mitigated?

Tools like [Google Lighthouse](https://developers.google.com/web/tools/lighthouse) offer a client view.

## Creating Test Plans (scripting)

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

- Recording tools hampered by technologies designed to prevent security attacks.
- Manual approach best promotes understanding but requires care
- Exporting and converting HAR/cURL reasonable compromise

### Using templates
Templates provide a good way to get started.

## Introduction to JMeter components

Learn about the key components that make up JMeter. 
- controllers
- samplers
- listeners
- pre & post processors
- assertions
- timers
- functions

## JMeter Plugins

A set of utilities for making richer tests is provided by the [JMeter Plugins](https://jmeter-plugins.org) project.
Dummy sampler - good for learning and debugging complex plans
Custom Thread Groups - good for creating more complex shapes

## Introduction to Other Helper Tools

How tools like Charles, Fiddler and in-built browser developer tools can help create tests.

## Understanding Correlations

Learn how to capture, store and return dynamic values.

## Using Data in Tests

Use CSVs to drive tests with CSV Data Set Config.

The importance of being able to trace data. 

## Writing Groovy scripts
Scripts can be used as flexible components.

Will look at how to make a post-processor to get a value and 

## Designing and Running Tests

Learn about different test types and learn how to design and execute:
- peak
- soak
- stress
- spike 

and other test patterns

## Analysis and Reporting 

Capture results and create HTML reports.

Introduce other reporting options.

Graphite/Prometheus/Influxdb/Grafana

PowerBI

## Integrating with CI/CD process
Using Jenkins to execute tests

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
