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

*Notes for AlgoExpert's SystemsExpert videos.* 📚
