---
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.jpg')
marp: true
---

# **Software Architecture**

---

# **Agenda**

---

<!-- _class: lead -->

# **Promotion Definition**

---

# **Domain Specifications**
+ System should allow business users to create/modify promotions
+ Promotions should be created on e-commerce data provided from the catalog service
+ Downstream systems should be able to consume data in a simple flat structure called PAM (Promotion Applicability Map)

*PAM:- promotionId : offeringId*

---

<!-- _class: lead -->

![System Requirements](./diagrams/System_Requirements.png)

---

# **System Context View**
+ Level 1 in C4 Modelling
+ Describes key users of the system

*view image*

---

# **System Container View**
+ Level 2 in C4 Modelling
+ Describes the different containers and protocols used for communication

*view image*

---

# **System Component View**
+ Level 3 in C4 Modelling
+ Low-Level details of the system

*view image*

---

# **Microkernel Architecture**
+ Monolithic architecture
+ Plugin Model
+ Communication using REST & Request-Response method (sync)
+ *Anti-pattern:* Intercommunication between plugins 

---

<!-- _class: lead -->

# **Promotion Definition: Version 2**

---

# **Event Driven Architecture**

*view image*

--- 

<!-- _class: lead -->

# **Promotion Definition: Version 3**

---

# **Microservices Architecture**

*view image*

--- 

# **References**
+ [Software Architecture Fundamentals, Second Edition](https://learning.oreilly.com/videos/software-architecture-fundamentals/9781491998991)

+ [Fundamentals of Software Architecture
by Mark Richards, Neal Ford](https://www.thoughtworks.com/books/fundamentals-of-software-architecture)

+ [Domain-Driven Design: Tackling Complexity in the Heart of Software by Eric Evans](https://www.amazon.in/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215)

---

<!-- _class: lead -->

# **Thank You!**

--- 

<!-- _class: lead -->

# **Questions?**
