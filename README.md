MOOC: Collaborative Resource Sharing Project
===============================================

About the Project:

This team project aims to ensure a stable communication across multiple servers in a dynamic overlay network.

In a decentralized, loosely coupled, service oriented architecture; a significant amount of time is spent on reliability and scalability aspects of the system. The major challenges that a distributed network has to deal with include storage and retrieval of data, establishing connection across the servers, promptly responding to the requests and graceful handling of errors. There are several design concerns as mentioned below that should be addressed in the implementation:
	· 	Inspecting the request and response type.
	· 	Understanding DNS Resolution and IP Identification between the servers and requesting nodes i.e. client
	· 	Heterogeneous development and training environments
	· 	Testing options are limited because assessments have to be conducted using automated tools and allowing limited peer interaction

Even though this problem looks straightforward, the solution is non-trivial when the network is loosely coupled and dynamic in nature. Our approach to solving these problems involves multiple technologies that not only help in solving network communication problems, storage and retrieval but also set global standards to make this communication system interoperable.

Installations to be done
------------------------
The following are the project dependencies that need to be installed.
	1. Python2.7
	2. Google Protobuf
	3. RabbitMQ
	4. MongoDB
	5. Erlang - Set ERLANG_HOME

Run Test cases:
-----------------
- To run Python Test

	1. Run MongoDB
	2. Run RabbitMQ
	3. Open Test/Python folder in source code folder
	4. Run PythonTest.java as JUnit

- To run RabbitMQ Publisher-Subscriber Test

	1. Run RabbitMQ Server
	2. Run SubscriberTest.java
	3. Run PublishTest.java as JUnit

- To run PerChannelQueue Test

	1. Run PerChannelQueueTest as JUnit
