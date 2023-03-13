# ROS-101
Let's learn ROS together

ROS (Robot Operating System) is a software framework that provides libraries and tools to help developers build robotics applications. ROS-Humble is the latest version of ROS, and it offers several improvements over ROS-Noetic.

Some of the advantages of ROS-Humble over ROS-Noetic include:

1. Improved performance: ROS-Humble has been optimized for performance, with a focus on real-time communication and low latency. This makes it well-suited for use in robotics applications that require fast and reliable communication between software components.

2. Enhanced security: ROS-Humble introduces a number of security features, such as support for Transport Layer Security (TLS) and access control policies, which can help protect against cyber attacks and ensure the integrity of data transmitted over the network.

3. Improved scalability: ROS-Humble has been designed to support large-scale systems, with support for distributed computing and cloud integration. This allows for the development of robotics applications that can operate across multiple devices and locations.

4. Enhanced support for multi-robot systems: ROS-Humble includes improved support for coordinating the actions of multiple robots, allowing for the development of more complex and sophisticated multi-robot systems.

5. New programming languages: ROS-Humble supports a wider range of programming languages, including C++, Python, and Java, which can make it easier for developers to integrate ROS into their existing workflow.

Overall, ROS-Humble is a powerful software platform that can help developers build advanced robotics applications with improved performance, security, scalability, and support for multi-robot systems.



However despite all mentioned benefits of the new ROS, due to better resources and documentaiton I will carry on with ROS-Noetic


here is some commands and hint i find useful which i will review and rewrite in better format later:

1- "roscore" to Lunch the ROS and "killall -9 rosmaster" && "killall -9 roscore" to end it <br/>
2- "rqt_graph" is used to show the relation between topics in diagrame. <br/>
3- "rostopic list -v" list of topics. <br/>
4- This is the format that is used to present topic and message type: "/topic_name [message_type]"  <br/>
