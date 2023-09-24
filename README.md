# Understanding Systems Design Fundamentals 🚀

## Introduction to Design Fundamentals 🌟
In the realm of software engineering, we often encounter two types of interviews: coding interviews 🧠 and systems design interviews 🏗️. While coding interviews assess problem-solving skills, systems design interviews delve into engineering knowledge beneath the surface of open-ended design questions.

**Coding Interviews vs. Systems Design Interviews**
- Coding interviews focus less on theoretical knowledge and more on problem-solving.
- Systems design interviews demand a deep understanding of systems, their robustness, functionality, and scalability.
- Design Fundamentals serve as the foundation for systems design interviews, just as data structures are fundamental for coding interviews.

**Why Design Fundamentals Matter 🧐**
- Design Fundamentals encompass various topics such as System architecture 🏛️, Availability ⏰, Databases 🗄️, Load Balancing ⚖️, Caching 🚀, and HTTP .
- They are indispensable for tackling Systems Design interview questions effectively.

## Exploring Design Fundamentals 🕵️
Building scalable, production-ready applications is both an art 🎨 and a science 🧪. It requires knowledge across various computer engineering topics and the ability to make smart design choices. Mastery of these disciplines can transform you into a Systems Expert 🌟.

**How Systems Design Interviews Work 🤔**
- Systems Design interview questions are intentionally vague and must be explored in-depth.
- Interviewees must ask questions, understand system requirements, and demonstrate fundamental Systems Design knowledge.
- Unlike coding interviews with objective solutions, Systems Design interviews involve subjective solutions that require confident justifications.

**Categories of Design Fundamentals 📚**
- Design Fundamentals can be categorized into four important groups that build upon each other.
  - Foundational Knowledge 🏢: Understanding concepts like the client-server model  and network protocols 📡.
  - Key Characteristics of Systems : Grasping attributes like availability ⏰, throughput 🚀, redundancy ♻️, and consistency 🤝.
  - Actual Components of a System ⚙️: Familiarity with components like load balancers ⚖️, caches 🗄️, and proxies 🔄.
  - Real Existing Products or Services 🛠️: Knowledge of tools such as Zookeeper 🦓, Redis 🗃️, and cloud services ☁️.

Mastering these design fundamentals is essential for addressing vague Systems Design interview questions effectively.

## The Client-Server Model 
At the core of modern networking is the client-server model, where clients 🖥️ request services from servers 🏢. Let's explore this concept by breaking down what happens when you visit a website .

**What Happens When You Visit a Website 🌍**
- Your web browser  acts as the client, and the website's server 🏢 is the server.
- Your browser initially sends a DNS query  to resolve the website's IP address .
- Once it has the IP address , it establishes a connection  with the server over HTTP .
- The server responds with the website's content , and your browser renders it.

**Understanding the Client-Server Model 🤝**
- The client-server model  is foundational for computer communication, driving how machines interact.
- IP addresses  and ports 🚪 play crucial roles in directing data between machines.
- Ports 🚪 are used to differentiate network services, like HTTP on port 80 or HTTPS on port 443.
- Network protocols 📡, like HTTP, govern the format and rules of data exchange.

**Why the Client-Server Model Matters 🌍**
- This model underpins global computer communication and modern technologies.
- Understanding it is crucial for designing scalable and efficient systems.

## Network Protocols 📡
Network protocols, such as IP, TCP, and HTTP, form the backbone of machine-to-machine communication. While they might seem complex, grasping their high-level concepts is essential for effective systems design.

**What Are Network Protocols? 📡**
- Network protocols are agreed-upon rules governing interactions between machines.
- They define the format, structure, and order of messages exchanged.
- Common network protocols include IP , TCP 🚚, UDP ⚠️, and HTTP .

**IP (Internet Protocol)**
- IP is the foundation of internet communication, providing unique addresses for machines.
- IP packets 📦 are the basic units of data transfer between machines.
- Packets consist of an IP header 📨 and a data payload 📦.
- Versions like IPv4 and IPv6 exist, with IPv4 being more prevalent.

**TCP (Transmission Control Protocol) 🚚**
- TCP builds on IP  and ensures ordered, reliable, and error-free data delivery.
- It establishes connections through handshakes 🤝, allowing machines to communicate.
- TCP handles data transfer and retransmission in case of packet loss.

