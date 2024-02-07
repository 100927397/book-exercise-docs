# Gateway Device Application (Connected Devices)

## Lab Module 01

Be sure to implement all the PIOT-GDA-* issues (requirements) listed at [PIOT-INF-01-001 - Lab Module 01](https://github.com/orgs/programming-the-iot/projects/1#column-9974937).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 
The implementation of the Gateway Device Application (GDA) in Java Eclipse serves as a pivotal component within the gateway device, responsible for managing data, analytics, and configuration settings. Its primary role is to facilitate seamless communication between the Constrained Device Application (CDA) and cloud services residing within the Cloud Tier. This involves handling data locally when necessary, establishing connections between the CDA and cloud services, and executing actions on the constrained device based on received telemetry data. Additionally, the GDA oversees configuration settings defining nominal ranges for various environmental parameters, ensuring system stability and performance.

How does your implementation work?
Operationally, the GDA continuously monitors and processes telemetry data received from the constrained device. Upon receiving new telemetry data, it conducts preliminary analytics to evaluate the data's significance and relevance. These analytics may include trend analysis, anomaly detection, or pattern recognition to derive actionable insights. Based on the results of these analytics, the GDA determines the appropriate course of action, such as initiating actuations on the constrained device or adjusting configuration settings to maintain optimal operational conditions. Furthermore, the GDA maintains a local data cache to ensure uninterrupted functionality, even in the absence of a stable connection to cloud services. Overall, the GDA acts as a crucial intermediary in the data pipeline, enabling efficient communication between the constrained device and cloud services while also providing essential data management and analytical capabilities at the edge.

### Code Repository and Branch

NOTE: Be sure to include the branch (e.g. https://github.com/programming-the-iot/python-components/tree/alpha001).

URL: 

### UML Design Diagram(s)

NOTE: Include one or more UML designs representing your solution. It's expected each
diagram you provide will look similar to, but not the same as, its counterpart in the
book [Programming the IoT](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).
![image](https://github.com/programming-the-iot/book-exercise-docs/assets/158244435/24f4aa1e-88b7-4195-91ad-121602afa9ab)


### Unit Tests Executed

NOTE: TA's will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

![image](https://github.com/programming-the-iot/book-exercise-docs/assets/158244435/e1840478-98e1-42e7-a344-a23211026d72)


### Integration Tests Executed

NOTE: TA's will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

![image](https://github.com/programming-the-iot/book-exercise-docs/assets/158244435/661f5d7e-a9ea-42a9-ae35-b318b1901d57)
![image](https://github.com/programming-the-iot/book-exercise-docs/assets/158244435/176358db-6683-46be-9445-8e98fbd64ffb)
![image](https://github.com/programming-the-iot/book-exercise-docs/assets/158244435/99d88a4f-dd9d-4552-a453-556ae73a1b8c)


EOF.
