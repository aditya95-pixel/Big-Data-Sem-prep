# Big Data Semester Preparation

## Group A

### Module 3

### (i) Characteristics of IoT are:
- (a) Dynamic and Self Adapting  
- (b) Interoperable communication protocols  
- ✅ **(c) Both (a) and (b)**  
- (d) None of the above  

### (ii) Each IoT device has a Unique Id:
- ✅ **(a) Unique Identifier**  
- (b) Internet Protocol Address  
- (c) Personal Computer  
- (d) Smart Phone  

### (iii) Applications of IoT are:
- (a) Music  
- (b) Home lighting  
- (c) Analytics  
- ✅ **(d) All the above**  

### (iv) IoT device can:
- ✅ **(a) Exchange data with other connected devices and applications**  
- (b) Cannot collect data from other devices  
- (c) Both (a) and (b)  
- (d) None of the above  

### (v) HDMI is:
- (a) High definition multiplier interface  
- ✅ **(b) High definition multimedia interface**  
- (c) High difference media interface  
- (d) None of the above  

### (vi) IEEE 802.11 is for:
- (a) Ethernet  
- (b) WPAN  
- ✅ **(c) WiFi**  
- (d) Mobile Communication  

### (vii) IPv4: Internet Protocol version 4 identifies:
- (a) Identifies the devices in the network using hierarchical addressing scheme, total 64 addresses.  
- (b) 128-bit address scheme  
- (c) Data transfer 250kb/s  
- ✅ **(d) None of the above**  

### (viii) CoAP, MQTT, XMPP, DDS are:
- ✅ **(a) Application Layer Protocol**  
- (b) Presentation Layer Protocol  
- (c) Session Layer Protocol  
- (d) Data Link Layer Protocol  

---

## Group D


### 26(a) Function of Management in IoT Systems
### [(CO4)(Analyse/HOCQ)]

In IoT systems, **management functions** play a crucial role in ensuring efficient operation, security, and scalability. The key functions include:

1. **Device Management** - Monitors and maintains IoT devices, including provisioning, authentication, and firmware updates.
2. **Data Management** - Handles data collection, storage, and processing from IoT devices.
3. **Network Management** - Ensures proper communication between devices, cloud services, and edge computing nodes.
4. **Security Management** - Implements authentication, encryption, and anomaly detection to prevent unauthorized access.
5. **Energy Management** - Optimizes power consumption for battery-operated IoT devices.
6. **Fault Management** - Detects and resolves issues in real-time to maintain system reliability.

Efficient IoT management ensures **seamless connectivity, improved performance, and enhanced security** in distributed networks.

---

### 26(b) Role of Subscribers in the Publish-Subscribe Model
### [(CO6)(Remember/LOCQ)]

In the **Publish-Subscribe (Pub-Sub) Model**, **subscribers** play a vital role in receiving relevant data. Their key roles include:

1. **Listening for Messages** - Subscribers register to specific topics of interest and receive only relevant messages.
2. **Decoupling from Publishers** - Subscribers do not communicate directly with publishers; instead, they rely on a broker for message distribution.
3. **Handling Events** - When a publisher sends a message, the broker ensures it reaches all relevant subscribers.
4. **Asynchronous Communication** - Subscribers receive messages asynchronously, making the system scalable and efficient.
5. **Filtering Data** - Subscribers can apply filters to process only necessary messages, reducing bandwidth usage.

Subscribers enable **efficient, scalable, and flexible communication in IoT and distributed systems** by reducing direct dependencies between components.

---

### 26(c) Functions of Queues in Push-Pull Communication Model
### [(CO6)(Apply/IOCQ)]

In the **Push-Pull Communication Model**, **message queues** manage data flow between producers and consumers. Their primary functions include:

1. **Decoupling Producers and Consumers** - Queues act as an intermediary, allowing producers to send messages without waiting for consumers.
2. **Load Balancing** - Messages are stored in a queue until a consumer is ready, preventing system overload.
3. **Message Persistence** - Queues store messages temporarily, ensuring reliable delivery even if a consumer is unavailable.
4. **Prioritization** - Some queue implementations allow prioritizing urgent messages for faster processing.
5. **Scalability** - Multiple consumers can pull messages from the queue, improving system performance under high loads.
6. **Fault Tolerance** - If a consumer fails, messages remain in the queue until successfully processed by another consumer.

This model is widely used in **distributed systems, cloud services, and IoT networks** to improve communication reliability and efficiency.

---

### 27(a) Comparison of REST-Based Communication APIs vs. WebSocket-Based Communication APIs
### [(CO6)(Analyse/HOCQ)]

| Feature                | REST-Based Communication API | WebSocket-Based Communication API |
|------------------------|-----------------------------|-----------------------------------|
| **Communication Type** | Request-Response (Synchronous) | Full-Duplex (Asynchronous) |
| **Connection**         | Stateless, new connection for each request | Persistent, single connection |
| **Data Transfer**      | Each request gets a separate response | Continuous data exchange |
| **Latency**           | Higher due to repeated handshakes | Lower since connection is persistent |
| **Best Use Case**      | Suitable for standard web applications (e.g., RESTful APIs) | Ideal for real-time applications (e.g., chat, gaming, stock updates) |
| **Scalability**       | Scales well with caching and load balancing | Requires persistent connections, may increase resource consumption |