**HTTP (HyperText Transfer Protocol)**
- HTTP operates atop TCP 🚚 and introduces the request-response paradigm.
- Machines communicate by sending HTTP requests  and receiving responses 📨.
- HTTP simplifies system development by providing a structured way to exchange data.

Understanding these protocols, especially HTTP , is vital for designing robust and efficient systems.

---
# Exploring Storage in Systems Design 📂

## Dive into the World of Information Storage 🌐

Information storage is a critical aspect of systems design. 🚀 It's a complex and vital topic that impacts how systems store and retrieve data, affecting their performance, reliability, and scalability.

### 🔑 Key Terms: 
Let's start by understanding four key terms related to storage:

1. **Databases** 📊
   - Databases are programs that record and query data.
   - They can use memory or disk for data storage.
   - Most databases need disk storage for data persistence, ensuring data remains intact through various system issues.

2. **Disk** 💽
   - Refers to Hard Disk Drives (HDD) or Solid-State Drives (SSD).
   - Data written to disk persists through power failures and crashes.
   - HDDs are cost-effective for long-term data storage, while SSDs offer faster data access but at a higher cost.

3. **Memory** 🧠
   - Short for Random Access Memory (RAM).
   - Data stored in memory is volatile and is lost when the process ends.

4. **Persistent Storage** 📦
   - Usually refers to disk storage.
   - It includes any storage that remains intact even if the managing process stops.

## Understanding the Role of Databases 📡

Databases play a crucial role in most systems, serving two primary purposes:

- **Data Storage:** They store, record, and save data.
- **Data Retrieval:** They allow data to be retrieved, read, and queried.

But here's the catch: databases are not magical black boxes floating in the cloud! 🎩☁️ Instead, a database is essentially a server—a computer like any other.

And the most crucial concept in storage is data **persistence**. Many assume that data stored in a database will survive system outages, but that's not always the case.

### Disk vs. Memory 🔄

When data is written to disk, it persists through system failures, just like saving a file on your computer. However, if data is stored in memory, it's lost when the process ends.

Why would anyone choose memory over disk? Simple: accessing data from memory is blazing fast compared to accessing it from disk.

Storage is a vast field within systems design, with countless database options. Each database comes with its unique features, trade-offs, and suitability for different use cases.

## 🌐 The Challenge of Distributed Storage

So far, we've discussed storing data on a single machine, but what if you want to prevent your entire system from crashing when that machine fails? This is where **distributed storage** comes into play. It's a complex challenge involving data distribution, replication, and ensuring consistency across distributed systems.

### Consistency Matters 🧩

Consistency refers to the up-to-dateness of data. When you access data from a distributed database, will you get the latest version or potentially stale data? Different databases offer various properties and guarantees, which come with their trade-offs.

The world of storage is diverse and intricate, with numerous database offerings, each tailored to specific needs. Your choice of database can profoundly impact your system's performance and resilience. 💪

# Mastering Latency and Throughput ⚡

## Lag in Systems: The Culprit of High Latency and Low Throughput 🕰️

If you've ever experienced frustrating lag in a video game, you've encountered the consequences of high latency and low throughput—something no one enjoys! 😡

### 🔑 Key Terms:

1. **Latency** ⏳
   - The time it takes for a particular operation to finish in a system.
   - Measured in units like milliseconds (ms).
   - Latency varies widely across different system components.

2. **Throughput** 🚀
   - It measures a system's capacity to handle operations in a given time period.
   - It's often expressed as the rate of data transfer, like gigabits per second (Gbps).
   - Throughput determines how many operations a system can handle in a fixed time frame.

## Demystifying Latency and Throughput 🚀

Latency and throughput are essential concepts in systems design, yet they're often misunderstood. Let's clarify them:

### Latency ⏳

- Latency is the time data takes to traverse a system, from one point to another.
- It applies to various aspects, such as network request latency and data access latency.
- Different system components have different latencies, and optimizing these latencies is a key consideration in system design.

