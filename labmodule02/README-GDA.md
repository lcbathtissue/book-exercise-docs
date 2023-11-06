# Gateway Device Application (Connected Devices)

## Lab Module 02

Be sure to implement all the PIOT-GDA-* issues (requirements) listed at [PIOT-INF-02-001 - Lab Module 02](https://github.com/orgs/programming-the-iot/projects/1#column-9974938).

### Description

NOTE: Include two full paragraphs describing your implementation approach by answering the questions listed below.

What does your implementation do? 

The Gateway Device App (GDA) now also integrates the system performance manager and system utility task modules to track and test the validity of the system's CPU and memory utilization while also logging the results to the terminal. 

How does your implementation work?

The GDA achieves this by using built in jdk modules such as Logger, ManagementFactory, MemoryUsage, etc for our classes in our program such as SystemCpuUtilTask & SystemMemUtilTask and JUnit 4 is used for automated testing of the software.

### Code Repository and Branch

NOTE: Be sure to include the branch (e.g. https://github.com/programming-the-iot/python-components/tree/alpha001).

URL: https://github.com/lcbathtissue/java-components

### UML Design Diagram(s)

NOTE: Include one or more UML designs representing your solution. It's expected each
diagram you provide will look similar to, but not the same as, its counterpart in the
book [Programming the IoT](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).

![Gateway Device App (GDA) - UML Design Diagram](GDA_UML_labmodule02.png)

### Unit Tests Executed

NOTE: TA's will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- ActuatorDataTest
![ActuatorDataTest](ActuatorDataTest_labmodule07_GDA.png)

- BaseIotDataTest
![BaseIotDataTest](BaseIotDataTest_labmodule07_GDA.png)

- ConfigUtilTest
![ConfigUtilTest](ConfigUtilTest_labmodule07_GDA.png)

- DataUtilTest
![DataUtilTest](DataUtilTest_labmodule07_GDA.png)

- ResourceNameTest
![ResourceNameTest](ResourceNameTest_labmodule07_GDA.png)

- SensorDataTest
![SensorDataTest](SensorDataTest_labmodule07_GDA.png)

- SimpleCertManagementUtilTest
![SimpleCertManagementUtilTest](SimpleCertManagementUtilTest_labmodule07_GDA.png)

- SystemCpuUtilTaskTest
![SystemCpuUtilTaskTest](SystemCpuUtilTaskTest_labmodule07_GDA.png)

- SystemMemUtilTaskTest
![SystemMemUtilTaskTest](SystemMemUtilTaskTest_labmodule07_GDA.png)

- SystemPerformanceDataTest
![SystemPerformanceDataTest](SystemPerformanceDataTest_labmodule07_GDA.png)


### Integration Tests Executed

NOTE: TA's will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- CloudClientConnectorTest
![CloudClientConnectorTest](CloudClientConnectorTest_labmodule07_GDA.png)

- CoapClientConnectorTest
![CoapClientConnectorTest](CoapClientConnectorTest_labmodule07_GDA.png)

- CoapClientPerformanceTest
![CoapClientPerformanceTest](CoapClientPerformanceTest_labmodule07_GDA.png)

- CoapClientToServerConnectorTest
![CoapClientToServerConnectorTest](CoapClientToServerConnectorTest_labmodule07_GDA.png)

- CoapServerGatewayTest
![CoapServerGatewayTest](CoapServerGatewayTest_labmodule07_GDA.png)

- DataIntegrationTest
![DataIntegrationTest](DataIntegrationTest_labmodule07_GDA.png)

- DeviceDataManagerNoCommsTest
![DeviceDataManagerNoCommsTest](DeviceDataManagerNoCommsTest_labmodule07_GDA.png)

- DeviceDataManagerWithCommsTest
![DeviceDataManagerWithCommsTest](DeviceDataManagerWithCommsTest_labmodule07_GDA.png)

- GatewayDeviceAppTest
![GatewayDeviceAppTest](GatewayDeviceAppTest_labmodule07_GDA.png)

- MqttClientConnectorTest
![MqttClientConnectorTest](MqttClientConnectorTest_labmodule07_GDA.png)

- MqttClientControlPacketTest
![MqttClientControlPacketTest](MqttClientControlPacketTest_labmodule07_GDA.png)

- MqttClientPerformanceTest
![MqttClientPerformanceTest](MqttClientPerformanceTest_labmodule07_GDA.png)

- PersistenceClientAdapterTest
![PersistenceClientAdapterTest](PersistenceClientAdapterTest_labmodule07_GDA.png)

- SmtpClientConnectorTest
![SmtpClientConnectorTest](SmtpClientConnectorTest_labmodule07_GDA.png)

- SystemPerformanceManagerTest
![SystemPerformanceManagerTest](SystemPerformanceManagerTest_labmodule07_GDA.png)

EOF.