### Key Analysis:
- **REST is best for request-response interactions**, while **WebSockets are optimal for real-time bidirectional communication**.
- **WebSockets reduce latency and bandwidth** but require **more resources** to maintain persistent connections.
- REST is widely used in **web services and IoT APIs**, while WebSockets are better for **real-time IoT applications** like smart home automation and live monitoring.

---

### 27(b) Exclusive Pair Communication Model
### [(CO6)(Remember/LOCQ)]

The **Exclusive Pair Communication Model** is a **one-to-one communication mechanism** where two devices establish a **direct and persistent** connection. 

### Features:
1. **Dedicated Connection** - A stable, continuous link between two devices.
2. **Low Latency** - Ensures fast and reliable data transfer.
3. **Secure Communication** - Encryption and authentication mechanisms enhance security.
4. **Limited Scalability** - Not suitable for systems requiring multiple concurrent connections.
5. **Example Use Cases** - Used in **Bluetooth Pairing, Secure IoT Messaging, and Encrypted Device Communication**.

This model is **best suited for IoT applications where data privacy, reliability, and low latency are critical**.

---

## 27(c) Applications of IoT Enabling Technologies
### [(CO5)(Apply/IOCQ)]

Several technologies enable IoT applications across industries. Some key applications include:

1. **Smart Homes & Cities** - IoT-enabled lighting, energy management, and smart grids.
2. **Healthcare & Wearables** - Remote patient monitoring, smartwatches, and fitness trackers.
3. **Industrial Automation** - Predictive maintenance, robotics, and supply chain tracking.
4. **Agriculture** - Smart irrigation systems, soil monitoring, and automated farming.
5. **Transportation & Logistics** - Connected vehicles, GPS tracking, and fleet management.
6. **Retail & Customer Experience** - Smart shelves, personalized shopping experiences, and automated checkout systems.

These applications leverage IoT technologies like **RFID, Cloud Computing, Edge AI, 5G, and Blockchain** to improve efficiency, automation, and connectivity.

---

### 28(a) Comparison of Infrastructure as a Service (IaaS) vs. Platform as a Service (PaaS)
### [(CO6)(Analyse/HOCQ)]

| Feature                | Infrastructure as a Service (IaaS) | Platform as a Service (PaaS) |
|------------------------|----------------------------------|------------------------------|
| **Definition**        | Provides virtualized computing resources over the cloud. | Provides a development environment with tools and services. |
| **Control Level**     | Full control over the infrastructure (servers, storage, networking). | Limited control, focuses on application development and deployment. |
| **Management**       | Users manage operating systems, applications, and storage. | Cloud provider manages OS, runtime, and middleware. |
| **Scalability**       | Highly scalable, users can configure resources as needed. | Scales automatically but within the provider’s framework. |
| **Target Users**      | IT administrators, system architects needing custom infrastructure. | Developers focusing on building and deploying applications. |
| **Examples**         | AWS EC2, Google Compute Engine, Microsoft Azure Virtual Machines. | Google App Engine, AWS Elastic Beanstalk, Microsoft Azure App Services. |

### Key Analysis:
- **IaaS is best for users who need full control over their infrastructure**, while **PaaS is ideal for developers who want a ready-to-use development platform**.
- **IaaS requires more configuration**, whereas **PaaS simplifies development with pre-configured tools**.

---

### 28(b) Cloud Computing Services Offered to Users
### [(CO6)(Remember/LOCQ)]

Cloud computing offers various services categorized into the following:

1. **Infrastructure as a Service (IaaS)** - Provides virtual machines, storage, and networking (e.g., AWS EC2, Google Compute Engine).
2. **Platform as a Service (PaaS)** - Offers a development platform with pre-built tools (e.g., AWS Elastic Beanstalk, Heroku).
3. **Software as a Service (SaaS)** - Provides ready-to-use software over the cloud (e.g., Google Drive, Microsoft 365, Dropbox).
4. **Function as a Service (FaaS)** - Supports serverless computing where functions run on-demand (e.g., AWS Lambda, Google Cloud Functions).
5. **Storage as a Service (STaaS)** - Offers cloud-based storage solutions (e.g., Google Drive, OneDrive, Amazon S3).
6. **Database as a Service (DBaaS)** - Provides managed database services (e.g., AWS RDS, Firebase, Google Cloud SQL).

These services help users **reduce infrastructure costs, increase scalability, and enhance accessibility** in cloud environments.

---

### 28(c) Characteristics of Big Data
### [(CO5)(Analyse/IOCQ)]

Big Data is characterized by the **5Vs**:

1. **Volume** - Large amounts of data generated from various sources like sensors, healthcare devices, and IoT systems.
2. **Velocity** - High-speed data generation and processing in real-time or near real-time.
3. **Variety** - Data comes in multiple formats: structured (databases), semi-structured (JSON, XML), and unstructured (videos, images, logs).
4. **Veracity** - Ensures data accuracy and reliability, as sensor data may contain noise or inconsistencies.
5. **Value** - Extracting meaningful insights and patterns to drive decision-making and innovations.

Big Data technologies process and analyze **massive datasets** to improve efficiency in **healthcare, IoT, predictive maintenance, and AI applications**.

---
