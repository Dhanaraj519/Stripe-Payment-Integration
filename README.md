# Stripe Payment Integration – Java Spring Boot | HulkHire Tech

**Role:** Java Developer Intern
**Company:** HulkHire Tech, Hyderabad
**Duration:** Feb 2025 – Present

---

## 📝 **Project Overview**

This project is a **microservices-based Stripe Payment Integration System** developed for HulkHire Tech’s AI-based assessment platform.
My responsibility was to design and build the **core payment-processing engine**, including Stripe session handling, security mechanisms, notification processing, and error-handling modules.

The project provides **end-to-end PSP (Payment Service Provider) integration**, enabling the client application (HulkHire.com) to initiate payments, track payment status, and process Stripe notifications securely and reliably.

---

## 🎯 **Key Contributions**

### 🔹 **1. Core Payment Processing System**

* Designed & developed the **central payment-processing logic** using Java + Spring Boot.
* Built modular & scalable microservices for:

  * `payment-processing-service`
  * `stripe-provider-service`

### 🔹 **2. Stripe API Integration**

* Integrated Stripe’s REST APIs to:

  * Create a payment session
  * Retrieve an existing session
  * Expire sessions programmatically
* Implemented idempotent & reliable API workflows using **Spring Boot + Stripe Auth Security**.

### 🔹 **3. Payment Status Management**

* Designed a payment-tracking module to ensure **100% reliable** status updates.
* Handled all states — *initiated, processing, completed, failed, expired*.

### 🔹 **4. Notification Processing (Webhooks)**

* Built Stripe webhook notification handler using:

  * HmacSHA256 signature verification
  * Custom error codes
  * Spring exception handling
* Ensured secure & consistent event processing for payments.

### 🔹 **5. Microservices Architecture**

* Implemented independently deployable services using:

  * Spring Boot
  * REST APIs
  * AWS EC2 (deployment)
  * AWS RDS (MySQL)

### 🔹 **6. Error Handling & Debugging**

* Designed a complete error-handling framework using:

  * Custom error codes
  * Spring `@ControllerAdvice`
  * Logging with Slf4J + Logback
* Strong debugging & issue-resolution contribution.

### 🔹 **7. Asynchronous Integration**

* Integrated **ActiveMQ** for async communication between microservices.
* Built producers & consumers for event-driven processing.

### 🔹 **8. AWS Cloud Integration**

* Worked with:

  * AWS EC2 for microservice hosting
  * AWS RDS for MySQL
  * AWS Secret Manager for secure key handling

### 🔹 **9. Agile Collaboration**

* Participated in sprint planning, design discussions, peer reviews, and deployments.
* Delivered all assigned tasks **on time**, earning:
  🏆 **STAR Performer of the Month**

---

## 🛠️ **Tech Stack**

| Category            | Tools / Technologies               |
| ------------------- | ---------------------------------- |
| **Languages**       | Java                               |
| **Frameworks**      | Spring Boot, Spring Boot JDBC      |
| **Microservices**   | REST APIs, Modular Services        |
| **Database**        | MySQL (RDS)                        |
| **Build Tools**     | Maven                              |
| **Version Control** | Git, BitBucket, SourceTree         |
| **Testing**         | JUnit, Mockito                     |
| **Cloud**           | AWS EC2, RDS, SecretManager        |
| **Async Tech**      | ActiveMQ                           |
| **IDEs**            | Eclipse, DBEaver                   |
| **Other Tools**     | Lombok, SonarLint, GSON, Mobaxterm |
| **Logging**         | Slf4J + Logback                    |

---

## 💡 **How to Explain This Project in an Interview**

Use this structure during interviews:

### ✔ **Project Introduction**

“We are building a Stripe Payment Integration System for HulkHire Tech.
The client application (HulkHire.com) integrates with our services to handle all Stripe-based payments.”

### ✔ **Your Role**

“I work on the **core payment-processing** and **stripe-provider** microservices.
I was involved in both **design** discussions and **hands-on development** of critical components.”



