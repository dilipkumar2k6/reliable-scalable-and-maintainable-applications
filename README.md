# Reliable, Scalable, and Maintainable Applications
- Many applications today are data intensive as oppose to CPU intensive
- Biggest problem is amount of data, the complexity of data and the speed at which changing

Following are desired for modern applications.
- Reliability
    - Tolerating hardware and software failure
    - Tolerating human error
- Scalability
    - Measuring load and performance
    - Latency 
    - Throughput
    - percentile
- Maintainability
    - Operability
    - Simplicity
    - Evolvability

A data intensive application typically built from following standard building blocks 
- Store data so that they or another application can find it latter (database)
- Remember the result of expensive operations, to speedup read (cache)
- Allow user to search data by keyword or filter it by various ways (search indexes)
- Send a message to another process, to be handled asynchronously (stream processing)
- Periodically crunch a large amount of accumulated data (batch processing)
 