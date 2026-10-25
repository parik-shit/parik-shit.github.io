---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research interests
======
Network security and privacy, networking architecture and protocol design, and applied cryptography, particularly how cryptographic and access-control mechanisms behave once deployed in working networks.

Education
======
* B.Tech, Computer Science & Engineering, DCRUST, Murthal, Sonipat, India, Oct 2020 – Aug 2024
  * CGPA 7.6 / 10
  * Security and cryptography electives: Network Security & Cryptography; Information Security & Data Hiding; Blockchain Technology & Applications; Foundations of Blockchain Technology
* Senior Secondary (Class XII), Physics, Chemistry & Mathematics, GSSS Alahar, Haryana, India (HBSE), 2020
  * 90.4% aggregate; ranked 1st of 162 students in the 2020 PCM cohort

Professional experience
======
* Apr 2025 – Aug 2026: Junior Network Analyst
  * GuestTek Interactive Entertainment Ltd., Gurgaon (on-site)
  * Network infrastructure for multi-property hospitality operators (Marriott, Hilton)
  * Configured and maintained switched access networks across multi-property deployments: VLAN segmentation separating guest, staff and management traffic, per-VLAN DHCP scopes and relay, and dedicated voice VLANs carrying IP telephony alongside data on shared access ports
  * Applied QoS marking and queueing so voice traffic held priority over bulk guest data on shared uplinks
  * Wrote and maintained access control lists filtering by protocol and port, restricting inter-VLAN reachability, limiting management-plane access to authorised subnets, and blocking guest-to-infrastructure paths
  * Diagnosed connectivity, addressing and reachability faults on live properties using packet capture, interface counters and device logs
  * Built monitoring over the Cisco Meraki and Aruba Central APIs, collecting live device telemetry across distributed sites, with scheduled polling and cached state to respect vendor rate limits
  * Put the vendor APIs behind one internal interface, reconciling their differing data models, authentication schemes and error behaviour
  * Ran the supporting services on AWS EC2 under Docker behind Nginx (TLS termination, rate limiting), with Redis and PostgreSQL; automated release and post-deploy validation on CentOS via Bash and CI/CD

* Apr – Jun 2024: Associate Software Engineer Intern
  * Aarohin Technologies (on-site)
  * Hardware modelling and simulation
  * Implemented a C++/SystemC scaler model of ARM AMBA bus peripherals, reproducing clock-scaling and interconnect behaviour in a virtual SoC environment
  * Built the simulation components using templates and concurrency primitives; automated build and test flows with Make and CMake, debugging with GDB and Valgrind

Selected projects
======
  <ul>{% for post in site.portfolio %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

{% comment %}
Hidden until there is content for them. Move a section outside this comment block to show it again.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
{% endcomment %}

Technical skills
======
* **Networking:** VLAN segmentation and trunking, voice VLANs, access control lists (protocol- and port-based filtering), inter-VLAN routing, QoS marking and queueing, DHCP scopes and relay, TCP/IP troubleshooting, packet capture; Cisco Meraki and Aruba Central
* **Systems:** Linux (CentOS), Docker, AWS EC2, Nginx (TLS termination, reverse proxy, rate limiting), CI/CD, Bash, Git
* **Languages:** C++, Python, TypeScript, JavaScript, SQL
* **Data:** PostgreSQL (schema design, query and index tuning), Redis
* **Tools:** SystemC, GDB, Valgrind, CMake, Prisma

Achievements
======
* Runner-up of 40 teams, Smart India Hackathon 2023, a national-level competition; problem statement: *Blockchain-Based Academic Certificate Validation*

Languages
======
* English: IELTS 7.5 (Academic)
* Hindi: native
