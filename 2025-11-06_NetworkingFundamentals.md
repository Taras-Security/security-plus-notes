Networking Fundamentals – OSI Model, TCP/UDP, IP, DNS, Ports

**Date:** November 6, 2025  
**Topic:** Basic networking foundations — understanding OSI, TCP/UDP, IP, DNS, and ports  

---

## Overview
Today I learned about the **OSI Model** and what it’s used for.  
It helps IT professionals identify which layer of the network a problem is happening in.

---

## OSI Layers (My Understanding)

### **Layer 1 – Physical**
All the physical parts — cables, wires, network cards, and signals that make connections possible.  

### **Layer 2 – Data Link**
Deals with **MAC addresses**, which act like identification numbers for devices or network cards.  

### **Layer 3 – Network**
Handles **IP addresses** and **routing packets** to other networks or devices.  
It doesn’t establish the connection — it just decides where packets go and how they get there.  

### **Layer 4 – Transport**
Where **TCP and UDP** operate.  
- **TCP** establishes a connection and ensures every packet is delivered correctly.  
- **UDP** doesn’t connect; it just sends packets quickly without checking if they all arrive.  

### **Layer 5 – Session**
Keeps the **communication/session** going between two devices or applications — like a phone call that stays active while data transfers.  

### **Layer 6 – Presentation**
**Translates or formats data** so it’s readable — decrypting, converting, or transforming what the computer understands into what people or apps can use.  

### **Layer 7 – Application**
This is the **visible layer** — browsers, apps, or anything you directly interact with.  
**DNS** runs here.

---

## DNS (Domain Name System)
**DNS** = *Domain Name System*.  
It translates human-readable domain names (like `google.com`) into IP addresses so the computer knows where to connect.  
It works on **Layer 7 (Application Layer)**.  

---

## Ports (What I Know So Far)
Ports are like doors or lanes for data to move through.  
Every application or device uses specific ports to send or receive information.  
Right now, I understand that ports help direct data to the right destination — for example, one port might handle login traffic while another handles messages.  
I still need to learn the exact common port numbers, but I understand their purpose.  

---

## Summary
- **OSI** helps identify where issues occur in a network.  
- **TCP** = reliable but slower.  
- **UDP** = faster but doesn’t check for errors.  
- **IP** identifies where data is going.  
- **DNS** translates names into IPs.  
- **Ports** define where data is sent inside a device.  

---

*End of today’s notes — Networking Fundamentals.*
