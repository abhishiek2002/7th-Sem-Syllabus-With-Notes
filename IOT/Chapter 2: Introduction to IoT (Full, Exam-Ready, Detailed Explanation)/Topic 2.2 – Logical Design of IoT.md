Great. Now moving to **Topic 2.2 – Logical Design of IoT**.
Again, direct, precise, and exam-oriented — no bloat.

---

# **Topic 2.2 – Logical Design of IoT**

Logical design describes **how IoT systems work internally**, not the hardware.
Think of it as the *software + data flow + communication logic* behind the devices.

Most exam questions come from:

* Functional Blocks
* Communication Models
* Communication APIs

Let’s break them down cleanly.

---

# **1. Functional Blocks of IoT**

There are **five standard functional blocks**.
If you remember this list, you can answer almost any “Explain IoT design” question.

### **(i) Device (Sensors/Actuators)**

Collects raw data using sensors and performs actions using actuators.

### **(ii) Communication**

Transfers data between devices, gateways, and cloud using Wi-Fi, Bluetooth, MQTT, etc.

### **(iii) Services**

Handles:

* data processing
* data storage
* device control
* analytics

Cloud services are part of this block.

### **(iv) Application**

User-facing part: dashboards, apps, websites, monitoring tools.

Examples:
smart home app, health monitoring app.

### **(v) Management**

Takes care of:

* device configuration
* network management
* fault detection
* security

This block keeps the system stable.

---

# **Diagram Hint (For exams)**

*(Don’t draw here, just remember the layout)*

Device → Communication → Services → Application
→ Management (parallel)

If you draw this cleanly, you secure extra marks.

---

# **2. IoT Communication Models**

There are **four**, and examiners love them.

### **(i) Device-to-Device**

Two or more devices communicate directly.
Example: smart bulb ↔ remote via Bluetooth.

### **(ii) Device-to-Cloud**

Device sends data to cloud; cloud processes and sends actions.
Most common model in IoT.

### **(iii) Device-to-Gateway**

Gateway sits between device and cloud.
It performs:

* protocol translation
* data filtering
* local decisions

Used in smart homes and industries.

### **(iv) Backend Data-Sharing Model**

Data stored in one cloud is shared with multiple applications.
Example: health data shared between hospital + insurance app.

---

# **3. IoT Communication APIs**

APIs allow software applications to communicate with IoT devices/services.

Most important APIs:

### **(i) REST API**

* Uses HTTP
* Standard request/response
* Used for reading sensor data or sending commands

### **(ii) MQTT API**

* Lightweight publish/subscribe
* Best for continuous IoT data
* Extremely common in real IoT systems

### **(iii) WebSocket API**

* Real-time two-way communication
* Used in dashboards, live updates

### **(iv) CoAP**

* Constrained Application Protocol
* Lightweight version of HTTP for low-power devices

---

# **Exam-Ready Answer Structure**

If the question is:

**“Explain the logical design of IoT.”**

Write:

* Functional blocks
* Communication models
* Communication APIs

Then give 1–2 lines each. Full marks.

---
