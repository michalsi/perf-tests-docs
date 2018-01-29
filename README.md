# perf-tests-docs
Collection of Performance Tests related materials 

## Performance Testing Theory

 - [Performance Testing vs. Load Testing vs. Stress Testing](https://www.blazemeter.com/blog/performance-testing-vs-load-testing-vs-stress-testing?utm_source=blog&utm_medium=BM_blog&utm_campaign=jmeter-vs-locust-which-one-should-you-choose)

 - [8 Tips to Decide the Number of Concurrent Users for Your Test](https://www.blazemeter.com/blog/8-tips-decide-number-concurrent-users-your-test?utm_source=blog&utm_medium=BM_blog&utm_campaign=jmeter-vs-locust-which-one-should-you-choose 
)
 - [Are you ready black friday 8 best load testing practices your app or site](https://www.blazemeter.com/blog/are-you-ready-black-friday-8-best-load-testing-practices-your-app-or-site) - quick intro to performance tests
 - [8 Load Testing Steps You Must Take Before the UK Elections](https://www.blazemeter.com/blog/8-load-testing-steps-you-must-take-before-the-uk-elections) - short explanation of steps required when working with performance tests.
 - [Lessons lernt from performance testing 2016 olympics](http://blog.loadimpact.com/performance-testing-2016-olympics)
 - [Think time in tests](https://octoperf.com/blog/2017/03/15/think-time/)
 
 - Making your performance engineering more efficient
    - [part 1](https://www.blazemeter.com/blog/testing-making-your-performance-engineering-more-efficient-part-1)
    - [part 2](https://www.blazemeter.com/blog/how-to-make-your-performance-engineering-more-efficient-part-2)
    - [part 3](https://www.blazemeter.com/blog/making-your-performance-engineering-more-efficient-part-3)
    - [performance testing rookie mistakes](http://performanceengineeringwisdom.com/performance-testing-rookie-mistakes/)

- [Six Design Principles of Continuous Performance Testing](https://blog.griddynamics.com/six-design-principles-of-continuous-performance-testing/)

- [Kainos ODP - Logging & Performance testing](https://github.com/KainosSoftwareLtd/gov-odp/wiki/Logging-&-Performance-testing)

### Collection of materials
- [MS Visual Studio - Load Testing resources](https://docs.microsoft.com/en-us/vsts/load-test/)
- [performance testing mindmap + list of resources](https://github.com/mgasiorowski/performance_testing_mindmap)

## Results Analysis

 - [The art of reading performance test charts](https://blog.xceptance.com/2013/04/22/the-art-of-reading-performance-test-charts/)
 - [Performance Test Reporting Fundamentals](https://msdn.microsoft.com/en-us/library/bb924371.aspx)

 - [Dashboard / report analyzer for load testing with JMeter](https://github.com/innogames/JMeter-Control-Center)
 
 - [2 Techniques to Get JMeter Test Results in non-GUI mode](https://www.blazemeter.com/blog/top-two-techniques-get-jmeter-test-results-non-gui-mode)
 - [BlazeMeter’s Sense - service for storing and analysing performance test results](https://sense.blazemeter.com/)
 


## Load generation Tools

### Jmeter

#### Tests design

 - [Meter Ramp-Up - The Ultimate Guide](https://www.blazemeter.com/blog/jmeter-ramp-up-the-ultimate-guide)
 - [Web Testing with JMeter: How To Properly Handle Embedded Resources in HTML Responses](https://www.blazemeter.com/blog/web-testing-jmeter-how-properly-handle-embedded-resources-html-responses)

#### Jmeter Components

 - [jmeter tutorial on Guru99](https://www.guru99.com/jmeter-tutorials.html)
 - [Logs, vars, props](https://jmetervn.com/2016/12/05/jsr223-with-groovy-variables-part-1/)
[JSR223 with Groovy: Variables (Part 2) - Sampler, ctx](https://jmetervn.com/2016/12/20/jsr223-with-groovy-variables-part-2/) 
 - [Parameters,Script File](https://jmetervn.com/2017/01/13/jsr223-with-groovy-variables-part-3/)

 - [If controller](https://www.blazemeter.com/blog/how-use-jmeters-if-controller-and-get-pie)

 - [JMeter Plugins](https://www.blazemeter.com/blog/how-install-jmeter-plugins-manager)

 - [JMeter – Creating Modular / Reusable Test Scripts](http://www.testautomationguru.com/jmeter-modularizing-test-scripts/)

 - [Creating a New JMeter Test Purely in Java for Java Sampler](https://stackoverflow.com/questions/42344726/creating-a-new-jmeter-test-purely-in-java-for-java-sampler)

 - [Beanshell vs JSR223 vs Java JMeter Scripting](https://www.blazemeter.com/blog/beanshell-vs-jsr223-vs-java-jmeter-scripting-its-performance)

 - [JMeter Maven Plugin](https://www.blazemeter.com/blog/how-use-jmeter-maven-plugin)
 - [Commercial and Open Source JMeter Plugins](http://www.softwaretestingmagazine.com/tools/jmeter-plugins/)
 
 #### JMeter listeners
  - [Listeners with Basic Displays](https://www.blazemeter.com/blog/jmeter-listeners-part-1-basic-display-formats)
  - [Listeners that Aggregate Data Samples](https://www.blazemeter.com/blog/jmeter-listeners-part-2-listeners-aggregate-data-samples)
  - [Listeners that Calculate Distribution Metrics](https://www.blazemeter.com/blog/jmeter-listeners-part-3-listeners-calculate-distribution-metrics)
  - [Listeners that Support Scripting & Enable Test and System Management](https://www.blazemeter.com/blog/jmeter-listeners-part-4-listeners-support-scripting-enable-test-and-system-management)
 
 #### Jmeter and CI
 - [JMeter – Continuous Performance Testing – JMeter + Maven](http://www.testautomationguru.com/jmeter-continuous-performance-testing-jmeter-maven/)
 - [Jmeter on docker](https://github.com/deliverymind/useful-stuff/tree/master/jmeter-on-docker)
 - [Running JMmeter test - jenkins pipeline tutorial](https://www.blazemeter.com/blog/running-jmeter-test-jenkins-pipeline-tutorial)
 - [Configure Jenkins to Run and Show JMeter Tests](http://www.baeldung.com/jenkins-and-jmeter)
 
### Gatling
- [Gatling](https://gatling.io/) - Scala
- [Gatling introduction](http://james-willett.com/2017/08/gatling-introduction/)

### Other tools
 - [wrk](https://github.com/wg/wrk) - HTTP benchmarking tool capable of generating significant load when run on a single multi-core CPU. 
 - [Taurus](https://github.com/Blazemeter/taurus)
    - [gettaurus](http://gettaurus.org/)
 - [Locust](https://locust.io/) - python

 - [Artillery](https://artillery.io/) - Javascript
 - [k6](https://k6.io/) - "A developer-centric load testing tool" - Scripting in Javascript ES2015/ES6
    - https://github.com/loadimpact/postman-to-k6 - convert Postman collections to k6
 - [Yandex.Tank](https://github.com/yandex/yandex-tank) - extensible open source load testing tool for linux users. Written in python

### Tools Comparisons
 - Gatling vs Jmeter
    - [abstracta](https://abstracta.us/performance-testing/gatling-vs-jmeter-findings/)
    - [octoperf](https://octoperf.com/blog/2015/06/08/jmeter-vs-gatling/)
 - [Locust vs Jmeter](https://www.blazemeter.com/blog/jmeter-vs-locust-which-one-should-you-choose)
 - [The Grinder vs Gatling vs Tsung vs JMeter](https://www.blazemeter.com/blog/open-source-load-testing-tools-which-one-should-you-use?utm_source=blog&utm_medium=BM_blog&utm_campaign=jmeter-vs-locust-which-one-should-you-choose)
 - [open source performance testing tools](https://www.joecolantonio.com/2017/07/18/open-source-performance-testing-tools/)
 - [Performance: which testing tool and why?](https://club.ministryoftesting.com/t/performance-which-testing-tool-and-why/634/12)
 - [open source load testing tool review - by loadinpact](http://blog.loadimpact.com/open-source-load-testing-tool-review)
 - [Open Source Load Testing Tool Review - Benchmarks- by loadinpact](http://blog.loadimpact.com/open-source-load-testing-tool-benchmarks)
 - [Open Source Load Testing Tool Benchmarks V2 - by loadinpact](http://blog.loadimpact.com/open-source-load-testing-tool-benchmarks-v2)
   - [Spreadsheets with results](https://docs.google.com/spreadsheets/d/13ZCxDxy06LlhDD0vuys9R04ppGv787c7DkZT1XO5-Gc/edit#gid=505204278)
   -[JMeter vs Neoload vs HP Load Runner](https://www.ubik-ingenierie.com/blog/apache-jmeter-vs-neoload-vs-hp-load-runner/)

 ## Monitoring
  - [How to Monitor Your Server Health & Performance During a JMeter Load Test](https://www.blazemeter.com/blog/how-monitor-your-server-health-performance-during-jmeter-load-test)
 - https://jmeter-plugins.org/wiki/PerfMon/
 - [Cassandra performance monitoring](https://cassandra-zone.com/performance-monitoring/)
 - [Measure Anything, Measure Everything](https://codeascraft.com/2011/02/15/measure-anything-measure-everything/)
 - [Actionable Metrics - Enabling Decision-Making in Netﬂix’s Decentralized Environment(video+slides)](https://www.infoq.com/presentations/Netflix-Metrics)
 - [Prometheus: Monitoring at SoundCloud](https://developers.soundcloud.com/blog/prometheus-monitoring-at-soundcloud)
 - [nmon - performance Monitor for Linux ](http://nmon.sourceforge.net/pmwiki.php)
 - [Overload𝛃 – performance analytics server](https://overload.yandex.net/login/?next=/)
 
 ### Java Profilers
 - [A Guide to Java Profilers](http://www.baeldung.com/java-profilers)
 - [Top 5 Java Profilers Revealed: Real world data with VisualVM, JProfiler, Java Mission Control, YourKit and Custom tooling](https://zeroturnaround.com/rebellabs/top-5-java-profilers-revealed-real-world-data-with-visualvm-jprofiler-java-mission-control-yourkit-and-custom-tooling/)
 - [List of Java Profilers: 3 Different Types and Why You Need All of Them](https://stackify.com/java-profilers-3-types/)


## Library
### Books
 - [Performance Testing Guidance for Web Applications](https://msdn.microsoft.com/en-us/library/bb924375.aspx)

### White Papers
 - [How to Ensure Your Website or Mobile App Won’t Fail on PEAK DAYS](http://cdn2.hubspot.net/hub/208250/file-2347246121-pdf/LoadTestingHolidaysWhitepaper_.pdf)
 - [How Shift-Left Performance Testing from BlazeMeter Enables Substantial Cost Savings](https://cdn2.hubspot.net/hubfs/208250/TEI%20CA%20BlazeMeter.pdf)
 - [Load Testing & APM: A Guide to Accelerating Performance Tuning and Troubleshooting](http://cdn2.hubspot.net/hubfs/208250/Whitepapers/LT-APM_FinalVersion.pdf)
 - [Continuous Testing In Practice - Completing the Continuous Delivery Process](http://cdn2.hubspot.net/hub/208250/file-2411660713-pdf/websol/Continuous_Testing__Whitepaper.pdf)
  
### Blogs
 - [Blazemeter](https://www.blazemeter.com/blog)
 - [Xceptance](https://blog.xceptance.com/category/performance/)
 - [octoperf](https://octoperf.com/categories/load-testing/)
 - [performance wisdom](http://performanceengineeringwisdom.com/performancewisdomblog/)
 
 ### Videos
 - [Blazemeter resources](https://www.blazemeter.com/resources)
 
 ### Workshops
 - [How To Build A Performance Testing Stack From Scratch](https://dojo.ministryoftesting.com/series/how-to-build-a-performance-testing-stack-from-scratch)
