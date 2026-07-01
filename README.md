# 🎵 Homelab Audio Streaming Platform

> A fully self-hosted audio streaming platform built with Navidrome, Docker, WSL Ubuntu, and Tailscale, providing secure access to a personal audio library from anywhere without subscriptions, advertisements, or third-party streaming services.

---

## 📖 Overview

This project demonstrates how to build a complete self-hosted audio streaming solution that gives users full ownership and control over their audio collection.

Instead of relying on commercial streaming platforms that require subscriptions or display advertisements, this solution allows audio files to be stored, managed, and streamed directly from a personal server.

The project combines Linux administration, containerization, networking, and self-hosting technologies into a practical real-world deployment.

---

## 🎯 Project Objectives

- Eliminate dependence on subscription-based audio services
- Maintain complete ownership of audio files
- Learn Linux administration through WSL Ubuntu
- Gain hands-on experience with Docker containers
- Implement secure remote access using Tailscale
- Develop practical networking and self-hosting skills
- Build a project relevant to cloud and infrastructure engineering

---

## 🏗️ Architecture

```text
+-------------------+
|     Smartphone    |
| (Amperfy Client)  |
+---------+---------+
          |
          | Tailscale VPN
          |
+---------v---------+
|    Host Machine   |
|   Windows + WSL   |
+---------+---------+
          |
          | Docker
          |
+---------v---------+
|     Navidrome     |
| Audio Streaming   |
|      Server       |
+---------+---------+
          |
          | Access
          |
+---------v---------+
|   Audio Library   |
|   MP3 / Audio     |
+-------------------+
```

## 📚 Lessons Learned

This project reinforced the value of **compound learning**.

Previous experience with Linux, networking, and containerization significantly reduced deployment time and troubleshooting effort.

Building practical projects with a real purpose accelerates learning and develops a deeper understanding of the underlying technologies.

By the end of the project, I not only had a working solution but also a complete understanding of:

- How Docker containers operate  
- How Navidrome serves media content  
- How Linux manages files and services  
- How Tailscale securely connects devices  
- How data flows across the system

-------

## Author

**Mohammed Zuoriki**

Cybersecurity Student | Cloud Security Enthusiast

Linkedin: https://www.linkedin.com/in/mohammed-zuoriki-856133250/

---
