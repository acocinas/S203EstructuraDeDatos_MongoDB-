# 🏥 Cul d'Ampolla - Optical Store Database

## 📌 Project Overview
This project aims to model a NoSQL database for an optical store called **Cul d'Ampolla**, using **MongoDB** with **mongosh** and **JSON Crack v2** for visualization.

## 🎯 Objectives
- Learn how to model **NoSQL databases**.
- Create different **databases** in **MongoDB**.
- Implement a database for managing **clients** and **glasses sales**.

## 🏗️ Database Structure

### 🏢 **Suppliers**
Each pair of glasses is supplied by a provider. The database stores:
- **Name**
- **Address** (street, number, floor, door, city, postal code, country)
- **Phone**
- **Fax**
- **NIF**

### 👓 **Glasses**
Each pair of glasses has:
- **Brand**
- **Lens prescription** for each eye
- **Frame type** (rimless, plastic, metal)
- **Frame color**
- **Lens color** (left and right)
- **Price**

### 👤 **Clients**
Each client has:
- **Name**
- **Address** (street, city, postal code)
- **Phone**
- **Email**
- **Registration date**
- **Referred by** (if applicable)

### 🛒 **Sales**
When glasses are sold, we store:
- **Client who purchased the glasses**
- **Employee who made the sale**
- **Date and time of the transaction**

## 📌 Exercises

### 📍 **Exercise 1**
Design the database based on the graphical user interface from the **client's perspective**.

### 📍 **Exercise 2**
Design the database based on the graphical user interface from the **glasses' perspective**.

## 🛠️ Technologies Used
- **MongoDB** 🗄️
- **mongosh** 🖥️
- **JSON Crack v2** 🔍

---
📌 *This database will help "Cul d'Ampolla" manage their optical store efficiently!*

