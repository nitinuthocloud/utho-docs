---
weight: 30
title: "Access NAT Gateways"
title_meta: "How to Access and Manage NAT Gateways in Utho Cloud"
description: "Learn how to access and view NAT Gateways in Utho Cloud to manage outbound internet traffic for private subnets securely."
keywords: ["utho cloud", "NAT gateways", "access NAT gateway", "private subnet internet", "network security"]
tags: ["utho platform", "networking", "NAT gateways", "VPC"]
date: "2024-03-07T17:25:05+01:00"
lastmod: "2024-03-07T17:25:05+01:00"
draft: false
aliases: ["/products/networking/VPC/NAT Gateways/Access NAT Gateways"]
icon: guides
tab: true
---

# **Access NAT Gateways in Utho Cloud**

This guide walks you through accessing the **NAT Gateway** section in Utho Cloud, where you can view and manage NAT Gateways that enable secure outbound internet access for private subnet resources.

## **Step 1: Login or Sign Up to Utho Cloud**

1. Go to the [Utho Cloud Console](https://console.utho.com/login).
2. If you **already have an account**, enter your credentials and click **Login**.
3. If you **don’t have an account**, click on [Signup](https://console.utho.com/signup).
4. After logging in, you will be redirected to the **Utho Cloud Dashboard**.

## **Step 2: Navigate to the NAT Gateways Section**

You can access the **NAT Gateways** section using one of the following methods:

### **Method 1: Sidebar Navigation**

1. In the dashboard, locate the **sidebar menu** on the left.
2. Scroll down to the **Networking** section.
3. Click on **NAT Gateways**.
4. You will be redirected to the **NAT Gateway Listing Page**.

### **Method 2: Using the Search Bar**

1. Use the search bar at the top of the sidebar.
2. Type **"VPC"** in the search bar.
3. Click on the **VPC** option from the search results.
4. This will expand the VPC menu in the sidebar.
5. Within the expanded VPC menu, click on **NAT Gateways**.
6. You will be redirected to the **NAT Gateways Listing Page**.

### **Method 3: Direct URL Access**

If you're already logged in, you can access it directly:

👉 [Go to NAT Gateways](https://console.utho.com/vpc/natgateways)

---

## **What You'll See in the NAT Gateway Section**

Upon entering the **NAT Gateway Listing Page**, you will see the following details for each listed NAT Gateway:

1. **Name**: The user-defined name of the NAT Gateway.
2. **Internet Gateway ID**: ID of the internet gateway associated with the NAT Gateway.
3. **Subnet ID**: The subnet to which this NAT Gateway is connected.
4. **Type**: The gateway type (e.g., Static).
5. **Created At**: Timestamp when the NAT Gateway was created.

These listings provide a clear overview of all configured NAT Gateways and their networking context, helping you monitor and manage cloud internet access effectively.

---

NAT Gateways in Utho Cloud are essential for secure and efficient communication between private subnets and the internet. By accessing this section, you can view existing configurations and proceed to create, manage, or destroy NAT Gateways as needed for your network design.
