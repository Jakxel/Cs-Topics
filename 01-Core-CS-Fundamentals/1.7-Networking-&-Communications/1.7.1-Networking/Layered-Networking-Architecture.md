---
title: 'Layered-Networking-Architecture'
pubDate: 2025-05-02
description: 'OSI TCP-IP models scientific article.'
author: 'Victor Jakxel Islas Carreon'
---

# Layered Netowrking Architecture

## 1. Concept of layering
KLayering in networking is the practice of breaking down complex communication systems into a series of **smaller, manageable, and well-defined layers**, where each layer performs a specific function and interacts only whit its adjacent layers.
**Key Characteristics:**
- each layer is responsible for a **speific Aspect** of communication.
- layers **only communicate** with teh layer directly above or below them (encapsulation)
- Changes in one layer can be made **independently** of others(modularity)

### Why networking is divided into layers?
Dividing netwokring into layers offer several key advantages:
1. **Modularity:** Each layer has a clear role, making desgin, developent adn debugging easier.
2. **Interoperality:** Devices and software from different vendors can work together as long as they follow the standar protocolos at each layer.
3. **Simplified Troubleshooting:** Problems can be isolated to a specific layer
4. **Flexibility and Upgradability:** A protocol in one layer can be upgraded or replaced without affecting others.
5. **Standardization:**Layered models provide a universal framework for learning, designing, and implementing network systems.

## Real-World Analogy:

Think of sending a package:
>	1.	You write the letter (Application Layer).
>	2.	Put it in an envelope (Presentation Layer).
>	3.	Add sender/receiver info (Session Layer).
>	4.	Hand it to a delivery service (Transport Layer).
>	5.	The package is routed (Network Layer).
>	6.	Carried via trucks or planes (Data Link/Physical Layers).

Each step is independent but contributes to the final delivery.

## What is a OSI/TCP-IP model?

The model OSI and TCP-IP are concept models that describes how the data is transmitted for the net, each whit its different approach.
The OSI models it's a frame of reference more general and theoretical with seven layers, for other part the TCP-IP models its a more practical and used in the internet implementation, with four layers.

## OSI model
**OSI(Open Systems Interconection)**
A frame of concept reference what divides the communications in seven layers, each whit especifics functions
### Layers
1. **Application layer**
2. **Presentation layer**
3. **Sesion layer**
4. **Trasport layer**
5. **Net layer**
6. **Data enlace layer**
7. **Fisic Layer**

### Function
Provides a estructure for understand and analize the communication in net.

## TCP-IP model
**TCP/IP(Transmition Control Protocol / Internet Protocol)**
A practic model and used in the internet, that organize the net communication in four layers.

### Layers:
1. **Aplication layer**
2. **Transport layer**
3. **Internet layer**
4. **Data enlace layer / Fisic layer**

### Function
Defines the communication in internet and the gestion of data between devices.


