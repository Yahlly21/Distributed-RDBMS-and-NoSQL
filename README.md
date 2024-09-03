# Distributed RDBMS and NoSQL Messaging System

## Liya Gurevich and Yahlly Schein

## **Project Overview**
This project focuses on the implementation of a distributed messaging system that leverages both RDBMS and NoSQL databases. The system is designed to manage communication between groups of smartphone users, handling user information, devices, conversations, and messages.

### **The project consists of two primary components:**

**Persistent Storage:** Implemented using MongoDB, this component stores essential data for system functionality and analytical purposes. The data includes user profiles, devices, conversations, and messages.

**In-Memory Cache:** Implemented using Redis, this component handles fast operations critical to the system’s real-time performance.

### **Features**

The system implements core operations, reporting functions, and recovery mechanisms to ensure efficient and scalable performance.

### **Performance Considerations**

The system is optimized for performance, with a focus on minimizing the runtime complexity of operations. For example, operations are implemented with O(1) complexity wherever possible, ensuring fast retrieval and updates.
