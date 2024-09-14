# Who this is for 
This is to apply technology roles such as developers in FinTech company such as https://anna.money/

# Content of interview preparation

\-i- interview ANNA Python questions

# Mind map

* Asyhc  
  * Learn  
  * Coding coding coding  
  * Rehearsal   
* Tom questions  
* Read 3 times of this document 

Tips 

* Simple and clean code is most important not only for your toy product but also for enterprise project because it’s easy to write easy to read easy to maintain and easy to test  
* Using asyn , async with, await  
* Adding try except for error handing

---

## Preparation for engineer manager interview

<img width="1446" alt="image" src="https://github.com/user-attachments/assets/e06ca506-9f42-4e55-958a-df8e781772e2">


To succeed in an interview at a UK Fintech company like ANNA Money, it's crucial to demonstrate your deep technical expertise, leadership abilities, and alignment with the company's mission and culture. Here's how you could frame your answers and some likely system design questions:

### **Answering to Secure a High-Ranking Offer**

**1\. Demonstrate Technical Mastery:**

* **Example Answer:** *"With 20 years of experience in software development, I’ve led teams that have designed and implemented scalable, secure, and reliable systems in the fintech industry. One of my key contributions was architecting a microservices-based payment processing system that handled millions of transactions daily while ensuring compliance with stringent financial regulations."*

**2\. Emphasise Your Leadership and Mentorship:**

* **Example Answer:** *"Throughout my career, I’ve not only focused on delivering high-quality code but also on mentoring junior developers, fostering a culture of continuous learning, and driving innovation within my teams. At \[Your Previous Company\], I spearheaded the adoption of DevOps practices, which reduced deployment times by 50% and increased system reliability."*

**3\. Align with ANNA Money's Values and Vision:**

* **Example Answer:** *"I’m particularly excited about ANNA Money’s mission to simplify financial management for small businesses. My experience in building user-centric financial platforms aligns with your goal of providing intuitive and efficient solutions. I’m eager to contribute my expertise to drive innovation and help ANNA Money continue to lead in this space."*

**4\. Problem-Solving and Innovation:**

* **Example Answer:** *"I believe in approaching problems with a combination of creativity and data-driven insights. For instance, when faced with latency issues in a real-time transaction processing system, I implemented a novel caching mechanism that improved response times by 40% without compromising on data accuracy."*

**5\. Commitment to Continuous Improvement:**

* **Example Answer:** *"I’m a strong advocate of continuous improvement, \*-both at the personal and team levels. I regularly engage with the latest industry trends and technologies, such as AI-driven fraud detection and blockchain for secure transactions, and I’m always looking for opportunities to apply these advancements to create more robust and innovative financial solutions."*

### **Likely System Design Questions**

1. **Design a Scalable Payment Processing System:**  
   * *How would you design a payment processing system that can handle millions of transactions per day? Consider scalability, security, and fault tolerance.*  
2. **Design a Fraud Detection System:**  
   * *How would you design a system to detect fraudulent transactions in real-time? Discuss your approach to handling false positives, system latency, and scalability.*  
3. **Design an API Gateway:**  
   * *How would you design an API gateway for a microservices architecture that handles financial transactions? Consider aspects like security, rate limiting, and fault tolerance.*  
4. **Design a Notification System:**  
   * *Design a system that sends notifications (email, SMS, push notifications) to users about their transaction status. How would you ensure timely and reliable delivery of notifications?*  
5. **Design a Data Storage Solution for Financial Records:**  
   * *How would you design a data storage solution for storing financial records that need to be compliant with regulations like GDPR? Consider data integrity, security, and scalability.*  
6. **Design a Secure Authentication System:**  
   * *How would you design a secure authentication and authorization system for users accessing a fintech platform? Discuss your approach to multi-factor authentication, token management, and session security.*  
7. **Design a System for Real-Time Financial Reporting:**  
   * *How would you design a system that provides real-time financial reporting to users? Consider the challenges of data consistency, latency, and system performance.*  
8. **Design a Peer-to-Peer Payment System:**  
   * *How would you design a peer-to-peer payment system that integrates with multiple banks? Consider transaction speed, security, and user experience.*

For each of these questions, you should walk through your thought process, discuss trade-offs, and explain why you made certain design decisions. Demonstrating an understanding of fintech-specific challenges, such as compliance and security, will be crucial.

## Samples answer:

### **Ideal Answer:**

"I once worked on optimizing a Python-based reporting system that processed data from various upstream sources in different formats. We noticed that the batch data processing was unusually slow. To tackle this, I first isolated the root cause by profiling the application using Python’s built-in `cProfile` and Perfana, which indicated high I/O wait times and a bottleneck in the database access layer. I collaborated with the system manager to monitor CPU and memory usage through AWS CloudWatch. Further investigation with the ELK stack pointed to a particular SQL query as the culprit. The query was performing a full table scan, leading to excessive processing time. We resolved the issue by adding an index to the relevant columns, which improved query performance significantly. As a result, the batch processing time was reduced by over 40%, and the system's overall responsiveness improved."

"To build scalable, maintainable, and secure applications in a fintech environment, I start by focusing on the design stage. A well-thought-out architecture is key to ensuring scalability and reliability. I typically follow principles like modularity and separation of concerns to make the codebase easier to maintain and extend.

For scalability, I ensure that the application is designed to handle increased loads by using patterns like microservices and distributed systems. This allows different components of the application to scale independently. I also make use of asynchronous programming in Python, using frameworks like `asyncio` or libraries like `Celery`, to manage concurrent tasks efficiently.

Security is paramount in fintech, so I implement industry-standard practices like encryption of sensitive data, secure authentication methods, and thorough input validation to prevent common vulnerabilities like SQL injection and cross-site scripting. Additionally, I incorporate automated testing, including unit tests and integration tests, to catch issues early and ensure that changes do not introduce regressions.

For reliability, I use monitoring tools like Prometheus and ELK stack to track system performance and health. In case of failures, I implement robust error-handling mechanisms and fallbacks to ensure minimal disruption. I also leverage AWS services for their reliability and scalability features, like using RDS for managed databases and S3 for secure and scalable storage."

### **What's Done Well:**

* **Design Emphasis**: You correctly pointed out the importance of the design stage in building scalable and reliable applications.  
* **Security Awareness**: Mentioning encryption, secure authentication, and input validation demonstrates a strong understanding of the security requirements in fintech.  
* **Scalability Strategies**: You’ve included the use of microservices and asynchronous programming, which are key strategies for handling scale.

### **Areas for Improvement:**

* **Expand on Specific Techniques**: While you mentioned good practices, expanding on how you implement them (e.g., which encryption methods you use, how you structure microservices) would add more depth.  
* **Real-World Examples**: If you have specific examples of projects where you implemented these practices, mentioning them briefly would strengthen your answer.  
* **Focus on Reliability**: You could add more on reliability, such as how you handle disaster recovery, data consistency, or how you plan for failover scenarios.

### **Ideal Answer:**

"In a fintech environment where security, **scalability**, and reliability are critical, I start by designing the application architecture with these factors in mind. I follow principles like modularity and separation of concerns to create a codebase that is easy to maintain and extend. For scalability, I use microservices architecture and distributed systems, allowing different components to scale independently. Additionally, I leverage asynchronous programming using Python’s `asyncio` and Celery to handle concurrent tasks efficiently.

**Security** is a top priority, so I implement encryption for sensitive data, secure authentication, and rigorous input validation to prevent vulnerabilities. I also adhere to the principle of least privilege and use secure coding practices to protect the system from attacks.

For **reliability**, I ensure robust error handling and logging, using monitoring tools like Prometheus and ELK to track system performance. I design the system to be fault-tolerant, with failover mechanisms and redundancy in place. Moreover, I leverage AWS services, such as RDS for managed databases and S3 for secure storage, to enhance both scalability and reliability. This approach allows me to build systems that can handle high loads, ensure data security, and provide a reliable user experience."

This response not only covers the key areas but also provides a clear, well-rounded approach that would resonate well with a system or development manager in a fintech environment.

### **Question: How do you design a good microservices architecture for a FinTech scalability-focused application? What do you bear in mind?**

**Answer:** "When designing a microservices architecture for a FinTech application, scalability and reliability are top priorities. I follow several key principles:

1. **Service Isolation and Decoupling**: I ensure that each microservice is independently deployable and loosely coupled with other services. This allows services to scale independently based on their specific demand and reduces the risk of cascading failures.  
2. **Domain-Driven Design (DDD)**: I use DDD to model the business domains within the application, which helps in identifying the boundaries of each microservice. This ensures that each service is aligned with a specific business capability, making it easier to scale and manage.  
3. **Data Management**: I often use a polyglot persistence approach, where each microservice owns its database and chooses the most appropriate storage technology (SQL, NoSQL, etc.) for its needs. This reduces cross-service dependencies and improves scalability.  
4. **Asynchronous Communication**: For inter-service communication, I prefer asynchronous messaging systems like Apache Kafka or RabbitMQ. This approach helps in handling high traffic and ensures that the system remains responsive even under heavy loads.  
5. **API Gateway**: I implement an API Gateway as an entry point for all client requests. This helps in managing authentication, rate limiting, and request routing, which are crucial for scalability and security.  
6. **Monitoring and Logging**: I integrate centralized logging and monitoring tools like ELK Stack or Prometheus with Grafana to track service performance, detect anomalies, and ensure reliability.  
7. **Resilience and Fault Tolerance**: I incorporate resilience patterns like circuit breakers, retries with exponential backoff, and bulkheads to handle failures gracefully and prevent them from affecting the entire system.  
8. **Security Considerations**: Each microservice is secured using token-based authentication (like OAuth2) and mutual TLS for service-to-service communication. I also implement role-based access control (RBAC) to restrict access based on user roles.

By adhering to these principles, I can build a microservices architecture that not only scales efficiently but also ensures high availability and security, which are critical in a FinTech environment."

### **Question: Can you elaborate on which encryption technologies can be used to build a secure FinTech application?**

**Answer:** "In the FinTech industry, data security is paramount, and encryption plays a vital role in protecting sensitive information. The encryption technologies I typically use include:

1. **TLS (Transport Layer Security)**: I use TLS to secure data in transit between clients and servers. TLS ensures that the communication is encrypted and authenticated, preventing eavesdropping and man-in-the-middle attacks. It’s important to use the latest version of TLS (TLS 1.3) for enhanced security.  
2. **AES (Advanced Encryption Standard)**: For encrypting data at rest, I use AES, particularly AES-256, which is a symmetric key encryption standard widely recognized for its strength and efficiency. AES is used to encrypt sensitive data like customer information, financial transactions, and stored files.  
3. **RSA (Rivest-Shamir-Adleman)**: RSA is an asymmetric encryption algorithm that I use for secure key exchanges and digital signatures. It's particularly useful for encrypting small amounts of data, such as encryption keys, that can then be used to encrypt or decrypt larger datasets using AES.  
4. **HMAC (Hash-based Message Authentication Code)**: For ensuring data integrity and authenticity, I use HMAC with cryptographic hash functions like SHA-256. HMAC is crucial for verifying that data has not been altered during transmission and for authenticating the sender.  
5. **Tokenization and Masking**: To protect sensitive data like credit card numbers and personally identifiable information (PII), I use tokenization and data masking techniques. Tokenization replaces sensitive data with a token that cannot be reverse-engineered, while masking hides parts of the data (e.g., showing only the last four digits of a credit card).  
6. **Key Management**: I use a robust key management service (KMS) like AWS KMS or HashiCorp Vault to manage encryption keys securely. Proper key rotation, access control, and auditing are critical to ensuring that encryption keys remain secure over time.

By carefully selecting and implementing these encryption technologies, I can ensure that sensitive data in a FinTech application is well-protected, both at rest and in transit, which is essential for maintaining customer trust and complying with regulatory requirements."

### **Evaluation:**

Your answers are strong, as they provide detailed insights into both designing microservices and choosing encryption technologies in a FinTech context.

* **What's Done Well**:  
  * You covered key aspects like service isolation, data management, and resilience in the microservices answer, showing a deep understanding of scalability and reliability.  
  * In the encryption technologies answer, you provided a comprehensive overview of the main techniques used to secure data, demonstrating your knowledge of both symmetric and asymmetric encryption, as well as key management.  
* **Suggestions for Improvement**:  
  * For the microservices architecture, you could add a brief mention of how to handle data consistency in a distributed environment, such as using eventual consistency models or distributed transaction management if required.  
  * In the encryption answer, consider mentioning any compliance standards you follow (e.g., PCI DSS for payment processing) to show that you are aware of regulatory requirements in the FinTech space.

Overall, these responses would impress a system or development manager in an interview for a Senior Python Developer role, especially in a FinTech setting.

### **How RSA is Used in a Modern Payment System:**

**1\. Secure Key Exchange:** In a payment system, RSA is often used for secure key exchange. Since RSA is an asymmetric encryption algorithm, it uses a pair of keys: a public key and a private key.

* **Public Key**: This is shared openly and used to encrypt data.  
* **Private Key**: This is kept secret and used to decrypt data that was encrypted with the corresponding public key.

In a payment system, RSA can be used to securely exchange symmetric keys (like AES keys) between the client and the payment gateway. Symmetric keys are used for encrypting the actual transaction data because symmetric encryption (like AES) is faster than asymmetric encryption.

**2\. Digital Signatures:** RSA is also used to create digital signatures, which are essential in ensuring the authenticity and integrity of a transaction.

* When a payment transaction is initiated, the payment gateway can use RSA to create a digital signature with its private key. This signature is attached to the transaction data.  
* The receiving party (e.g., the merchant or a financial institution) can then use the payment gateway’s public key to verify the signature. If the signature is valid, it means the transaction data has not been tampered with and it indeed came from the payment gateway.

**3\. Protecting Sensitive Information:** RSA can also be used to encrypt sensitive information that needs to be securely transmitted between the client, payment processor, and bank. This could include things like:

* Credit card numbers  
* Customer personal data  
* Transaction details

### **Concrete Example:**

**Scenario**: Let’s say a customer is making an online purchase, and the payment gateway wants to securely process the payment.

1. **Step 1: Key Exchange for Symmetric Encryption**  
   * The payment gateway generates a symmetric AES key to encrypt the transaction data.  
   * The payment gateway then uses the customer’s public RSA key to encrypt this AES key.  
   * The encrypted AES key is sent to the customer’s device.  
2. **Step 2: Secure Transmission**  
   * The customer’s device receives the encrypted AES key and decrypts it using its private RSA key.  
   * Now, both the customer’s device and the payment gateway have the same AES key.  
   * The transaction data (like credit card details and purchase amount) is encrypted with this AES key and sent to the payment gateway.  
3. **Step 3: Digital Signature**  
   * To ensure the transaction’s integrity, the customer’s device creates a digital signature using its private RSA key.  
   * This signature is attached to the transaction data and sent to the payment gateway.  
4. **Step 4: Verification**  
   * The payment gateway receives the encrypted transaction data and the digital signature.  
   * It uses the customer’s public RSA key to verify the digital signature, ensuring the data hasn’t been tampered with.  
   * The payment gateway decrypts the transaction data using the AES key.  
5. **Step 5: Processing the Payment**  
   * Once verified, the payment gateway processes the payment by interacting with the bank.  
   * The bank might perform additional encryption and verification steps using similar mechanisms before finalizing the transaction.

**Outcome**: Throughout this process, RSA is instrumental in securely exchanging encryption keys, verifying the authenticity of the transaction, and protecting sensitive information, ensuring that the payment is secure, reliable, and cannot be intercepted or altered by malicious parties.

### **Summary:**

In a modern fintech payment system, RSA plays a crucial role in secure key exchange, digital signatures, and protecting sensitive information. By using RSA to manage key exchanges and validate digital signatures, the system ensures that transactions are secure, authenticated, and protected against tampering, making it an essential component of secure online payments.

## Sample questions for system design

 I would ask a staff engineer candidate, along with brief outlines of what I'd look for in their answers:

1. Q: How would you design a scalable transaction processing system for our banking app?

A: I'd expect a discussion of:

* Microservices architecture  
* Message queues for asynchronous processing  
* Sharding strategies for the database  
* Caching layers  
* Eventual consistency model  
* Idempotency to handle duplicate transactions  
2. Q: Design a real-time fraud detection system for our financial transactions.

A: Key points to cover:

* Stream processing (e.g., Kafka Streams, Apache Flink)  
* Machine learning models for anomaly detection  
* Rule-based systems for known fraud patterns  
* Low-latency data stores (e.g., Redis, Aerospike)  
* Alerting and manual review workflow  
3. Q: How would you architect a system to handle regulatory reporting requirements?

A: Important aspects:

* Data warehousing solution  
* ETL processes  
* Data integrity and audit trails  
* Encryption and access controls  
* Automated report generation  
* Version control for reporting logic  
4. Q: Design a high-availability solution for our core banking services.

A: Expected topics:

* Multi-region deployment  
* Load balancing and failover mechanisms  
* Database replication strategies  
* Circuit breakers and bulkheads  
* Disaster recovery plans  
* Monitoring and alerting systems  
5. Q: How would you approach building a secure API gateway for our banking platform?

A: Key considerations:

* Authentication and authorization (OAuth, JWT)  
* Rate limiting and throttling  
* Request validation and sanitization  
* Encryption (TLS/SSL)  
* API versioning strategy  
* Logging and monitoring  
6. Q: Design a system for real-time account balance updates across multiple channels (app, web, ATM).

A: Important points:

* Event-driven architecture  
* Concurrency control mechanisms  
* Caching strategies  
* Consistency models (e.g., read-your-writes consistency)  
* Push notifications for real-time updates  
* Conflict resolution strategies  
7. Q: How would you design a system to handle scheduled payments and standing orders?

A: Aspects to cover:

* Job scheduling systems (e.g., Quartz, Airflow)  
* Retry mechanisms for failed payments  
* Handling timezone differences  
* Scalability for large volumes of scheduled tasks  
* Audit logging for compliance  
* User notification systems

These questions cover a range of critical areas for a fintech company like ANNA Money. I'd be looking for candidates to demonstrate deep technical knowledge, an understanding of financial industry requirements, and the ability to design scalable, secure, and reliable systems.

### Designing a Scalable Payment Processing System

*To design a payment processing system capable of handling millions of transactions per day, my approach would focus on scalability, security, and fault tolerance, ensuring that the system not only meets the immediate demands but is also future-proof.*

### **1\. System Architecture:**

* **Microservices-Based Architecture:** *I would architect the system using a microservices-based approach. This allows each service to scale independently based on demand, ensuring that the system remains responsive under heavy load. Key services would include Payment Gateway, Transaction Processor, Fraud Detection, Notification, and Reconciliation.*  
* **Event-Driven Architecture:** *To handle high transaction volumes efficiently, I’d leverage an event-driven architecture using message queues like Kafka or RabbitMQ. This decouples services, enabling asynchronous processing and reducing the risk of bottlenecks. Each transaction event would be processed in stages, allowing for horizontal scaling of services that need to handle high throughput.*

### **2\. Scalability:**

* **Auto-Scaling and Load Balancing:** *Auto-scaling policies would be implemented across the microservices to handle dynamic traffic patterns. Load balancers would be employed to distribute traffic evenly across instances, preventing any single service from becoming a bottleneck.*  
* **Database Sharding and Partitioning:** *To ensure the database can handle the scale, I would implement sharding and partitioning strategies. This would allow the database to distribute the load across multiple nodes, improving read/write performance. For critical data, like transaction records, I’d use a distributed database like Cassandra or a cloud-native solution like Amazon Aurora.*  
* **Caching:** *For frequently accessed data, such as transaction statuses or user account information, I’d incorporate an in-memory caching layer using Redis or Memcached. This reduces database load and speeds up response times for users.*

### **3\. Security:**

* **Data Encryption:** *Security is paramount in payment processing. I’d ensure that all sensitive data, both at rest and in transit, is encrypted using industry-standard protocols like AES-256 and TLS 1.2/1.3. This protects against unauthorized access and data breaches.*  
* **Tokenization:** *To further enhance security, I’d implement tokenization for handling payment details. Actual payment information would be stored securely, while only tokens are used during transactions, reducing the risk if data is compromised.*  
* **Access Control and Monitoring:** *Role-based access control (RBAC) would be enforced across the system to limit access to sensitive information based on the principle of least privilege. Additionally, continuous monitoring and anomaly detection would be in place to identify and respond to potential security threats in real time.*

### **4\. Fault Tolerance and High Availability:**

* **Redundancy and Replication:** *To ensure fault tolerance, I’d design the system with redundancy at every layer. This includes replicating databases across multiple geographic regions to protect against regional failures and using multiple instances of critical services with active-active or active-passive failover configurations.*  
* **Graceful Degradation:** *In the event of a partial system failure, the architecture would support graceful degradation. For example, if the fraud detection service is down, transactions could still proceed but be flagged for later review. This ensures continuity of service even in adverse conditions.*  
* **Disaster Recovery:** *I would implement a comprehensive disaster recovery strategy, including regular backups, automated failover mechanisms, and disaster recovery drills. The aim would be to minimize downtime and data loss in the event of catastrophic failures.*

### **5\. Monitoring and Observability:**

* **Real-Time Monitoring and Alerts:** *I would set up comprehensive monitoring using tools like Prometheus and Grafana, coupled with real-time alerting systems. This ensures that any issues are detected and addressed proactively before they impact users.*  
* **Logging and Tracing:** *Distributed tracing and logging would be integral to the system, providing end-to-end visibility of transactions. This aids in both real-time issue resolution and long-term system optimization.*

### **6\. Compliance and Auditing:**

* **Regulatory Compliance:** *Given the financial nature of the system, it would be designed to comply with all relevant regulations, such as PCI DSS for payment processing and GDPR for data protection. Auditing capabilities would be built into the system to ensure traceability and accountability for every transaction.*  
* **Audit Logs:** *Comprehensive audit logs would be maintained for all critical operations, ensuring that any anomalies can be traced back to their source. These logs would be stored securely and accessible only to authorized personnel.*

### **Conclusion:**

*By focusing on these key areas, the payment processing system would be able to scale efficiently, ensure security, and maintain high availability, all while being adaptable to future growth and regulatory requirements. This approach aligns with ANNA Money’s commitment to providing reliable and innovative financial solutions to its customers.*

---

Certainly\! Here’s an elaboration on fraud detection with a real-world example to provide a comprehensive answer:

\---

\#\#\# \*\*Fraud Detection in a Payment Processing System\*\*

\*\*Overview:\*\*  
Fraud detection is critical in a payment processing system to protect both the business and its customers from fraudulent activities. A real-time fraud detection system leverages machine learning algorithms to analyze transaction patterns, identify anomalies, and implement risk scoring to prevent fraudulent transactions before they are processed.

\*\*Real-World Example:\*\*

\*\*1. \*\*Machine Learning Algorithms for Fraud Detection:\*\*  
   \- \*\*Algorithm Selection:\*\* To build an effective fraud detection system, I would use a combination of supervised and unsupervised machine learning algorithms. Supervised learning algorithms, such as Random Forests or Gradient Boosting Machines, can be trained on historical transaction data labeled as either “fraudulent” or “legitimate” to predict the likelihood of a new transaction being fraudulent. Unsupervised learning algorithms, such as Isolation Forests or Autoencoders, can be used to detect anomalies in transactions where labels are not available.  
   \- \*\*Training the Model:\*\* For instance, consider a model trained on transaction data from a large e-commerce platform. The dataset might include features like transaction amount, location, time of day, and merchant information. The model learns patterns associated with legitimate transactions and flags deviations from these patterns as potentially fraudulent.

\*\*2. \*\*Analyzing Transaction Patterns:\*\*  
   \- \*\*Feature Engineering:\*\* Features are engineered to capture transaction behaviors that are indicative of fraud. For example, we might include features like the frequency of transactions from the same IP address, changes in spending patterns, or unusual transactions compared to historical behavior.  
   \- \*\*Real-Time Scoring:\*\* As a transaction occurs, the system scores it in real-time using the trained machine learning model. For example, if a user who typically makes small transactions suddenly attempts a large purchase from a foreign location, the model might assign a high fraud risk score to this transaction.

\*\*3. \*\*Risk Scoring and Decision Making:\*\*  
   \- \*\*Thresholds and Alerts:\*\* The fraud detection system applies thresholds to the risk scores to determine whether a transaction should be flagged for further review or blocked outright. For instance, a risk score above a certain threshold might trigger an alert for manual review by a fraud analyst or automatically block the transaction and notify the user.  
   \- \*\*Adaptive Learning:\*\* To continuously improve the system’s accuracy, the fraud detection system incorporates feedback from manual reviews and false positives. For example, if a transaction flagged as fraudulent is later confirmed as legitimate, this feedback is used to retrain the model and adjust thresholds, enhancing the system's precision over time.

\*\*4. \*\*Integration with Other Systems:\*\*  
   \- \*\*Multi-Layered Approach:\*\* The fraud detection system is integrated with other components of the payment processing system, such as authentication and authorization services. For example, if a high-risk transaction is detected, the system might require additional verification steps, such as multi-factor authentication, before processing the payment.  
   \- \*\*Collaboration with External Services:\*\* The system can also integrate with external fraud detection services and databases to enhance its capabilities. For example, it might cross-reference transactions with known fraud databases or leverage industry-wide threat intelligence to identify emerging fraud patterns.

\*\*5. \*\*Example Scenario:\*\*

Consider a payment processing system for an online retail platform that implements this fraud detection approach. One day, the system detects a transaction from a new user who is making an unusually large purchase and is shipping to an address that is different from their billing address. The transaction is flagged by the machine learning model due to its deviation from typical spending patterns and high-risk indicators.

\*\*Action Taken:\*\*  
\- The system immediately blocks the transaction and sends an alert to the fraud prevention team.  
\- The user is contacted to verify the transaction. If verified, the system updates its fraud model with this new data.  
\- If the transaction is confirmed to be fraudulent, the fraud team takes further actions, such as investigating the source of the fraudulent activity and updating the fraud detection rules to prevent similar cases in the future.

\*\*Conclusion:\*\*

By employing machine learning algorithms for real-time fraud detection, analyzing transaction patterns, and integrating with other systems, we can effectively mitigate the risk of fraudulent transactions. This approach not only protects the integrity of the payment processing system but also ensures a secure and trustworthy experience for users.

\---

This answer provides a detailed explanation of how a real-time fraud detection system operates, using a practical example to illustrate the concepts and techniques involved.Certainly\! Here’s an elaboration on fraud detection with a real-world example to provide a comprehensive answer:

\---

\#\#\# \*\*Fraud Detection in a Payment Processing System\*\*

\*\*Overview:\*\*  
Fraud detection is critical in a payment processing system to protect both the business and its customers from fraudulent activities. A real-time fraud detection system leverages machine learning algorithms to analyze transaction patterns, identify anomalies, and implement risk scoring to prevent fraudulent transactions before they are processed.

\*\*Real-World Example:\*\*

\*\*1. \*\*Machine Learning Algorithms for Fraud Detection:\*\*  
   \- \*\*Algorithm Selection:\*\* To build an effective fraud detection system, I would use a combination of supervised and unsupervised machine learning algorithms. Supervised learning algorithms, such as Random Forests or Gradient Boosting Machines, can be trained on historical transaction data labeled as either “fraudulent” or “legitimate” to predict the likelihood of a new transaction being fraudulent. Unsupervised learning algorithms, such as Isolation Forests or Autoencoders, can be used to detect anomalies in transactions where labels are not available.  
   \- \*\*Training the Model:\*\* For instance, consider a model trained on transaction data from a large e-commerce platform. The dataset might include features like transaction amount, location, time of day, and merchant information. The model learns patterns associated with legitimate transactions and flags deviations from these patterns as potentially fraudulent.

\*\*2. \*\*Analyzing Transaction Patterns:\*\*  
   \- \*\*Feature Engineering:\*\* Features are engineered to capture transaction behaviors that are indicative of fraud. For example, we might include features like the frequency of transactions from the same IP address, changes in spending patterns, or unusual transactions compared to historical behavior.  
   \- \*\*Real-Time Scoring:\*\* As a transaction occurs, the system scores it in real-time using the trained machine learning model. For example, if a user who typically makes small transactions suddenly attempts a large purchase from a foreign location, the model might assign a high fraud risk score to this transaction.

\*\*3. \*\*Risk Scoring and Decision Making:\*\*  
   \- \*\*Thresholds and Alerts:\*\* The fraud detection system applies thresholds to the risk scores to determine whether a transaction should be flagged for further review or blocked outright. For instance, a risk score above a certain threshold might trigger an alert for manual review by a fraud analyst or automatically block the transaction and notify the user.  
   \- \*\*Adaptive Learning:\*\* To continuously improve the system’s accuracy, the fraud detection system incorporates feedback from manual reviews and false positives. For example, if a transaction flagged as fraudulent is later confirmed as legitimate, this feedback is used to retrain the model and adjust thresholds, enhancing the system's precision over time.

\*\*4. \*\*Integration with Other Systems:\*\*  
   \- \*\*Multi-Layered Approach:\*\* The fraud detection system is integrated with other components of the payment processing system, such as authentication and authorization services. For example, if a high-risk transaction is detected, the system might require additional verification steps, such as multi-factor authentication, before processing the payment.  
   \- \*\*Collaboration with External Services:\*\* The system can also integrate with external fraud detection services and databases to enhance its capabilities. For example, it might cross-reference transactions with known fraud databases or leverage industry-wide threat intelligence to identify emerging fraud patterns.

\*\*5. \*\*Example Scenario:\*\*

Consider a payment processing system for an online retail platform that implements this fraud detection approach. One day, the system detects a transaction from a new user who is making an unusually large purchase and is shipping to an address that is different from their billing address. The transaction is flagged by the machine learning model due to its deviation from typical spending patterns and high-risk indicators.

\*\*Action Taken:\*\*  
\- The system immediately blocks the transaction and sends an alert to the fraud prevention team.  
\- The user is contacted to verify the transaction. If verified, the system updates its fraud model with this new data.  
\- If the transaction is confirmed to be fraudulent, the fraud team takes further actions, such as investigating the source of the fraudulent activity and updating the fraud detection rules to prevent similar cases in the future.

\*\*Conclusion:\*\*

By employing machine learning algorithms for real-time fraud detection, analyzing transaction patterns, and integrating with other systems, we can effectively mitigate the risk of fraudulent transactions. This approach not only protects the integrity of the payment processing system but also ensures a secure and trustworthy experience for users.

\---

This answer provides a detailed explanation of how a real-time fraud detection system operates, using a practical example to illustrate the concepts and techniques involved.

---

# (1) Coding challenge

import asyncio  
import aiohttp  \# Async HTTP library

async def fetch\_data(url):  
    async with aiohttp.ClientSession() as session:  
        async with session.get(url) as response:  
            return await response.text()

async def main():  
    urls \= \['https://example.com/page1', 'https://example.com/page2', 'https://example.com/page3'\]  
      
    \# Create tasks for each URL  
    tasks \= \[fetch\_data(url) for url in urls\]  
      
    \# Run all tasks concurrently  
    results \= await asyncio.gather(\*tasks)  
      
    for result in results:  
        print(len(result))  \# Print the length of the fetched content

\# Start the event loop  
asyncio.run(main())

**Benefits**:

* `aiohttp` is used to make non-blocking HTTP requests.  
* `asyncio.gather` runs all fetch tasks concurrently, making the process significantly faster.

The core concepts in Python's asynchronous programming include **coroutines**, **event loops**, **tasks**, and **futures**. The `asyncio` module provides the necessary tools and APIs to implement these concepts in your code.

### **Key Concepts**

1. **Coroutines**: Functions defined with `async def`. They can be paused and resumed, allowing other coroutines to run during the wait time.  
2. **Event Loop**: The heart of asynchronous programming. It continuously checks for tasks that are ready to run and executes them.  
3. **Tasks**: Wrappers around coroutines that manage their execution.  
4. **Futures**: Objects representing a result that may not be available yet. They are used for managing the result of coroutines.

#### **Basics of Coroutines**

A coroutine is defined using the `async def` syntax. When called, it doesn't execute immediately but returns a coroutine object, which can be awaited later to actually run the function. This allows you to write code that can handle asynchronous I/O operations, like reading from a file or making a network request, without blocking the main thread.

**Explanation:**

* `async def`: This is how you define a coroutine.  
* `await`: This keyword is used to yield control back to the event loop, allowing other coroutines to run. It effectively pauses the coroutine until the awaited operation completes.  
* `asyncio.run()`: This function is used to run the coroutine. It handles the event loop creation and execution.

#### **Coroutine Lifecycle**

* **Pending:** The coroutine is created but not yet running.  
* **Running:** The coroutine is executing until it encounters an `await` or returns.  
* **Suspended:** The coroutine is paused at an `await` and will resume when the awaited task is complete.  
* **Completed:** The coroutine has finished execution either by returning a value or raising an exception.

When using `asyncio`, the concept of "workers" isn't the same as in traditional multi-threading or multi-processing models. Instead, `asyncio` operates with an event loop that can manage multiple asynchronous tasks concurrently. However, you can still increase the concurrency by optimizing how many tasks your event loop can handle and how they are scheduled

**Event Loop Creation:** When you call `asyncio.run(main())`, Python creates a new event loop.  
**Executing the Coroutine:** The `main()` coroutine is scheduled to run in this event loop.  
**Managing Execution:** The event loop manages the execution of the `main()` coroutine, as well as any other coroutines that it invokes (like those created by `asyncio.gather()`).  
**Cleaning Up:** After `main()` and all other coroutines have completed, the event loop is closed, and the function returns the result of `main()`.

### **`results = await asyncio.gather(*tasks)`**

#### **Overview**

`asyncio.gather(*tasks)` is a function that runs multiple coroutines concurrently and waits for all of them to complete. It returns a list of results once all the tasks have finished.

#### **How It Works**

* **Task Creation:** When you pass multiple coroutines (or tasks) to `asyncio.gather()`, it schedules them to run concurrently within the event loop.  
* **Concurrency:** The event loop runs these coroutines, switching between them whenever they reach an `await` point.  
* **Result Collection:** Once all coroutines have completed, `asyncio.gather()` collects and returns their results in a list.

#### Even loop

\# Manually creating and running an event loop   
loop \= asyncio.get\_event\_loop()   
loop.run\_until\_complete(main())   
loop.close()

#### Taks

#### **Tasks**

Tasks are used to run coroutines concurrently. They are created using `asyncio.create_task()`.

`async def task1():`  
    `await asyncio.sleep(1)`  
    `print("Task 1 completed")`

`async def task2():`  
    `await asyncio.sleep(2)`  
    `print("Task 2 completed")`

`async def main():`  
    `# Run tasks concurrently`  
    `await asyncio.gather(task1(), task2())`

`asyncio.run(main())`

#### Futures

#### **Futures**

Futures represent the result of an asynchronous operation that may not be available yet. You typically don't need to create futures directly, as tasks and coroutines handle them internally.

# (2) Potential questions

### Scale workers

* **AWS Elastic Load Balancing (ELB):** Automatically distribute incoming traffic across multiple EC2 instances.

**Example:** In Kubernetes, you might define an `HPA` (Horizontal Pod Autoscaler) that scales the number of pods based on CPU usage.

# (3)GIL

### Why Do We Have the GIL?

The GIL simplifies thread management and protects against race conditions and memory corruption in Python, making it easier for developers to write concurrent code safely. It was introduced when support for threading was added to Python in the early days of the language.

### Compatibility

Lots of Python packages (and the main Python interpreter, CPython) make heavy use of C extensions, which aren’t inherently thread-safe. It’s possible to get multiple threads to try and access the same resources, which can lead to extremely negative effects. The GIL made it safer to create and use C extensions, which in turn made it easier for developers in the 90s to start using Python to create software, driving adoption.

Without the GIL, multiple threads running concurrently could manipulate reference counts of objects simultaneously, leading to race conditions and memory corruption. The GIL acts as a safeguard, allowing only one thread to execute Python bytecode at a time, preventing these potential issues.

Threading and asynchronous processing with [`asyncio`](https://docs.python.org/3/library/asyncio.html?adobe_mc=MCMID%3D76939882016590140953202899526371252792%7CMCORGID%3DA8833BC75245AF9E0A490D4D%2540AdobeOrg%7CTS%3D1723626150) are both methods to improve performance, but only work for IO-bound operations. However, there are a couple of methods that work for CPU-bound operations.

Python supports multiprocessing through the [`multiprocessing` module](https://docs.python.org/3/library/multiprocessing.html?adobe_mc=MCMID%3D76939882016590140953202899526371252792%7CMCORGID%3DA8833BC75245AF9E0A490D4D%2540AdobeOrg%7CTS%3D1723626150), and it’s also possible to write Python-like code using [Cython](https://cython.org/?adobe_mc=MCMID%3D76939882016590140953202899526371252792%7CMCORGID%3DA8833BC75245AF9E0A490D4D%2540AdobeOrg%7CTS%3D1723626150) to improve performance. Both can improve the performance of CPU-bound operations, but they come with downsides.

#### Multiprocessing

Python's `multiprocessing` module lets you use multiple CPU cores by creating separate processes, each with its own Python interpreter and memory space. This is effective for CPU-bound tasks as it bypasses the GIL, which operates on threads, and lets you use the multiple cores on your machine for true parallel execution.

Unfortunately, creating multiple processes has a higher resource overhead compared to threads, resulting in increased memory usage and startup time. It’s also slower and more complicated to communicate between processes than between threads. Finally, processes don’t share memory by default, making it more challenging to share data between processes and synchronize them.

### How Does It Work?

The main important technique to allow the GIL to be removed without affecting the performance of single-threaded code is biased reference counting.

In biased reference counting, objects accessed by a single thread have their reference counts managed more efficiently than those accessed by multiple threads, providing a performance boost for single-threaded programs where most objects are used by just one thread. This means that the performance of no-GIL Python using this technique on single-threaded operations is comparable to regular Python, whilst multi-threaded CPU-bound Python programs are much faster\!

The project also makes no-GIL Python more efficient by deferring the reference counting process for top-level module objects that aren’t likely to change in a Python program, as well as designating some objects as “immortal” \- objects like `None` are never destroyed so don’t need to be counted. There are also changes in how memory is allocated for Python objects which makes it easier to allocate memory in a thread-safe way.

Sounds great\! So the question really becomes: when will we have access to no-GIL Python?

# (4)PIC DSS

The Payment Card Industry Data Security Standard (PCI DSS) is a set of security standards designed to ensure that all companies that accept, process, store, or transmit credit card information maintain a secure environment. It was created by major credit card companies, including Visa, MasterCard, American Express, Discover, and JCB, through the Payment Card Industry Security Standards Council (PCI SSC).

### **Key Objectives of PCI DSS:**

1. **Build and Maintain a Secure Network and Systems:**  
   * Install and maintain a firewall configuration to protect cardholder data.  
   * Do not use vendor-supplied defaults for system passwords and other security parameters.  
2. **Protect Cardholder Data:**  
   * Protect stored cardholder data.  
   * Encrypt transmission of cardholder data across open, public networks.  
3. **Maintain a Vulnerability Management Program:**  
   * Protect all systems against malware and regularly update antivirus software or programs.  
   * Develop and maintain secure systems and applications.  
4. **Implement Strong Access Control Measures:**  
   * Restrict access to cardholder data by business need-to-know.  
   * Identify and authenticate access to system components.  
   * Restrict physical access to cardholder data.  
5. **Regularly Monitor and Test Networks:**  
   * Track and monitor all access to network resources and cardholder data.  
   * Regularly test security systems and processes.  
6. **Maintain an Information Security Policy:**  
   * Maintain a policy that addresses information security for all personnel.

As a senior developer in a payment tech fintech company, implementing PCI DSS compliance requires both an understanding of the technical aspects of the standards and the ability to apply best practices in your coding and development processes. Here are key points and coding practices to consider:

### **1\. Data Encryption**

* **At Rest:** Ensure that sensitive cardholder data (e.g., PAN, CVV) is encrypted when stored. Use strong encryption algorithms like AES-256.  
* **In Transit:** Use TLS (Transport Layer Security) to encrypt data transmitted across open networks. Avoid older versions of SSL, as they are no longer considered secure.

### **2\. Tokenization**

* Replace sensitive cardholder data with a token that can be used in your systems without exposing the actual data. This minimizes the storage of sensitive information and reduces the scope of PCI DSS compliance.

### **3\. Secure Coding Practices**

* **Input Validation:** Implement strong input validation to prevent common attacks like SQL injection and cross-site scripting (XSS). Use prepared statements and parameterized queries.  
* **Error Handling:** Ensure that errors and exceptions do not leak sensitive information. Log error details securely without exposing them to the user interface.  
* **Code Review:** Regularly perform peer code reviews focused on security. Utilize static analysis tools to catch potential vulnerabilities early.

### **4\. Access Control**

* **Principle of Least Privilege:** Ensure that users and systems have the minimum level of access necessary to perform their roles. Implement role-based access control (RBAC).  
* **Authentication:** Use strong authentication mechanisms, such as multi-factor authentication (MFA), for accessing systems that handle cardholder data.

### **5\. Logging and Monitoring**

* Implement detailed logging for all access to cardholder data and critical system components. Ensure logs are protected from unauthorized access and stored securely.  
* Use monitoring tools to detect and respond to suspicious activity in real-time. Set up alerts for unusual access patterns.

### **6\. Regular Security Testing**

* **Vulnerability Scanning:** Conduct regular vulnerability scans on your systems to identify potential weaknesses.  
* **Penetration Testing:** Perform penetration testing to simulate real-world attacks and assess your defenses.  
* **Patch Management:** Ensure timely application of security patches to all systems and software.

### **7\. Secure Development Lifecycle (SDLC)**

* Integrate security considerations into every phase of the software development lifecycle. From design to deployment, ensure that security is a primary focus.  
* Use automated tools to enforce security policies during the build and deployment processes.

### **8\. Compliance Documentation**

* Maintain comprehensive documentation of your security controls and practices. This documentation will be crucial during PCI DSS audits and assessments.  
* Document data flow diagrams to demonstrate how cardholder data moves through your systems and where it is stored or transmitted.

### **9\. Vendor and Third-Party Management**

* Ensure that any third-party services or vendors you use comply with PCI DSS standards. Require proof of compliance, such as an Attestation of Compliance (AOC), before integrating their services.

### **10\. Continuous Education and Training**

* Provide regular training to your development team on secure coding practices and PCI DSS requirements. Stay updated on the latest security trends and threats in the payment industry.

By focusing on these areas, you can ensure that your systems are robust, secure, and compliant with PCI DSS standards, thereby protecting both your company and your customers from potential security breaches.

## (4.2)Code sample about security of payment system

### **Data Encryption**

#### **Encrypting Cardholder Data at Rest:**

python  
复制代码  
`from cryptography.fernet import Fernet`

`# Generate a key for encryption`  
`key = Fernet.generate_key()`  
`cipher_suite = Fernet(key)`

`# Encrypt the cardholder data`  
`card_number = "4111111111111111"`  
`encrypted_card_number = cipher_suite.encrypt(card_number.encode())`

`# Store the encrypted data`  
`with open("encrypted_card.txt", "wb") as file:`  
    `file.write(encrypted_card_number)`

`# Decrypting the card number when needed`  
`decrypted_card_number = cipher_suite.decrypt(encrypted_card_number).decode()`  
`print(f"Decrypted Card Number: {decrypted_card_number}")`

### **Tokenization**

#### **Replace Card Number with a Token:**

import uuid

def tokenize\_card(card\_number):  
    \# Generate a unique token  
    token \= str(uuid.uuid4())  
      
    \# Store the mapping between the token and card number securely  
    token\_map \= {token: card\_number}  
    return token, token\_map

card\_number \= "4111111111111111"  
token, token\_map \= tokenize\_card(card\_number)  
print(f"Token: {token}")

\# Retrieving the card number using the token  
retrieved\_card\_number \= token\_map\[token\]  
print(f"Retrieved Card Number: {retrieved\_card\_number}")

### **Input Validation**

#### **Prevent SQL Injection:**

python  
复制代码  
`import sqlite3`

`# Assume we have a database connection`  
`conn = sqlite3.connect('payment_db.sqlite')`  
`cursor = conn.cursor()`

`# Safe way to insert data using parameterized queries`  
`def insert_cardholder_data(card_number, cardholder_name):`  
    `query = "INSERT INTO cardholders (card_number, cardholder_name) VALUES (?, ?)"`  
    `cursor.execute(query, (card_number, cardholder_name))`  
    `conn.commit()`

`# Example usage`  
`insert_cardholder_data("4111111111111111", "John Doe")`

### **Access Control**

#### **Implementing Role-Based Access Control (RBAC):**

python  
复制代码  
`class User:`  
    `def __init__(self, username, role):`  
        `self.username = username`  
        `self.role = role`

    `def has_access(self, resource):`  
        `if resource in self.role.allowed_resources:`  
            `return True`  
        `return False`

`class Role:`  
    `def __init__(self, name, allowed_resources):`  
        `self.name = name`  
        `self.allowed_resources = allowed_resources`

`# Define roles`  
`admin_role = Role("admin", ["read_data", "write_data", "delete_data"])`  
`user_role = Role("user", ["read_data"])`

`# Assign roles to users`  
`admin = User("admin_user", admin_role)`  
`regular_user = User("regular_user", user_role)`

`# Check access`  
`print(admin.has_access("write_data"))  # True`  
`print(regular_user.has_access("write_data"))  # False`

### **Regular Security Testing**

#### **Example of Automated Security Testing in CI/CD:**

`# Install a static analysis tool, e.g., Bandit for Python`  
`pip install bandit`

`# Run Bandit against the codebase to find common security issues`  
`bandit -r /path/to/codebase`

### **Combining Fernet with Additional Security Measures**

To enhance security, consider combining Fernet with other techniques:

* **Tokenization:** Replace sensitive data with non-sensitive tokens.  
* **Masking:** Obfuscate sensitive data by replacing parts with characters (e.g., `xxxx-xxxx-xxxx-1234`).  
* **HMAC:** Calculate a hash-based message authentication code to verify data integrity.

import hmac  
import hashlib

def protect\_data(data, key):  
    \# Tokenize sensitive parts of data  
    tokenized\_data \= tokenize(data)  \# Hypothetical tokenization function

    \# Encrypt remaining data using Fernet  
    encrypted\_data \= cipher\_suite.encrypt(tokenized\_data.encode()).decode()

    \# Calculate HMAC  
    hmac\_value \= hmac.new(key, encrypted\_data.encode(), hashlib.sha256).hexdigest()

    return encrypted\_data, hmac\_value

As a staff coder, understanding the various key types used in cryptography is essential, especially when working on secure systems, such as those in payment technology. Here’s how you might explain the different key types—symmetric, asymmetric, and HMAC (Hash-based Message Authentication Code):

### **1\. Symmetric Key Cryptography:**

**Definition:**

* Symmetric key cryptography, also known as secret-key cryptography, uses the same key for both encryption and decryption. This means that both the sender and receiver must possess the same secret key and keep it secure.

**Characteristics:**

* **Speed:** Symmetric key algorithms are generally faster and more efficient than asymmetric ones, making them ideal for encrypting large amounts of data.  
* **Security Risk:** The main challenge with symmetric keys is securely distributing and managing the key. If the key is compromised, all communications encrypted with that key are also compromised.

**Common Algorithms:**

* **AES (Advanced Encryption Standard):** Widely used and considered secure for encrypting data.  
* **DES (Data Encryption Standard):** An older standard that has largely been replaced by AES due to security concerns.  
* **Blowfish, Twofish:** Other symmetric key algorithms used in various applications.

**Example Use Case:**

* **Encryption of Data at Rest:** AES is often used to encrypt sensitive data stored in databases or on disk, where the same key is used for both encryption and decryption.

python  
复制代码  
`from cryptography.hazmat.primitives.ciphers import Cipher, algorithms, modes`  
`from cryptography.hazmat.backends import default_backend`

`key = b'sixteen byte key'`  
`iv = b'sixteen byte iv.'`  
`cipher = Cipher(algorithms.AES(key), modes.CFB(iv), backend=default_backend())`  
`encryptor = cipher.encryptor()`  
`ciphertext = encryptor.update(b'Sensitive data') + encryptor.finalize()`

### **2\. Asymmetric Key Cryptography:**

**Definition:**

* Asymmetric key cryptography, also known as public-key cryptography, uses a pair of keys: a public key and a private key. The public key is used for encryption, and the private key is used for decryption. The private key is kept secret, while the public key can be distributed widely.

**Characteristics:**

* **Security:** Asymmetric cryptography eliminates the key distribution problem of symmetric key cryptography since the public key can be shared openly.  
* **Performance:** It is computationally more intensive and slower than symmetric key cryptography, making it less suitable for encrypting large volumes of data.  
* **Key Pair:** The strength of the encryption relies on the mathematical relationship between the public and private keys.

**Common Algorithms:**

* **RSA (Rivest-Shamir-Adleman):** One of the most widely used public-key algorithms, often used for secure data transmission and digital signatures.  
* **ECC (Elliptic Curve Cryptography):** Offers similar security to RSA but with shorter key lengths, resulting in faster computations and lower resource usage.

**Example Use Case:**

* **Secure Key Exchange:** Asymmetric cryptography is commonly used in protocols like SSL/TLS, where it securely exchanges symmetric keys used for the bulk encryption of data during a session.

python  
复制代码  
`from cryptography.hazmat.primitives.asymmetric import rsa`  
`from cryptography.hazmat.primitives import serialization`

`# Generate a private key for use in asymmetric encryption`  
`private_key = rsa.generate_private_key(`  
    `public_exponent=65537,`  
    `key_size=2048,`  
`)`

`# Obtain the public key from the private key`  
`public_key = private_key.public_key()`

`# Example of serializing the public key to share it`  
`public_pem = public_key.public_bytes(`  
    `encoding=serialization.Encoding.PEM,`  
    `format=serialization.PublicFormat.SubjectPublicKeyInfo`  
`)`

### **3\. HMAC (Hash-based Message Authentication Code):**

**Definition:**

* HMAC is a type of message authentication code (MAC) that combines a cryptographic hash function with a secret key. It provides both data integrity and authenticity by ensuring that the message has not been altered and that it comes from a trusted source.

**Characteristics:**

* **Integrity:** HMAC ensures that the data has not been tampered with during transit.  
* **Authenticity:** By using a secret key, it ensures that the message originated from a legitimate source.  
* **Speed:** HMAC is relatively fast, as it primarily involves hash computations, making it suitable for real-time data authentication.

**Common Algorithms:**

* **HMAC-SHA256:** Uses the SHA-256 hashing algorithm for the HMAC process and is widely used in secure communication protocols.  
* **HMAC-MD5:** An older and less secure option that is now considered outdated due to vulnerabilities in MD5.

**Example Use Case:**

* **API Authentication:** HMAC is often used in APIs to authenticate requests, ensuring that the data sent in the request has not been modified and that it comes from an authorized client.

python  
复制代码  
`from cryptography.hazmat.primitives import hashes, hmac`

`key = b'secret_key'`  
`message = b'message to authenticate'`  
`h = hmac.HMAC(key, hashes.SHA256())`  
`h.update(message)`  
`mac = h.finalize()`

### **Summary:**

* **Symmetric Key Cryptography** is efficient for bulk data encryption but requires secure key management.  
* **Asymmetric Key Cryptography** is crucial for secure key exchange and digital signatures, though it's computationally intensive.  
* **HMAC** is essential for ensuring message integrity and authenticity, commonly used in API authentication and other secure communications.

When discussing these key types in an interview, it's important to explain not only how they work but also their practical applications and the trade-offs between them. Emphasizing your understanding of these concepts in real-world scenarios, especially within the context of payment technology, will demonstrate your depth of knowledge and experience as a staff engineer.

HMS and KMS

Google Cloud's Key Management Service (KMS) and Hardware Security Module (HSM) integrate is critical, especially in a fintech environment where security is paramount.

### **Overview of KMS and HSM:**

**1\. Google Cloud Key Management Service (KMS):**

* Google Cloud KMS is a fully managed service that allows you to manage cryptographic keys for your cloud services. It provides the ability to create, use, and manage keys securely within your cloud environment. This service supports symmetric and asymmetric keys, allowing for encryption, decryption, signing, and verification.  
* KMS simplifies key management by providing a centralized system where you can define, rotate, and audit keys, ensuring that your data is protected both at rest and in transit.

**2\. Hardware Security Module (HSM):**

* An HSM is a physical device that provides extra security for cryptographic keys. It is designed to protect and manage digital keys in a highly secure environment, safeguarding them from tampering and unauthorized access.  
* HSMs are often used in high-security environments, such as financial services, where compliance with strict regulatory requirements (e.g., PCI DSS) is necessary. They provide a higher level of security than software-based key storage.

# (5)System design questions

Q: Describe your experience with high-volume, scalable systems. A: I've worked on systems processing millions of transactions daily, using technologies like distributed databases, message queues, and microservices architecture to ensure scalability and reliability.

**Handling High Transaction Volumes:**

* **Context:** "In my role, I’ve worked on systems designed to process millions of transactions daily. This required building infrastructure that could handle spikes in load without compromising performance or reliability."  
* **Challenges:** "One of the main challenges was ensuring that the system could scale horizontally as the transaction volume grew. This meant designing a system that could add more nodes or resources dynamically, without requiring significant downtime or manual intervention."  
* **Solution:** "We used distributed databases like Cassandra and PostgreSQL in a clustered environment to ensure that data was replicated and available across multiple nodes. This setup allowed us to handle read and write operations efficiently, even under heavy load."  
* **Impact:** "By implementing this architecture, we were able to maintain sub-second response times, even during peak transaction periods, which was crucial for maintaining user trust and satisfaction."

**Ensuring Reliability with Message Queues:**

* **Context:** "Reliability is a key factor in high-volume systems, especially when dealing with financial transactions. We needed to ensure that every transaction was processed accurately and in order."  
* **Challenges:** "Dealing with network latency, potential message loss, and ensuring that transactions were not processed multiple times were significant challenges."  
* **Solution:** "We used message queues like Apache Kafka and RabbitMQ to decouple services and ensure that messages were delivered reliably. Kafka’s ability to persist messages allowed us to handle retries and ensure that messages weren’t lost, even in the event of a service failure."  
* **Impact:** "This approach improved the fault tolerance of our system. We achieved high reliability, with an uptime of over 99.99%, ensuring that transactions were processed accurately and in the correct order."

 **Scaling with Microservices Architecture:**

* **Context:** "To manage the complexity of a high-volume system, we adopted a microservices architecture. Each service was responsible for a specific piece of the business logic, allowing us to scale components independently."  
* **Challenges:** "One challenge was ensuring that services communicated efficiently, without introducing bottlenecks or single points of failure. We also had to manage data consistency across distributed services."  
* **Solution:** "We used RESTful APIs for synchronous communication and message queues for asynchronous communication between services. To manage data consistency, we implemented patterns like Saga for distributed transactions and ensured that each service had its own database (polyglot persistence) to reduce coupling."  
* **Impact:** "This architecture allowed us to scale specific parts of the system independently, optimizing resource usage and improving overall system performance. We also saw a reduction in deployment times, as each microservice could be deployed and scaled without affecting the entire system."

**Monitoring and Observability:**

* **Context:** "In high-volume systems, it’s crucial to have a strong monitoring and observability setup to identify and resolve issues quickly."  
* **Challenges:** "The main challenge was monitoring a system with multiple distributed components and ensuring that we had real-time insights into system performance and health."  
* **Solution:** "We implemented monitoring tools like Prometheus and Grafana for real-time metrics and dashboards, and used ELK Stack (Elasticsearch, Logstash, Kibana) for centralized logging. We also set up automated alerts for key performance indicators (KPIs) like transaction latency, error rates, and system resource usage."  
* **Impact:** "This setup enabled us to proactively identify and address issues before they affected end users, improving system reliability and performance. It also provided us with the data needed to continuously optimize the system."

## Transaction

Q: What's your approach to handling concurrent transactions? A: I implement proper locking mechanisms, use database transactions, and design systems to handle race conditions. I'm familiar with concepts like ACID properties and isolation levels.

### Saga pattern

implementing the saga pattern in a microservices-based payment system is crucial for maintaining data consistency across services.   
A Saga is a design pattern that helps manage distributed transactions across multiple services in a microservices architecture. 

Problem Statement

In a microservices architecture, each service is responsible for its own domain logic and data. When a business process involves multiple services, ensuring data consistency and integrity becomes a challenge. Traditional ACID (Atomicity, Consistency, Isolation, Durability) transactions are not feasible in a distributed environment, as they require a single, centralized transaction manager.

Saga Pattern

The Saga pattern addresses this challenge by breaking down a long-running business process into a series of local transactions, each executed by a separate service. Each local transaction is called a "saga step." If any saga step fails, the entire saga is rolled back, ensuring data consistency across services.

Here's a high-level overview of the Saga pattern:

1. Saga Initiation: A client initiates a business process by sending a request to the first service in the saga.  
2. Saga Steps: Each service executes its local transaction (saga step) and updates its own data. If a step fails, the saga is rolled back.  
3. Compensating Actions: If a saga step fails, a compensating action is executed to undo the effects of the previous steps.  
4. Saga Completion: If all saga steps complete successfully, the business process is considered complete.

For this example, we'll consider a simple payment process involving three microservices:

1. Order Service  
2. Payment Service  
3. Inventory Service

We'll use AWS Step Functions to orchestrate the saga, and AWS Lambda for our microservices. Here's a sample implementation:

First, let's define our Lambda functions for each service:

1. Order Service:

python  
Copy  
import boto3  
import json

def create\_order(event, context):  
    *\# Simulating order creation*  
    order\_id \= "ORD-" \+ str(event\['orderId'\])  
      
    *\# In a real scenario, you'd save this to a database*  
    return {  
        'orderId': order\_id,  
        'status': 'CREATED'  
    }

def cancel\_order(event, context):  
    *\# Simulating order cancellation*  
    order\_id \= event\['orderId'\]  
      
    *\# In a real scenario, you'd update the order status in the database*  
    return {  
        'orderId': order\_id,  
        'status': 'CANCELLED'

    }

2. Payment Service:

python  
Copy  
import boto3  
import json

def process\_payment(event, context):  
    *\# Simulating payment processing*  
    order\_id \= event\['orderId'\]  
    amount \= event\['amount'\]  
      
    *\# In a real scenario, you'd integrate with a payment gateway*  
    if amount \> 1000:  
        return {  
            'orderId': order\_id,  
            'status': 'PAYMENT\_FAILED'  
        }  
    else:  
        return {  
            'orderId': order\_id,  
            'status': 'PAYMENT\_PROCESSED'  
        }

def refund\_payment(event, context):  
    *\# Simulating payment refund*  
    order\_id \= event\['orderId'\]  
      
    *\# In a real scenario, you'd integrate with a payment gateway to process the refund*  
    return {  
        'orderId': order\_id,  
        'status': 'PAYMENT\_REFUNDED'

    }

3. Inventory Service:

python  
Copy  
import boto3  
import json

def update\_inventory(event, context):  
    *\# Simulating inventory update*  
    order\_id \= event\['orderId'\]  
      
    *\# In a real scenario, you'd update the inventory in the database*  
    return {  
        'orderId': order\_id,  
        'status': 'INVENTORY\_UPDATED'  
    }

def revert\_inventory(event, context):  
    *\# Simulating inventory revert*  
    order\_id \= event\['orderId'\]  
      
    *\# In a real scenario, you'd revert the inventory changes in the database*  
    return {  
        'orderId': order\_id,  
        'status': 'INVENTORY\_REVERTED'

    }

Now, let's define our Step Functions state machine to orchestrate the saga:

json  
Copy  
{  
  "Comment": "A simple payment processing saga",  
  "StartAt": "CreateOrder",  
  "States": {  
    "CreateOrder": {  
      "Type": "Task",  
      "Resource": "arn:aws:lambda:REGION:ACCOUNT\_ID:function:create\_order",  
      "Next": "ProcessPayment",  
      "Catch": \[  
        {  
          "ErrorEquals": \["States.ALL"\],  
          "Next": "CancelOrder"  
        }  
      \]  
    },  
    "ProcessPayment": {  
      "Type": "Task",  
      "Resource": "arn:aws:lambda:REGION:ACCOUNT\_ID:function:process\_payment",  
      "Next": "UpdateInventory",  
      "Catch": \[  
        {  
          "ErrorEquals": \["States.ALL"\],  
          "Next": "RefundPayment"  
        }  
      \]  
    },  
    "UpdateInventory": {  
      "Type": "Task",  
      "Resource": "arn:aws:lambda:REGION:ACCOUNT\_ID:function:update\_inventory",  
      "End": true,  
      "Catch": \[  
        {  
          "ErrorEquals": \["States.ALL"\],  
          "Next": "RevertInventory"  
        }  
      \]  
    },  
    "CancelOrder": {  
      "Type": "Task",  
      "Resource": "arn:aws:lambda:REGION:ACCOUNT\_ID:function:cancel\_order",  
      "End": true  
    },  
    "RefundPayment": {  
      "Type": "Task",  
      "Resource": "arn:aws:lambda:REGION:ACCOUNT\_ID:function:refund\_payment",  
      "Next": "CancelOrder"  
    },  
    "RevertInventory": {  
      "Type": "Task",  
      "Resource": "arn:aws:lambda:REGION:ACCOUNT\_ID:function:revert\_inventory",  
      "Next": "RefundPayment"  
    }  
  }

}

This Step Functions state machine implements the saga pattern by:

1. Starting with the CreateOrder step  
2. If successful, it moves to ProcessPayment  
3. If payment is successful, it updates the inventory  
4. If any step fails, it triggers the corresponding compensation action (CancelOrder, RefundPayment, RevertInventory)

To use this saga in your application:

1. Deploy the Lambda functions and the Step Functions state machine to your AWS account.  
2. When a new order comes in, start the Step Functions execution with the order details:

python  
Copy  
import boto3

def start\_payment\_saga(order\_id, amount):  
    client \= boto3.client('stepfunctions')  
      
    response \= client.start\_execution(  
        stateMachineArn\='arn:aws:states:REGION:ACCOUNT\_ID:stateMachine:PaymentSaga',  
        input\=json.dumps({  
            'orderId': order\_id,  
            'amount': amount  
        })  
    )  
    

    return response\['executionArn'\]

This implementation ensures that if any step in the payment process fails, the system will automatically roll back the previous steps, maintaining data consistency across all services.

**Option 2: Stateful Coordinator (AWS Step Functions with DynamoDB):**

* Centralized coordinator for complex sagas with multiple steps and retries.  
* Stores saga state in DynamoDB for persistence.  
* Offers better visibility and control over the saga.

### Q: How do you optimize database queries for large datasets? 

A: I use indexing strategies, query optimization techniques, caching mechanisms, and sometimes denormalization. I also consider partitioning for very large tables and use database-specific optimization tools.

### System capacity

Estimating System Capacity

To estimate the system capacity, you'll need to consider the following factors:

1. Traffic patterns: Analyze historical data to understand the average and peak traffic patterns, including the number of requests, transactions, and concurrent users.  
2. Resource utilization: Monitor CPU, memory, disk, and network utilization to identify bottlenecks and understand how resources are being consumed.  
3. Service level agreements (SLAs): Review SLAs to determine the acceptable response times, error rates, and throughput.  
4. System architecture: Understand the system's architecture, including the number of microservices, databases, and third-party dependencies.  
5. Scalability: Identify which components can be scaled horizontally (e.g., adding more instances) or vertically (e.g., increasing instance size).

Using these factors, you can estimate the system's capacity using various methods, such as:

1. Benchmarking: Run load tests to measure the system's performance under controlled conditions.  
2. Queueing theory: Apply mathematical models to analyze the system's behavior under different loads.  
3. Simulation: Use simulation tools to model the system's behavior and estimate capacity.

Handling Special Spike Events

To handle special spike events, such as holiday sales or unexpected traffic surges, consider the following strategies:

1. Autoscaling: Implement autoscaling mechanisms to dynamically adjust the number of instances or resources based on traffic demand.  
2. Load balancing: Use load balancers to distribute traffic across multiple instances or services.  
3. Caching: Implement caching mechanisms to reduce the load on databases and services.  
4. Content delivery networks (CDNs): Use CDNs to distribute static content and reduce the load on origin servers.  
5. Rate limiting: Implement rate limiting to prevent overwhelming the system with excessive traffic.  
6. Queue-based architectures: Design queue-based architectures to handle high volumes of requests and messages.  
7. Monitoring and alerting: Set up monitoring and alerting systems to detect anomalies and notify teams of potential issues.  
8. Capacity planning: Regularly review and update capacity plans to ensure the system can handle expected and unexpected traffic surges.

Tools and Techniques

Some popular tools and techniques for estimating system capacity and handling special spike events include:

1. Load testing tools: Apache JMeter, Gatling, Locust  
2. Monitoring and alerting tools: Prometheus, Grafana, New Relic, Datadog  
3. Autoscaling tools: AWS Auto Scaling, Kubernetes Horizontal Pod Autoscaling  
4. Queueing theory tools: Queueing theory libraries and frameworks, such as Queueing Theory Toolbox  
5. Simulation tools: SimPy, Simulation Studio  
6. Cloud providers' scalability features: AWS Lambda, Google Cloud Functions, Azure Functions

By using these tools and techniques, you can better estimate your system's capacity and develop strategies to handle special spike events, ensuring your microservice payment system remains reliable and scalable.

---

### Concurrency Async

When elaborating on your deep understanding of coroutines, event loops, and asynchronous context managers as a staff coder, it’s essential to not only explain the concepts but also provide concrete examples and real-world scenarios where you've applied them. Here’s how you might do that:

##### 1\. Understanding Coroutines:

* **Concept:** Coroutines are a special type of function in Python that can be paused and resumed, allowing you to write asynchronous code that doesn’t block the execution of other tasks. They are defined using `async def` and can await other asynchronous operations.  
* **Example Project:** In a high-performance web server, you might use coroutines to handle multiple client requests concurrently, without the overhead of threading or multiprocessing.

**Code Sample:**  
python  
复制代码  
`import asyncio`

`async def handle_client(reader, writer):`  
    `data = await reader.read(100)`  
    `message = data.decode()`  
    `print(f"Received {message!r}")`

    `response = f"Echo: {message}"`  
    `writer.write(response.encode())`  
    `await writer.drain()`

    `writer.close()`

`async def main():`  
    `server = await asyncio.start_server(handle_client, '127.0.0.1', 8888)`  
    `async with server:`  
        `await server.serve_forever()`

`asyncio.run(main())`

*   
* **Explanation:** In this example, `handle_client` is a coroutine that handles each client connection asynchronously. By using coroutines, the server can handle thousands of connections concurrently without blocking on I/O operations, ensuring high performance and scalability.

##### 2\. Event Loops:

* **Concept:** The event loop is the core of any asynchronous framework in Python, such as `asyncio`. It manages the execution of asynchronous tasks, scheduling them to run as their I/O operations complete.  
* **Example Project:** In a real-time messaging application, the event loop might be used to coordinate the sending and receiving of messages, ensuring that messages are delivered promptly even under heavy load.

**Code Sample:**  
python  
复制代码  
`import asyncio`

`async def send_message():`  
    `await asyncio.sleep(1)`  
    `print("Message sent")`

`async def receive_message():`  
    `await asyncio.sleep(2)`  
    `print("Message received")`

`async def main():`  
    `await asyncio.gather(send_message(), receive_message())`

`asyncio.run(main())`

*   
* **Explanation:** Here, the `asyncio.gather` function runs multiple coroutines concurrently on the event loop. The event loop manages these tasks, ensuring that `send_message` and `receive_message` run as soon as their respective delays are over, without blocking each other.

##### 3\. Asynchronous Context Managers:

* **Concept:** Asynchronous context managers allow you to manage resources that need to be cleaned up asynchronously, such as database connections or file handles in an asynchronous environment. They are defined using `async with`.  
* **Example Project:** Suppose you’re building a web scraper that needs to manage multiple database connections concurrently, ensuring that each connection is properly closed after use.

**Code Sample:**  
python  
复制代码  
`import asyncio`  
`import asyncpg`

`class DatabaseConnection:`  
    `def __init__(self, dsn):`  
        `self.dsn = dsn`  
        `self.connection = None`

    `async def __aenter__(self):`  
        `self.connection = await asyncpg.connect(self.dsn)`  
        `return self.connection`

    `async def __aexit__(self, exc_type, exc, tb):`  
        `await self.connection.close()`

`async def fetch_data(dsn):`  
    `async with DatabaseConnection(dsn) as conn:`  
        `result = await conn.fetch("SELECT * FROM my_table")`  
        `return result`

`async def main():`  
    `dsn = "postgres://user:password@localhost/dbname"`  
    `data = await fetch_data(dsn)`  
    `print(data)`

`asyncio.run(main())`

*   
* **Explanation:** In this code, `DatabaseConnection` is an asynchronous context manager that manages a database connection. When you use `async with`, it ensures that the connection is established before entering the block and is closed properly after exiting, even if an exception occurs. This pattern is crucial in high-concurrency environments where resources need to be managed efficiently.

##### Real-World Application:

* **Scalable Microservices:** In a microservices architecture, you might use coroutines and event loops to handle incoming requests asynchronously, allowing your services to scale effectively. For instance, an API gateway could use `asyncio` to route requests to different services concurrently, improving overall system throughput.  
* **IoT Systems:** In IoT applications, event loops can be used to manage the asynchronous communication between devices and servers. By handling sensor data asynchronously, you can process real-time data from thousands of devices without delays.

##### Conclusion:

Your deep understanding of coroutines, event loops, and asynchronous context managers enables you to build high-performance, scalable systems that can handle a large number of concurrent tasks efficiently. These skills are crucial in environments where low latency and high throughput are required, such as in financial systems, real-time analytics, or large-scale web services. Providing concrete examples of how you’ve applied these concepts in real projects will demonstrate your expertise and practical experience.

---

### API compatibility issue of microservices components

As a staff engineer, I'd be happy to elaborate on API versioning and backwards compatibility. This is a crucial aspect of maintaining a robust and scalable microservices architecture, especially in a fintech environment where stability and reliability are paramount. Let me break down the approach and add some concrete examples:

1. Semantic Versioning: We use semantic versioning (SemVer) for our APIs. This means our version numbers follow the pattern MAJOR.MINOR.PATCH.  
* MAJOR version increments for incompatible API changes  
* MINOR version for backwards-compatible functionality additions  
* PATCH version for backwards-compatible bug fixes

For example, moving from v1.2.3 to v2.0.0 would indicate breaking changes.

2. API Documentation: We maintain comprehensive documentation for each API version using tools like Swagger/OpenAPI. For example:

yaml  
Copy  
openapi: 3.0.0  
info:  
  title: Payment API  
  version: 1.2.3  
  description: API for processing payments  
paths:  
  /payments:  
    post:  
      summary: Create a new payment

      *\# ... rest of the specification*

We host this documentation on an internal developer portal, making it easy for teams to understand and integrate with our APIs.

3. Deprecation Policy: We implement a clear deprecation policy. For instance:  
* We support the last two major versions of an API  
* We give at least 6 months notice before deprecating an API version  
* We use HTTP headers to warn about upcoming deprecations:

Copy  
Deprecation: date="2025-01-01"  
Sunset: date="2025-07-01"

Link: \<https://api.example.com/v2/payments\>; rel="successor-version"

4. Extensibility: We design APIs with extensibility in mind. For example, using a fields parameter to allow clients to request only the data they need:

Copy

GET /api/v1/users/123?fields=id,name,email

5. Content Negotiation: We use content negotiation to allow clients to request specific versions or representations of our API. For example:

Copy

Accept: application/vnd.company.api+json;version=1.2

Or using URL versioning:

Copy

https://api.example.com/v1/payments

6. Backwards Compatibility Techniques:  
* We never remove fields from API responses; we only add new ones  
* When changing field types, we ensure the new type is a superset of the old one (e.g., changing a string to an enum)  
* We use nullable fields for new required parameters  
7. Feature Toggles: We implement feature toggles to gradually roll out new API functionality:

python  
Copy  
if feature\_flags.is\_enabled('new\_payment\_flow', user\_id\=request.user.id):  
    *\# New payment flow logic*  
else:

    *\# Old payment flow logic*

8. API Gateway: We use AWS API Gateway to manage multiple versions of our APIs, allowing us to route traffic to different backend services based on the requested version.  
9. Monitoring and Analytics: We track usage of different API versions to inform our deprecation strategy:

python  
Copy  
def process\_payment(request):  
    metrics.increment('api.payment.requests', tags\=\['version:v1'\])

    *\# Process payment logic*

10. ##### Communication: We maintain a changelog for each API version and communicate changes through multiple channels (email, Slack, developer portal) to ensure all stakeholders are informed.

11. ##### Testing: We maintain comprehensive test suites for each API version to ensure backwards compatibility:

python  
Copy  
def test\_payment\_api\_v1\_compatibility():  
    response \= client.post('/api/v1/payments', json\={  
        'amount': 100,  
        'currency': 'USD'  
    })  
    assert response.status\_code \== 200  
    assert 'id' in response.json()

    assert 'status' in response.json()

By implementing these strategies, we ensure that our APIs evolve in a controlled manner, minimising disruption to our clients while allowing us to innovate and improve our services. This approach is particularly important in a fintech environment where stability and reliability are crucial, and where regulatory compliance often requires maintaining older versions of APIs for extended periods.

---

# (6)Python

### Q: How do you stay updated with the latest Python developments and best practices?

 A: I regularly read Python Enhancement Proposals (PEPs), follow Python blogs and newsletters, attend conferences when possible, and participate in local Python user groups.

### Q: What's your experience with asynchronous programming in Python?

 A: I'm experienced with asyncio and have used it to build high-performance, non-blocking I/O applications. I understand concepts like coroutines, event loops, and asynchronous context managers.

### Q: How do you approach logging and monitoring in a production environment? 

A: I implement structured logging, use centralized log management systems, set up alerts for critical errors, and use monitoring tools to track system health and performance metrics.

### Self keyword

In Python, the `self` parameter is a reference to the instance of the class itself. It's used in methods that belong to a class to allow the method to access the instance's attributes and other methods.

### **When is `self` used?**

* **Instance Methods**: When you define a method inside a class, the first parameter of that method is typically `self`. This parameter must be the first in the method's definition and is automatically passed when you call the method on an instance of the class

Yes, it is possible to define methods within a class that do not use the `self` parameter, but these methods are not instance methods. Instead, they are typically classified as either **static methods** or **class methods**. Each type serves a different purpose:

### **Static Methods**

* **Definition**: Static methods do not access or modify the instance or class state. They behave like regular functions but belong to the class's namespace.  
* **Usage**: Use static methods when you need a method that performs a task but does not depend on instance or class attributes.

**Syntax**:  
python  
复制代码  
`class MyClass:`  
    `@staticmethod`  
    `def static_method(param1, param2):`  
        `print(f"Static method called with {param1} and {param2}")`

* `MyClass.static_method('arg1', 'arg2')  # Call without creating an instance`

# (7)Multithreading

Threads share the same memory space but can execute code simultaneously. This is useful for I/O-bound tasks but has limitations for CPU-bound tasks due to Python's Global Interpreter Lock (GIL).

### **Designing Multithreading for CPU-Bound Tasks**

For CPU-bound tasks, consider using multiprocessing instead of multithreading, as multiprocessing bypasses the GIL by using separate memory spaces for each process. However, if you must use multithreading, follow these principles:

1. **Task Granularity**  
   * Break down tasks into smaller units of work that can be executed concurrently. Ensure that the workload is substantial enough to benefit from multithreading.  
2. **Thread Safety**  
   * Protect shared resources using synchronization primitives like locks to avoid race conditions.  
3. **Thread Management**  
   * Create a pool of threads to manage and reuse threads efficiently. This can be done using `concurrent.futures.ThreadPoolExecutor`.

### **Example: Multithreading with CPU-Bound Tasks**

Here’s how to use multithreading for a CPU-bound task, like computing factorials:

python  
复制代码  
`import threading`  
`from concurrent.futures import ThreadPoolExecutor`  
`import time`

`# CPU-bound task`  
`def compute_factorial(n):`  
    `result = 1`  
    `for i in range(2, n + 1):`  
        `result *= i`  
    `return result`

`def worker(n):`  
    `print(f"Computing factorial of {n}...")`  
    `result = compute_factorial(n)`  
    `print(f"Factorial of {n} is {result}")`

`def main():`  
    `numbers = [10, 20, 30, 40, 50]`  
    `with ThreadPoolExecutor(max_workers=4) as executor:`  
        `futures = [executor.submit(worker, num) for num in numbers]`  
        `for future in futures:`  
            `future.result()  # Wait for all tasks to complete`

`if __name__ == "__main__":`  
    `start_time = time.time()`  
    `main()`  
    `print(f"Elapsed time: {time.time() - start_time:.2f} seconds")`

### **Explanation**

* **ThreadPoolExecutor:** Manages a pool of threads, allowing you to specify `max_workers` to control concurrency.  
* **`submit(worker, num)`:** Schedules the `worker` function to be run in a separate thread.  
* **`future.result()`:** Waits for the thread to finish and retrieves the result.  
* **`compute_factorial(n)`:** A CPU-bound task to compute factorials, used to demonstrate multithreading.

### **Multiprocessing Design for CPU-Bound Tasks**

For CPU-bound tasks, multiprocessing is often a better choice. It avoids the GIL by using separate processes, each with its own memory space.

### **Example: Multiprocessing with CPU-Bound Tasks**

Here’s an example of using multiprocessing to compute factorials:

python  
复制代码  
`import multiprocessing`  
`import time`

`def compute_factorial(n):`  
    `result = 1`  
    `for i in range(2, n + 1):`  
        `result *= i`  
    `return result`

`def worker(n):`  
    `print(f"Computing factorial of {n}...")`  
    `result = compute_factorial(n)`  
    `print(f"Factorial of {n} is {result}")`

`def main():`  
    `numbers = [10, 20, 30, 40, 50]`  
    `with multiprocessing.Pool(processes=4) as pool:`  
        `pool.map(worker, numbers)`

`if __name__ == "__main__":`  
    `start_time = time.time()`  
    `main()`  
    `print(f"Elapsed time: {time.time() - start_time:.2f} seconds")`

### **Explanation**

* **Pool:** Manages a pool of worker processes. You can specify the number of processes to run concurrently.  
* **`pool.map(worker, numbers)`:** Distributes the `worker` function across the list of numbers, with each process handling a separate part of the workload.  
* **`compute_factorial(n)`:** A CPU-bound task used for demonstration.

### **Choosing Between Multithreading and Multiprocessing**

* **Multithreading:** Suitable for I/O-bound tasks where threads can run concurrently during I/O operations. Be cautious with CPU-bound tasks due to GIL.  
* **Multiprocessing:** Ideal for CPU-bound tasks as it avoids the GIL and uses multiple processes to utilize multiple CPU cores effectively.

#### ThreadPool vs AsyncIO

##### 系统资源和效率考量

* Asyncio 在处理大量并发任务时，占用的系统资源相对较少，特别是内存方面。因为它的实现基于事件循环和协程切换，不需要为每个任务创建单独的操作系统线程。例如在一个服务器应用中，需要同时处理数万甚至数十万的客户端连接，如果使用传统的多线程方式，每个线程都需要占用一定的内存空间，很容易导致内存耗尽。而 Asyncio 可以在一个线程内高效地管理这些连接，大大降低了内存开销。  
* Threadpool 在一定程度上简化了对多线程的管理，但创建过多的线程可能会导致系统资源竞争加剧，上下文切换开销增大。如果任务数量远远超过 CPU 核心数，过多的线程可能会导致大部分时间都花费在线程切换上，而不是实际的任务执行上。例如在一个小型设备上运行的数据分析程序，系统资源有限，此时需要谨慎使用 Threadpool，避免创建过多线程影响性能。

* ##### 考虑任务类型：

  * 如果任务主要涉及 I/O 密集型操作（如网络请求、文件读写等）且不需要复杂的同步机制之间的协调，那么 Asyncio 通常是一个很好的选择。例如在构建一个高并发的网络爬虫时，Asyncio 可以高效地管理大量的并发网络连接，等待服务器响应的过程中不会阻塞其他连接的处理。以爬取网页为例，当同时发起成百上千个网络请求时，Asyncio 可以轻松地处理这些异步操作，减少等待时间。  
  * 对于 CPU 密集型任务且任务之间相对独立，可以考虑使用 Threadpool。比如进行大规模的数学计算或数据处理，像对大量图像进行复杂的滤镜处理等。如果有 1000 张图像需要应用一种计算量较大的滤镜算法，使用 Threadpool 可以将这些任务分配到多个线程中并行执行，从而加快处理速度。

### ThreadPoolExcutor vs ProcessPoolExecutor

When using `ThreadPoolExecutor` in Python, threads are managed by the operating system and can be scheduled to run on different CPU cores. However, there are some nuances to consider regarding thread execution and multicore CPUs:

### **1\. Thread Scheduling**

* **Operating System Scheduling**: The operating system's scheduler is responsible for assigning threads to CPU cores. In general, it tries to make efficient use of available cores, and threads from the `ThreadPoolExecutor` can be executed on separate cores.  
* **Concurrency vs. Parallelism**: Python threads, due to the Global Interpreter Lock (GIL) in CPython, do not always achieve true parallelism for CPU-bound tasks. The GIL allows only one thread to execute Python bytecode at a time, which means that threads may not fully utilize multiple cores for CPU-bound operations. For I/O-bound tasks, threads can still be effective, as they can perform I/O operations concurrently while waiting for external resources.

### **2\. `submit` vs. `map`**

**`submit`**: This method schedules a single callable (function) to be executed by a thread in the pool. It returns a `Future` object that can be used to retrieve the result or handle exceptions. With `submit`, you have finer control over individual task submissions and can manage each task’s execution more explicitly.  
python  
复制代码  
`from concurrent.futures import ThreadPoolExecutor`

`def task(n):`  
    `return n * n`

`with ThreadPoolExecutor(max_workers=4) as executor:`  
    `futures = [executor.submit(task, i) for i in range(10)]`  
    `results = [future.result() for future in futures]`

* 

**`map`**: This method applies a function to a list of inputs and returns an iterator that yields results. It handles task submission and result collection automatically. The `map` method is convenient for applying a function to multiple inputs in parallel and is often used for batch processing.  
python  
复制代码  
`from concurrent.futures import ThreadPoolExecutor`

`def task(n):`  
    `return n * n`

`with ThreadPoolExecutor(max_workers=4) as executor:`  
    `results = list(executor.map(task, range(10)))`

* 

### **3\. Effectiveness with Multicore CPUs**

* **I/O-bound Tasks**: For tasks that involve waiting for I/O operations (e.g., network requests, file operations), threads can effectively utilize multiple cores, as while one thread is waiting for I/O, others can continue processing.  
* **CPU-bound Tasks**: For CPU-bound tasks (e.g., heavy computation), Python threads might not fully utilize multiple cores due to the GIL in CPython. In such cases, you might want to use the `ProcessPoolExecutor` instead, which uses separate processes and can bypass the GIL, allowing true parallelism.

### **Summary**

* **ThreadPoolExecutor** can leverage multiple cores, but the degree of parallelism for CPU-bound tasks may be limited by the GIL.  
* **`submit`** and **`map`** both allow you to schedule tasks for execution, but they differ in how they handle task management and result retrieval.  
* For I/O-bound tasks, `ThreadPoolExecutor` is effective and can take advantage of multiple cores. For CPU-bound tasks requiring full core utilization, consider using `ProcessPoolExecutor`.

Using threads or processes effectively depends on the nature of your tasks and the level of parallelism you need.

---

As a senior staff coder, I'd be happy to discuss best practices and pitfalls for parallel programming and concurrency in modern Python, as well as explain the Global Interpreter Lock (GIL). Let's break this down into sections:

1\. Parallel Programming and Concurrency in Modern Python

Best Practices:  
1\. Use appropriate tools for the job:  
   \- \`threading\` for I/O-bound tasks  
   \- \`multiprocessing\` for CPU-bound tasks  
   \- \`asyncio\` for asynchronous programming

2\. Minimize shared state and use thread-safe data structures when necessary.

3\. Use high-level abstractions like \`concurrent.futures\` for simpler parallelism.

4\. Implement proper error handling and logging in parallel code.

5\. Use \`queue.Queue\` for thread-safe data exchange between threads.

6\. Consider using \`multiprocessing.Pool\` for easy parallelization of CPU-bound tasks.

Pitfalls:  
1\. Race conditions: Ensure proper synchronization when accessing shared resources.

2\. Deadlocks: Be cautious with lock ordering to avoid deadlocks.

3\. Overusing threads for CPU-bound tasks due to the GIL (more on this later).

4\. Neglecting to join threads or processes, leading to resource leaks.

5\. Assuming parallelism always improves performance without proper profiling.

6\. Overcomplicating simple tasks with unnecessary concurrency.

2\. Global Interpreter Lock (GIL)

The GIL is a mutex (lock) that protects access to Python objects, preventing multiple threads from executing Python bytecode at once. It's a fundamental aspect of CPython, the reference implementation of Python.

Understanding the GIL:  
1\. Purpose: The GIL simplifies memory management and allows non-thread-safe C extensions to work safely.

2\. Impact on threading: Only one thread can execute Python bytecode at a time, limiting true parallelism for CPU-bound tasks.

3\. I/O operations: The GIL is released during I/O operations, allowing other threads to run.

4\. Multiprocessing: The GIL doesn't affect separate processes, making multiprocessing effective for CPU-bound tasks.

5\. Performance implications: CPU-bound multi-threaded Python programs may not see performance improvements due to the GIL.

6\. Asynchronous programming: The GIL doesn't significantly impact asyncio-based concurrency, as it's based on cooperative multitasking.

7\. Alternative implementations: Some Python implementations (e.g., Jython, IronPython) don't have a GIL, but may lack compatibility with certain C extensions.

In modern Python development, understanding these concepts is crucial for writing efficient concurrent code. The choice between threading, multiprocessing, and asynchronous programming often depends on the nature of the task (I/O-bound vs. CPU-bound) and the specific requirements of your application.

Would you like me to elaborate on any specific aspect of parallel programming, concurrency, or the GIL in Python?​​​​​​​​​​​​​​​​

## Multithreading and multiprocessing

### **Multiprocessing:**

* **Use Case:** Best suited for CPU-bound tasks where the workload involves heavy computation that can benefit from parallel execution across multiple CPU cores.  
* **Overhead:** Each process has its memory space, so there's more overhead in terms of memory usage and inter-process communication.  
* **Python GIL:** The Global Interpreter Lock (GIL) does not impact multiprocessing because each process runs in its own Python interpreter.

### **Multithreading:**

* **Use Case:** Ideal for I/O-bound tasks, such as network requests, file I/O, or interacting with external services like AWS S3, where the program spends a lot of time waiting for I/O operations to complete.  
* **Overhead:** Threads share the same memory space, making them lighter than processes in terms of memory usage and faster for context switching.  
* **Python GIL:** The GIL can limit the effectiveness of multithreading for CPU-bound tasks but is generally not a concern for I/O-bound tasks.

### **For Your Case:**

Since the code involves making network calls to AWS S3, which is an I/O-bound task, **multithreading** is likely the better choice. Multithreading will allow you to handle multiple S3 requests concurrently, reducing overall execution time without the overhead associated with creating separate processes.

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAB8gAAAWCCAYAAAB4mL2wAACAAElEQVR4XuzdebBkZX03cP5MVSpVqXotK6kkWlKvxiQG35BgERVDIEqEoKKAICAGBIGAgoggsm+CCMgOQRQRJAjisMQAAo6KLMqirLLKDAPDDsM2bHOe11+bbk4/5869p+/t2326+/NJfUumn3Oe7nv79pnKfO/znFVWrFiRiqLoewAAAAAAAACgSVZRkAMAAAAAAAAwCRTkAAAAAAAAAEwEBTkAAAAAAAAAE0FBDgAAAAAAAMBEUJADAAAAAAAAMBEU5AAAAAAAAABMhFZBXk5edPc7AAAAAAAAADAMCnIAAAAAAAAAJoKCHAAAAAAAAICJoCAHAAAAAAAAYCIMvCCPAAAAAAAAAMCgKcgBAAAAAAAAmAgKcgAAAAAAAAAmgoIcAAAAAAAAgImgIAcAAAAAAABgIijIAQAAAAAAAJgICnIAAAAAAAAAJoKCHAAAAAAAAICJUCnIB1GUAwAAAAAAAMCgKcgBAAAAAAAAmAgKcgAAAAAAAAAmgoIcAAAAAAAAgImgIAcAAAAAAABgIijIAQAAAAAAAJgICnJosFfTsrQ8PZieL+4RkUEl3ZNeTIvSK+nJ/CMJAAAAAACMOAU5NMyK9FJ6Kl2bHizOTL8tThSRIWZRcVp6vLgqvZyeyD+qAAAAAADACFKQQ4PEqtXFxTdTXtKJyPCzLP06/8gCAAAAAAAjRkEODfFSejQ9UJyU8lJORJqT54o7848uAAAAAAAwQhTk0BBLiwtTXsaJSLOyqDg9FenV/OMLAAAAAACMCAU5NMDL6dGUF3Ei0swsK27NP8IAAAAAAMCIUJBDAzxT3JDyEk5EmplH0w/zjzAAAAAAADAiFOTQAI8Vl6W8hBORZmZxcWb+EQYAAAAAAEaEghwaYGnxg5SXcCLS1Jycf4QBAAAAAIARoSCHBni4OD9VSzgRaWoAAAAAAIDRpCCHBlCQi4xWAAAAAACA0aQghwZQkIuMVgAAAAAAgNGkIIcGUJCLjFYAAAAAAIDRpCCHBlCQi4xWAAAAAACA0bTSgnw+y3Kgm4JcZLQCAAAAAACMJgU5NICCXGS0AgAAAAAAjCYFOTSAglxktAIAAAAAAIwmBTk0gIJcZLQCAAAAAACMJgU5NICCXGS0AgAAAAAAjCYFOTSAglxktAIAAAAAAIwmBTk0gIJcZLQCAAAAAACMJgU5NICCXGS0AgAAAAAAjCYFOTSAglxktAIAAAAAAIymWgV5v0tyoJuCXOYz1y05LC28+4C08J4D0/0rTqiMDyI/f+Dg1mv46X0HVcZGMQAAAAAAwGhSkEMD9LMgv/OFr6fdDtgg7br/Bmn3gzesjMtw8+O79k877PmBtO/RG7feq3x8tplu3rf+9Z+mVVZZpZVfLj28cu4g8od/9Aed13Dvq8dXxkctAAAAAADAaFKQQwP0syC/8dEjOkVkJB8fp0TR+qsnj6w83uT8w3tW7bw3h//nFpXx2Wa6eRXk/Q8AAAAAADCaFOTQAAry3hJf4+4HbZj+5M//OG23+7qV8SanXFZ/6YiNKuOzzXTzKsj7HwAAAAAAYDQpyKEBFOS95cRzt+18faNWkJ9z1a6t1d4bbfWudNNjR1TGZ5vp5lWQ9z8AAAAAAMBoUpBDAyjIe8soF+TDyDgU5Pe+0vs58xkAAAAAAGA0KcihAZpakEeZetblu6TTL9oxXXHHfunul46tHJMnys+F9xyYTr94x3TS9z6dzvvZ7un2546pHDdVFt59QOv5Tj5/u3TRL/ZMty07qnJMfH2Hnrx55+vbbLv3pBseObyTus/Vzi1Pf61zbvw5vsb/+dXerddwwTVfSL9+6muVc8qJ8fL5kShzL7z+i605fnDtHq2vo3xcO/evOKF1fLzmn91/UCszFdjXP3RY59h4rdPN206vBXm83vja4/VfcuNeU74P0+XaxYem0xZ8Jp156c6t9zReT52C/NZnjkoLrtuj9QsQZ1/x2XTNokNajx94/KbpHav/Reu9z89p577XTkg/uffA9I0Ld2j9DF3924Nbj+XH9SsAAAAAAMBoUpBDAzStID/rR59Nb1r1DV3ztLPpNv9Y2cI7EmXmtrutUzm+nfd/eLX08wcOrpwXueyWL6c11vq/lXMi62+yeqssj+OiDM7H80Rhns8/Xf5uzbd0zo17d5eL3HaiYI7COz83Ui6ff/HwV9IOe36gMsf5V++eVlvjzZV5f3zX/q05Tvn+9p3H/s8b/2ilq6XvfOHrXXP/6PZ9p513qtc4XUEev9jw7nX+sjJfJLZvv/TXX66cU85J523Xui/8VOeW/5wX5FHAb7PrP1fOi5R/Lt7ytjdWvjdRgkeBnn/P29nr8I+ke14+rvJa5xoAAAAAAGA0KcihAZpUkH/68+tWSsY8UUbGyujyeVFk58flifNuevyrXedFeVkucKdKFMhx7K+ePLIylmcuBflMOfC4TSvnl1/7x7d9d+Wct6/2Z63jpiuyYyV4FOPtx7/13ztVnidy/DnbdI6JInumead6jSsryI/77utzT5dYvZ+fG4X3Z/dbv3LsylIuyG9/9uhW8Z0fkyd+dmJFevl54xcmVlbolxNf/81PdP/czTUAAAAAAMBoUpBDAzSlID/27H/vOveTO/9TOuOH/5HO++nn01dO/URXiRulZqxobp8bW3K3xz712bXTYads3ipd88I9xsrPGat/y+P7HPWx1vMdc+bWrW2147HYejuOjWI1VrfvuNcHOsfHyvTYUrud2Ao+/7qmS16Q77zPv7aeP0rqvb9aXVEeW4aXz8/L/Tj+4BM3a72W+Nrb5X5sOR7fw/IK63KR/fkD/63zePyyQf46I+99/9s7x8R8debNX+NUBXl8TeWvIZ6nvcV8bHeerwDPv8eHnLRZ5fyjv711a+V8FOr597BckG++/Xs7j8dx8b5feed+rZ+78tcUX0O+ZXr53EisFv/ulZ9rZbcDNuga2/hTa1a+7rkEAAAAAAAYTQpyaIAmFORx7+pykZmv1o3ECu7yat/9jtm4a/zLX/to577R5cTW2+1z4jnKY1Fctse23HGtrrHYTvvchbtV5ovStn3OdruvWxnvJeWCPIrVfDy+L7EKvH3MBpt2l9d5QT7TNuTlLcPLRfZ1Sw7rmiffxv6n9x3UGYviON9qfGXzRqYryKN0XnPtt3bGYyV4fg/zeK6NtnpX55j4pYT2WPxMlH9uYov5fAv12Aq+/LW1x3/z4te7Hs+//7Hle3k8Cvv2WNyjvP14/OLGVNv3x73ky+dffMNelWNmGwAAAAAAYDQpyKEBmlCQ73HohzrnxL3E8/F2YmV1+7gPf2KNyvhUicK1vBo4StX2WKzYbj8e24XftfzYyvl55qsgjxI6H4/ELwuUv6exJXp7rFw+x8r2/Nw80xXZUb63xw464eNdY+UV0bHKvpd5pyvIz/vZ7p2xWLGfl9vtxBbl7ePKv+TwH3uv13V+vsq7nXKJ3n6OuK97+7H4xYv8nMh6G72zc0ysLm8/Xl5N/58/+P1q+qkShX37uMP/c4vK+GwDAAAAAACMJgU5NEATCvJyORvboJ/0vU9PmShu28dF8ZrPE2V4lOi77r9Bq0CP7bk/tvXrq8QjP7x5787xF/1yz66xKFnLK4WnyqAL8ki54I2Vze3Hy+VzbM2en5dnuiL7ez/Zrev70H48CuXy9vblXzCoM+90BXlsgd4ei/t55+93Oe3jIrGyPn/e9rbvU2WqgrxczsfPSX5OJFart4+J7finmu+oMz5Zea3tlLdh32bXf67MP9sAAAAAAACjSUEODdCEgry8dXrdxKrw8hyxHXqsAs+Py5MX4HHv6PyYKEyjMM5fZ2QYBXn7fuiR2N67/Xi5fL528aGV8/JMV2THLxeU54stwuPxuJ95+7GtdnpfZc6Z5p2uII/7zLfHesnP7v/996pcVF/92+o25+1MVZDf8fwxncdivHxP+0j8ufyccV/yePz6h7q3o6+bj2/77srrmm0AAAAAAIDRpCCHBhh2QR7bYpfPidXKb1r1DTMm7h/enqO89XokCs+4b/Xn9l+/VeqWV0DnBXkktsmOOfNSM1YA5/fbHkZB/r71/qpz3HHf3abz+HTl81SZrsiOxDbg7fHt9/iX1mMbbvb3nccuu2Xqe5xPN+90r7H8dUXy93iqxC9T3PPycZWftfx9KmeqgjwSq9bbj8f9z8vnxPe5PH8U4/F4/Pz0+pojh5y0WeV1zTYAAAAAAMBoUpBDAwy7II+U7xF+yY17Vcany+3PHt1VgH5ky3e17lldPuaDH/t/nfGpCvJIFKzHfOdTXWV6JFaYl48bRkFeXmEfK+Xbj09XPk+V6YrsSPl7Gf973ZLXV0vHfbfz4+vMO91rjFXV7bEDjt2kMu90idfaPjfS3nZ9qqysIM9L8NhSfd+jN66sbN9l3w92zon3qTwWK+/z55vvAAAAAAAAo0lBDg3QhIJ83Q3/tnNOeYV0nRz97a0758YW67G6OD+mTkHeTtxje72N3tk5vnw/7ki5IN96l7Ur5/eSOgX5XcuP7fqelrdSn658nirTFdntbLvbOp1jYqv59n9/48IdKsfWmXe61xhldHtsix3Wqsw7U2baGaCdlRXkkdMv3rEzNlXi3uGxHXv7+HzHg2sWHVJ5vvkOAAAAAAAwmhTk0ABNKMh33udfO+dEIT3ddtl5Ymvs9rm7H7RhZTzSS0EeufbBQ7u+jvhze+yk87brPB7z5uf2kjoF+YHHb9r1WqKgbY9NVz5PlemK7HauvHO/rueLxAr/6d6T6eZ9+2p/1hnL7+t+5qU7dz1Pr2VzeYv0D39ijcp4O9MV5KdesH3XDgbtxPbvK9vNoPy+xS8U5OPzHQAAAAAAYDQpyKEBmlCQ59tW7/Sl9aYsZP/nV3u3CuryY3Fv53KpmZ8TK5/Lc59+0Y6dsShLP/35ddPCuw+oPE/5nPL4Rb/Ys/N4FK+3PnNU5Tnrply0TlXGRplfLnfzXwCYj4I8kt8bPFZ658fUnbc812bbvadrLFb7lwv02MY9VvDn88f26fGLAvnjx5z5+u4BkfhzfkysuC8fUy7IY0v99uMHn7hZuuzWfVrPH9uml38RIU/5lyQiK1tdf9qCz6SLb6i+r3MNAAAAAAAwmhTk0ADzWZDHlucz5abHf3+/8ENP3rxybtyXOsrHw07ZPG38qTU7Y+VtxqOALJ+3/R7/kr713zulM374H13bhbdTvp/02Vd8tvN43A87Cta9j/xoV2kb23iXy9L8nucxHqvYv3r6lmnTbf4xnXX5LpXvy8pSLshjzs/tv35rRfNXTv1E1/25288Tz10+f74K8vyXCqYqrevOu8OeH+iaK97Xs3702c54/ssI8XV+4ZAPpVO+v33r/Yjz29/v+N6U546yO3YcKJ+/9gf/pvVzE8d+/sB/63qvIuWCPO453n48fr422updrfekfU68lnU2eEdl5Xtkg01X75p3/U1WT4eftkWrFI9fKGivbo+fpal+2WMuAQAAAAAARpOCHBpgPgvyOmlvXx4ldNzTOx+fKlGAlp837l+dH1NOviK6vc36TOdF4p7j+dcZq43z49rZ7YANKsevLOWCfLrEFuBTbQ0/XwV5FLrtbcc/ufM/VcbzTDfv9Q8dVvl6ovQuH1O+j/x0iUI7f+7LbvlyetOqb6gcu7KUC/Ly/eRnSr46/abHjkhrrv3WynFT5Yc371153XMJAAAAAAAwmhTk0AD9LMhvfuKrlXJwpkSBWp7jnKt2rawKjkRhGwVprA6PLbDL59y1/NjWyvD8nCiQT7/491uqx/bk7cePOuOTrcdi9fLm27+3cl6ktdJ5JavB4/kPOuHjlXMidQrldsoF+T+8Z9XKXLGCOVY2x/c1PzdSXukehW0+nqdc6C6858DKeDlfOmKj1nGX37ZPZSzPTPPGfc3L9wvPC/JIbLNfXtHdTqzmjvljh4E7X/h65bzIr5/6Wuv7lK8Wjz/HFvzlx8u7AcQW73sc+qHOa4ufsfjvrXZ6X1pvo3dW5ovjy88bc8Xrmuoe5m952xtbP1tX//bgyuudawAAAAAAgNGkIIcG6GdB3s/85sWvtwrsi365Z+37fN/x/DGt4y/99Zdb5+fjsVV4bMmezxcrpq9ZdEg6/+rdW88505bi7UQxH6uDL7z+i+m6JYd1rU6uk3JBHgVxvI6433m8jrjvdn78IHPbsqNaryN/fC655emvtb5X8b3Ox9qJ72F8D2LFfJ1V8eXELy7E9zHek17PnSrxessledyjPD+mfOwPrt2j9QsF8XORj/czAAAAAADAaFKQQwM0tSCfhOQFeT4u85//+vGuK12ZHim/R/HLF/n4MAIAAAAAAIwmBTk0gIJ8eFGQDzfnLtyt9b2PrewPP22L1i4A8XjsMBBb/efb78eq+nyOYQQAAAAAABhNCnJoAAX58KIgH17i/uFvWvUNXQV4JL/veDv7Hr1xZY5hBQAAAAAAGE0KcmgABfnwoiAfXuJ+5adftGNabY03V8rwvDA/7JTNK+cPMwAAAAAAwGhSkEMDKMiHly13XCv9w3tWbeWXSw+vjMtgcv7Vu6cDj980bbHDWmnNtd+a1tvonenTn183HXPm1tPen3xYAQAAAAAARpOCHBpAQS4yWgEAAAAAAEaTghwaQEEuMloBAAAAAABGk4IcGkBBLjJaAQAAAAAARpOCHBpAQS4yWgEAAAAAAEaTghwaQEEuMloBAAAAAABGk4IcGkBBLjJaAQAAAAAARpOCHBpAQS4yWgEAAAAAAEaTghwaQEEuMloBAAAAAABGk4IcGkBBLjJaAQAAAAAARpOCHBpAQS4yWgEAAAAAAEaTghwaQEEuMloBAAAAAABGk4IcGkBBLjJaAQAAAAAARpOCHBrgweWXpPuWnyEiIxIAAAAAAGA0KcihAW65/tF0w+WviMiIBAAAAAAAGE0KcmgABbnIaAUAAAAAABhNCnJogFuvf7pSwIlIcwMAAAAAAIwmBTk0wJ3Xv1op4ESkuQEAAAAAAEaTghwaQEEuMloBAAAAAABGk4IcGuCFZwuRxubRZbeme5b915wSc+TzjnIAAAAAAIDRpCAHYEZPF79Ivy1OnFNiDgAAAAAAgGFSkANQm6IcAAAAAAAYZQpyAHo216I8zl+eluTTAgAAAAAAzCsFOQCzMteSvF2UAwAAAAAADIqCHIA5UZQDAAAAAACjQkEOwJzFdulLiwUpL757iZIcAAAAAACYbwpyAPrGanIAAAAAAKDJFOQA9N1ci/JYja4oBwAAAAAA+k1BDsC8mGtJHlGSAwAAAAAA/aQgB2BeKcoBAAAAAICmUJADMBBzLcqV5AAAAAAAwFwpyAEYmLmW5IpyAAAAAABgLhTkAAycohwAAAAAABgGBTkAQxEF99JiQcqL716iJAcAAAAAAHqhIAdgqKwmBwAAAAAABkVBDkAjzLUoj/OXpyX5tAAAAAAAAB0KcgAaY64lebsoBwAAAAAAmIqCHIDGUZQDAAAAAADzQUEOQCPFdulzLcqV5AAAAAAAQJmCHIBGm2tJrigHAAAAAADaFOQAjIS5FuVLiwWKcgAAAAAAmHAKcgBGxlxL8oiSHAAAAAAAJpeCHICRoygHAAAAAABmQ0EOwMiaa1GuJAcAAAAAgMmiIAdgpM21JFeUAwAAAADA5FCQAzAWFOUAAAAAAMBMFOQAjI0ouJcWC1JefPcSJTkAAAAAAIwvBTkAY8dqcgAAAAAAYCoKcgDG1lyL8liNvjwtyacFAAAAAABGlIIcgLE215I8YjU5AAAAAACMBwU5ABNBUQ4AAAAAACjIAZgYsV36XItyJTkAAAAAAIwuBTkAE2euJbmiHAAAAAAARpOCHICJpSgHAAAAAIDJoiAHYKIpyQEAAAAAYHKs8tprr1XK8JmSF97zEQAYJEU5AAAAAACMPwU5AJTMtSiP85enJfm0AAAAAABAAyjIASAz15K8XZQDAAAAAADNoiAHgJVQlAMAAAAAwHhRkAPANGK79KXFgpQX371ESQ4AAAAAAM2gIAeAGqwmBwAAAACA0acgB4AezLUoj9XoinIAAAAAABgOBTkA9GiuJXlESQ4AAAAAAIOnIAeAWVKUAwAAAADAaFGQA8AczbUoV5IDAAAAAMBgKMgBoA/mWpJHHiy+87ucmRYVp0ufs7j4VnqoODc9XlyRnivuyt8+AAAAAAAmhIIcAPqoH0W5zH8eTN9Jz6d78rcPAAAAAIAxpyAHgD6LknxpsSDlpaw0L88Wt+ZvHwAAAAAAY0xBDgDzxGry0cjLxRP5WwcAAAAAwJhSkAPAPFOUNzuPF1flbxkAAAAAAGNKQQ4AA6Akb24WFaflbxcwIlakF9Mr6an0cnpCpBF5JT2ZXk3P5j+qAAAAQIMoyAFggBTlzczL6fH8rQIa6sViUXqsuDwtLr5Z+SyLNCcnp6XFD9Ky9Ovf/dT6/28BAACgSRTkADBgi9M3U/Uf0mWYeaG4L3+bgIYpfvd/j6cfVT6/Ik3PkuKs9GLxYP4jDQAAAAyJghwABiy29M7/8VyGm+eKO/O3CWiYR9Mllc+uyOjkpPRSWpr/WAMAAABDoCAHgAFTkDcvCnJotmeKmyufW5FRy8PF+fmPNgAAADAECnIAGDAFefOiIIdme7A4s/K5FRnFvFA8kP94AwAAAAOmIAeAAVOQNy8Kcmiul9Ijlc+syKjmieIn+Y84AAAAMGAKcgAYMAV586Igh+Z6Nt1W+cyKjGoeTrZZBwAAgGFTkAPAgCnImxcFOTTX0+n6ymdWZFTzYDoj/xEHAAAABkxBDgADpiBvXhTk0FxPpZ9XPrMio5pFxTfyH3EAAABgwBTkADBgCvLmRUEOzaUgl3GKghwAAACGT0EOAAOmIG9eFOTQXApyGacoyAEAAGD4FOQAMGAK8uZFQQ7NpSCXcYqCHAAAAIZPQQ4AA6Ygb14U5NBcCnIZpyjIAQAAYPgU5AAwYAry5kVBDs2lIJdxioIcAAAAhk9BDgADpiBvXhTk0FwKchmnKMgBAABg+BTkADBgCvLmRUEOzaUgl3GKghwAAACGT0EOAAOmIG9eFOTQXApyGacoyAEAAGD4FOQAMGD9LMivf+iwtMOeH0hb7fS+tNFW70rrbfTOtM4G72j975Y7rpV2O2CDdO7C3dK9rx5fObedA47dJG272zpp8+3fmz6y5bvSBpuu3jp/023+Me1x6IfSNy7cId37ysrPX1k+tvWa6cDjN608PlPuefm4dN7Pdk/7Hr1x67W85W1vTG/96z9N717nL1uv8+Tzt0t3v3Rs5by5REEOzaUgl3GKghwAAACGT0EOAAPWz4L8f361d1pllVVmzP954x+lsy7fpXJ+JMrn/Pg8b1r1DSs9f6pcccd+rfP+5M//ON332gmV8ZXll0sPT2us9X8rz5/nve9/e+XcuURBDs2lIJdxioIcAAAAhk9BDgADNoyCvJ3TFnymMkdekP/hH/1BK/m5kctu3ady/lTZfo9/6ZzzvZ/sVhmfKhf9cs9WkZ8/51TZ8ysfrpw/lyjIobkU5DJOUZADAADA8CnIAWDA5qsgj1L7khv3SlfeuV+64JovpBPP3Tatv8nqXcVyrATPtycvF+Q/uHaPzuNx3OkX7dhVWq+74d9WXkOeO1/4elfBvtl276kck+faBw+tlOCxPXy8nngddy0/Nl2z6JD01dO3TKut8eZ03ZLDKnPMJQpyaC4FuYxTFOQAAAAwfApyABiw+SrIo/zOxyNHfGPLruJ5wXV7dI2vrCBv58xLd+6MR1mej+c57rvbVMru2587pnJcOVvssFbX8VHM58fMZxTk0FwKchmnKMgBAABg+BTkADBggy7I719xQteK7iiwy+MzFeQ3PnpEV3l9x/PTl91T3UM8f85yfnT7vl3HHvnNrSrHzHcU5NBcCvLxzk/uPTAtvPuAdO3iQytj4xgFOQAAAAyfghwABmzQBXnkLW97Y+e4w0/bomtspoL8ol/s2Rn/kz//48p4OeWyu/yc733/2yvHtrPxp9bsHBcr1PMt4AcRBTk0Vz8L8tjNYqcvrZe22fWfW7d/2Gird6WPb/vutN3u66bdD94wfePCHdL1D01/C4eDT9ws7br/Bq384uGv9Dwuryfej7p/v4xLFOQAAAAwfApyABiwQRfkseK7fUzk3IW7dY1PV5Df/uzRXSvCDzlps8r85Wy/x790jv3Wf+/Uek3tP8c9xPPjI+UifZ+jPlYZH0QU5NBc/SzI8x0xVpZ1NnhH5XYU7ZSvWRf9cs+ex0ct8XfInS98vfJ4P6IgBwAAAIZBQQ4AAzbIgvzeV49vrZJsHxNbrUfpXT6mXJDHvcD3PXrj9KUjNkqf3PmfurZm/9Rn1073vXZC5TnaiQKlfXz8b6wE32XfD3bO3+vwj1TOufeV4zvjkZUVUvMdBTk01zAK8naOP6d6e4iZCvCZxkcll926T9pqp/e1vo5YWZ+P9yMKcgAAAGAYFOQAMGDzVZBHKR0rvI89+99b/xvbCEfhUC57Dj1588oc5YJ8ZVl/k9XTr548snJuOXGf8fbxUa7HY+Xt2aM0ivuhl8/56X0HdT3PTFsbz1cU5NBc81mQX3LjXumKO/ZL5/308+mYM7dO71vvryrXv3z3i5kK8JnGRyVxHW9/HQry/kVBDgAAAMOnIAeAAZuvgnymxD12p1oBXi7Io2SP+4BH8vMjJ567beX8dspbsZ/3s91bj0UhXp4r38L9u1d+rmv+qV7fIKIgh+aaz4I8H4+cesH2XcfEThjl8ZkK8JnGRyUK8vmJghwAAACGT0EOAAM26II8Cuqzr/hs5dx2VnYP8tj+/Ee379tVkkSiPMrnuPy2fbqer1x0RzHfHmuvLG8ntlQvzx3Pmc89iCjIobkGXZBHNv7Ump1j3v/h1brGZirAZxpveuI6fMMjh6eNtnpX5+s48ptbtR5rJ26hkZ/Xzj0vH5cu/fWX08nnb5cuuOYL6dZnjqoc006dgvzmJ77aed64H3o+3s5ty45qPV88b+wMEH/Oj2kn5on5ysfE1x1/p8b5sftJfjuSfkVBDgAAAMOnIAeAAZuvgjxWf0fBfdblu6TdDtigqwSKsiA/t52VFeTlfOaL7+8cE+VPvtK7XIL/x97rdY3FavLya/zNi1/vjP1y6eFdr/Pq3x5cee5BREEOzTWMgvygEz7eOeYf3rNq19hMBfhM4/3KgcdtmvY+8qPTFtCzyekX79j1PZoqx3znU5Xzfv3U19JHtny9VC/n7av92ZR/D81UkOe7jJzy/eovaC2858D07nX+svKckXjvoqzPz4ldAWL8Hav/RWunk/af8xxw7CaVW4PMNQpyAAAAGD4FOQAM2HwV5G9a9Q2dx6PALm95vtoab17p6uw6BXncg7dcGly35PV7hcdKvCi+22PxmsrnxvOWx2N1XnssiofyvOcu3K3y3IOIghyaaxgF+a77v/5LRrGavDw2UwE+03i/su1u67SeI66vnz/w39JNj3+1csxsMpuCPK77UXDnx+U59OTNu86briCP4rv8d8fn9l+/8lqP++42leeYKvnz7rzPv3bGokTPjy8nSvL8eecSBTkAAAAMn4IcAAZsEAV5pLzteSRWG+bnR+oU5FG4l+c6/+rf32M8cuzZ/941ttVO76ukXHKsu+Hfds0dKwvL5+bPPYgoyKG5Bl2Q37X82K7r0peO2KhrfKYCfKbxfiVeV/lrieyw5wfS9Q+9/gtMs0lsaR47kaz9wb/pzPvZ/dZvPdZO7P7RPj5+Car890gU3VFcx99BZ166c+uaX36NC+8+oHPuygryWBVfnnODTVev7FwS85Tnfe/7397Z1v3Ec7etFN9X3LFf59xyQR6JW4PELxnEL2nF/dZjZXl5bLqt3XuNghwAAACGT0EOAAM2qII8km8b+/MHqluY1ynIf/HwV7rmKa/0zkuIOon52udHoVMem+o1zncU5NBcgyzIb3rsiK57b0fynS1mKsBnGu9nooTeYoe1ul5v5JM7/1P62f0HVY7vJTFHe74ojfPxdr5y6ic6x0XJXd5hJHLvq8e3Cu72MRtu9vedsakK8ji+XKrHDih5QR1l+Zprv7VzTBT4+VboUdyX38vyveTLBXm8X/nfO3Fv8vIvdkXpXh6fSxTkAAAAMHwKcgAYsEEW5FEqxOPtY/LV25E6BXm5AIm0C+7Lbu1epR4rDtfZ4B1Tplw27HfMxp25b3ik+z7k6230ztYKzvw1tPPDm/dOV965X+XxuURBDs01nwV5FKV7f3WjtONeH2gVt+WxSL69emSmAnym8flIrOiOFdDl62z79ZdXTveSugV5+euNe7fn45HLbvly1+uKYjwen6ogj/ei/Vis3p5qRfx5P9u9c0ys9o5SPT8mEqvh28fF96b9eLkgP+bMrSvnReJ71z4mVqTn47ONghwAAACGT0EOAAM2yII8Elvcto+JnHTe6/cAj0xXkMcqvShGyufHNrbt8U9/ft3O43HP8/y5y/nCIR/qHBvbF5fHYvVf+Tlirqnup3v8Ob+/32y85nxF4VyiIIfmms+CfLrEderXT32tMsdMBfhM4zMlivpY7Zynzi8G3fnC19NXT9+y6zWUi+FeUqcgj1Xa5e/Zr548snJMO+Vf1oqV7/FYXpDHvc3L8y24bo/KPJG4p3j7mHev85fppO99eqUpzxe/kBXn1ynI457n7WPKv9Q11yjIAQAAYPhWycvvlSUvsOcSAJhkgy7II+WVkbEir1z6lAvyWOm97W7rpO12X7d1TrlkiUTR0i42oqAur1aMVeb585aT3xP9khv36oxFqZI/VySKj9iCPbbJLZcrkVhlmD/HbKMgh+YadEEe16L4ZZyVrUqeqQCfaXym5K+nnVg1nR+bJ36p6Ywf/kfX9uPzWZAvvOfA2s9Tfk2nX7xj67FyQT5VvnjYhyvzRMqvrZe0t52vU5BHKd4+Zu8jP1oZn20U5AAAADB8CnIAGLBhFOSxRW25zI5yoT1WLsinSxxXvg9rvtIviqf8efOUi6Mo4ctjcc/X9Td5/T610yW2cs/vGTuXKMihueazID/7is+mUy/YPp11+S6tFdp1dqaYqQCfaXym5Ne7ds6/euUF+W9e/Ho66oxPVq7nca2sU6xPlToFeXx97WPaW6SvLHH7jPaxR35zq9ZjMxXkkYV3H1CZ633r/VXXMfH330yJ9+Wel49rnV+nID/wuE07xyjIAQAAYLwoyAFgwPpZkJfv6xr/+J+Pl3PISZt1FQpx//B4PLYRzguJSBTqcW/XWEkeZXi+mjKKl/axsfI8f76pstsBG3TOiZXs+fj9K05IBxy7Sfq7Nd9SeT2ReK1RZsRx+blziYIcmms+C/J8vE5mKsBnGp8psW35VMmPi8Q9tvf8yodb19Py1xVbsl94/Rcrx/eSOgX51b89uHPMTCvIy9f1+IWEeGyqgjyea/s9/qXz59hJJL/mf3zbd3fG4++M/LlmioIcAAAAJpuCHAAGrJ8F+TgnVvrFCvkoUq64Y7+VFkT9iIIcmmvSCvK6iVXY5a8lEr/QFNfN/NjZpFyQn3TedpXxSH4P8lufOapyTOu4V4/v2sWkvSo8L8jbz3P7s0e3VqS3Hz/6290l9r5Hv779+RY7rFV5vpmiIAcAAIDJpiAHgAFTkDcvCnJoLgX51Nl2t3U6z7Pxp9ZsbRGfHzOXbL3L2p35Dzx+08p4O+Vt3dtbp+c5bcFnur7v7a3OywV5vkV73Ke8PRblevk2HmdeunPXfNcsOqTynNNFQQ4AAACTTUEOAAOmIG9eFOTQXAryqbPLvh9MW+64VvrpfQdVxvqRfY76WOfreO/7314Zb+eIb2zZOS6+9hseObxr/KbHjugq0WP79PbYdAV5ZP1NVu+Mf2zrNTuPR8Fevj1IvL5fPXlk5fx4LVOV+wpyAAAAmGwKcgAYMAV586Igh+ZSkA8n51+9e9f3KgrpKI3jnt9RXLeL8Nhmvfw1R9F9yEmbpe9e+bl02Cmbpzet+obOWKwEj/umt59jpoL8uiWHdb2Gs3702c5YbCVfHov7sH/hkA+lU76/fav03mHPD3S2dT/1gu275lWQAwAAwGRTkAPAgCnImxcFOTSXgnx4Ka/gznPOVbt2jouyulyET5Uoq8+6fJeu+WcqyCMHn7hZ55h4jjueP6YzFvcmz59nqrz/w6t1zakgBwAAgMmmIAeAAVOQNy8KcmiufhbksXq5XJzm43VS3i78khv36nl8lBJl9BY7rFUpnCPHfXebrmNvW3ZU69hYyV0+LorxKNpjNfhU87ePW1lBfu+rx6fV1nhz57gvHbFR13hsMR8FeP764nnXXPut6dCTN093vvD1rnN23X+DznHHnv3vleeMlIv5fY/euDI+2yjIAQAAYPgU5AAwYAry5kVBDs3Vz4JcZpdbnv5auuCaL7RWit/0+FfT/StOqBxTzi+XHt7aov3nDxw847H9ShTpC+8+oPU64/nz8aZEQQ4AAADDpyAHgAFTkDcvCnJoLgW5jFMU5AAAADB8CnIAGDAFefOiIIfmUpDLOEVBDgAAAMOnIAeAAVOQNy8KcmguBbmMUxTkAAAAMHwKcgAYMAV586Igh+ZSkMs4RUEOAAAAw6cgB4ABU5A3LwpyaC4FuYxTFOQAAAAwfApyABgwBXnzoiCH5lKQyzhFQQ4AAADDpyAHgAFTkDcvCnJoLgW5jFMU5AAAADB8CnIAGDAFefOiIIfmUpDLOEVBDgAAAMOnIAeAAVOQNy8KcmguBbmMUxTkAAAAMHwKcgAYMAV586Igh+ZSkMs4RUEOAAAAw6cgB4ABU5A3LwpyaC4FuYxTFOQAAAAwfApyABgwBXnzoiCH5lKQyzhFQQ4AAADDpyAHgAG75ab70i033yMNypIlS/K3CWgIBbmMUxTkAAAAMHwKcgAYsBuveiHdcPkr0qAoyKG5FOQyTlGQAwAAwPApyAFgwBTkzYuCHJpLQS7jFAU5AAAADJ+CHAAG7OarqgWtDDdPPLQif5uAhlCQyzhFQQ4AAADDpyAHgAFTkDcvCnJoLgW5jFMU5AAAADB8CnIAGLBFd7w20rnv9mXptttvmVXyuZoSBTk0l4JcxikKcgAAABg+BTkA0LP8H/zrZnlyr2+gN/fc9WC68arnRcYmAAAAwHApyAGAnuXFd908XfwinwpgWlGQ57dFEBnVKMgBAABg+BTkAEDPlhYLUl5+14mCHOiVglzGKQpyAAAAGD4FOQDQsyi68/K7ThTkQK8evGtFpWQUGdXc/ONX8h9xAAAAYMAU5ABAz2ZbkMfKc4BeKMhlnKIgBwAAgOFTkAMAPVuelqS8/K4bgF48+fAK+d8sevj29JuHL5tV7n3o2sp8MpwAAAAAw6UgBwB6piAHGKwVv7vy/rY4qXJNrZvn0h35lAAAAAATSUEOAMxKXr7UTZTrAPTmmXRj5XpaN4uLb+XTAQAAAEwsBTkAMCt5AVM3cf9yAHrzYPpO5XpaN667AAAAAK9TkAMAs7K0WJDyEqZOFDUAvXmuuKtyLe0lr6Xn8ykBAAAAJpaCHACYlSi68xKmTqJYB6C+h4sLKtfSunm8uDKfDgAAAGCiKcgBgFlRkAPMv+XFQ5XraC95qXgknxIAAABgoinIAYBZWZ6WpLyIqRsA6nms+FHlGlo3j6SL8ukAAAAAJp6CHACYtbyMqZso1wGY3qvp2cr1s5c8X9yTTwkAAAAw8RTkAMCs5WVM3SjIAWb2VHFt5fpZN0vS2fl0AAAAACQFOQAwB3E/8byUqZO4fzkAK/e7/88pLSpOr1w/62ZZujmfEgAAAICkIAcA5kBBDjA/ni1uq1w76+aB4pRUpFfyKQEAAABICnIAYA6i6M6LmTqJYh2AlXuoOLdy7aybJ9PP8ukAAAAA+F8KcgBg1mZbkEcAmNqL6YHKNbOXvJKezKcEAAAA4H8pyAGAWVuelqS8mKkbAKb2aPHDyjWzbuJcAAAAAFZOQQ4AzEleztRNlOsAdHs5PVm5XvaSF9OifEoAAAAAShTkAMCc5OVM3cT27AB0ezL9tHK9rJuHiu/l0wEAAACQUZADAHOytFiQ8pKmThTkAN1WpJfTA8Upletl3TybbsunBAAAACCjIAcA5iSK7rykqRMFOUC3ZenmyrWybhYVp+fTAQAAADAFBTkAMCezLchj5TkAr1tSnF25VtbNU8V1+XQAAAAATEFBDgDMyWwL8ggAv/dCuqdyjewlr6Zn8ykBAAAAmIKCHACYk+VpScqLmroB4PceSRdWrpF181jxo3w6AAAAAFZCQQ4AzFle1tRNlOsAk+6lYmnl+thLlqeH8ykBAAAAWAkFOQAwZ3lZUzexPTvApHu8uLJyfaybpcUP8ukAAAAAmIaCHACYs6XFgpSXNnWiIAcm3avp+cq1sZc8V9yVTwkAAADANBTkAMCcRdGdlzZ1oiAHJt3TxfWVa2PdPFicmU8HAAAAwAwU5ADAnM22II+V5wCTbHHxrcq1sW6eKW7IpwMAAABgBgpyAGDOZluQRwAm1bPFHZVrYt08UJycXkvL8ykBAAAAmIGCHACYs+VpScrLm7oBmFQPF+dVrol180SxMJ8OAAAAgBoU5ABAX+TlTd1EuQ4waV5MiyvXw17ycnosnxIAAACAGhTkAEBf5OVN3cT27ACT5rHi0sr1sG4eTZfk0wEAAABQk4IcAOiLpcWClJc4daIgBybNK+npyrWwl7xQ3J9PCQAAAEBNCnIAoC+i6M5LnDqJYh1gkjyZrq5cC+vmoeK/8ukAAAAA6IGCHADoCwU5wMyK9Gp6oPjPyrWwbp5Nt+RTAgAAANADBTkA0BfL05KUFzl1AzAplqVfV66BdbOoOO13M6zIpwQAAACgBwpyAKAvFOQAM1tSnFO5BtbNU+mafDoAAAAAeqQgBwD6Ji9z6ibKdYBx90K6v3L96yWvpmfyKQEAAADokYIcAOibvMypm7h/OcC4eyRdXLn+1c1jxWX5dAAAAADMgoIcAOibpcWClJc6daIgB8bdy+mxyrWvl9hpAwAAAKA/FOQAQN9E0Z2XOnUSxTrAOHsiLaxc++rm4eL7+XQAAAAAzJKCHADom9kW5BGAcfVaerFyzeslz6U78ykBAAAAmCUFOQDQN7EFcF7s1A3AuHq6+GXlmlc3i4sz8ukAAAAAmAMFOQDQV3m5UzfurwuMq8XFtyvXvLqJch0AAACA/lGQAwB9lZc7daMgB8bRc8VvKte7XvJaeiGfEgAAAIA5UJADAH21tFiQ8oKnTuL+5QDj5uHi+5XrXd08XlyVTwcAAADAHCnIAYC+iqI7L3nqREEOjJvYGSO/1vWSl9Ij+ZQAAAAAzJGCHADoq9kW5LHyHGCcPFZcXrnW1c3S4sJ8OgAAAAD6QEEOAPTVbAvyCMC4eDUtq1zjesnzxb35lAAAAAD0gYIcAOiruWwpDDAuniquqVzj6ubB4ux8OgAAAAD6pFZBnhfccw0AMN7ysqduolwHGH0r0qLiG5VrXN08U9ycTwgAAABAnyjIAYC+y8ueuont2QFG3bPp1sr1rW4WFaemFemVfEoAAAAA+kRBDgD03dJiQcpLnzpRkAPj4KHi3Mr1rW6eTFfn0wEAAADQRwpyAKDvoujOS586UZADo+7F9EDl2tZLXi6ezKcEAAAAoI8U5ABA3822II+V5wCj7NH035VrW908lv4nnw4AAACAPlOQAwB9N9uCPAIwql5JT1Suab3kxbQ4nxIAAACAPlOQAwB9tzwtSXnxUzcAo+rJ9NPKNa1uHi7Oy6cDAAAAYB4oyAGAeZGXP3UT5TrAqFmRXkoPFCdXrml181y6PZ8SAAAAgHmgIAcA5kVe/tRNbM8OMGqeKW6sXM/qZnHxzXw6AAAAAObJSgvyvNTuZwCA8be0WJDyEqhOFOTAKFqSzqpcz+rm6XR9Ph0AAAAA80RBDgDMiyi68xKoThTkwKh5vri7ci3rJa+l5/IpAQAAAJgnCnKYUMvTQ62tQJ8oFqbH0uXyv3n8d3kiLUzPpBvdBxnmaLYFeaw8BxglS4sfVK5ldfN4cUU+HQAAAADzSEEOE+bZ4tb0YPGdlP/jrEydB4sz07J0S/5tBGqYbUEeARgVy9PDlWtYL3kpLc2nBAAAAGAeKchhgjxeXJXyf5SVenk8Wd0FvYpdGPLPUt0AjIpYAZ5fw+rGjhkAAAAAg6cghwkxl5Wc8vs8na7Lv63ADPLPUd24xQEwCl5Nz1WuX73k+XR3PiUAAAAA80xBDhPgtfRC+m1xUsr/UVZ6T/xDOFBf/hmqm/ilHoCme6q4vnL9qpu45Q0AAAAAg6cghwmwrPh1yv9RVmaXZenm/NsLTCO2D84/R3WiIAdGweLim5XrV908U9yUTwcAAADAACjIYQI8Vlya8n+UldnlkeKS/NsLTGO2t3dwX16g6Z5Nt1euXfVzclqRXsqnBAAAAGAAFOQwAZYU56TqP8zKbPJgcVb+7QWmoSAHxtXDxXmVa1fdPFH8JJ8OAAAAgAFRkMMEmMv2n9KdRcVp+bcXmMbytKTyOaobgKZ6MS2uXLN6ycvp8XxKAAAAAAZEQQ4TQEHevywq/jP/9gIzyD9HdQPQVI8W/1O5ZtWN27UAAAAADJeCHCaAgrx/UZBD7/LPUd3E6nOApnklPVW5XvWSF9Jv8ykBAAAAGCAFOUwABXn/oiCH3sX9xPPPUp3E/csBmubJdHXlelU3S4r/yqcDAAAAYMAU5DABFOT9i4IceqcgB8bFiuKV9EBxauV6VTfLilvyKQEAAAAYMAU5TAAFef+iIIfeRdGdf5bqJIp1gCZZln5VuVbVzaLitFSkFfmUAAAAAAyYghwmgIK8f1GQQ+9mW5BHAJpkSfpu5TpVN08W1+TTAQAAADAECnKYAAry/kVBDr1bnpZUPkt1A9AUzxf3Vq5RveTV9Ew+JQAAAABDoCCHCaAg718U5DA7+WepbqJcB2iCpcWFlWtU3TyeLs+nAwAAAGBIFOQwARTk/YuCHGYn/yzVjYIcaIKX0iOV61MvebFwLQMAAABoikpBnpfZ8xFgsBTk/YuCHGZnabGg8nmqk7h/OcCwPV5cVbk+1c3SdEE+HQAAAABDpCCHCaAg718U5DA7UXTnn6c6UZADw/ZaeqFybeolzxV35lMCAAAAMEQKcpgACvL+RUEOszPbgjxWngMM09PFLyvXprp5sPh2Ph0AAAAAQ6YghwmgIO9fFOQwO7MtyCMAw7S4OKNyXaqbZ9IN+XQAAAAADJmCHCaAgrx/UZDD7CxPSyqfp7oBGJbn0p2Va1Ivie3ZAQAAAGgWBTlMgPkoyC++Ya+06/4bpB/ftX9lLM9eh38kffX0LSuPR668c7/WPL1kwXV7VOY5/+rd09+t+ZZ027KjKmP9jIIcZi//PNVNlOsAw/Bw8f3KNalunkg/zqcDAAAAoAEU5DAB5qMg33mff02rrLJK2nGvD1TGyll49wGt4/7wj/6gMhY59YLtW+O95IBjN6nM8+FPrNEaO+bMrStj/YyCHGYv/zzVTWzPDjBoc9n5IvJS8Wg+JQAAAAANoCCHCTAfBfnaH/ybViH9J3/+x+n+FSdUxts58LhNO8X2zx84uDLej4L8xkeP6Iy9e52/rDxHP6Mgh9lbWiyofKbqREHOpHktLU8vFY+kF4tFv8sDMqQsLX5QuR7VzcPFeZX5JjeL0kvpEdvNAwAAAI0x8IIcGLz5KMhjRXi7lL7kxr0q4+1EYd0+7rQFn6mMlwvyd6z+F+m/frzrjLluyWFdc+xz1Me6CvSf3X9Q5Xn6FQU5zF4U3flnqk4U5EyKZ9JN6aHie5XPgMi4ZEk6Oz2drksr0vL8xx8AAABgYBTkMAH6XZBHQV0upD+3//qVYyK/evLIGY8rF+SxKj0fnyn3vXZCetOqb+h6nj0O/VDluH5FQd48K9LL6fl0V3qi+El6pLg4LU3fb90zVpqXxcW3K5+pOllUnFaZS0Y/S9MP0mPpsvRMuiEtL5bmH+2JEqtrlxRnV372RcY1i4vT0/PFfflHAQAAAGAgFOQwAfpdkJ91+S5dhfRb3vbGyjGRE8/dtuu4qQrwuRbk51y1a9dzRKIwn27b97lEQd4sT6fr0wPFKZX3SURGLw8XF6Tl6aH8Yz72XimeSYtTf/+eFhmVxH3eAQAAAAZNQQ4ToN8F+d5HfrRSSl92y5crx2201bu6jolt2fPieq4F+Yc/sUbn/Cjq2/99/tW7V47tRxTkzfFI8d+V90dERj/Pp3vyj/tYe6y4tPI9EJmUPJy+l38kAAAAAOZdqyDPS+x+BGiOfhfkH9myu/iO7H7Qhl3H3PPycV33KW/np/d13x98LgX5DY8c3jk37l9+/DnbdP68xQ5rVY7vRxTkzfBkcXXlvRGR8cgDxcnp1bQs/9iPpVfS05WvX2TS8kJ6IP9oAAAAAMwrBTlMgH4X5OWV2u289a//tOuY7/1kt8oxkVO+v33XceWCPLZGP/TkzafMSedtV3kdX/7a6yvZDzh2k3TL01/r/DnK+TueP6ZyzlyjIB++KM7y90VExitPpIX5R38sLUu3VL52kUnLk8VP848GAAAAwLxSkMME6GdBfvtzx3RK6D/58z/u2kb9yjv36xy3w54f6Dy+05fW6/z3zvv8a9d85YJ8uuQF/H2vndAq1Nvj1y05rPX4uhv+beexuAd6/vrnmkXFqfm3lwF7prip8r6IyHhlUXFa/tEfS48XV1W+dpFJy8PFBflHAwAAAGBeKchhAvSzIF9w3R6dAvqDH/t/6fSLd+z8ec+vfLhzXLu8jpXc5a3Q3/v+t3fNN9uC/LtXfm7KOY8645Odx3vdsr3XLC0WpKeLX7SyPC3Jv+3Mk0eLH1beCxEZv7yUHsk//mPnkeLiytctMmlZks7KPxoAAAAA80pBDhOgnwX54adt0SmgP3/gv6W7lh/budd43Ac8jomV5O1jNtvuPa3HYrV5/DmOjdXf7fnKBflqa7w5XXj9F6fM5bft0/U6Ntzs7zvnHfnNrTqP3/TYEZ3HI+2V5YOM4nx+PVScU/mei8j45fni7vzjP3aWpgWVr1tk0rK4OCP/aAAAAADMKwU5TIB+FuSf3PmfOuVzlNvxWJTg7ccW3nNg2u+YjTt/PvPSnVvHrL/J6q8fc/cBnfnKBXndFd/lFemRXz15ZNd4rChvj8V9yvPzhxXFeX8sLr5V+d6KyPjl2XRb/vEfOwpyEQU5AAAAMHgKcpgA/SzI/+E9q3bK5x/ftX/rsbMu36Xz2D5HfSytufZbW/8dq8XvfunY1jG7H7xh55jyvcFnU5DvfeRHO+fENu/5+KEnb94Zf8vb3lgZb1rKxbnyfGYKcpHJyLLilvzjP3YU5CIKcgAAAGDwFOQwAfpVkN/7yvH/n733DpqjOPD3+fOqvuWqq7or111dcNlln31nG5/tw8VhY3NgzAGHMQZjMGA4MNGAAZlwZBFFECKKHAwWSVgEkZUDEspZQgnlnPMbp3/6jH69b0/37r677+y77+w7z1P1lKXp7smzMvOZ7i4Ez3JJ6yOF5XaYdTuUurTDq8tn3r6osPyia39WWF5tQK7h2e385lJzk591yY8THnn8txL7+c7ka4P1NIr0Og8hIEfMhwTkiPmQgBwAAAAAAAAA6g0BOUAOqFVA7s4t/t1Dv5woc4det9rh1eXYpbcVlh925NcLy6sNyAcNvzzYTmeee8V/BetpdPMcnBOQI+ZDAnLEfEhADgAAAAAAAAD15iA/2K6VAJAdahWQDxx8fiF0PvPiwxNlr4+5MhFKu8OrS/X8dstt7/NqA/ITTvt+ob56kqu3eDHdoeC1Lwv3dexLbzYPwTkBOWI+JCBHzIcE5AAAAAAAAABQbwjIAXJArQLyy28+rhA63zHwtESZAu+/+eIXCuW/Pu+woP0hh3+1UK7e6FpWTUA+ZV2/Ql358og/BHWs83cPSNR96s0Lgzp5sjfNc05AjpgPCcgR8yEBOQAAAAAAAADUGwJygBxQq4Dcndt78NirgvLz+xxVKH/h/d8H5eddeWSh/OGXz42XVROQX3/vSYW6CuM197lfx9XtbX7MSd8JyrExg3MCcsR8SECOmA8JyAEAAAAAAACg3hCQA+SAWgXkbg/xGZvvDcqHTPhjXOYPr26977mzCu0vuPqn8bJKA3IN0a4h1W1dhfF+HV93SHg5dX2/oA6WNqvDtROQI+ZDAnLEfEhADgAAAAAAAAD1hoAcIAfUIiCfve3+RO9tv1x+3v6o+bt//Ouiw6vLd6ZcG4Thz75zcWHZUSd8O2hjfXPi1Ymw++1J1wR1fOfu6J9oo4Der4PV29PBOQE5Yj4kIEfMhwTkAAAAAAAAAFBvCMgBckAtAvJK/WjOjebT1XcFy7H3W6/gnIAcMR8SkCPmQwJyAAAAAAAAAKg3BOQAOaCeATmib63nOScgR8yHBOSI+ZCAHAAAAAAAAADqDQE5QA4gIMcsquC8K73OCcgR8yEBOWI+JCAHAAAAAAAAgHpDQA6QAwjIa+eK6Kk4yLWhrgJevw6mt1xwTkCOmA8JyBHzIQE5AAAAAAAAANQbAnKAHEBAXjsVkJeC4Lz71XldHj0ZLEfE3icBebZduO8hM3rRrbHTN90blCNWKgE5AAAAAAAAANQbAnKAHEBAXjvLBeSlcINzwnPsqoRRmDcJyCv3xv4nmytuOb7L6nfFX2dnvvjhpeaggw6K/fV5hwXlWXbQ8MvNby/9iRk4+PygLOvO3HKf6XP7Cebym48zn66+KyhvRAnIAQAAAAAAAKDeEJAD5AAC8trZlYC8FATn2fWN8X3Mdw/9spm7o39Q1lM2chhVrY0eAC1te9Tc88yZ5twr/su8M+XaoLwRnLKuXxycHnPSd8yX/+WL5mv/9vfxn3VNJq66M6jfHRKQV+7ffPELhd+Hrvj8e5cE6+zMRv1NmrX1/sSxD59/c1Cnp5yx+V7zefujwXJXPZd230/8zSFBeSNKQA4AAAAAAAAA9aYmATkAZBsC8tpZy4C8HAzX3rMqdFD4MODFs4Oy7nL+7gFmwZ4Hg+XWRg2jfCvp/Z7lAKiSAEu9U+3+K7hc0vJIUCfL6r7/f1/4q0SI6Pv6mCuDdrWWgLxyCcgrd/LauxPH/tHsG4I69Vbn8ugTD473R78xfrnreVceWdj3I479ZlDeiBKQAwAAAAAAAEC9ISAHyAEE5LWzXgF5KQjOu99pG+4phA+HHfn1oLzWfjTnRnPWJT+Ot/fM2xcF5dZGDaPk4uaHTb+nzjAHH/Il842D/yEo981iAFRNgPXkkAsK+6+geUlr4wTkQyb8MREe/vNX/tacefHh8XDU+rOWKYzVBx1+21pLQF65b316tXl11BWB+q2w1/KoE74dlFvVq9pfZ2c28m/S7Y+dFv8WXXbTsUFZT6hRGuy57Oz3Zdznt8WjOfzo6G+YoVOvC8obUQJyAAAAAAAAAKg3BOQAOYCAvHb2dEBeCoLz2qm5fN2AUGGEX6eWKni02+qtAbmGSbf7XklAnsUAqJoAa1HTQ+bsy44w3/reP5lHXjk3KM+y+ojBHqfuTX3cYMsW7nvIXHnr8eahQf8btOsOCcjTe/19vyxcTw3575ensZF/k7JmNb8vvVECcgAAAAAAAACoNwTkADmAgLx2ZjUgLwXznFen5o62vWStV9/586BeLSUgbwzzEGCpV7h779ejl3g5CcjTW21APm/nA/EoAo+/cb75cNYN8UcRfh1rZ79Jmopg6vp+BctNNaA57//88WXm2XcujucE10cmfh2r7kutb+6O/oVlWvcHM6+P9/udydfGx+G3kxohxN2nmVvuK5Tp998tq0R/ugWNFjF6cV/z7NCLzcDXf2cGj+tj5u0q/RzZY/m7f/zrwrn8eO6NiW34dV3LnSdZzfVMc17TSkAOAAAAAAAAAPWGgBwgBxCQ185GC8hLoeCcXuehr4y8IhEQSgXmfgjiqrBUocL0jfcEZVY32LCBhoIH/f2ks35Q2NZ9z51VMvwoFkZpv0YsuDkOLzTEcjXhhUIQG5y8O+26RCjia/fVDYa17TFL+pqn3rzQvDb6yjh48ttJDd2s9dt9V9DsHqMbUHUlAFKopR7nL7z/+3ge5Ykr7wzquHZngGXPk2tn1yRLAZaup3ud/HLrJ8tvN3+84+fxs6H5nP3yWklAnt5KA3KF0t899MvB75/UaA7ufW4t9pvk2ue2EwrlmmpA95df58/DLg8+SrKeeu5/Fv1d1bDoKtcIDfodsn/3vfWhXyV+u/Xc+HU0XYAt12gVfnln6rdAbSesuCMxNYSvpmfQc+Mfy0XX/iyo6zt+2YF2l/zfMUHZvc+eGaxTduV6dvW81kICcgAAAAAAAACoNwTkADmAgLx29paAvBx5Ds5P/M0hhRDA7TH8xvg+QV2rgh9bT2GtXy5/f31HsDHgpXPiZQpo/eDB19aVbhh1yjmHmr6PnJrYtvWau04sO+e1wmHNre63k//xw6/EIa3fRj07bR319FQoXmzbCsn8sFlhi1/PVcGzrVtNAKRg9oTTvh/Ul9o3hTuzt3XMq1yPAEshvV+mDyD8dcosBli6f93r+tneB4M60r2mE1eV/yAhjQTk6a0kIH/45XODe8hXQbL/O1guIH9yyAWJ9qrrb/d3Vx0VbMdX9+ObE69OtLv0xv8ulOs3y2/jqmfBtussIH9nyrVBeTn1/Npe8cf96ntBua+OZfqm5OgTF15zdFDPt9qAvKvXs6vntRYSkAMAAAAAAABAvSEgB8gBBOS1Mw8BeSl6e3CuQNK+/LdzR9u/n3HR4UF9ayUBuRts1CIg70wFT/4+yEqCE3nn46cn2rnbLhXqWhU0u227IyBXz+9iAb2verDaNvUIsCoNyCu5Dj0VYLkjGlx/70lBuSQgrx09HZDr3nXvG308o5EY1DN64ODzEx8K6c/unPSlAnKNaOCu8/bHTgu2q3ns3TqaakLPz+CxV5m7n/xNfP+7212wp+NjDfc5kKp7Vd//iUey0DQV7v2pMjtVgMLsfk+dEX9c5Jbb9WoqCH0QU8ofH/Ovie2OXnRroa1GgbDLz7n8CHPXE6fHz7n/EYDK3POgdegDJPd4H3vtvHiZ1Y6ioREidG7c/fB/H9Ncz66e11pIQA4AAAAAAAAA9YaAHCAHEJDXzjwH5KXwg/NGDc9vuL8jSFK4qN7H9u8KTkuFAV0NyDVcucKPI479ZqHs8puPSwQj6q1t11EsID/7siPi8ENl7nqkG95I/d0t/9HR34iH5Vawo0DGD1zVw7ncthX0aNsaIvkXZ3aEqlJDqtu2b0+6Jj5mW6ZA3D1Gbd/WrSQA+mjOjYltaXjmOwaeFg+Vrv3pc/sJ8TXRcrc3ez0CLIXF2n9dF1vXD8izHmDpQxH3WHXv3tj/5ITuPa/zrQ8qpK61v740EpCnt7OA3B0148jjvxVMaaApENwh0PXc2LJiAbk/HYH/PNk67j1UrHe5tus+CzcPOKVQ5j4HquOP/KCe4u763d8YqWkMbJkbkJdTbdznS8+5X0f/hmikCn+5nmvbTvvll0v3WN2pLIp55a3HF+r6v49prmfa85pGAnIAAAAAAAAAqDcE5AA5gIC8dhKQV44bnGe917mCbTc0UE9CLT/qhG8XlikU9dvJrgbkVvWctGUKOf22VjeM0jY1X7pbrm27IbeCMbfs0CO+VihTEO8Pwa3elW7vYbcnuL/tQcMvD/bPHbb9un6/SJTpfNqybxz8D0Fb31IBkI7jkMO/WihTkK45zv32moe7WFBVrwDr5RF/KNT1A/JGCLAuvq7zYeWLqakE/HWlkYA8veUCcn2A414/9fz220t9gGLraAQJu9wPyHUvu8+nPtqxQ5C7Xn3nzwt1NO2BX27VhyO2np4bu9x9Dga8eHbQTmoaClvH/+3uSkDujiSh59b//Syn6rofDegZ9+tU8/tS6vcx7fVMe17TSEAOAAAAAAAAAPWGgBwgBxCQ104C8trg9zr3z3O9dQNN9ay2y/u/8NvCcoU9fjvZEwG5P9+v1R262x0WXr2r7XL1giw1R7mCGVvPDYor2fZ9z51VqKNjcstqFZC710mO+/y2oG1XrHWAVSogb4QAa9i8mxL7WI3aP399aSQgT2+5gFxD+Nsy/S74ba0TV95ZqFfqd+HUc//TnH7BjxL1NAqHvy55/Kkd0x2oh7mmTCjmbY/+ulDva//294X2lTwHf7jluEIdt/e5rDYg1ygR7nFNWnPgA6pi6rdEwf4Vtxwfh/r6aOnkszueSfn+jPC5r+b3pdTvY9rrmfa8ppGAHAAAAAAAAADqDQE5QA4gIK+dBOTdS08F5yec9v3CS38FvXb59I33FJZL27PcNUsBuYa4tnXcQF/DX9vl6untB1Gu7vFqKORKt62h1m0dfx7yWgXk7tzBCoL9dpVYjwCrVECe9QBL50bXx7Y/5qTvmGkb7gl0z4WG07fL3XmiayEBeXrLBeTuB0AKrf22Vg3zb+tJO2pDsakXXPVhjr8u6d4/laoPWGz7Sp4D3fu2jjuahqwmINe/Ae6UA0/85YKgjlVTHRx8yJeCffctNrJDNb8vpX4f017PtOc1jQTkAAAAAAAAAFBvCMgBcgABee0kIO8Z3OB8efREcF3SqBDYDQv83sPqUW7LNES33z5LAfmHs24o1NHw48W2UY22h3Yl2x469bpCHQ1B7JbVKiA/65IfF5Zff+9JQbvOrFeAVSogz3qA5Qbz0p/H3urOxax51/3yWklAnt5yAflND3TcK6Wea2ux+6KzgFzPjMJodz36jXTrKHzWlAKd6X4QU8lz0Pfhjo9p/Oeg0oBcH4zoYx9bt9xHOe5w8FL/LujZ1wcr+t1yQ/a0vy+lfh/TXs+05zWNBOQAAAAAAAAAUG8IyAFywMIVn5gFK0ZjDVy4cpx/eqHOrIyeN/7L9TS6AdKxJ/97UO72vlaI4Zc3QkCuP9vl0g+fiqljVVBb6bbVk9jW6a6A3D0ODSfvtytnPQOsUgF51gMsdyjpcteJgLx29GRArt8iW3bcr0p/sDFv14DE/Th/94B4uR+Q6xkaseDmxEcofW4/IVifO52Bfjf88s5M+xxUGpC7v/3a51JDxs/b+UDi34FfnPmD4DdC/7bY8rS/L6V+H9Nez7TnNY0E5AAAAAAAAABQb7oUkANAYzF99C4z9eMWrIHTRu7xTy/UmVoG5Aq0FQbbF/6a51ZhqavCXjdMeGfytYl1NEJArvp2+a0P/Spo15mVbLseAbnmObbLqxk+vN4BVqmAPOsB1l1PdASC5faPgLx29GRA7g75r1Dbb2t1f1fcQNn9XdDzpXBcy93fAmmXW4864duFsmo/dJFpn4NKAvJh825KHINGn/DrWB/409mFejqP9sMi12p+XyavvTsody31+5j2eqY9r2kkIAcAAAAAAACAekNADpADCMhrJwF5z1PLgHzQ8I55syvVD5nc4PWzvcXnYK40IB84+PygrbWSkLpUQO72XD7josODdp1ZybYrDciL9cL3LRUAaVj1rhxHvQOsUgF51gMsza9s23730C8H5VY3IB+/7PagvFYSkKe3XEDuTy8xauEtQXv5u6uOKtTRlBN2ebnfhQuvObpQdugRX4uHK7dl7n2se2lJyyPBNsuZ9jnoLCDX77g+5LF1Lrr2Z0Ed18tvPq5Qt89tYY95Wc3vywczrw/KXUv9Pqa9nmnPaxoJyAEAAAAAAACg3hCQA+SAGaOagqAXu+b0kc3+6YU6U8uA/ITTvl942a+e5Ap2i/kfP/xKoZ4CcXdeXTfYKDZns8Kfw478ekfw8FIyID/7siMKZX0fOTVoby0XRllLBeT+UMgTVtwRtC1nJdsuF5ArULZlOn9+W99SAdCzQy9OHIfmzPbbFrPeAVapgDzrAZaOy90/fdjg15HuENpdGSK7UgnI01suIJe6P2358ad+L/h45J0p1ybuiWffubhQVu53QaM2uEOp3/fcWYWysUtvS6xTHxAVC8l1Pxb7aCjtc9BZQH5+n47nT6OKlPrwyXrHwNMK9d3fXatGBnGP1z2HVrdX/R/v+HlQ7lrq91GmuZ5pz2saCcgBAAAAAAAAoN4QkAPkgJmjw6AXu+aMkS3+6YU6U6uAfMq6ZFipUNOvY9UQ127dp968sFB29IkHF5b//vpjgrbqfei29QPyG/ufXChzw1DfcmGUtVRArpDE7RGp7czccl/QXgFusZC+km2XC8g19Lx7DgaPvSpo71oqAFrU9FAcWLnHOH3jPUF79Wq+rt8vCn+vd4BVKiCXWQ6w/KHddW/P2d4/qKf7x9a54f7qtlGNBOTp7Swg98Nqfcyje0vz0V9z14mJMvUEd9t29rvgftCiD2P0+2LL3Pm9pT660PQPehY11P8p5xxaKPM/hEn7HJQLyP2PifRhjKZkKKWGjx86NTmk/AVX/9Q8/94l5oX3f2/Ou/LIRJm87KZjg/31z/URx34z/qjgqr7/E5zbUr+PMs31THte00hADgAAAAAAAAD1hoAcIAfMHteKNRR6lloF5O5w3QpJivVgdHV7mx9z0ncKy915m+WZFx8e93pUsOGGuYXg4aVkQO4Ouy0VZCuEUFikeaBtqNRZGCVLBeTS7x2sY1bQq2G1FYYoyLfDxT855IJE20q2XS4gl26oatej7aq3tD4ScOuWC4AGj0ueL+3zH245zjzyyrnxuXWHrLc9wesdYJULyLMeYOnDAncfdJ/oHOnDCZW5H4RYda9p3xRy6h7019lVCcjT21lALh977bzgmvpqKPQxS/om2lXyu6DfMFtHgbJdro9m3NEzyqnfQnedaZ+DUgG5fmv1d3/75bRzk2vKB7/MVc+I+3d/lAp9nOL2uPd1e7GX+32UXb2eac9rGgnIAQAAAAAAAKDeEJADAEBDUYuAXOGMhlS3L/o1pK5fx1ehtxsw2OBawXqxINzV3ZYfkEs3RPJ9ZeQVcZ1KwqhyAbl05+Iup0JQt10l2+4sIH9/RjKgdz3k8K8m6nYWAN395G+CdRTTDafrGWCVC8hllgOsBXsejOcf9/enUnVs/jq7KgF5em964JTCtSn3O6fpIfTRh389FRjr4xl3WgnroOGXF+qdfsGPgnKpYfrthzfSf670++bOaW/Vs6bfIX3I4s5fLq+4peP34aFB/xtsU97+WMeoEToHbplGonCPzy7Xx0L+fnSmPnBSW50ffVjjl+vfBvWkVx1N72CX93/ht8E+a+QLdzoPq87f6MUdvwWdrUd25XqmPa9pJCAHAAAAAAAAgHpDQA4AAA1FLQLyNydenQgN3p50TVDHd+6O/ok27py6Gq5cwbFbrlBDQ2h/PPfGxBzYD798brBuDeFeKsC19SsJo7QtW6dYSC3Vg7lYL2Dtr3osa+hjhaRum0q27YbzGo7cL5evjrqiaA9NhUhuvUoDIB2jvy6pYZHV49kdHryeAZZ6ldoyDRXtr8fuf1YDLH30ce3dJyaCTVfN165zVexaajh7f31dlYC8/urjIX2YoSB7+qZ7g/LuUh+YaJQLTTFQbFj/RlG/5ToG/R4Wm7tc/1ZoRItyx6iPCjRShoZv1787fnk19tT1rFYCcgAAAAAAAACoNwTkAADQUNQiIO8uFWoqpFZA0tmQ7cWcve3+OMhQUKQww+85WUuXtD4Sh7TanuZj98u7SwU2oxbeEve8VFhfLAiuRq1P61GgpOPxw31fAqzqnLbhnnjfdE40F7R639oyzZ+ue/WtT6+Oz4mOxW+fRgJyxHxIQA4AAAAAAAAA9YaAHAAAGoosB+SIWDsJyBHzIQE5AAAAAAAAANSbg9rb24MAvJgAAABZgIAcMR8SkCPmQwJyAAAAAAAAAKg3BOQAANBQEJAj5kMCcsR8SEAOAAAAAAAAAPWGgBwAABoKAnLEfEhAjpgPCcgBAAAAAAAAoN4QkAMAQENBQI6YDwnIEfMhATkAAAAAAAAA1Js4IHf1g3ECcgAAyBIE5Ij5kIAcMR8SkAMAAAAAAABAvakoIAcAAMgKBOSI+ZCAHDEfEpADAAAAAAAAQL0pGZADAABkEQJyxHxIQI6YDwnIAQAAAAAAAKDeEJADAEBDQUBeeyetucuMXnRr7NK2R4NyxJ6QgBwxHxKQAwAAAAAAAEC9CQJyKwAAQBZp9ID85LMPNX0fOTVY3pN+99Avm4MOOih27NLbgvIsOWj45ea3l/7EDBx8flCWdWduuc/0uf0Ec/nNx5lPV98VlGNSAnLEfEhADgAAAAAAAAD1hoAcAAAaikYOyIfPvzkOof/uH/+6rj21p2+6N1jm2igB+ayt9xf2U+p8+nV6yhmb7zWft5e/plfccnxh30/8zSFBOSYlIEfMhwTkAAAAAAAAAFBvCMgBAKChaOSA/IKrf1oISF8fc2VQXksXNz9s+j11hjn4kC+Zbxz8D0G5a6ME5JPX3p0IyD+afUNQp96++OGl5ugTD473RyG5X+563pVHFvb9iGO/GZRjUgJyxHxIQA4AAAAAAAAA9YaAHAAAGopGDcgX7HnQ/L8v/FUhID3t/B8GdWqphvC22+otAbm8/bHT4uO57KZjg7Ke8Mv/8sXCuessIB/3+W3mmJO+Y3509DfM0KnXBeWYlIAcMR8SkAMAAAAAAABAvQkC8iiKYgEAALJIowbkD798bqL3s5y3a0BQr1b21oA8a1YTkGN1EpAj5kMCcgAAAAAAAACoNwTkAADQUDRqQH7I4V8NAnKF5n4968J9D5mp6/vFqve5X26dtuGeuM7MLfcVlmmu7nenXVfYjkJcuy6/riwWkM/Z3t+8POIP5tmhF8fLKp0zXUO7fzjrBvP4G+ebIRP+GK/Hr+OqfbX7ZZctaXnEvD3pmngdb0682szd0b9wnMWOQfvmllWiP1/4ktZHzOjFfePjHfj678zgcX3KfsAwf/eAeD2aT96eu4/n3pjYhl/XdVHTQ8E6XeftfCA+fzoHOp+6H/w6/vp1nuwyncMPZl4ft39n8rXx+vx2WZeAHDEfEpADAAAAAAAAQL0pGZC7AgAAZIVGDMiHzbspEVbbP2uobb+u9c7HTy/Uu+auE4NyqdDT1lFQa5d/63v/VFheTLeudAPyQcMvN4cd+fWgjXqhj1hwc7APVgXdvzjzB0E721aBvd9Gfu3f/r5QT3OMX3TtzxJD0cuXPr4sWOfffPELhXVouHK/vDMVZqvthBV3JOYG99X84p8svz3Yb+2nX9d3/LID7S75v2OCsnufPTNYpxw+/+bE9XDV8Oxu8G7VcPMq13VX8G//7nvrQ78KPgzIsgTkiPmQgBwAAAAAAAAA6k1FATkhOQAAZIVGDMgvuPqnhZDy+fcuMf/8lb8t/F0BrV9fugH51Xf+PCiX6jFs69QqIO/MiSvvDPZDPZXdntSl1DH5bd2A/NfnHRa0UbjuHqfVDcjfmXJtUF5OHa96WKvtcb/6XlDuq8B++qbk8OkXXnN0UM+32oC82DD8vjruN8b3SbS79Mb/LpT/xw+/ErRxVUjubzer5iEgX9v2rvm89SnEXLuidZD/aAAAAAAAAAAAdCtxQO6H4cUEAADIAo0WkGt4dNsjWv+robXdHr7X9ftF0EamCcg1PPmAl85JlP3548sKauhudz1+QK6Ave8jp8ZBrP7XLVOI7bZV0OyG3NqWgl710H7xw0vNUSd8O9F+9KJbE+3dtlLn6PbHTov383dXHWWe+MsF8Tb6PXVGYl/cgFzzratHdyl/fMy/ltwHnQu7/JzLjzB3PXF6vP/atttGZe5+ax3aR+2HrfPYa+clzrMdRl1DnN/95G8S++EH5ArT3e2pF78+ptB5HDj4/MTIA/qzhrK3bd2AXGqfrur7P+a10VeaZ96+KPHBhMo0JLu77ayah4B8ztT1ZurHLYi5dvqYHf6jAQAAAAAAAADQrRCQAwBAQ9FoAbnbK/i3l/4kXqbA1A07iw17nSYglwqNbZl6YfttXd2A/PhTv2c+25uc81xBty2Xmq/blin4dfdB23Xbqq7WaeuccNr3E+V+QK75tv39s2oeblvPDcjLqTZuQKz99evccP8vi/bkVzBt2ym498ulG1zP2JzsZe575a3HF+r6AfmJvzmkUHbk8d8K5ijXnOvuyAMK8m2ZG5Brf/wh4XWfuMPW+x9IZFUCcsR8SEAOAAAAAAAAAPWGgBwAABqKRgvIDzn8q4VgcvC4A0NjKxB3ex6/OfHqoF1PBeRjl94WlEs3nHWHWXcD4tse/XXQTn40+4ZCHTlvV0cPZjcgv/i6nwVtXbsSkLtDoSt4LvYxQilV1x06XiG1X6cWAfmUdf0S50dD1vtt5R0DTyvU0TWzy92AfMCLZwft5CnnHFqoo57ufnkWJSBHzIczx+z2Hw0AAAAAAAAAgG6FgBwAABqKRgrINTy2DSUV6C5t6whnz+/TMYS37VnumrWAXOGyrWMDfQ19bpfJYgGy1Q3YdV7scjcgHzz2qqCda7UBuYY5t/XVg3rSmmTvdleF4RrS/Ipbjo97c2su75PP7giV5fszwuC6FgG5hrK3y9Xb3W9n1YcJ7vHY5ZUE5H+45bhCnZsHnBKUZ9E8BOQLp7YFYSFi3pw1ptV/NAAAAAAAAAAAupWD/CC8EgEAAHqKRgrI3RD899cfkyhTb3I37PSHNc9aQH7crzqGSVegq2WjF/dNHIPfxvXQI75WqPvs0IsLy92A3O2ZXsxqAvLpG+9J9NLXXOZ+Havm6j74kC8V6pay2NDktQjI+7/w28JyDUfvt7Nq3nF3f2ZtvT9eXklArlDc1rn+vl8G5VmUgBwxHxKQAwAAAAAAAEC9ISAHAICGolEC8vm7ByTmffaHzVbva7f88TfOT5Q3QkD+zpSOudT97fsec9J3CnXve+6swnI3INdQ434710oDcvUGP/rEgwt1Nby4X8eqXuO2ntQ1OemsH8Q9rs+65MeJkL27AvKbHugIr3993mFBO1d3X0cvujVeVklA3vfhUwt1CMizw86tEVbh2i3zzaItQ2rm51tGBNvAnhEAAAAAAAAAoJ4QkAMAQEPRKAH5Q4P+NxFmKmz1dQPyo074dqJ9IwTk45fdXljWWQ9ydxsa+twu746A3D13Oi+ztx3oae07b+cDiWvwizN/EITcx57874Xy7grIB7x0TmG5zrPfzqq52209qY8wtJyAHPLCmuiN4D5J47Zokr8JAAAAAAAAAADIAQTkAADQUDRKQK45rN0wsxInr7270N4NeTUvtr9+WWlArhDXb+va1YDcn4N8zvb+Qbu4Xmuyt7zt+SxrHZAPm3dTYp80fLpfx/rAn84u1NMQ6xrC3K9TTUDuXr9ilgrI3TnItR9+O+uHs24oevwE5JAH2syu4B5Ja5NZ728GAAAAAAAAAAByAAE5AAA0FI0QkH8058ZCGCmPOPab5sjjv1VUNzjWPNF2HQMHn19YfvLZxYcIf2XkFYU6fkCusNaWVdO7u5qAXLoBtzt0uuvTb11YqCPdILqWAbnmcVdveVvnomt/FtRxvfzm4wp1+9x2QlAuqwnI/WH0fUsF5FPX9yssl6MW3hK0lb+7qmNO+x8d/Y3CcgJyyAM7ojnBPZLGVdGL/iYAAAAAAAAAACAnEJADAEBD0QgBuRtkHnL4V4Ny1z/e8fNCXXco9HenXZcITRWiuu3GfX5bIlz3A/KlbY8m2g8ee1WwbWuagPyeZ84sLFdY7O/n9I33JELwC67+aaK8lgH5+X06zrvWq8Dcr+N6x8DTCvV/fMy/BuXPvH1RoVw++87FQR0NjW/LdS39ctdSAbnUvOe27PhTvxf0Znfne/f3hYAc8sD66L3gHknj5mi0vwkAAAAAAAAAAMgJBOQAANBQZD0g17zQbnB995O/Ceq4fjw32dtcwbiWK9xV6G2X//NX/tb0e+qMOAA94bTvJ9pIPyCX6mXs1vn1eYfF7RXg39j/5EK9NAG5hll3e1FrPxQ8vzziD+auJ06P99uW6bz483TXKiB/8cNLE8eqfdKc4qUcseBmM3Rq8iMEhffPv3eJeeH935vzrjwyUSYvu+nYYJ+uuevERB2NFqCe9Ff1/Z/4fLt1ywXkOu/ueg478uvxtdJ87f42Dj3ia4m2BOTQ24lM6/57YmBwj6Rxj1nmbwYAAAAAAAAAAHICATkAADQUWQ/IB7x0TiLMnLbhnqCOrxswqxe0Xf7Ya+cl1uXrznNeLCB/f8b1QRur27M9TUAuNbS4G4QXU+G4wl5/vbUIyNVrXX/3t1lOOzf5GRcdHpS5qme5+3d/mPV5uwYkPmTwdXuxlwvIZWfXW37re/9kxizpm2hHQA69nT1maXB/pLL9CRMZ/psGAAAAAAAAACCvEJADAEBDkfWAXD2IbRCpOcb98mK6wanfM1o9mv0AVkOx33D/L82c7f0LyxRQ++uVr466omh4rGDa1nGD9k+W3x6sQ7q91t/69OqgfO6O/nHY7G9LwbjC9U9X3xW0ke6c4RqO3S93XdRUPCB/4i8XBMfXmTbkV+iunuF+uc7Ps0MPDGOu+cnt8v4v/DbYr/HLbk+cQ6uOffTijjC7s/XI0YtuTdxDVh2v5lTX/vptrril4/55aND/BuXy9sc6hpO/6YGOue6zLAE5WDZFI4L7I40bzIf+JgAAAAAAAAAAIEd0KSD3BQAAqBdZD8i7S/WuVu/lyWvvDso6U/ORj1p4SxwKq4d4sZC1lmpftS2F7Z+3PxqUZ1ENja95vj+cdUPRuctnbrkvHpJdHyX4ZVZ9BDB4XJ94+HZ9MOCXV6OumXqK65pP35Qclj4vEpCDZUWNf/d3mfn+JgAAAAAAAAAAIEcQkAMAQEOR14AcMW8SkIPYZ9YE90Za28wefzMAAAAAAAAAAJAjCMgBAKChICBHzIcE5CC2monBvZHGddGb/iYAAAAAAAAAACBnEJADAEBDQUCOmA8JyEGsjl4J7o00bjfT/U0AAAAAAAAAAEDOICAHAICGgoAcMR8SkEOL2RrcF2ltNpv9zQCkJIqH7W81uxCxzurZiwzvpAAAAAAAoHoIyAEAoKEgIEfMhwTksMPMCO6LNK6KBvmbAOgS+tBiSzS+5iMcIGL1Lo8GmjXRa2armRB/WAUAAAAAAFAJBOQAANBQEJAj5kMCclgbvRXcF2ncYj7xNwFQNQrh/HsLEbPj1uhT/7EFAAAAAAAIICAHAICGgoAcMR8SkOebdrMvuCfSus+s9jcDUBWbzejgvkLE7KkRHgAAAAAAAMpBQA4AAA0FATliPiQgzze7zGfBPZHGFe3P+psAqIrd0eLgvkLE7LrHLPMfYwAAAAAAgAIE5AAA0FAQkCPmQwLyfLPRfBTcE2ncZIb7mwCoinXRkOC+QsTsuj56x3+MIeOsm99u5n3Qaia92GLGPt5sxjyKiA3nY83mk2eazYy/tJhlk1rN3u3kBgAAkF0IyAEAoKEgIEfMhwTk+WZ59FRwT6Rxt1nsbwKgYlrNruCeQsTs2xbt8x9nyCDrF7SbsU80mY/vQcTe6MKRbf5jDwAAkAkIyAEAoKEgIEfMhwTk+WWvWRHcD2ltN83+ZgAqZk+0LLinEDH77jOr/ccZMsbK6e1BmIaIvc8Zb7T4jz8AAECPQ0AOAAANBQE5Yj4kIM8vW8zY4H5I43rzrr8JgKrYaeYE9xUiZt/d5jP/cYYMsXNDFIRoiNh7XTy21f8ZAAAA6FFqEpAXEwAAoDsgIEfMhwTk+WVl9FJwP6Rxh+FegnTsMDOC+woRs+9OM9d/nCFDzBnaEgRoiNh7HXZfk2ndR2YAAADZgYAcAAAaCgJyxHxIQJ5PmsyG4F5Ia6vZ4W8GoCq2R9OD+woRs++OaI7/OENGiNqNGX5/GKAhYu92zZx2/+cAAACgxyAgBwCAhoKAHDEfEpDnk21mSnAvpHFN9Lq/CYCqISBHbEwJyLPLttXMPY6YR+d/xFzkAACQHQjIAQCgoSAgR8yHBOT5ZG30RnAvpHGbmexvAqBqCMgRG1MC8uyybn5bEJwhYu93+usE5AAAkB0IyAEAoKEgIEfMhwTk+aPV7Azug7Q2mfX+ZgCqhoAcsTElIM8uq2YSkCPm0UkvEZADAEB2ICAHAICGgoAcMR8SkOePnWZOcB+kcWX0J38TAF2CgByxMSUgzy4rpxOQI+ZRAnIAAMgSBOQAANBQLPh8kpm/bDwi9nJXrFjlP/7Qy1kfvWf8cCONm80YfxMAXYKAHLExJSDPLgTkiPmUgBwAALIEATkAADQU00fvNFM/bkHEXi4Beb5oN63m8/Yw3EjjHrPM3wxAlyAgR2xMCcizCwE5Yj4lIAcAgCxBQA4AAA0FATliPiQgzxe7oyXGDzbS+eT+tfLfJFAbCMgRG1MC8uxCQI6YTwnIAQAgSxCQAwBAQzFzTHMQpCFi73Ptyp3+4w+9mE3RCOMHG2ncaD70NwHQZQjIERtTAvLsQkCOmE8JyAEAIEsQkAMAQEMxa3RrEKQhYu9zw4o2//GHXszK6HnjBxtp3GUW+JsA6DIE5IiNKQF5diEgR8ynBOQAAJAlCMgBAKChmPdJK2LDOueTJjPzk61mxicbeszZE3YF+5VFCcjzw75ojfFDjbS2mT3+ZgC6DAE5YmNKQJ5dCMgR8ykBOQAAZImD2tvbg3C7FgIAAABAcbaaicZ/iVtPN5qPTWSa/d0C6BG2RhOCezSNa6M3/U0ApIKAHLExJSDPLgTkiPmUgBwAALIEATkAAABAD7DbLDEromeM/zK3Xq6K/mz2Rqv93QKoO6ujV4P7M43bzXR/EwCpICBHbEwJyLMLATliPiUgBwCALEFADgAAANBDtETbzbrobeO/0K2n280Mf7cA6kZztCW4J9PabLb4mwFIBQF57Z224R4zetGtsYuaHgrKEWshAXl2ISBHzKcE5AAAkCUIyAEAAAB6mK2mtkNMV+uGSEOu87IC6s/2aEZwP6ZxVfSyvwmA1NQ6IL/z8dPNFbccX7HX3HVisI5G94TTvm8OOuig2MFjrwrKy/ns0IvNRdf+zJxz+RHm9At+ZE4551Bz0lk/MH+45TjzyCvnmg9mXm8+2/tg0A7LO2j45ea3l/7EDBx8flDWqBKQZxcCcsR8SkAOAABZgoAcAAAAIAPsNovNiuhp47/crZero0FmX7TG3y2AbmVd9FZwL6Zxq/nE3wRAamodkH/t3/6+EA5Xqr+ORjdNQH7elUcG58f3/33hr+Kw3G/bHU7fdG+wLEsuaX3EzNxyX7DcddbW+xPnb/j8m4M6jSgBeXYhIEfMpwTkAACQJQjIAQAAADJCq9GQ67UNDKt1h5np7xZAt9Bu9gX3X1r3mdX+ZgBSQ0Bee7s7ILcec9J3zJR1/YJ1pHVx88Om31NnmIMP+ZL5xsH/EJRnQQ1j3+e2E8zf/eNfm/P7HBWUu05ee3fivH00+4agTiNKQJ5dCMgR8ykBOQAAZAkCcgAAAICMscV8YvyXvPV0YzTMtDPkOnQzu6IFwb2XxhXRs/4mAGpCdwbkfR8+1bw66oqyvjG+T7CORrdWAbmGWP9w1g1xoPvUmxea6/r9wnz5X76YCHsPOfyr5vP2R4P1pPHT1XcV1p/VgPyx184r7GNnAbm8/bHT4mO57KZjg7JGlYA8uxCQY5ac9GKLmfpKi5k8qCUo604nvtAcb3fKyy1m2L1heW+UgBwAALIEATkAAABABtkdLTLLe3TI9ZfNPrPW3y2AmrEh+ii479K4yYzwNwFQE7ozIH9z4tVBeR6sVUB+/b0nBeUL9jxoLr7uZ4mQvP8Lvw3qpbE3BuS9UQLy7NJdAfnGxe1m7dzO1z3n3VazdUW7mVLnQLRSF45oNbs2RmbZpM6PBdPrMuy+sLy7bG/r2O4nzzQH5b1RAnIAAMgSBOQAAAAAGaXFbDNrozeN/8K3nu4ws/zdAqgJy6OngvstjbvNYn8TADUhSwH51PX9Yt05peftGmD+/PFl5tl3Ljbvz7jeLGl5JNFm9rb74+0oMFWd0Yv7lu1RPW/nA4XtaP5qv1xqG7aOtu+Xu2p+a+3f029daD6Yeb1ZuO+hbg3Irb8+77BCPc1JXm6u8KVtj5oxS/qaZ96+KN7X8ctuj5f59aSO591p1xXWrR7r9lz416aYc3f0N0Mm/NE8/sb58Xr0d79OOVX/ncnXmoGDzzfvTLk2/iDAr6Ph1e98/PTCPp52/g8T++heM9WtZv9179hzNWj45fHw7H4df1+0Xvd8atmLH15qXnj/92XPdVoJyLNLdwTkox9tLqx/3BPlw8a92w68t6wkTK+3Yx/vOA4x7fXiIb6C3M6OEyvTJe8BeXffVwTkAACQJeKA3NUPumstAAAAAFTHlmi88V/61tON0XATmVZ/twC6zJ5oeXCfpZVpAaC7yEpAPn3jPYlQds72/uaoE75dWGZV+KnAceDrv4vnyPbLpQLje589s2gwefyp3yvUKzW8u8JNW0fhq18uNex5se1rTmxt3/69uwLyCSvuSGxXHwj4dXT8fR85NbE/rhqyXfONu22+9b1/Cuq56vj87Uh9mHDYkV8P6sv/+OFX4qHi/TauD798rvnnr/xt0FYeesTXzCsjr4jrKcD3y33tNVPY7pf9zRe/EGxb6mOJP97x86LnSm20f36b+bsHFOro44wRC24OhsCX3z30y2bs0tuC9mklIM8u3RGQz32v4/+rllv/8P4dgejuzVFQ3tNOeDYZkM8YkgzIFaRuWd5uonZjdqzL3v43oi55DcjrdV8RkAMAQJYgIAcAAABoAHZFC2ve47YaV0evmCazzt8tgC6xORoT3GNpXBcN9TcBUDOyEpCr161tpxD2R0d/Iwgaf3fVgaG0Fbb6ZcW8qu//BNtxA/LB44oH5Or5a+sUC8ifHHJBsK1SdldALo89+d8Ldf1jVZBcKrB21fWasbmj93lXAnKFx369YqrXt99WPd+POek7Qd1iKvBWD3B/uW+1AbnWWex+8z3lnEMTow7oYw1bpmBc6/bbuNtVoO5vO40E5NmlXIDdVdfM6Ugbm3eXDvjmf9wRpLfv/6NfngXXzW+P923bqvagbPnkjuPsziAzT7rkNSCv131FQA4AAFmCgBwAAACgQWgxW80607NDru80s/3dAqiaVdFLwb2Vxp2GEAS6j+4MyBVoKxQtpoaedtu5AbkbOqqn+FNvXmhOPvtQM3rRrYX6Pz7mX+M66p2snr+PvHJuvF7Nme2u45Plye2kDcg1jLq7fvV6vu3RX5vXx1wZB8V+wNydAflF13bMRa5h3d2y0y/4UWI/1Fv85RF/iL3y1uMTZQp+bbu3J11jBrx0TqFMgbiGZbdq+HR3O7om7roUNGt4ddVTr3ZdH7d8+PybE+1/ceYPEuVnXHR4/AGC2mtu9aNPPDhefs8zZ8b1FVD/edjliXnYVcfdR7sNDZXf76kz4l70tm6xgPy3l/4ksQ839j85Hh5eIwxceM3RibIBL55daOcG5FaF/boPdG/powW3rO/DpwbbTiMBeXbpjoBcc3a7jHmseOC4fU17ot6oh4vXy6r1CjLzpAsBeffeVwTkAACQJQjIAQAAABqMnh5yfVM85LrzRgegCprNxuCeSmur2eFvBqBmdGdAXk6FoG47PyDXetQL2l+/VQGmwkp/vvFFTQ8lQvLbHzstUZ42IHd7ZSsM9ue01tDw7jnozoD8joGnJc6XXa65s+1yBcL+RwLSD/qHTr2uUPbp6rsKy3Uu/bZWDeGu4c9t3ctvPi64HgqpTzqrIwRXmG3LFGa7+6B5v/1tyI/n3hgsU/hu253f58DIAqXUvPDu+XDLNFS+uw+vjb4yaO8G7PpgwM6L7gfkxa6XPt6w5fqowy9PIwF5dumOgLwtOTK5WT6l+DbcUFLMe781qOM67N4mM2VQi1n6SZtZOKI1HgLdr+M6dmBzHHaOHNCxbPQjzWb+h63m8wltZvrgFjPigbCdVDtXfy5oLVs7ryPg370lStTXdvx1Wqs+jsc71muXaXj6Oe+2mmWftsVD2pf6CKGcE55rNp/t376uz6JRrZ0Gw/qAQXXcbWk/Zr7ZEu+H9kfzz/vtSvnpn5rN0v3XYdGYVjP11Zb4vLh0NSAf+eD+fRqyf58mtsVq/7Sffj3XagNynYN5Hxw4/7Pfbun0/Be7j3SPLNx/3peObzOz3jqwj2nuq2olIAcAgCxR94BcAgAAAEA6dkWfmeXRk8Z/GVwv10SvMuR6L6DN7DV7o1Vmh5lpNpnh+6/ra8G1rsQV0TNmbfSG2RgNM1ujyWaXWWiaovWm3SRfOopt+8v99mlcEw32N1ESBen7otUlbd5/FnROAFyyGpA//94lwbor9YE/nV1YzwVX/zRRliYgd+cmlwqS/bZSvbkL2+jGgPy+584q1HWDbHe4cPW+99tZ3R7o6mltl1cakOv82XrqOe8OP+6qIdxtPc3xbZcfcvhXC8vVc9xvV85aBeTnXH5Eoey4X30vaCv10YU7fLqCfS13A/JiQ89Lt4e9RkTwy9NIQJ5dah2QD78//P8b+3aGvWAViPpoOHO/nlRQunlZsre5Ra82V04rfgxt/39Qv2NtFAe3Gu7dR+0VUrvtFHb6qJ4tV2DdGQo2/f3p6nG44a3C9O1rw3Uo9PfbFVPnYeOiA/NbF0PDyc//qPi6NMy8aNt/6RRm27/7bFjYHpf77a3LJrUV3X6rd1qrDcj1oUDTrvAaW7brPigRMFcakE95ucW07Ouo66L9VzDvtxn/dMeBaTu6v4rdixNfCJ8Jn2L3VVclIAcAgCxBQA4AAADQoGjI9bXREOO/EK6nOyKGXG8UmqMtZrdZvP+umWjWR++aldELwfXsDv3wvNbDq28zk/1DNU3RRrPLfLa/7FOzIfrArI5e2V/38aBtKfXxyapo0P7z9I7ZFI3cv54pZp9ZbdpN5y+noffRnQH53U/+Jh6yu5iztyV7h/sB+eLmh4N1F3PSmrvioavPvuwIc8Sx34x76bq9mjXktVs/TUDuDk1u50MvZr0C8j63nVCo64a7CqHtcg1TrmHqi+kOw37uFf9VaF9pQK4h7W099az31+9q68mp6/vFPc3d/XSHz6/EWgXk7scEzw69OGhrVYBv6931xIG51CsJyNXb3D12vzyNBOTZpdYB+bTXi4dufjCpENVnT5HwTz1uSwWSLnu2RkGgagNyoVC3HLPf6Qg2OwvItU+d4QeZaY7DDW91jnyqmb9dHyFUwmfDw5B82+qOtn6Y7aPr67fXcW0tEaoXwz8P5VTdSmhtKn6uKgnIV0ytbNQu9QB322l9Fn0YUOw+2LE+6tJ9lUYCcgAAyBIE5AAAAAANzuZonPFfCtfTTdEIE5nKXzxBfWgyG8w2MynuYV1NONxo7jUrzR6zzGw1n5p10VtmeXv3jqygsH+L+cTsNotMy/4zDL2f7gzI35x4dVBeSjcg17zefrnvvJ0PmEv+75hE+FhMheZuuzQBudtW83T77az1Csh/fd5hhbqak1vL9MGAfw4qUeuy6600IPfn7q7UcZ/fltiG1HDt/vrLWauA3O0ZruHW/bZW92ME9bzXskoCcukep1+WRgLy7FLrgHz5pOIhooa6dusVCwkVUvrr8+czV+9nDWmtHtPqEeyyyjsWNyAXCsnXLWg38/a3XT0ruZ/qeWzbqRf8mjltZv2Cjv9PrVeotlxh7MKRrYk51NUjWMNlW/WhQK2Owx+KXijo1nYUrPrntpxu+L9vR2Q27N8PzXm9aWnyvx8Uuus8uG3dgFzonGxZ3m4WDGuNh4t3P0JQmT+n/Dpn6HChe2DVjLb4HLjDiluqCcilPQaF0NpXrXvVzLagV7mGRffbdhaQ+yMeaN+1Hg2zriHq/Q8G3OvvBuQWbU/Piob637stOjDEfBfuqzQSkAMAQJYgIAcAAADoBai37LL2J4z/crheamjuJrPe3y2oMxoufYsZa1ZGLwbXqHeqe35gkeX1c230F7M9mhaP6AC9kywG5J0NRf3Z3gcTPX/ldw/9chwuX3bTsXEvcru8lgG5e2zF5qq21isg17Dmtq7t1Txkwh8Ly6Q+NqhEzWdu11tpQO6e50q3pWur0QHc/dRyf92dWauA3N3/YnO1W915yE8++9B4GQE5lKLWAbk77LYbqO7d3hFAuz1lFWK7Ybk7l/OMIckAT0Gsv71EiL3/j6Me6ihzA3KFpG6ZnP9xa0cFEwaymrvcoleo/rYVLFt2rCvdszftcfgBebFhvKtRwayCXX+5H5j623Gvp/Zp0ovJcr/nvbsNv3e0hon3z7fmhHfxyztT29/8eXsQzEv3AwX3YwhruYBcw8Wr57lFveD9IeT1MYHucYuCbVvmB+Talobp9/fBWul9lVb/egMAAPQkBOQAAAAAvYRmsyUO6/wXxPWUl9H1RT33d0dL4mHA6zVkOpZ2g3nP7Izmmjazx79U0MA0YkB+9Z0/L9TVMN2aG9wt/2Dm9YXyWgbkCuHt8if+kpxD3bUeAfnrY64s1JN2XuyxS29LLNdQ5n7bzqw0IHd7sN/60K+C8nKOWdI31X7WKiBXsG3LPpxVugf5pTf+d6GePsLQMgJyKEWtA/LmPR3vGme+2ZLoVWxDX/W4tagHszuntjuX9s4N5UNNOWJAk3Ffby4a1dHeDcgnDyoeKrttJz6fDC1rFZCnPQ43vFXvYr9tLdUQ75al45P3hhuQq3e239Zvr/NTrK2dw9xvK12qDcjLOWVQx41YbEj6cgG55mS3xPteYr/GPZkMwu1yPyBfPDb8OMG10vsqrQTkAACQJQjIAQAAAHoZm6Oxxn9JXE8V1iq6he6h3eyLh/feGA03K6Png/OPPe/y6On9z+Eo02w2+pcPGpBGDMjdUPPpty4MyisNyAcNvzxoK0sF5Kecc2hh+f/dUzq8rkdA7vbeVg/sRU0Pxcs1VLldLiesuCNo25luQF7uWtz0wCmFepqj2y8v55KWRxL7OXHlnUGdcroBueaf98tdywXk7nl8/r1LgrZWzfFu69333FnxMgJyKEWtA3L3VePIB5vMxsUdweiS8QeCQbenrUK6ldM6AsH1n3UEwG7Pctu2mLs3d6xv7dyO46kkIHeHxnbnIZe1CsjTHocb3qrXu9+uq2qId/W41rzm6iGt8F691y3utZCVBORbV3bU0ccPdrl7npdOKN5WupQKojtTPcg1tLo+vNAxadvuuRV+m3IBuTv8u66leuCX0sWuxw/IRzwQ7rNrpfdVWgnIAQAgSxCQAwAAAPRCdpkFZnk8/HT4wrgero5eM81mg79bkIJIM15H0+gp3mASlDc+jRaQz9/dEUpKDdft1ykXkCtM9YNO3ytvPb5Qxw3I/3hHR891BaIa6t1vK7szIF/S+kg837h7Dp4ckuzN7vZ01/r8dXTm5LV3F9qrh75fblXPfXc/qg3j3SHiq93PgYPPL7Q99uR/D8pdywXk517xX4UyO3S6r3s+5BvjD4w8QEAOpahlQD7huY4g0M4n7oZw6l2scNCi3riqo57mFs3HbNfnvrbUMOX+9qyaB9uiUNQuryQg11DYlrnvJcPnWgXkaY/DDW8//VPpobkrVedi387O3wlvWlJ9QK5Q3KKPI+xyF90Tfrti9boSkGvu+Eped/vtygXk/vzxlTL5zweO0w3I9QGCv23fSu+rtBKQAwBAliAgBwAAAOilNJvNZm30hvFfGNdTDTcN6dlp5phV0cvB+cXGkaC8cWm0gFxDcSu09cNK69wd/c2Rx3+rUO4PEa6hwG3Zf/zwK3GPa7f82ele9xMAAIAASURBVKEXJwJNNyAfvejWRNlvL/1JHL667RfseTARUNcqINeHATqfR594cGIfdAz+8ORueCyfefuiYDtSve+HTr0uWO73Qi91DPo4QefX1tO88DO33BfUm7q+XzyHt7/84ZfPTWxH++3X0b4MePFs887kaxPL9XfbTvfDnO39g7bWcgH58Pk3J/bh7UnXJMrV0/2ks35QKFeob+8ZAnIoRS0D8oWjOoaiduccd3sPLxrdUcf2MHaDaBusSxd/vmtX9XS2uAF7JQG5ehhbuisgd+nKcZQLb6tVoa3/OlgfCWjo9h1ro3j4cUtXAnL3GGxA7veg1nzdfjurS7UBuTtagVAYrZ7jW1e0J4Z+F37bcue4ZW+yrdbbmVqf7SnuHr97f5ey0vsqrQTkAACQJYKAvB5BOQAAAADUjy2mZ4dc32xG+bsEFbIr+qzHP3LA2rolGmfazF7/UkOGabSAXLohsQLLu544PQ5x+z11RmL71tnb7i+0/Wj2DYkyhboKam979NfmsCO/HrR1A3L5u6uOSpRre9fcdWIc7vZ9+NREYCxLhculdANyqeBV58PfL3nwIV+KQ3t/HdIdSl5qiPB+T58Rh+IaGt0eq/ZXIbDfXufFba/5xhVU6/hv7H9yoZ7bW18qgFZPe83RrvoXXfuzwgcNfk93Bfv+dnRtFaZrP2+4/5eFXuYaCt1tO2/nA4kPJbTdy28+ztz77Jnm1HP/szAnuywXkEsND+/uQ5/bT4h7x+u+cIdgl6+OuqJjHwjIoQS1DMjdgNLtPbx+Qcdydwhv28NWusHs2IEHAkq37swyPa/d4Hbbqup6kNcjIE97HOXC22p1h3vXOZ/2enJ/3GtVq4B89KPJgLzcMbhUE5C784QLbdsfytzFb1/uHGsIesuGhdXPAU9ADgAA0DkE5AAAAAA5YJeZb5ZFjxv/5XG9XBO9Tu/ZKtgdLTXroreD84i9w9XRy2a3WehfdsgojRiQ+z25fTUntxsqH3XCtxPt1fPbb+Pqhtx+QD5r6/1BaFrOtAF5KRUeFwu2rdM33mMOPeJrQbtivj/j+qC9lvn1rIcc/tVE3Qf+dHZQp5gKv/3tTFx1Z8X7OWrhLYm2tz92WlDHqmHybb3OAvIZm++Nh+L31+F7/X2/TLQjIIdS1DIgd+cWV09xu3ziC8mAVNjh1a1uCLlg2IG2bs/dxWNLz73thtyrZ1U3B3mtAnINw+2XW9MeR7nwthqnDEoGosWGa++OgFy6r6DnvV/6HLhUE5CrB7xlx/ri18LFLyt3jt1h49Uj3W/bmWkC8nL3VVoJyAEAIEsQkAMAAADkhKZok1kTDTb+C+R6ujOa5+8WOOwzq8wG80Fw3rB3ujEaZlqirf5tABmj1gG5Gy77w2KXUyGlbaeQ3S/31dDgfm9x9Sg+5ZxD4x7jCl4VWmq5H4oqWFYvaLetVG9mDUeu3sd2mXoX+9vWPOBX3/nzwvpdFXC7Q7wPmfDHoH05L7j6p8E6tR2t8/w+R8W95Mcs6Ru0K6aGAr/z8dOL7qc+IDj9gh+Z8ctuD9pZ1Vta585vW+z6jF16WzD8u9Q1UQCu/dDw8347qfN584BT4g8b/PZSQ5y/9enVQTv1QFfPf7++1EcQtt6ipvIBudS50kcHxfZBw9gX276Gvbd1ygXkbk93vyyNBOTZpZYBebm5st2ey8IOr251g1VbtnNDx3tLd8hx1wnPJsP3+R92hK/dHZAvm9RxwFqPX25NexzlwttqdIfAb20Kj0d2V0DuXv99O4qfA+lSTUCu47HYDyx8XfwydwQDv707LYCY9GJ116DagLzS+yqtBOQAAJAlCMgBAAAAcsZmM8b4L5Hr6WYz2t+l3NMUrTebouHBucLe74roObMjmuXfEpAhah2Q19tPlt8ez0M+ac1dQZkC1BELbjYfz70xKJMKZsd9flvcXkN2++WVqJ7v7067Lg6atT6/PCvqowH16Ne58OdNL6eCY/Xc1jlSCN5ZW50D9fDXhwFT1vULyjtTc8hrHnB9AKG5y/351YupfVKPd7X7dPVdqa+D3Ydh824q20u/pyUgzy61CshHP5IMeP3yNXOclNckh1eXnw0P5y/X8N8uc95NBpeay9rtta5e6cPu7Sjv7oBc++My5rHiwWna46hVQD5jSHI/Rj2cXNe011oSw8FrTnK3PE1Arvouq4rcd/qowqWagHzfzo7zt/nzZLCvc7l1pXNg+xn3ROl5xndvSR63hmp3A3SF/X57qWuj4y+23FJJQF7pfZVWAnIAAMgSBOQAAAAAOUQ9uZdFA43/Mrleqid7s9nk71Yu2W4aO3zD2rgpGuXfGpARGj0gR8yrBOTZpVYBuRvqKUD0y92Q0B9eXY5/uqNcIa1driGtXbYsb4979K6Y2pYINYVCdned3R2Q+3Nrq87WVe1m9ew2s2drFPfYtnXTHEetAvIRzvEIHfvySW3msxGtcW9xn9bmZFCfJiBX2K3r7qLj1pzen09si8+HTzUBuTsMulBIrvOo4cqbd4fvvxc510ZuX5tsr31dOLKjzsw3kzuva715WbtZtn/fdS7c9joed93VBuTV3FdpJCAHAIAsQUAOAAAAkFMUUPfskOsDzU6T3yHXW80OsyH6sMh5wby6LnrLv00gAxCQIzamBOTZpVYB+ZrZHSnujnXFh4W2QbA/vLrVfU1pe+iOe7I5CJCL4Yax1u4OyOW6+WGwa9myomOf0hxHrQJyuXJasie3j3vOxEbnWqUJyKV6sLs91DujmoB85IPJ81QMBf4WXc+xj3ecywnPeQe+H4Xe7jb8XvClUCDvtqs2IJeV3ldpJCAHAIAsQUAOAAAAkHM2R6ON/1K5nmrI97yxO1psVkUvBecCcWX0gmk1u/1bBnoQAnLExpSAPLvUKiB3e9Cumll8nTZg9IdXt7o9fee93xFWqxezwtZi4apCTz/YtrqB6KQXi2/TDchnD03WcXtc6xWq31Zq39Y583a77NqYDEq7ehzu8N7qae+XV6t6rfton9TrWqG0O+e2eizbdltXdOy4gnZ/vdINdot9CKFQWussxrp5yRPj9l6vRAXR7vW0aEQDDXM/vP/+e2xPR/mUl5PXW0PMu3Ol+wG51IcWxXqkC82Dvnb/MYx6KNlGH0dYKg3Iq7mvuioBOQAAZAkCcgAAAAAwO6O5xn+xXE/jIdejPAy5Hpkt0YTg+BF9NS89ZAMCcsTGlIA8u9QqIK9EzXk9/8PiIXClaj5mDec+ffCBwNMv7ynV23zWWy3xvk18obnT3s89fRya91zb1j6MHRiG7joeDSuuecH9slqoAFhhs85Z2l7xvgqk5+2/zxSAF7sOOiZ9DFGsTOp86LxMerH0fqnt1FdbzLwPWmu+/67V3lfVSEAOAABZgoAcAAAAAGKazUazJnrd+C+Y6+fjZpeZ7+9Wr6HJrDfrzNtFjhuxuLpnoOchIEdsTAnIs0s9A3JEzI4E5AAAkCUIyAEAAADAITKbolHGf8lcTzdHvW/I9Z1mrlkePR0cK2JnNpl1/u0EdYaAHLExJSDPLgTkiPmUgBwAALIEATkAAAAABOzo4SHX10ZvmGaz2d+thqPN7DWbopHB8SFW4z6z2r+1oI4QkCM2pgTk2YWAHDGfEpADAECWICAHAAAAgKI0mQ09O+R6u4ZcX+DvVlkUSO+LVps9ZpnZFS2Me25vNzPMtmja/r9/ZvaZVabFbDOR6f6XMy3Rtv3n77XwuBC74J5ouX+LQZ0gIEdsTAnIswsBOWI+JSAHAIAsQUAOAAAAACWJ4iHXRxr/pXM93RyN9XcrptXsNjvNnP37N8Ksjf5iVkTPBG3Luar9z/vXPS4O09vNPn/1qWiNdps10eBgm4hp3B0t8W81qAME5IiNKQF5diEgR8ynBOQAAJAlCMgBAAAAoFPUE9t/8VxPFYA3my1x7+/t0QyzLnorqJPK9ifMevOu2WUWmsi0+4dfFe3793Rd9Ga4DcSUroz+ZFqi7f4tB90MATliY0pAnl0IyBHzKQE5AABkCQJyAAAAAKiIJrO+h4cMf7zIstq7Kvqz2Rp9apqjrsyB3m7WR0ODdSLWyo3RMP+mg26GgByxMSUgzy4E5Ij5lIAcAACyBAE5AAAAAFRMFLXHQ5r7L6F7q5vNWNMcbfFPQ0k2RB8E60CstTujuf6tB90IATliY0pAnl0IyBHzKQE5AABkCQJyAAAAAKgazf3tv4jurS6PnjJbzUTTuv+oy6GevX5bxO5wZfScaTGVf7gB6SAgR2xMCcizCwE5Yj4lIAcAgCxBQA4AAAAAXaLJrDOro1eN/0K6t7oyet7sMvP90xCzORoV1EfsTjVaAdQHAnLExpSAPLsQkCPmUwJyAADIEgTkAAAAAJCCdrMxGm78l9K92a3m08QZ2ByNDeog1sMd0azEvQjdAwE5YmNKQJ5dCMgR8ykBOQAAZAkCcgAAAABIzQ4z2/gvpnuzG6OP4yHXt0YTgzLEerlCQ61HW/3HEWoMATliY0pAnl0IyBHzKQE5AABkiZIBeXeG5QAAAADQ+9gXrTWro1eM/4K6t7o2GhwsQ6y3G6Nh/qMINYaAHLExJSDPLgTkiPmUgBwAALIEATkAAAAA1IzItJlNJl9DriP2tLvNQv9RhBqwz6yOXR39OTjniJh9CcizCwE5Yj4lIAcAgCxBQA4AAAAANUdzI/svqhGxe1wdvWzazF7/MYQuYEPxddFbhfM7f9k4M33sVkRsMFesXOU/4pARCMgR8ykBOQAAZAkCcgAAAADoFvZFa+Lgzg/zELH2bonG+Y8gVEixUNxVAfnUj1sQscEkIM8uBOSI+ZSAHAAAsgQBOQAAAAB0G5FpZch1xDq4PHpq/9O2038EoQSdheKuBOSIjSkBeXYhIEfMpwTkAACQJQjIAQAAAKDb2RHNNH7ohIi1dXs03X/0wMEG4pWE4q4E5IiN6YaV7f7PAGQEAnLEfEpADgAAWYKAHAAAAADqwj6zxqyMXjB++ISItXFNNNh/7HJPV0NxVwJyxMaUgDy7rFyxysz/bDYi5sxFy+f4PwcAAAA9BgE5AAAAANSFyLSY1dGrxg+fELF27jXL/Ucvd9QiFHddsHJUQ7h4xQyzZuUWs2FlGyLGEpBnFQXkq6LRiJgzP980zf85AAAA6DEIyAEAAACgLmyNJho/eELE2rrJjPAfvVxQ61C8UdTx6tgBABoJAnLEfEpADgAAWaKigLzWITkAAAAA5IumaKPxgx1ErL3Lo6dMq9npP4K9EkJxAIDGZFe0JgjOELH3uyGa7v8cQMbYtSkyyya1mdnvtJopg1rMp39CxN7qpJdazMwhrWbxmFazZXk+R14iIAcAAACAbmdzNNb4IQ8ido87zGz/Eew1EIoDADQ+BOSI+ZSAPLvs2x6ZWW+1mo/vaULEnDrx+RazcUm+gnICcgAAAADoVlrN9rhXqx/4IGL3uD56138MGxpCcQCA3oUC8q3mM2xQ1+9eYObOnlcztT5/G9h7heyxc0NkxjzWHIRliJhPV81o838mei0E5AAAAADQrTD3OGL9bY12+49iQ0EoDgAAkE22rmgPXqanUesDgJ5DQy37zyUi5tsd6/LxbzMBOQAAAAB0G+2m2ayInjd+CISI3evOaK7/OGYeQnEAAIDsM+Xl2oZpANBzrJ7VFjyTiIiz3m71fy56JQTkAABQlhazxewyC8w2M3n/n8bvdxxiptxqPjHbzVSzxyw2rfvvVsgWe6MVxg+DELH7XW8aY5h1QnEAAIDGgoAcoPcw9VWGVkfE4rY29f4sl4AcAACKsjtaZNZErxv/hS5i1t0QvWeaonX+LQ09xDYzJbhGiFgfI5PNYdEIxQEAAOpD0+7I7FgXmfWftZvlk1vN4jFt5rPhrWbu+61m1tstZvrgFjN5ULOZ+EKz+eTp5nge4pEPNpmP75X7zPD+TfHfRz3StL+syYx7orZhmsJ2AOg5ht8fPpeIiHLzst6f5RKQAwBAwJZonPFf6iI2mjvNPP/Whh5gbTQkuDaIWB/3mhX+I9ljEIoDAADUnubdkdn8ebtZNbPNLBnXZua+12qmvNJsxj/VbIbdF77szpp5Csj37TBmy4p2s3lZu9m4ZL+L2s36BW1m3bx2s2Z2m1k1o82snNYWf8iw7NM2s/STVrN8Slv8ccO21e2maae/RoB07N0RBc8kIqJV/y71dgjIAQAgwfZomvFf7iI2qvvMKv8Whzqi+cf9a4KI9XOHme0/lnWFUBwAAKB2tLdFZtvqyCyf3GZmv91qxj5e297cPeH4p5vMknGtZsOi9jhAbmRa9hqzfe2B0FsB9/yPWuPhq8c92WyGqUd+kePviurJP+mlFjPrrRbz2YiOEH3nhmyOHATZRfeMf38hIlqXTSQgJyAHAMgR+/+T1CyLBhr/RS9io7rOvOnf5lBH9pjlwTVBxPq5ORrrP5bdDqE4AABAbdi9OYp7Fito1RDo/ovr3ujIh5rM1FdbzMKRrXEv67bmbL5H3rstMqtnHeixP+G5ZjNyQHgsPaGGw585pMUsn9IaD60PUI6dG+hBjoil1UgmvR0CcgAAKLDDzDL+C1/ERrfZbPRvdagTjEiB2LOuj971H8tuwYbi/vZ7u4TiAABQS1r2GbN2XpuZPbQlDor9F9V5dfKgFrN0fKvZuiKKe9H3BPpYQUPNzhnaWvN52LtTG5gv+3T/+VvZbtpae+b8QTYhIEfEchKQE5ADAOSKDdH7xn/5i9jobo9m+Lc61ImN0fDgeiBi/VwV/dl/LGsGoTgAAEB6tq9pj4cYVwjsv5jG0BEPNJkZf2kxyya1xfNydxe7N0Vm9cwDPcQ1n7u/H42qAvNpr7fE99yOdd13/qAxICBHxHISkBOQAwDkitXRIOO/CEZsdDebUf6tDnVibfRGcD0Qsb62md3+o9llCMUBAADS0bIvMhsWtpv5H7WY8U/3nuC1pxw7sNnMebfFrP8s/Type7dHZsWUNjN5UH6uy5RBBz422LWJsDyPEJAjYjkJyAnIAQByxYroaeO/FEZsdDUyAvQMK6Jng+uBiPV1X7TaNEdbTWRa/Ee0IgjFAQAA0rNhcZuZ90GrGfVwfsLXejvuySbz2YhWs31tdWHv+oUHhk7315c31bN85bS2+EMByAcE5IhYTgJyAnIAgFyxInrK+C+IERvdDeY9/1aHbkRh3Ibog+A6IGLPujx6wqyM/mTWRIPN+ug9szkabXaauaYt2us/xoTiAAAANUBDgC8e02Y+eYZQvN5OeqnFLJ/cZlqbir+H3rEuMgtHtprRj4Rt8+6w+5rMzDdbzJrZbaZlj3/moDdBQI6I5SQgJyAHAMgVBOTYGyUgrw87o/lmbfRmcP4RMfuuj4aaLdEn+5/hvwRlvV1CcQAAqCV7t0VxMKuhq/0XzdgzKuzdtKTNNO828XDiE57jg4VK1Zzl8z5oqbpXPjQGBOSIWE4CcgJyAIBcQUCOvVEC8u5ll/mMucYRsaEkFAcAgFqzdm57HMQOuzd8wYzYG5z7XovZtoqgvDdBQI6I5SQgJyAHAMgVBOTYGyUg7x72mKW5HIIZERtTQnEAAKg17W2RWTm9zUx8gd7imB9nD20xW1YQlPcGCMgRsZwE5ATkAAC5goAce6ME5LWlOdpi1kfvB+cZETFrEooDAEB30NYcmeVTmFsc8+2st1rM5mUE5Y0MATkilpOAnIAcACBXEJBjb5SAvHbsMgvMyuiF4BwjImZFQnEAAOguWvYdmMN6/FME44jWGUM0xztBeSNCQI6I5SQgJyAHAMgVBOTYGyUgT0+72Wc2m9HBuUVEzIKE4gAA0J007zHm8wltZtwTBOOIpZw5pNXsXM97/0aCgBwRy0lATkAOAJArCMixN0pAng4Nqb46ei04r4iIPSmhOAAAdDetTZFZOr7NjB1IMI5YiSMGNJnlk9v8RwkyCgE5IpaTgJyAHAAgVxCQY2+UgLzrKBxfFb0YnFNExJ6QUBwAAOrFqpnMMY7YVacNbjY71pIBZB0CckQsJwE5ATkAQK4gIMfeKAF511A47p9LRMR6SygOAAD1ZNPSdjP1VYJxxLQO799kPp9Ib/IsU+uAfMn4VrN9bXu83t2bI7Nna2T2bo/M1pXtZsXUNjPzzRYz8sGwne+we5vMmtlt8XpmD20JyrF2Tn+jxWxf0x5Pj+Besx3rIrN6VpuZ936rGft4Zf8mLhzRanZtjMyySW1BGTamBOQE5AAAuYKAHHujBOTV02TWBecREbEeKhAnFAcAgHqjIGbOewQxiLVWH5xsW00ekEVqHZBXOge9wnK/rauCVouipOH3h3Wy7Lgnm+OQ31+eRSv9iGXrinYzckDY3qoQ3WXa6/x72hskICcgBwDIFQTk2BslIK+OZrMpOIeIiN0poTgAAPQULXuNWTymNe7t6r8YRsTaOOy+fAQtjUZPBeSiaVdUchoLP7TV/ePXyaKL9v9b0rz7wDlQSO6XZ1H/XJejfX/V2W8XD74nPJsMyGcMKV4PG8s8/G4TkAMAQAECcuyNEpBXTqvZYZZHTwTnEBGx1hKKAwBAT7NyelvDhBiIvcEpL/9/7L0JeBzVme4/kLk3859cZjKTXGYymUwGBgayOQkJxMN+YQgBhhgCYQlhGQhrgAAGTAgBzGpsjHezmsUYA7YxYIP33cL7bsu2bNmWLVuSF8mWF0m91fnrLc3pPnVOdXe1urrV1fX+nuf3BHfVqa1bJaXf+r4TsVtwk9KgkAE52nWvGh+1g9KtC+L29BUIWFViEeFaaT1zQJvdqjsezV5tXkqq5xeU3y1qQI7rjQAc1d+bZsdEw8aEiLaYWV66Bxvq17e/xzEh9tcmjGU0mDIgZ0BOCCGhggE5LUcZkHsjISJipzXauH6UUuqXDMUJIYSUAnZw8zGr2yjtCucMiYiGjd6rVknhKGRAvqfaDElnD2qz57tWqV0VnAA8m0EPyBGG68th7UrnzyvmKdfXoeUpA3IG5IQQEioYkBfHrYmhYs7m3mLOpifFop3PGcupvzIg90aD9Zlx7SilNF8ZihNCCCkl8EX/nCHml8CU0uK6bXH5By+lTrEDcumRRmc+VPFaR5iMqS5Qnaw6Z6h70IyW3uunxUTN4rj9v+mqmqWzBrbZFe3bFsZt8ZCUl6k1Zr7UMa66Iia2VMTtini8pq4ze3DHsVpK9r9iXNRxHvp2HfsY0GYfz7ZF7ecyJfu5YL5vfbs4l7WfxextrPs8JuYOy7wNqZeAHNaucIbkG6bHksv092z+K+77xjHJY0SF+tLR3h5UQ5eBJaOi9nQo1fNiYtE77tvXxbFUte8H7x325datAPPbY9tw8buZjwfXXa6b7vri9crJHeeIavx060ndrhkeIsJx4/O2+pP2z9EI8/12E+fntr18ZEDOgJwQQkJFIQPyzZHBYuz8nuLPL10pLrnqFHHcvx8rTvzuN8Tp550kbrn/PPHyuFvFprZBxrhydPnuF8Rf/MVf2OI66Muls6ueEHf0+rl9zTYcGWgsp95kQJ6dJmuRcd0opbSz1iXGMRQnhBBSUrQ2W/YX8/qXv5TSrnPD9Kj+o0qKSFcF5ItHOuerrlnSUUWOAFSn5YDzGBGmo4LZDbRs11uyIyzGfOfpOFBn2YGkfowQreHV0FsFLeAR0mM9L9MGuIWvCE/R0cQN7Bf718dAtVIdx+C2fwTt+jg3vQbkmAce7dMlOH+8jnPQQfznGNu3TTTWmMcIcJ6N2xOu4TXODb+704FW7vOGm+8dguV07xs6GOCBhOQ+3vQ+d3rkSOpY6tY53xsE8NFWZUMK+FziIQt9exWvp/aN9xTXUs5hr6KeCz7P+nakG2ek3iC0y9eXd0YG5AzICSEkVBQqIF9a30ecetYJyVA4nWdecLIxthz1GpD/9Izjk+v1ee06Yzn1JgPyzByxthrXjFJK83G3NVm/1RBCCCFdRl1l3LdqKkqpv678iCF5V9FVATlUQ2uEp3gtW0COat90IaREPSeEul6ItZlh4tL3sn8uZUUvQvZs6AE5KsbThbgqOH89PFYDcr0aHyDI1s8nnV4DctiwIXXA8pp5Ccibtmc+UZyPvi90BvCC/OxAXKfmevN66CA8lg83QPWziIcN9GOB+kMdamU4HsrwQl2lc9v4/EjwWXD7bDe3/0zt25q6fvLBBDcP7U2dx+4q9/PIVQbkDMgJISRUFCIgn7C0l/jasccYYbibvZ7vYYwvR70G5Kiwl+v98YXLjeXUmwzI0xMXLWKn9b5xzcrBL2qeFk8Pu0bc8PtzxAU9uokf/exfxQ9+8i+B8Yen/au47LpTRb83r7enZdDPj9JSt8Wq1W85hBBCSFGJtgixfqpZtUUpLS0XvmWGbKTwdGVArlY9o0oYr6F1NipzEQJK1IB8zQRnaI31qmbG7JC39WDHGLSmVvezd0vHfhBA7t+ZsKfZwLznelU5WmKr49TlGIsxaCu+exNyso6qYLnusvej9n7V2AtV8XhNqlYtzxrgDLmx/Z2rO9qrox24XiGvz9OujpXUr0/Y+0Ggihby6vqZzCUgr57vDEvxGh5a2LU27gjPcR3kGP0hBexjy4KOFuvyM9BU6/ys6A/N4PrUVybaf5/HxOZ5sWQ1Ol5Xq/9xzVUQGGMMWp3j+qjgwQI5Tq28xrHrLfShGlLjGsvXl33gPFaE3Pgsoc16zdK4/TlRWT4m9TeJGpBL8N7i4QB0D2jZb9nbx8+FClr668eHY1bBPVVfpzMyIGdATgghocLvgHxh7bNGCH7/k5eIjxc+ZLdTr2odJBZsf0b0HfFb0e3Ub4dmPm6vAfn7s+6zq8gvv/40sWLPC8Zy6k0G5OnZa802rlfQHT72VvG9H3/LuPcE2TPOP8mepkI/V0pL2b1ihn7LIYQQQooGQgy0TtW/7KWUlqazBkVE5Ij+k0wKSVcG5Ag8JXoF8caZqVBODcjVebARjuqV1QiYET6rr6HSF+GmW6ioBvEIxNVlaoSlt21HW2+E9fr21OB6/qvm/qRoKS5BoOp2bHhQQEUNbfWA3K19t1dzCcjRflwFLcLlMlx3Ca6dfB3zdavov5fxcAGqs+W/8Z6qoTKOCXN/68eCuenVcbMHtTkq8vdtMz9/CMpVZDt17FO9pngQQB2H5eq2EVonj1XJpRH0659JPECAz7AELdTlMj0gxzG4nStUW6/rn0e4aU7qZybb+5iLDMgZkBNCSKjwOyC/7o6zHCHPiAl3GuuEUa8BOfVHBuTulFtr9dlVT9hV4nq4XC7i4SL9nCktddva78CEEEJIsdErASmlwdFLi2TiD10ZkKNiWqK3BE8XkKshIFj4tnuY6FW1jbp+DHElu8R56WPd9BKQo5JcRQ+MpQha0QpcolYeq/vBnNr62FzMJSBHmK2iTl2SLiBHkK2Sbl51qfreAwTs+jpu4ve+BPufNdBcB8pOAwBzmMvX0f5coj8soVaYqwE3qtMleK9QLa/vD+KzoCJf1wNyVMfrY6VbvlDep1azJb3aan/H8szXOBcZkDMgJ4SQUOFnQD698s+OcAdtgvV1chVzmY+ado8YMfFOMWdzb7Elnr7t8PrDA8Syhj6i8tCA5Gtr9r9oj3970u/tynW9bTG2N2P94+LlcbeK8QseFKubXjS2K0XIje2vauxn/3vtgf72GIydvOpRsbFloDFGHSuvi1tAjv1i26r6sUqxnymr/yRe+eg2W+y7OjrEWE/fP7apXj+8NnLK3fa1qdj2dMZrq4v35cM594tXx99mX79s+4frmlPX67Plj9j/1tfxSwbk7tRbE4xrFVTfnXqP+Nu/+2sjVC4n3e4VlJa6jWKefushhBBCCgYCjXWT0n/BTCkNhmr7bVI4ujIgl22ygRFIpgnIEbbq0RLaWKNKV9++Lqq00aocny3sD1XKh/c5N6aujy4kKjiObGGtl4Bcbx+OdtrpVCup1bbp6n7WT8vvd14uATlazKuoy9IF5FCtfgao7lbn8FZVW7Wj1by+PJ1qC3TMCa8vl6rzhcvW/lCfS13OLw/R6lyC1vDydTVUR2itv3+qKnLbekDu1tpdimXqZ1+d0x4PA6jg50Qf31kZkDMgJ4SQUOFnQH7lTd2TwQ7mIEdLdX0dr6Ly/B//+atGYATv+uOFrtu+588X2cvRohyt3NXjkX7lmL8Sb3x6hx3oPvjML+1/6+v0fOpSo7Uxwnf13LCOPg5i3uPFu8y28dkCcrSb17eF6lh1nU8WPSQuuuJHxnrS2x++wPFwgNux47rO3PC4fQz6+B93P07M2/KUMV6Ka/qHJy52vWYQbeHnbHrSGIcHG04/7yRjfYj3CmG/PiZfGZCbHBabjOsUVEdNv1d86S+PNj5P5ebRRx/leq+jtJStaf+7IioO6LcgQgghxHeaGxJiySj/vhSmlHatenhJ/KcrA3K14lWvgk4XkOvLJHIO73QVvJgj20skpY5BIKkHuwDHg8pzfR/QS0Cuh6VeQXt5t/1gfmp9H7mYS0CutrhHxbS6LFNAjmNUW5RLmnaYQTnmDZdk+wypqvO2o32/vlyqhvz6OeDnQYKgHq+hSl6C6662UFdb9OeCfNBCDchxffRj1d2/M3UR8YCJfH1LRep9yeWhAi8yIGdATgghocLPgFwNXR/rf4Wx3Iuomr615/lGUKSLQHlJ3fOOsXc/9ovk8nThutQtIFa99/GLHdtG8Kyvk04EyGPm3u8Yn29AXh0bkjaYVu1+7onGttVjx74R8OvjpFiGQF3fBqrUT/zuN4z1dfX9Dx59s7GOm8++fK2xz3xkQG5SZ31kXKcgiocwyr1yXLXy4EvGNaC01N0vFuu3IEIIIcRX6jckxJwh+YUElNLSkyF5YenKgFxtH475ttVlmQJyiDm31bmfJdimWvkL92x2JrMIIvG5atqecISqQN8PKtPVymQVhO76+l4C8r1bzOPx4pqJ7i3W9fPN1VwCcrWzg1p9DTMF5LDitYg4rDwUoa677vNUVTaOQZJLq3D1YYbalenHrf4k9cHTj3PFWLPlvjoXPCrG1fXVYwX6e+Ym3jtZKa4G5HhdP1bd5R8qx55IhfXqHOdVSoW7HzIgZ0BOCCGhwq+AHBXZaqiDamd9HS8O+/AWx3auv+tsMXZ+T7sl99PDrnEsu/qW0x1j1YAc/svxXxe9h1xlt2f/3QPnuwbMN95zbrKFOyqo1WVqJbgekCNIxrbRMhxtzrF9fd9qFXq2gPz1T24Xz7/6G0ewP7vKWUH+SJ/L7NexDs71pXduFP3fvsGoKkcLc3Wcfuzwwst/aIfXuLYP9P4vx7Leg69yjEdgjvNR1+n59KX2dUOb9aeGXi1O7vZN+/Wpa1LV4Agy1TFnXnByspU93mdUj6vL0apdvy6ddbs1Quy3liRtFTuThpGDVqVxjYKq/rkpdxmQ0yC603pfvw0RQgghvoEvb/UvdCml5SND8sLRVQG53qpbbVsNswXkUrQXV4N2oIa86hzRAGG53sZaRd++dN7LEUdLeEnlFOdxewnIEd5K1Pmsc7ErAvJ5w53twNX5u2G2gFyK6ns10JWgBT6Wqw8toM29Pj6davhevz79OHUee0zLoi9Hq3QJwnT186VXu6tdEHZXpd9nOnMNyKHadh9zo+O6SXDdvUw3kIsMyBmQE0JIqPArIEdrbjXUcWszns0NRwY6AmK0QNfXQVCu7kcNZNWAHCE05txWxyLQVcfqVcsIgtXq6rc+vyu5TA2ZEbSv3Nc367Gp288WkEtPPeuE5Hp6QI45u3s938O1whtBvxx38a9PcSzTA/JH+15ujMe1lsvPvvA7jmWoppfL8P64BdmocEfrdvlvzGeOanI5DtvQ51THQxVoyy7XQXt6fbuFtN76JKlbmF5O1FnjjfMPopgeQf0sh0EG5DSoxsRB/VZECCGE5EWsVYi1nzEcpzQMMiQvDF0VkKuVt6iEnTnAudxrQA4RCOrhtQyn0bpd0tzgvh0VfZkuKozVcFqf61pdtmCEe3CNSnAJzl1f7sWuCMj1yvdlHzjbzHsNyKXV853Ba3VFx+9zfG4k+LnXx6XTMQe51rJfFeG5xK0d+dYFqeuhhtHN9ea66jz1uRyrtDMB+Q6lzT2Of9ui1L9R4a+vn68MyBmQE0JIqPArIB898w+OUAcBqb5ONlFdLMcjqN7YMtBYB15y1SnJ9TDvuHxdDchRXa2PQ0W3XI6QW18Ob7n/vOQ6qBCXr6shM0JifZz0949emFxPbTfuR0CeybnVvZPjUM2tLvNy7Gq1t3p86vzlEFXn+lg3UZkux3z/lG/ZAbq+DsSDBnK9dO9JKZgpSC/1ML1FbDfOJ6ie8h/OLg9hkAE5DaqHrc367YgQQgjpNIf2JsTikfmFApTS4Dh7EEPyQlDsgBxzhKuhNUBAq6+XS0Bub7dvmx02S7Yv69im2oYdVev6OKiiL3MTbb8lesCtBterPnafp3zOUGclNgJZfZ1sFjsg36bNm473WV8n14Acqj/TMmBGUK7idY71bcp54H1xq6TG5wSt0yUI1fV1ZvRvs49fZ9n75vupVqODXP8u6UxArlaMA73iXV8/XxmQMyAnhJBQ4VdAjpbqaqiD6mB9nWw+/FyP5PjbH77AWC5V57W+9JqfJF9XA/IBI82AHMrl6cLYP790ZXIdVGvL172EzHDq2seS6yHkl6/7GZAjtEZr9Tt6/dxulY4x191xVnIcVNf3cuyo3ncbj7nH1fPx+uADqufluNPPO0kMH/O7tKr71av+g2YpVqXvsWYYxxlEl9b3EUcddZTj8xIGGZDToNpoVei3I0IIIXkQOWKJph0Ju1Vr1ayYXdW2ZFRULHw7Yn/hOv+ViN0KFKESvuzFl5yzBnZ8Gbt0dFSs/jQqNsyIia0LYmLn6rjYW50QLc3B+L4O4fgXb5hf4lJKy1vc1xiS+0uxAnKEephnWp0nGqBCV86jrJopIEebdLSWVl9DBboKfq/h9daDqf3pYSj2i9+jKviMyeX4Xdm4PWG3V1fH1W9IjUHMpS5Tz2/fNjN8lR7ao1TQt/8n5pbW10HgjGpn9ZikxQjIETCv/Cgq9u90XiNQ8bq5z0wBOUJvvCd6aN12KHUdWvZ37BvvpXp+OCa3/S1+N2pXtav7Vx+SaNhoXn91PnGw8C1zu1Cfdz5dK3y061cDd4TVbu8X3iO34+lMQA7d7oO5jM9FBuQMyAkhJFT4FZAjvFJDnYptTxvrZPPKm7onxz8z/BpjuRTzXsv1UJ0sX/cjIFfnOe9MQL5m/4uO64DgGa/7FZD3ef06Rxv4dKpjvB6723h1TvhzL/qeMSadN9x9jnFMXpy/9SljW+VqpiDdrzC9/f/aiBrrFWPfQbTviN8an5cwyICcBtV68bF+SyKEEOIRfMG/fXlcVE6K2SE4Qm/9C0y/RFtazKlaV5lwzANaKiAcTzevK6W0/EXbardwiHSOQgbkAIGlGnaqYG5nvU23NF1Ars6DjeAUgeeutXH7oTEVWe2rtsAGCD4RrtcsiRthPVDnQm/anhqLqndUpSMsVqMtvUW3HqziGBEMowU85quW66GKXA1zAa4dqtNrFsftcF0ud6vWLlRADnB+6d4zLNs0170SP1NALluVY7t4IA/nqf8cy4caoD53PMDDDHgP0GJcfcCgcnLqeLBcBftAhT4CenUMwHuin4NUDa5BlfK50EWnABWcO94/VLTjIUa0PZfo3RI6G5Dj70EdPDiir+eHDMgZkBNCSKjwKyDH/NJqqIMQW18nm+df+oPk+HQBN5y00lnVLF8vhYBcvw4Ltj9jv+5HQP5ov185tv0vx3/drhy/74lLHA8XQHWc12N3G/9In8uSr2Ff+ph0Yh5z/VizieuCNvj6tsJuPlXp+8VSY3tB9baH/tPxmQqLDMhpUK2xXtVvSYQQQjKAL3LxpeTike7hQbHEl7frp8TEzjVx0drFFeYIxwv5cAClNBii6jN6RL9DkM5Q6IA8HQjz9Gpi1XQBudrePB34/SnXR+eUdGGvRJ1nGrGVrBjXA2w39MrvOUPM4FsFxyPXxVzkmdaV4Jj0OdoLGZCnAwG/W3W0NF1Ajr9jsoGHJdBlQN2eXu2dDvXzga4Aegt/NzBG358uKtoBrrVblwNVBOFe0CvROxuQ61MKAK+t6HOVATkDckIICRV+BeQQc1/LUOf6u842lmfzmlvPSI5HUK0vl46ccndyvR93Py75eikE5Hol/aa2Qfbr+Qbk6pze8E8v/soIk9Xl6utej91tPOZyl69d0KObMSadV99yenLck4N+bSynhVEP0nda7xnrBNUevznV8RkNiwzIaZCNiD36nx2EEEIU8KVu9fyuD8XTOWtgxJ7D1a3daqFBOK4fD6U0vK6blD10I9nxOyBvrjNzHwR5qPBurrfsau+l72X/HYffNRK1ShsdBND23C1ewmsIVeW0IlKEkGorbwnaYS8fE7XXVyvQ0Vod4/D7WK9Ml6CzC8bqxw3R+lsN3VXktqWoJE/3UAFCY1Q5Yx19H2pbb7f247m4pcI93MX87ajA3l2VsNvj6+N01Tb3eC/k63iwDe+Leswq+NsnXfCODgPp3gMEyg0bEvZ0Mvo4VLnj+ulgjFqpnklZpY1j15e5uaT9c+3WlQDgWqIzj/6QHzriSHIJyKH6mcZnWV/ulwzIGZATQkio8DMgx5zYarDzRU1ubdYRSMuxdz7yc2O5VA2xUTktXy+FgHxcRSrIRlW0fD3fgPyuP16YfP13D5xvjINyOVRf93rsbuM/XpiaW149n2yqc7nnUnlOaToxl736GQ2LDMhpkG21Mne5IISQsLJnc1ysGGd+wVvKYl7S+g3uX6r7DcNxSqmbXqqJSWb8DsiLJSpoEXyv/Sxmh7cL3oxkrfKVU4ggpJ7ez1yOClxUdevLEGoiqEXbb4Ti2SqPpeh0IMe4hbi69vrtx4egVT+GchEt8leNj3ac56ioPYe3vo6beG9xXXA98V7oQXM6Edpjf3hfvb5vqnhQI9dxeO9wjGj9nm91fybVSnlUsOvL/ZIBOQNyQggJFX4G5MsanNXTF17+Q1HV2lFB7SZapc/c8Hjy3698dFtyLILc6ugQYwxamKuV6g8/lwqxSyEgv+iKHyXXUyuuVzX2S74O04Ve6QLy7ueemHw9Xft6dfvq616P3W28ftyvfXy7Mc5NtcofylbzlHbWn52T+hkIk+nuFZQGQQbkhBDiJIjBuO6it6OiZkksbdVUvjAcp5SmE5W/XdHRopwIakBOaZhFq361Qt7LAxidlQE5A3JCCAkVfgbk8N7HL3aEOwh8V+zta6w35P2b7eUnfvcbYv3hAfZrCNMR4MqxvQdfZYx77pVrHdtftPO55LJiBeQYu+HIQGNsn9evcxybGmRXx4Y4lg149yZjPEwXkF9y1SmuxwXx0MAfnnBedwTbcnk+ATlEBbg6fvKqR42xCPHwsMLqphftf6P9u/ogw5kXnOw4Jikequg9xHyfKdVlQE5p8GRATgghHZRDMK47d1ibqFnqbzXngV0MbiilmUW7bsvfW0+oYEBOaXBE+360iFdb+GOudH09P2VAzoCcEEJChd8BOUJQtBDXQx60R0YL9suvP81u1a0uU9upDx7dEZxLr73tTLtqecTEO8UNd5/jWPZA7/9y7LtYATnEOT7W/wr72B4fcKU4+8LvOJaff+kPjG13O/XbjnVQYT+3urdjnXQBOfahHjvC6Pdn3SeGfXiLXamubheOmnaP67F3JiBfua+vvU91Od6Lfm9eL14ed6u474lLxNeOPcZ+/ZE+lyXHIUhXx2CdB5/5pd0pAO8PPg9yu6+Ov804HkpVGZBTGjwZkBNCwk45BuO6+PK2YWP+FZ0H6lg5Tin15sYZ5R/gFAoG5JQGQwTjOqgiz3cO+mwyIGdATgghocLvgByua+4vLv51quI5k+de9D3HXOVb4kPtwFxfT/ey356WrDyXFjMgzyRCbrWyXYpAW18Xwb+6TrqAfGPLQLvaXh+v71f+N8JoWc2db0AOMbe6Wt2fTuxXHffSOzca67iptqOn1E0/A/Ivfelo8e1/+7r49gn/t+D+4zez/9xkkgE5DbIMyAkhYSXWZomNM2PGl47l7OpPop1ufVzoaihKaflZt65z95uww4Cc0mDYsMF5j0MV+fxXChuOQwbkDMgJISRUFCIgh2j7/eSgX4sfdz/OCHwg2m8jxMZ6+liIOay/f8q3jHGo3Eblsr4+RCWzXG/Qe/9tLIdyebqAXG3h/mjfy5Ov6wE5KuL1Y0NlPKra3eZOl771+V2OoFsPyNW5xudsdlaXL63vY1ed6/vFsWAud+z3vEu+b4zHgwTytUwBuVolri+Daw/0tyvHZbW4KsbiwYaKbamHHaTztjzlWuWOMTjfZ1++1rVlPaWqfgXk/3X1T8TCHc8a2y+knyx6SBx/0j8Yx+JFBuQ0yDIgJ4SEkd2b4mLhW4X/ArNUxYMBbQf1q5KeaIslpvc1t0MppZnEHLyH9jIkzxUG5JQGwy1fxEXksCWaGyyxYXqsaH8rMSBnQE4IIaGiUAG5KuajRrtttP2esb4jyNXXSeemtkFiyuo/iQlLexkV48XUrQobx4PzmrCkV84hFuZl/2z5I3a1vb4sm2h5jopuBOCY21xfjvAP18ttmV8irMcxTF37WLJSPZs4njmbnhTjFzxoj9eXU5pJPwLyo446ypjWoFg+NfRq43i8mOu9hdJSkgE5ISRMhLFqPJ0Vr0bE3mpvwRVCLn08pZR6ceW4qH5LIVlgQE4pzSQDcgbkhBASKooRkJeDbgE5pbR4+hGQf+kvjxZL6p43tl0MvU43oMuAnAbZ/WKR/mcHIYSUJWGvGk/ntsXm/JkqvGaU0nzdUpH5PkOcMCCnlGaSATkDckIICRUMyL3JgJzSrtWPgBz+9x/+n9jYUtyW/gjlu536beNYvMiAnAbZ7dbrIiqa9D89CCGkrKieHze+XKQp102KibZD5veCy8dEjXUppTRXZ/RvEwd3e+tYQRiQU0ozy4CcATkhhIQKBuTeZEBOadfqV0AO//bv/lqcecHJ4qyff6fgnnrWCXblun4MXmVAToPuPjFH/9ODEELKhk1zGI57cfG7EdG4PRVgrfuMregppf65diJbrXuFATmlNJMMyBmQE0JIqGBA7k0G5JR2rX4G5EGSATktB9tEnf7nByGEBJ6NMxjy5uLMAW1ix/K4qJrF60Yp9d/dVawi9wIDckppJhmQMyAnhJBQwYDcm1Wtg8RPzzje9uJfn2Isp5QWVgbklAbXPWKK/ucHIYQEmtWfsD04pZSWkovfZRW5FxiQU0ozyYCcATkhhIQKBuS0HN1ujTBeo8GWATmlwbaVVeSEkDJh4dsR48tESimlXe+2xXH9lk00GJBTSjPJgNzngDxq7Rf7EyvEHmuq2GWNFbXWe2InpbRLxM9fnTWu/edxmmi2VouYdVC/P5AQwoCclqO7xeeOz3mr2Gm731risN76xFYfT0tPPwPyr//DMeKCHt3Ezy/7YcE9+8LviP/95b80jsGrxQjI1x7oLx7pc5m45KpTxInf/YY4uds37eO+5tYzxOiZfxBbE0ONMeXuqsZ+oufTl4p7H79YLNr5nLGc5m6jNd9xXyaEkCAya6D5RSKllNLScPbgNnGkiYV6mWBATinNJANynwLyhBUVe61ZyS9EKKWl6T5+WRl6GJDTclQPyHPBLUxnkN71+hWQ3/7wBaI6OsTYfiFdua+v+MnpxxvH4sVCB+Qjp9wtvnbsMcZ+Ve9+7BfGuHL3vicuSZ5/j9+caiyX4r0N4wMEnbHWGiksUf7/Z5sQUr4wHKeU0tK3cgpbrWeCATmlNJMMyH0IyONWm12lqn8pQiktTeutT/X7BAkRDMhpOZpPQO4VtyCdYXrh9CMg/9JfHi2W737B2HYxHDjqJuN4vFjIgHzOpieN/f3jP39VfOWYv3K89tbndxljy91b7j8vef7nXvQ9YzkeLEAXAixHSK4vp+4esqr0WykhhASCBSPYVp1SSoPi3q0J/TZO/gcG5JTSTDIg9yEgR/tm/csQSmlpu8+aq98rSEhgQE7L0WIE5LngFqYzSM9NPwJyOLvqCWPbxfCJgb82jsWLhQzIURkt9/Mvx39dTF37WHLZ4l3Picf6X2G3W9/UNsgYW+7O3/qUuPDyH4ozLzhZTFz2iLH8uH8/NnntGJB7d7eYrN8eCSGk5FkxNmp8eUgppbR0XfYBq8jTwYCcUppJBuR5BuStiXrjixBKaTCMigP6/YKEAAbktBwttYDcK25BOsP0Dv0KyDEvOCqn9e0XSrTffn/WfeLb//Z141i8WMiAXG2tPmr6vcZyml4G5J03Lg7rtz5CCClZ1k+NGV8cUkopLX13rWEVuRsMyCmlmWRAnmdA3iQWGF+CUEqD4QGxQr9fkBDAgJyWo0ENyHPBLUwv5yDdr4AcHnXUUeLYb/yt+Id/Krxf/fuvGPvPxUIF5JWHBjj2g4pxfR2vosJ88qpHxcvjbhXjKnqKZQ19jHUyua65v5iwpJcYPvZWMWFpL7HhyEBjnarWQfZ2odtyKVroY51Vjf0cr68/PCA5fnNkcPJ1dBTAfsfMvV8sqXvesZ5UraCXy9GKXl67aesec6yP9bbEhyb/rR+LrnpuhXq/S8kjYqt+OyOEkJJk68K48aUhpZTSYMgq8hRN2xOiuiImlo5mRxRKaWYZkOcZkNeL8caXIJTSYNhglX+gREwYkNNyNAwBeSYiYo9xTYKunwF5kCxkYKrupzMV5Ai2r7vjLOOYIQLk1z6+3RijOnj0zXZrd30s7H7uiXblvVz32ZevTS57+LkexrYgrpW6f3WZOqc4gnzsW62gl9u9648XGsfSd8Rvk9u5o9fPjeW6FdueFgtrn03+G3O6Zwr173/ykuS62L++vNxstBbotyxCCCk56isZjlNKadBtrLH023toQCiOQFwPxee91ShWL91IKaWu1mzfpt9Oyo6CBuQ7rLeML0EopcFwp/W+fr8gIYABOS1Hwx6QC5EwrknQZUDuvz894/jkfk787jfEmv0vGuukExXjahV1Oi+//jS7zbw6dsXevvb83vq6biKExxg1IH/o2V8axwOxrlwnU0B+5U3djf1AVJBnC8hvf/gCY7kuAnKse/aF30m+NuzDW4zjlaoPCXy23JzvvNxElwtCCCllWg9aYv4rZtBCKaU0WFZOKv9KSAkCcRmK69dBdd5bTaLWmkMppa4yIM8zIN9mveL4AoRSGhx3WO/o9wsSAhiQ03KUAbkQu6wxxnUJsgzI/XfAyBsd+0JFNV6rjg4x1lVFS3AE6nIcAt5+b15vt1cfMfFOI4Du//YNjvGX/fY0x3JUob86/jYxfsGD9roX9Ohmv/7CG6lg2s+AXIpq8NEz/yB6Pd/DruLGemj1/vyrv3GE22pAjvnrR027x1F9jvAbr0llS3a8Ltc596LvGccLEYjLdTCvub68HK1p/7uDEEJKmcopmcMFSimlwXBG/4g40lS+VeTpqsQzyYCcUppJBuQMyCkNrTust/X7BQkBDMhpOcqAXIi91mzjugRZBuT+i3my9TAbysA7XVCutgQ/84KT7Xm59XUQMst10GJczvuNAFnd1xuf3mGMhZjXW/233wF5n9evM8arqueoBuRShNly+cp9fY3lcGPLQPvc5XoLtj9jrHP3Y79ILv/jC5cby8tVTANBCCGlSMNGtlanlNJycktFXL/VBxavVeKZZEBOKc1kY1uNfuspOxiQU0pdZUAeThiQ03KUAbkQB6xVxnUJsgzICyNC8D+/dKWxX3hyt2+Kjxc+5Fgf1dHqOot3PWdsE6KterdTv51cb8b6x+3XTz3rhORrqBzXx6XTz4Acx6W3fdf1IyCHt/Y8P7mePnc6jkFtU/9FTUdr9jB4yNqk37IIIaTLibVZYsFbESNMoJRSGlwrXouIRIAzcgTi1RWxvEJxVQbklNJMNlsMyBmQUxpSGZCHk00N00RV/WRKy8qahmX6Rz10tIgdxn0+yDIgL6zp5t+GY+ben1xv6trHkq+jOnr4mN+lVZ3j/JWPbrMDYbWiGu3K9eNIp58B+YPPuI9X9Ssgn7L6T8n1UJmvBvOfLHoouez0804yxpaz+63i3KNbmy3RWGOJ+vVxUbeO0tIXn9XGmoT92SXFp2p2zAgSKKWUBt9daxL6Lb+kybdKPJMIyDduXRk4q+tWil0tq8ResZpSWkAZkDMgpzS0MiAPJ8tnHRHLpkUpLSsrV9bpH/VQstMabdzrgyoD8uK4fPcL4sZ7znUcA0JtOa82gm/9GL2Iuc0X7XzO8RpavOv7T6efAfng0TcbY3X9CsihWkmvPmxw20P/mXwdLe31ceUspoAoJNsWx8SCNwvzpSKlxfKLNyJi26KY/vEmBWLftoTxHlBKKS0Pl30Q1W/7JYUfrdPLTTm3Oq4LIYT4CQNySqmrDMjDCQNyWo4yIO+gSSww7vVBlQF5cUXFt3ocr46/zX79kT6XOV5HVbQXJyztJcYveNAxTt9nJv0MyF8ed6sxVtfPgBzj5bpX33K6/Vp1bIj42rHHJF9f3fSiMa6cbRCf6rcrXzjSaIlF7/CLRVpeLngzIg7tZUV5oVnyHu8dlFJazqKrUCkhA3GG4illIM5QnBBSSBiQU0pdZUAeTlbMihjhIqVBd+OKZv2jHkpaxS7jXh9UGZAXX7VFes+nL7VfQyW4fO2CHt2MMZmcW93bcW7Z5gFXDXJAvvZA6rggjnPsvAeS/+7xm1ONMeVurfWufrvKm0RM2BW3+hdtlJaDmD811qZ/6olf1FXGjWtOKaW0vKyc1LVdWVglbsoqcUJIV8CAnFLqKgPycLJylhkuUhp0N6+M6x/10FJnjTXu90GUAXnxvfuxXySP44a7z7FfQyW4fC3XKvDq6BDHuS3c8ayxTjrVgPy+Jy4xlsOuCsgxf7u+XPeaW89Iro926jfde27y3299fpexfhj0m6pZnDuYlrcbZ3TtF/vlzPIxDCsopbTcnTMkIuJF7rTOKnFTVokTQroaBuSUUlcZkIcTBOQrZlBaXjIgT7FfLDXu90GUAXnxveSqU5LHcUevn9uv4XjU43vt49uNcZn8/infSo5FaK0vT+fwsbcmx11xY3djOXx/1n3JdYoZkE9e9aixXHdcRc/k+piTHPO647/xv5sjg431w6CvWELMHGB+AUdpOTnjxeJ/sR8GmnZw7nFKKQ2LuzcV/nsCVombskqcEFJKMCCnlLrKgJwQQsqPmDgotlsjjHt+0GRA7r8La5+123t/tvwRY9mwD29xHMfomX9ILrvxnnOTr2Me7ZkbHjfGV7UOEk8Pu0asauzneH3w6Jsd20XwrY/dEh9qt3KfsKRX8jUcozpuWUMfx5j5W59Khs6w0AH5+Zf+ILn8wWfcW76rop28GqpLc3lIoNz0k33bGHDRcLi3ml8u+03lZIYYlFIaFjdM9/9JM7ZON2XrdEJIKcOAnFLqKgNyQggpT5rEAuOeHzQZkPsv5vKW+0FVM9qoo6366eed5DiGH3c/zlHljGNCAK2ug6AX4ffwMb+zA2O0X5evq/tEUHzmBSc7xmIu895DrhKvf3K7+NOLv0pWmZ994XeS4za2DHTsE9vv89p1dpB+6TU/cWwPFjogf/i5Ho79nXvR9+zW6Q/0/i9x9S2nG+vDP75wuXGcny5+2FgvLPpJzVLOH0zD4daFbLPuJ0f2W2JGf/M6U0opLU+/eKNN/1XQKdg63ZSt0wkhQYEBOaXUVQbkhBBSnkStJhH0v9EYkPuvDLEziXUW73rOGIu5yPWQ3E1UmG9qG+QYi8r17ud6ez9nVz2RHKdXtev+9Izjk/9d6IC88tCAjOePQF8fM2/LU451UFGurxMm/WTTHAbkNBxyHnJ/2VIRM64xpZTS8ra5IfcAl1XipqwSJ4QEFQbklFJXGZATQkj5ss+aa9z3gyQDcv8dOeVuo5pbinblj/b7ldhwxAx6pTg2BM9qa3MpKtJRTZ3u+KtjQ8TjA65MG9Jffv1p4pNFDxnj3vr8LiOYPrnbN+3K87UH+idfw3bVcbc99J/JZV7mTe/51KXJ9fu/fYOxHFZse9oRyktxPeZs7m2sj+p59Vqhgl9fJ0z6ycaZDLloOFw/lQG5XyTiQlS8Zl5jSiml5e3WBd7mIWeVuCmrxAkh5QADckqpqwzICSGkfImIvaLGetW49wdFBuSFE/OET171qBg17R4xdn5PsWjnc3aYq6+XSYwZV9HTrpJG+K0vz+S65v52q/GJyx6x5xb3su+l9X3E+AUPiiV1zxvLii3OHdcNc7HjXPTlqnhwQL63uFb68rBYY72m36LyggE5DYsMyP2jYUPCuL6UUkrL36WjI/qvhCSsEjdllTghpNxgQE4pdZUBOSGElDdN1iLj3h8UwxqQrz88wLgWNJgu2P5M8n099awTjOVhcpc1Tr895QUDchoWGZD7B66lfn0ppZSGw2irZf8uQPBbXRFjKK7I1umEkHIn8AE5qlN+3P24rBUaNH8nrXzUbp159oXfsVtVouqlx29OFb2HXMUvbH32vRn3ihvuPkcMH5t9XsxCyYCcEELKn1rrPeP+HwTDGJD//f/9P8Z1oMFyS3yoXZ3/WP8rHK3h+715vbFumNxrzdZvTXnBgJyGRQbk/lHxWsS4vpRSSsPhF2+wdboqW6cTQsJE4ANyBLT4YmnAyBuNZZlcsbev8Vq5iZaWaJOpv56r2A6Ccf2LWtWvHXuMWN30ojE2H/06/qCJ66he2xnrHzfWgYW+PgzICSGk/DlibTXu/0EwjAH5hZf/0LgONFhecWN343296ub/ENXR3NrQl5vN1mr91pQXDMhpWGRA7g/N9ZZxbSmllNKwyCpxQkiYCXRAvnz3C8kvl04/7yRjue7myGDR57Xr7Mrnk7t901heLuK69HzqUrsy5dae5xvLc7XX8z0cX+T99Izj7cAcX/J95Zi/8v1LW7+PP2hi/kz1ek9d8yfH8mJdHwbkhBASDnZbU43fAaVu2ALyv/7K/w71HNXl4kVX/MjxvqJbEKrK9fXCZotVq9+W8oIBOQ2LDMj9oWZJ3Li2lFJKaTnLKnFCCOkg0AE52hOqXzLN35r5i8NFO59LrlvOAfmwD29Jnme+ASoqlNVrPODdmxzLl9b3sYPy6ZV/NsZ2Vj+PP6g+Pewa+zN6z58vMpYV6/owICeEkHDQaM03fgeUumEJyL/0paPtc/Xz7yzadeIBx0uv+Ym4/8lLxMwNjxvLw2pctOi3pbxgQE7DIgNyf2BbXUoppWGQVeKEEGIS2IAc1RaYB1v9EvGhZ39prKfKgDx33570++S2zrzgZGN5IfTz+MvRYl0fBuSEEBIO9ohpxu+AUjeXgByB5ODRN4vPlj8ipq59rCRUf5en8+eX/VBsbBlonDul5WSt9a5+S8obBuQ0LDIgz59YqzCuK6WUUloOIhCvrogxFCeEkAwENiB/f9Z9xheJCMy3JtzbFGJeZ3wxKtc97t+PFcsa+iTtzFzObmMrDw0Qo6bdI0ZMuFNMWvmo65yCCPfnVvcWb3x6h71uxbanPbVXnLPpSXv9l8fdKiYs6SXWNfc31kH77WdfvjZ5ntfceobjPHF8+phM9n/7huS2brr3XGO5dMLSXnabyB93P85Ylou5Hj/eV7lMvoZr/unih+3r9PHCh4zrhC+bp6z+k3jlo9tsJ69yf5/U7WH7K/el5q3H5wzv4Wsf3y4+nHO/fdz6OF2v71+mz2Wu1ycfGZATQkg4aBCfGr8DSl2vAfnQD24xxpaC6t+k6fzVDT8zxlFabu61Zuu3pLxhQE7DIgPy/KlfnzCuK6WUUhpU2TqdEEJyI7ABeY/fnJr8AhFht/zvcRU9jXXh90/5lvHFoyrmc9bHZHLFntT859j/2gP9xfmX/sDYrhpYIgTvPeSq5Lzduo/0ucyeJ13fF+agPvWsE4z14cW/PsUOW7EewmJ9uS4CVX37mUR4LMemm+ddbcOOhxT05V7tzPGf+N1vJJdh7u47ev3cuL7yM/HJooeMuR9Vb3/4AteAGaG2XAct5RGK6/uAV99yuut4r+8fAnN9+deOPSav65OPDMgJISQc7LTeN34HlLpeAnL8XtbHlYoMyCnt8JC1Sb8l5Q0DchoWGZDnz4ZpvF9QSikNrgjE2TqdEEI6TyADclTKyi8PEXwPef/m5L+vu+MsY33od0COSl51LNqP69v83QOp9tcINxEw6+voIvBVK5URmKshsJuogsa6+nzhbuYaoFbHhtghrRzv9gCCXwF5Z45fvTb4IlxfX7bSx3m4hdq63c890TiukVPuTi5Hhbw+RvWCHt0cY3N5/7IF5J25PvnIgJwQQsLBdutN43dAqeslIH936j3GuFKRATmlHfo9/zhgQE7DIgPy/Fn2Pucfp5RSGixZJU4IIf4RyID8Ty/+Kvnl4ZODfi3W7E9V1iIEXX/YrOJFy+0B796UXA+hNiqDpeMXPGiMyaQakEtRST58zO/sCuMrbuxut9SW619725mOdVEtPnrmH2zvf/ISx7Irb+qeHIeKc3XZY/2vEGPnPSAGjLwxGfqjeh3rIgQeNf1ececjP0+uj8BWPc8Z6x83ziWbaCEut4fr+2jfy+3jkKrHj+VoAS5dWPussb10dub49fAZ+3962DX2unhAQYbPENcc6+C9v/uxX4iX3rnRbiGvV5WjBbq6DzUgl6Ld/Fuf32Uf72W/Pc2xDF96y7E5vX/RIaLPa9c5xqgBeWeuTz4yICeEkHCg3/+DoJeHDjGFjT6uVGRATukwUW99ot+OfIEBOQ2LDMjzZ97wiHFdKaWU0lKSVeKEEFI4AheQo005qpTll4eLdj5nv662Nx/2oft8k1hXriMrizurHpAjqEWVuL4efG/Gvcn1EHh+UWN+Yau2MocTl3WErAjL5Wu/vdNZHY9AFeG1vi2cvxxza89UFXs+djv1247j8yrCZX1b2czl+PWAHHOL6+tIUaHd6/kerg9Q3HjPucltoO25ukwNyBHA4/3Ux6tf1COIl6935v2rah2UHKMG5NJcrk8+MiAnhJBwUGuNNH4HlLq/vPanjt//bo6Za/6OLRXxd55+vLqXX3+aMY7ScrLJWqLfjnyBATkNiwzI8yPWJoxrSimllJaCCMSrK2IMxQkhpMAELiBHxbX84hBtzeXrqASWr5970feMcbCQATmqifV1pGr7dVSX68ulmD9brodKYryGSmf5GkJqhKf6OF2/A1RUWqvnmovFDMhRWa0v9+rc6t7J7eifDTUgTzefab83r0+uc8Pd5yRf78z7x4CcEEJIMUEVp/47oNS99cH/TP4uTOfvH73QGFcqMiCndJiIiH367cgXGJDTsMiAPD/270wY15RSSintKlklTgghxSdwAfml1/wk+cUhQkn5+oo9zsBaVparFjIgx1zT+jpSde5rBPlow+6m2ob95vv+nz12wtJejv2gLXe2dvB+BqgLdzzr2D/aq+PcVWdueDy5HO3L1WWokta3mc1cjl8NyNG6XF/uJirI8T7ggYQLL/+hOPWsE+y569XzVNf3EpCj9blcR52HvDPvHwNyQgghxWSvmGn8Dih1X3jjt47fr27+r//9l8mOPKUmA3Iadhusz/RbkW+EKSCf8WKbPYcyXDAiWK2i5wyNJI+dba47JwPy/Ni1Jm5cU0oppbRYsnU6IYR0PYEKyJc19HF8cbiqsZ9juVqpjXnK9fGFCsjR8l1fLl28K7XPXFSDWDl3tupPzzg+betQPwPUwaNvTm4L5+n2IADeB3UdfXmu5nL8akCOMF9frtvn9evs0Fm/nrrqGC8BufpF93mXfN+xLNf3jwE5IYSQYoI2x/rvgFIXf18dddRRxu9X3S//1f8SPZ++VExd8yfXv2G6SgbkNOwesjbotyLf8Dsgb9yeEAd3W+JIkyXaDlkicrjDI42WXYG6bXFczB7cNQHvinHR5HlHW4PVLrpuXTx57Pu2sZK3MzIgz4/Nc/29V1BKKaXZlIE4Q3FCCCkNAhWQP9rvV8kvDS+64kfG8mdfvja5/Lh/P9ZYXqiA3G1fUlQLq192IkD24jPDr3FsB63Z1bnXpag616u0/QxQ73384qzbKpWAfGl9H2O5qvr5kceKyvH7nrjEMVc4VMd5Ccg/W54+IIe5vH8MyAkhhBSTg9YG43dAEPzhaf9q/F4tJ48++ihx/En/IG74/TliddOLxvlTGlS3J94SCRHRb0W+4XdA7pU9mxNiel9zfCFlQB5uGZDnx+pPosY1pZRSSv2UVeKEEFLaBCYg3xIf6ggYEYxef9fZDhFMql8sTljSy7GNrgjI5215ynFMWxNDjXW8iiB1wLs3GRXQqFBW1/MzQFVb2j819GpjOQxCQD52fk/HNUOHAb2STF2uvu5HQA69vn8MyAkhhBSTVmun8TsgCL7y0W2O36fl7D/9y9+Llfv6GteA0iC6z5qr34Z8pasCctBcZxnjCykD8nDLgLzzbJ7n732CUkoplbJKnBBCgkNgAvL3ZqTmePaqnMdbqgbkmUJtL3oNyBHsq8e0YPszxjq5ikAac2fLbWJea3W5GqDeeM+5xvhcxDWU27rnzxcZy6EakGMOcn15ruZy/F4D8rv+eGFyvd894B4qy+VQfd2vgFya7f3LJSDPdn3ykQE5IYSEh+3Wm8bvgSD4o5/9q+P3dzl79e/c/wahNEjiXhMV+/VbkK8UMiDfujAulo+JijUTo6J6Xkwc2mM5loPlHxavKpUBebhlQJ47TdstsfCtrpkSgVJKafk6vV+bWPh2RGycHhM7VsTtKXoIIYSUPoEJyNVKZlQpI4R0E3M7y/W+csxf2WGj3MaSuucdy/R95KLXgBz+uPtxyXVvuf88Y3lnXFj7rONLU/xbLhs+9tbk626t6HOx95CrkttCkFsdc7YDh+ua+zuORV+eq7kcv9eAvPu5JybX+3CO+9zf6c7B74AcZnr/sgXkuVyffGRATggh4QEVnfrvgSA4Y/3j4pi//f8cv1PL1W986++M86c0aB6wVui3H98pZEC+eKQZrK35NBVSA7Ra19cplAzIwy0D8tzw+95AKaWUZnLOsDZRNSsmDuxiWE4IIaVKIAJyBJ/qF4SjZ/7BWEe6/vAAx7qY+1ku06u5x857wBjv1VwCcjXQhG98eoexDnz9k9vFxGWPOF5DII2K5zmbnnS8PnnVo45tqsvRWl6+jgcB1h7ob+zLq7hG6n56PnWpEZLj3+o6ny5+2NhOLuZy/F4D8kuuOiW5Xq/neziWoe39H55IzbUOUeUtl+cTkHfm/csWkOdyffKRATkhhISHI1aN8XsgKL496ffiS1862vF7tRzFnOT632CUBsk6a7x+6ykIfodgKm4BOWw9mKokP7wvfZv1ucMionJyTGxbFLeDdfxbXyedmN8cgXjN4rjYMD1mV8FmCsjnvxoRX7wRERWvp9/H7MEd68CZA1Kvz3ixzX4N21D3v/S9qNi6oGP/WK5vL52z2re97vOYfez433nDIzkF5NhX1eyY2FLRUcGvHqsuto31sU/52pwhEbF+Ssw+9hVj28e/ZI5LJ96jtZ+1v2ftx47OAbMHOZdXvJa6hvpYVVw/ud78VzKv61UG5N7AQyusGqeUUtqVftH+9xj+jmFYTgghpUUgAvJH+16e/HIQgSHmctbXUVWrzdHKWl125gUnO75sROA5YOSNdoj5WP8rjG2lM5eAHKoBLbz416eIPq9fZ4fif37pSnH6eSfZr2NudPX81Nby8lgf7fcrez31miD8l2MqD75kB6fq8nsfv1j0HfFbcdXN/yFGTbvHOL5Mnn3hdxzHjkry3z96oT0n+QO9/8v+t7ocXnlTd7s9O5blOu96LsfvNSB/fMCVyfWw7Yef6yHen3Wf3a78gh7djONX95FPQN6Z9y9bQJ7L9clHBuSEEBIeLBEPbJt1OGLineL//E3qd2M5+q8nZv97k9JS9ojYpt96CkJXBORqq/WWA2ZAjrkoEWC7EYsIsWp8+rbsaNnZVOv+ZWpcKV7XA3IVhLP6duH+nantoh2ofH3T7FTwikAXwbIbRxotO3zWtytFENx2yGxDDxLKJtMF5Ki6stxPXRxpslzD/3ikYznmg58zNCIih839W+0vVWX5nGxfFk+771j75d04o2O8ug7Cf307UqwvwfumL++MDMgzg8+C3/cDSimlNF8Xj4zaYXlzfZo/NAghhBSNkg/IERyipbr8cvDWnu7zR6vqFdvLGlLB6aSVzspd1VPPOsHYVjpzDchX7HnB0eY7kzhGOe66O84ylusi5NX39/Swa4z1pPc/eYmxfibRvhQhrL4dr2Lud32b2fR6/F4D8o0tAx3ruon3X/43znd104v22HwC8s68f9kCcuj1+uQjA3JCCAkXe60Zxu+CIDlt3WPiuz/6Z+P3Yrl492O/MM6Z0qC415ql33IKht+BmEq6gBwht6Sxxhn2Imj1Ql2lGRLPezkiIkfMgNeNzgTkahWTIyCfo4S5yrm5gQBa3y5EdXu6gFnHLSBvbvB23noorR6v+gCBG2smmA8moCI8Xaivg+ryfVtTJ4kHJfTtSQ/tTW1zd5V5vp2RAXl6dm+Ks2qcUkppadv+99n6aTFxcI/HP5gIIYT4TskH5B8vfMjx5aCX9t36nNj93rzesfyD2fe5Br4IUPVtpXPlvr45j0PY/+zL14p//OevGvtGyH7tbWeKim1PO8agFTde19eH3U79dtpqYVRto8JbHwNvuPscY/1s4nxRFa5vC6Ka+bd3niVue+g/jWUQ4bG+vWx6PX61EhsPIejbUUWAjo4C+vZQvT9zw+N25T7Cbfn6nM297XFqFTjeC327cMrqPyXXOf/SHyRf78z7t6kte0Du9frkIwNyQggJF0fENuN3QdDE78eBo24SJ3znH43fj0EWD/HhATr9fCkNgrusMSIh0pRPF4BiB+S1q5wBONpxy2XLPnAmtAix0V4dbdZrlsYdwTpA+3B122rrdoD27dsWxu1qZL2qvFABueTgbktUz4vZVd2okldBu3h1u2jdrofjeHAAlenYRmuzc7wekO9Y7rymCJ43z43ZXyKjNbulDEclutr2XA/0EZLXb0iIyikxsXO1c7sIwvVrop8brvnWhR3vGd5rWZG+a03H9Vr0jnOHOHd9m2jpruJXcMuA3J1da/15AIFSSikthpjaBn+/ojsOIYSQ4lLyAXmhRFg9u+oJMa6ip5i35amif+m4Zv+LdviPaicv+0Z4u2D7M/bxInRV58jOJLaNinQ8WIBK7nznrsR1Q4g/dn5POxRG6KxuEw8nfLLoIXufCNX18bnq9/FDHBeuIwJwt+0t3PGsmLC0l+uyztrZ9y+bhbg+UgbkhBASPhqsCcbvg6A6a+MT9vQ56P6C6WK+88Nvin///j8FRhzvRVf8SDwz/BrHVCyUBska61XRKur0W01BKWRAjpC3dkXcDkfx33oYi0BbjkMojVbcEgTaelCNL0TVQFatxsY83yoIxvVjUwPfQgbkbu3I1Zbxe7c4A0lcGwmC8pUfOQN0HI/6JbAakKOlu8qmuea+0bpdbdG+e1NqvPqeIADX5wxHyK6CFvZyGeY5V9nyhXnNIarj1X+rbdzRMUBfX72e0RYzlO+sDMhN8POpXydKKaU0CM4a0DHNjf6wHiGEkMIR2oCcUppZBuSEEBI+DovNxu8DSintrAdFpX6bKTiFDMgzgcAYwa0cp4aXqGJWg1jV+a86A2H5utoeHO3G9XEQQa2kUAE55hnXx0E1nFdbi6NFucqWBe6BJSrBJWpAjv+WHExz3hCV6BJUpMvX1YB8yXtmC3VoKd87q9XcakU/Ksf1celEkC7R3weIayhBdby+vLMyIHeybZG/P/uUUkppVzh7cJvY3P53jtcpXwghhHQeBuSUUlcZkBNCSHhoFTtFvfWJ8buAUko7a6M1X7/VFIWuCMgRFqONtjoOc4pLEJrWLI6nVQUV1Kh61l/Tjwt2ZUCOVusStfId11+SiKXfd7qAXG0rj7bu+rWSom26BNXkcryXgFwNwuU85DhOlWXvu491E++9Grovfjc1dtZA53bnDHV/LzsjHshA1TtC9z2bE+3XK2G07Q8LCBL060MppZQGWfyer6t0/p1ICCHEXxiQU0pdZUBOCCHlDUNxSmmh3G1N0W85RaOQAbk9/3f79tFGW6VhgznnMaqqO8OSUVGxcnwq+EaLcn3b0q4MyBEsSyJHUuvUKw8GHE4zFqYLyNXW6V5Rr5GXgFxtib7u847Py8K3nclyumuWzv07U+eNFvPy9S0VqRNCW3l9XCHEAxY4H3yO0B4fn1e0oT/YkLBbvJcbaz51f58ppZTScnCjNu0OIYQQ/2BATil1lQE5IYSUHzIUZzBOKS2UXRmOg0IG5ItHpqp/m3akAlGw6B1nZbAeRCLEzSbCYVQjb12YClUxj7l+TNIuDcg/dQ/I0RZdogbFum4BuV7FbVnmNXJTDZ69BORqy1IZkFdOTp0ztqmPyebyD50PNchrrs4jimpvfVxXOGtgxG4tj7nhMdf9tsUxsbsqIZrrLfu9DBKL3nF/jymllNJyEn9n4u8dQggh/sKAnFLqKgNyQggpDxCK77eWMBSnlBbcOmucfgsqOsUKyGcPjthBqAShqzpOnXca4aO+3UyqAbXaPly3FANytZIaLdL1cVK3gByq17QzlcGdDciXvqdM+i7SX7NMqu3NN86I2Z8RCcL+GS+aY0pRPKSBtv74fK2fFhPbFsVF/fq4OFBnldR8qLMH+deunlJKKQ2CtSuVP5QIIYTkDQNySqmrDMgJISS4IBRnC3VKaTHdYb2l34q6hGIF5HDTbGfLS1R+y2VoaS05vC99UOwm5r9WmdHfXAd6DcgxD7Y+FhYiIMd87BJU0evjpOkCcrX9OebW1sdls7MBOcJrFb0jgBdxDSWo8kKwLDlQl9tDEqUsPo8Vr0fE8g8jYv3UmP25r6+M2w9HqHPIF5KZA8zjopRSSsPgqo+dfycSQgjpPAzIKaWuMiAnhJDgwVCcUtoV1liv6bejLqOYATlsbU4Fgu3/F1jMG96xjhoyA7ex6UQFr8qute5BcaaAXJ3Le9kHZlCMQBhjJH4F5Kg4VsEx6mNhuoBcrUCPR9M/HJDOzgbk9ljl+2a0itfHZVOtGAfq9V39ifuxlKPT2z9bFa9F7M/duklRsXVBvP39TtjTEqg/L50F1e36PimllNIwOWuQ829FQgghnYMBOaXUVQbkhBASDBiKU0q7Utx/SoliB+QLRjhD0UN7OoJVhNwJJStGWDr/FXM8wr6GjWZ1sdqiHcH7mglmwIrgUd2+ukytxEborI9FRbOKXwE5KnvVNuloO45rpI9vVuYqVwNyhNoqqHJ3a02O6qlti80HB/IJyLcvU54qaMdt+2i9XrsyLtZ+5v45Q7cAnUxt8sNpq5j/akQsfT/afv2jonp+TOxcExdN2y3Rst+yP+/pWD7G/CxRSimlYXT2EIbkhBCSLwzIKaWuMiAnhJDShaE4pbQUbLQW6LenLqfYATlUq6GBDF31FpgI/hAGb1sYt0NWNaRW27PDhW87g3eA8BXV5DWL43YQr6IH5PoxYSwC38aahKO6XOJXQA63KMG9BCE99lG7Ku4I74EakNvHXukM71HZjXnct3yBSuS43b5cordCzycgR/itVn0DHGvDhoR9Tns2J5JV5unax1dOclbQA4zT16OZnTe8TSwdHbUfRNg8LyZ2tn9uVox1fz8ppZTSsOr29yIhhBDvMCCnlLrKgJwQQkoLhuKU0lKx1npXHLY267epkqArAvLp/ZzBLAJoVJBjGYJwLyCI1beLINwrekCO1uRuQbiKWuntZ0AOD9RlKAPW0ANyBNX6AwDpQHCujs0nIIcI3GMeC7LcWtfj2NXrCvQQn1JKKaXUL1eN55zkhBDSWRiQU0pdZUBOCCFdjwzFGYxTSkvFfdZsEbMO6rerkqGQAfnCt9IHnXq1OCqd5TIEtXrVtARhLCqmZw8ytwmXj4kaVc0A4Tdas0vcKprR0l1t1S5pPWjZc4M31abGo724HFc1MxWQo/Jc3y5Uv4x1C/fhloq4a0iPQF0N0PdWu1dYb5wRc8wLLkEAjX1Wz4vZgbQ6Bi3dJYtHmgE2VAPyNRPNdfDAw+5NCSPolrQcsIxgPd329QcXKKWUUkr9Fn8zEUIIyR0G5JRSVxmQE0JI14BQfL+1hKE4pbSk3GWNEYetLfotq+TwOyD3UwSvqDqunByz5x7Xl2cSFeEIyxFMzx2W29hZA9rsQBxhMLajLy+0c4ZE7AcIcPw4Fn15NmcN7HgAAcef67nnK/aHNt+YAx7vmR7Iu4l50yXoIKAvp5RSSin126pZDMkJISRXGJBTSl1lQE4IIcUDoThbqFNKS9Uma5GwRDC+dCvlgJyWvwjz1ar3Ygf6lFJKKQ2vm+e5tO4hhBCSFgbklFJXGZATQkjhYShOKS1Vd1gjRZO1UETEPv3WVdIwIKdd4eJ3o2Ln6rijxXvLfvfW85RSSimlhbJmCUNyQgjxCgNySqmrNdbrdotfQggh/sJQnFJaytZZ48VBa61ICCXpCxAMyGmxRTCugyryitdZPV7OojvAyvFRUTkpFiiXfxi1Ox3o55Orc4a2n/9H2c8fUxQseidiTzGhb4NSSmkB7NsmmranpnshhBCSHgbklNKsIshBWI5QhxBCSO4wFKeUlrK4PzVZi0WL2KHfvgIHA3JabBs2OL+ERhX5/FcYjpejCMXr1sVF60HL8Z4HkcONlqhZHBczXzLPM5OrPo7a3RFyJRET9rWbPZg/G5RSWmjxYFK0Nfd7NSGEhA0G5JTSnEVYzupyQgjJTJhCcZwnzvewqBa7xefGckppKTlc1Frvib3WbHFEbBFx0aLfvgINA3JabLd8EReRw5ZobrDEhukxMb2vuQ4NvqiEjrbqd5zgc6TJEktGRY3z1UUF+O6q/CsSoy2WWPZB9v1RSinNz/VTY/otmBBCiAYDckpp3jIwJ4SQDmQoHoZgXIbibsTFYdFoVRhjKKXFd7c1WTSJBeKgWCdarXphifL9smz//oSY/Ib5BSGllObjtkVmG/1ywrKEWPNp5tB601z/fne0HbJ8afNOKaU0s7Ury/v3FyGE5EtBA/J16yrF2nVrKaUBVf+C1Ytsx04ICRu43+G+F/ZQXCcmmo3xlNLi22p5+5kNIvG4JaZMaRUPP3xAnHbabvEXf7FD3PnLJuPLQUop7axLR0ftALncQXU8Wsjr5w8xZQBapPtJ7Yq4sR9KKaX+OmtgRByoy7/7ByGElCsFDciXzWgVy6ZFKaUBdMXcA8YXrJ2R1eWEkHIEIXFYWqjLUNxrMC5Btaq+LUpp8S23gHz79ph4+eXD4pe/3Cu+/OVaOxRXZUBOKfXLmQPaRMuBEKTj/8PeLQnjGsD103xOx9vBtAT6fiillPrv0vcjoXjQixBCOgMDckqpq34F5KqsLieEBJ0wheK5VIu7sUdMM7ZLKS2+5RCQV1fHRL9+B8UZZ3RUiWeSATkNizP6m69Rf133uf/BcKmzYIRZRV63rjAteue9bO6LUkqp/1bNCt/vM0II8UJBA/IVM8zQjVIaDAsRkOuyupwQEgTCEorDfENxlVrrXWP7lNLiGxF79B/PQLBvX0IMHXpInH129lCcATkNo+unxkQiLsSRJkvs25oQtaviYvO8mFg7MSaWvhcVc4ebY2huog142KicFDOuQ6Ha8y7/MPO855RSSn2yb5s4uJtl5IQQolPQgHw5A3JKA2sxAnJVVpcTQkoJhuL5ERctxn4opcW3xnpd//EseSZObBVXX73PCL69yoCchkUE5NmwEkK07LdE4/aE2Lk6Lqrnx8Taz6P2vNqYV3raC63GdmnK5vrwhQm1K825wZvrCnMdlo9hQE4ppcVyQwGmyyCEkKBT0IB8y6o4pbRIbly113bNqk2+qX/JWkxZXU4IKTYMxf2jxao19kkpLb4N1kT9x7Mkqa+Pi2efPShOOKHOCLxzlQE5DYteAvJsWJaw59hu2pEQdWsTYssXcbFuUlQs+yAq5r8aEdP7mfsNk3jAIBOYRxtta4PipjnZPzMHdpnzkGcKyNHFoH5DomMfM1NuqYiLI43pxwEG5JRSWjxnvNgmWpsz35cJISRsFDQgTychpLAg9EC4XE5BDwNzQkghkKF4Od0v01noUFzliLXV2D+ltPjuF0v1H8+SYtGiiPjv/240Qu58ZEBOw6IfAbkX2g4K0VSbEHWVcbF1QVysnxITyz6MiIrXI/aX7fpxlZPZOLTXMsaUspi3PhuomtfHZQrIV4zNHHJnGsuAnFJKiyseZiKEEJKCATkhIUCGy/qXpkGV7dgJIfmAe0dYqsWLGYqrHLK6tgsJpbTDiNin/3iWBBMntohf/GKPEW77IQNyGhaLFZBno+2QJQ7sskT9+rjYuihmHxdC0y/eiIgZL5nHHSSzEfaAPNoqxPS+5n5UM4UxDMgppbS4zhzQJhLpb8uEEBI6GJATEjJYXU4ICSNhDMW7IhiXHLQqjeOilBbXButz/Uezy/nwwyPi9NN3G6G2nzIgp2GxVALybESOWHbA2rAxIbYtjokN02Ni5biomDfcPKdSMxthD8gBHoTQ11fF+54OBuSUUlp8qyuC8fcDIYQUAwbkhIQcVpcTQsqZMIXiXVUt7kaztdo4RkppcT1kbdB/NLuMMWOOiJ/9rLDBuJQBOQ2LQQnI04F5zvVzKjWzwYC8Y/01E6Oi4rWIPW+9dNHbEVGzJJ5xHncG5JRSWnxnD87+u4AQQsICA3JCSBJWlxNCyoGwhOKwlEJxlf3WMuNYKaXFs96aoP9YdgmTJrWKs88uTjAuZUBOw2KQA/LdVXHjfErRbDAgzw8G5JRS2jXWrozrt2RCCAklDMgJIWlhdTkhJCgwFC8tmgUryCntSlutrr1HLFsWEZddttcIr4vhI79rELNfaaa07N0477D+oxcYlo/J3Ja7VMwGA/L8YEBOKaVd44pxUf2WTAghoYQBOSHEM+UWmLO6nJBgw1C8dGkRNcY5UEqLY6P1hf4jWTQaGxPinnv2G6F1MR0/YZ2oteZQWvZu2VE60yjkwr6tCeOL+lI1GwzI84MBOaWUdo2bZge3Cw0hhPgJA3JCSKdgO3ZCSFcgQ/FyuvekM2ihuErEajLOh1JaeOusj0RCdE1FyNChh8Tf/d1OI7AutgzIaVgMakBeNTNmfFFfqmaDAXl+MCCnlNKucddatlgnhBDAgJwQ4gvlVl3OduyElA74OQxLtbgMxYN+77FE3Dg3SmlhrbFeE22iXv9xLDgLFrSJc84p7jzjmWRATsNiTd1G/ccxECwYEYz26jAbDMjb/05vtkT1vJhY/mHU4epPomL3poS+ugMG5JRS2jUebEh/XyeEkDDBgJwQ4jusLieE5AtD8eCzw3rHOFdKaeE8KNbpP4YF55FHDhgBdVfbe+BKI0iktBzdLzbpP5IlT9OO4LRXh9lgQC7E4pGZQ+5929KH5AzIKaW0a0ywgJwQQmwYkBNCCg6ry4ODJRIiLlraPSRiopnSDB5q/5y06h+hvAlTKB7kFupeCMP7SGmpuF8s1X8EC8r06a2iW7cGI5wuBRmQ07AYxIB889zgtFeH2Qh7QB5t/78C+rq6G2emn+e23APyhW9HxLL3o2Lp6KiY3tdcHmRxPjgvnB/OU19OKS1dK16L6LdjQggJLQzICSFFhdXlpQGC8FaxSzSLFWKvNV3UWWPFdutN49wozWaNNVzUWu+0/0yPF/vEHHFQrBVt1m79I5eRsITisNxDcZUD7fcX/fwppf5b7HC8FKvGVU/6fjXtIl8ZsUdExWFaRINGkNqrw2yEPSAHS0ZlDrkba/ypIK+rTIim7d7dt7XruxWoFZpfvFGYz/78VyLGuediY7szXzK3m02cjwTnqS+npSHeJ7zPbYcs+32C+O+m2oRY9I5/n0n153PhW5m3i/3KdevWxY3lbq6fEhPx9o/c3GGZt029uXJ8NHVzIoSQkMOAnBDSpbC6vHjExWHRbK0WDWJi+7EON46dUj/dbr0h9ohp7Z+6Kns+ah2G4uVPpP0ToF8LSqm/1lrv6j96BWPZsojo3r00q8Zp6XjRRXtFdXX6ilESXtyC11I3GwzI2//eO2yJrQvjYtX4qB26SNd+FrND6kzkEpB3ph2wvo1im0tAPntwRMweZL6ezWUf5B90zRue+djcZEBe+tauyP5Ds2G6P1091M/6us8zb3P91NTfCImYt89Oa3PHPah2pbdAnWYW3VwIIYR0wICcEFJSlFtgXgrV5UfEFrFbTDKOjdJiWWO9IvaJWaJZrGEoHjJ2WG8b14ZS6q/FuN8MGXLQCEIpTeff/M1OMWrUEf1jRELOlorgBRvZYECeHwzI28TKj6L25whs+SL3nxEG5NTNysnOANRKCHF4nyUO7bHs/7Zfa//Y4cEMfWxnLGRArn7WvEzrQLNbvz7zw0uEEBImGJATQkoWtmPPj4PWerHL+sA4BkppYSxGSBU09oqZxnWilBbGQtx/IhFL3HhjoxGAUurF++7br3+kSIgJWnt1mA0G5PnR2YC8YWNCbJwRy2jllMwhXTH0EpAjsJR0JiCfNaDNOHdpXMnOm3a4XzNUEHdmfnQG5KWt+t7jM6a20cdnBq31dyzP/fOWzkIG5Hs2OcPcbNM60Owe2sOAnBBCJAzICSGBodyqywvVjh0V47vEGGN/lFL/laG43z/H5cJBq9K4ZpTSwunnQ3hLl0ZEt271RuhJaS6ee+4etlwnduWi/gV9EMwGA/L86GxAni2AKxWLEZBnMnIkte1tC/3dNgPy0hVV4Sp+VYlnMpefz1wCcjy8ISveJfu2JYz1aG4SQghJwYCcEBJIWF1ugjnG94ppxnYppf7KUNw7Meuw2J54y7iGlNLCmc/fEpJ33jksjj7aDDsp7Yxf//ouMXFiq/4xIyEiiO3VYTYYkOdHsQNytBLH2JolcfszuXR0NGP19JyhETsIhtP7mcshrqlcZ84QZxCZKSCX41oOpK7tztXx5LbgzAHm/nIx14Ac54vW3NsWdcwpj0pjfR1pZwJyjKmaHbOvPd77TOeHUDd5HZTqZ7SU37Y4ble+610p8B7hPa2e3/4et6+DIFZ/T3TxmcA+1HPFmPVTYmLrgrhYMTbq2H825w6LiLWfxexjXDMx6mleeVyHVR9H7euO/eqflVxd+l6qfDzTe7N4ZNQOmxFA69cyV3P5+cwlIEeXAx0cb6afW5pZ9WeXEEIIA3JCSJkQ9uryQ1aV2G69YWyHUuqP+JlkC/XO0VRG92ZKg2I+IfljjzUbASelfti//0H940ZCAsIf/Uv6IJgNBuT5UYyAHEEawlK15bTOzjVx18Ct9WDqvBFc6svhprmpAO9wo/PaZQrIEeJmY8eK7KF2Jr0G5Hgf4mkys7ZDlnHsMJeAvGpWzKgClhxpskTF6+b2DzYox74oLrYviwv96+R9WzsqiRePjDjW14kctuwwWN8HlOeNzzgeEMC6Othv1Uz3919qH1+ac4y1/9gh6NXHIExHdw03sC0E9PoYL+KzrDJroLkOVH8mFr1jvge5mMvPZy4BeWtz6vqo+0j380izu35qhpshIYSEEAbkhJCyQ1aXl1Ngnqm6vNH6wlifUuqPDMXzh1XklHaNuH/lym9+s88INSn107vvbtI/diQEVLyWX/jSVWaDAXl+FCMgRyW0FxprzLbNjoB8qvs+N3c2IK8ojYAcwW428DWuPqe714C8OUNwraK/p2rgjRDdDVn1jBDfC273IfXBgEwPUYA1E8zPK7bpdf8IxOU4PDSULlBXQYcBt4c3sql2JthTbX62YakH5OpnDMeqflaDOm1HKYiuAYQQQlIwICeElD3lFpanqst3iN3WJGM5pTQ/GYr7D6vIKe06vdzPdu6Mi7PO2m2EmZQWwh499oqWFn4vEBasDOFZqZsNBuT50dmAHKFrXWXC1cXvmtuM/s/9JhbpmL8YQRvWRTinolcZFzIgn/9qR7txeWygqTZhvybVx+RqtoAc10ol2irE5nkxsWJcRxtz9fjx32qrcS8B+Y7lzvAd863jeq2fFhN165wV4diG2o7crSL8QF1CbJwZsyvHG7enQl+0hZcc3G3Z28Z7rIfzWKYfo145jyC2fkPCfiAALe9VEITr49UgGiC43dp+rXFMtaviyYr0XWtS1x/t3NVri6Ac+0JVNB6c0B8IwHb0/WYT7496fQ/sSog9m5yq4AER+TOEFvH69rLp9ecTqu9tpoB8z+bUMe6uStjt8FWKMbd6uTlrUPbfAYQQEjYYkBNCQke5BeaU0vxlKF5YWEVOadea6f62YkVUnHBCnRFiUlpIf/az3aKmJnsFJQk+boFrUMwGA/L86GxAngmEk/rYNZ9GRe0Ks4065n5WQ/L69c5K20IG5FKExpItX5jHno/ZAnK1fTXW1ecEn/9KxFHljOBZLssWkOvzHKMVvb4Otq9eo92bUtdfD8h3rTWPXxVhKlqt668j6FfRl6sBOQJwfc5whPkq6lz0eIhBJd37hwcO1H8j3JfgoQS3oBfXWiWXedClCMU7w/6d7hXnmfT686mTLiDHz6r62Vv4dsc1Ulvg1yx1v940vXj4gRBCiBMG5ISQUCPbsSMc079MppSWtwzFi0uztdp4DyilxdNtqpbp01vFV7+60wgvKS2G//Zv9WLFijQT35KyQa2cDJrZYECeH8UKyDNZuzK1YZynuqycA3I9wEbLb308rK9MpZQIk93GuwXkahtnhN36cmn1vNT1Q2AvX1cDclR16w83eFUPWhHKq8vVgHzJe+7XQP0ae+FbqfHoSCDx2vIbDyGoLHjT/XOB41ZboOfyswJXjM3SLz4DpRCQo1OABA8RyNdRTZ98vcXbNacp8RAKIYQQJwzICSFEgdXllJa3MhRnMN417LamGO8JpbR4qiH5Rx8dMQJLSovt1762S8ydmz20I8GlapZ7sBgEs8GAPD9yCf3UAA7VtaiEdBNtmPWxUoSRDRsTdiiNcA3GlEuit9Au54Ac7bwlCGL1sVLMTa0iX88WkKvXDq3NaxbHXUU7c7ftqAE5wnZ9+24iVEbg3rQ9YYftCLBb9js/u6s/cX7mvATkahAu5yHHvlSWve8+VnflR87gWr8equp+9fcvkzg2tTMCPtd4v3TVzye6LMjX9Sp6L3r9+YTqQxfpAnK1uwHaz8vXK153fh5lZTnNLturE0KIOwzICSEkDawup7Q8ZCheOkRFk9hhsdU6pV0p7omjRjEcp6Xjl79cKyZPbtV/ZZAyYfmH3oKjUjQbDMjzo7MB+brP3cPqdM4ZGvHUblqvSC3ngFytxMV56mOlaO2tMu/ljvPIFpB3pqIYld5yvBqQYz5xffu6G6bHHBXX6aic5HwfvQTkaltv+dlDMKvitcIdwXdnwBQB+rbSqT/UkC68V68XxujLczGXn0/8LEncAnK9u4Fe9Y+Kcgla6+vjqbtrJnr4ASGEkBDCgJwQQjzC6nJKgyMCILZQL00Oikrj/aK0XK1NvGe81tX2fXOCEVBSWgpOmNCi/8ogZcDcYfkFL11pNhiQ50cxAvJZA52BGkAoigB2f23CDsUlYQrI1VbLR7Tj1lVZ9kHHe5YpINerq/E1MMLvbB5pSh2HGpBvW5T5umxW2rRLWg5YomlHwv4ZVb+G7kxAjgpsifzsVU5O7VMN9rO5d4vzQQ39GqQT4aa+rXSqc6O7BdDSUg3IEXpL9K4OsE6tQHd5OIO6W1fZuYczCCGk3GFATgghnUBWlzMwp7S0ZCgeDPZaM433jtKgW2uNEnvE1Pa/DZaJI9Y2YYmOL6JwT9LX7SpfGDHx/2fvPeAkK+t8bz/rfVevVzdcUdeLa3rV6+4iZpdVUdRFVNYLXgTXgPCKKCiwICoKKGBAchrSAEMYcnDIMAyTmBkmJyZHJvV07p7Ouc/z9q/aU/XU85yqrqqu6j5V9f1+Pt9dqZPPqdPTfX7n/3+8UBIxTj75JCF5JTHQU97hxVgQkI+PiQjI7bGwxbaX0pfV2Nsh1RSQ712d2rmoEDJ0/pT0at55N+RWQa5QN0Ttu93pY5lrQK7uADYKxhdOTT/XdsBdrIB8xf3p1bi5VpDbY96rMt2dXgzV4jwk27WNY0Dujhmv9ernrK39vRZq2+5uA9NVe3W77T4AAKQgIAcAKAKE5YiTJ6F4ecJ45Fi2Dt9qaoPHTFMwz3SYDSM/f+pMYLI/ddLPqMkesuWqu6kcx/LwmWcIySuFlj3l3f52LAjIx8dEBOR22LZzsR+05hqQb50Tvc1iBuS7lvn7Nx6zBeQbcxyDfO2M1PnR49zw87ECcrst+d5V+R9XrgG5HTjrONQS3p2nFAH57KvS76VcA2a7zXU+lef5qGsdouNzp4faAfmye6OPPVfzuT+zBeS6z/JFY9y728B0aa8OAJAZAnIAgBJAYI5YWgnFK4NyD8n3B494n2F5WRM8ZOqDpxPfRXU2aA5eMq1msTlgVpi2YE0iAO8Mtphus9P0BHvNwMjU8TBZIfmUBx/3QkjEuPra1+41s2czJnkl0LiDgDxOVltArmpnm6jwNFtAbofXNa9Eh7R6CSTEC8itrE9jZLvLutuo31zc+yVbQO6O8xy2Tndtt4JqtaoPP9e40Daq5LaXO1CTOi8KYvXdc9edzVwD8tZ9qe207I4+f6UIyBPLWpmj9tddLkq34v3ViJc2xqv9nRYaL92dR9r7X0iVv20+92e2gLy3PXWu9QKBvsNRDqafRjP3Wn87mJL26gAAmSEgBwAoMWE79sl6KI5YOd5ius0u9xaDMqdcQ/KG4DkzaNpMW7Dam4blYW0wI3ENJ5qJfoFu2tOPeQEkYtx905tqzNKlzhNwKDvqNkUHVuXiWBCQj49SB+TuWNiqmranv3RTf1qI7IZ1DVtT4asCObeN9o5F6dWubkBuj2/uTgtttMYCtwPoYpgtIJdqRx6iann3BQK36nTnotQ6Xrwy/dyqZbu9rMJmm7b9w4mqa3cfFOZGVc7nGpDXWeNRuy84SLWtt7GPQY4nIN+zMn3dUceh74yq3O024PZLEXpEvuphf7sKfPXzUy8iuNPG0m2Lr2p+fdfd+fR9C9G43+70fMzn/swUkLsvbWzJ0LVBui+/lOJFg0pR196+1gAAkA4BOQDABEN1OWLhtgSL3FsKKoByC8lbzEITmNQDuY5ggzcPxtv64BkzZCavjfNE/R7w6MIHzV+/brcXPiKWgwcfvN9s2UJb0HImU9VtuTgWBOTjo9QBubRbfatiVuMzb5o1aPavH0pbZ8iCm1NB4hqrvbhQyKR24XWbhyMDJzcEb6tNH/9c2986N33fN1mtzoUCw/otw4lwXsFsptbsuThWQO6G2DqmfauHzNZ5g6b51fR9H+zzw3u7AllofzU2dzi91gqvhebXcSm01nXobk3tn9uiPNeAfN1T6Tuh7+qOBYOJ1vf2OkIO7EsPgscTkCv8dr8H+r6pE4Da+St0Ds+RHd6ritxu/S+0r/pu7V42ZJp3DSen51qZ7tq0M30DehSvdem7pWn2fRGifVTlv/ZZrfXddWYzn/szU0CujiMh2t+oFyps7WrzbGOtV7vuSyIAAJAOATkAwCRCdTli/g6aTvdWggqgzazyrnUcVcV4FF3BNrM7uM2bH+NnQzDLBGbyHxbpdrLTZwAAgABJREFUdwB334rpnM33mLe+fbsXOiKWk4ceWm9aWpwkAcqGPSsyB1vloBsAuig0VFhaLiocG4vWvX4laTkH5Godng0Fkfa6FRzay9vVvlHYbdTdgHzxnX4XDIXm7j7aAazLltm5H6vrWAG53L187N+HdB/YwXeo9s1lx8L0AHms8xei4Nxed64Buexqzr4Nu5Jf2G3WxxOQSwX7+jmQC3Ybe1XnuyF5FHqEPqeA9uHzrk8/tnzR98JdZzbzuT+jAnJ9V+zzEfWijqsq9m3G8zJJpbrgFnXJSDtNAADgQEAOABAjqC5HHNtW87J760CF0GP2mprgYe+ax8Ga4EHTGWx1dzmNnmCP2Rvc7S2L8bHZvORetkmlVCH5ugNTzT9/eIMXNiKWo0ce2ejeOlAmlHvbW4XF1UZUMBaLgNzKYu121bmoKuOoanFVMKtiXCFnGM7pkaW9rKpY7TboIaocVmWmqq1DFNS621b7bLvKOCogV7voTCGv2ni78+eqXSWsfXWnhyq4dUNkoXOh/c02vrOqte1zawfkoQrSo142SYwx3TVa8e22r7e/c2P9HNH+qTLcRfulNviaR+OTh+xbm1qfPZb1sunR30c7IFew7U5Xu/mGbamqbxe1so8KjVVJHlXlLnS+tM/u2O75qI4RbicAGx2XthH1mF6t6931ZTOf+1MvKIToOPWZzo/NWOuQah1uU+4dS0qhXowBAIDsEJADAMSQXlNr3IfdiDjqnuD2WFR/QmkYNn2mKZjnXfdJc3iqORAsS+xXLvSZelMTPOCvByfd1mCJe7liQ7E7yXzhayu9kBGxnD355Bb3toEyQOGh+8C+nFS742rjlSf9ADCXgFxhm0JChVRq05zLo798AvJiqABU45CrstudpoBW+7P6seh9Ugi6/L7R5QsJLRXEK/RbNj3zsppH4aHG5V50W78XGpdabU+V4hufH0xs352eTc2/buS7EzXWdejc60bHHFfInG2+QtWLBlq32oNrW+50jeetlyVKse1QrVvXWdtRRXOu13DJXf2JdvuqYtd3zZ0+XrUvuq7aL70QYlela+x5XReF1NqPXPcZ4+3CqRoCIIcfxAAAVQ4BOQBADGkK5hr3YTciptSYz1DZ9JjdpsE86137ibTJzDb9I/83XwZNu6kPnvPWh5PlVNNh4v8zo1gdZL53+gIvXESsBC+6qN29bSDmaKxn96F9OamgrdpQS173PIwVkGu8ZXe8YIVwmaqiQyY6IEdErBZ3LfOHQAAAAB8CcgCA2BGYPYZxbBGzqWpLqA66g10THpQ3BrNMt9nt7kreHDDLvHXjxFobPJboylIujDckv+CqmV6oiFhJTp/e5d42EGPWP1PeAagqKaNaN1cqmdp5ZwvIs7U1XnR7f1rrZRcCckTE4qufvUP9mX9uAwBACgJyAICY0WV2GPeBNyL6DppO9/aBCkZBeZOZY/YF073vQjHcO7JeteDuN83upsdFV7B9ZN33eNvD0qtuLLm2xo8ThYbkdz7zmBcmIlaar33tPrN8efq4oxBf1LbXfXBfbi6c2h85fnKl0d0SJMYsdo9fZgvIx2pXrQA9EwTkiIjFd8+KzD93AQAgHQJyAICY0WzmGvehNyL60ma9etE43weClSP/90nve5G7tyaqi5uCOSPfpfVm2JQucBkwraY+eDpiH7A03mzagrXuZSgrek1NxHFldtGuO81Bb9vhhYmIleiHPlRvenp4rlAOrHq4MgJQjSk8XMF5w8DI/bQ0y9jYmQLy/u7Am9d184uZS8gJyBERi+viO/sr+t8rAIBiQ0AOABAzSlUdiVhpNpoX3NsHqpQB02Z6gr2JcaZbgpdNQ/C8qQueSowD3hi8aJrNfNNiXk60PO80WxNV4oGZ+Jap2jf3e4zFtSZ42PSafe6pL0sUkms4CfcYo/zskau8EBGxkv3ud1vcWwZiyNa55T0Gue3iaf2mo77ynmc1bhs282/MHI7LTAG5gnV3XtctswnIEREnyr2rSccBAPIhp4DcDbjHKwAARDNo2o370BsRo90b3O3eQgCxpzvYbWqDP3vfZxy/apFfyk4Ak8VYIflp5831wkPEavCaaxhqJe50No0doJaTL145WhHdsHXY9HaU77OtrpbA1G4YMq88kVtAnSkgFwtuyR6uazuZICBHRCyeS+8eMCbzj2sAAIiAgBwAIEZ0me3GffCNiJllHHIoTwJzIFhhdgdTve805q+6BfSa/e5JrigyjUt+659neKEhYjW5aFGfe7tAzFjxQOWGoBp/W5Xlhbrmz/kNbq6x0Jfc5a8nH+de5x/HWGYLyOs2DXvzh6rVb5ClYQ8BOSJi8cz2QhIAAERDQA4AECPU/td9+I2Ime0xu93bCKBs6DMNiXbw7vcac3NPcKdpN+U91ng+uCH5ivo7zFvfvt0LDBGryQ9/uM69VSBm1Lwy5D3Ex1HVgj5fJuOFg2wBuVBL3znXpi+z8qEB09uefTkCckTE4rhlTv7/ngAAAAE5AECsaAxeMG4AgIiZbQ+qJxyDyqXDbDT7gune9xsz22RmmwHT6p7Kikfjkofn4OgTlnphIWI1euaZB9xbBWLEQG/ghac4auu+LOXVGdi9YuJfOBgrIBeDfca07h1OtJ/vah57fkFAjog4fvVCEq3VAQAKg4AcACBG1BnGpUXMx5ZgkXsbAZQlQ6bbtJlVpia43/ueY0q9SNZj9rinr6pQSH75LS97ISFiNTtjRo97q0CM2DRz0HugX+3On9JvCnk81tM28eO65xKQFwIBOSLi+Jx3/cjP6PrS/IwGAKgGCMgBAGJEHCsI/3jLt83ZFx2dsw/M+S9vHTg+dw7daC6/43vmB2d/wTy14jxvejXbGMxybyOAsiYwg6bDbDC1wWPe971a3R3caprNfNNnaKUsdu4cNP/9v9d4ASFiNfvud9eari6eNcSVph2Zx6muFBV4K/Dd9MKg2TxrbGvWFj5W7PYF/vqi3DhzMNGSfbwV/ATkiIjxVMOYAABA4RCQAwDEiD3BHcYNBibb9//z281rXvOanD3jwq9468DMrmm+wrw6fKP3ue39s89Knt83v/VNZsfAFG+earU+eMa9jQAqhs5gq6kLnvS+99XinmCaaQleNv1Bi3tqqppjj21KCwYRcdTTTqu+YRfKiQ3PVm4V+dZ5g2Y4xsO/9ncFZs2MwsNoAnJExPi5ZXaM/+EBACgTCMgBAGLE7mCqcQOCyZaAvDROn3mGOfKYQxPnTCG5O9126owfJc/v/3jT682OQQLy0LrgCfc2Aqg4uoPdpimYZ/YEd3r3QCVaFzxu2s1aM2g63VNR9Uyb1pUMAxHR95lnet3bBmJCZ2Ng5lzjP+AvdxX8lwPBsDFL7ur39j8X22rzHys9F1Y9TECOiFiIy+8fMMMUjwMAjBsCcgCAGKE2sm5QMNnaAfklN5xgHpp3dlYX7fq9tw70fc8H3po8r2MF5Nv6rjcnnXmEOeRj/2imPPgDb3o1S0AO1cSw6TOdZotpCJ4f+f7f7N0P5WxN8IBpDZaYvqDePWz4Cy0tw+agg2itjpjNQw5hKIY4s3PRkPeQv9zt6yyfZ1yN2wprdV+7oTQpzMJbCwvsERGrWQ2b0ba/NC8uAQBUGxkDcjfULqYAABBN3APyx5f8wpuOhZlPQI6ZJSCHamXAHDBtwWpTG/zZuy/KRVXENwVzTbfZ5R4eRPDjH7d6YSAi+l50Ubt7+0BMGBowZvG0yglFNe54OdHbHnjHkIubXyx+lXx/d2H7gohY7dasJRwHACgWBOQAADGi0gLydQeuMivrLzNbe69Pfrax81rz2KJzzW2P/9i8uPE3Znv/Dd5ymdzQfrV5avl55uZHTzVPrTjPbO6+zptHaptybcuVyc+03ftmnWmmPXW6eW7N+WZl3eg80l3edufQjd76NnVdm/xM1d2aZ/72S8wdT55m7nvxLLO05lJvPaHhsv/wjr9LntdZGy5Mrs/eH401bn8uN3Zc463TVtNnLP65ueWxU83MVy5IO/eu4frtgF7job+045LE9Xl4/jlmVcPl3nJxkoAcwJh+02zazTrTEMw0e4K7vPskTmpM9dZguekJ9phhU17BwmQyd26fFwIiYmY3bSp+oAfFYf/6yqkir5aAfOHU/qK38q1ZWznfA0TEiXLTC/x+AwBQTAjIAQBiRKUF5B897D2J5X70i39PBLdf+vqHkusKffNb32Tun32Wt6ztDQ/8wLzzvQd5y8rDjni/eXDu2cl5VzdenpymKu31bVdHbvcd735z8n8/sfQX3jZDte5wvkM/+a7EZ2f+5qvJz04554vmg4ce7K1fY4VfO/0kb32nnfdlb17XsE393c/91Jv2jRM/5a1Tzt702+T5dj3qGx+OfBFALwyE86youywRimu/3eW/dcqnEy8YuMvHQQJyAJ/eoM60mZWJMNq9Zyba/cEjidbpBOLj47OfbTBuAIiImf3mN5vd2whixNoZlTP2dDW0WJc7FhYvlFH1+Lzr/W0gImJm1z4+4P44BQCAcUJADgAQIyo1IJcaP9sNXm2fXvkrb/nVTVckwl133ihVXa5lVPEcfqYq7c8e+UFv3h/+7EvmvD8dk/zv75/xeW/boSf+5HPJ+S6+/vjEZ2dc+BVvnZn8+n9+3OwYnJJc349/eaQ3j2u+AbleIHDnc9WLCKrct5ebPvOM5PRM4Xrokccc6m03DhKQA4zNoGk3PcE+0xFsMq3BUtMYzEq0Zt8b3O3dU/m6e/h2UxM8nBgXvSV42bQH602P2W0GTKsJTJHLzaqUqVM7jRv+IeLYPvVUr3s7QUzoORCYBbf4D//L0Q3PFi84LiXBsDFL7iq8vf2LV/aZph3jb+s72GfMqkcq5wUJRMSJcPVjA0Xv5AEAAATkAACxIu4BuYLlP97ybc9r7z3ZW066oatC8t/d+K1EUHvlnSemVSsrCHeXP/Z7n0pb/runHW6mzvhRooX41Xd/PxHa6vPL7/hechk7IA9VJfnNj/wwUSF93EmHmfnbLjZL9v0xOV37odbn7vbV/t3ex7B1uhuQH/OdT5q7nv2JeWje2eay276bds6kXUmubatyW4F1OP2mh09JfBaqtu2aV/v4p6nfMSedeURyXjcgV5hub+vTX/zfiX1R23a1orfHOtf/tlva2wF56MlnHZFYXq3i3fP/zCr/JYbJloAcYHwEZtgMmV4zYNpMn2lIBOldwQ7TEWw0bcGaRCW6Qu8usy0RfKs6XeH30MgnBOClZ3DQmHe8o9a4wR8iju0nPlHv3lIQI+q3FF7NHDe3zhs0wzHOyfu7ArOmSFX7658eKKhqXgG9rvn8GwsP6RERq1G9VDRE8TgAQEkgIAcAiBFxD8gzqbDXXU7aAfnXjv+YN2b4owt+lrYeu9Labv8tNb63u36pINj+bzcg1/6/0nqVt5y0W6+rCtudbgfIR3z1X5Kf2wH52Rcd7S2ngPuEH/xbch5VsrvHbgfX9hjgUT4w57+S87oBucL5cNoXjz4kGa6Hatx0uz39pbd+OznNPj69CBDV6l6BezjPry471ps+2RKQA0Alc/HF7cYN/RAxd2+9tdO9rSBGbHtp0AsCylWNR64QQ+PDbpoVDzfOHDQrHhgwc67193e8Lry137zy5IC3Tc+RfVh+34CZfbW/DkREzO7KhwbMYB9ZCgBAqSAgBwCIEZUckC/Y+TtvurQrqcMKbfnJw9+X/FyV4+5ymXQDclVDu/OEKnQP51Mrdne6xt4Op9sBuh2QR40zLt39UHW5Pb0YAbnGDbe38fza871l5R9u/s/kPLom4ed2QK5jdZeTqvQP58nWin6yJCAHgEqlrm7I/PVf7zNu4IeIufuud9W6txbEjNWPFqeyGRERsZJccf+A6e8mRwEAKCUE5AAAMSLuAbnafT+57JeemYLZXALyT3zmvcl5wnHIXx2+Ma21udqSu8tl0g2m7ZbirppmB/Th2N9yS891afuwseOa5LRcAnJ59AkfS86nlvD2tGIE5GpVH36u9vXucqFL9qa3kw8/zyUgV6v1cJ44jkNOQA4Alco55xwwbtiHiPl7+eXt7u0Fk0zrnuGEqm5eeg8BOSIiou2yewsbzgIAAPKDgBwAIEbEPSB/fMkvvOnZzCUgD8cRl08sHV2/KsnDz+TOoRu95TJpB+RqLe5Od/3p+Ucl5z/3919Pfj7tqdOTn3/z5MPSlsk1ID/tvC8n53NbsRcjIFfoHn6uMN5dLlQvAoTzybDlfC4BuV5aCOdRC3d3+mRLQA4AlciuXUPGDfkQsTAPOqjG9PW5dxlMFGEYvmPRaLtvNwRARETElEvu7jc9beQnAAATAQE5AECMqMaA/KhvfDg5TxiQz1j88+RnuYTctnZArhDane46Z/Nvk/NrrPAwjFcQHX6u8dDtZXINyDVmdzif2ya+GAH5b675ZvLzTAF3aDifDCvycwnIn1lFQA4AMNGccUarcUM+RCzcP/6RKvKJgDAcERGxcBff2W+6W8lOAAAmCgJyAIAYQUA+uv6XdlyS/Eyq5bq7XCbzDcilPd75g3PPNpu6rk3+t1qw7xiYkjZ/rgH5yWcdkZzv3N+lqtNlMQLya+89Ofn5147PXEG+sTN1PFLHp88JyAEA4seePVSPIxbbt7xlvxkY4FlEsSEMR0RELI7L7u03Xc38rgIAMJEQkAMAxAgC8tH1K5C2A12Noe0ul8lCAnI7aFY79VseOzX532qT7s6fa0D+2SM/mJzvhgd+kDbNDsiX1/7JW9Y2U0Buj0F+6Cff5S0XOvOVC5LzKfAPPycgBwCIH+ee22bccA8Rx+9VV3W4txvkgR2GE4gjIiIWz02zBs0QL/IBAEw4BOQAADFidzDVuAHgZDsZAbk85GP/mPz8lHO+6C2XyUICclVU/483vT653Ke/+L+T//u5Ned78+cSkGu5cB6poNmebgfkz6/1t2GbKSBfWX9Z2jbmbb3IW1b+8GdfSs6j0D78vDIC8sfd2wgAoGxpbR02f/3X+4wb7CHi+H33u2vdWw4yQBiOiIhYeudc22dq1g65/wwDAMAEQUAOABAj9gS3GzcAnGwnKyBXxbUd/t786KneshovXAH1U8vPS35WSEAuv3f64Wnbkzp2dz5pB+QXX3+8N33Jvj+mHfthR7zfm+dLX/9QcvrP//B/vOm2mQJyaY+VfvQJHzPb+29Im/7UivPSjmnaU6cnp1VCQF4fPO3eRgAAZcsf/tBu3FAPEYvntGld7m1X9RCGIyIiTrwrHug3bbXD7j/LAAAwgRCQAwDEiL3BPcYNACdbOyB/53sPSrTyzubdz/00uex4AnKNO263KJdHHnOouWTKCeb2J35sLrjq/yarzD931D8llys0IJ+x+Odp25LahjuftANy+d3TDk8E+grrf/Lro9Kq0eWTy37preOXlx6TNs8RX/0Xc+WdJ5qfXfIfXlidLSDXebXXo+p37cd9s870tuEG9ZUQkDeame5tBABQtrzjHbXGDfQQsXh+8pP17m1XVSgMl4ThiIiIk+eW2YNmmMJxAIBJh4AcACBG7A8eNm4AONnaAXkuXnNPquX4eAJyqUpshbruNqIM24sXGpArkP+Hd/xd2jozjX3uBuTZvPyO73nLy42d13rbs93Sc11y3mwBubzp4VO85V31MsFLOy5JW64SAvJm85J7GwEAlCV3391t3DAPEYvvCy/0urdfRUIYjoiIGC/n3dBnataRjAMAxAUCcgCAGNFgnjNuADjZfvDQg40btmbz2ntPTi77ic+8N/n5y7t/761bfu34jyXnUTtwd/qOwSnmt9d+M1G97m5LKjC2g/U1zVckp2VqkZ5Je1/ssbpd7YBcIbxbMR4u/8K6C7xlbRft+n3aOQrV+uZvT4XZD88/Jzntmycf5q1Hzt92caIK3V3Xm9/6JnPaeV82W3uv95a5f/ZZyfm+/aPPetPlzFcuSM6jtvDu9Mm2LVjl3kYAAGXJZz/bYNwgDxGL7wknNLu3X9lDGI6IiBhvVz40YDrqaakOABAnCMgBAGJES7DIuAEgptzQfnWiXfnTK39lVtZflqj6ducZj6f/6ssmDIPVptydHmoH5JpP+7G05lLz2KJzE5XyGhvdXSabWvbRheeaOZt/mzhGd3o+atuqFFfL+NVNV3jTK82uYLt7GwEAlB2LF/d5IR4ils7duwfd27BsIAxHREQsL7fOK9/fOwAAKhkCcgCAGNFpNhk3AMSJUS3NNYZ6GHyvb8scVLsBuTsdJ84B0+LeRgAAZcePf9zqBXiIWDovuaTdvQ1jCWE4IiJi+brhuUHTXksWAgAQVwjIAQBiRF/QaNwAEEur2pxfeeeJaa3Ojzspuo15KAF5PNwT3ObeQgAAZUdvb2De8IYaL8BDxNL5vvfVubfipEMYjoiIWBmuf2bAHKihnToAQNzxAnI3zC6FAACQmT3B7cYNArE0KhgPg+7QQz72j2Z14+XevLYE5PGwLnjKvX0AAMqOadO6vPAOEUvv88/3urfjhBGG4TsWDRKGIyIiVogvT+s3G54bcP/ZBwCAmEJADgAQMxqC54wbBGJpvGTKCcYOx1VFvrblSm8+VwLyeNhmVrm3DwBA2fHv/97oBXeIWHq///2JGaaFMBwREbH61L/5+rdfvwMAAEA8ISAHAIgZHWaDcYNALI13PHmaOfKYQ80Pf/Yl8/D8c8yrwzd680R52e3fTYTpcvrMM7zpODH2m0b39gEAKCt27hz0QjtEnBhf97p9iSEOig1hOCIiIroSmAMAxA8CcgCAmDFkuowbBCJiujXBA+6tAwBQdlx2WbsX2iHixHnvvd3ubZkXdhhOII6IiIi5qt8fJAAATB4E5AAAMaQ+eNq4gSAipjxglru3DQBA2fGpTzV4gR0iTpzHHtvk3pYZIQxHRETEUklgDgAw8RCQAwDEkC6z3biBICKmHDBt7m0DAFBWbNlCe3XEONjR4bc6JQxHRETEyZJ27AAAEwMBOQBATNkX3GvcUBARbzKNwQvu7QIAUHZcfjnt1RHj4NTruxIPoAnDq8NFt/WbOdf4nyMiIsZVAnMAgNJAQA4AEFPag7XGDQYR8SbTG+x3bxcAgLLj8MNpr44YB4/4cKP3IBorw/ClBwUKbqgw74Z+b35ERMRykHbsAADFYcIDcgAAyJ29wT3GDQcRq9mG4Dn3NgEAKDvq64e9kA4RJ8c3vL7Ge/CM5We2MNxloDfwlkdERCxXCcwBAAqDgBwAIMZ0mI3GDQgRq9m+oMG9TQAAyo677+7yQjpEnDwv+2GH97AZ42s+YXgU9ZuHvXUiIiJWgrRjBwDIHQJyAICYUxc8btyQELEabQkWurcHAEBZ8p3vNHsBHSJOnid8vtl7wIzxcLxheBQbnmOseURErA4JzAEAMkNADgAQc/pMvXGDQsRqc19wrwnMkHt7AACUJW97234voEPEyfN9B9d5D5Rx4g3D8FI/yF90O+OPIyJidUo7dgCAFImA3A2xiyEAABSPA8EK4waGiNVkj9nl3hYAAGXJypX9XjiHiJPvQxf2eA+RsXROVBjuMjxovH1BRESsVgnMAaCaISAHACgTGsxzxg0NEavBA2apezsAAJQtV1/d4QVziDj5XvCddu+hMRbHyQrDo2jczvjjiIiIUYb/VhOYA0C1QEAOABBzek1NwtpghnGDQ8RKt9E8794SAABlzbHHMv44Yhz9P//W5D0oxsKMSxgexbb5g97+IiIiom+c/z0HACgGBOQAADFFoXhd8IRxA0PEarE2eMwEhjeXAaCyeMtbGH8cMY7+v/+r1nswjGNrPzwvhwfoy+8b8I4BERERx5bqcgCoNAjIAQBiBKE44qj7gwfNoOl0bxEAgLJm48ZBL5RDxPj4+CW93sNgTFluYXgU7jEhIiLOn9KX+DdC/7bp3zn9e+fOg74E5gBQ7hCQAwBMMmELdYJxxFFrgofMoOlwbxUAgLLnzju7vEAOEePjn37Y4T38rVbDccPLOQx3GeonIEdERN/Vj/a7/2QkCANgd370ZfxyAChHCMgBACYJQnFE37rgcTNkut3bBQCgIvjJTw54gRwixsf/76hW74FvNViJYXgUfZ2Bd+yIiIg7FuYW6hKY5y7jlwNAOUBADgAwgRCKI2a2ycx2bxkAgIriX/+13gvkEDE+fvaQBu8Bb6VZLWF4FN0tBOSIiOjb2ZR/lhG2Yycwz02qywEgjhCQAwBMAATjiNltN2vc2wYAoOJ43ev2eYEcIsbHt//P/d4D3XK2msPwKNrrCMgRETHdtTMG3H8uCoLxy/OTwBwA4sBr3GC7WAIAVDuE4ohjWxv82fQFde7tAwBQcWzYMOCFcYgYP2dc0us9xC0HCcPHpnUPATkiIqZbt7E0/2aGATCB+dgyfjkATBYE5AAARSQMxQnGEbO7J7jdtAVUjQNA9fDQQ91eEIeI8fPa0zu9B7dxkzC8MBq3D3vnEhERq9eFU/vN8JD7r0VpoB177jJ+OQBMFATkAABFgGpxxNzcHdxiWoPFZnjkrgEAqCZ++9s2L4hDxPh59nEHvAe1k2kYhvOgePzUbhjyzi8iIlav2+ZNTsUy45fnZ3iu+D0IAIoNATkAQIHEPRTXvnWazaY5eMnsDqZ60xEn0n3BdNNmVpgh0+PeSgAAVcG3vtXsBXGIGD+PO7zZezA7URKGl5a9qwnIERFx1Bev7DPt9fHIMBi/PD9pxw4AxYKAHAAgD+LeQl37pX2UNoEZMp3BZlMfPDsy383ecoilcE9wh2kK5pjuYFfa9xEAoBr56EfrvSAOEePnYf/U4D2ILYWE4RPPrqVU6iEi4qhb58Y3YA0DYALzsWX8cgAYDwTkAAA5UA7V4m4ongmF5T1mt2k1SxLL7QmmeetDLERViTeY50ybWTXyfax1v3oAAFXN3/xNjRfEIWL8fOdba72Hr8WQMHzy2bWUCnJEROwz86f0m5628skvaMeeu/y+BQD5QEAOAJCBSgrFx2LY9Jh+05gIzrvMVtNhNpj2YD1iRjvNxpHvyjbTE+wZ+e40m8AMuF8rAAD4Cw0NQ14Ih4jx9K//2z7vYWu+2g9neUAbH+o2EZAjImKf2bm4fKuNGb88P8Nzxe9jABAFATkAgIUC5wPB8tgG49ov7V+xgnEAAAAoPcuX93shHCLG14cu7PEesGaSMLx8aKsd9q4fIiJWly/f0W8G+yonu2D88vykHTsA2BCQAwCY6qoWBwAAgIllxoweL4BDxPg65YxO74GqDMcNJwwvT/q7jXdNERGxuty7esj956GiCANgAvOxZfxyACAgB4CqhVAcAAAAJoIpUzq9AA4R4+tF328nDK9QZl/tPyBHRMTqcMOz1ReE0o49d5fdO2A2zx4wdZuGTc+BABGLaXtghmI4OicBOQBUFQqc4xyM00IdAACg8jj//DYvgEPE+HrzzZ3ubQwVwsvT+r0H4oiIWPkuvXvA9PeQWRCYI+JkuuDWPrPx+UHTEpMXkAnIAaAqiHMoLqkWBwAAqFx++MNWL4CrdP/qr/aaz3++wXzhCw3mox+t96aP18MPH133Jz6R/7pLvW9Y/l58cbt7G0OFsOYxWs4iIlabs6/qi00YEycYvxwRJ9MNz05+SXlRAnIAgDhCKA4AAABx4Nhjm70Abrwq4F26tN80NAyZ/v7AdHUFpr5+yCxb1m++8pVGb/6J9oMfrEsev/bPnT4e3/KW1O9Pg4PGmz6Wpdy3fPx//p99ZurUTrN9+2Di+mlfWluHze7dg+ammzrN3/5tjbcMTow//Wlr8jsClcWW2VTNISJWm3tWVfa448WC8csRcaJd/djkhuQE5ABQccQ5GNd+EYwDAABUF6p2dgO48fj00z3uJjx+9avJbeteyhC6EgJyfScUimejs3Ny9s32fe+r9T6rBr/97Wb3ckCFsHv5kPdgDhERK9eNMyc3fClnaMeOiBPhrmWT9xITATkAVARxDsUloTgAAED18qEP1XkBXKFedVWHu3ozMOD/Tfae90xusFnKELrcA3JVhvf2pl+z4eHRY7FZsqTfW3YifMMb9pm77+5KBPjaT3d6NfjVrzamXwyoGBq2DXsP5RARsTJ95QnC8WJCYI6IpXDBzX3uj5sJg4AcAMoWQnEAAAAoB971ruKE1Ro7W0FqSF3dULLCV+261Vp99ep+s2vXoLfsRFvKELrcA3KFzza/+117ctrBB+9PvAShcFpVzO6yE+FHPpI6P9UakH/mMw3WFYJKoq8z8B7KISJi5Uk4XloYvxwRi+mBfdaDjgmEgBwAyg6CcQAAACgnDjpovxfAFeKXv5xe1frOdxZnvaWwlCF0uQfkr76aKhWfP7/Pmz7ZEpDvNR/+cOocQOWx5O5+76EcIiJWjoTjE09YXT7/Rv6NRcT83bNyctqsE5ADQFlAKA4AAADlyhveUOMFcIV43nltyXWON9h94xv3maOPbjJ/+EO7OeOM1jFbsqst+LHHNpk//ak94XHHNZnXv36fN19oPiG0qt8///kG89vftpkrr+wwp53WmgjB3flCowLyd7xjf+I4VI2t8b1f+1p/udB89i30n/+5zvz85wfMxRe3Jyr1df7ceXJVY4uH6Hjd6a46Fm1fjnWd/uZvapLzvu1t6S9QHHJInTn99NbENvX/NY+7vF66+Na3UuNv6/yE68tl+29/+35zyikt5rLL2hPr0X+784S++c2j+2pfa11Hnefzz28zn/pUfaJrgr2MzoXOv9b/gx+0lOwlkQ98gIC8ktmxkHHIERErVcLxyWXlQ1SUI2L+bptPQA4AkEYYisc1GCcUBwAAgFx47WsLD1Nt7eBSuAFoLqpttx3Q2igMnTaty7zudan9PemkFrN/f+Y/Vpct648Ms3MJoRWAqiV8JtRC/l//td5bzg7IxZ49/v7pz9R58/oiQ/xc9i303HMPRI7xLrZtGzQf+ED2wDjK2trU/uZSQf7xj9cn59dx/f3f++c7dO7c1PhtixePjmGuNvzbtzsDnP+Fjo7AXHddKqTv7o4+1pBMFft6waG1NbotnrahlyvcZRYuHN1XTVewH7WPOl699KDv5KxZvYn/dpk9uzcxbrq7/vGo4B0qF7VwdB/KISJi+Us4Pvksu5eAHBHzd/OL/t+CEwEBOQDEDqrFAQAAoFIYGooOFAtR1bU2ChRVfe3OF6Uqb8NAcixUia1ltO5c/tw7cGDY214uIXRNjR9su2j74TjroW5Ang2Fr4ceml4pncu+yVWrMof3Idq/k09u8ZbN5oIF6ddB1fjuPK7NzanwWWOUu9ND7TBfL1QoWM4UXIesWTOQXL6QgPz66zvc2SK5777utOUWLUqdB603G7pO2dA5dfdrPKryHSqbeVP8B3OIiFi+bpkzxi8TMCEQkCNiIRKQA0BVQygOAAAAlUi2ALYQt25N/8NR1eBql+3O53rXXV1py7W0DJtbbulMhLtXXNFhXnlltOJG42Pbyz33XG/icwWYCjRvvbXTTJ3a6VWVq+W1vVwuIbRacYesXTtg7r23OxG2usG0ptnLuQG5QmEd349+1Gpuv70rEdjbKIjPd9+mTOm01mDMunUDibbfOtfTp3eZYWsTWke2qm5XVVu7zJnTm3gBwp03VKF4SFOT/0KCdFuj6zN1DLDRcZxzzgFz6aXtZu/e0WuolubhOk48scXcdFPq2HXdNT1U18ze5he/2JicV+h7pe+C5rvmmo7ECwo2ao8eLmsH5ELX8ZFHuhOt9vUdiHrUoO/pL35xIDGP2wnBfRFiPL71rQTklc6G53iAj4hYCc6+qs/sXT32S5cwMRCQI2IhEpADQNWhwPlAsDy2wXgYihOMAwAAQKH09UUHsIX67nfXmt5e/28wVQkr+HTnlxrn2f6zTa23oyrPP/GJem/MaP3388/3moMO8gPgMFQXhYTQ8sknexKt1t3PFdqHaN/taXZArmkay9qermr5Z57pSc4j7BB4rH1zz9evftXmzaPrYFc1z5jR482TTbWyd9E21SI9apxvjQFv71PUObMDZx2/Prv55lTYrQDaHdNbLxWovbn92Uc+kjo/+q652wnVebZfRlAVt7t+VbDrpYsQtc0Pp9n7G451bi+rINzGrUDXdbdfVLjgAv86Fepb3kJAXunUbmAcckTEcnfJXf2mZU/2TjkwsRCQI2IhEpADQNVAtTgAAABUC1EB7Hh973trzcaN0WMsqrJbY1bb89vjUmt/7DHGx+Phh6cqod0gdawQeiwVtNptt+3Q2A7Io1p+h6qaOUTjfoefj7VvL7wwWjUvNEa6Oz30wgvbkvPt3p1eeZ+LWj5qfHP9ia3qfnf+lStTlfUzZ/amTXPPVzh2+3nnpfZRfPSjfrDummtAftpprcn51Jo96qULqe9riI4t/NwOyNWZwF1O44pHLWdrj2H/8MPpAfp4pIK88ultD7wHc4iIWD6ue2rQ9HX5v0fB5EJAjoiFSEAOABUNoTgAAABUI0NDmQPG8aqxqxXMuigotdtN2+3Q1YLcXU8uqlpXrdWXLu1PhM3t7cNm06b0kN6ef6wQ2lbhrsLiefP6Esejttw7d6Yf1/HHNyfnzzUgP/vsVAWygujw87H2LWw9LtTe/corOyJ96KHu5HyFdgpQa/b77++OHIM7rAIPPfbYpuQ0txr8pJNS7erVTSD8/G1v259WZa0/39X6PNtLErkG5KroDtE23fNjaxNWitsBedQLATJE++1Ok48/nuoUoE4H7vRCZQzy6mDFA/3ewzlERIy/OxZG/OIEsYCAHBELkYAcACqOcmihrv0jGAcAAIBS8trXZg4ji+ExxzSZ5ub09pIKxcPpdpWyxhx3lx9Lje9th6yZsJcZK4QOPeOMVtOVQ/XPD36Q2u9cA3I76BXhOOFj7ZvdOj1Xsu1HLqrN+WOP9Rj3z2u9BGHPZ5+rn/40Nfb88uWpSmr3JQj7RYEQ7a/mi6r6zjUg13jmhfCZzzQkli9GQP7gg6mQvpgB+bvelap6h8pl5yLarCMilpPLpg+Y5l05/FIKkwYBOSIWYlkF5AAA2aBaHAAAACCFWkW7AVyxVTXxqlWpkFSoUlfjRNtEjV2dzaeeSh/LW2G7KsdV7b19e/ofsfZyY4XQUmNG2+hPTY1XPX9+n1m/fiAtlC8kILdbdIv3vW+0TXu2fXPPl/ZBxzyWOhfu9gvxqKMa047bbfFuj12+devoNhVy28u8853p48hLVZ/b44WHKHB3x/7ONSB3X8pwz0mUOt/h/RDngPwDHyAgrwZ6OwIzf4r/gA4REePnljmDZqiwd/NgAiEgR8RCJCAHgLKGUBwAAAAgmoMOGq1cLrVuW+iwwtgOT7/97VSr8rG0x5gWTz7Z44X9Nvbn2UJoqdbf9p+Wu3YNJsaqtuexW8MXEpBrvO0QO2Ada9/sduff+lbu56tY6gWBELtdujz44PRrrGt++ump6zTWWOia163YV9Btz5NrQK6APkTV7+70sYxzQP6Rj6S+O1DZbH+JKnJExDi76PZ+U78l9TshxBsCckQsRAJyACg7FDjHORjXfhGMAwAAwGTz7nenB7+ltLMz9ffaVVd1JD5rakol5NdfP/pZLi5enKpIV3W6O13a2J+PFULfemtncroCWzd4l+MNyLVMiLYRfj7WvtXXp7Z7ww3RwW0pPe+8VGV91P5t2ZJ6eKA26RonPURjubvzu2r88Rdf7E0uI+yXE+yAPGr7ofb43+oq4E4fyzgH5J/9bENyvVDZ9BwIzNzr/Id0iIg4+W54bsD0Wb/bQvwhIEfEQiQgB4CyIc6huCQUBwAAgDhx6KHpLaxLpUJmu1o8DEuXLUsF3d3dQeS401HaLbk1Vrg7XdrYn7/nPektqlUxbk9fsCAVjs6eHR1sjjcgtyucFSqHn4+1b3Zwq/P1+tfndr6K5X33pUJfbd+dfuqp6cF/+Ce6/n/UiwZRqiW/Wp6HXHdd6sWJQw5JBeSZgmlpB/ki3/b9cQ7Iv/a1puR6ofLZOm/Qe0iHiIiT54oH+03DVn9oGIg/BOSIWIgE5AAQawjFAQAAAArjc59r8AK4Qv3tb9vMypX9iSpf+3OFuBqv2iYMfj//+fRq2KVL+yOD1B/9qDWtYnrv3lRA7YaPCljtVuBCwXM4XSG8zU03pQeg99+fCjbdFt/yd79rt5Y25uKL25PT7IBcf55GjbmtlwNsvvKVxpz3za0eViW9qq7dbRx3XJO54orcK/JDde401vrvf9+eGPPcnva1rzUmjilk7ty+yOVV2e3ijlceqtb4//VfB9I+e+Mb96Vt5447upLT3HHY1ZbdXafUd0gt2ENaWoYjuyVojPNHHun2Po9zQP6d7zQn1wuVT9fIz6DZV/sP6hARcWJdek+/2b+edurlDAE5IhYiATkAxJI4B+O0UAcAAIBy4BvfKN441gohQ/S/VR2uwNwNTPW5vdwLL6S31Faw+cwzPebSS9vNvfd2m9ra0YeR+nMvDNZnzEi10NbnM2f2JoJWtW6vq/MfXv7iF+khrDvWtbZx+OGjLwtoLHSb5cv7E6H2+ee3eUG/WLgwFRTbAblQ1bzCVh3Lo4+mjiVkzRq//Xe2fZN2FbfQ/BpnW8G9ztf27ak/4D/xifwqp+2x3VXFvXPnYOJlA40fbqNz/m//Fr1uXTuXE09MVdmHvuMdqTHL9SKC9v2uu7pMQ0P6OfrCF9Jf4rC/Z0LV+Dff3Jlotf/EE6nxxvWSgI2uxaxZveZPf2pPhN56GSN8hKDrY28jzgG5OiZAdbFlNlXkiIiT5aLb+s2elYPJ3xmgfCEgR8RCJCAHgNgQ51BcEooDAABAOXHqqdEVuPn68Y/Xu6uOROG12xZcFcPr16fGqs7GtGmj1cR/+7c1pq8v+99/7e2pIFXhqF3NrTDdRRXw4XSNW50NBbo2YZt1NyDPhkLnt7/drzAfa99URf3KK9n3L0TBubv+bOZ6Hdyqb1u3yj3TWOHqCDAW69b5LxAcf3zmCmpdc3teezz5bOh7aS8X54D8kkvSOxhA5dPZGJhZV/gP6xARsXQuuLnf7Hx50AymNyWCMoaAHBELkYAcACYVQnEAAACA0nDhhemVs4X6N39TY+68s8urFg/R56rSVQtud9lQjRutca2j0JjjWt5uJ6722G5FtmhtHTZHHdWYCOLtamS1c7e3p6pwO2S3Q2gdjyrDXTT/RReNzqfxyUOmTh0NUe2A/IIL2rxqaKEKeVU8u8ef676FKqSOOl8a+1yBr9aR7XxHefTRTWnjo7voxQGNA+4uZ6tt2n+aq0OAO4/UetSm3R6bPkSfqaLcfZki9KyzDkQup3PmzqvAPqqrgPZR3ytV5P/939ekLTNvXuraT5kSfa3s9bjTpPY/5Omn83tRIZsK7KH62PQCVeSIiBPhkrsHzJ4VQ2YgvcERVAAE5FjJzr+x36x8cCChXvBxp2PhEpADwKRAMA4AAABQWm68MTr8K1SFo4ceWmdOOqklEXhrvGR7/O9cVEX5Mcc0JaqyP/Wp+owhaeh731trTj21JRGAawxvd7rajGs/oqbJ972v1nzrW82R1dxvfnNNYtljj21KVK2703Vsasl+8MGjy+r4f/rTVvP1rzcl51H4qvWr5beCd3cd2cy2b6HaL61b+xnux3jVceslg3POOWDOPvtA4tyOdR1s7TbxCqjd6bY6Z3rZ4Xvfa058b/T9ccc/j1Lz/Pu/NyauvbYx1rnV9f/iFxvNKae0JLbnTi8X1UYeqo/OhsDMu56HnYiIpXLVwwOmdkPE23dQMZQ6IFcouXXeoGnYNmy6WwMzPGjM0IAxPW2Bad41bFbcX9rtl6urHxswbfuHTUd9YLqag8S50zlrrwtMzStDZuNzg2bBLfwONJa1G1IvBOv75k6fKFc+NHI9a4cT98G86/3p5WjsA3IAqBwIxQEAAAAmjscfL15lK6LUSw0hbstzHL8rVvRbdzBUE3tXDXkP7BARcXyue2rANL9KMF4NlDIg3zY/t3HqD9QMm7nX+ctXs68u8Ts9RdG6Z+TcXesvj6OWOiB/8co+s/DWsV9UGLT+VNm/vjJ+dyUgB4CSEobicQ3GCcUBAACgUlm5st8L4BDzVdXcqmJXdbNavIfcccfomPFYPOvreYhfzSjIcR/aISJifi6bPmB2LhpKVKhC9VCKgHzeDf2moyG/79HCqWOHjNVkrgG5GB6Zdd2Txb+OlWCpAvKX7+g3LbuHTTDyJ4h+ZrrTXXWNQpp2FG8/JlMCcgAoCVSLAwAAAEwuTU1U+OL43bnTf2iwbdtg2pjxOH7f8Ab+Nql21HaUNqOIiPkbhuJq5QzVSSkC8t729GxKUZWCyvXPDCbaSy+6bbTtejimfXvt2AFjtWkH5GpJrwB81SMDZtvIeavfMmwGevz8T6Gtu55qt1QB+e7lqfXmEpBvmT2YqCJXm/xFt1fGdSIgB4CiQSgOAAAAEC/+7u+KM241Vq/796dXfqxbN5DTOOKYn//yL3Vp5xmqk0ppV4mIWGoJxcGm2AG5G5opBM8W3G5/aTDr9GrVDsgVhrvT5b416X9r6IVBd55SqxbjL17hfx4X4xKQV6LuvT5RVH1APmz6TZ9pMD1mr+kOdiOWrW1mlWkMXjQ1wUNeIB0HtV/aR6n9VUA+MPJfAAAAANXAxz9e7wVxiPk4e3av2bNnyMyd22e+/OVGbzoWx2OOaXJvX6hSNs4c9B7eISJWu7Ov6TNrnxgwe1YOmY4GQnFIp5gB+eyr01tJq/J59lX+fLmq4FzaYzzPnzJafa6XPF4Z+V5rm/YyC27uNxueHUwEmJpnxQMDeQe42qbCP4XUqtrO5RjmXDtynz0+YHYtHTKbZo4/9M8lIJf7VqeH5Npvd55QnYcV9w+YnS8PJc6hrn2u50bHs2XO6HnV71u6Jlq2tyNIBPP2OZpzTeraqd2+vY6di4cSVfArH/K/d4vv/Ms2VozOk+851FjsiWu/bCjx//VdyCUgn3vdyLWbMXLtRs651HV0v1e22q/ajamfpV0tQfJ4pb6j4bzqcGRPk9nOedo1GjkXi6dlPwc6Rq3THode29d38NWRc7360YHE9XCXK4axDsgrkfZgvak1f/ZCPEScWPcGd5qmYK7pCxrd2xQAAACgYvj2t1u8IA4R4+fPf37AvX2hSunrGn1A6T7AQ0SsNl++vd9snTtomnYOm+HJyTCgTChmQK6XMGz0HXTnyVW1oQ5R6P7STf2mv8vPvRQGKlRUKKpAPhM164ayBpMKGFv3Zn6BRK2xVz7onyvtV1ezv19C41MrpHSXycVcA3JVcNv3eGejP6+OW23ZM6GfE5lCVIW1YSt8F7UMD+lsSm1XxxyisejXzBjwfg5pnZp3/o39pnHb6FjeUWi5TS9k/x4prO/rjL4G9gsbbkCuED3TcqKtNkgLu6UC77FQYB7OH/WdjHo5QNdR+xeF4t69q6K/R0N/2R0NU6BzGXWPaHmF7e6y4zV2AXmlMmjaTW1AMI4YR9uC1e4tCwAAAFARXHxxmxfEIWL8vOOOLvf2hSpGD4DdB3iIiJWuQhtV0yqg7DlQuTkBFJ9iBuRttamAb7BvNAAtVL3wFqLwNCqkba8fDSJV/ZsLLbujf0dQxbAdpGbCPSYtlynYtVG4ni2cjzLXgFzWb8583vWzIercuej4F05ND4N1fLmgZe2XB+x97+8OEgGtiyrJNW/dphxO4Agaw9s9brn6sdyugbADcgXSueCeT4XxY5FvQK515nKNVKmv/baXDQNyEbUtm3VPFe9elwTkE0Bghsz+mLafRsRR24O17q0LAAAAUPY88ki3F8QhYvxcvHjsB1VQXailqvsQDxGxUlTr3xUP9JvtLw0lKi+jKgYBcqWYAbn9XcwURueqHZCHKIhVpbgqlPUiiB00KkQWqmpWEKqXRdQG261cXjY9/XjVAtwNWLXvavGtALBuc2odqoQOl1PFuR2qax01r4y2V9+xaDARZtrsW5vf7yb5BOQ7FqYfpD3NrW5XtbjamMuWPekHbo9hrrbj9vHpf6sjwKqHB9LalgtViWfa9xB9NzTevCr59cJA2JJdFfghve2BaRj5maY27tpPG10Dt9V9tmu3Y8FgYn02bgV5uA2t40DNcGJMd10nt6pcbfPDZRRQ6zy07U9tWMemlvWhassfzq8XAXS+7P10A3JV/dvo5/q6JwcS3yVVsduopb69rB2QC4Xk+s6qDb6+jzY6LnvZ8UpAPgG0mJe9MA4R4+eg6XRvXwAAAICyZtOmAS+IQ8T42dFRmc9DYHwQkiNiuaswSK3SVSG5efZo2OEGKQDjpZgBuR0CZmoJnatuQK6AVtXQ7nyhChQVHrqV2hob3A7JVbFsT2/dl9pp7b8dboYqFHU/t8NlVf/aY22HukFypjbmUeYTkCu4t1F7en2uttohig/dlwOkWyUeVhm74We4zlBdXxt7zG43INfLDO51sdVLDxuf9yvE9d20UacAe7rC8BBduzV/Tp+ubdovKrgBucL55leHI6+d/bM2KlhWiB/SXudPd7Xb0dsBuXvtosaQtzsE6DjnXZ+aZgfk2k97mtw0K/06uhXo49H9jkwUVROQq3p8dzDVC+IQMX4eCJa7tzAAAABA2fOGN9R4YRwixsf3v7/OvW0BkhCSI2KcVSij0Gn5fQNm3dODZvuCQbN//XBiHOReXv6CCaJYAbkqqm2iAs9QBYoKvF3tNt1uQK77w11PrqoyOERjNYef6x60UdW5u2yUCt1tFt/pB6xSAa3d9toN2bOZT0Cu82ajlt363G7bnW0sdLs1/v71o/M1bk99lmlccxv9HAunuQG5rqW7fK7aAbf9e92i29KvXdiy3dV+ScENyLOpsddD9IKFO71YAbmq70Oignip75sd/6pCPpxmB+TL74/+ftnLLrmr8GvhSkBeYrqDXV4Ih4jxdH/wqHsLAwAAAJQ9n/50gxfIIWJ8PP74Zve2BUiDkLx46gFtMSuPEMvZFQ8OmFWP9CcqFjX297qnB8zG5wbNphcGE2Plqs2uAr1dS0dbCitsUgvf7pbA9P+lFTRAHChWQO4GplGVsKFu6+sQVTOH87gBea7V1wqr67cMJ0JdBctS40iH2CGkXT2teC1blbOt7nsbVUBn0g5Gdy3J/XeSfAJyN6gMP7dR63B330LtNuxhu3SFySGte/xgWR0ubOxrl7bvvX64nEl1AVBFt35O6prpWtldCXRdw3nVIj5EAXama5dLQK4XJXR+9KKAtqlr5ramd5cpVkBuv8Sg1vzucqH2/uiYws9zCcjtbRdzHHL3ezdRVE1A3mZWeSEcIsbVW9xbGAAAAKDsOfPMA14gh4jx8bLLOtzbFsCDkHz8KqjQg2WNDRrVihSxmnx1yeSEAgCloFgBubTHrNaQAO70UHVJUGW1XV0tMgXkCknddbjOv7E/bVzoTNhh8+4VuYfQtgqVC8EdPzqb+QTkWm+Izqk+04sChaBwWsvb4Wd/t799vQxko3blUfuuYNdd1lXBbi5dM5p2pALuuo2pa931l32OcqyAXBXzuUSr7nLFCsjtbdtj3Lva7eQV5Ief5xKQa4z0kA3PZg7h8zU2AXml0hwsiAjhEDGuDpke9zYGAAAAKGvuuafLC+QQMT7Onm2VXQBkgZC8cFUla1cuadzVbOPAIlaye6xADaASKGZArurbEHVMcKdHaVcIZwrIFby7y9nOvS69ElcoOOyoD8yBfcOJgDnEDpubdlohaw5BbtRyQseQi+o04a4rk/kE5HaLdFXn6zO1uLdx9yWTCp61vMaytlFXDHub9u8F7vWx9z2sSM+kWrO7EacCXb3soHb49vjxdkCuaxui8Nhdb2i2gNxuIy90/DouVczbrd2Fu95iBeQ2UWPEh6p6PkRjuoef5xKQ2/clAXkZ0WzmeQEcIsbXQdPp3sYAAAAAZc2WLYNeIIeI8bHTeuADMBaE5Pm78fkBM9Tv32d6GL94GiE5Vpf2OMYAlUIxA3KF4iEKGxVcu/O4ar6QQgNyux242PZSeghot1K3w2b7nlYo6643k4Uul4+5BuQLbk6vFNcLAfpcYalNphbk2exsSv/3X23r1UnGrkgW9pjYMp+A3H6xQWG4O057/ebUtbUDcvu7lm0bmQJytwJeYbnbxt/GXW+xAvK073+WCnL7eMNrLAnICcgRMSYSkAMAAEAl8g//sN8L5RBx8v34x+vd2xVgTGrWDiWqotyHfOi78+XsDz7V0nTZvYTkWB3Wrk8P4AAqhWIG5FutcaGFwlR3HtdiBOT2OnYu9l+GyxSQKywM0Trc5TKpSvBClsvHXANyt5o9DF/dMeGXTc//32utQ11jsmGPhx2aa0C+wgnxl97j72OmgFwt/EOynZ9MAbndjr+9Pnp5G3eaHZDrxQF3umumgNzubrB9Qebw2g657eELCMgJyBExJhKQAwAAQCVy3HHNXjCHiJPvWWcdcG9XgJzQw1q3QglTzr66z+xfl1ulbF9HYFY+5D/QRqwUZ1+V3toWoNIoZkAu7cBPrHsq+/rHG5DPuyG9gtqtApaZAvKFt6Yv+2pEuB6lxjsvZLl8zCUg3+WMha624/Z0Ozx1p+WiOgA0bI3++aeX5HSN3GVkrgG52raHDPZFX+NMAfmmWenh7OrHor9nmQJybS9EQa+7nLRxp9nnXgG0O901U0Cu8xNit063Vccem00zU/tbtQF5NUBAjlheEpADAABAJXLddR1eMIeIk++jj3a7tytAXuxYWPwH2uXuotv6E2N55oMezmZrC4pYrs65ti8RyABUMsUOyO0wOqRuk19JrurkfWvTA95CAnK3UnqjFR7Kl27qN/3dqTxNbbzt6fZY2grr7X0IVSDe/OqwWXBLKhBW1XByuZH/uephf7m5Iz9DdOwK4t1pY5kpINdLO2v+PJDWcjtk0e3p23ED9J0vR//eo6r7qBcZFIILnZddS4fMygcHEudC07K1bM81IF8zI/27opcd7Ok6p/YLFBqTPJymn8/2NAXQUUO/qDo8xA7Iezusz19N/37q2Fr3pp9f9xqufyY9HNb3zN22baaAXC9s2mi99nK63j1tqX0dGkhvl09AXsEQkCOWlwTkAAAAUImsWdPvBXOIOPk2NuZW4QqQjcbtQxkroKrNzbMGTW974c8c3Ye6iOXs/Cn+uMYAlUixA3KpMZJdFGlp7GoFuwqlFVS7FBKQS3tMbAWIqhpWhfH+9UOJZV00bne47MKp6dW5QuG32lgrFG7dM5zYd6F25uFyCortgFaoSnvvqiGze9lQ4udHOL2Q6m07ZBbah6hjEZrmjrseagfBQmGpzotCcbXAD8cA1/VQGGsvG6Lj6G4JEsva1y38XK3SM+17toBcIbeN1q9zt2XOYOTLSQqZ7XBYx+Ci79fe1UOJly/csdLtgFzHnjbt1WGzZfZgonW6u5xwx1l3uwjoGrSOfO9r1g2Z7tYgUR1vz58pIJf2SxpCLypumz9o9qwc8joyaB/tZQnIKxgCcsTykoAcAAAAKpX/9b8YhxwxTn7yk4w/XnmoI8BmY4IFI///+RGfnTD7Ol80G57d5T34qxZXPFhrml9d6p2XQtw8a7u3fsRyU1WiUQEfQCVSioBcutXLY6Eqbzu4zicgV+CYDQW5drisANReXi2r3bA7CsVy9nIaizzX5RQGu/udTTcgz4QCare62VZV5XY78Wy88kT6d8GuvB+L1Y+mls01IJd6oSAbdgAsGp1x7dtqc99HOyBX+/hMLxyE2KG2rqHdQUCqO0AmNHa7PW+2gFwvabhBeBSN2/1ODATkFQwBOWJ5SUAOAAAAlcr3v9/iBXSIOHn++tdt7m0KZUuHGQ3Er5p09656wbx0U4v3ALBSnX9jq9m9YrZ3Hsbrtpde9raFWC4qlGuvzxx6AFQapQrIpSqL1R46U4isgFLV2m4wK+3K7rECcqkW4VGBp6p5FbwvvSdV8e0G3VItsrUvmaK3tv3DkedKlcSqEI9C1eyqBg7bkufjzkURB2NGx+pWxbHGBs817FTVde3GVEW7jc6Z1hd1bMum949ev78cnubVywU6T2HleYjC9Kh9z6V6XpXSLtpXVXW/eGVfopo6RNfTXV7bi7r22ic7QLfHMJf6eW+HxyE6NrU+n311+ksCKx5IP0c6r3XWGOk2Okf2vPZLCu56wnUpAI+6RgrXM11rO3hfNt1fr7SPUS91uNMLlYC8xBCQI5aXBOQAAABQqdx3X7cX0CHi5DlvXo6lMBBz9o94s3ED1sm0v+tms3PxfLPg1kbvQWAlufH5Vaa79Xbv+IvlvjUzzZxrO7ztIsZZhXQ9B6rjuTtASFQwWgoVUqtSWy2iVUE75xp/nmKokFDjkC++0w+lFUIq+Fz9WPZjVnCqfdVY327VcDaX3DW6nCp5Fey60+OgroPCVp0DjZHuTs9HNyB1p+ej2rurCl3DtdidBEK1r2rBrxcd3Gmh86f0J+bRNc7n2PQyhr4zCq6jrpu2qWA5aprUtvTvh/Z9yd39GefLVb2soXXpfCikd6fHRff6TxQE5IgYSwnIAQAAoFJpbh72AjpEnBz/5/+scW9RKEv0UK10Ae14HeidYnYtm2sW3VbvPRAsZ5fft8s0bv+zd7ylsG3/fWb5/a96+4AYRzXWMEA1MlEBOZafeolh65zBtHG/bd1xuDPNh5UpAXmJISBHLC8JyAEAAKCS+cIXGrygDhEn3u99r8W9PaEsedm4gWocHRq43uxZ8aJZPG2/92CwnFz7+EZTv/kJ7/hK7fDgdWbzi8u9/UGMi6r207i0ANUKATlmUu3hhVrF71iQquxWpfzOl4fS2nurLbm7PFa2BOQlhoAcsbwkIAcAAIBK5pprOr2gDhEn3oce6nZvTyhL4ls9HuXw0DVm7+oXzJK793kPCOOqqt+3L1hkOhvv8o5noq155Tkz9/o2bx8RJ1O11HXH0QWoNgjIMcqVDw64X5WsbHw+eoxsrFwJyEsMATlieUlADgAAAJXMjh2DXlCHiBPrf/tv+0xPT3U8E6lsWo0boJaTza8+YrbMWWpevqPWe1gYB9c8ttnUbng6Eeq7+z6ZttdNNyse3OHtL+JEO/e6PrNvLS3VAQQBOUY57/o+U7d52IwVRQ6P/ChVUOouj5UvAXmJISBHLC8JyAEAAKDS+fSnabOOOJkef3yze1tCWbLDuOFpuXqg5n6zbf5is+SuGu/B4US6+M4as23e4kQI7e5jnAyGr0m8XODuP+JEufKhgZH7pDqerQPkAgE5ZnPutX1mx6JB0/zqsOlpC8xgnzG97cHI7z/DI7//ZB6fHCvfSQ3IbSsVAnLE8pKAHAAAACqdq6/u8AI7RJw4H3yQ9uqVwUbjBqeVYFfLNLNr6Vyz/L5d3kPEYrrg5ibzyhMbzKtL5pmmnY+avs5bvH2Ju/vXP2PmTTngHRtiKVWYAwDpEJAjYiESkJcYAvLyd8fAFDN/28UJl9f+yZuOlSUBOQAAAFQ6e/bQZh1xsnzjG2vMEB1xK4R1xg1MK83hoWtNz4HbzIF9D5i6TU+a3ctnm61zl5pXnlxvlt//qll4a6N58apu8+KVPWbONZ2J8bnn39hiFtzSlBg7fPG0/WbJ3XvNsnt3mxUP7ExUqTdsnWF626d62ypXOxruNisf3u49cEUstgtv7Tf1W4YNAPgQkCNiIRKQl5hiBuTX3nuyOeWcL5pvnfJp8/X//Lj50tc/ZL549CHmGyd+yvz4l0eaP039Tk4B7vztl5jTzvtyYtn3fOCt5tBPviuxLq1j9qbfevNn8riTDjOXTDnB+7zSnLXhQvOa17wm4ae/+L+96bm4vu1q86vLjjVHn/Ax8/5/frv54KEHm88d9U/mP0/9jHlgzn+ZV4dvTJt/+swzzNkXHZ3wsUXneutz/dkl/5GY95yLjzZbe6/3prtqfz562HtyWrd8Yf2F5tRzv2QOO+L95p3vPSjxndF38JeXHmPWtlzpzR/6xNJfmBN/8rkx1ffaXTaTOje6Dvr/7rRiSEAOAAAA1cBXv9rkBXeIWHpPOUXjVkNlUPkBOeauKuHnXtvhPXhFLIYbZw4k2gIDQDQE5IhYiATkJaaYAflXj/uICYPabH7z5MPMpq5rveXl+Vd8w5vfNZfgUUG65v2Hd/yd2TmUHu5WmuMNyHU+3/zWN3nn2faMC7+StowC43Carpm7Tludf3td2QLr0Mtu+25iXr1s4U5znfb06d7+2v6PN73eXH33973l5DX3nOTNn0l3WVdV8Ov828u8tOMSb77xSkAOAAAA1cD06d3GDe4QsfTOnt3n3o5QthCQY7qdjXeZdU+t8x6+Ihbq0nsGTMNWqsYBxoKAHBELkYC8xExGQC5V4avW4PbyNz18ijefqoHdz3IJWH/0i39Pzv/IS+d40yvJ8QTkCnXd86uXChQq25/d9exP0pYrdUB+yMf+MTn/xo5rvOmhqjB399/d99AZi3/uLV+sgHxF3WWJ82bPr+4FpXg5g4AcAAAAqoGhocD87d/WGDe8Q8TS+U//VOfeilDWEJBjtLUbnzYvT9vvPYRFzMftCwbN8OQ8twcoOwjIEbEQCchLTKkC8rN++zXz4sbfmOfXnm/un32WOfd3X/cCxCvvPDG5rFp421XMRx5zqFnddEVi2o7BKYmKcIWyx37vU952XTd3X5cWkqpNuDtPJTmegPyY73wyuaxeRlCr8nDasv2XmguvPi7Rbn1bX3pb9FIG5E8tPy9tfrXud+cJveGBHyTn++yRH0x837Q9dSi4+7mfpn2n1DLeXd4OyPVSxcbOayPN1PFAarpe+LD3Wdt25yuWBOQAAABQLZxxRqtxAzxELJ2XXtru3oZQ1hCQY2YHeqeYbfMWew9iEcdy9aMD5sA+qsYB8oGAHBELkYC8xJQqIFdw6U5XMKrxrcN5NMZ4OG3O5tGW6KGvtF7lLZ+rdmgaqhDTna9SHE9AbgfI9714ljc9k6UMyL972uFp8yv4duexvW/Wmeaob3w48hqf+ZuvJtejlybc6XZArnnd6WOpFzv0Moe9v1Hf/WJKQA4AAADVwsqVA8YN8BCxdO7fP+TehlDWEJDj2LbufcCsemSr90AW0XXelD6zZwX/TgAUAgE5IhYiAXmJmciAXP7h5v9MzqOK5fBzjYMdfv6eD7zVWy4fP3n4+5LrGmt/8lXV7PO3X5IY9/rmR35oHl14bmQwa7uq4XKzsv6ytHbb+kzHrErjRbt+n3Mrbs2nQFzbfnj+OWZpzaUFB+Tab/scqWLcnSeTpQrI17dd7V07+fLu33vz5qLa69vrcdu1jzcgd8c//9kl/+HNU2wJyAEAAKCa+MIXGowb4iFi8f3ud5vd2w/KHgJyzN29q2aZl25q9h7MIsr1zwyarpbKfT4OUGoIyBGxEAnIS8xEB+T2OON2Re8zq36V/DwqyMxVtXUP16GgPfzfY1Uhj+XiPX9IC4VdVUUcFeKqNXc4z7SnTk9Uytv7FfrRw95jFuz8nbd8qIJ5ta2PGl/bbu+dT0Au7fXEoYL8T1O/k5zPPk+/vPQYb95cVBv/cB1q8e9OjwrIdc02tF/tzeuq47LHSteLGTsGpnjzFVsCcgAAAKgm7r+/27hBHiIW33nz+tzbD8oeAnLMz56228zGmau8h7NYvb58R7+p3UjVOMB4ISBHxEIkIC8xEx2Qn33R0cl5Djvi/cnP1x24Kvm5/ObJhyVCYXf5sdQ40uE67nr2J4kq9fC/FXK78+fq147/WNr+RanwOhw3PdSu0lbga7c0d9W0qLGu1W5e7ejd+aPMNyD/xGfem1xW7e91Hdx5oixVQK7xzsP5nltzfvJ/6zqqnbk7/1h+65RPJ9cRNX69HZAr7LbPswL1r//nxxMV/u5ycuqMH6Ud13i+X/lIQA4AANE0jLhmxPkjvoCT5swR5464csQaA8XhPe+pNW6Yh4jF8zOf0b8hUHkQkGNhNu54zKx9fKP3kBarx4VT+83OxUNmoLdyn4kDTCQE5IhYiATkJWYiA/IX1l2QnC4vuOr/pk23w0ypqupHF/zMW08mN3dfl6yw1v/f1nd92hjUv7rsWG+ZXJ2x+OfJ9Zx81hHm0lu/nTjGH/7sS2n7rGn2cm4bc6nxsrWs2rOrJbc97ZIbTvC2ffQJ6eG8xui+9c8/Mg/NOztRVW5Pyzcgv3Z6KiCWCun12ViV0HZA/qWvf8j88ZZvZ9Ruqy8zBeRPLvtlch5V5OszfQfCz3QN3GWyqYp+e7s6Z+48dkCeSX2X1ArfXdauHtfLDzoPCtU1v6rJdY5KEZoTkAMAQDqbR5xu3AebGBdvG3GVgfFxxRUdxg30ELF43ntvt3vbQUVAQI7js3Xvg2b9s2u9h7VYuS6+s9/sXjFkBvsq91k4wGRAQI6IhUhAXmJKFZB/48RPJdpbK4BUhbE9TSpIdKulFZzaFcShCn3vnz12+2+FzuEy3z/j84nPnlp+XvIzhZiFVCGHKtCPCjxvfvTU5DbstvHSDcijqq1//of/k5z+uaP+KW2aO4Z2VMhrtxHPNyBXdbeq9e1tSFVsa72ZgvJs7ebHMlNAruA/nEet+PXZhVcfl/zsxJ98zlsmm/YLF/peRY3zbgfkunZ6eeG4kw7z2uC71f16GcM9rii1zvBYiiUBOQAApFC1uP8wE+Po0wYKp6srMG98Y41xQz1EHL/vf3+te8tBxUBAjsWxvf4es3nWcjP76k7vwS1Whsvv6zc1rwwZU7mPwAEmFQJyRCzE2ATklRqUlyogz6bC8ZmvXOAtL9c0X2G+d3oqKLXV+pfs+6O3TKiqdsN5VZ2tzxSI223NH1/yC2+58apt6JjCbdgBsB2QR42BLedvuzg5j4JZe5o9vriq1d1l5awNFybnyTcglwrBf3PNN5PrsFWwHHXOih2Quy32wzDaPjcKmxVMu8tG+fzaVHt2Oe3p07155GOLzk1M10sCdgCuc2J3H5B2db/d/t1W1yvqJY95Wy/ytl2oBOQAADCKqpL9B5gYZ9V6HQrl179uM26wh4jj94Yb+PuiciEgx+La3XKH2Tb/ZTN/Sqv3ABfL01WPDJj6zcMGAEoLATkiFiIBeYmZ6IBcVcDuON1RKuA85juf9JZXyLxs/6Xe/HZIrEDcrhY+9dxUG/SwsrxQFYZrbHONpa790xjeqji291HhaTh/LgG5W42c6fNVDZd7y8rxBuShy2v/ZH7y66PSthmqSnZ7Xjsg1wsNao+eSQXs9rqiAnK1rA+nK6y2p9mB882P/NBb1lXhtv1igca6z9Y5wO1kEKrvkL1tdUUIp9ndCqS+B0v2pl7eUPAetvuXGtvcXX+hEpADAIAxeoh1o3EfWmI52GSgMOrqhsxf/dU+44Z7iFi4Bx9M9XhlQ0COpbGv8xbz6uL5ZuHUBu9BLpaHax8fME07CcYBJoqdjSvNro7FiIh5+erere6PkwmBgLwA7YBc1bcPzz8nMXaz2nWHn3/t+I95y2VT45ar7bgdRmo77nx2CP7T849Km6Zq8nCaQsstPblVIbvqeOzgNZP2WNm5BOTSXj78zB6zPduyxQrIQxXEn3TmEWn7FI7pHs5jB+RRbeNtFTTb64oKyO0gevrMM9Km/eKPqRb0uQTN51/5f9O2N2fzb715clXj1ofr0bVPbmPkmO1tzN7kb+Oy27+bNs/2/hu8eQqRgBwAAIzZaNwHlVguLjBQOD/72QHjBnyIWLhXXtnh3mZQURCQT4SdnX8027f/KmFb2x+86XF1585fJ/Z5377feNNydaj/erNn5Syz5K59XgCL8XTDc4OmdR/BOMBEo4B8XzAfETEvCchLTKkCclXYhp/fN+vM5OfyjidP85bNpqp/1V7cXseKusuS01UBbFfrqvrcXl4Vxfb0Wx471dvGWKpq3N6+1qeK4v+66GuJqni7jXuxAvKpM36U/ExV0O4yocUOyEM13rm9X9qfcFoxA/InlqYqzHVe3SD5hfWp45NLay71thGqVub2vD+75D+8efLRrhTXNQ4/t8cu1wsg7nJS30t7X4rVZp2AHADg/2fvTMClqM68nziZMfkmPpP5Mpox6he3EEWDiQ5GRRIkQSSEMEhARFAEo0gARVRwYZFFNpe4IAgoUdwiuIAIGgRFRUGFiMiiiOyrl32He3m/fguq7qlzuu/t27e36v79nuf3JNY5p6q6ulr79r/ec0DkDbF/oMSo+KxA6qxdSxU5YrrU6vEC/IkDQqQ3IH/mmdbSrduvpUOH86VVq19IkyY1pXHjM6Vt2/Pk9tsvkVGjWsj69X2ccYXu44+XL1k3cGAjp70i163rLT16XCKdOl3kXcdmzc72rqn+7403XiT33NNQZs7sJKWlQ52x1XHXrnuDcz7xxP9w2pN1+vSO0rlzHZkw4WrZ+OXLsuD1T2XGgzucUBZz65xx+2X57FLZvZl/6QPkCgJyRExFAvIMk42AXNUw2QwaP99+vzO+IrW/GTaaU34/9Oy1oTYNrG3NgPy3TX7u7L8iF+54IDT+f9uc762VbvYxX3u6AnKtpPa3/bTm8c4Y30wF5KpOHe7vu3v/JsH2dAbkV15/cdCm19l+71Rz/N33N3eO4R/HXIde13P/Ym951XsqPvh0eRBuVpCbD3388oJTnHG+5oMTz77V1WlPRQJyAAAQeU7sHygxKj4sUD169GAtcsR0+Ne/8ndF4ZPegLx581pi/m2eyHbtasvu3YOc8YVqdQLy+fPLZzysyOOO+75Mm3aDMz5V0xGQb93aP3SOixff7m3X6ddXzXtT5v79Syeoxez53qj98sWMg7KVanGAvGDjoXlO8IWIWJlbZan9r5OsQECeghUF5FrxbYbMGrDa4ytTg0h//PC/dwi2myFusup62/b+E2lWC2tIalc4q5kIyN/5sm9ou1bC2+PUTAbkne++LNi3uX57ugLyz7beF2pLxkQPC/Qf3irUz143PRXN6d0btyxfHsC85hrE2+NUnfnAPB+dMt/uk4oE5AAAIDJG7B8pMUqWCqTOli1lcswxa8QO+xAxeX/6U9YeLw5yE5CrtWufJAcPprfqOV/NRkDuO3Hitc4+UjEdAbnOFmCe24IFtzp9tm94Spa++5588MRaJ8DF9Pv2Q/tlweQDsvGLMpHC+wkbINIQkCNiKhKQZ5hsBeTq4FHhNZknzrnd6ZNIDaXNalyd8ly329Nv12t0lrdOdTzNgL73g39yjpHIrr1/H4zr3q+8ito0EwG5vmZzu14/e5yayYBcQ2F/3x17XBpsT1dAfu/IK4Pt+v7Y75mpuY/XPukZOsb7y8NPLmtVun0eVVXPW8N4f5+d7ihf2958X9VPNpRP+e+rU/2bfRbv/qvTJxUJyAEAQGS02D9AYpQ8KFA97r13u9iBHyIm79ixu+2PFRQkmQvIe/duIIsW3eYFvDrNdv/+l3lBq/k38NixVzj7KETTFZAfc8zRMm9eN1mypId8+GEXefHFttKixTmha3rqqT+U/fuHOPupqukIyNXHHrtcatU6Xnr1auC02W76aoIsnDpP3n5omxPsYvWcN+GArP5nqezfVXi/WwMUCjsPrUNETMlcQECegpUF5Bo4mtXeZ9Q6IVQV/cRrN8qfu//WWWNa+5iBrKrTnmubuTa5Tq9tH9P01gHl1cB6bLs9kQMeK69M/nXDM512XVPdPLcnJt0YtFUnIFev6HBRsF0fELCDYXXUKzcEfaoakH+4eqA0bV1bJs9196tV+uZ5PTf9pqAtXQG5vg/+9m59GztjTfW1+X3NGQi0UlvfF79Ng3Z7GvdE6tT9Z597UvDAhemdwy4Pnbf9QId577W5sa73Ov22L/c9FAr1zenZqysBOQAAEJBHXQLydHDaaevFDv0QsXLr1Nlof5ygYMlcQP78822c9i1b+kvNmj8K+uha2nafQjRdAbmG33a7+sQTLYM+6pw5XZ0+VTVdAXkq7t89XFZ/OlXmjf9CprNeecrOGXdAvv6wVHZuYgp1AAAASC8E5ClYWUCuvjH/rtAXew0h/baLG5wRbNf/f8PtDbzAXKewNsfodu2/aNeDoarwQY+3do5nalZaq/FC4XhqKG2Ou/6233mB6t+m/MUJ7tUuvRoFY6sbkOvDAvb+r+pY16smf+zF67xpz822qgbk5hTiGuLq/nRadTOMVnV6e3Nq+XQE5K/Ovi20fdrCXs5YU7vaXENo3X7/364O7UfV15JI833v+1CLYMwF9X4qN/dp7M0SYL9+c3p13/e+7hfqo2Puebilt0a6Pe3/+HdvccanKgE5AAAQkEddAvJ08Le/7RI7+EPEyn3jjb32xwkKluwG5OqIEc2DPokCX3XDhj7emtqTJ3eQr766Q8rKhjl9fHfuHCgbN/b1LC2NP227Tufu99Hw12zbtOnwdvMYuu3NN6+XqVOvkxUr7qrw+Kb79g2W2bO7yvjxV3tB9bZtAzIekB86NMyrLq/s2mu/ZcvukEmT2ntV/ToFut3HN15Arq9l5sxO3njdT0XXxL+mvvpwhNnuvx+bN/cLtvnn9+qr13rH0X0c3P+QlHz9onz1/rvemuUE5on96JkD8uXbB73p0/fuKLzfpwEAACB/ICBPwWQCcvXGnpcG/dR3l/XzKpnNbYls0LRWUHX+4Lh2oba5G4c4x7I1w3YN3+32RGoobZ+LqVnBrPrTrFc3IFc1CLePl8iqBuT/79T/cvZhq33mrA1X9acjIG/15zrBtmQq+u2HBbRyX8/LfEgiGZ+fcXOwT/OhjETquekU7vb5qMOebOv0t63KfZaMBOQAAEBAHnUJyNPFb3+7SezwDxETe9VVm+2PERQ02Q/IdVpwv4+Gunb7a6+1d6Zi973jjvpxpw9v2bJ8mvFZszo77aqG3cHf4H/+VbB99+5BwXY9tk5fXqPGsc6xL7jgJ/L113c6+/XVANie7tzX3F8mAnLVPMaYMS1DbfrQgB7XDNF9jzvu+3HfKzMgV1u1Kv89z1f317fvpc5a8jt2uL/f6XHMPvrwg9+mD0NoKB7v/Dp0OD/0QMOhsvtl88rnZdn7M4s+MJ/99AH58p2DsmlpmexnVQwAAADIIgTkKWiuV63Tc9vtvhoaa1js923S6jz5Yu9DMmRMG6da3Fe3P/7y9d502v5+dL1xv12ns7aPE0+dxtsfo1OW2+2J1PPTynD7vHSNap0aXvto5bG/XauadZtWufvbKgrIzZDXblPfWtTbqWr2j3/PI+XTbek1scdW5NNvdE4YEus5aYV/vLWztYre76cV03a7qb5n5n4/23qfs776XfeVzyRQkTqNvj+m+TUXhKa/T9YXZ3YL9qfvq65Hb65v76vbtKLcr1RPpE69rtO02+P1+lX0OUhVAnIAACAgj7oE5Oli1qz9YgeAiBjfo45aLcuW8e+f4iL7AbkGqn6fevVOC7Zr9XD37uEZ8OJZu/ZJTuWzGZC//35n55iqVoL7fcyA3AyCNWTWINc+pq+2aaBu73vhwtu88NruH89MBORmyK9q9bXfpsF9gwY1nPOwbdeudqj63g7IK7JOnZNl3brewdhkAnLzgQV9+MDub9q06VnOazbdtnacLJ8zXeZNWCwz/rrdCZILxQ/H7pcvZhyUTV+VyQEm+gAAAIAcQkCeIzVM1apgnX5bw9tJH/dIej3pbKiBt56TThW/ZI8bHOu56pTsC7bd77SlQ62e17Bcj5/OY+h5T/30TnnmH11k/HvdvWpt82GEYlCvgb63OgW7rk1ut1emf288+1ZXb/r1TF0/AnIAACAgj7oEVOmka9etYgeBiOh6773b7Y8PFDzZDcgXLLg1aFfvv79J0GZWlqudOl3khd3z5nWTxx67PNSmVcXmftMVkPs2a3a2d/66r379GobaHnmkWWi/Gk7bFe86Riukp0y5Tlq3/mWoLd0BuYba+nr8PlqFrVPO++2dO5fPzKc+8MAfvWuqlfa3335JqG3cuCuDcfZ10WNrZbqOGzv2Cu/hBrNdq+f9sVpRPnp0C3n00WZBe0UBuW/Xrhd71+ytt26QNm3OC7XpOduvPZF7d4yUzStekFXz3pQlb82RuS9+Ie+N3OQEzvno2w8dXjt8weQDsuyDg7JhSZns2HhIyvhqCAAAAHkEATki5qUE5AAAQEAedfkVNJ3s2nVITjxxndhhICKWe955G+yPDhQFmQvI27Y9zwtSn376Shk27A+hNlVDZb8ae8+ecMgcL0TWgNQcr2G735bOgFzP1R6r5+O3N2z4s1DbgAGXhV7T55+Xn5eqlfHt259f4WurSDMg1/Bb13B/7rmrvP/VKeftcH7kyObBWPuBBLOy3NcMsXVf+l7odvO66HHtynldf3zo0D+E9q8PBZh9dD12v62igFz3r2ui2+dWv375DIFDhjR22qvqobIHZOc3T8rGL16R5bO3yOevH/DW7dZQ2g6qM+lb9++TD57cL/NfPSBL3z0o6z4vk61ryuTAnsL7TRkAAAAKEwJyRMxLCcgBAICAPOoSkKebZ57ZLXYgiIjlTpvGfL3FSeYC8orUIPazz7oH41566ZqgTYPUvXsHO/tWzSC8V68GcbdXJyDX87LHqUuX9gz66DTs/vaSkn6h1zVx4rXOWPXxx/8U9KlOQF6ZOkW9Btf+WK3I9tvMCm9TXdPdnFbeD7mTuS6qOX27Vt6bbckG5PaMAL76gIXfRyvh7fbquUZMykpF9u8+JLu3HpLtG8pky6oy2bS0VNYvLJPV/yyV5bNLvTB78bSDsuD1A/Lpywfkkxf2y9zxB+SzSQdl0ZsH5cu3D8qyWQdl5SelsvazUtn4ZZlsXlEm29cdkl2bD8m+nYek9EDh/W4MAAAAxQcBOSLmpQTkAABAQB51CcgzQatWJWKHgoi4Sm66aav9cYGiIfsBuU6drsGyOW7QoN8H7Trtt71fX5323O/XqtUvgu2ZDsi1qtp8Df72GTM6Bttq1Treqxa3x6qZDsg1fI5XgW2G15Mnd3DafTt2vDDop+eq25K5Lqp5Dewp4KsbkOtU636fytYhr7rhgBwAAAAAkoeAHBHzUgJyAAAgII+6BOSZYM2aUvnBD9aIHQ4iFrM/+9k6KS21Py1QPGQuINcKb53SW4NpDU797fEqmdu1qx2069Thdruv7s/vd+65JwTbMx2Qq34f1d+m5xpvn7bpCsh1KvLZs7t6Vd733BNeGz3eGt1mZbg5Jb1t//7l08T36HH4AYVkr8vatb1D5+FP0a5WNyCfO7d8Wv3Gjc902qsnATkAAABAqhCQI2JeSkAOAAAE5FGXgDxTjB27S+yAELGYnTKFqdWLm8wF5Frt7W/XQNcMUSdNah8a16RJzaBt3Lgrnf36fvrpLUE/M3DNVUDerduvg20aMttjfNMVkJsV2jqVet26pwRttWufJAcPDg2NNc955cq7nX37muuQX3PN/3jbkr0uBw4MCR3HnB2gugG5ue48ATkAAABA/kBAjoh5KQE5AAAQkEddAvJMcvXVm8UOCRGL0dtu22Z/PKDoyE5ArrZte17QpmHpjh0DgzYNrP22xx673NmvrxmqXnDBT4LtuQrI7777d8G2m2+u64zxzURAri5ceFvovB55pFmoXV+P32au+W5rvg5/bfdkr4tZQa4V7mYbATkAAABAYUJAjoh5KQE5AAAQkEddAvJMsm1bmZxyyjqxw0LEYvJXv9pgfzSgKMleQL5hQx8vQPXbtfrabxs8uHGwvWfP+s5+fTU89/vptOz+djMgj7cWt5qJgHzs2CuCbY0aneGM8c1UQK5qoG2em1kp3rDhz4LtU6Zc54z11Wnv/X76mnRbstflww+7BP20it1sIyAHAAAAKEwIyBExLyUgBwAAAvL7ZN263rJ0aU9PnYbUbs9vCcgzjU4rbQeGiMXkJ5/stz8WUJRkLyBXR49uEbSrH310k7f95ZfbBds0jLWnClcPHRomtWodH/QbNOj3QVuXLhcH2/2A19ZcsztdAfl77/0ltF0ruu1xaiYD8t27B4XWeNfp6v02rWr3t/tTp9uuX98n9BpmzersbU/2umi47fez12EnIAcAAAAoTAjIETEvJSAHAIBMBuS61qROX/rgg029iq0aNY6VmjV/JPXrn+5Vg7300jWyf/8QZ1y21alX/R9Vv/76Tqc9vyUgzwZ9+mwTOzRELAYfe4y/F8AnuwG5PrBWp87JQR8NvDUM1yDVnA7cnipcNUNmVaf29tsefvh/g+26f/vBuMmTO4TGpisg1+87Zjitx9bA2R57yy2/CfqkOyBXzbBZnTDham/74sW3h7b7DyT46rU3p74/99wTgmtnXhet/N+6tb9zXK1KN/evxzPbCcgBAAAAChMCckTMSwnIAQAgUwG5To9at+4poR9D49mgQQ1nbLYlIIdkaNLkG7HDQ8RCtkOHzfbHAIqa7Abkqq6FbX5nuO++Jt527W9uv/76C+TVV6/1wu3OneuE2vr1axja54IFt4ba9XuI7m/48Mu9B/jMNjVdAbk6ceK1oTYNk3VN72eeaS1PPdXKq+g22zMRkKutWv0i6KdhtB9od+x4Yej4AwZc5oXTen3MKdjVd965MdifeV38ferreuWVdt4DDM2anR1qj7cGOwE5AAAAQGFCQI6IeSkBOQAAZCIg/+STm70fN80fQxOpa4na47MtATkkw4YNpfKTn7AeORaHtWtvKMjfLKA6ZD8gV3WdcfN7g/53WiuX7e3xbNPmPG9acXufdohua07Pns6AXL399kuc4yUyUwG5Li1jrvGu10O3b97cz1sf3T4PW/9BBV87IK/I1q1/KTt2DHTOiYAcAAAAoDAhIEfEvJSAPF/YFXNhzJkxX485CbFAnRLz/ZhfCqFePpHegHzNml7Oj6G6lufs2V296UX1B9BVq+6WJ5+8QmrXPik07WmuJCCHZJk+fZ/YQSJiofnv/75GFiw4YN/+UPR8Ju5/g1JXl17x/9v74ottnXZfDV/NKdW1+tlv0+BUp/q2v3foki6J1hdXdbrwBx74ozNOq8knTWov06bdEGzTqmp/nIbt/vaKAnIzfLbb1Ndea+8tOWMfX4NdM0AfOvQPztiKNKvj9RrY7aYjRjQPHfvzz2/1tuvDB/ff3yQ0HbyvTgs/Z05XZ19mQK5TqevrsMfqQwfjxl3pjPXV74h+Xzsgnz69Y9CmswXYY1VztgFzbfX0SEAOAAAAkCoE5IiYlxKQ5xoNxt8Q9w9wxGLwwZjvxCy870PRI70BuT09p/4IbPfJNwnIoSoMH75T7EARsZAcP36PfdsDSLoD8nSq4aoGpDqDTbyK8USWlg6V5cvvlFmzOsvOnW5Vc6bVYFmrvnU9bn2A0G7PtVrprWuRL1p0m/dQgd3ue+jQMHn33b8EIbu6Z88gr6pbX18+vraqSUAOAAAAkCoE5IiYlxKQ55INMUeK+8c3YrH5bEx+iM8t6QvI9QdUMxyvqHorGXUK0BkzOnqVZVrNtXFjX6dPRWoVlP7wPXXqdV5F0+rVvZw+aryAfPv2Ad6xdT1TfzpXe1w8td+yZXcEFWgrVtyV9NjUJCDPBbfcstUJFRELwcGDd9i3O8AR8jcgR8ysBOQAAAAAqUJAjoh5KQF5Lhkr7h/eiMXqywK5JH0Bebt2tcWcHlMruuw+lakVXDrtqTmdqqlO0fn++52dcabr1/fxpmC1x6o67WmvXg1k27YBQX8zINdpPOvXP90Zp8ddsqSHcyxfDcEffbRZaFpV0yFDGsuBA1W/HpVLQJ4rmjcvETtcRIyyHTtusW9zAAMCcixWCcgBAAAAUoWAHBHzUgLyXPGRuH90Ixa7SwVyRfoCcl3v0g+ENeS225PxsccuD/ZRke+8c6MzVh0//uqEIbVp//6XBWPMgLwy41Whb93aP26obqvrjW7e3M8ZXz0JyHPF/v2HYvfOBrFDRsQo2qTJN/YtDmBBQI7FKgE5AAAAQKoQkCNiXkpAniv+Ju4f3YjF7msCuSI9AbmuTWmGwXPmdHX6JKOud+kH3FoF/uCDTb0p1rUC2wy+taLbXg9T1740z+HUU38oI0Y09yrOdYr1AQMu8/ah23XdT3+cHZCfe+4JXjW4rkmq/2u2dehwvnPO119/QaiPnqtOz67ec0/DUJtW2dvjqycBeS5ZubI0dj+tEztsRIySv/rVRtmzp/B+n4B0Q0COxSoBOQAAAECqFE1Avungu/L1gdGIGBH3Hdxlf4wh4+g1t//gRkSR4QKZYpXhrCP+/Yj2+5C6uk63GQTr+uF2n2TVKvAPP+zibNf1vM1jfPZZ96BNpzivW/eUoK1hw595ld32PnQK91Wr7g5tMwPyli3Pkb17B4fa33zz+tBxS0vLg3mdkt3frtPKr1wZ3rc6f3730Pi5c7s5fVKXgDzXzJ17QH7wgzVih46IUfCnP10f+/cW/x6BZCAgx2KVgBwAAAAgVYomIF+ycLV88o8DiBgRd++lgjz76B/X9h/ciHjYPQJVoaLgO73hdzJqtbQZAmtgbfdJh+3bnx8c47XX2gfb7eMvX36nMzaRZkCuQb/drmrVud/HnGa9QYMawfZXX73WGefbo8clQb/Ro1s47alLsJUPTJ++T446yg0fEfPZ445bI/PnH7BvZ4AEEJBjsUpADgAAAJAqBOSImJcSkOcCXWfZ/oMbEQ+7RcDHDr9zF3wnq06pbgbU9vTnqThvXjcZPLixN615vXqnSbNmZ4eCap3+3O9rToVe1WnMkwnIGzc+M+gze3b59PHmtO9PPdXKq36PpzkN+80313X2n7oE5PnCxIl7vNARMQoec8wamTVrn30bA1QAATkWqwTkAAAAAKlCQI6IeSkBeS74Qtw/uBHxsCVS+NjBdzTC72TcsKGPmAG5Todu90lWDal1qnNzf/EcOvQPwZhOnS4Ktg8bVr49GZMJyFu0KD8fXZtct+k08vY5JWO8dcxTl4A8n3jxRUJyzH+PPnq1zJhBOA5VhYAci1UCcgAAAIBUKZqAfMXCUieAQ8T8df/ewvv3UP5DQI6Y2BKJNoUZfCfroUPDxAyBZ87s5PRJRp0aXdfyNvfVtOlZcscd9eW22+pJrVrHB9vNgFzXHPe3P/98G2e/FZlqQK7rpJvnqdXtyThiRHNn/6lLQJ5vPP/8brEDScR88d/+bbX84x977dsWIAkIyLFYJSAHAAAASBUCckTMSwnIcwEBOWJiSyQ/sau+iyv4ropmeK0V3XZ7Mppreuv+lizpEWo3p1I3A3JzbfK//rWps9+KTDUg175mQK4PCdjjMi8BeT7ywguE5Jh/fu97q2XaNMJxSBUCcixWCcgBAAAAUqVoAvKdWw4hYoQkIM8FBOSIiS2R7GIH34Tf1bVHj0vEDIxXrrzb6VORy5bdERq/enUvp0+igFynVfe3d+x4oTOuIlMNyMvKwlXzq1ZV7fWmRwLyfOWllwjJMX/8z/9cKzNnMq06VAcCcixWCcgBAAAAUqVoAnIAAKgMAnLExJZI+rDDb4LvbLhxY18xA+Nmzc6WffsGO/18P/30llCF+LRpNwRj69U7zemvJgrIJ0/uEDp2vHA9kakG5PbYbt1+7YzLvATk+czUqXvl//yfNWKHlYjZ9KST1slHH+23b0+AKkJAjsUqATkAAABAqhCQAwDAEQjIERNbIpVjB99m+G3vD3Nh794NxAyq69Y9RUpK+jn9Xnihjddes+aPZPfuQd62BQtuDcYdc8zRwXZfDdN1DW+/j65J7rft3z/E25ffpmuSf/PNPc5xV6y4S4YMaRzaVp2AfMKEq0Ovd9Kk9s5YdeLEa2Xu3G7O9upLQJ7vzJq1T37847Vih5aI2fDnP98Q+3cn/56AdEBAjsUqATkAAABAqhCQAwDAEQjIERP7ucQPvgm/o+SWLf2lRo1jxQyN1fr1T/emYG/b9rxQyK327FnfG6shtwbj/natQB8//mqZMaOjVy1utql16pws5rrf77/fOdSu/fv0udQL4595prV07lwnaPvwwy7BuOoE5GrLluVtqvYdM6alF4o/+GBT77Xrdl1T/eDBoc6+qyfBVxTQgLJWrfVih5eImfSSSzbJpk2l9u0IkCIE5FisEpADAAAApAoBOQAAHIGAHBEL3x07BoYC5Yps1OiM0Frlzz9/uLI8kRpmm0H5Aw/8MXTsUaNaOGPiqUG9P6a6AblWquuU8PYx4qnTytv7rp4E5FFhy5Yyadhwk9ghJmImbN16s30LAlQTAnIsVgnIAQAAAFKFgBwAAI5AQI6IxaFWdj/88P+GwmdTraYeN+7KUAW4r4bkdrX4iSf+hwwa9HspLR0qb755fbC9XbvazvilS3tK48ZnOsdUtbpd1zHfvn1A0F8r0f12M6w3bdXqF0GfOXO6Ou1lZcNk5Mjm3nnGO+b111/gTe9uj6u+BORR47rrNosdZiKm09tv32rfdgBpgIAci1UCcgAAAIBUISAHAIAjEJAjYvF54MAQmT+/u0ybdoMsXnx7UtOMa59Fi26Tjz66SbZtKw+zffftG+ztc/XqXk6br4bWWhGuU69raL5nT3hN80yp5zt7dldZuPA27zzt9vRKQB5F7r13hxNqIqbDkSN32bcbQJogIMdilYAcAAAAIFUIyAEA4AgE5IiImE4JyKPK+PG75Zhj1jgBJyb2e99bLqefvkjq1ftEGjWaI5df/oFcddV7ct1170iXLtPl9tv/IX37TK1Q7atja9VaIP/3/37lHCOq/r//t06mT99n32YAaYSAHItVAnIAAACAVHECcgAAKFYIyBExV/7dcNYRV8UcEacvRkcC8iizcOEBufDCjU7YWcxqaK0BtobZo0e/LFOmPCPz54+WzZsfFvf+r7579jwoS5eOlLfffkoGDZosf/zjbDn22KXOeeXSU09dJL/73cdy/fVvO4G/+uwz02TXzti/0w/pv9fnyeHvm2tjbotZKgDpYPnylbJs2ZuIRWdJyUb74wAAAAAASUJADgAARyAgR8R0myj49q2M0eLuE6MjAXkhcOONW5xQtFj81a/+6VV/P/PMi15Q7d7jufGrr0bKuHHjpVOnGXLOOZ85550Jzztvvtx881vy+OMvy7Rp42TZsnQ9wPRozL/FfDXmJzE3CEBV0YB8/Pj9iEUnATkAAABA6hCQAwDAEYorIF+58m5v3V9dA9hui5q6drG+FnXLlv5OO2JmtMPvqgTfyUJAHm0JyAuFJ5/cJd/97monNC00dYp0DcS1Mty9n/PXjRsf8UL8Dh3ekbNqfu68rlSsU2ee9OjxD5k06TkpKclMhXxiH5HDgfmcmCti7heAiiAgx2KVgBwAAAAgdQjIAQDgCOkNyJ95prV06/Zr6dDhfGnV6hfSpElNadz4TGnb9jy5/fZLZNSoFrJ+fR9nXLY85pij5Vvf+pZnaenQUFtZ2TB54omWcvPNdeWTT252xmbSAweGyPvvd5YHH2wqLVueIzVqHCs1a/5I6tc/3bueL710jezfPyQ05pVX2gWvpWvXi519IlZNO/jOVPidDATk0ZaAvJBYvPig/Pa3m5wgNerq9OCDB0+O/ff+CXHv4Wi6cOEoGTPmJbnyyvflX/91hfOaE6nTx48dO0HWrBnu7DO3apX5GzG/jFkmADbLl29xgkPEYrCkZLv9cQAAAACAJCEgBwCAI6Q3IG/evJb4oW1FtmtXW3bvHuSMz7QVBeTTp3cM2o477vty8GC4PVNu2NBH6tY9xblGtg0a1AiNy9eAXK8rFe35ZD4F38lCQB5tn5PDgRYUEv37bxc7WI2av/zlfBkw4HVZtGiUuPdtYalh94gRr0i9ep8410H98fFfeFOnR+cBgTExZ8RcKQA+X39d6gSHiMXgN9/w0BAAAABAqhCQAwDAEXITkKu1a5+UtRDat6KA3AyctZ/dngm1Ul3DePvaxHPw4MahsfkWkG/a1Ff6979MTjzxP6R799847ZgJ7fA734PvZCEgLww1KF8iUDh88ME+ufDCjWKHrfnsD37wlXToMFNef/1Zce/R4nDh56PkrrvekOOP/9KrFv/73/W/GW6/6Ph0zA9i7hIobjQgf/31A5gV98bcXGUnT95m7APTJQE5AAAAQOoQkAMAwBEyF5D37t1AFi26TebP7+5VZ/vhqRn6jh17hbOPTFpRQK5TmHfpcrGce+4J8sILbZyx6XbNml6ha6Hec09DmT27q3cu+/YNllWr7pYnn7zCe5hg7dreofH5FpC/+GLb4HwIyKurHXwXUvidDATkheW4mIsECocoVJPXrv2pPProq7JunU7Tbd+TWBiOFIJygGyh3z/tz2CyAgAAAADkDwTkAABwhMwF5M8/74bMOvW2rq3t99H1ye0+mbSigDzbdux4YXAu6muvtXf6VCQBeVQt5uA7WQjIC9OnYi4UKAzmz98f+2/4N6FQOh/89a/nyt/+NkHc+w8L15Eih2L/PT20UwAgUxCQAwAAAEBhQEAOAABHyG5Aro4Y0Tzoc+qpP3TafbWKWqvPX3rpGpk1q7Ns3NjX6VORq1f3kokTr5U337xeli7tGfvv3bC4AblO8677Nt25c6CzP3X9+j7y3nt/kfHjr/b+V9cPt/sko1bWm+F4KpX0lQXkWoHuv549exKv965To2ufROuG67WbNu0G7334+OObZMcO99roPkaOLH9f//znX4Wu565d9zpjfMvKhsmyZXfIpEntveOsWHGXt83u56tr1/v7PXBgSLD9yy97yoQJV8u77/7Fe5/scZm3oqpvqBoE5IXt2JgLBAqDsWN3yUknrQuF1Lnw0ks/KoCpw7FaHhpxOCiXfQIAmSDO5y4pAQAAAADyBwJyAAA4QvYDcrPSWANru10DWLu62lenaH/11WudMaYaktpTuat16pwc+mc/IJ869Tqnb9u254X2WVLST9q1q+308/db1SnZzX3pGuT6MIDdpzIrC8jNwHrQoN877ao+COD30Wtmti1YcKvUrXuK83rVFi3O8cJy7bd1a3+n3VYDc/vYGoI/+miz0EMLpkOGNA4F4L7duv066KOhvd5n9jruiV5valYUfBN+ZwYC8uLwyZifCkSfffsOSc+e28QOrbOhBuMTJ+p69/b9hcXr2JhLBADSjf1ZS1a+LwMAAABA/kBADgAAR8h+QN6376VBn3r1Tgu1acV4vHDbVgNsrQg3x2rgreue230TmWxArhXm9euf7vQxvfnmus7rrMgaNY4Nxj7wwB+d9mSsSkB+773xA2N9GMHvYwbkGkybU+HH8+WX23l9tfLcbrO1A3IN1Su7pqqew+bN/UJjzYA80UML6asgLxHIBQTkxeWYmPMEos+SJQflqqtKxA6xM+FPf7ow9t+5l8W9nxB934y5TQAgXdifsWQlIAcAAACA/IGAHAAAjpDdgFyrks0g8/77mwRtOiW4Gcrq9Os69bhOrz55cgcnDH3qqVahfZtTt6sNGtSQp5++0huvYbFdqewH5GvW9JJRo1pIly4XB21mQD53brfQuM6d68j06R29gLply3O8bTo1uP1aE6mBu7m/OXO6On2SMZMBuVZ2m+eoIb5OKT9u3JVy7rkneNu2bx/g9dXr+NZbN0jPnvWD/k2bnuVdE9/Fi28PHff66y8I7V+rxWfM6Oh5zz0NQ236vptjzYDct0ePS7yxgwc39sbbrzN1SwRyAQF5cToq5lyB6DNz5j5p1GiT2KF2OvzOd1bG/p3/D9m06RFx7yFE28djzhcASAepLmNBQA4AAAAA+YMXkAMAAGQyINeQWQNuDamHDftDqE3VQFbXk/bHmsGohttmm68G2X4fDbz9Kbi1itkMwDUw9QNWjQ46AACAAElEQVRwX3vdb7tdA1bz3P3tGgr72zW0tyvXNYDXcN8+10R+/fWdofNYt6630ycZMxmQmw8j3HjjRaExGvDPnNnJ2Zc5dX737r9x2n314QK/n06NvnLl3U4fnUnAvEb6kILfZgfkY8a0dManzxKBXEBAXtyOjPlxzDKBaDNlyl6pXz99QXnLlrPko490an77nkGszIkxvxEAqA6pBuS6PBEAAAAAQH5AQA4AAEfIXEBekRrGfvZZ92CcrsFtticKjTWcrl37pKCfX5l8552/DbZphbOub22PVc0QPdmA/M03rw+d29q18c8tWc3jqInOtTIzGZDffffvgu16vZN5ACDZgFwffvD7VbSevD7k4PcbPbpFsN0MyPXc7AcW0muJQC4gIEd1RMw5MUsFos3rr++VSy9NPSg/+eTFMnbsBHHvEcSqqA/fLBMASBUCcgAAAACIPgTkAABwhOwH5J06XSQlJeF1pT//vHzqdQ2xx4+/OqF16pwc9PXXwa5b95Rg28SJiUPXVALynTsHepXO5vlpGKyV1Pb+k1GnVDevR6r7yWRA/sknN4fOUR86+PDDLs5402QDcvM90Gny7ffX15yG3Vzj3QzIBw5s5Ow/vZYI5AICcjR9NOaHMQ8IRJu3394nf/pT1dYob9fuXVm+/DFx7wvEVJ0nAJAKGnTbn6dkJCAHAAAAgPyBgBwAAI6QuYC8V68G3lTcU6de501N7m9v0eIcZ5wGomYgm6w6/bmON0PXFSvucvbvm0pAbrf5aqCsU8jb+6nMDRv6hPZT0flWZCYDclXXBbdfsz6c8O67f3H2oyYTkOvMAPY+k7FDh/ODfZgBebx17tNriUAuICDHeD4c84OY+wSizeefH5QuXbbKd7+7WuxA3Jeqccys7woAVBUCcgAAAACIPgTkAABwhMwF5GZ4OW3aDaHAc9Kk9qFxdhirgXoyaqXzpk19Q2MrqshONSBXdUr4evVOCx1L1Wm+N27s6/RPpE4Jbo6Pt553MmY6IFd1CnTz4QZfre62r3MyAblWoZv7sd/PRI4Y0TzYhxmQv/TSNc4x0muJQC4gIMeK/GvM92PuEYg2O3cekoce2im/+MUGoWocs+9UAYCqkGpArlOzAwAAAADkBwTkAABwhOwE5KqGzn6bTlmu4azfppXgflvTpmc5+61InQLdDF0rCqurE5D7vvfeX0LroKsNG/7M6VeRtWodH4zVKeft9mTMRkCuahD+zDOtQ9PMq/pQg9kvmYD866/vDO0jlfXDCcgLn+XLZ8R8HSNqaakG2PZnKRM+GHNmzN0C0UenX+/QYYsMHz5J3PcaMVNOEABIFgJyAAAAAIg+3yorK7O3AQBAUZK9gFynFjcDag06/TZzzWutGLb3W5lmeFvRWtnpCMhVDY0HDLgs6K9u3hxeV70ie/S4JDR25cq7nT6VWZWAvG/fS512NZmA3HfLlv7SrNnZQX9dl9xsNwPyLl3c81HLysLV86tWVf11E5AXPlOnbpbx4/djRM1eQO57f8y3Y+4UiDLbY74s7vuLmGknCAAkwypxPz/JCgAAAACQH1BBDgAAR8heQK6OHt0iFJB+9NFN3na7Clyn9rbHVmT9+qcHY1u3/qXT7puugFzV6mdz+vEXXnBfbyK1yt18vRo879s32Onn++mnt8iSJT1C2157rX0wXl+/PWbChPJ13a+55n+cdvXtt28M+lQWkKtr1vQKnbf+c7zj6X1gj/W94IKfBP3MhySSlYC88CEgj7bZD8hNZ8jhoBWixcqYT4r7fiJmS525AAAqhoAcAAAAAKIPATkAABwhuwG5VhDXqXNy0EenGvfXstaqY3+7VoTbgbCqIfJjj13uVTOb280p2lX9Z3vs6tXhcLcqAfn99zfxwmRz2/79Q0KB+9ixVzjHrMjevRuEzqdu3VOkpMStQtfgXdtr1vyR7N49KNiuDxeY45cvvzM0bt68bqF2e+p57W+evxmQ67W55ZbfyNKlPUNj5s/vHtqn2f7xx+Xno/vdvn1AaKyvGaSr9nr0vhMnXitz53ZzthOQFz5Tp+5xQleMjrkNyH3firlFIArMj/mAuO8hYrZlTXKAiiEgBwAAAIDoQ0AOAABHyG5Arn72WThkve++Jt52rSLXkNZs0zBU9zN+/NUycGCjoGLbrjzWQFen/DbHNmp0hjz88P96U5H369cwFAaryQbk27YNCLbrWuOPP/4nGTOmpTRufGZof3aYXJka8teocWxoH6pWg+sU7HoOZoW62rNn/bjnperr69y5jhfca/vevYND11P3pRX8+vBAq1a/cI5rBuTTp5dfiw4dzvfG6Ptkrp2uDzHoAw/+GH3/zGus7foQwJNPXiHt258v06bdEPRt2fKc0LFbtDjHu6Yaij/4YNNgRgDzAQpfAvLCZ8qUA07oitExPwJy33/E3CzFyz45HGgsi7k45mcxP4n5Ycx5cvg7wOqYW2MeODImixxKdT1bxEz5hgBARdifmWQFAAAAAMgPvIDcFAAAipXsB+SqBr1mQPr114ern3Utcjskj6eGr34Q7Ltgwa1OoFyRyQbk+jrssbYaTNuvMRl1DXANh+39xVMDf3utcg3+7X5bt5ZX15vrgsfTrOY3A/KOHS90+trqvu3Xo9X9dj/fe+5pGPT75pt7pF6905w+8dTp5c1jEJAXPhqQT5qUKXfG3FZNd4u732JzT8wd4l6bbXkWkPtq6PWNFDb75XAQruH3xJijxL0OlflEzHdiLo95UDIK4TjmrZMFABJhf16SVR/WAgAAAADIPQTkAABwhPQG5GZlcLwA1XfXrntDQbhWNPttWomsIahd8a3Wrn2SFwprH3ufqobD7drVdsbqP48Y0Ty03ax+VmfO7BS06T787evX9/HCXQ3l7fPRbVpRblc5V0Vdy1wr3c21uU21iloruLWfPVaP+8gjzUKvywzI1SlTrnMeOtB96rTxOg26v00fLvDH6FTq119/gXMuqr4HZjW4/VqGD48fktsPEej1HzmyuXNuqlbW6/FXrLjLOcZtt9UL+lV1rfqqWyJQSKQjkNN9QDk6PbaGqvZ1yld1CuWNUjisjflBzOfFfa3V9WE5HLR/GnOvpBXCccx7dfYJAHCxPyvJSkAOAAAAAPkBATkAABwhvQF5ul27trfMmtXZqzC3K74rUoNaHaPVxxs29HHaU1H3qet461rbc+Z0lXXrejshe3U9cGCIF05rAL148e1JB+96bfRaaQV+onPS6/Dhh128wN9uS6Qef9Wqu733QM/LXvs9kbpWvF57XSddz6uy906ni589u6ssXHibN9Zuz50lAoVCugI5iI9O3T1W3OuVr74ec71Ek20x35fsPpgwUg5Xlm+Q6vO2uPtHzEf14RAACPN3cT8rycgDhgAAAACQHxCQAwDAEfI7IEfMrSUChYL93qYiP+5Wzucxnxb32uWrk2Kuk2hQIofD5UfEfR3ZVKvKv5bU0Ott7w8xX31IDs/SAADlEJADAAAAQLRxAnKCcgCAYoWAHDGxJQKFQDqqx/lht2osijlO3OuYr74ac43kJzvk8HTPD4h73rlUw+6qTJmbaqiCmEufi7lfAMAn1X+X8z0KAAAAAPIDAnIAADgCATliYksEok46wnH9MRhSY0nMZ8W9pvnqK1K10DfTfCnZnUo9FXVd98qmq081UEHMB1mPHKCcVL9XEZADAAAAQH5AQA4AAEcgIEdMbIlA1LHf01TMp8A0quh/a54X99rmqy/FXCG5o1QOr/ltn1c++0+Jj1bn230RoybrkQMcJtWAnIcNAQAAACA/ICAHAIAjEJAjJrZEIMqk+iOuKRVP6WWpRKuaeHzMVNfbTpVNEq2HCUxnSpg3jDbEKDs85lYBgFS/WxGQAwAAAEB+QEAOAABHICBHTGyJQFRJ9QdcU8LxzKGh84viXvN8Vc/1K8k8a2OOEvf4UVLXJt8m0auAR6zMaQIAOquO/dlIRgJyAAAAAMgPCMgBAOAIBOSIiS0RiCr2e5mKkHl0GvMJ4l77fPUFObwueCbQa2EfL6qOi7MNsRDM5dILAPlAqgG5CgAAAACQexIG5ITlAADFBgE5YmJLBKJIOqbwpno8u6yM+bK470O++lzMJZI+5ot7DETMP18SgOKGgBwAAAAAok1SATkhOQBAMUBAjpjYEoGowdTq0WZ1zFfFfU/y1WdiLpbqMUfc/SJi/rpAAIob+zORrAAAAAAAuYeAHAAAjkBAjpjYEoEoUZ2qJlPIPboWt65lbb83+erTMRdK1flU3H0hYn77t5j7BaB4sT8Tyarf0wAAAAAAcgsBOQAAHIGAHDGxJQJRgqnVC491MSeL+z7lqxqcJVtdqlO02+MRMRp+IADFi/15SFYCcgAAAADIPQTkAABwBAJyxMSWCEQFplYvbDbEnCLue5avPhnzM0mMBv/DxR2HiNFQP+P8XgLFSqoPJBKQAwAAAEDuISAHAIAjEJAjJrZEIAqkIxxXIf/ZFHOquO9dvjom5j/F5UVx+yJitFwsAMVJqgE5DyICAAAAQO5JOiAnLAcAKHQIyBETWyIQBez3LRX50TZalMR8U9z3MV8dHXOuHEb/125HxOj5qgAUJwTkAAAAABBdCMgBAOAIBOSIiS0RyHfSUT3OD7bRZUvMaeK+p/nqCJFDD8XZjojRdKMAFB+pfvfi+xYAAAAA5B4CcgAAOAIBOWJiSwTymVR/oDXVKiiIPttiThf3/UVEzKTvCkDxker3LwJyAAAAAMg9BOQAAHAEAnLExJYI5DP2+5WKqwQKiR0xZ4j7PiMiZsJRMQ8IQHGRakDOQ4kAAAAAkHsIyAEA4AgE5IiJLRHIV1L9cdaUSqbCZVfMmTEfEPd9R0RMp4sEoLhI9TsYATlAfFbI4Qc8n4v5eMxHEfNAvRf1ntRZuvQeBQAoHAjIAQDAY82a1bJ06TREjOOOHbq+MeQfqf4wa0o4XhzsjvlezAfFvQcQEdPhFAEoLnT2HftzkKwAUM4mOfzgiP05QcxHX4i5UQAACgECcgAA8NCAfPz4/YgYRwLyfMX+Yz0VobjYK4cfinhI3HsBEbE6jhCA4oKAHKD6rI/5sLifEcR8Vu/ZdQIAEHUIyAEAwIOAHDGxBOT5SDqqLKgeL172x/xADk8baN8XiIgpeugrASgeCMgBqs/T4n4+EKPgUwIAEHUIyAEAwGPNmm1OKIiIh92+fY/9kYGcwtTqkC4Oxpwd8zFx7xFExKr6DwEoLuzPQLICgMjn4n42EKPkZwIAEGVSCshtAQAg+qxeXeaEgoh42O3b+b6TP1SnWskUwKQs5kdyeIpk+15BREzWxwWguLA/A8mq3+cAip1XxP1sIEbJlwUAIMoQkAMAgIcG5FOmHEDEOBKQ5xNMrQ6Z5hM5HHLZ9w0iYjJuEIDiwb7/k5WAHEBkuLifDcQo+YgAAEQZAnIAAAAAiAhMrQ7ZZG7M0eLeQ4iIFXiI/85AMZHqg4t8TqDY2Sfu5wIxiu4VAICoQkAOAAAAABEgHeG4ClBVPo35hLj3EiJiPCcJQPFAQA6QGjvE/VwgRtFtAgAQVQjIAQAAACAC2H+IpyI/xkJ1+Czmk+LeV4iIpn8TgOKBgBwgNQjIsVAkIAeA6EJADgAAAAB5Tjqqx/khFtLF53I4ALPvMURE9f6YBwSgOEj1Oxrfy6DYISDHQpGAHACiCwE5AAAAAOQxqf7waqrVTQDpZmHMp8W93xAR1wtAcZDq9zS+m0GxQ0COhSIBOQBEFwJyAAAAAMhj7D/AU3GVAGSOxTGfFfe+Q8TiVR+gASgGCMgBUoOAHAtFAnIAiC4E5AAAAACQp6T6o6spU3hCtvgi5nPi3oOIWHy+LwDFgT6EaN//yUhADsUOATkWigTkABBdCMgBAAAAIA8hHIeosjTmC+Lej4hYPE4SOaTTrO8UgMIm1YBcBShmCMixUCQgB4DoQkAOAAAAAHmI/Yd3KgLkkikxHxT3vkTE4vJhkUNjYv/7vHjBubwdc1HMvQIQfQjIAVKDgBwLRQJyAIguBOQAAAAAkGfotJv2H95VlepxyAW7RA7F7r1DI8S9JxERbTU0nxNzrQBEF/u+TlaAYoaAHAtFAnIAiC4E5AAAAACQRzC1OkSVz2KOEvd+RERMRv33xxsxlwlAtLDv5WTV6nOAYoWAHAtFAnIAiC5pCcjjCQAAAABQNaozTacpQDYpifmauPchImKqToy5UgCigX3/JisBORQzBORYKBKQA0B0ISAHAAAAgDyBqdUhasyNOVzc+xARMR1OjrlGAPKbVL+/EZBDMUNAjoUiATkARBcCcgAAAADIA5haHaJEacx/iHsPIiJmQp16fYMA5CepBuR8b4NihoAcC0UCcgCILgTkAAAAAJBj0hGOqwDZYHPMF8W9/xARM+0nApB/EJADVB0CciwUCcgBILoQkAMAAABAjrH/yE5FfmSFbLAs5mhx7z9ExGz5pgDkF6k+6Mh3NyhmCMiLzX37BsvSpT09S0r6Oe3RlYAcAKILATkAAAAA5JBUf1Q15QdWyAZfiHvvISLmwucFIH9I9bsc39+gmMl8QP7557fKc89dJT171pdGjc6QGjWO9f73llt+Iy+80EZKS4c6YzBzvvnm9fKtb33Ls0OH8532ZNyypb8MGHCZ9O7dQNau7e2050YCcgCILgTkAAAAAJAjUv1B1VSn9QTINITjiJhvPhJzuwDknlS/z/EdDoqZzAXk27cPkPbtzw/C2ESee+4JMnt2V2c8ZsZ0BOR9+14a7KN161867bmRgBwAogsBOQAAAADkCPuP61RcJQCZZZG49x0iYr64TgByCwE5QNXJTEA+a1ZnOfHE/3DC8ETefffvnH1gZkxHQN6t26+DfehsAHZ7biQgB4DoQkAOAAAAADkg1R9TTZmaEzLNB+Led4iI+eY+Acgd+rCifU8mK0Cxkv6AfMGCW50AXCvJJ0/uIKtX95KDB4fKokW3ydChf5Bjjjnaa1+/vo+zH8yM6QjIly+/U5o1O1saNKghc+d2c9pzIwE5AEQXAnIAAAAAyDKE4xAFFop73yEi5qNjBCB3EJADVJ30BuSHDg2T+vVPD4Xj48Zd6fTz3bSpr0yZcp2zPQpq0G9vi4LpCMjzUwJyAIguBOQAAAAAkGXsP6pTESCTrBX3nkNEzGffFIDcYd+PyQpQrKQ3IH/xxbahcPy119o7fVJ1//4hMn9+d3nppWu8Kdw3buzr9EnkgQND5LPPDo/98MMu3vrodp94lpUNk2XL7vCq3195pZ3Mm9dN9u4dLJs395MaNY6V0aNbhPrv3j3IOy9Vj+lv//LLnjJhwtXy7rt/carlS0uHyldfHT7G+PFXy/vvd5Zdu+51zsVUHyzQY2zZ0t/7Z309+rr09ek10nO0x/jGC8j1wYYlS3p44+fM6So7dw50xqnm6/PV98XuZ6rXUCvOp069znsYQmcRsPukRwJyAIguBOQAAAAAkEV0vUn7j+qqSvU4ZJJdcrga077vEBHz3Q8FIDfY92KyAhQr6Q3ITz31h0H4WqfOyU57Ku7YMVA6drwwFLz76jrnr756rTPGd+vW/tKmzXnOOLVWreO9wNse4/v22zeGXo+vTgtfs+aPgn9+4YU2wRhzbW4Nm59/vo0cd9z3Q+MHDfq913fVqrtD/W2bNj1LVq682zkvDan9Prrv/v0vc8b649et6+2MNwPydu1qy6OPNgumujfV89Tw3hx7xx31nX5PPnmFcwxVHwRo1eoXTn9Vj9erVwPZti25BxWSk4AcAKLLt8rKypxwOx0CAAAAAIRhanWIAq+Ke98hIkbFzwQg+9j3YbLq9OwAxUj6AnINO80QdObMTk6fqqrV0BqC2wGrbdu254lWQacyduTI5s5xNfS1+8VTA2AN8P1xZuCt4bPdX/UryFu0OMdps9UguaSkX+jctLrc7pdIHa9V6+Z4MyCvzFtu+U1obLIBuVbCxwvdbTXct8emLgE5AEQXAnIAAAAAyALVWZ/SFCCDHErHQxyIiLl2jQBkF/seTFYCcihW0heQf/LJzaHws7Kptytz377BoUptreYeO/YKb3p1nY7cDqCfeqpVMFbXBzfHalCu1dwLF97mBcRNmtQMjV26tGcwVv+/2das2dlepblO0a6Bsdn28svtQuccryK8R49LZMaMjjJ4cGO5556GQV+dEt3v07XrxfL443/yztE+hraZx7ADcq0i1ypw3Z+ejz1er5s53Xu8gLxLl4u96c+1rVGjM0Jt5rX5+OObZNSoFtKw4c+Cdjsg//zzW53jjxjR3Js6Xo8xYMBlXniu2yubSr5qEpADQHQhIAcAAACALMDU6pDvfCnuPYeIGEVfEYDskur3PL7bQbGSvoBcw10zFLXbq6qGyf7+GjSo4U0tbvfRsNbvo6GrHwSb2zUcX7s2PNW4Th3esmV5BbdWgvtt5pTl9eqdJnZlujnduwbFZpsdkI8Z09I5Z9P772/iTbVub9f1ys3XZbaZAbm26Xro9ngN9M3zMKvkzYBcx+tU8uZYXTNcp8f3+9x3XxNn/+Z7YwbkOrZu3VOCNr0+Os29PV7XOI/3uqsnATkARBcCcgAAAADIMOmoyuUHVMgkW4V1xxGxsFwgANmDgBygaqQvIDdDUzs4Nl227A6pUeNYRw2X/T5afW4GvPHW0lY1vK5d+6Sg3+LFt3vbdX/+tuHDL3fGqQsWhCud/WpmrRj3t2lQbY8zw2cN3802MyDX87LD9WTVceb08Fu2lIfMZkBuH9/0zjt/G/TToN/fbgbkHTqc74xTzYcd9IEAuz1RQK6V8v52dfnyO52xmZOAHACiCwE5AAAAAGSQdITjKkAmYd1xRCw0n4i5RwCyQ6rf9wjIoVhJX0CulcbxAllbnebcDFF9dU1uv485TbdWOeua1ok0q511inGdXt3crxku22qlu99Pz0u3abW6v2369I7OGLs622wzA/KBAxs5Y+OpYbhOPd6376XSuvUvvddzzTX/EzrGp5/eEvRPNiA3r6FOw+5vTyYg/+ijm4I+OuW63Z4oINep3v3tOgW+PS6zEpADQHQhIAcAAACADGL/AZ2K/HgKmWSxuPccImIhOFMAsgMBOUDVSF9A/uqr18YNZG1XrLjLq65WzSppMyDX4NvfXhXHjbtSvvrqjuCf7enJbTXI9/vquua6zZxiXadAt8fce+/vg3Z9DWabGZBrFbY91nbmzE6hCvhE6vri/phkA/Jt2waE9rFnz+Ep6pMJyHW9db9PvNkAEgXknTpdFGwfNuwPzrjMSkAOANGFgBwAAAAAMkSqP5aa8sMpZJpnxL3vCtdNm/rKe+/9RZ5++kp54omWlao/utr7sNUfRO1xiZw48VpZsqRHsFYlImbaNQKQeVL9zqdTswMUI+kLyOfPLw9VVV1n2u5j+8wzrYP+ZkA+ZEjj0L600jsZP/nkZk9/XEUBsmpOpz527OGg9913/xJs04DdXL9cQ+ZatY4P2s1p4VUzIH/ppWuc45lq1bj5GvVYbdueJ336XOoFzfqQgd+WSkCulenm/v01vzMZkGtff3syDwikVwJyAIguBOQAAAAAkAFS/aHUlB9NIdPMFfe+K0z1x8Kzzvrv0A92yXjOOT929mWrVUP2uMr87ne/4/2YqYG9vT9ETKevCEDmSfV7H9/1oFhJX0Cugbj5HWvUqBZOH9tEAbn5na5p07OccRWpFer+2MoqyC+44CdB32nTbvC27d07OBSC6z40tNbQ3t6+YUOf0P6SDcj1Wul4v2+bNufJ5s39Qn2aN68VtKcSkOu5+f1UXdddt2cyIG/f/vxg+1//2tQZl1kJyAEguhCQAwAAAEAGsP9wTsVVApA5dsccJe59V1iWlPQLrRFZVTMVkPt+//tHywsvZLvSBbHY3CoAmUW/s9n3XTISkEOxkr6AXDW/62kFdGVV5IkCcrMKXCvD7XEVaa9Bvn37AKePWlo6NBRSL13aM2jbsWOgNGlS0/m+aJ6TVprb+0w2INcZlPx+OsV6vBmNqhuQz5rVOXS+/vZMBuQ6rbq/vWPHC51xmZWAHACiixeQm9pBd7oFAAAAgEIn1SoiU6ZWh0wzR9z7rrDcuLGv/Pzn5RU3qZjpgFw96qhvB9NrImImnCcAmSXVgFwFKEbSG5BrkGt+t/rzn38VN/z1TRSQ29XoySy1Y1qz5o+CsYm+2+lyO+YxzPPUadVvueU3oXZVA+lBg34v+/YNdvanJhuQ9+7dIOina57b7Wp1A3JzvFmFn8mAXNdx97erq1f3csZmTgJyAIguBOQAAAAAkEYIxyEqPCXuvVdY1q9/eujHslTMRkCufvvb35a5c7s5+0bEdPiSAGQWAnKAqpHegFxt2fKc0HcrrSr317821W3mmtVmQK526XJx0KbV6EuW9HD2oUH1Y49dLlu29A9tf+KJlsHYGjWO9R7WNNu/+eaeUIh+2231gjadYt1v0/ObPr2jd656LF3XW7XPwzfZgHzEiOZBv3gB9KRJ7UPX8LXX2gdtZkCuFfC6Lro9fsyY8tevzpzZKWjLZECu07ib11XH6rW2x+s0+Dplvb29ehKQA0B0ISAHAAAAgDRRnR9HTQEyzRJx77vC8q23bgj9QJeq2QrI1csuO8PZNyKmy70CkFnsey5ZAYqR9H8XXbbsDi/Qtr9fnXvuCXL99RfInXf+Vpo1O9tptwNyrSLXCmmzjwbQzz/fRsaPv1oGDmzkTR3ubzfH6jTrGoz743Q/GkrPmNFRHn/8T8E4VUNmc/3vjz66KWjT6c+1Cr5x4zND+9O1yDUk3rYtPH17sgG5Poxpvi4N6KdMuU6mTr0utA/fXr0aBGPNgFzV83rggT96Vfa67rf50IGqU8Wbx85kQK6+/3751O6qv4a7LmWkMwZ07lwnaDMr46svATkARBcCcgAAAABIE7qOpP0Hc1Wlehyywavi3nuF5UUXnRz6kSxVsxmQqx98kM4f7BCx3AUCkFnsey5Z9QFLgEJF729V/8bRv5XS8fdSYktK+nnTetvfrxKpIWq8QFnXIrdD8nhqIK/Vy+bY+fO7h4LweOpxp027ITROK8XtfonUaundu8sruJMNyFVdo9ven6kddPthsh2QV2Tduqd408Wbx810QK6OGtXCOZd4tm17njM2dQnIASC6ZD0gVwEAAACg0GBqdYgK68W99wrLxYtvd34IS9VsB+RaLWTvHxHT4SsCkFnsey5ZCcihUMheEF6ROhX58OGXeyGt/T1L1XC6Xr3TvDXCNfS1x/tqJbkGz9rf3odWePfr19DrY49Td+wY6AXRdkW77ksr1u3w2FfDaD037adqxXirVr+QG2+8yKuEN/d1331NgnFaCe5vr2zddA3itTLcfk0auuta3tpH1yf3tz/1VCtvmx2Qx1vKSB8M0OuilfT2cXXKeL+fVvTb7erChbcFfbR63m6Pd162S5f29Mba56Zq1fujjzaT7dvDFfjVk4AcAKILATkAAAAAVBOmVocoMVvce6+w7N3b/dEvVbMdkP/nf37PqURCxHQJkElSDQQJyCFq2FXh9j2dP5aWDvUCU63Wnj27q1dhbvdJRg20Z83qLF9/fae3T7u9Ijds6OONXbnybqloHfFkHDCgPCDWNdft9qqoFehaKa9V27r+ud2u66vrlOx+mGwG5Fpd7+9DK+Y//vimhA8L5MqysmHe+6VTr+s9EG/N9PRIQA4A0YWAHAAAAACqif1HcipSPQ7ZYry4919hedppFU9rWRXPOOM4Z/+2Y8a0dMZVx1deaeccAxHTIT9iQyZJNSjkOyDkK3YQnuo9jsmqQbwGzvZ2X3OacnuN70wbLyBHle8WABBdCMgBAAAAoBowtTpEiV3i3n+FpVYH2YFzdfzXf/0XOXCg4oruW2+t54yrjn/6Uy3nGIiYDlcIQOZINTzkeyDkA34YThCeK7XiuUGDGt53wdatf+lVZet06Lp9yZIe3oxF5pTtWk1u7yOTEpAnkoAcAKILATkAAAAApEg6wnEVIFssEvf+Kyy7dLnYCZyr64QJVzvH8dUfLn/2s2OdMdXxu9/9TprXRkTEw84XgMyR6vdCAnLIJlSF56tVWbJHA2qdAt3eRyYlIE8kATkARBcCcgAAAABIEfuP41TkR1HIJpPEvQcLx4MHh4Yqa9Llf//3MbJs2R3O8bSip3PnOk7/dPjkk1c4x0PE6jpTADIHATnkEwThUXP9+j7So8clzndC28aNz5TVq3s54zMtAXkiCcgBILoQkAMAAABACqT6I6gpP4hCljk0Qtz7sHCcOvU650fEdPnv//5v0rfvpTJt2g0yd243efrpK+WCC37i9EuXv/3tT53Xh4jVVR8SAsgUqX431OASoDowPXoh+c0398gLL7SRPn0ulWbNzpb69U+XDh3Ol/79L5MFC251+mdLnTWpTp2TPVu0OMdpL14JyAEguhCQAwAAAEAVSfUHUFN+DIUsc2inuPdhYdmmzXlO0BxVjzrq27J2bW/nNSJidRwnoOyPuTLm5zHnxZyLafElce+5ZHziyHjMnP+Uw8vMrJdoQ1U4Yv5JQA4A0cUJyLMRlAMAAADEZ3HM12M+GfOv4v7xhQXjoTjbCk69h0fHnCiH130tE8ghh74S9z0qHHXax+9//2gnaI6y99/fxHmdiFgdH5HiRkPxV8S9LojF5MMx34q5XfIbqsIRoyEBOQBEFwJyAAAAyANWxPybuH9sIRaSOr23Vu9ATjiUjpkP8tfnnrvKCZij7rnnnuC8TkSsriVSnBT2fwMQq64G5Usl99hV4fZ5ImJ+S0AOANGFgBwAAAByzDJx/8hCLGQ/FcgBh14W970oHBs3PtMJmAvBxYtvd14rIlbH2VJ86BTT9nVAxMNma9p1OwgnDEcsDAnIASC6EJADAABADimN+bi4f2QhFrqbBbJN4c5SsWlTX/nXf/0XJ1wuBO+++3fO60XE6lhs65DvifmAuNcBEQ87QdIP06MjFo8E5AAQXQjIAQAAIHcc+ljcP7AQi8FpAtnmUXHfh8Jw+PDLnWC5UDzttB86rxcRq+tGKR74rolYuZskNagKR0QCcgCILgTkAAAAkEOeE/cPLMRi8DGBbKKzVdjvQeF40UUnO8FyIfnBB12c14yI1fEDKR4miPv6ETHsJ1I5BOHV079ueg31Wi6J0wcxihKQA0B0ISAHAACAHHK/uH9gIRaLWwSyhf5wY1//wnDZsjucQLnQ7Ny5jvO6i90tW/rL0qU9PffsGeS0V8etW8v3vXt3evetZvLcMVmfleJhpLivHxHDviHl2FXhdl+sXDMIV+OxQ9xxiFGUgBwAogsBOQAAAOSI7eL+cYVYTK4UyBZrxb3+heHAgY2cQDlT/tu//Yucc86P5ZJLTpfjjvu+054p9VgHDw51XnumLC0dKk891UratasttWufJDVqHCv1658urVv/Up55prXs3TvYGZNtu3X7dXB9XnrpGqe9Ouq67/6+x4270mlPRg3BBwy4THr3biBr1/YOtSV77tOnd/Qejpgw4WqnDaurPqC4V4oDHsZErFxdhoYwvOr6VeEVBeGJICDHQpGAHACiCwE5AAAA5IhvxP3jCrGYXCqQLfRHS/v6F4Y1a/7ICZQzYZs258nmzf1Cx/7739vKscdmJyifMuU657VnQq3I11DcPr7pBRf8xBmXbZMNmVMxHQF5376XBvvQBwvMtmTOXavYzWu+ePHtTh9VH2bQMN7ejsm4TAof/f3Jft2IiFXVnh69qmF4PAjIsVAkIAeA6EJADgAAADmCgByL3S8FskVhBuT//OctTnibCS+//OfOsX3ff7+zHHXUt50x6faqq851jp1utTK8Vq3jQ8fV6vUTT/yP0LaePes7Y7NtMiFzqqYjIDfPr1GjMxK2JTr39ev7hK75ggW3hto3beor/ftf5r033bv/xhmPyfi+FD4E5IhYVatTFV4VCMixUCQgB4DoQkAOAAAAOYKAHItdAvLsUZgB+a231guFiJlyxYq7nGOb/ulPtZwx6fb73z9adu261zl2Oh09ukXomJMmtQ/atm8fIC++2NarLp87t5szNtsmEzKnajoC8uXL75Rmzc6WBg1qONcr2XN/7LHLvQcWevVq4LTpe+Hvg4A8VcdL4UNAjoiJzERVeFUgIMdCkYAcAKILATkAAADkCAJyLHYJyLNH4QXkZWXD5IQTwpXNmfC//uvfnWPbDh7c2BmXCZ999irn2Om0bdvzgmP16XOp055PJhsyp2I6AvKKTMe5E5Cnw4el8CEgR8RcB+GJICDHQpGAHACiCwE5AAAA5AgCcix2CcizR+EF5DNmdHQC5Ex4zjk/do5tqyGqPS4T/v73ZzrHTqe6trh/rPHjr3baq+KGDX1k5sxO8sor7bz1sw8eHOr0MV23rrf3nmrwO23aDbJxY1+nj2lVQuZt2wbI7NldvX2/9lp7+eqrO2J/lw9z+vnaAbk+jPHllz3l5ZfbyYcfdpEdOwY6Y3x37x7knbvp/v1DQn0qO3edPt0cb68xru0jRzYP9vHnP/8q1N+faUDPM9E52G7e3C/oW9G1KTz3SWFDQI5YXGZrevTqs3v3Dpk1awli5N21a7t9ewMARAYCcgAAAMgRBORY7BKQZ48N4l7/aNuhw/lOgJwJ8ykg/853jvLCUfv46VKnBPePlUoF+b59g71xxxxztHPuqlaoL13aM+i/c+dAeeCBPzprnPvq9OK6xrt9HLWykFlDbQ35dUp4e7+qnuOTT17h9bPHmgF5/fqne+uw2+N1v/Pnd3fG3nFHfaevHifZc9dQ2x6vx/fbt27t77TbamCufTt1uijYdt99TZxzTXRMPYbdp3AtkcKGgByxMM3XqvDk0YB8/Pj9iJGXgBwAogwBOQAAAOQIAnIsdgnIs8cuca9/dN27d7D84Affc4LBTJhPAbn66KPNnOOny969G4SOFS8ATqT2rVnzR8752tard1owRtfYttvj+c47NzrHqyhkVj/7rLuzn3j269fQGWsG5JU5ZkzL0NhMB+RaTW632/oB+axZnYNtNWocK4kqw83p2ps2PctpL2yjFypVDQJyxOgbnarwqkBAjoUiATkARBkCcgAAAMgRBORY7BKQZxf7+kdXDRXtUDBT5ltAfuGFP3GOny516nH7eBog6xTldl9TnVb81FN/GBo3YMBl3lTpOs368OGXe9Xgun3BgluDcRoG+9XmrVr9Qh58sKkX1g4Z0jhUha5j7SnaKwqZfRs2/JnXXqfOyTJwYCN54YU23tTk/rn4rlx5d2icHZB37HihvPXWDTJ5cge5556GoTb1009vCcZ+/PFNMmpUi+DYalUCcn2do0e38B6E8PuYAXlp6VDvXHr2LA/iNdTWa+2rU9prXw3ENRj3++n08OaxfM2ZAyZMqN7U+tFzrJSHT341Zjz9YMo0ChCQI0ZHuyq8sNm9+5ATNCJG0V27yHoAILoQkAMAAECOICDHYpeAPLuMFPc9iKaXX/5zJ6TMlPkWkKvLlt3hnEO61DDXPp6G1RoM22th+5qV5zpduh/Qmmqwu2RJD2e7ToMeL7hdseKu0DloRbjZXlHI7DtvXjfvvbErp3U9bjMk10p2s90MyONNTa7X3wyeNYC3j2EG6VUJyH11unq/jxmQ+5pV3927/8Zp99WHDvx+GvTb7WZFur7Pe/YMcvpgVTTD9qqG7pmAgBwx/7SD8Ex9/vMbAnIsFAnIASDKEJADAABAjiAgx2KXgDy7jBP3PYieuj7y0Ud/Jwj1Mm0+BuT9+1/mnEM6nTLlOqciXNUAVV+r2Verx80+zz/fxtlfqrZvX77O/GuvtQ+1JRMyV+TTT5e/Z7fdVi/UZgbk9uv11bXRzdetYbzZni8B+caNfUPnqe+X2W7eu/ECdMwHUw3cVQJyxNzqf26LNwhPhAbkc+eWIkZeAnIAiDIE5AAAAJAjCMix2CUgzy6TxX0Poqeu+WwGfpk2HwPyM8/8kXMO6VYriUeMaO5VhNvHHzr0D0E/XXvc365BbllZ/HWuK1MD5sGDG0uHDud765TrtN9mSG+vvZ5MyOy7bl1veeSRZtKly8XSqNEZ3vTnegx/vB7L7J9MQK7WrXtK0E+nbzfb8iUgV1u0OCfo+9xzV4XaGjc+M2h7992/OGMRETEZqQoHAACA6EFADgAAADmCgByLXQLy7PKxuO9B9LzkktODQC8b5mNArs6dG65YzpQa1D788P+G1gRXNRjXdjOo1fDZHl+ZX399p7RsWR7gJtIM5dVkQuadOwfKHXeUr9WdSPu8kw3IO3euE/TTQNxsy6eA/M03rw/61q9/erD9m2/uCbbrgxCpPtyAiFhcEoQDAABAYZAwIM9kWA4AAABAQI5IQJ5d9Edc+z2IlqtX95Kjjvp2EOplw3wNyG+55TfOeWRSXT9cg1r/+Bry6vYhQxoH26o6Rffy5XeG9qk2bXqWF2rrtOfmOuFVDcj37h0sDRrUCO37ggt+4o3r1auBV0Xub081IO/XrzwEt9+PfArIDx4cGrrO/hr2TzxRPhuDriNvj0NELG6ZHh0AAAAKGwJyAAAAyBEE5FjsEpBnl/3ivgfRctiwPwSBXraMF07aanhrj8u0J5yQ/YrfPn0uDY7vVyKba3lruG2PqUgzwNYwXEN4s12nVffbqxqQ33vv74N2rX7XKmqz3ZwaPtWAvFOni4J+w4dfHmrLp4BcNc/Hr3bX99DftmjRbc4YRMTi8RGhKhwAAACKDQJyAACA/8/em4BNUR34+nMzM3fmP8sz87+z3DuTZLJeJ3HyaBKjIS5RmcElSAwhoHFQCTgEEI3iBkQWFVQ0LlHjvsToiBEXXKJhXFDR0bgFAZcIboiKguAKLui59asvp79T53T3119Xd1d11fs+z/sk1jmnuqr6o7v6/OqcAxlBQN6ozz9/tFm+fLLRVLx+WVFct+64+Byl1v71y4spAXnnuciE70P3+OUv/2Ml0OukGrnuH4trI1OEt8Pbbx8XHEs7dafq3myzv4u33X//wZVtWjPcb1NLjWJ2z6XaNU4TkLtrp19//Q+C8lYE5Gpn691yywGJsk4G5Fpb3S/31Wh9W1/XZtWqaZX//upXPx7URyyT3Xif+dFHJ5sVK6bEx/3ii9ODcuyv8wwAAABA2SAgBwAAgIxobUB+330HxVPSaorbffb5SjyST533+v+TJw+MR7ctXXp40K4bdNe+3bTppKC8CDYSmGi0qKbEPeSQHcxDDx0SlHefBOSd51YTvg/d4bJlh1f+jXTavfb6cnA8VgXEf/iHHwvadMLRo7cJjqednnvusMpr21BVD/e4xzR/fhhGV/PWW39YabPTTp8LymW9gFzfd7Zs1qzdEmXvvHNC4pjef39OsO+0AbmCKfc1FEC75fUC8nrHbu0rIL/66v0q5cOGbRGUV9OdVn7w4C9W/r+us18XsZqa5WHmzF1ir7ji34PybjXNfeYZZ3wnvocbO3aAGTlyq/iBqaFDvxR/PmsmixtuGB0vc+C3S+urr86sHLN9YAnTSEAOAAAA5YOAHAAAADKitQG5GyTUU8F5t02lmqbjsltsJCDXaFFbR4FJOzpcOysBeed5xoTvQ3f44x/3hpZZeMABXzdvvDErcUwamfx//s9fBnU75V/91Z/Ga23716pZNSJx3323is/Ln75d3xvuZ7GdplvqwSy7XaOTFT77+37rrdnmhBO+ZdavPy7+bz2wZdtovwq13foK4jQi3dZRqOyWu2ufq5773aDzcI/13nsnJtq++ebsRECs6d3dcjcgnz1790SZ1EMBbntdM79OvYC83rFb+wrIH3zwR5Vynav/t1nNK68cWWnj+vLLM4K6iNW87rpRlb8b/8GSbjbNfebmm//v4N+Ur/6d66Egv20aCchbLQE5AAAAlA8CcgAAAMiIbAJyqQDjtdeODfaRV9N0XHaLjQTkbse0rkn3XwsC8s7zQeTpJnwv8q0Cz8985n8Fn2Wd9s///H+ar3/9n+Jg6J/+6a+D8izUSGL/ejXrPfdMrOxXgc7++38tXndcM5G4r6nPn+ee+3Glnb5P3M9pOXHiduaSS/aKP8802lQhr7YrHFab996bk2ijEZfz5u1n7rhjXDxa3N/fdtt9Ov47sK95880HJMr1veaOhNbDYLZMo93PO+97ZtGiA80FFwyvGmi9/npvwOwG5FJhuNZa12hyXQ97LtaVK48OrmW9gLyvY5d9BeR64MC9Rqozffqg+LU0crVaGKeHEPzrqnPz6yHWkoA81P880b78f2dWzYTit29WAvJWS0AOAAAA5YOAHAAAADKifQG5Orw1Ou+xx46IAwEFAwMGfCrRSVdtxFteTdNx2S02EpArUNJaswp7NBLQL+8+Cciz4SYTvhf5ViOA/aABe1Sw7F+vZp0wYdtg/9VcuHB80Fbvkbvudy3dsHfu3Oojmq363nI//0899duVthrhvvXWn0zUd9fS1rq8/v5c9QCAQiX730OGbF5p6wfktdSx+WuPW+sF5H0du+wrIJdnn/3d4Jis7gh/1zFjtknU01rmfh3EWhKQh7oBuZbcsNt1z3bjjaMTD9S4nzNpJSBvtQTkAAAAUD4IyAEAACAj2heQa7pbv1wd8hoNaOuoM9Cvk1fTdFx2i40E5MWTgDwbFpvwvci3jQa3ZfRP/uSPKtOWp1UPVfkBqqu+W+pNx61pvjVy3B9hLfU5PnnywMTIc6mQ3B9tqaBd07Hr837BgrGV7aNGbZ1oq1Hf7vH6IfPDDx9adXSn9qO2q1ZNq4T6bghtA3KtKax11/3j039rVH29a3HccbtV6l966d5BeV/HrnDNltUKyDWi/mc/qx6S633w60u/vj+1PWI9CchDawXkVvczrNa/5WYkIG+1BOQAAABQPgjIAQAAICM6G5BLd81XuXr1jKCOVMe81pBVUKtRga+8MjOoU02thbtkyWHm2mtHxWof/V0n+4UXpsXr36pDUSMA/bVk+9txqeBIx++eg47pgQd+FJ+fOjO1Hq3fTur6aJpajQB64okj4+vi17EqZLCvo3p6IGHFiinmhhtGm9tu+6F58cXpQRvXegG5jtfu26rpdf19+Or477prQtyhrePv67146aXp8fTGGlGo8270fW9eAvJseD3ypyZ8P/Lp++/PMX/7t3+e+OzCpJo23L9uadTnmdYAv/32cfFngj7L+vr88NXnj74/NKVwXwG+9q01zvW57E51btVoan2f6PvBL5P6zF28eFL8HeeXyeefPzo+Fn3G+WX6jtG56uEAu00h/p13jk+Ex3rtWvtIY1/H3oi6PtqHrp++a+p9T7rTuyug98sR69mqgFyf67pf1P3OffcdFD9c49eppj4fdN+m+xTdm+mzyV16oRFbfZ/ZV0DuBtmy1kMp/b2H7k9ArnPStbrppjHxUhZaTuPtt48P6vn7132g7mfdbbpumjlDn5NuWV/2955UNvt7pDkJyAEAAKB8NBSQtzokBwAAAMgiIFfHudtJp1DALVdQrLZuHatG2c2f/4Ngn/I3vznYDBu2RdDGeuSRO/fZEad1dKtNz6t1Z93/TtNxqdF+Rx21czAaUJ1ubhsF2pp+1z8WqbVd16w5JnidadMGVeoo7N5ii38I2up1tYat31bWC8jVEenvq9YU+QpKtEauf45uO3UI2/oK2jVtcbVrL3Ue6kj1X6c1EpBnxy0mfD/yqTr0/b9LTLrTTp8LrhtiNQ85ZIfK340efvDLEeuZNiDXwzIjR24VfIZJ3W888sihQRuFsAp1/WUJrLrf0TIGfYW1nbjPrBaQP/jgjyrlen2/vNl76EYC8pUrj07cX/ruuee/xA8Q+e0U4ts6ehBBvxfcJSmsWgbjmWemBu2t/b0ntTb7eySdBOQAAABQPgjIAQAAICM6H5BrNKDbyaSOK1umERrVOg591ZnljtZRR2Ktji/XWgGO2k+f3hsu92WajstqUwerQ9atP2nSjkEdX52v3wna6Jq1cu+9vxycRysCcr2H/nTC1XTfi3pr2LpqNKX/euklIM+OlSZ8P/Lp97//leDvEZN+7GP/o+boasR1646LAyV9b9i/GX3f+99DiH2ZJiBv9D5Tyxq47TSq2q9TzWOP3TV4TdnJ+0z/3lAPIe6ww2cq5eeckzy3NPfQjQTkw4dvGezLV6+/du2xiXYK5N19V1s2w6qyaqPim7knte0a+Tvxf4+kl4AcAAAAygcBOQAAAGREZwNyTV/pjmoePPiLlTIF5W4nlkZPX3LJXvHIao3e1HqtbqeUv57qnDmD4+3q0FJQ/ItffD+u44+I8YNfqc5Ct86gQZvF7fXa1dZ+TdNxKbU/hcKaQlxhuKaxtHWvuOLfE3W1hqvC6UWLDjTnnz880UGoDsMNG3o7BP2AXOvTaipbBcua/tg/Dn8keb2AXOvk6vUPOmj7Sh0/IFfnpD/qfdas3eLz1JSWWnfWvv/uVL4apWOvsYL7007bM566VO+pe+3VtpHpMPsnAXm2XGbC9yRfKlz4sz/748TfNVb3pJP2CK4fokZ++n8r+mx/6KFDgrqIfdlsQK77B/c+SPeLc+eOjJc20JTdQ4Zsnvgb9UcV77rrP8fbNdp79uzdzZVXjozvEf3ZeqqNhu7kfabuv3Ufpc9j3UO6+z744O1NtVHuzd5DNxKQa/p69/XPO+978XX3HwZVmdvODcitQ4d+KW6rWYX0MIJbduaZQxPtm70nTft7JJ0E5AAAAFA+CMgBAAAgI9oXkGsaygsvHGEuv3wfc8YZ3zHjx28bdABqhIZte8wxvR1d6jisNhJEAa2to31p/UhbppD1xBMHV23nhroayeKWaVSbe1ya/tzvmNS6tO5x++V96QfTGonk15Fa19A9FnXY+nV0vO4Uk6efvmelzA3IZ87cJWirdRQ1Pbuto45QN2CvF5BbNR2ureMH5O7oKO1b6zv67XXt/Gn1paYuVSeqv13rS9p9ylrXrnkJyLPlMRO+J/lSD5K4f4NY2y23/Mfg+iHqu979O9GDXu73P2J/bDYgd+8hdY+iJX/cct2fjBjRO9pZD+y55Zp6Xd8H/ohh3Vu5IbkegHTLs7jPrKbuf3UsflvZ7D10IwG5POWUIfFU6/52TTlv2+sauWV+QH7yyXsE7fWggi3XAwxuWbP3pGl/j6STgBwAAADKBwE5AAAAZET7AvK+1Ahh206di27ZSy8lOy2t6pR013+s1tlVzaefnlJp409nPnXqv1bKvvrVj5tqI2uk27mZpuNy8uSBQbn1+OO/VamnsNovt2pUuK2nUeJ2uxuQ+6PDrW5npnSnLU8TkLtrRUqN8PHbNqsb6msdSr88nQTk2fKSCd+TfLnbbl9I/G1jfZct6x2Jhyj1oJOCTI1s1ajbjRt7l1ZB7K/NBuTuw4UaPeyXS40kdj/Pqq27XU2NuLZtjjhip0RZp+8ztR89hFJrSnL3/rsR691DNxqQ11L39e5U5m6A7wbk1dZNlxrlX+31m70nbffvkb4lIAcAAIDyQUAOAAAAGdH5gFzrIPqjNRSo2HJ17Gk0cS01taWt605NblWnmKY71AgdTcWo11OnvHsMbn13Xcbrr/9BsD9rqzouNVW6X251Ry5pqkn/3K3q2LX1tG/bvpGA3H8dd2rINAG5O0JQnbK1OoD7UiO0NIpJa7VrTUi9h+4Umfob89ukk4A8W1r7GdRqV6+eYf7ojz5W+fvL2j/90z+KH7LRgyKa7lWj2BS4+PWydMqU2g8BIaLrDZH3/t5fevp10dpMQK7p1d3PqVojqaV7z6Hp1/1yhaaazlsjq/X6Grms+xXbRvctbv1O32e6a5DrvDU6XVOtu+eva+jvQ/b3Hro/AblCZT3gqRmO9HCn7uf33/9riX0vXjypUr+RgFyzIFU7tmbvSVv5e6Q5CcgBAACgfBCQAwAAQEa0NpxyA3J1GirA0TTh7hqG6uTSmr5uO3U0uR1cjeqHwJrSvdaIGVe3jdshqVFu/jlVq5em4/KFF6YF5VZ3dFOjup2GjQbk6vi09dyp2NME5BqRZLc32mHt+swzUxPBfS1bv8YxAXm2rDfhe5IftTyE/zeYlX/3d38RPFwkFYCMHTsgqJ+Vn/70/zIKQvzjRETXCyM/NP1npacN2H39wL04oXszAfmKFb2joP2pvH3dsFtrTtvtunfVA0D+Z56vf0ydvs90A3LXI4/svffT/aYfGjdzD91oQK41v90R17V0l9ppJCCX1Y6t2XvSVv0eaV4CcgAAACgfBOQAAACQEe0LyDXixG7319Y+7LAdE+3mzBmc6GjS6J1GfOihQyr7+MlPhgT70DEoAB41autEmW3jTzeuoMk/J2urOi41ItUvl+qodI9FnZT++VZT52b30WhA7l5v931KE5DX2mcjPvvs1KBTds89/yXuiNZUpe7angTkReNtE74n+fHrX/+nxN9lltabIlaj6D7/+b8N2mRlvZkyEFHeafJDd4XuzQTkul+0beqFrVIjp23dSy7ZK96mZQG0HrX7OTdgwKfi+6Zp0wbFo8irHVMW95m1AnKtAe4ei7sGezP30LKRgNxdFkjqPHX/OGPGLmbChG0T93+tCsibvSdtxe+RdBKQAwAAQPkgIAcAAICM6ExALi+6aESi0+nhhw+tlCnMtdsVjPr77ct77pmY2Pcppwwx778/J1HHLbfbNBrI3a4g39+3tVUdl7UCcumuw6ipxv3yvmw0INf07bbeccftVtmeJiB319/s73vodjorDPdHybp/VwTkReM9E74n+VDhgf27y9o//uM/jNdG9Y/RddKkHYN2Walj8Y8PEV1fMsXFD9ylf/7N20xArpHbtk1fI8gVfNu6t976w3jb8cd/K9FesyO5bdwpvd1jyuI+s1ZA7j+IqVmetL3Ze2jZV0Cu83fPa+TIrcxrrx2bqOPOMtWqgLzZe9K0v0fSS0AOAAAA5YOAHAAAADKicwG5Oubc9fq0bq4dSeOO7NFIDH+/felOeVkrmKnWgSZrjVzxbVXHZb2AfMiQzSv16o0WrWWjAbkbSLuvkyYgV4es3d6f9/Dpp3unPZXVpqAnIC8ymmLYf0/y4a9//R+Jv80s/cIX/j44Pl9Nj+u3y8p/+7f/GxwfIlo18rpMqP/JvwbN20xA7q9B/sYbs4I6Uvd37v3e8uWT4+3uA4zV1hGvFZDLTt9n1grIX355RuIaaNpzbU9zD91XQO4G1Zpi3Q/eZTsC8mbvSdP+HkkvATkAAACUDwJyAAAAyIjOBeRy6dLDEx1Zp522Z7zdH2Ezf37Y+VhPd71I2+Hn6+7f3T5w4Ocr2/fZ5ytBO2urOi7rBeRuwO0+QNCojQTkixdPSlwLd6S6pjO322fN6h1Z7lorIF+37rjEfht9DzU6y7bR++iXSwLyonOJCd+X7NXnk/s3naVbbvmPwfH5uiPfsvbjH68dZiDiYlMusg/IpXsvZqdO91X47X6WKdB9550Tgm1+u3oBeafvM2sF5OefPzxxHgrMtT3NPbR/76f7ebd8+vRBlTJ3xiLXdgTk/nE1ek+a9vdIegnIAQAAoHwQkAMAAEBGdDYgl1On/mui80nTXmr7QQf1Tvut0Tb+NNvy3XdPNGef/d2448vdPmLElpW2J544OFH20Ucnx+scuq/ptvdDpWrBskY1u3XSdFzWC8ifeWZq4nU0qqdaSK6O2Kuv3i/Y7gbkZ5zxnaB81appialD/UDaXXtRI2eqnWetgFzqPbdl6szUcfrt1fl4wgnfMuvX97wH7kMT6hxWR7RbX38HOhZbRyG+v890EpBnzwITvi/Z6382ZGm3BeSNHC9iOb0w8gNTLvIRkLtL/Wi0sz/d+Zo1xyTu1+z9hu4j3fDaTk1uffPN2Wbw4C9WyrVUjFvufza3+z7TD8g1g9MNN4xO7F8zCdnyNPfQOk637PLL90m0P+ecYZUyrdPulkn/uG68cXSlLE1ALpu5J5Vpfo+kl4AcAAAAygcBOQAAAGRE5wNyBaDuVJXqVNR2dVK526Wm/NYU4PPm7Wdmz969EpRqu7vP00/vHempTkx1di1cON5cddW+8RqC7j6lXVNSqnNPo7XdcnW4KmBWJ+yxx+6a6BiVaTou6wXk8txzezsTpaak1LGoE/G8875nRo3aulLmT0fuBuRS74GunzpjFbb75/HAAz9KtL/55gMS5Xo/9J66deoF5FpX0n+NiRO3i0dqacr2mTN3qUw1qjBebbSusttm6NAvxe+3Xkejxf39aZp+ddi6r5tOAvLsWWLC9yV71Snu/u1laSOBsx/CZOkBB3w9OD5ElP9tykf7AnKp+6R6KgBWOz1wqGDcttM9jgJc3W/o/sp9GE/3Hu5a2e69pO4ZVX/RogPNBRcMT9zjWV9/vXcK907fZ+q+WvfJhx22o9l77y8nzlnqtR577IhK2zT30FLX2C3XfZyWz1HZww8fmijTQwe617zllgMSy/pYp00bVNlv2oC8mXtSmeb3SHoJyAEAAKB8EJADAABARnQ+IJd+EKtOOG3X2n9+p1Q11aGlYNXub+PGE6t2ULrusMNnEu3d0SIaxex2jPZlmo7LvgJyjfRxR6/U0x8l7gfk9dRIqmqv7Xd0qlPXrVMvIJcaWdXoe2jbqNPRL3fVqHe3k/PUU78dvG7zEpBnz2oTvi/Zqwcx/vqv/7/g7zELuy0gV2jkHx8inhn5hikf7Q3I+9JdS1qjiPu639P9hh8Cay1yv57/Gm4QPWTI5on2nbzPrKfq+eugp72HVpju17/ppjGVcnckdzU1stz9b3t8aQNy2cw9qWz290h6CcgBAACgfBCQAwAAQEa0NiB3p1LUKA2/3NWd0lEdTHYqcY3c0IgMf9SHVHirkTb+GodSwbNGrfhttPajRoJq/+4UmCtW9IxusaqzT6Oz/dfVf+u83O0Kkv3Xr6em27RtNYWnX15NdTj6I46kOuw0okcPGfgjqd2AXB21/rlITaupjlr/9awa9TRmzDaV+n5ArvUpbZmul99evvHGrPj9tyNzXHVMkycPrEytb1VI7h+vzlUjmdRRvGDB2D5ftzkJyLNHv03OMuF7k70//el3gr/hLOymgFyfPRs2JJdKQER5uyknrQ3INQ23/7lTT30mue01JbpCW/8eRfcgw4dvaV58cXrwmlKjof0gWW10T6J7Jy1jY0NVP3CVnbrP9Pet+ziNJNf057WC97T30Londa+NG5BrOnKNDPf3rfq2ntYnt9svvXTveJu79nu9gNy9bn6ZbOaeVDb7eySdBOQAAABQPgjIAQAAICNaG5C3WnVSavSH1uau1annqykV1Uadd9XaaFpyjQypViYVOuv1Fi+e1Odo706okT0a8aRjViefX+7qBuQKy3Qu7jXsT4erRsToGtQL0xtR11Cvv2zZ4YkRR9VUB+zjjx8RT/3uTk9qVSerroU/tXw6CcjzwTUmfG+yV/+GvvnNzwad4522WwLyj33sfwTr8yKiPCPyVVNOWhuQt1J7j/L880fHn/d+eTVVV21eeikM0rUPBcruFOa+ebvPdE17D7127bHmkUcOjR9C8MsUeKvtkiWHxfe2frnW89ZDCH3d66axP/ekrs38HmlOAnIAAAAoHwTkAAAAkBH5Dsixf/oBuV+O1SQgzwdLTfje5EN1jP/bv/3fIAzupN0QkGs6+v/8z38PjgsR5W9MeclvQI6YLwnIAQAAoHwQkAMAAEBGEJAXSQLyZiQgzwfvRZ5rwvcnP5577jDzqU/9/0Ew3AnzHJD/2Z/9sRk2bIua0xIj4i9NuSEgR2xMAnIAAAAoHwTkAAAAkBEE5EWSgLwZCcjzwx0mfH/y5yuvzDS/+tUYc/bZ3+2Yv/zlvsFx+P7ud0cF7drpz3++d7zkQXunm0Usgs+ZckNAjtiYBOQAAABQPgjIAQAAICMIyIskAXkzEpDnh1UmfH8QEbvZOw0QkCM2JgE5AAAAlA8CcgAAAMgIAvIieeGFI8x22306dsGCsUE5VpOAPF9oKmL/PUJE7EbnRn5ggIAcsTEJyAEAAKB8EJADAABARhCQY9klIM8XS034HiEidptnRa42IAjIERuTgBwAAADKBwE5AAAAZAQBOZZdAvL8cZ0J3ydExG7yMQMWAnLExiQgBwAAgPJBQA4AAAAZQUCOZZeAPH+wFjkidrOLDLgQkCM2JgE5AAAAlA8CcgAAAMgIAnIsuwTk+eQuE75XiIh59wYDPgTkiI1JQA4AAADlg4AcAAAAMoKAHMsuAXk+2RB5kQnfL0TEvEo4Xh0CcsTGJCAHAACA8kFADgAAABlBQI5ll4A8v2gNX//9QkTMo4TjtSEgR2xMAnIAAAAoHwTkAAAAkBEE5Fh2CcjzzUITvmeIiHmScLw+BOSIjUlADgAAAOWDgBwAAAAygoAcyy4Bef75pQnfN0TEPPgrA31BQI7YmATkAAAAUD4IyAEAACAjCMix7BKQdwdnmvC9Q0TM0vsNNAIBOWJjEpADAABA+SAgBwAAgIwgIMeyS0DeHaw34XuHiJiF5xu+O/oDATliYxKQAwAAQPkgIAcAAICMICDHskvI0T28asL3DxGxkyrAWmugPxCQIzYmATkAAACUDwJyAAAAyAgCciy7BOTdxZuRZ5vwfUREbKenG6ZUbxYCcsTGJCAHAACA8kFADgAAABlBQI5ll4C8+9gYebUJ30tExHZ4feRqA82h/qf16y9FxD79L/+fDwAAAEDhISAHAACATHjjjXVm4cJnEUvrqlWr/H8W0BW8b3pCKz/IQkRslVpr/FED6VD/07x57yFiH959N/ekAAAAUD4IyAEAACATFJD7nTOIZZKAvNv578hTTRhsISI26UfnRN4b+ZaB9Kj/yf/uRcRQAnIAAAAoIwTkAAAAkAkE5Fh2CciLwIuGKdcRMbUE423ho482Bd+9iBh6111r/X8+AAAAAIWHgBwAAAAy4fXXGdWD5XbVqg/9fxbQtTwYeYYJQi9ExLr+nGC8jaj7yf/uRcTQu+/+wP/nAwAAAFB4CMgBAAAgEwjIsewSkBeNVyJvjTzNhCEYIqJVD9P82piPVhhoL+p+8r97ETGUgBwAAADKCAE5AAAAZIIC8iVLNiGWVgLyovJm5MLIM00YjCFiOb0w8sbI3zJavIOo+2nDho8QsQEBAAAAygYBOQAAAAAAQFt4JPJcE4ZliFhsfxl5e+QS0zO7BAAAAAAAAOQJAnIAAAAAAIC2caoJwzNELLbXGwAAAAAAAMgvBOQAAAAAAABtYb0JgzNELL6/NgAAAAAAAJBfCMgBAAAAAADagqZY94MzRCy+Cw0AAAAAAADkFwJyAAAAAACAtqBplv3gDBEL70f3GgAAAAAAAMgvBOQAAAAAAABt4RwTBGeIWAKXGwAAAAAAAMgvBOQAAAAAAAAt53UThmaIWA717x8AAAAAAADyCgE5AAAAAABAy3nOhKEZIhbfCwwAAAAAAADkGwJyAAAAAACAlqMplv3gDBGL7y0GAAAAAAAA8g0BOQAAAAAAQMt5woTBGSIW32cMAAAAAAAA5BsCcgAAAAAAgJazxITBGSIW28sMAAAAAAAA5B8CcgAAAAAAgJbzsAnDM0Qstg8YAAAAAAAAyD8E5AAAAAAAAC3nNyYMzxCxuF4QucEAAAAAAABA/iEgBwAAAAAAaDlXmTBAQ8Ti+lsDAAAAAAAA3QEBOQAAAAAAQMtYGXmvCcMzRCyuvzQAAAAAAADQPRCQAwAAAAAAtASCccRyusIAAAAAAABA90BADgAAAAAAkAqCccTyer8BAAAAAACA7oKAHAAAAAAAoCmYTh2x3N5iAAAAAAAAoPsgIAcAAAAAAOg3BOOI5fY/I981AAAAAAAA0H0QkAMAAAAAADQMwTgiXhi51gAAAAAAAEB3QkAOAAAAAADQJ0ynjojWtQYAAAAAAAC6FwJyAAAAAACAuhCMI6J1rQEAAAAAAIDuhoAcAAAAAACgKgTjiOi6ygAAAAAAAED3Q0AOAAAAAACQgOnUEdH1osi3DQAAAAAAABQDAnIAAAAAAIAKBOOI6KvPBQAAAAAAACgKBOQAAAAAAAAE44hY118aAAAAAAAAKAYE5AAAAAAAUGKYTh0RG1UhuT4zAAAAAAAAoJshIAcAAAAAgJJCMI6IzciU6wAAAAAAAN0MATkAAAAAAJQMgnFETCshOQAAAAAAQLdCQA4AAAAAACWB6dQRsZUy5ToAAAAAAEA3QkAOAAAAAAAlgGAcEdslITkAAAAAAEA3QUAOAAAAAAAFhmAcETshU64DAAAAAAB0CwTkAAAAAABQQPI6nfrcKtsQsRhqynUAAAAAAADIOwTkAAAAAABQMPIYjEs7wvSqKmWIWAxZlxwAAAAAACDvEJADAAAAAEBByHswbnkp8qe/L0PE1nlt5KORr5vsPw/8f/cAAAAAAACQFwjIAaBkbIx8AxFb5nsGACB7FERp1KYfUGVtvYDstyasj4j99/rIx03Pfb6PRnJn+dlQ7zMAAAAAAAAAsoKAHABKwFLTM5rkTBN2WiFies+NvClyuQEA6DxZjxKtZSPB2M0mbIeI1f1p5GWRt0Q+EPlM5IemMbIMyZlyHQAAAAAAIG8QkANAgXkx8lITdlIhYvu8JvItAwDQfro5GLd8aMxHeojP3wdima0WhGvK9LRk/ZlBSA4AAAAAAJAXCMgBoKCsjjzdhB1TiNh+9WAKU68DQLvoxunU66HPyzyeTys8rco2LI8Kus+JvCjy8sirTM906L+OvCPynsiHTM9sT7+LfM60Jgivh0Jq/zg7abOfEwAAAAAAANBKCMgBoKDMNWGHFCJ2zv8yAACtJ+sRoLVMG3q9E/mfJtxvN3tB5ArDNPJl9X6TX7Jel1yvDQAAAAAAAFlCQA4ABUTTMPodUYjYeZlqHQBaRVGDcZc3In9uwtfoRvWgombzsdxWpQ4W19+a7iDrzxWmXAcAAAAAAMgKAnIAKCC3mrADChE77xIDAJCOok2n3hdrI+eb8PW6yRsjN5iQu01YF4vnMtNdZB2St+uzBAAAAAAAAOrxB5s2bQrC8L70A+92CADQPEWbohSxW2WadQBIQ9bBVS07EWg9FHmmCV877y409dG0234bLIZab/wp050w5ToAAAAAAEDZICAHgAJytgk7nhCx815rAAD6T5mDcZdXTPeMJv9F5JOmMR4xYXvsbs+NfN50P1mH5Ey5DgAAAAAA0CkIyAGggJxhwk4nROy8jIgCgP5QtunUG+Uhk9+H/zTK/b7ITaZ/PGbCfWF3enHkS6Y4ZP2ATtafNwAAAAAAAOWAgBwACggBOWI+JCAHgEbJOpSqZV7CqjdNzxreebrHucWYj9aY5nku8jIT7he7R81wsN4UD43k9s+1k+blcwcAAADA5wPT83AstlddZwBoNwTkAFBA8tR5jFhmCcgBoC8IxvvHusg7Ik8z4TF3ypsinzat4d3I/zLha2D+/W9TfLKc0YJ7KAAAAMgDSyKvjzwv8hQT3rNge9V110Opj0aSmQG0GgJyACggBOSI+ZDOXQCoBdOpp+NV0xMsd2rq9XMi7zQ966K3A3W8nWXC18X8eWHkU6Y8ZP0QD+uSAwAAQBbofu98E96bYHaeG/mkAYDWQUAOAAWEgBwxHxKQA0A1sg6catkt4biLpt5bHnmb6VkL2j+nNP408grTswb6BtN+FL5fbcLjwPxY1CnV+4Ip1wEAAKBMPGHC+xHMj48ZAGgNBOQAUEAIyBHzIQE5ALgQjLcfTcH+cOStkddEXmIavy/SeuBqtzTyJZPduneLTHhsmL1lmFK9HgrJs5z1gnsqAAAA6AQbI8804b0I5sfTI982AJAeAnIAKCCNdgQjYnulMxcABNOpZ486ujQt+yrTM1L7tcg3Tc/I8PedenlBo+IV2PvvGXZevQ96P6CHLB/00ecoU64DAABAO8nyXgcbVw8VA0BaCMgBoIAQkCPmQwJyAMhjB4s+m8oUjncrGsF+T+QpJnwPsf3quuv6ZzWTQJ7J+nONzy8AAABoF5ea8N4D86eW1wKAtBCQA0ABISBHzIcE5ADlJesAqZYES92HRr1runj/vcT2qeut6w61yXrKdT7LAAAAoNVoZin/ngPzq2YJA4A0EJADQAEhIEfMhwTkAOWDYBzahdZW/5kJ31tsnbq+us7QOFmG5Ey5DgAAAK1krQnvNzC/agktAEgDATkAFBACcsR8SEAOUC7yGI4znXqx0NrpvzLh+4zp1XXV9YX+k/VnHyE5AAAAtIKXTHifgfmVGZ8A0kJADgAFhIAcMR8SkAOUg6zDoVoSjBeXZyJvNOF7jv1X11HXE9KhkNq/tp2UzzsAAABICwF5d0lADpAWAnIAKCAE5Ij5kIAcoNgQjEPWqFPo15GnmPDvAGur66XrRqdaa8l6XXLuuwAAACANBOTdJffyAGkhIAeAAkJAjpgP6agFKC55DMeZTr28aP29OyLPNOHfBfaq66PrxHqF7SXLz0fWJQcAAIBmISDvLgnIAdJCQA4ABYSAHDEfEpADFI8sg596EoyDeD3ynsgLTPg3UmZ1PXRddH2gM2T9WclnIgAAAPQXAvLukoAcIC0E5ABQQFobkG/adJK59NK9zahRW5utt/6k2WyzvzMDB37e7LPPV8zll+9jNm48MWjj+sIL08zcuSPNwQdvb7761Y+bLbb4BzN69DbmjDO+YxYuHB99rp4ctLFu2HCCOeaYXc3MmbuYWbN2C8qL4IIFY+Nz6+s6yuXLJ8fXQt5005igPO/q/Z44cTuz006fi/+Ottvu02b48C3NSSftYdasOSao7/rBByeZu+6aENcdOvRL5rOf/Ruz++5fMFOn/mv897Vq1bSgjeu55w6rXLsXX5welLdHAnKA4pB12FNLQiCoxoeRT0XebMo7qlznrfPXddD1gM6T9ZTrfD4CAABAfyAg7y4JyAHSQkAOAAWkdQH5009PiUPxP/iDP6jpgAGfCtpZb7xxdFDfd/DgL9YMR199dWairl9eBA899Jvxuel//TJfheL2Wowfv21Qnlf1oMO++24VvPe+69YdF7SVb745O/478ev7XnnlyKCtdfPN/3el3v33HxyUt0cCcoBikMdwnOnUoVHeilwceY0J/46KqM5T56vzhnyQZUjOlOsAAADQKATk3SUBOUBaCMgBoIC0JiDXiGaN9nYDyL//+78wn/jEXyW2TZ48MGgrNULcDzBrqf3ee+/EYB9lCsjlzTcfEJS7dmtArlHj/nuuEeDuf+tBDL+d1AwE/t9hPceN+4Z57705wX4IyKF/bIh8OPK6yAtNz+fq6Vg6TzXhv+s8qOPyj7UZz4mcG3mn6ekMguKzJvK+yP804d9VN3uF6TkvnR/kk6wfNCIkBwAAgL4gIO8uCcgB0kJADgAFpDUB+QUXDE8EjzfcMLpS9sYbs8xVV+0bh5oPP3xo0FZ13bY77PAZc+utPzTr1x9n3n77ePOb3xwcT43t1lFI/s47JyT2U7aA/C//8k/qTv/djQH5E08cmXgPNWX+++/3BNjvvnuiWbTowHjK9LPOGhq0/eijk+Np+d32p522p3nssSPiKdeffXaqmT//B/F07W6davsiIIfGedDkNxhFbKc3mJ6HQ6AcrI9cGvlr0/MgkP/3kGd/Ebkw8neGkeLdhEJq/73spMy6AQAAAPUgIO8uCcgB0kJADgAFpDUBuTsl9owZuwTltfRDTa0T7QffVjfwlaefvmeivGwBuRw0aLN43Xe/nuzGgPyii0ZUjllrjvvl9fSn6K81wl4PbAwZsnmlnh620IMYbh0CcmiIjxaa8H1ELJOXRm40UEbWRv428nqTv3XLL4hcEPmkIRAvAllPuQ4AAABQDQLy7pKAHCAtBOQAUEBaE5BrbXEbKM6bt19QXks/9K61rrR1+vRBlboaQa31pm1ZOwJyO/JYPvfcj4NyV414t3UVwrply5dPjkfFX3PN/ubBB3+UOO7+6Afk8sQTBwf1ZH8C8tWrZ8THpzYrVkyJvr9ODupY9QDDK6/MTJyDrtOjjx5WOb+33mru/I4++t8qx6yp1v3yWvoPWmjGAb+Oq/7O3Gt48sl7JMoJyKFvNBLRfw8Ry+ivDEBPEP2C6RllvijyRtMzcrtd4flZpmfqd/39/Xfk46ank5IHNooJU64DAABA3iAg7y4JyAHSQkAOAAWkNQG5pr22gWJ/RpDvuus/V9qNHr1NUO6rKcXdYFNTZtuydgTkL72UfL2lSw8P6lgHD/5ipd755w+Pt6m+pox392EdPnzLOEz291PPagG5rBbiNhKQa9S1v068dcqUgVXX5542rechBQXSCqbtf/tqXXmV++3reeaZQyvt+zOCXGvSu6+tkN+v43vIITtU6isQd8sIyKFvtIat/x4iltVXDUBtFFqrA/HpyCciF0c+YHqC9Nsib468zvR8D+p/9d/arnLVU321U3tC8PKSdUjOlOsAAADgQkDeXRKQA6SFgBwACkhrAnJ3ZLfUaGK/TjU1vbVtc8cd44LyarpBtDvNejsCcqkg2+7zqKN2DsrlypVHJ15bI8i1drYbtFbz2mtHBfuqpxuQjxv3jcr/V8j9+uvJUev1AnIF14cdtmNwPL5aN/7ll2ck2rqjvBVi+21cFZL751BPjWJ322vKdb9ONS++eK9KGz2Q4JdXU2vbu6/lhvkE5FCfdSZ8/xDLLMERAHQCjeRmynUAAADIAwTk3SUBOUBaCMgBoIC0JiDXiF0/HD322F2D0NZV6z679TU1uV+nmpp627bRKGC7vV0B+Z13jq/sU4G+gm+/zgknfKtSZ9KkHeNtZ53VOxpannrqt82iRQeayy77fmU6cH8q9r50A3JNZ65R3va/99nnK4m69QLyq67aN3FsEyZsa+65Z6J55JFDzdlnfzdRNmZMcmS/G5BLXRO913fdNcHccMPoxFTnKqu1pnw1tZ76Zz/7N4n977//18zTT9cfEe4ek3+8tfRnI9C08baMgBzqo5GM/vuHWGavNgAAnSPrkJwp1wEAAICAvLskIAdICwE5ABSQ1gTk0h3Fa9U64cccs2vVtcWXLTs8UXfDhsaC1OOP7w2jhwzZvLK9XQG5RhZvttnfVfar4Nkt13rd7jTlWm9c20eN2rqyzQ+otWa3AmX/tfrSD8g1BbobSF9yyV6VurUCcl1n93hnz949eB0F5bZculPLu2G0rsvzzx+daKu1yfW+2zr33XdQsP96+q9t1RT8Tz55VFBfjhjRO8q/0Sn+9R64+3enuycgh/rcb8L3D7HMXmwAADoLU64DAABAlhCQd5cE5ABpISAHgALSuoBc3nzzAcEIYKnAVCOn3br+dNr+vmp5wQXDK2222OIfKtvbFZDLc88dVtmvplx3yxYu7B1h7gb2bpCsqcrffffEYL/91Q/Ite2JJ45MnLcNkWsF5Gpnt2uE98aN1Y/LDZ21zrjd7p6X/55a3YcDNFrdL+/Lxx8/wuy00+cS52XV6/sPU7hTvWsdc39/tXSDfK3HbrcTkEN9tC6u//4hltlzDABA59FIbv/zqJMSkgMAAJSX9gTk6mPUzJnqE9OgFPV3qR/ypJP2MGvWHBPUd9UsleoLVB/ewIGfj9urb08DY9TnpQEtfhur+tk0wGnmzF3MrFm7BeX11MyRtq0GNfnl6qc74oid4vPSrI+aKVKDYObMGRwflwYaaUZJv11rJSAHSAsBOQAUkNYG5FI3VeecMywxStmqGzpbzx8p3GiArBso22bXXf+5sr2dAbluMt1967VsmW7s7HaF/nb7Qw8dkmijkd79HU3tWy0gl7redrseGlDoXSsgd6eDP/LI6muqy7lzR1bq7b33lyvbGwnINYrb1nHXie+PGrmvc6i2zrkeRNAIcFt36NAvVcp0U+7vq5q6+Xb36b432QTkPzc9N+yvRW4wkGfuNuH7h1hmCcgBys0HkesjX8nIy034udQp9dqPmvCYsHtdF7nJAAAA1Ke1Abn6Uvfdd6ug/8u32gydUoNlqg1YclX54sWTgrYyTZ/qSy8llzD0y90+tlqqL1P9xH7b1klADpAWAnIAKCCtD8itCrzPOOM7iVG68tFHD4vLX3vt2MT25577cbCPah500PaVNlo7225PczPXiFrv3O5b64trm25M7TY9manp1t02bphvVeB7990HBvtvxFoBucJkhca2TPVqBeTu6G4F6/5rWDUFvK2ncN9ubyQgVyhu6/zkJ0OC8v6qc3GnuZc/+9l3K+WHHbZjZft//MfXg/bVfPnlGYn9aU1yW5ZNQF7Nn5meqYvnRs6PXGB6wtkHI5dFPm16fpSpU/pdA52CgBwxKQE5QPnQw3z/HfkLE34mIBbByyLvM9xjAwBAdVobkGt0tdtHJf3AW7NT+u2k+u/8vtd6nn/+8GAfafpUWxGQW6dPHxQvJ+nvI70E5ABpISAHgALSvoDcqqcYNZW3vdlReGvL3JugRtfk3nPPf6m0OfnkPSrb09zMNaKm/bb7tlO7n3fe9yrbNA2730bOn/+D4KZWjh07IDEKuhFrBeRy9eoZiRtiTVtk/78bkLtBeq2AW+qpUltP75/d3khArumTbJ1WBORSU0HtsMNnKvvVDbYt0wMLdrumofLbVvPhh5MzGLgPN+QnIO+vp0WeG3lp5FWRN0beZnqmAH0k8onI5yNfjXzLMDqmWQjIEZMSkAOUi8dNJ35DIObDsyJ/ZwAAAJK0LiD3l07UzIjvv98TEmvw0aJFB8YzJ9rBOq5+OK3+Oy11+MIL0+J9LFt2eLxUpR+g+yPJ0/Sp+sfgl7t9bOo7Vf+qZt3UzJWaDt4/Nk3V7u8jvQTkAGkhIAeAAtKZzi13ym2tg2O3K2i22/W0pN/O1x2xLefN269SluZmrlEHDdqssn/dTGpktf6/bubqreWjIPzyy/dJPCggNcLcr1vPegG5dEeNu7oBuUZY2+1nn907Ctt3wYKxlXoDBnyqsj2rgFzedlty3Xr7gIHWLHK3r1o1LWjrq5twW1+j092y7g3Im/GnkeebnilCr4m8OXJh5P2mZ8rQpwxTv/sQkCMmJSAHKA9PmvAzALEMLjcAAAC9tC4gv+iiEZU+KM066ZfXU2t727Za6vLpp6cEdaQ/BbsGH7nlafpU+xOQV+tj04yO7mAeqeP166WTgBwgLQTkAFBAOhOQu2GrG0bOmrVb4gbo7bePD9q6nnrqtxP1n3pqcqUszc1co2o0uN2/uza2pvj261ZTAb+7XrY7dXkj9hWQy2rTMrkB+Ykn9k77PnnywKC9VeG5radp2e32LAPyd945IXFedlr011+flXji9PjjvxW09ffj1tc68m55XzfvWPap3wnIEZMSkAOUA808o3/v/mcAYhnUA6UAAACW1gXkbj9bI4OHrP7Sgep79eu43nprctCJ29+Vpk81bUAuNdrdDfDdwVWtkYAcIC0E5ABQQDoTkGsKHXuT44bC/ohwPfnot7VqjXJ3BPawYVskytPczDWqRiz7o8Dl8uW9QX1fanSz27aR0c7WRgJyhb/+et1uQH7ttaMq2/V0abVp3rWmuTu6/4QTegPnLANyTQ3lntf69cdVytxZChR+r1hR/alZv6589NHDEuWN3LxjfzzV9HSo/9zUnvr9uchXIt+M/MDkGwJyxKQE5ADl4Lcm/PePWCaXGgAAgB5aF5C7fWj9GUGuvjrbTv17mzaF/Xuu6utz+7vcJTDT9Km2IiCX6ud092MHxbRGAnKAtBCQA0ABaU1Arpusfffdylx//Q+Mu5az1Noy7mhdraXjlmsUs3sDNHv27sH+FWD6wfSDD/4oUSfNzVx/dEdgS00D5NeRujGdNGnHIDzXubjt/fJ6NhKQy0ceSa6v7QbkWr9IN862TDfifnt3bXXp3pS2OyDX6G+1V9DvbtfDFO6ofa1H7pb777/OUWsuuXX0nhx88PaJetXev0Zv3rGd2qnfL4u8OvJXkXdE3he52PSsBbkyck3k25Efms5BQI6YlIAcoBxoKRb/3z9imbzeAAAA9NC6gNwf2a0p1/061VQ/rG3j97XWUn10to07zbrfp+a3q2erAnL1Lbv9x3feOT6o07wE5ABpISAHgALSmoD8nnsmVm5gNCWOpqzWKN199vlK4iZJNzoaCe621U2YP+JZYfiYMdvEUwvZdb5djzxy5+AY/Ju5rbf+ZJ+uXXtssJ++XL06OYWRbmT9OvL228dV6uhcFCbrRtQdma3z9B8oqGejAbk86aQ9KnXdgFzOnTsycQ5jxw6Ip4/XGub+FO3HHpu8yW5nQP7WW7Mr7fS3ounotVb4hAnbJm6SpdYd99ufdVbv61p32ulz5qijdo5v/P196PpXW9fIvXnX37P/d+OrtdH9fWAWnhV5UeQVkddF/jryrsgHTM+InxWRL0aui9xomoeAHDEpATlAOTjbhP/+Ecsk06wDAICldQG5BnO404tL9avWWk/cOmDApyr1a/XP+V511b6VNur7stv9PlW/XT1bFZBLtw9Yg3f88uYlIAdICwE5ABSQ1gTkCjDdm6FaLlxY/ek/jQ7W+jJ+/Woed9xuQXvp38w1Yn+mN3fVjaraK9jXE45+uRw37hvB6/nqxtRvV8/+BOS6wVY4rLp+QK5Q3h+5X82RI7cKRnK3MyB3b9TrqfDfb9vffejHxzPPTA3aS/fmvRGvvHJksA/sBk8xPZ39l0ReaXpGBf1X5D2RD0c+HvmsCad+JyBHTEpADlB89B3o/9tHLJu6dwQAABCtC8ilPxOkdfTobaoO7JDuIJBGB264A5yk7dP0+1T9dvVsZUA+YsSWlbruFPDpJSAHSAsBOQAUkNYE5I89dkQ8Stq9IXJVWPzyyzOCdq6a+nvKlIGJEdbVrBVGvvbasUHdvtRNnL+fRrzvvoPi9vWeZtRU6hqZ7b+m1KjjWiPP66k12u0+NOLbL/d9/vmj4xtmPyC3LlgwtuoIfQX/l1yyV1BfzpzZu373FVf8e1Auzz77u5U6p522Z1BeyzVrjomnhfJHelsHDdos/tHgt/O9996J8dTptfYj9aSt/mb8trKvv0HfefP2C/aBRfV006rPTcTiSEAOUHw084r/bx+xjG4yAAAArQ7IpZaotANdfDVYZcOG3gEs7703J1HeV/BsfeKJIxPtNGBJ2/MSkI8atXWlrvpA/fLmJSAHSAsBOQAUkNYGPRptrCcbNb34HXeMMytWTDEffHBSUK8v33xzdhxy3nzzAfFU2n7QqZskhdRvvDEraNsp7777wGB0dTV1/itXHh2fj0Jze/PZKfV+9LXOuW6slyw5zDz00CENnVO71TV79tmp5q67JsQPEixbdnhTx6UnYXXuehDgllsOCNYf1yjy664bFf+d9meqe0REdCUgByg+75rw3z5iGSUgBwAA0fqAXKofS8sfbrfdpxP9V1IDQdw+VrdMfbD+vqppB/xYNfuktuclIHcfENDgG7+8eQnIAdJCQA4ABaS1AXm7VMDp3my5fuITfxWP+NU0PH47RFfd+OsHhf83ZNVNu/6WFMz7bRERsZYE5ADFh4AcsUcCcgAAEO0JyF0VlGuGR7ff6mc/6w2N3dkPL798n6B9Na++er9KGw0asdvzEpCrj9fW1aApv7x5CcgB0kJADgAFpDsCcrl06eFVpwO3Kvj02yD66mnb00/fM/j7cdVIer8dIiLWkoAcoPgQkCP2SEAOAACi/QG51AybO+zwmUp/lcJmWzZ06Jcq2487bregbTXd/rDdd/9CZXseAnJ/6Uwt5+nXaV4CcoC0EJADQAHpnoDces89E81BB20fhOVHHbVzUBexlqtXz4jXWdfMA/4U/uvXd3YafETE7paAHKD4EJAj9khADgAAojMBubztth8m+qzsNOtaftJu00hzTc/ut/V1p26fMGHbyvY8BOSzZu2W2M/bbx8f1GleAnKAtBCQA0AB6b6A3FU3hXrCUOtV63/9csRG1d/SmjXH9Llee/s8PfKsKtux6J555tD4h+3EiduZMWO2Mfvv/zUzevQ2Zs6cwebGG0fHf5N2XbAyuGLFlPiBp8GDvxj/yN9660/GM4QceeTO5oknjgzqYx4kIAcoPgTkiD0SkAMAgOhcQP7OOyckguMXX5web7/77gMT2zWgyG/rqtkS3frz5u1XKcs6IH/rrdmJwSvqG/HrpJOAHCAtBOQAUEC6OyBHLI6/ND18GPl25JrIlZG/i1wceZ8xH90e/e9NkfMifxF5nukJ1v19YTfp/lispdYWe+SRQ4O2rXbt2mwfNDr55D2Cc/ddsGBs0M6qB6UaeWoeWy0BOUDxISBH7JGAHAAAROcC8mXLDk/8JnZnPXRHhGsqdoXpfnu5ceOJ8ZTqtq76IdwH8bMMyNetO87suus/J/axatW0oF46CcgB0kJADgAFhIAcMR/agLwZPoh8M3J15LORj0c+HLko8r8ir4+8MvKSyLMjTzHh62NWNhKQW6dPH2Tee29OsI80vv/+HHPBBcPjkdoK4v3yTnnVVfsG5/vZz/5NsE0/nv22Cs333PNf4nJmE8lCAnKA4kNAjtgjATkAAIjWBuTHH/+teHY5P+DW718/BHfLb775gMTvZc3E9u67Jybq6Deyu465dEePyywCch2Xfstr5ji3/YwZuwT7SC8BOUBaCMgBoIAQkCPmwzQBeTNsjFwX+WLkisilkQ9E3hX568jrIq+IvMgw9Xt7dX8snnvuMPP440fEU5/NnTvSTJs2KDHNmJw5s7U/FjU9m913VgG5Rn3//d//ReU4FHbb0ex6ql1Tqx966DfNyJFbBW2l+4OagDwLCcgBig8BOWKPBOQAACBaF5BrenH7e1a//4cO/VLcF6A1wv3+AC3D5rbVb+nhw7dM1FGbYcO2iJdy22mnzyXK5KBBmwXLuPkBuR6g70v7m70/AbmOTQ/Cf+ITfxUcl9x3363i6+HvI70E5ABpISAHgAJCQI6YDzsdkPeXOlO/mzsifxV5deRlkedH/tSE54jVrPU0tVUBttbgdn80PvnkUUG9Zs1DQK7zcc/PnTKuEcsYkH/wQZ7WpScgByg+BOSIPRKQAwCAaF1AXm02tWqedNIeQVupsFthuF+/mkcdtXPV35J+QN6Idhr0/gTktdQD8xoN77dtnQTkAGkhIAeAAkJAjpgP8x6QN4Od+v2VyOcin4h8JPLeyNsib4y8KvJS0xOwnWrC61J8+wrIpaZBd6cbHzjw80EdqR/GK1ZMMTfdNCaeMu2eeyaat98+PqhnVRCttc3tfhU0v/LKzIrVpjNv5nX6UtOqucfgl9dS08/pON2nzx977IjEOfhtXPVk+n33HWSuuWZ/s2TJYcFUdK56D+w+3WnvVq+eYa6//gfm1lt/aJ56anLQTp0Fd9wxLu70UJ2+jsn1jTdmmd/85uC47e23jzMrVx4dbz/rrKHmq1/9eNyJ4bexair+Rx89LD63e++d2K/X7b8E5ADFh4AcsUcCcgAAEK0LyNesOcYcc8yuwWhxq0Z863e738734ov3CqZSl9qv9qHfrX4bqx4099v1pX7rqq1+a7rb/X3rQXy/rX73a+S7lpG7/PJ94t++frvWSkAOkBYCcgAoIATkiPmwiAF5M6gDfr3p+bH5dOSyyAcj745cEDk/cm7kxZE/M+F17D4bCcilgk73B6VGftsyBaeagtz/0WnVlOXPP98TrroqZPXruip4dus3+zp96Yb0stEp1fT0u38Mvs899+OgnaZsHzDgU0FdqensqoXJ8+f/oFLn4IO3N0uXHh780Feng+rq+E899ds1p41TOz1U4L+G9c03Z5tDDtkhaCfdDg91KvhP/6vtuHHfCNpJHY/Ow3+99BKQAxQfAnLEHgnIAQBAtC4gt+q33bPPTjV33TUhfrh62bLDgzXJG1EPS+s3th7U1u9hTcPu1ymfBOQAaSEgB4ACQkCOmA8JyJtnQ+RrpucHz/LIJZH3m26Z+r3RgFw/at0nyu+8c3ylzF9zrJpqa9cIs/Y3IG/2dfry9ddnJfYxatTWwZpo1TzyyP4H5Frb3a/jq+ndNOrabXfddaMq5YMHfzGxZrrVPpF/9tnfDcqq6b6HVoXr7pTxtdR11sh7t61GjNcK5V21rltrO0kIyAGKDwE5Yo8E5AAAIFofkGM7JSAHSAsBOQAUEAJyxHxIQN45+jP1+7mRp5nw/WqdjQbk0g20zzvve5XtmibcbtfoZpUpCJ40acdEMKoyd38PPPCjeDozW65wVU+qW7Vft36zr9OIY8Zsk9iHRngvWnRgUM91+fLJ8XG6YbWdytyqp+dtfYXl7mtoqnqtc6Zp2a++er9EMK3/r2nVbVs3ILdqxPwttxwQT2Wn0NmO5tYobvsww957f9mcdtqe8XHNmTM48ZCDRpL7I8DHjh1QKVfdyy77frxGu17HDb/1d/Phh70ht6aHd/+WNCX/JZfsFQf9mgpfDx24x37ppXsH17N5CcgBig8BOWKPBOQAALAycrEJvyMwvxKQA6SFgBwACggBOWI+JCDPN++Z3qnfbzDh+9e8/QnIR4zoHcGtqc7dslNOGVJZo9pVwa8buPrlmqrdliuw9ct9m32dvtR65/6U5VIhttbf9uu7usG21k7zy6377POVSj2NAnfDc3sM7lrv7kMIfkC+//5fSwTUvlqb3X/AQPohvdY+t2UbN56YKNOUeG5brfvulrv715p1drumeq82Fd/55w+v1NF75D4AkE4CcoDiU86A/Omnp8QPY73wwrSgDMsqATkAQDlRKC7Vd+N/N2D+JSAHSAsBOQAUEAJyxHxIQN49aD10//1r3v4E5O4o4COO2Ckor6am0nZHHisEdsv7G5DXsq/XaUSF2+PHb1vZh+uwYVuYVauqBxSNBOSrV89I7E/Tkft15DnnDKvU0Sh2u90PyLU/v22jjh7dO1r+xhtHV7ZrRL/drnPy20mtkW7raHS5tinod4/tpZd616d31Xu09dafrNTTWux+neYkIAcoPp0JyM86a2j8Xedvz8K33z6+8nnpLznSqHqQ6qKLRphDDtnBPPTQIUE5dqME5AAA5YJQvBgSkAOkhYAcAAoIATliPiQg7x6yC8h32ulzlbpa59ovVwCqKcNnztwlHi293Xafjkc6u+Hp4sWTEm2aCcibeZ3+qPDaHe3tBhTVwt9GAnJNNW7raKp6v9yqUYK2njsS3g3INardb1fLRx451Jx44uB4Cnm9fwq43VHqCoNs3Xvu6T1GXVN/X1LTuvttly07PHHMGr1eS+3X1r322lHB/puTgByg+LQ/INeSE3bJjGeemRqUd9pWBOSaAcXuQ+fmL6th1awfGzaEM3/kybVrq3+/lk8CcgCA4kMoXjwJyAHSQkAOAAWEgBwxHxKQdw/ZBeTuCG0F1G7ZXXdNSIwOrqU/7Xd/A/JmX6cZly493Oy66z8n9quR5H69RgJyrblt62iqer/cqmnH3ddbv75nJLwbkI8b942gna/CHXdK/FqedNIelTYKSOx2Bd1+WKL/dttqXXJtV/Dt77cR7Qj09BKQAxSf9gfkmlHDfj7NmrVbUN5pWxGQu98d+lzftCkZkOsBpwkTemZOueGG3hlF8qK+Ey+4YHj8vd/IPUI5JCAHACgmhOLFloAcIC0E5ABQQAjIEfMhAXn3kE1AruDXDTcfe+yISpnCcrdMnfD77ruVmTFjl7jj3Y7Ik35w3Z+APM3rNKtGq0+atGPidf3pzRsJyE87bc9KHY3m9std3dfS2rPa5oYcBx+8fdDG9dlnpyauhdTI7ylTBsZT47trrbsBudTodFs2ffqgRNncuSMT+7Sj6efMGZzYrhHqjdi66X4JyAGKT/sD8iFDNk98junz36/TSVsRkGsJjIMO2j6eueTKK0cG5RMnbld5jTwG5P25RyiPBOQAAMWBULw8EpADpIWAHAAKCAE5Yj4kIO8esgnINZrODUHVca/tb701Ow6q7faRI7cKQmKNurblfnDdaOd32tdJ45tvzk6c+913H5gobyQgv/zyfSp1hg+vPYLcDUSkRnVre38C8kGDNqvU1TV98smjEuWaGt2W+wG5H4IrWFe474Yoctq03vBcI8Hd+v7xtF8CcoDi096A/Pnnj058xkktO+HX66StCMj7koC8GyUgBwDobgjFyykBOUBaCMgBoHD86lfrIl9DxIy9884X/X+ekFs6H5D74bQ7AvoXv+gNRzUFqqZD9dvXC67dzm8FzX7bVr1OWgcM+FRl31ddtW+izA3IX355RtBWumuQ6/j9cuuSJYdV6mkUuN3eaED+9NNTKvWk1jT369QLyOVNN41J7MP3kEN2qAT3UiPBbZlGXfr7a78E5ADFp70B+THH7Bp81vW1nIWWwHjllZmxdpvW+H7ggR+Za67ZP/5O1QNWfjupkd2aiWX+/B/ES4esW9eznIZrrYBc35v6nL7jjnGJ13bVcdhjs+q73C/XLCz2NS65ZK9EfR2jv1/rhx+eHH/fKFS/9dYfmuee+3G8za9Xy0bOX9f3kUcOrRyfvmvd4/Pb6AE1bV+z5phgX1Z9d9U6v2r71Xug89P0+4sXT6q6hnvaa9F/CcgBALoPQnEkIAdICwE5ABSO+fPfNvPmvYeIGUtA3k10NiBXR7G/DveqVb2hq6bhttuPO676mq31gmsFyrZMIbzftlWvk0aF8e6U5f76625A/uijhwXtpTrdbR351FM9U6f7utO5ayS43d5oQK7OeVtvp50+F5TLvgJyvZa73rxVfwcKK/z6Cl3cego8/DrtlYAcoPi0LyBX6Gk/4/U95D4Q5j4M5Ot+f+q77Kijdk60lXo4ym3z8MOHJh64ctV3ycUX71UJYf2AfOHC8fFDSH67vff+chwmu69zyy3JJUmkwnBb3teDUFIzn/jnrOBX3yH+eVq15Ea1B9iaOX9NC+/XcfVH1bvHVCugnjr1Xyt13PNTqO4exxtvzEpMuW+1s+fItNeieQnIAQC6A0JxdCUgB0gLATkAFA4CcsR8SEDeTXQmINdIrAULxibCX6n1vt3255wzrFKmANXfv0ZUue01CsstVwezW75oUXL68la9Tl8qLDjssB3jkXnudnXUH3roNxP7dkfhSbcTffbs3YN9W92ReiNGbBl0nLsjsf1zaDQgX7r08Eo9ddr74Y6mW3cDFq1J7pa7U8GfffZ3zbJlh8cPSWgt3lqBg9Qat7adgiZ/Wnf57rsnxvv0R/2ll4AcoPi0LyDXZ639/FLIPX78tpX/1rITfn2r+/2pmVXs/7e6U4Lr81NLU/h1qqkR1WrjL7lRT4XJmzb1jm5uR0CuEH7gwM8H9Xx1XfzlRpo5/3YE5FOmDKzUcc/v1VdnJvbrLlVi1QNsrbgW6SUgBwDILx0MxT/6RbgNcywBOUBaCMgBoHDMnx8GdYjYee+88wP/nyfklvYF5OpcVnhabfSwVOe6Hw5rNJhbR4GrRlirc94PlqW7drXV74hW0KB1rdUZfeqp327Z69TTPQb9/yOP3DkOzP0HBLTdb3vCCd9K1Nl99y/EU9Uee+yuienon3lmaqKeOtd1nhr17e/DH/3daECuKWPdkGDo0C9F/8b3i6fi1Whxf6Tbdtt92ij8tu21hrgtGzVq6/g912g/207h9+DBXwzWYdffhf93o/dF4ZJeXw8O2GBe2/3jTicBOUDxaV9Ars80+7mlWTLcmTiqPZBldb8/pT4n9RCQ2uv769prR1XqXnjhiERdfc/o818Ppl199X6Vh4zcELtaQK7P6Cuu+Pf4M9idcURqf7atZno5//zhia5sickAAIAASURBVIeX3H0rtNVx6vvKlmumFm2zrl49I3G+Y8cOSLyeRkjru0X6U9Tr+8Nt28z5a6p696Etfce4x+fPFNOqgNyq7399f2lWlP33/5pZvrx35pc01yK9BOQAAPmig6F4/DpSr/lSlXLMrwTkAGkhIAeAwkFAjpgPCci7ifYF5LVUKOpPK+6qdVr9Nq7+FO1+p7bW9fTbWHfY4TMte51aKkjw91VNBRPV1h9ViOGHw64bN55Yqav1y/1yX42a03qm7ms0GpBLhdL+Pl3dwFvahxAaPT6rG8ZIjYCvdx2s+nvy135NJwE5QPFpT0Cu9aLtZ5MCUW3zHzRylxVx9b8/lyypvcSGuz+FtO5ob+sLL0xLrFnuB+Q/+cmQoI07ZbiCfr9cga0td8Nn68SJ21XKNROLX269/fbe/egz/Pnnjw7qaIkR93j1YJu2N3v+UrO62HbuiPxqtjIg13vrT1tvTXMtWiMBOQBA9mQVirsQkHeXBOQAaSEgB4DCsWLFJkTMidAttDYgV4ez24krFRIMH75lPJpMHchai9Nv56qps6tNnaoOZk3jqjpaN9xuv/TSvYN93Hnn+MQ63+4+Wvk61dR+L7poRDBa3KrtCqjdkda+Clk0Gttvqw77FSuSYbdGobmj9qw6f03vq+Px9+9OAdzICGyF5P5ocYXXGqmuYELT59vt7ug2Tft+/PHfqkwdqzb6/xMmbBuPRvf36U8Tr5HkOj6/ntx660/Go+r9WQjSS0AOUHzaE5C7o3312We363PRbj/55D2CdtINyCdPHhiUV3sNfZ9Ue9Cqmv4a5H65VKhs62iWDr+8VQG5O8uKRlT75VZ9h9l6F1wwPN7W7PnLrALyeg8FprkWrZF7dgCAbOhkKC6rheIuBOTdJQE5QFoIyAEAAABKT2sD8laq9a41ilij6NxR01atPa1RVLUCd3VoP/XUZHPvvRONpiOvFhS34nVqqQD8pZemm9/85uA4QNZr9He9bHXm33PPxHgNbn8knK/OVyPFNdJ97dpWr1Has376448fEU9T+/rr4bXQ9dUoNwUsflkttR83hNAa5X4dq66FfS+rjRZsnQTkAMWn9QG5PiPdB7PcKbQVFtvtdmS5rxuQL1qUXHbCddiwLSr1tPyGX17LRgJyfY/YOtIvb1VA7n7u6+EzTT1eTXfq8UMO2SFu2+z5y6wCcv/hr1qv099r0RoJyAEAOkfeQnEXAvLukoAcIC0E5AAAAAClJ78BORZDjebfsOGEYLtVU7TbTn89ROCXd14CcoDi0/qA3A3BNcOFW6YHsdzAVA8a+e3dgLzeg0Ya2W3rac1tv7yWjQTk0g1s/bJWBOR6cMy9Fo06Zsw2cftmz19mEZBXG4lvTXstWiMBOQBAe7GheKeC8f6E4i4E5N0lATlAWgjIAQAAAEoPATm2z7vumhB35mtU5YUXjojDCW3XaPyFC8cnRsTJvkbJd0YCcoDi0/qAXGt228+ys84aGpSPGLFlpfzgg7cPyt2AfPXqGUG59Ed4r1wZrlddy7wE5JrlxD0HBciNeM45w1Kdv8wiIK81Y4BMcy38fTUvATkAQOvpllDchYC8uyQgB0gLATkAAABA6SEgx/aoQEEd+W7nv6y2nrg87bQ9g31kIwE5QPFpbUD+7LNTE59nQ4ZsbiZM2DahG4Drc9Bf0qORgFy607hr+Q+/vJZ5Cci1TIatI7UciV+nns2ev8xbQJ72WrRGAnIAgNbQjaG4CwF5d0lADpAWAnIAAACA0kNAju1RHf033jg6nmrYDQB8FUKcd973gvbZSUAOUHxaG5DPnLlL8NnWl9deOyqxj0YD8t13/0Kl3ty5I4PyWnY6IL/66v2Ccpl2FHiz5y/dgLxecC3d6+A/zGBNG5CnvRatkYAcAKB5uj0U72XdulfN7bevxC5xzZpX/LcQAPoJATkAAABA6SEgx/Z7770T4ymHx437htlpp8+ZoUO/ZCZN2tFcdtn3665Pno0E5ADFp3UB+fvvz0mMah4w4FPxdOvVVFhq6+25578k9tNoQH7kkTtX6n31qx83mzadFNSpZicC8oMO2r5SXm2aeauuka136KHfDMrr2ez5y5dfnlFpq/P0y13d92r58slB+QcfnGQGDvx8pU4zAblMcy1aIwE5AED/KE4o7qKAfN6897BLJCAHSA8BOQAAAEDpISBHTEpADlB8WheQX3/9DyoBp3zzzdlBHeuiRQcm6rpBeKMB+YoVUxL7OOqoneOQ3q+nB5PcEdadCMhPPfXblfJBgzYLyq0aXe6eQ63p2HVt/WnUmz1/6Y/Y1vvht7PqAQZbb+rUfw3K9bruvpoNyNNci9ZIQA4A0DcKqG0w7n+OtsPOhOIuBOTdJQE5QHoIyAEAAABKDwE5YlICcoDi07qA3J3ye599vhKUu2q0szva/Mwze0dZNxqQy+OP/1YiVNV62iedtIe57rpR8ZIVmqVD2xV2v/VWT2DfiYBcobR/XDrHM874jhk+fEvzyiszK3VHjNgyUVflF144Ig6CTzttz8robO1Do7Xd12nm/K0K7t22Y8ZsE89mollNFPDbetqPW2/8+G3jMPvYY3dNvFfWZgNymeZapJeAHACgOsUPxV1ee+2jIITF/LpmzYf+WwgA/YSAHAAAAKD0EJAjJiUgByg+rQnIn312aiLYrDX619WdhlyBp93en4D8vffmmAkTtk28di0vvnivuE0nAnKpcNc/BuvCheMr9dasOSZecsOvU83FiyclXqOZ87dqX34d6w47fKZST0F0tSDc9bOf/ZvK/08TkKe5FuklIAcA6KVcobgLAXl3SUAOkB4CcgAAAIDSQ0COmJSAHKD4tCYgP/nkPSrBpYLljRtPDOr4uiGztOtbKyy32xSY+u2quWDB2Hgdbj9ElQpcNaLajjh+550TKmXNBuR33TWhUjZq1NZBuX2dceO+ERyPrDbl+bnnDouPx6+rYHns2AHmued+HLyGtT/n73rnneMTI/mtCsTdeuvWHRePMHfr6PpoxPdjjx1hpk8fVNnunttrrx1bc5+1THstmpeAHADKTnlDcRcF5I89tgm7RAJygPQQkAMAAACUHgJyxKQE5ADFpzUBeV7UiOqlSw839913kFm58uiqoXCnff31WfHxPProYWbt2mPNRx+dHNTx699//8FGwfO77/b9oIFrM+evQPqppybH08I/88zUuq+pMh3XQw8d0tC+05rmWvTfKyPv/b35C2wAANoDoTgAQNkhIAcAAAAoPQTkiEkJyAGKT7ECcsTWqiCH0BwAikgWoTifowAAeYSAHAAAAKD0EJAjJiUgByg+BOSI/ZPQHAC6FUJxAAAIISAHAAAAKD0E5IhJCcgBig8BOWJrJDQHgDxCKA4AAPUhIAcAAAAoPQTkiEkJyAGKDwE5Yvt0R5sDAHQKQnEAAGgcAnIAAACA0kNAjpiUgByg+BCQI3ZWpmgHgHZAKA4AAM1BQA4AAABQegjIEZMSkAMUHwJyxOwlNAeAZuh0KG6DcQAAKBIE5AAAAAClh4AcMSkBOUDxISBHzKeE5gBQDUJxAABoLQTkAAAAAKWHgBwxKQE5QPEhIEfsLgnNAcoHoTgAALQPAnIAAACAkrNkybPm7ruXI2LFZ/x/JgBQOAjIEbtfRpsDFA9CcQAA6AwE5AAAAAAlRwH5vHnvIeLvvemm9f4/EwAoHATkiMWU0Byg+yAUBwCAzkNADgAAAFByCMgRkxKQA5QBAnLE8khoDpA/OhmKS0JxAABIQkAOAAAAUHKWLt0UBISIZfamm973/5kAQOEgIEcst0UIzXW/8lbkm4hd4pORV/xe/99kOyQUBwCA2hCQAwAAAJQcAnLEpATkAGWAgBwRq+kG53nkmcibI8834bEjIqE4AAA0CgE5AAAAQMlRQL54cWP+9rfro/99IvrfBzKx57V1DOGx5dPmrpXahfvqRl+I9c+vE/a8tn88jQsARYeAHLHHe0xnpznuRvMw2nxD5HwTHhsiEooDAEAzEJADAAAAQAN0eo04327t9Gj2muV11FKz6Hz8c+yURbuWANAaCMgRe3QfCtO9lg2Cm72HKYudDM31Hl1mwmNALLPd+vsQAADyAgE5AAAAANSBYDwdzV67bj7nehCUA0BeICBH7LGvWVMIzRu3XaH57SZ8LcQy2u2/DQEAIE8QkAMAAABAFQjGW4N/Xo1ahHOvB0E5AGQNATlij30F5LUgNG/cNKH5OybcH2KZLMrvQgAAyBsE5AAAAADgQDDeOnQe/vk1alkgKAeArCAgR+yx2YC8Gu5oc/91MKk72rwey0zYFrEs3moAAADaBQE5AAAAABiC8XZAQN44WXWkN9IxDQBF5P333zXXXfc2YulVv2B7YYr2xq02RTvTq2OZvcwAAAC0CwJyAAAAgFJDMN4+mg3IdU3KCkE5AHQGBeTz5r2HWHrbH5BXg9C8cX9WZRtiWTzbAAAAtAsCcgAAAIBSQjDefpoNe8sckFuavXZpJSgHKAsE5Ig9ZhOQV4PQHBF9f2oAAADaBQE5AAAAQKkgGO8czV5nAtpesgzKAaDIvP++CYJCxDL64Yf+v468QWiOWF4JyAEAoH0QkAMAAACUAoLxztPs9SacDSEoB4DWQkCO2GP+A/JqMNocsRwSkAMAQPsgIAcAAAAoNATj2eFfi0Yt6/VqBIJyAGgNCshXrvwQM/H6Jn319+2xlXZnQF4NQnPE4klADgAA7YOAHAAAAKCQEIxnj39NGrXs160vbOe3f906IUE5AEB6/M/WRuX7EfoLoTlid0tADgAA7YOAHAAAAKBQEIznA10D/9o0KjQGQTkAQHfS7H0Kn73QCgjNEbtHAnIAAGgfBOQAAAAAhYBgPF8QkHeOrEJySVgDANB/mr1f4TMX2okbnPt/e4iYjQTkAADQPgjIAQAAALoagvF80mznqq4nNEez17wVEtoAADROs5/XfNZCp2G0OWK2EpADAED7ICAHAAAA6EoIxvNNs+8NAXl6mg1eWiHhDQBA3zT7Oc13JOQBQnPEzklADgAA7YOAHAAAAKCrIBjvDpp9jwhYW0ezAUwr5H0EAKhNms9ngDxCaI7YHgnIAQCgfRCQAwAAAHQFBOPdRbPvFde49aQJYtJoO8oBACCJvuv8z8xGBegmCM0R00lADv+PvXuPtqos9P/vf+efGv3RyEYjG5U1rKiBZeGx0EQ6SEYcQg5kHlEEMzQwEFEguYMKZPpTM/P6TR1p3vB29MsxU0m/eP96RU+o27siivcLAj7f/Zn+nrmf+Txz7T3XXHOutfec79cYn1GseVlX19prfebzTAAoDwU5AABAv0YxPjD5j2PW8FiXh6IcAPoP/70ya4CBzh1t7r++CSHJUJADAMpDQQ4AANAvUYwPXK2MjOMxL1+nfpDW9fL8AsDH/PfIrOF9FFXEFO2EpIeCHABQHgpyAACAfoVifOBrpSBH+3SyKAeAuvPfG7OGv1FQF7Y0P8eE/x0QUpdQkAMAykNBDgAA0C9QjFdH3oJczwHaj6IcANov7988vHeibi434X8HhNQlFOQAgPJQkAMAAHQUxXj15C1cKcg7x47S8p+TdoSyB0Ad5X3P5T0TdVN8Qf7aa0vMokX7mjVrDg+W+bnssolm8eKRZuvWlcEym5tvnmqmTRtqrrji4GAZaW+2b19lzjtvgpkxYy9z770zguUDLxTkAIDyUJADAAB0BMV4deV9XinIO8+e/9N/btoRSh8AdZL3vZb3StRN8QW5ivEddtjBDBnyhWCZm48+WmV23PET0brr188Oliuvv740Wm7z2GPHBuuQ9kUHK9jnQs9dbwc2DIxQkAMAykNBDgAA0FYU49WX9/nlR//+g6IcAMqV9z2Wg8lQN8UX5KtW/TQuUZ9++rfBcpv7758Zr/eXv/xnsFx56aWFiYL84YePCdYh7cvq1ZPi5+KTn/wXs20bBTkAAI1QkAMAALQFxXh9+I991vD89D95C5wiQlEOoMr0mee/72UNUCfFF+QHHviduEQ97bSfBcttli/fL17v6KP3DpbbnHnm/mbw4M+Z+fNHBMtIe7NlywozffqeZrfdPm8uvfSgYPnACwU5AKA8FOQAAAClohivH/85yBqep/6LohwAikVBDmRTfEG+yy6fiYvvoUO/FCy30RTsWdYjpLxQkAMAykNBDgAAUAqK8XriB/9qoygHgOL473NZA9RJsQX5228vT0yJrjz//PxgvRdeWBCs55/P+pVXFpmNG3uyefPSYD9+3nprubnnnt+YK6442Nx77wzz3nsnBusoaft8550TzE03/cpcd91k88ADRwe3R/nwwxXmoYdmmSuvPMSsWzfdvPnmsmAdP3ab66+fEu1b08TrMn89P7ovug5dl6aj17/9ddxkuU+a8r6ra16UDz44KdiHzfvvnxSvp33qsXCfC0XPtb+dn6zPhxuNUn/wwY8f4zvumBZdl79OcaEgBwCUh4IcAACgUBTj9UZBXg8U5QDQOv/9LWv4Owd1UmxBftddRwXF9x//OC5Y7/zzfx6spxLZLlex6i/fccdPBPuxueSSg8zOO3862EYZNuwr5pZbjojX3bRpcbxMo91Vco8ePSjYTuWy3eb115eagw76brCOounfVWD7t0m5+upDU2+Xzt89bdrQ6Bzr/jZPPDHXDB/+1WAbRSPt3cep2fv09a/vGP//tOfF5ne/Gx2vpynzb7zxsGBfEyd+N9jOppnnw0bP+dSp3w/WV3ba6VPRY+lv03ooyAEA5aEgBwAAKATFOCRvcarnDwNP3ue71eh6KcoBDHT+e1vW8P6HOim2ID/33AlBualC1F9vzJhvButddNEv4uVZC/JXX11ixo79VrBuWuwIbI1Mt5epeB0xYpdgXfec6BrNrPX8dfycdVaycH7yybnBOn5efnlhYhsVy/46afGvK+t90vnc7b91HnH/8VQ++mhVYpr8tWt/nbkgz/N8KFkfY12nbp9/vflDQQ4AKA8FOQAAtbK1Oy93p6s7T5Aoz3TnNZMfxThceQtTCvKBLe/z3mooygEMZHn/fuJ9D3VSbEGuUdF+qam4RfC7754YLFdmzNgrXkdTep9zznhzxhlj4+VpBbk/qlsjkFevnhRNTf7nPx8QF/HnnTch3sYtk21UCF9++cHRKOVDDvme2bBhTnw7Bg36bLyeSlyV2I8+OtusWXN4MErbbqe4RbFGU+v2qGw+9dQx0X3xz7uubd19qeS2U7lfdtnEaH13+WOPHdv0fXrjjWWJddJGo2tac7tco+N1mabJP/vs8Wb69D3jZWkFeZ7nQ1O9u4+xHqsLLvh5dDs0Lf2kSUMS+9R+/OvNHwpyAEB5KMgBAKiF9d25zIRfOElP9OX7v7rznMmGYhxp8r4m+LG/GjpZlPN+AGCgyfueyWcm6qTYgnyPPb4YF5nHH/9v8f/XyHK7zg039IxGnj17WPz/ta2/P5WndrlfkOvc2m5xeu21k4PtFZXZ7r/9MlnlrKZQ97dTVArb9VSO69zp7vJt21aaCRN2jdc54IBvx8t0e+3ll156UGI7FdX33dczLfv27auikfZ2/QULRhh/pLTKepXSdh2VzXZZM/fJLbmPO26fYPmUKbvHy1VUu8v+/vep8TK/IM/7fCxePDLeRgcF6AAKfxv3edD09FnO4Z4tFOQAgPJQkAMAUGkfdme1Cb9okt6z1jRGMY7e5H1t8JxWS97Sp9VQGgEYSPK+VzLrCuqkuIJcBa5bYrrnxR458mvxekce+YP4cpXEmurb/nvLlmTx2VtBvtdeX46XaaSyf3saxS+TVdj769i4U43/4Q/7B8uVhx8+JrE/e+5y92CBmTN/GGzn5vbbe0Zt6/FQ8e6vo7z22pJ4PT3G9vJm7tMjj/TcXr9s1rnL3WV+Wd1bQZ7n+dDz7d7uF19MHoBgo4MFhgz5QryeO3q+tVCQAwDKQ0EOAEClFfeDSv3yD5NEMY4s/Octa3huqylv+dNqKMoBDAR53yMpyFEnxX2fe/zx4+IC0553fNSob8SX6fzUGiltR1ZrKm0Vn4cfvke8zgMPHJ3YZ6OCXNupwLXL3KnN+4pfJjcajewW/srmzekjshXdF7ueHSGtqdTd7TX9eFfXvGBbRecUt+sNH/7VaGr0RnH3uXHjomj7rPfJRtdh19U05vZyjRi3l8+fPyLYrlFBnvf58Mt6/766caeYv+qqScG+8oWCHABQHgpyAAAq6z4TfsEkzeUlQzGO5vjPX9bwHFeXntu8JVCroSgH0J/p/dF/38oaoC6KK8jd8taOmL744gPjy3TuaI0Yt/+eN+9H0ToamW0v86f0blSQa6pze7mi4t2/PY3ilskqtv3lNk88MTdezx2tnRZ3enRbOKuktufcdqNi+ckn5ya2b3Tu9r5iC/es98lGBbNdf9y4wfHl7qj3Z589PtiuUUGe9/nwC/+sueiiXwT7yhcKcgBAeSjIAQCorPNN+AWTNJezUi5rVyjGBx5+6EdvVFZTlANADz43gb4VV5DrvNm2wDz//I+Lbp1r2142evQgs3Tpj+N/23Nwr1376/gyFcXuPhsV5OvWTY8vz1IIu3HLZE2h7i+3uffeGfF6Ov+4v9zN2LHfitd1S36NQj/ppFGJ0dU255wzPl5PU9C7y3Sf+opuux0pnvU+2Wg79xzp2l4j3+2/dV51fxulUUGe9/lYsWJU0/db0XPj7ytfKMgBAOWhIAcAoJJeNeGXSzIwQjE+cOX9oZ+pYuuFohwAevjvU1nD30qoi+IKcnc69bvuOiq+XCOU7eUqmu3/alpuLXfPq63zb7v7bFSQawS2W6zafWVJ1jL56ad/G6/X1whyd+T1TTf9Klj++utLzZIlIxO3WbnjjmnR8ilTdo8vO+20nwXb95Ws98nNCSf8JN7mjDPGmuOO2yf+t86J7q+vNCrI8z4fGglut9Foe395+aEgBwCUh4IcAIBKetyEXy5J/w7F+MCXt/SkIK+nvK+XIkJRDqC/8N+fsoa/mVAXxRXk7ojkt99eHl+eNo22nV7dxhbnyvvvnxRf3qgg988P/txz84Pb0yhZy2T/Ot58c1mwjrJt28rM599ev352dJ123WOP3Se6/JRTes5XPnXq94Pt+krW++TmpZcWJrax92Hw4M8F69o0Ksj9xyrr8+GO0m9m5HlxoSAHAJSHghwAgEri/OMDJxTj1ZH3XPUU5PWi7zqvmo//u3+6OzeY8DXRrui6dRtIffNMd17pzlYDdEbez04O9EFdFFOQu2WrX3S+884JifJU8afIdqcot1OvK40KckWjze0ye87zLGmmTB406LPxuv750W2uuebQxH2z0543yiWXHBSvax+rNWsOT+wj7fzfvaWZ++RGJbd7vYrOFe+vZ9OoIFfyPB86kMK97quvPjRYp9xQkAMAykNBDgBAJd1pwi+XpH+FYrx6+JEfvfmf7lzZnZNN+BogpD/kL915wADtxWcn0LtiCnJNK25LzrTzVx944Hfi5e706jaLF/dMP37uuRPiy3sryN2iWbniioOD692+fVU0jfc99/wmvqyZMvm88yYk1t24cVFi+aZNixMl+uzZw+JlTzwxN7pfml7d3eYPf9g/uE8q1TVy214+YsQuZvPm5HaKrl/TofuXN3Of3GiKd/cx1Cjy9947MVjPpreCPO/zMX36nonH4/HHjwu20+vgzDP3T31MWgsFOQCgPBTkAABUEgV5/w3FeHXl/ZGf10O1be/OtSZ83gnpr1FR/roB2iPv6SYoyFEXxRTkJ588Oi45ly/fL1h+7bWT4+Vz5w4PlmvksF3uTjHeW0Gukl1FslvK6jzWKpA1qlu3yY5qHjnya/F2zZTJmjrcnRJd5f4f/zguKor/9Kf/iEaA22Uql3U+dbvtokX7xpfrPl966UHR1PLuVPSTJg2J13/wwVmJ+6L19FheddWkqFTWOcLtNOirV09K3M5m7pMft5hfsGBEsNxNbwV53udDo8jdKfYVjUBX4a7p+fUY2Mc568j07KEgBwCUh4IcAIBKoiDvf6EYrz7/Oc8aXhfVdpUJn3NC+nsu6M6HBihf3oKc05OgLoopyN2pulWG+8s1Ktku96dXV3TebrvcPQd2bwW58vzz882wYV9JlKuN8s9/fnxu8GbLZBXXbhGeFhXXGkXvbpdlG3+09IUX/iJYLy0qnt3tmr1PbjR1vN22r3OH91aQK3meD0WvCb8kT4teA1u29D6FfXOhIAcAlIeCHACASqIg7z+hGK8HPcf+c581qK7/a8Lnm5CBkpsNUD4KcqB3xRTk7vmnNbW4v1yZPHn31OnVlW3bViaKUI3c1uUqQ91y1N/ObnvqqWMaFtIqcu+666h4fY3ytss0Pbq/v7S89dbyaGS7O/pbUck9fvyu5oUXFgTbXH/9FDNq1DeC26NoGnq/HLd56ql5UQHub6PrUvl81lnjgmnQ89wnm3ffPTHa9wEHfDtY5ue2246Mr8cd/e6m2efDRiPJNULcjpJ3M2TIF8ySJSOjdfztWgsFOQCgPBTkAABUEgV550MxXi8U5Ejzv0z4fBMyUHJyd7YYoFx8fgK9K6YgzxKVyI88ckxweZFRkX333b8x9903Mzpfd1oZ32pefnlhdO7uZ545PtP+VWZrtPTtt0+LSnEV0v46aVHRrJH169ZNj67TX15kNEo+reRvNXmfD90WPcY6WECPg7+8uFCQAwDKQ0EOAEAlUZB3LhTj9ZT3B35GwFXXayZ8vgkZaPkfA5Qr7+enAtRB+wpyQvpfKMgBAOWhIAcAoJIoyNsfivF6Y4pY+FQs+s83IQMtem8Dyua/7rKGv7tQBxTkpM6hIAcAlIeCHACASqIgb18oxiF6HfivjSyhfKqu+0z4fBMy0PK/DVA+/3WXNfz9hTqgICd1DgU5AKA8FOQAAFQSBXn5oRiHi4IcPt6HSRXyXwYoH5+hQGMU5KTOoSAHAJSHghwAgEqimCkvFONI479OsobXUnXxPkyqEApytAMFOdAYBTmpcyjIAQDloSAHAKCSKGaKD8U4euO/XrKG11R18T5MqhAKcrSDim7/tZclFOSoAwpyUudQkAMAykNBDgBAJVHMFJaPLjSUmOidXh8pr51MQXXxPkyqEApytEPeglwHLwJVR0FO6hwKcgBAeSjIAQCoJIqZ4vKiAXpHQY40vA+TKoSCHO2QtyBXgKqjICd1DgU5AKA8FOQAAFQSxUxxoSBHX/L+sM/It2rjfZhUIRTkaAcONAMaoyAndQ4FOQCgPBTkAABUEsVMcaEgR19UdPuvmyyhIK823odJFUJBjnbxX3tZA1QdBTmpcyjIAQDloSAHAKCSii1mLr74QDNz5g/NlCm7mwMO+LYZPXqQGTXqG2bixO+aY4/dx5x99njz0ksLg+1sHn10tpkzZ3i0j6lTv28mT9492nbWrL3NBRf83KxbN928/vrSYLu0vPnmMrNixSgzYcKuZtCgz5rBgz9nRo78mvnlL//V/P3vU7v/jlgVbNNaKMjRl7wFuUaeo7qKfR8mpDOhIEe7+K+9rNHoc6DKKMhJnUNBDgAoDwU5AACVVGwxM27cYLPDDjv0mUmThph33z0x2H716knBumlZtGhf88EHJwXb26xZc7jZccdPBNu5Of74fwu2ay0U5OhL3oKcH/Wrrdj3YUI6EwpytIv/2ssaPktRdRTkpM6hIAcAlIeCHACASiq2mMlakCtDhnzBbN26MrF91oJc0ajw+++fGdyGDRvmBOvutNOnzCc/+S+Jy2644bBg29ZCQY6++K+ZrOFH/Wor9n2YkM6EghztkvdgM2ZjQdVRkJM6h4IcAFAeCnIAACqp2GLGLcgXLBhh1q+fbR58cJa5+eapZunSH0dFtVtSa9p0d3u3IN9tt89HBfjjjx9nbrrpV+aMM8aa/fb7emJ7ld6vvLIosY8DD/xOvHznnT9tHnnkmHjZiy8uML///b9H061v2bIiuP2thYIcvVHJ7b9msoaCvNqKfR8mpDOhIEe7qOj2X39ZQkGOqqMgJ3UOBTkAoDwU5AAAVFKxxYxbkF9yyUHB8s2bl0Yjv+06Oj+5u9wtyFWG+9srF130i8RocE3X7i53p1b/299+FWxfXijI0ZtWCnJUW7Hvw4R0JhTkaJe8BblGngNVRkFO6hwKcgBAeSjIAQCopGKLmb4KcuWPfxyXGOHtLstSkCsqye16ym23HRld/s47JyQu14hxf9vyQkGO3uQtyPlBv/qKfR8mpDOhIEe7UJAD6SjISZ1DQQ4AKA8FOQAAlVRsMZOlIL/ssonxOhoJ7i7LWpBv27Yymibdrjtt2tB4mVuQM4Ic/Qc/6KORYt+HCelMKMjRLnkPOFOAKqMgJ3UOBTkAoDwU5AAAVFKxxUyWgnzRon3jdYYN+0piWdaCXNE5ydP2M3Tol+LLNZ37G28sC7YtJxTk6I2Kbv81kyUU5NVX7PtwVbN160qzYcOcKC+9tDBYTjodCnK0CwU5kI6CnNQ5FOQAgPJQkAMAUEnFFjN9FeQPP3xMYoT3ySePTixvpiC//vop8bruSHR/+nWdk1yXqVzx91FsKMjRm7wFuUaeo9qKfR+++OIDzcyZPzRTpuxuDjjg22b06EFm1KhvmIkTv2uOPXYfc/bZ4wdkwfzoo7Pj9/Xhw78aLO8tS5f+2Bx55A/MmWfuHyzrD/nnP+eY447bx5xyyhjz3nsnBssHRijI0U7+6y9rgOpau/Z5c8MNmwipaV7z/5MAAKAwFOQAAFRSscWMW5CrjLnggp+bCy/8hVm16qeJZcpOO33KvPtusghopiD3y/ZNmxZHl2/fvspMmjQksUzR+c51e8oryinI0Rv/9ZI1GimHaivvfbi36H3Sfw/uz8lbkHd1zYu3O/HEnwTL+0PcmU/OOWd8sNzm1VeXBJf1n1CQo53811/W8JmK6lJBfvnlWwipZVavftf/TwIAgMJQkAMAUEmdKWZUjj/00Kxg+2YKck2z6+5z8+al8TKV4BqJ51+vonOX33nnUcH+Wg8FOXrjv16yhh/zq68z78PKkCFfKPGgoWKTtyBfsWJUvN1TT80LlveH6HQg9jauXPnTxLIPP1wRleZ6rvT55W/bf0JBjnZiVhbAR0FO6hwKcgBAmSjIAQCopPYXM5rmttEouGYK8ttuOzJe151i3Y2mEZ47d3hwG5S1a38drN9aKMjRCOdLRW/Kex9esGCEWb9+tnnwwVnm5punRlON6wAl971QM2v4++iPyVuQ77LLZ6JtNErbX9ZfcsstR0S3TzOv2NlQbF54YUF8vynIAYuCHPCtXbs1KA0JqUtWr97i/ycBAEBhKMgBAKik8oqZ+fNHRCX2jTceFk1vbi8fP37XYDubZgpy91zjGlnnL3fzyiuLzPTpeyZKIZXqW7asCNbNHwpyNEJBjt6U9z58ySUHBcs124Y7YlnnJ/fX6Y/JU5Dfd9/MeJtzz50QLB8IoSAH0qjo9l+DWUJBjuqiICd1DgU5AKBMFOQAAFRSe4qZm276VaKcvvbaycG2SjMF+XHH7ROve8AB3w6Wp+Wqq3r2r+j6/HXyh4IcjeT9IV8j5FB97XkfdvPHP46L19EBTP5ym7feWm7WrZturrzyEHP//TOjf/vrpOWNN5ZFp7K47LKJ5rrrJpsnnpjb/d1tVbBeo2zfvioqxC+//ODoQCuVxHkK8tmzh8XbvPZacuYS/VvnJ1fefHNZsK2NrvuDD04KLrfZuHFRvJ9t2z6erv7115dGlyt2PU1lf/fdv4keSz02eizd9Wzcx0nL9bjb+6DR8O667qlF0pL3+csXCnK0E5+rgG/Dhm2kY9nQ/bfOf/carRNuV5dsMlkeozxxH1cAAMpCQQ4AQCW1r5jR1LF22Y47fiL1h/qsBbnKF40At+tqtLq/TqNoGlu73bJlPw6W5w8FORrJOxUsP+TXQ/veh21UXNt10k5RoUJbJbRdx43eQx96aFawjUptFdqa0cPfxl7P+ef/PFrP39ZGBbOmhXff323c/WYpyFVI67NG6+sx8ZfPmrV3vL+pU78fLFdUQmv5qaeOCZYpui/ulPU6rYcud0fo6zId0OXfpzvumJb6WP3zn3Pi/e+22+eD5W503f5tUvI8f62HghztREEOoD/J8p7EDBYfy/JY5Yn2q1m7AAAoHgU5AACV1L5i5uWXFyYKgpkzfxhsn7UgX7FiVOIH/w0begqFvnL88f8Wbzdt2tBgef5QkKORvAU5P6TVQ/veh20WLdo3XmfYsK8klmkb9/21Uc46a1xiO5Wu/jppWbJkZHB7FI2W1nTv/vppyVKQr1lzeLx+2mwhGlltl+uzSYW6v87JJ4+OlmuUfVqxr5I77Ta5BfmUKbsHt99OlV5GQZ73+Ws9FORoJ05dAqA/yfKexN/1SXo88n5H6i3aL481AKBYFOQAAFRSe4uZc84Zn/iBXtPNusuzFORXXHFwYh9pRXtvmTBh13hbjerzl+cPBTkayfvjD6Mg6qG978MPP3xM4j1UJbBdpoON3GUjRuwSTc+tMlmjzt0ZOJTHHjs2se+RI78WXa71li/fz1x66UFREatC2N3umWeOD26X+96saFS3Totx661HRKPK3WVZCvJDDvletK7K7/ffD6dI11Tm7ujvv/99amK5CnEV43a5Cnd/H0cdtWe8XKPj7eVuQW5vw5ln7h+dbuToo/eO7pfWu+aaQ83ZZ49P3A63INdn5MUXHxgv03rah42eF/f2tPr8tRYKcrRTljKqUQCgaFnek5jBIp0ttP3Hq4hQlAMAikFBDgBAJbW3mFHh4P5Ar9LEHbXXqCDXOo88ckxi9Lei0mHTpsWJ63j++fnmwAO/E51v1b9+d1phxS9EWgsFORrxXytZQ0FeD+W9D+vUFhdc8HNz4YW/MKtW/TSxTFHh+u67J0bb6f1Zo8ntMpXS/nnD9V7sni5jzJhvJpbrffeii34RbLdly4pESa6y2F2+du2vE7fLFshudD/s8r4Kcp3Cw67baPp0xS3ep0/fM7FMBbR7m0aPHpRY/uGHKxKzorjnOPcL8r6mNN9rry/H67oFuaJzoNtlduR5Wop4/loLBTnazX8NZg2frQDK4L/X+KEg71uZRTnv/QCA/CjIAQCopPKKmbSCXPGn4f3d73pGL7oFuaLzx+6yy2cSl7nL0kb0nXDCT+J1NH2tplFXse6fj3WPPb4YFRz+9vlDQY5G/NdK1vBDTj2U9z7cW1SOu8Xt7bf3TBeuqb11PnB/34qKYLte2vnLG0Ulvd1u9uxhiWXuVOMaYe1vqzz66Ox4nb4K8r/85T/jdVW++8tt3M8jfaa493n8+OSIduWpp+bFy90p3MeO/VZiv25BPmfO8OB6/RRRkJf9/PUdCnK0m/8azBo+WwGUwX+vSQuyYfp1AED/QkEOAEAllVfMNCrIFRUGdj3Flg5+Qd4oOqfr5s1Lg/0q7pS4jaJ1XnxxQbBta6EgR5osUy42CuqhvPfhRjnyyB+YV1/tGfGsaCp0u1wF9OWXH9ww7r42blwU3Aa9v55++thoVLZmA9HU6+7oZrdQfu+9ExP7e+WVcH9KMwW5rlPr6SCAtHOHu3HLbJXMuswtpd3MndtTdk+aNCS+XI9Jo33+4x+NC3qbIgryIp+/fKEgR7vlLU8oRwCUwX+vSQuaw/TrAID+gYIcAIBKKraYcc8hq+nM/eU277xzQuKcqwcc8O3o8uuum5z44V7RCDcVK0cc8QNz2mk/M3feeVSwPzca1afzrvr7sfvSiHUVMv52rYeCHGnyFuRMw1gfxb4PuwX5/PkjzG23HWluvPGwxMFDGh3tb6fZNvz3zCzp6uoZVf3228ujEtlfx497Cg33nOj6XPBvl03WgtwtlHX//eV+VqwYFa8/a9be0WXuTCT6LLMzmegzRJ8fmpbevT92mnobtyB/7rn5wXX6KaIgL+L5ay0U5Gg3CnIA/UmW9yTkR1EOAOgcCnIAACqp2GKmP0UjzB98cFZ0HlmNClTJ4J+PtdhQkCNN3h9zKMjro9j34UYzefjn1L722smJ7TTK212uQr2vqDi2p6p4//2TgoOTdCqLmTN/GBXV7v7dgtydOUQHQ/n3xyZrQa4Dqex6jzxyTLDcj2YwsetrmnXdH3sAl/33n/70H/E6Osf6lVceEv/7kEO+F+zTLchffnlhsNxPEQV5q89f66EgR7vl/XylDAFQhiwFOad4aF3e9/6+wvTrAIDGKMgBAKikYouZeoeCHGmy/FiWFgry+ij2fbhRQa5MnPjdeJnK37feWh4v06kr7DKVzP5++4o76lojrTWbh7tcByzZ5W5B7p7LW8Wyv1+brAW5SmSt01uZ7Gfo0C/F+54370fx/z/ppFHRco2M133SZTpfunt+co3O9/fXiYK81eev9VCQo93yliR8vgIoQ5b3JAry4jD9OgCgfSjIAQCopGKLmXqHghxp8hbk/DBTH8W+D/dWkKustUWvotHddtkpp4yJL5869fvBfvuKe9qMa645NFjeqCDfsGFOfLmydevKYFslS0GuEeN2nVNPHRMsb5Qzz9w/cRts3POhH3fcPsFyPZZpI7DLKsg14tvf1qbV56/1UJCj3fIWIxTkAMqQ5T2JgrwcWR77POH7GADgYxTkAABUUrHFTL1DQY40/uska/gBrT6KfR/urSBXzjlnfKLkvfvu30SXuyO5lWefPT7YtlH8c3KnlcaNCnKt626r2+dvq2QpyDWVu11HxbK/vFFUYru3QdGIbHedJ5+cG6wzffqewb6UIgvyl17quW0q5P1tbVp5/ooJBTnaTZ+T/uswawCgaFlKWgrXcmV5DvKE6dcBoO4oyAEAqKRii5l6h4IcafzXSdZQkNdHse/DfRXk27evSkwprmm7NWpbRbWdnlzR+cQ3b14abL9x4yJzxhljE5d99NGqxMj0O+6YlliuqdxHjfpG4jrd5e704Jr6/b77ZgbXe/XVh8brpBXk27atjLbVcp2P21/eV1Ta2/0r998f3oaxY7+VWOf226cF6yhFFuR6vtzr/Mc/fh1sr7Ty/BUTCnK0GwU5gP4kSzlLydoeTL8OACgWBTkAAJVUbDFT71CQw8eP98ii2Pfhvgpy5aGHekZzK7/73ejocneUt6LCefny/cxVV00yF130i2iacVuEr149KbHPMWO+GW+3226fN3/6039EZa5GhLuFsc0bbyyLt3WnEbfRNOHa9vLLDzbTpg1NLEsryG+77ch4uW6rv7yvaBu7vQprf7ny979PjdfRlPIqr/11lCILckVlt3v/dUCBbu/RR+9tfv/7f4/Xa+X5az0U5OgE/3WYNRyEBqBoWf7up1xtP4pyAEDrKMgBAKikYouZeoeCHL4sP5Q1Cuqj2PfhLAW5MmfO8ESZ+tRT86LLL7ywpyjuLSrE3f355xL3s/POn47OoW3/PXr0oMT2KsL9bRolrSBXoW6Xa8S6v7yvqLC3219xxcHBckUj5W35PW/ej4LlNkUX5A88cHTwGNj4ZX7e56/1UJCjE/zXYdZQkAMoWpa/+/8ar412K7MopywHgKqjIAcAoJKKLWbqHQpy+LL8UJYWfjyrl2LfhydM2DUuQS+7bGKw3Oadd06IRkHbdQ844NvxMpXl7ohwG40+HjbsK+ass8aZ9947Mdinpkb3R4trm0mThkQF9PPPz4+vU6Ob/e0fe+zYqPz2r1f71LTg9t/uOcwVjeS2I6MnTvxusN+sGT9+1+h2acp5f5nNeedNiK5Ho7X9ZTbuVOebNi0OlvvRY2rXf+KJucFy5dZbj4inkPcfG3/dvM9fa6EgRyfo89J/LWYJZQaAMvjvNX74G7/zmH4dANA8CnIAACqp2GKm3qEghy/vjy/8eFYv/fd9WOf11sjwdeumZxoJbfPMM8dH5yF/8cUFwTKNwn788ePMo4/ODpbZqKBWWa6p4N98s2cq9rLz7LPHm/XrG98uRcXy2rXp5wEvOzoQQCPM9diqBP/gg5OCddzkff7yhYIcnUBBDqA/8d9r0oL+I+93tb7CZwwAVA0FOQAAldR/i5mBFwpy+PjhHlnwPkyqEApydELecoPPWQBl8N9r0oL+J+9nSV9h+nUAqAoKcgAAKoliprhQkMNHQY4seB8mVQgFOTohb6nBTC0AypDlb3/0X2VNv67XBd/vAGAgoyAHAKCSKGaKCwU5fP5rJGt07nLUB+/DpAqhIEcntFJkAEDRshTk/J3f/+k5auXzpbdQlAPAQERBDgBAJVHMFBcKcvj810jW8MNZvfA+TKoQCnJ0gj4v/ddi1gBA0bKUqvydP7BkeU7zhOnXAWAgoSAHAKCSKGaKCwU5XPxoj6x4HyZVCAU5OsV/LWYNABQtS5lKKTowMf06ANQZBTkAAJVEMVNcKMjhoiBHVrwPkyqEghyd4r8Ws4ZRnACKlqVApQwd2Jh+HQDqiIIcAIBKopgpLhTkcOX94USjCFAvvA+TKoSCHJ3ivxazhiICQNGyHCDLe0915P2+11e0Xw7iAoD+hIIcAIBKopgpLhTkcKno9l8jWUJBXj+8D5MqhIIcnZL385aSCkDRKMjrSc9p3s+i3mKndQcAdBoFOQAAlUQxU1woyOHK+yMJP4LUD+/DpAqhIEen5B3Bx+ctgDL47zV+OBi2umyh7T/nRYTPLADoJApyAAAqaMuWe7pzOikgH374sv/wotbyFuRMp1c/FOSkCqEgR6fkLSMoqQCUwX+v8cN7Tz3k/WzqK0y/DgCdQEEOAEAFPf54l7n88i2kgGze/Ir/8KLW/B8zsoYfPOqHgpxUIRTk6JS8JQQlFYAy+O81aUF9MP06AFQBBTkAABVEQV5cKMjRI8v5BxuFgrx+KMhJFUJBjk5p5TMXAIqWpQxF/TD9OgAMZBTkAABUEAV5caEgRw9+rEczKMhJFUJBjk7hMxdAf0JBjr5QlAPAQENBDgBABT322Lag6CX58tpr/F0CK++P9Uz3Wk8U5KQKoSBHJ/mvx6wBgKJlKT+ZMQqS5bWSJ0y/DgBFoyAHAKCCKMiLCwW59V537u3OVd05uzundOfkeuUj/0eKZpKyvwGd07pzQXdu7M7/GKShICdVCAU5Osl/PWYNJRWAomUpPXnvgYvp1wGgv6MgBwCggjZt2k4KCgW53NOd35vwizkhNhd253kDFwU5qUIoyNFJWaY0TgvFAYCiZSk6ee9BI1leP3nCaw4AWkFBDgAAgF6sNeEXcULSopHljJzpQUFOqhAKcnQSBTmA/iJLwcl7D/qS5XWUJ0y/DgB5UJADAACggadM+OWbkN5yvsHHtm27qzunEjLA87/9lzbQRnmLBEoCAEXTQaD+e40f3nuQlS20/ddQEeF1CABZUZADAACggctN+IWbkL7yoIExjz/eZS6/fAshAzp33fW0/9IG2ihveaCR5wBQpCwFOe89yCPvZ11foSgHgL5QkAMAACDFOyb8kk1IllxpQEFOqhEKcnRW3tKAkgpAGfz3Gj+896AVeT/z+grTrwNAIxTkAAAASPGECb9cE5IlpxtQkJNqhIIcnZVlxGajAEDR/PeZtABZbO7O/d357+5cZT6euc3mnP8//muriGi/7nURUmb02tZrXK91veaB/oeCHAAAACn0Jcb/Qk1I1nxg6u6xx7YFZSMhAy133bXVf2kDbURBDqA/8d9n0gL05rXuXGPC1w0hdYhe+/pvAOg/KMgBAACQ4k4TfqEhJGveNHVHQU6qEApydJ7/+ZI1KtcBoEiaQt1/r/EDNKLPpdNM+JohpE7RfwP8jYb+g4IcAAAAKSjISSuhIN+4cTshlQjQWf7nS9bw4yuAomUpyHnvQRodcPgnE75eCKlj9N8CB+Gif6AgBwAAQAoKctJKKMgBAEXIUkil5Q5tDAAF0vuK/17jh4Icaf6PCV8rhNQ5+m8C6DwKcgAAAKSgICethIIcAFAECnIA/UWWgpz3HqQ5z4SvFULqHP03AXQeBTkAAABSUJCTVkJBDgAfe7c7r3VnE8mVv5nwMyZLtJ2/L1JMXjdMjYp6oiBHHm+Z8HVCCPn4vw2gsyjIAQAAkIKCnLQSCnIAdbahO9d15w8mfH8kpCq5oDu3mo8PAAHqQNOn+/8d+KEgh+8ZE75OCCEf/7cBdBYFOQAAAFJQkJNWQkEOoI4+6M7VJnxPJKTq0d+NQNVRkCOPf5rwdUII+fi/DaCzKMgBAACQgoKctBIKcgB1dIkJ3w8JqUvWGaDashTkf43XBj72uAlfJ4SQj//bADqLghwAAAApKMhJK6EgB1A3/zDheyEhdctGA1Sb/5r3Q0EOHwU5IemhIEfnUZADAAAgBQU5aSUU5ADqRL9h/H8mfC8kpG5ZY4Bq81/zaQFcFOSEpIeCHJ1HQQ4AAIAUFOSklVCQA6iTJ034PkhIHfMHA1Sb/5pPC+CiICckPRTk6DwKcgAAAKSgICethIIcQJ3o3Mv++yAhdc0bBqguTaHuv+b9AC4KckLSQ0GOzqMgBwAAQAoKctJKKMgB1Ml/m/B9kJC65nkDVFeWgvzZeG2AgpyQRqEgR+dRkAMAACAFBTlpJRTkAOrkBhO+DxJS13QZoLruMOFr3g8FOVwU5ISkh4IcnUdBDgAAgBSdL8hff32p2bBhTpR33z0xWD6Q8swzx0f346mn5gXLqhkKcgB1QkFOSE+6DFBdWQpyrQNYFOSEpIeCHJ1HQQ4AAIAUxRfk27atNH/+8wFm0qQhZsiQL5hddvmMGT78q+bAA79jLr74QPP++ycl1j/++H8zO+ywQ5SLLvpFsL+BlE9+8l/i+6LHwV22ffsqc955E8yMGXuZe++dEWw7MENBDqBOKMgJ6UmXAaqLghzNoiAnJD0U5Og8CnIAAACkKLYgf/LJuVEpbkvitOyxxxcT29SlIL/55qnxsh13/ITZujW5fGCGghxAnVCQE9KTLgNUl6ZP91/zfijI4aIgJyQ9FOToPApyAAAApCiuINfI8MGDP5cow1UE77TTpxKXzZkzPLFdXQry1asnxcu0nr98YIaCHECdUJAT0pMuA1QXBTmaRUFOSHooyNF5FOQAAABIUVxBfs454xNF+LXXTo6XvfnmMnPZZROj0eX33TczsV1dCvItW1aY6dP3NLvt9nlz6aUHBdsOzFCQA6gTCnJCetJlgGrzX/N+/tqzKkBBTkiDUJCj8yjIAQAAkKK4gnzixO/G5fDChfsGyxulLgV5p1POlO4U5ADqhIKckJ50GaDa/Ne8HwpyuCjICUkPBTk6j4IcAAAAKYoryHVucVsOX375wcHyRkkryDXa+t57Z5irrppkHn74GPPhhyuC7fxoiveHHpoVbaM8+OCsPkvhjRsXRdm8eWl82TvvnGBuuulX5rrrJpsHHji64T6ee26+ueaaQ82aNYebDRvmdP9tuyq1INf29nps3n57eWJf7757YnT5W2/1XK7tdB+uvPIQc889vwm2Scv27aui88Bff/2UaEr3+++fGT0ur722xOyyy2eiUf7+Nq2FghxAnVCQE9KTLgNUm/+aTwtg9b+C/JVXFkXfUxV9v/aXE9KeUJCj8yjIAQAAkKK4gnzs2G+1PIL8zDP3N1Onfj/+t42KZ5W+/rbKXXcdZcaNGxxsY3PssftEpbe/3aZNi+N1VB5rGvjRowcF2/vbXnHFwcF51ZWhQ7+U+LctyG+88bBgXY22d/c5f/6I6HJNv66i3f7bz2mn/Sxa7t8X5ZZbjjA77/zpYBs9doMGfTb+d7HTu1OQA6gTCnJCetJlgGrTCHH/de8HsIotyNevn20WLdo3yiWX5Pv+dsAB346/A/7jH78OlhPSnlCQo/MoyAEAAJCiuIJ8wYJkqavRz/46aXEL8r5y9dWHJrZVCe2O2m6UYcO+Elyvjqi3y1V4jxixS7Dd0Ufvnbgu/z72lmYKcvcx8It2PyrJ/fty/vk/D9ZLi34kcUeptx4KcgB1QkFOSE+6DFBtFORoRrEFuWZks9/hdBC3vzxLKMjzRzO8vffeicHlJE8oyNF5FOQAAABIUVxB/sQTc4NCdsmSkeaNN5YF67rxC/Idd/yEWbx4pLn11iPMZZdNTIyK1v/3p1tfsWJUtEwlt/Z14YW/MH/+8wHBqHJNVe5u5xbkNhpJrh8jVMQfcsj3ouno7Pp//OO4xLoq1HVdd9wxzZx11rigqLcF+fPPzzdnnz3eTJ++Z7yst4Jc0WOgx+6224401147ORpZ7i7TF3a7rW6ju61G8mtqdU03r4LfXaap593rbT0U5ADqhIKckJ50GaDa7jDh697Ps/HaqDsK8irkkUeOMUce+YPoMdP3cH85yRMKcnQeBTkAAABSFFeQK2kjmVUcq/B2z/Ptxi2HNRX4s88en1iuc3O7+9OU6u5yjYg+6aRRidLYxi2lx4/fNbHML8h13a+/nn4bddvdAvy44/aJC3AbTYPn7s9f/ve/T42X9VaQq6R/5pnkY6D76F7/unXT42VLl/44vlwj5f0p2N0p60eO/FpiWeuhIAdQJxTkhPSkywDVRkGOZlCQVyHTpg2NHzMK8qJCQY7OoyAHAABAimILcuWGGw5reC7siy76RbC+Ww6nLVfckreZc7A9+WTPqPbBgz+XWOYX5Lrd/vY28+b9KF5Po7m3b08/D7hbYuctyBs9BpMmDYnX0ch6e7l77nedH93fTqPJ7XKNsveXtxYKcgB1QkFOSE+6DFBtWQpyrQMIBXkVQkFeRijI0XkU5AAAAEhRfEGu6HxdmpJchaz9gmmzcuVPE+tmKYdPPnl0vM6qVcntbTSCXFOra3S3SuO99vpyolhX3PX9gtyfut2N9mXXu+aa5HnQ3ZRZkC9cuG+8zqmnjokvd8+dfvPNU4Pt3IJc8Ze3FgpyAHVCQU5IT7oMUG0U5GhGZwtyzYR2002/ir6rPvjgLPPBBydlLsh18LcOLFchrH08/fRvGx4Qruh7tGZ5c7fXbGo6pdl9981MndlNp137299+Za6/fkp0ijD/u7KNttW+lS1bVkT71qncdNu0/QsvLAi26S0vv7wwuk+6Xu2n0f3aunVldJ36nm4fswsu+Hl8W+zt8bezyfsYuuvosjVrDjc33nhYn9v70f3U6dlWr55kHnvs2Oj+2GXaj70PjWb1s9Hrxq779tvLg+X5QkGOzqMgBwAAQIpyCnIbfcE67bSfBefn1pd2u06WcvjMM/eP19F06v7yc8+dEJ2b272OtLjbuAW5Rrz7+3Tj3n59WfWXp63nf+lvtSBXKW7X+d3vRseXu1Os60ACf7sTTvhJvHzIkC8Ey1sLBTmAOqEgJ6QnXQaoNk2f7r/u/VCQw+pMQf7ww8dE3/HsujY6UN39bppWkKs4PeOMscF3dZsVK0YFB5GrwLbLVVhrv2nfw3XA+ptvLouK86FDvxQs1+xu7m8CNvPnj4jXmTnzh9F6/raNZqZzc911k1MP1lfmzh0elN0q0P31/Fx88YHB9bT6GOp2Pv74cdFp1vxt99jji+app+YF12mj31p0EH2j69ZvDjoY4fnn58eXaV0NZvD3ZaNT49l19Tj5y/OFghydR0EOAACAFOUW5Db60ud+cdaXXbssSzncW0Gustj9IqiyWyPHFy3aNzEtueJu5xbk+kLqX2faeop7NLafMgvy008fG6/jFuRr1/46vlzX7x5Vry+/7o8K7uNeTCjIAdRJcQW53p/1I6Q+q7JGI5P8/dQ1+iFbM8YcddSe5vDD94g+7/XZqh+KL730oOhH9/ffPynYrpXoR/DzzptgZszYy9x774xgef3SZYBqy1KQ/zVeG3XX/oJco4XtOn3FL8g14nz48K8G6/kZNOiz5rXXlsTbvfPOCfGytGLcTaOC2kbfXfVd271d7vfivqIR8v537o8+WmVmzdo7WNePDip46aWF8XZ5CvIiHkP9DtHb46hlaSPy9XeO9uuv72fYsK9E648c+bX4Mvd0bX7cU+VpJjp/eb5QkKPzKMgBAACQoj0FueJOEa4vkvbyLOVwo4L89tunJb4AagS1f4S2u9y9PGtBrqnF3H2408n56URBrgLALcF1G/RY62h1/3JNvebvt7VQkAOok+IKcv/gqyzRtJv+fgZi9ENvb6OXskQHfPmPjx997qks97fNG53GxO5bP1j3dsBcPdJlgOrzX/d+KMhhtbcgV0Hqfuap2PzDH/aPDp6+5JKDzG67fT6x3C/IdXCZu1zfHfV9VXFHESs6CM1u55a7NpMn725uuOGw6BRraYWxvpOeddY4c8cd0xKzmylHH7134nb5BfmBB34n2vettx5hzjlnfFAK+9+dVf66y4888gfRbwYqe93fFJQpU3aPt1OBranR99vv6/HyBQtGRJfZ+N+li3wMNeJez5tu65IlyW31O4B7vfo7yi2ylWXLfhzdRk2zrteB/R1AMwz4j4vuo7s/G/fUbL39PtJ8KMjReRTkAAAASNG+glw/7Kd94cpSDjcqyDXtl73c/3Jt435xdC/PWpAr7lHd69ZND5bbdKIgV956a3n0w4l7X93oC7R+LPH32XooyAHUCQV5K3nkkWOiH6p1X3SOTn95M8lSkNvoR2f/R+08cUfq6fPe/5yvX7oMUH3+6z4tgLS3IHeL6BEjdgnOLa3pzd0y2S3I/QO+nnnm+GD/fgGvc4vrcr/c1enU3O302bjXXl+Ol+t7tn/bNCW5Xe6fAsz9XqzZc/zbpanRVcjbdTRK3R50p/91R60vX75fsL1bAiu2QLaZNm1ovKy3v1WKfAxXrfppsK1uu12u0d/uMhX3dpnur8457m+v50Gz+Nl/66B697eKZ58Nb6/72K9cGd6m/KEgR+dRkAMAACBF+wpyHTVuv3DpiHZ7eZZyuFFBrinD7OU6WtrfTrHLFffyZgpy9wcIHcXuL7fpVEGuadV1gIB7XxV9YT7xxJ9E5yfz91dMKMgB1El5BblGRvWVN95YFuxnICXrj85Z4hbkGsH10EOzoh+5r7760GgEl38uT/1Yr2lX/f00E/0oP336ntHfMEWOTB+46TJA9fmv+7QA0r6C3D3wXHFPseVGU5DbddyCXIW6vVyfm/52NjqViV1Po7d1mT/Fur+N4o6A1mhmf/mmTYsTt99dluV7cdrfULr8yisPSdy2RqdamTBh13g9nfPcXZb1b5WiHkN9X/e3UXTucLuO+1uFe/5yRaPO/W0bxZ16Xr8RuMv0N5J7cEFa4Z8/FOToPApyAAAApCiuINeXKhW/11xzqNF5Ot1l69fPTpTHmnLMLsvyJbhRQe5+ufXPTa7b407rrrhHrzdTkOt2uftJu53PPTc/sU67CnJ98bejA3R0uY5m1xHhKsX1GLRaCPQeCnIAdVJeQe4vr2Ky/uicJW5BnjbySqPI5szpmWVG+fOfDwjWI62kywDVpynU/de+H0DaV5C703c3mkVNaVSQu9/L9dmo60qLO4X4jBl7RdtmKXd1oJpdJ60gV+xyxb08y/dixf0dwH6+q/S1lx177D7BNjYqle16eozcZVn/Vin7MdTfMXYdxV7ujkrXQQD+7y69RQcT2m01w5z7O8Fddx0VL3NPh1dMKMjReRTkAAAASFFcQe6eD1xfuA455HtRQa0R1+6XO32ZfPrp38bbZfkS3KggP/XUMYn96kvxLbccEZ1ja8yYbyauV9F5uey2zRTkKrv987jp3F2aUk5TruooefdLstKugvzuu38TX64p6n75y381o0Z9IzF6Tucg0w8pxY8+pCAHUCedL8hffXWJ6eqaF6Wv93S7XqNRQPpR9ckn50Y/AOvzUZ/Nvf3QquvbuHFRYlYS/circ4pq9JQOhvvwwxXBdjpXt7bTZ5+9vxdc8PPoMhuNzva36y19FeQ2Or+oXU+f03r83OX2+t0D6HSf9Hhcd91k88ADR0cHorm3VXn77eXx+s8/Pz9+rHubsUX7setpH/5yRY+DfvzWKDg9ro3Ws9HrSOu4z5su0+jCG288rM/ntLV0GaD6shTkz8Zro87aV5C75fDFFx8YbGuTVpC/+OKCxN8fWWPP152l3M1SkLvfnd3Ls3wvVtyR2XYqdp3n216m86H729ho5jm7njuznZKlIG/HY6i429rLspxLvLfo9wK7vXsKttmzh8WX6280f7vWQkGOzqMgBwAAQIriCnJ7XtG+ogLb3S7Ll+BGBbk7erpR3HOg6Sjr11//+EfwZgpyRVO3qvj3998o7SrI9WO8f92NosdK07L5+84fCnIAddL5glyjj+w2+oHcX27jjgTSZ5/7maTCVOf/9A/sstEP22lF9x57fDFarh9RVRDrB3t/W12XZjJxt7v++inBen56+4E/LVkLcs2o4l6Pfli2y9wpXvV3gM7Xmnaf3HOP27if4+7fIb39IK/Pbruef7qWt95abqZO/X5wPYp+PE+bvtWdZlVlvs416k8tr+h5e+qpecH2rafLANV3hwlf+34oyCHtK8jdz51GpxlT0grydeumJz4j9P02S+znW5Zytx0FuXsd+vzUZe5neG/b6uA3u54/TXyWgrwdj6HiXoe9LO1+N5Pzz/95vL0t7PU3oh4He7n9vaS4UJCj8yjIAQAAkKK4gvzRR2cnRmr50Re4l15aGGynI77tOn/5y38Gy5U//ek/4nX882+//PJCM3bst4Lr09Rg+rFYI9c0otpe/sQTc6PtXnttSXyZfmTwrzMt+rKoI9P9UkH/1hde93J/xJZ7pLr24S7L8hi4BwmccsqYxDJ9Sdf52HX9ikaM6weRI474QTDy3X/8WgsFOYA66XxB7k6Pqfgjom30/m/XWbbsx/Hl+hzT56O7j7Toc1Gfk+4+bUGu+J8tfu67b2a8XScLcmXcuMHxuprxxV7uPgf6gdo9n6iNpq7VSGz/crcgdz+f/ZFoNprG1C2v3VFbGjHunvezUXSd7nSo7g/s2rf747YfLSv2ADmlywDVl6Ug1zpA+wpy9/P4qqsmBdvapBXkOmDK/Xxo9nRcWcrddhTkRx21Z7ze0qUf/52jmdTsZfps9rexcc/hrsfSXZalIG/HY6i412Evu/DCnlO/acY8f5u+ooMB3f3qAD29Nuy//QP4igkFOTqPghwAAAApiivIbfQDrIppjSDTqGkV0iqp/fWKjn7I13Skuj5/9Laic4Tfe++M1GXNRl+C9cVYR5+roPeX97eoHLFfensbcdh8KMgB1El5BflZZ41LjT/riqIDoux2aT8Auz+8Ku7Bae65MBX9iK3PasU9p6niH8zl/iCvqAzWD9/67NV0nO6P3TpwzW6nz2dNWa6pQO3yBQtGRJfZNPtZ2kxB7k7D6p5r1H8OFBXNKiU0YlunitmwYU40hfrZZ48306f3/BjvFuSaet7dhw5i8G+DHiO7XAex2cs1C4w7ElAjzPRYan0dWOBOF6u451H3n2dFj7vOrarT3uhgAHeZZqLxb1dr6TJA9VGQI6v2FeTuZ8PKlT8NtrVJK8h1ELf72aCZVvztekuWcrcdBbl7UJs+93SZZpqzl82ZMzzYxsY9sM3/W8ctyK+44uBgW6Udj6HiXoe97M47e2YI0t8M/jZZ4h5IoL853IMNbrjhsGD91kNBjs6jIAcAAECK4gty0v688MKCaASaf7mNe5S8/wNLa6EgB1An5RXkjeKfkkPRD7Z2edqIZf2gbJe7P/zqwDV7uUYUp52bXJ8l7vW7I8Hdgnz8+F3Ne+8lRyS7I5AU/4C0LKOysqaZglwzvNh13Rlj/OdAy3qbVrS3U6W45bkKeX9bd4Yd99ye7kEJ+rE/bZS3ynm7jgoFO/29X5CnPQ7Ll+8XLx858mvB8tbSZYDq0/Tp/mvfDwU5pH0FufveroJVpx3zt1fSCnLF/TzX56m/XW/JUu6WXZC7U6Qr99//8d8qGk3v3ra0g/R1oLsOVLPrnXjiTxLL3c9znY7G396m7MdQce+jvWzz5qWJy9NOwdJX3IP2dE5y+1y4f2MUGwpydB4FOQAAAFJQkA/06Ah2ewS9pkS7557fRCPSdLlG8uuHBXfaVXeq3dZDQQ6gTvpHQa4fL933df8Aqb32+nK8TJ8J9nJ3tFVvP6i6I67POWd8fLn7Y3Cjc1q7t0sHb7nLOlWQq5C267qjt/3noK9RU70V5I88cky8zP+B2Z3OVMtsCb5ly4rE9b/4YvLxstGP+foB26732GPHRpdn+YFdI+DtOhod7y9vLV0GqD4KcmTVvoLcfW9X9Pmq73/uOjqIzf3cdgty90A7pdFn8jXXHJo4UE7J8tlTVEF+2mk/C7bTrC7u/dKsOnaZHgP3lCVpM6e4p25T/L9Vfv/7f4+X6e8mf3ubsh9Dxd2/e7lOXedu7/8dqLz99vKo/E878M8/7YtNs0V/9lCQo/MoyAEAAJCCgnygxx0p2Ff0BVpHnfv7yB8KcgB1Ul5Bfvfdv0lNV1d6Ee2eOuPYY3tGLP/znz0/musHZHcb98doTdWtH9/T4k7DPmPGXvH2WQryoUO/FK/j/yDcqYJc5ya162rku73cfw76GjXVW0GuuOd21/To9nK3oJ8/f0R8uV+q+8+DG/dxteebzfIDuwoS9z76y1tLlwGqL0tB/td4bdRZ+wpy5eij9068v2sWFBWiKm5VDLujpBW3IFd02i13uT4fzz13QlTonnLKmPgzTftxR2Jn+ewpqiBXVAZrCnV95507d3hiO0V/K7nba113uf6m0UGB+lx2/w5RdCoS/3a5o6sV3X89nirr9Rht3LgoXrfMx1Bx9+1erlPX+I+D7pv+3rjyykPMokX7xgcs6rnw96toan53e8V/LIsLBTk6j4IcAAAAKSjIB3p0bll3tF+jjBr1jeg87P72rYWCHECdlFeQ+8v7ikY82W3dEcsqYO3ll102MV5fo5P9z4Us0dTgdh9ZCvIxY74Zr3PXXUcllnWqIHenN3fPSeo+B1nO49lXQe5O7Tpu3OD4cvdxc89T6pYfzcROOdvqD+ytp8sA9eC/9v1QkEPaW5BrZLBOneF/RjSKX5Bv2rQ4Gn3tr5cWTWlut8vy2VNkQd5bzjtvQrBfzaKmz3p/XT8HHfTd1NOaKCq6/fVtbrnliHi9Mh9Dxd3eX6Yi3x0t3ygqyv1tFf0d565X/CwzbijI0XkU5AAAAEhBQV6V6Av6pZceZBYu3NeMHfut6Ih1lQIaOffww8cE6xcTCnIAddJ/CnJFp9Ww21933eRodJIdMaT/1RTedt1166Ynrk+FcJbo/N12H1kKcn3+2HX6S0Gu87TbdTW1qr3cfQ6y/DDcV0HuT32v/T/66Oz43xpp5q7vFgiK/9g3yr33zoi2L+IH9tbSZYB68F/7aQGKLcjdg6702eovV7ZtW2lOOOEnqUWpPid1gLT9t/4O8LdXmXzWWeNSt9fnokZfP/30bxPbqFS26zT67Pnd70bH67ifu26yFOS6Df5IaUVTn/f1/XbNmsMTn//uPjXS2l/fje6jO425G41Qd9ct6zFUGj1GNjqFi/62cv/2sNG2OlDAv24bTbPu7l+vI3+d4kJBjs6jIAcAAEAKCnLSSijIAdRJ/yrIb7+9ZxpQ/Xiuc2g3+qHTHymkH0b9/fWVgViQr13768T9vummX8XLii7IFT3udp0zzhibmOFFz5e7rnuKFI289/fVVyjIgXbRCHH/9e8HKLYgbzb6TLv//plRIari3F/eV954Y5m5886jogO7/POZtzNuQa7PSf29ollzNGJaf3uokPa36S06WPChh2ZFB5c1GjHeKHpMdGCBzvH96qtL+vzbqZOP4csvL4weI52+Je2842kZMuQL8WPd6O+6YkJBjs6jIAcAAEAKCnLSSijIAdRJ/yrIFfcco26BrR9K3fX0g7J7fe5U31lTZEGuc6T62zaTrAW5O/2sRl+7o+rLKMh12hN3n3Z0lp4nf139WO/eNn95X6EgB9qFghxZdLYgr0r8gtxfToqJ/g60j/Nee305WF5sKMjReRTkAAAASEFBTloJBTmAOul/BbnOv+nuR5k0aUiwnuIW3CqY/eV9pdWCfPr0PeNlGl3tb9tM+irINXrOPwfp6tWTEuuUUZArWuZer/LnPx8QrPf228sT61x99aHBOr2FghxolywF+bPx2qgrCvIiQkFeXnSwpEbD//73/56YEr6vKedbDwU5Oo+CHAAAACkoyEkroSAHUCf9ryBXSeqfn9Oeo9qPRm276zWa5vyaaw419903M7i81YJcP8jaZTp/qL9tM2lUkGv6VE1vqinL3fs6dOiXjD81alkFuaY4da9bz89776VP6+oeNKBziD7++HHBOpqm9cwz9zebNyenTKUgB9rlDhO+/v1QkIOCvIhQkJeXQw75XuJvAmXy5N3N1q3NT8nfXCjI0XkU5AAAAEhBQU5aCQU5gDopryDXeSD7iqbv9vejzJq1d7wfFcH+cjcTJuyauN7x43c15547ISrFTzlljBk+/KvR5ZoS3P/BtNWC3C+OdR2nnz7WnHbaz6LbsXHjomB/jeIW5IoKYpXc7mU2euw2bJgT7KOsglxxp75fsGBEsNxGo8jdUVyK7tsllxxkLr/8YLN8+X7R9Ov2cndbCnKgXbIU5FoH9UZBXkQoyMvLuHGDE38T6NQ3zZ7TPV8oyNF5FOQAAABIQUFOWgkFOYA6Ka8gz5Inn5wb7Ef55z/nxOtcdtnEYLmbTZsWm2HDvhLsOy0PPHB0YttWC3JFRbh/PTa33HJEsH6j+AV5o5x88uig6LcpsyDXdKV23eeemx8sd6MR/35JnhaNMHfPoU5BDrQLBTmyoCAvIjpoTwf7KWvWHB4sJ/mzdOmPzQEHfNssXjwydcaa8kJBjs6jIAcAAEAKCnLSSijIAdRJcQX5a68tCQrQvvL0078N9mOz335fjwrUDz/sKVAbRaOFzjprXGopq6L48MP3SL0u/Vht13vmmeOD5YpbgKdN9a4p0KdO/X5wvYpGTfvrN8rs2cOC7XV/Ro36RjSi/pxzxjc8oMDGfQ4GDfpssNzPbbcdGa/f6DzvNrqfmlpdP0T7y9KikeQq/f3p8hWNgF+yZGS0jn8d7n3392nj7tNf1lq6DFAPmj7df/37oSAHBTkh6aEgR+dRkAMAACAFBTlpJRTkAOqkuIK86Dz77PFm/frZweV95Y03lkXn7H700dnRua795WVF17tu3XTz4IOzzKuvLjH++cGrEN23F15YEFzeV7SNpqPXKP1t29JHv/ePdBmgHrIU5H+N10ZdUZATkh4KcnQeBTkAAABSUJCTVkJBDqBO+m9BTkj702WA+vBf/34oyEFBTkh6KMjReRTkAAAASEFBTloJBTmAOqEgJ6QnXQaoD//174eCHBTkhKSHghydR0EOAACAFBTkpJVQkAOoEwpyQnrSZYDOeKs7L5iPX4Ptiv/6T4u7fqei6eA3G3QCBTkh6aEgR+dRkAMAACAFBTlpJRTkAOqEgpyQnnQZoH3e6M4t3TnbhK9FEub07lxvPi7M0R4U5ISkh4IcnUdBDgAAgBQU5KSVUJADqBMKckJ60mWA9nioOyeb8DVIsuUWg3agICckPRTk6DwKcgAAAAQee+xpc+utTxGSK++9pykuAaAuKMgJ6UmXAcq33oSvPdJ8bjUoGwU5IemhIEfnUZADAAAgoIL88su3EJIrFOQA6oWCnJCedBmgXNu780cTvvZIvjxnUCYKckLSQ0GOzqMgBwAAQICCnLQSCnIA9UJBTkhPugxQrgdN+Loj+fNfBmWiICckPRTk6DwKcgAAAATWr98WlJ6EZM277/L3PIA6oSAnpCddBijX1SZ83ZH8Od2gTBTkhKSHghydR0EOAACAAAU5aSUU5ADqhYKckJ50GaBcZ5vwdUday+sGZaEgJyQ9FOToPApyAAAABFSQP/QQIflCQQ6gXijICelJlwHKdbIJX3ektTxvUBYKckLSQ0GOzqMgBwAAAAAAyI2CnJCedBmgPNtN+Jojredpg3I899xzZv36tYQQL/pvA+g0CnIAAAAAAIDcKMgJ6UmXAcqj34z91xxpPRTkZVEJ6J+OihCyhYIc/QIFOQAAAAAAQG4U5IT0pMsA5aEgLycU5GWhICckPRTk6A8oyAEAAAAAAHKjICekJ10GKA8FeTmhIC/Lc8+9ExSDhBAV5O/4/7kAbUdBDgAAAAAAkBsFOSE96TJAeSjIywkFeVmefXZ7UAwSQrZE/20AnUZBDgAAAAAAkBsFOSE96TJAeSjIywkFeVlUAv7tbx8SQrxQkKM/oCAHAAAAAADIjYKckJ50GaA8FOTlhIIcAFA/FOQAAAAAAAA53X33M+aaa94ihHTn5Zdf9P8TAQpEQV5OKMgBAPVDQQ4AAAAAAJCTCnL/vIqE1DUU5CgXBXk5oSAHANQPBTkAAAAAAEBOFOSE9ISCHOWiIC8nFOQAgPqhIAcAAAAAAMjp7ru3BSUhIXXNyy9v9/8TAQpEQV5OKMgBAPVDQQ4AAAAAAJATBTkhPaEgR7koyMsJBTkAoH4oyAEAAAAAAHJ6+ultHcszz2zqzv/p/v/X54621378fdc1WR/Pj9cLt697KMhRLgryckJBDgCoHwpyAAAAAACAAecOE5YczeZZA58eE/9xahQeP6C9KMjLCQU5AKB+KMgBAAAAAAAGDJWyfzVhwdFMVK6jsawHH+h5ANA+FOTlhIIcAFA/FOQAAAAAAAD9XhHFuLZn1HM2WR9rDjYA2qecgvyJJ+aa447bx4wa9Q2zyy6fMUOGfMGMHj3IHHvsPuaxx44N1nezdetKc9ttR5qVK39qxo79ltl550+b/fb7upk370fmkksOMs8/Pz/Yxs3pp481s2cPM9OmDTVTpuxuDjnke2by5N3NihWjzHXXTTYbNswx27atDLYrNhTkAID6oSAHAAAAAADo17KOaO4tFLnNYap1oP8pviBfteqnZocddug1a9YcHmynvPXW8qhU99f3c+mlBwXb2gwa9NlgfT+DB3/O3H//zGDb4kJBDgCoHwpyAAAAAACAfqmoUePIJ+tjz2MMtEexBflll00MymiNAPcv27x5abDtc8/Nj4prf91GmTr1+2bLlhXBfrIU5DYLFoxI3UfroSAHANQPBTkAAAAAAEC/0+qocaZTL4b/uDYKI/SB8hVXkH/00Sqz446fiMvnMWO+aV59dUm0TFOaa2r1mTN/aA466Lup2+622+cT5fUpp4wxjz46O5pyvatrnrn66kOj6drddc44Y2ywL7cgP+uscWb9+tnm3ntnRNOzz58/wnzyk/+S2MeiRfsG+2g9FOQAgPqhIAcAAAAAAOg3mpnau1Eoa4vTzPPBAQlAuYoryB9//LhE8fz66+Eo8UbRucHdbW+44bBgHeXNN5dF5zK366mQf+edExLruAX5nXceFezjhRcWJPah6Lb767UWCnIAQP1QkAMAAAAAAHRcUdOpU9IWL+vzwlTrQLmKK8h1XnFbOGukt7+8UfzR4/Pm/ShYx42mZ3fLbZ3z3F3eV0GufPjhisTU78OHfzVYp7VQkAMA6oeCHAAAAAAAoKNanU5doRgvl/94Nwqj94HyFFeQ33//zERx/fbby4N10nLHHdMS2z3xxNxgHT8zZuwVr69C3F2WpSBXrrzykMT1amS5v07+UJADAOqHghwAAAAAAKAjihg1TiHbHs0cxMDBCkA5iivI33hjWaJwnjRpSHTucX89P+ef//N4m732+nKwPC133XVU4ro0Ct0uy1qQaxv3fOS33npEsE7+UJADAOqHghwAAAAAAKDtWi3GmU69/bI+Z0y1DpSjuIJcmTJl90RxvcceXzT/+Mevg/XcHH/8v8Xra3t/eVo02tu9no0bF8XLshbkiju1+5/+9B/B8vyhIAcA1A8FOQAAAAAAQNs0MxK5URg13hk6IMF/LhqF5wgoXrEFuc4PPnjw5xLltaJzfN9889RgfWXChF3j9RYu3DdYnpatW1cm9n/PPb+JlzVTkLvXPXPmD4Pl+UNBDgCoHwpyAAAAAACA0hUxnTqjxjuvmQMceK6AYhVbkCuvvbbEHHHED4KSXBk3brB5/vn5ifVVntvlq1b9NNhfo7jTo1933eT48mYKck0Db9edPXtYsDx/KMgBAPVDQQ4AAAAAAFCqZkrVtFCM9y9ZD3RgqnWgWMUX5DYPPjjLHHjgd4KSfKedPmVefHFBvN7Ysd+Kly1ePDLYT1p0bnN3n+vWTY+XNVOQDxv2lXjdM8/cP1iePxTkAID6oSAHAAAAAAAoRTNTcjcKU3X3P808rxzYABSnvILc5uGHjzEjR34tUWhrJLldPmvW3vHlv/zlvwbbp+WllxYm9qdzkttlzRTkKuvtujfccFiwPH8oyAEA9UNBDgAAAAAAUCimU6++ZmYFAFCM8gty5aOPVpmjj+4pwpWXX14YLTvjjLHxZRrR7W+blvvum5nYl0aU22VZC3JNBe/u49FHZwfr5A8FOQCgfijIAQAAAAAACtNMcdooFOMDQ9aDIJhqHShGewpy5a23licK6bVrfx1drvOHu5f75yhPy8KF+8br77zzpxPLshbky5b9OHG977xzQrBO/lCQAwDqh4IcAAAAAACgZUWNGsfAwVTrQHu1ryBX9tjji3EhfdllE6PL3nhjmfnkJ/8lvvyEE34SbOfmvfdOTKw/bdrQxPIsBfnbby9P7GPKlN2DdVoLBTkAoH4oyAEAAAAAAFpSRDFOgTowZZ0xgIMfgNa1ryD/8MMVZscdPxGX0u45v90R4Squn3hibrC9zeLFI+N1lWefPT6xvK+CfPPmpcE50bOMWm8uFOQAgPqhIAcAAAAAAMglaznaW7QPDGxZD5DguQZaU2xBfv31U8ysWXubF15YkLh869aVZubMHyZKaY3itstfeWVRYtlOO33KPPdcsrTWecZnzNgrsZ4/elxpVJDrnONr1hxudtnlM4l9qJz399F6KMgBAPVDQQ4AAAAAANCUoqZTZ9R4NTDVOtAexRbkI0bsEhfP+v/HHrtPVJj7pbQu97c944yxiXWUYcO+Yo47bh8zZsw3E1OiKyrR00Z+uwW5ttE5yrWuv29l4sTvJor64kJBDgCoHwpyAAAAAACAzFodNU4xXk1ZD5hgqnUgv+IKcpXVfgGdFpXdGlHub6/ovOT++mnRFOmbNi0OtlfcgrxRNNW7O8V78aEgBwDUDwU5AAAAAABAn4oYNc4U29XmP9+NwusAyKe4gvyDD04y5503IRgtbqPLV6+eZD76aFWwrZs77phmRo8eFIwYV/bY44tm5cqfRtOt+9vZDB78uWA7Xff48buaBQtGmIsvPtC8+eayYLtiQ0EOAKgfCnIAAAAAAICGiijGGTVeD0y1DpSruILcRgX4iy8uMHfddVR0zu97751hNm9eGqzXV7SfDRvmmJtu+pV59NHZDUed989QkAMA6oeCHAAAAAAAIFWr06krjBaul6wHUzDVOtC84gtyolCQAwDqh4IcAAAAAAAgoahR46ifZkaRc/AE0BwK8nJCQQ4AqB8KcgAAAAAAgFgRxTjTZ9dbMzMP8FoBsqMgLycU5ACA+qEgBwAAAAAAaGrkb6MwIhhW1gMtmGkAyI6CvJxQkAMA6oeCHAAAAAAA1FhR06kzEhiuZg644MAKIBsK8nJCQQ4AqB8KcgAAAAAAUFPNTIXdKBTjaKSZ1xeAvlGQlxMKcgBA/VCQAwAAAACAmili1DijfpFF1tcZU60DfaMgLycU5ACA+qEgBwAAAAAANVFEMc506mhGM1Ot87oCekdBXk4oyAEA9UNBDgAAAAAAaqCZ6a4bhVHjyKOZ1x6AxijIywkFOQCgfijIAQAAAABAhTFqHP1B1tcgU60DjVGQlxMKcgBA/VCQAwAAAACAimpm5G5aKMZRFKZaB1pHQV5OKMgBAPVDQQ4AAAAAACqmmTKyUZhOHUXLesAGo8iBdBTk5YSCHABQPxTkAAAAAACgIphOHf1d1tcnB2gAIQryckJBDgCoHwpyAAAAAABQAVlH5/YWinGUrZnZDXg9AkkU5OWEghwAUD8U5AAAAAAAYAAratQ40C5ZX6+8LoEkCvJyQkEOAKgfCnIAAAAAADBAZS0aG4Xp1NEp/muxUZhqHehBQV5OKMgBAPVDQQ4AAAAAAAaYIqZTp3hEJzHVOtA8CvJyQkEOAKgfCnIAAAAAADBAFDWdOoUj+oOsr2WmWgdEvxlv23YqKTzP+A81AACVR0EOAAAAAP+vvXsPtquu7z6e//qPjn84xXHUeXzQoY/ooMWG1uIFmUZUpGlEFCiXEFQQIiVcgw8JlwCBUNSKiIItIzhguVku1VoRG8BqLXdQ+nAVYky4ikACJIH15LuZtfnt3zrn7L3PXuucfXZe75nXjJy19j47+4Q/5HPW2pJmQINeNW4Y17DVz1Xk7nggxX8zvuyyF6nZ2rW/y99qSZJGPgO5JEmSJEka4uq4aty4qGGtn1/88Ase2rKL/2acj7sMzkAuSdoSM5BLkiRJkqQhrI5h3FXjmgn1+vfcrda1ZRf/zTgfdxmcgVyStCVmIJckSZIkSUNWP1fVjsdV45op9XOrdb/woS23+E/G+bjL4NaufSl/qyVJGvkM5JIkSZIkaUiq66pxaabVzy+FSFtm8Z+M83GXwRnIJUlbYgZySZIkSZI0BNUxjLu6VjO5Xv8d8Esg2jKL/2T86KMv0QBJkra0DOSSJEmSpD6K/7+2EWr0UFEdAPt1Y1F93mGyoXjl3x1potxqXZIkSZqKDOSSJEmSpAl6frP/3uyyzb5RVEcaoHfnbnb5Zrds9mIhVev1VuuuIpckSZImm4FckiRJkjROt2721aI6zACDO3uzOwqpWq+3Wo8xXZIkSVK/GcglSZIkSWP0i6I6xgD1u7mQOnOrdUmSJKnJDOSSJEmSpKzVRXWEAZrzWCF11utV5G61LkmSJPWbgVySJEmSlHVNUR1hgOb8WyFVy/+ejMet1iVJkqR+MpBLkiRJkpLi/499uagOMEBz4vPIpTy3WpckSZKayEAuSZIkSUpaU1SHF6B5TxZSNbdalyRJkurOQC5JkiRJSvp/RXV4AZr3UCGNXf53ZTxutS5JkiT1koFckiRJkpR0d1EdXYDm3VtIYxfDd/73ZTxutS5JkiR1y0AuSZIkSUq6q6gOLkDz4u4N0ni51bokSZJUVwZySZIkSVKSgRymh4FcExVXhud/Z8bjVuuSJEnSRBnIJUmSJElJBnKYHgZydcut1iVJkqQ6mpWP3+PJB+xBSJIkSZKGNQM5TA8DuXrJrdYlSZKkQTOQS5IkSZKSDOQwPQzk6qV+brXuKnJJkiRprAzkkiRJkqQkAzlMDwO5eq2fW61LkiRJyjOQS5IkSZKSDOQwPQzk6ie3WpckSZImm4FckiRJkpRkIIfpYSBXP7nVuiRJkjTZDOSSJEmSpCQDOUwPA7n6rddbrbuKXJIkSUozkEuSJEmSkgzkMD0M5JpMvd5qPcZ0SZIkSZGBXJIkSZKUZCCH6WEg12Ryq3VJkiSp3wzkkiRJkqQkAzlMDwO5JluvV5G71bokSZIUGcglSZIkSUkGcpgeBnINUv73aTxutS5JkiQZyCVJkiRJSaMxkL/88pnF/fcfV9x33+Ji9eqlleNNe+CBV773qlVLKse6me7XznQxkGuQ3GpdkiRJ6jUDuSRJkiQpqd6B/Lvf3btYtOiDxYEH7lDsued7it1227bYddd3FPvu+97imGM+XJx33h7FmjUnVB43qMceO7GYNWtWyzbb/HHleOneexcXxx774eIrX5lbrF+/vHJ8Mp577rT2937zm19XOd5Nr6+dUWMg16C51bokSZLUSwZySZIkSVJSvQP57rtv1x57JzJ//uxi3bp6BurQ68i8445vbZ93/vl7VI5PhoGcyTGQa9D6uYrcrdYlSZK05WYglyRJkiQlTc9AHmbPfkuxceOKynNMRq8j87bbvqF93ooVn6gcnwwDOZNjIFcdxfCd/90aj1utS5IkacvMQC5JkiRJSmpuIF+6dE7x618fXdxxx5HFT35ycLFs2UdbA3I6kl9wwWcqzzEZvY7MP/3pF1pXkcct3x9//KTK8ckwkDM5BnLVlVutS5IkSRNlIJckSZIkJTU3kF9yyT6V4089tazjKu74fPL8nMmYzpHZQM7kGMhVV261LkmSJE2UgVySJEmSlDS1A3k499zd2+dsvfXrK8dLzzxzavHzn3+xuOKK/Ytbb13U+uf8nFK3kfn3v19WPProiR1efvnMynlh06YVxf33H1dce+2BxWWX7VfcdNPC1gien1caayB/+ulTipUrDymuvnpB8cADx23+/9ljf6/Q7bWPZe3aE4of//ig4pprFhT33HNM8eKLZ1TOGUT8IkP8ua+8cn7xq18d3b4VfvwM4r3bsOHV7/fCC6e339P168f/XPn4c8Y58dz5sVQ/P/dnn33l9YT4ueXHQ7z28pyJfo6h6fe1k4FcddbPrdYlSZKkLSsDuSRJkiQpaeoH8ksv3bd9zmtf+0eV4zFO77zz29vnpOL26HfeeWTlMd1G5vi88/y57r13ccc5jzxyfLFo0Qcr55Xmzn1n8fDDx1eeOx3Iw557vqfy2PhznnjiR8b8zPVurz113XUHtX6pIH/+sGDBDgPfNv766w9uvYb8uWP4j59neYv8yy/fr/2Yb37z1V94WL7845XnDDFkp8+VHw+T+bl/+tPvbp/zs58trBwPP/rR59vnfO5zf145Hpp+X8dmIFfdudW6JEmSNFYGckmSJElS0tQP5DEUl+fstNPbOo7FY/KBciwxyqaP6zYy9zKQ77HHq2PreGLofuKJkzselw/kE4mh93e/W9rXay8dccSHKs+Xi9f3i18cVnlsN3GF+5FHdn/+UlxZXz42HchPO23sgTyuAi/PGWsgn+zPPR3I44r3/HnDD3/42fY5Yw3kTb6vEzOQT10bN3tos5s3u3GzlSPqmqL692w8cW7+eKZeXPl/x2ZrCkmSJDWXgVySJEmSlDS1A/lddx3VMTyeddZu7WP33be449icOdu0brMdt9uOq85jXE6Pxy2wy8d2G5mvuuqA4rzz9mhfAR3ygTy+T3nssMPeX3zrW59q/RnyATWOpY/LB/K4Evnb3/5064rmCy74TOuXANLjMcSnj+/22sPFF/9tx3MsXLhja/i98cZDW3+urbZ6TcdzTHSr87FcdNFeHc+//fZvKs4/f4/WnyFuNZ9fFV/nQD7Iz33Qgbzp93ViBvLme3azf9/srKL6/sOwOb945Zc4JEmSVHcGckmSJElSUnMD+b77vrc1EF944V7FmWd+ouNYiKF03bpXBse4gjkdkpcunVPknxEetyeP5yzPiVuel8d6GZnDBz7wv9vn5QN5iME+brWefz1uKV4+Lr8tfDqQx7Hyz1SKP9uKFZ/o+LPH51yXx7u99vjs7Hje8py4ZXh+Tnyud3pr9K9+dW7lnPHEY9Pnj/f4+edPr5wXtxovz6lrIB/05z7IQN70+9qdgbzZVm32jaL6vsOwu2Iz/z1VkiSpzgzkkiRJkqSk5gbyicRImn6mdIyb5bG4ennTpupndYcnnzy5fV46VHcbmUvdBvLxxGibXn0ew2l5LB3I86ujU3FldHnevHnvan+922uP0bk8Hp+Rnh8v/eAHrw7Be+/9p5Xj40kH7nhPn376lMo5Ib2Svq6BfNCf+yADedPva3cG8uZ6rjCOM7NdW0iSJKm+DOSSJEmSpKSpH8gPOeQvK5/jnY6sO+/89tYAO570ueIq4Hh8t5G51MtAHmN4jKLxWekxiMYtvvff/886vu/ttx/RPr/Xgfz66w9unxe3YS+/3u21pyNw3N49fz9K55zzyfZ52277hsrzjOfwwz/Qflz8mfPjpSYG8kF/7oMM5E2/r90ZyJvruqL6fsNM81AhSZKkejKQS5IkSZKSmhvIlyyZU6xceUhroIxBuPx6/hncIT77OR1Ae/XQQ19qPb7byFzqNpDH6509+y2V75OLz8cuH9PrQL569dKO5yg/z7rba09v8d2riV5Hbpdd/qT9uPjM7/x4qYmBfNCf+yADedPva3cG8mZ6abOvFNX3G2YaV5FLkiTVlYFckiRJkpTU3EB+ySX7tL8en7mdDo1XX72g43HpSBtiUO8mBs4NG85oPb7byFyaaCBPb6Ud4lbe8dnXJ5zwkdZV71tt9Zr2sckM5PFa0+cvr6Kf6LXHZ3Snj4nXkL8PY5k/f3bl+48nHYpvuOHQyvFSEwP5oD/3yQ7kU/G+dmcgb6aHi+p7DTNRfEyAJEmS6shALkmSJElKmpqBPMTYnA6SMZqWxw48cIf2sa997W8qz9vNRCNzaryB/NlnT20N4uWxffZ5b+tzr9PHpn+2yQzk6RXk/Xx+evrZ57feuqhyfFBxa/Py+af6CvJBf+6THchD0+9rdwbyZrqtqL7XMFOtKyRJkjR4BnJJkiRJUtLUDeRr157QMUIvWvTB9rGvfGVu++sHH/y+yvN2021kLo03kF944V7tr8ct1ssrlFODDuTxmPR7lF/v9tp3223b9vH8Pa1DvN/l8w/6GeTjPX68gXzQn3s6kP/kJwdXjofxBvKm39fuDOTN9LOi+l7DTPVEIUmSpMEzkEuSJEmSkqZuIA/nn79H+3j45S//rvX1H/3o8x1ff+SR4yuPnchTTy3reHxcEZ6fE8YbyJcundP++rJlH608Lgw6kKdXS6dDbbfXfvzxf9U+tv32byo2blxRee5BnHnmJ9rPH7/A8PvfL6ucE8YbyC+/fL/21/ff/88qjws//ekXxnyPBv25f/GL728/9oILPlM5Hk46aZf2Oen73vT72p2BvJluKqrvNcxUjxWSJEkaPAO5JEmSJClpagfy+OznHXd8a/uc7bZ7Y2uYjCu243+XX58zZ5vWcJw//tFHTyy+/vV5la9v2rSiY2j97nf3rpwTxhvIzz331aug43Ox88fFZ6anz3/NNa9+hno6kI83MOefb37PPce0j3V77Q8++KWO48cdt/OYY+4ddxzZGqvzr3ezatWSjuePq7Ljz5Sf9/nP/0X7nHQgj9uTp4+Pn1H6uIce+lLHnQPSgXzQn3vclr18bPy9ir9f6fFrrz2w47WlA3nT72t3BvJmMpAzSgzkkiRJdWQglyRJkiQlTe1AHu6888iOYfLv/3631tdjiEy/Hp9TfuqpHyuuvHJ+cdFFexXHHvvh9tD6/e/Przxv3LY8ffy8ee8qHnjguI5zxhvIb7mlc+Q9+uidWqN23J47bgWfHgtLlsxpPzYdyMvXHVcnx2s8++x5rdeRHj/88A/0/drT25iHOD/G4Rjuv/WtTxXz589uH4vBO3/+bhYv3rnj+eNW78uXf7y46qoDWldmpz/XkA7kzz9/esfneW+99etbdwqIn9mee76n43Ehv8p+kJ/7XXcd1fHYGNjj790553yy47PVS+lAHpp+XydmIG8mAzmjxEAuSZJURwZySZIkSVLS1A/kIR9k42re+Hr6WeATmTv3nZXnTG/jXYoriNNzxhvIQ/pZ3GOJK8vTfy5vs54P5BPZe+8/bX0ed7+vPa6MTm8nPpEYePPn7+bpp08pdt31HZXnGk86kIdLL923ck4qvWtAPpCHQX7uCxfuWDkvlV6hng/kTb+vEzOQN5OBnFFiIJckSaojA7kkSZIkKanegTxuz10OijGa5sdLMSqnVx3HlcblsRjLYwjNB8q4ininnd7Wuup3/frllecMcdX3ttu+of2YfCCPx5fH7r+/8+ryF144vXVleP594/nK54nPJy+//p3v7Nn+s5Rfi+8/1tAcI21cDZ2/3n5ee4ghPT4vO3/+eC/jPYvnePnlztuM9yrG4rPO2q3j51KKK6vT75sP5CG+d/7Y+HPHc/7hD6e0vxZXmOePDZP9ucdt0b/85b+uPC6uJo8rwX/844PaX4tfgsgfH5p8X8dnIG8mAzmjxEAuSZJURwZySZIkSVJSvQN5neKzue+7b3HrSu21a0+oHJ/IE0+c3Pps7LGu1u5m3brlxc03H966FXzcPjw/Hp+RHbdkj9E3/jmG0xtuOLS4++6j2ufEkBvfP24fHsN7/hwT6eW1x+uK547XWb6OOsWfMd73+B7lZ4IfccSH2sPxWAN5KX5W8dg1a06oHOvFZH/u8bj4vPOf/Wxh8eyz4793E2n6fe1kIG8mAzmjxEAuSZJURwZySZIkSVLS8A7kDJdeB3J6ZSBvJgM5o8RALkmSVEcGckmSJElSkoGc3hjI62YgbyYDOaPEQC5JklRHBnJJkiRJUpKBnN4YyOtmIG8mAzmjxEAuSZJURwZySZIkSVKSgZzeGMjrZiBvJgM5o8RALkmSVEcGckmSJElSkoGc3nz96/OKHXd8a8vKlYdUjtMvA3kzGcgZJQZySZKkOjKQS5IkSZKSDOQwPQzkzWQgZ5QYyCVJkurIQC5JkiRJSjKQw/QwkDeTgZxRYiCXJEmqIwO5JEmSJCnJQA7Tw0DeTAZyRomBXJIkqY4M5JIkSZKkJAM5TA8DeTMZyPuxceOK4r77FresWXNC5fhEXn75zOL++49rPXb16qWV49TBQC5JklRHBnJJkiRJUpKBHKaHgbyZ6h3Izz57XnH00TsVCxfuWBx44A7F/vv/WbFgwQ7FGWfsWlxzzYLWOLxp04rK42aKX/3q6GLWrFktO+/89srxiTz22Intx26zzR9XjlMHA7kkSVIdGcglSZIkSUkGcpgeBvJmqncg33bbN7RH4PFst90bi1tvXVR57EwwUwbydeuWF+vXL698fSzxCwtPPbWs8vWZyUAuSZJURwZySZIkSVKSgRymh4G8maZ+IC8tXTqnePHFMyrPMcyGfSC/++6jikMO+cvW97j66gWV46l4PcuWfbR485tfVxx55Icqx2cmA7kkSVIdGcglSZIkSUkGcpgeBvJmam4g/+Y3dy9+/euji5tvPry45JJ9iiVL5hSvfe0fdYzkJ574kcpzDLNhH8jj1vbl9+g2kF966b7tcw3kkiRJSjOQS5IkSZKSDOQwPQzkzdTcQP6LXxxWOb569dJit9227RjJ/+d/jq2cN6wM5MPOQC5JklRHBnJJkiRJUpKBHKaHgbyZpnYgDxs2nFFsvfXrex6an3nm1OLnP/9iccUV+7c+uzz+OT9nLE8/fUrrNcQQfM01C4r77z+uePnlMyvnjeell85sDeKXXbZfsXLlIa1xf6oH8rVrTyh+/OODWq//nnuOGfeW9Bs3rigeffTEYt9939v+Hhdc8JnW10rpY+O1xBX+5bmf+9yfd5z73HOnVb7HZF5XiM9DL583fvbl1++9d3Fx+eX7FTfccGixZs0JlcdNjoFckiSpjgzkkiRJkqQkAzlMDwN5M039QB5i7C7PC7/97dLKOTFoxwidnlfacce3FnfeeWTlMTFqx6A9e/ZbKo8JcYv3f/qnz7TOyx9b2rRpRevz0fPbwYf0efsdyGMgLh/bbSC/7rqDOn6JILVgwQ7FY4+d1HH+tdceWDkv993v7t0696mnllWO5WIwz1/TZF5XWLTog+1z4ucet9vfaqvXdDx2+fKPVx43OY8WkiRJGjwDuSRJkiQpyUAO08NA3kzTM5DHldzpAP0f//GFjuMxouYD7FjiKuj0cTGa5+eM5eSTd6m8phDj8a67vqNy/liaGsiPOOJDle+Vi/cufX/7GciffHJyA/lkXldIB/L582dXHhN+97sTKt9vcgzkkiRJdWQglyRJkiQlGchhehjIm2l6BvKw/fZvap/7rW99qv31++5b3DGezpmzTevK47jNetwubk0FqAAADPJJREFUPa4eT4/HLb7T591llz9pfT3OO/XUjxXf+94+rSF9u+3e2PG43/zm+Mpr+vSn391xzsEHv6+48sr5rQE/ripPjzUxkF988d92fI/4TPEf/vCzxY03Hlqcd94eHVdex3OsX7+89bgnnji5dcvzj33s/7SPx+uNr5XK25jHFfJxJfjixTu3z507950d5+bv6WRfV0gH8tKxx364uP76g4vTT9+1OOmksX9ZYXIM5JIkSXU0a9OmTUUv8sF8EPlgDgAAwHB46KHfFNdd9wgwxVatWlX595E63LhZXNFdj3Qg//nPD6scT6VjdIyo8bVNm84sdtrpbe2vx8gbt0NPH7dhw4qOz9qOcTc9fssti4qLLtqr8rgXXjijYyT/xjc+2XF85cpDO0bcGMbT4yE+17s8HgN5fnwi+UCeH1+79sSOq+p/9KPPV86Jq7/jseU5X/3q3I7jMVyXx66+ekHl8an4ZYPy3COP/FDleGnQ15UP5N/+9qcrj6/Po0X17zgAUDeNfgZyAAAA2mIgv+yyF4ApZiBvyvQN5Ontto8+eqfW1268cWH7a3GF+caNKyqPC3HFdHlejLf58fFceOFele9ZSj9fPG4nnj82/OpXR7fPqXsgP+20j7ePl78wMJYf/OCz7fP23vtPO441MZAP+rrSgTze4/wXF+plIAeAYaKZm4EcAACAtgcf/E1x6aUvAFPMQN6U6RvI0yvFy6u541bo5ddigL700v3GVZ4X4irn/PlXr15anH32vOKLX3x/69bjcev19HvOm/eu9rnr1i3veL4Ys/PnC3ff3dxAnl5Rf9hh76/8eUvnnPPJ9nnxfqfP0c9A/s//3NtAPujrSgfyuOV9/vz1MpADwDDSzMtADgAAQNuDD24s8uEOaN4jj2yq/PtIHaZvIH/zm1/XPjeuPo6vpQNvPx588Evt533mmVOL44579fO1xxOjefmYO+88qv31eF35ay01OZCntyjvVf5amxjIB31d6UB+8cX7VJ6/XgZyABh2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>
