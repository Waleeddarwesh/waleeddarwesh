# 👋 Hi, I'm Waleed Darwesh Saad
### 🛠️ Django Developer & Cloud DevOps Engineer
**Computer Science Graduate** | **NTI Cloud DevOps Trainee**

<p align="left">
  <a href="https://www.linkedin.com/in/waleeddarwesh1/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>

  <a href="mailto:Waleeddarweshsaad1@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>

  <a href="https://hub.docker.com/r/waleeddarwesh/">
  <img src="https://img.shields.io/badge/Docker%20Hub-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  </a>

  <a href="https://github.com/Waleeddarwesh">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 👨‍💻 Professional Summary
Result-oriented **Django Developer** and **Cloud DevOps Engineer** with a solid foundation in backend architecture and scalable systems. Currently leveraging intensive **NTI technical training** to specialize in Cloud infrastructure, bridging the gap between robust software development and automated, efficient deployment.

- 🎓 **Education:** B.Sc in Computer and Information Technology (**GPA: 3.63/4.0**)
- 🛡️ **Certification:** Red Hat Certified System Administrator (**RHCSA**) | Cisco Certified Network Associate (**CCNA**)
- 🚀 **Current Focus:** Advanced Networking, Linux System Administration, and CI/CD Automation.

---

## 🛠️ Technical Arsenal

### **Backend Development**
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
</p>

### **Infrastructure & Fintech**
<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" />
  <img src="https://img.shields.io/badge/Channels-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Stripe-6772E5?style=for-the-badge&logo=stripe&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
</p>

### **Cloud & DevOps**
<p align="left">
  <img src="https://img.shields.io/badge/Red_Hat-EE0000?style=for-the-badge&logo=red-hat&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=red-hat-openshift&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
</p>

---

## 🌟 Featured Projects

### 🧶  [**Craft**](https://github.com/Waleeddarwesh/craft-v1.2) | *(Graduation Project - Grade A+)*
*An enterprise-scale, multi-vendor ecosystem orchestrating E-commerce, Logistics, E-Learning, and Real-time Social Networking into a single, high-performance architecture.*

> 🔒 **Note:** Some source code repositories or versions may be **private** to protect project structure, business logic, and sensitive implementation details.
> The architecture spans across 3 major iterations:
> - **[Craft V1.0](https://github.com/Waleeddarwesh/craft-v1.0)** - Initial architecture, core marketplace, supplier/customer/delivery roles, and e-learning MVP.
> - **[Craft V1.1 ](https://github.com/Waleeddarwesh/craft-v1.1)** - Production-ready improvements including Docker, Daphne ASGI, Arabic localization, Redis, Celery, and CI/CD.
> - **[Craft V1.2](https://github.com/Waleeddarwesh/craft-v1.2)** - Advanced backend features including audit logs, dispute resolution, support tickets, FCM push notifications, supplier analytics, and privacy-ready enhancements.
> - **[Craft V2.0 (Microservices)](https://github.com/Waleeddarwesh/craft-v2-microservices)** - Next-generation architectural evolution transitioning the monolithic backend into a distributed microservices ecosystem for isolated deployments, high availability, and infinite scalability.

#### 🏗️ **Core System Capabilities**
- **Multi-Vendor Marketplace & Logistics:** Engineered a comprehensive e-commerce engine handling product variants, dynamic carts, Stripe payment orchestration, advanced return policies, and a dedicated delivery routing module for drivers.
- **E-Learning Integration:** Built a fully-featured digital academy allowing suppliers to upload video courses, track student enrollment progress, and issue automated certificates.
- **Social & Engagement Engine:** Developed a real-time social layer where users can follow suppliers, browse dynamic content feeds, and receive personalized product recommendations driven by an interaction-history algorithm (Views/Carts/Purchases).
- **Real-Time Communication:** Designed persistent, bi-directional WebSocket infrastructure using **Django Channels** and **Redis** for secure instant messaging and live push notifications (via Firebase Cloud Messaging).
- **CRM & Conflict Resolution:** Implemented a priority-based Support Ticket system and a multi-party Dispute Resolution workflow to mediate conflicts between buyers and suppliers safely.
- **Automated Analytics & Reporting:** Leveraged **Celery** and **Celery Beat** to offload heavy background processing, generating real-time supplier dashboards (total sales, return rates, top products) without blocking the main event loop.

#### 🛡️ **Enterprise Security & DevOps Operations**
- **Granular Access Control:** Engineered a complex Role-Based Access Control (RBAC) matrix defining strict permissions across four distinct interfaces: Customers, Suppliers, Delivery Personnel, and System Admins.
- **Compliance & Hardening:** Implemented strict GDPR data portability tools (JSON data export/soft delete), brute-force account lockout protection, Django `AUTH_PASSWORD_VALIDATORS`, and comprehensive Audit Logging for all admin actions.
- **Cloud-Native Infrastructure:** Fully containerized the stack using **Docker** & **Docker Compose**. Deployed on Railway utilizing **Daphne ASGI** with native HTTP/2 support, persistent PostgreSQL connection pooling, and dynamic, on-the-fly Arabic database translation using `django-modeltranslation`.


### 🚄 [**SwiftRide**](https://github.com/Waleeddarwesh/SwiftRide)

*Engineered a high-performance transit ticketing ecosystem using Django and event-driven architecture.*

* **Real-time Synchronization:** Built a live train tracking and notification system using Django Channels (WebSockets) and Redis for sub-second updates.
* **Secure Ticketing:** Developed an encrypted QR-based validation system with automated concurrency-safe seat reservation and ticket generation.
* **Robust Payments:** Integrated Stripe to handle complex financial workflows, including secure checkouts, refunds, and multi-currency transactions.
* **Scalable Infrastructure:** Implemented Celery for background task processing and containerized the entire stack with Docker for production deployment.


---

<p align="center">
  <b>Arabic (Native) | English (Professional)</b><br>
  <i>"Building the future, one automated endpoint at a time."</i>
</p>