**Examples of Latency:**
- Reading 1 MB from RAM: 250 μs (0.25 ms)
- Reading 1 MB from SSD: 1,000 μs (1 ms)
- Transfer 1 MB over Network: 10,000 μs (10 ms)
- Reading 1 MB from HDD: 20,000 μs (20 ms)
- Inter-Continental Round Trip: 150,000 μs (150 ms)

Latency is crucial in designing systems, as it impacts the user experience. Systems with high latency can result in laggy interactions, which is especially problematic in applications like online gaming.

### Throughput 🚀

- Throughput measures a system's capacity to handle operations in a given time period.
- It's often expressed as the rate of data transfer, like gigabits per second (Gbps).
- Throughput determines how many operations a system can handle in a fixed time frame.

**Boosting Throughput:**
Increasing throughput can be as simple as investing in better network infrastructure. However, blindly increasing throughput isn't always the best solution.

### Balancing Latency and Throughput 🎯

When designing systems, you'll need to make trade-offs between latency and throughput. Some systems require low latency to ensure near-instantaneous responses, while others prioritize high throughput to handle a large volume of requests.

**Remember:** Latency and throughput are related but not correlated. A system can have low latency in one aspect and low throughput in another, so it's essential to consider both when optimizing system performance. 💡

---
# Understanding Availability in Systems Design 💡

In systems design, **availability** is a critical concept that relates to how often a system is up and running. It's essential to consider because it impacts the user experience and the success of a service. 🌐

## What is Availability? 🔄

Think of availability as a system's resilience to failures. When a component, like a server or database, fails, does the entire system collapse, or can it continue functioning? This concept is often called **fault tolerance**.

Another perspective is to view availability as the percentage of time a system remains operational in a specific period, such as a month or a year, meeting its primary functions. It's vital for users to rely on a system being consistently accessible.

💡 Availability is a crucial consideration when designing systems, as it directly affects both end-users and system designers.

## Measuring Availability 📊

Availability is typically measured as a percentage of uptime in a year, but high percentages are crucial. Here's a quick breakdown:

- **Two Nines (99%)**: Equates to around 87.7 hours of downtime per year. Generally unacceptable for most services.
- **Three Nines (99.9%)**: Allows for roughly 8.8 hours of downtime per year.
- **Four Nines (99.99%)**: Only permits about 52.6 minutes of downtime per year.
- **Five Nines (99.999%)**: The gold standard, guaranteeing just 5.3 minutes of downtime per year.

The term **"nines"** signifies the number of nines appearing in the percentage, making it a standard way to discuss availability in the industry. Five nines (99.999%) is considered highly available.

⚡️ Keep in mind that even 90% availability isn't great, as it means about 36 days of downtime in a year, which is unacceptable for most services.

## Importance of Availability 🌟

Availability matters significantly because it can impact both customer satisfaction and a company's revenue. Service providers often formalize availability through **Service-Level Agreements (SLAs)**, which include guarantees about system availability.

SLAs consist of **Service-Level Objectives (SLOs)**, specific guarantees to customers. They provide peace of mind and set clear expectations.

💼 Major cloud service providers like Google Cloud Platform or Amazon Web Services offer SLAs, emphasizing the importance of availability.

However, achieving high availability involves trade-offs. It can be challenging and costly. Therefore, not all systems need to aim for five nines of availability.

When designing systems, consider what parts are critical and require high availability and which can tolerate some downtime.

## Improving Availability 🚀

To enhance availability, eliminate single points of failure by introducing **redundancy**. Redundancy involves duplicating components to ensure continued operation if one fails.

### Passive Redundancy 🔄

Passive redundancy means having multiple components at a given layer. If one fails, the others handle the load until the issue is resolved. Think of it as backup components ready to take over.

🛩️ An example is twin-engine airplanes. If one engine fails, the other can keep the plane flying safely.

### Active Redundancy 🏎️

Active redundancy is more complex. Multiple machines work together, with only one or a few handling traffic or tasks at a time. If one fails, the others detect the failure and take over.

🔄 Implementing redundancy is a key strategy to make systems highly available.

### Processes and Human Intervention 🤖

Remember that some failures may require human intervention. Establish rigorous processes to handle system failures promptly.

Availability is a vital consideration in systems design, impacting both user satisfaction and the success of a service. Designing for high availability requires thoughtful planning, redundancy, and robust processes to ensure a system remains reliable even in the face of failures. 🌟

