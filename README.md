This course covers the fundamentals of performance testing with JMeter.

## Prerequisites
You will need a machine with JMeter (and Java) installed which can be downloaded from [here](https://jmeter.apache.org/download_jmeter.cgi)

We will also be looking at some additional plugins from the [JMeter Plugins](https://jmeter-plugins.org/) project, so it will be useful if you also install the Plugins Manager which is located [here](https://jmeter-plugins.org/wiki/PluginsManager/)

Finally, if you would like to get some early reading in, you could browse the [user manual](https://jmeter.apache.org/usermanual/index.html) or read some of the interesting articles published by [Blazemeter](https://www.blazemeter.com/blog)

## Topics
### What performance test tools do (and how they work)
We will look at how performance test tools solve the problem of behaving like large numbers of users without actually having lots of users or their devices (browsers/smartphones/IoT devices)

We will examine the potential issues with this approach and how to overcome them.

We will also introduce tools like [Google Lighthouse](https://developers.google.com/web/tools/lighthouse) which provide complementary information.

### Creating Test Plans (scripting)
Learn how to create test plans using 
- JMeter Recorder 
- manually
- importing cURL/HAR

#### A simple example
Apply to volunteer at this [example site](https://volunteer-example.herokuapp.com/)

Sample Test Plans:

- [manual example](.\plans\apply_to_volunteer_manual.jmx)
- [trace example](.\plans\apply_to_volunteer_from_trace.jmx)

#### Which approach works best?
- Recording tools hampered by technologies designed to prevent security attacks.
- Manual approach best promotes understanding but requires care
- Exporting and converting HAR/cURL reasonable compromise

#### Using templates
How templates can provide a good way to get started.

### Introduction to JMeter components
Learn about the key components that make up JMeter. 
- controllers
- samplers
- listeners
- pre & post processors
- assertions
- timers
- functions

### JMeter Plugins
A set of utilities for making richer tests is provided by the [JMeter Plugins](https://jmeter-plugins.org) project.

- Dummy sampler - good for learning and debugging complex plans

- Custom Thread Groups - good for creating more complex shapes

### Introduction to Other Helper Tools
How tools like Charles, Fiddler and in-built browser developer tools can help create tests.

### Understanding Correlations
Learn how to capture, store and return dynamic values.

### Using Data in Tests
Use CSVs to drive tests with CSV Data Set Config.

The importance of being able to trace data. 

### Writing Groovy scripts
Scripts can be used as flexible components.

Look at how to make a post-processor to apply more complex logic.

### Designing and Running Tests

Learn about different test types and learn how to design and execute:
- peak
- soak
- stress
- spike 
- custom patterns

### Analysis and Reporting 
Capture results and create HTML reports.

Introduce other reporting options such as:
- Graphite
- Prometheus
- Influxdb
- Grafana
- PowerBI

### Integrating with CI/CD process
Using Jenkins to execute tests

## Useful links
The following links will also be useful:
#### Make jmx files from har files
https://converter.blazemeter.com/

#### JSON primer
https://jsonpath.com/
https://jmespath.org/tutorial.html

#### Regular expression cheatsheet
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions/Cheatsheet

#### Downloading Jmeter
https://jmeter.apache.org/download_jmeter.cgi

#### User manual
https://jmeter.apache.org/usermanual/index.html
