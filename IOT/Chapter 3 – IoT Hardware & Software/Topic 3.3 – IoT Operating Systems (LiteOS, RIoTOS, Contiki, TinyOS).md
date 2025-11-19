Alright, moving to **Topic 3.3 – IoT Operating Systems**.
This topic looks theoretical, but it’s extremely easy marks if you know the purpose of each OS and one or two features.

We’ll cover **exactly what exams expect** — not the useless deep-dive.

---

# **Topic 3.3 – IoT Operating Systems**

IoT Operating Systems are lightweight OSes designed for:

* low memory devices
* low power consumption
* sensor/actuator control
* wireless communication
* real-time performance

The four OSes you must know:

1. **LiteOS**
2. **RIoTOS**
3. **Contiki OS**
4. **TinyOS**

Let’s take them one by one.

---

# **1. LiteOS**

LiteOS is a **lightweight, Unix-like operating system** developed by Huawei for IoT devices.

### **Key Points (write these):**

* Open-source, lightweight
* Supports real-time operations
* Supports IoT protocols (NB-IoT, CoAP, etc.)
* Easy to develop because of Unix-like structure
* Designed for smart homes, wearables, industrial IoT

### **Why it matters:**

It provides multitasking and good security while running on low-power devices.

---

# **2. RIoTOS (RIOT OS)**

RIOT is an OS designed specifically for **low-power, networked IoT devices**.

### **Key Points:**

* Open-source
* Supports multithreading (rare in IoT OS)
* Extremely low memory usage
* Supports IPv6, 6LoWPAN, CoAP
* Written mostly in C

### **Why it matters:**

It allows complex networking on very small devices — perfect for sensor networks and embedded IoT.

---

# **3. Contiki OS**

One of the most popular IoT OSes, especially in academic and research environments.

### **Key Points:**

* Open-source
* Focused on **wireless sensor networks (WSN)**
* Supports IPv6 + 6LoWPAN (key IoT protocols)
* Has a built-in network simulator called **Cooja**
* Works on extremely low-memory hardware

### **Why it matters:**

Contiki is widely used for teaching and research because of Cooja simulator and strong networking support.

---

# **4. TinyOS**

TinyOS is one of the earliest IoT OSes created specifically for sensor networks.

### **Key Points:**

* Open-source
* Written in ***nesC*** (a variant of C designed for embedded systems)
* Extremely lightweight and event-driven
* Ideal for tiny battery-powered devices
* Limited multitasking

### **Why it matters:**

Designed for highly resource-constrained IoT nodes in WSNs.

---

# **Short Comparison Table (Exam Gold)**

| Feature       | LiteOS                   | RIOT OS              | Contiki OS                 | TinyOS            |
| ------------- | ------------------------ | -------------------- | -------------------------- | ----------------- |
| Type          | Unix-like IoT OS         | Multithreaded IoT OS | WSN-focused OS             | Event-driven OS   |
| Memory Use    | Low                      | Very Low             | Very Low                   | Extremely Low     |
| Programming   | C/C++                    | C                    | C                          | nesC              |
| Networking    | Strong                   | Strong               | Very strong (IPv6/6LoWPAN) | Basic             |
| Best Use Case | Smart devices, wearables | Embedded IoT devices | Sensor networks, research  | Tiny sensors, WSN |

This table alone can fetch full marks.

---

# **Exam-Ready Short Note**

If asked:

**“Explain IoT Operating Systems.”**

Write:

* LiteOS: Unix-like, low-power, real-time
* RIOT: multithreaded, low memory, IPv6 support
* Contiki: best for WSN, includes Cooja simulator
* TinyOS: ultra-lightweight, event-driven, written in nesC

Done. Full marks.

---

If you’re ready, next is:

**Chapter 4 — IoT Architecture & Reference Model (Topic 4.1: Introduction to Architecture)**

Say **"next"**.