---
# Caching in Systems Design 🚀

Caching is a fascinating topic in systems design, and it plays a crucial role in optimizing system performance. Let's delve into caching, break down key concepts, explore its various applications, and discuss some real-world examples.

## Key Terms 🔑

### Cache
- A cache is a tool, whether hardware or software, that stores data for quicker retrieval.
- It's often used to store responses to network requests or results of computationally-intensive operations.
- Keep in mind that data in a cache can become "stale" if not updated when the main data source changes.

### Cache Hit
- When the requested data is found in a cache.

### Cache Miss
- Occurs when the requested data could have been found in a cache but isn't, often due to system failures or design issues.

### Cache Eviction Policy
- This policy defines how data is removed or "evicted" from a cache.
- Popular policies include LRU (Least Recently Used), FIFO (First In, First Out), and LFU (Least Frequently Used).

### Content Delivery Network (CDN)
- A third-party service acting as a cache for your servers, distributed worldwide to reduce latency.
- CDNs, like Cloudflare and Google Cloud CDN, help deliver content quickly to users in various regions.

## Understanding Caching 🌐

Caching is a fundamental technique in systems design, commonly employed to enhance system performance. It's used to speed up operations, reduce latency, and improve the user experience.

### Where Can You Use Caching?

- **Client-Level Caching:** Clients can cache data to reduce the need for frequent server requests.
- **Server-Level Caching:** Servers can cache data fetched from databases to serve subsequent requests more swiftly.
- **Intermediate-Level Caching:** Caches can be placed between components within a system, optimizing data flow.
- **Hardware-Level Caching:** Modern computers employ hardware-level caching, such as CPU caches, for faster data retrieval.

Caching operates at multiple levels in a system, depending on the specific use case.

## Concrete Instances of Caching ✨

Caching proves valuable in various scenarios, primarily aimed at speeding up processes and avoiding redundant work:

1. **Network Requests:** Caching helps avoid frequent network requests by storing previous responses.
2. **Computationally-Intensive Operations:** Caching stores results to prevent re-computation of resource-intensive tasks.
3. **Scaling Data Access:** When multiple servers or clients access the same data, caching can reduce the load on the primary data source (e.g., a database).

## Real-World Examples of Caching 🏆

### AlgoExpert

- On AlgoExpert, the **questions list** is cached on the client side. This static content, which doesn't change often, is stored locally, reducing the need for repeated server requests.

- When users **run code** with AlgoExpert's solutions, the results are cached. Subsequent requests for the same code execution can retrieve cached data, significantly improving response times.

### YouTube Comments Section

- Imagine designing the **YouTube comments section**. Here, caching becomes complex due to mutable data (comments that can be edited).

- Two caching approaches are considered:
  - **Write Through Cache:** Updates both the cache and the main data source (e.g., database) simultaneously. Ensures consistency but requires extra database access.
  - **Write Back Cache:** Updates the cache immediately and asynchronously updates the main data source. Offers faster responses but introduces potential data staleness.

### Handling Data Staleness 🕰️

Caching introduces the challenge of dealing with data staleness, where cached data becomes outdated. Solutions depend on the specific use case and system requirements:

- **Single Cache:** In some cases, centralizing caching in a single cache (e.g., Redis) can mitigate staleness issues.

- **Use Case Considerations:** Determining when data staleness is acceptable is crucial. Some data may tolerate staleness, while others require real-time updates.

## Eviction Policies in Caching 🗑️

As caches have limited space and must handle data updates, eviction policies define how data is removed:

- **LRU (Least Recently Used):** Evicts the data that hasn't been accessed for the longest time.
- **LFU (Least Frequently Used):** Removes the data that has been accessed the least.
- **FIFO (First In, First Out):** Eliminates the oldest data in the cache.
- **Random Eviction:** Removes data randomly from the cache.

Choosing the right eviction policy depends on your specific system and its caching needs.

Caching is a powerful tool in systems design, but it comes with challenges like data staleness and eviction policies. Understanding your system's requirements and use cases is essential when implementing caching to ensure optimal performance and user experience. 🚀

---

*Notes for AlgoExpert's SystemsExpert videos.* 📚
