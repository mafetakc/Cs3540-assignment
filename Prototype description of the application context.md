# C++ Prototype Descriptions

This file provides descriptions of four prototype systems implemented in C++.

---

## 1. Voice Recognition Prototype
- Simulates a very basic **voice recognition system**.  
- Compares two sets of voice features (stored vs. input) using **Euclidean distance**.  
- The smaller the distance, the closer the match between the voices.  
- **Output:** A "voice match score" representing similarity.  

---

## 2. Biometric Security Prototype
- Implements a simple **biometric authentication system**.  
- Uses **Euclidean distance** between stored biometric data and an input sample.  
- If the distance is below a certain threshold (5.0), access is granted; otherwise, access is denied.  
- **Output:** "Access Granted" or "Access Denied."  

---

## 3. Mobile Financial Services Prototype
- Simulates a **basic banking application** for a customer.  
- A `Customer` class stores name and account balance.  
- Functions allow deposits, withdrawals (with insufficient funds check), and displaying balance.  
- Demonstrates **object-oriented programming (OOP)** with simple financial operations.  

---

## 4. Health AI Prototype
- Mimics a **health monitoring system**.  
- Stores a short history of heart rate samples and calculates the average.  
- A new heart rate measurement is compared to the average.  
- If the new value is too far (±15) from the average, it raises an anomaly alert; otherwise, it reports normal status.  
- **Output:** Either an alert message or a normal reading.  
