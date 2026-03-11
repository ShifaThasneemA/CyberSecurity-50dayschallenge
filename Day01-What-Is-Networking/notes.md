# Day 1 – TryHackMe: What is Networking?

Room: What is Networking?
Platform: TryHackMe

## Overview

This room introduces the basic concepts of computer networking and explains how devices communicate with each other across networks. Networking is an essential concept in cybersecurity because most attacks and defenses happen through networks.

## What is Networking?

A network is simply a group of devices connected together so they can communicate and share resources. These devices can include computers, smartphones, servers, and many other internet-enabled devices. A network can range from a small local network with two devices to a massive global network like the Internet.

## The Internet

The Internet is essentially a large network made up of many smaller networks connected together. It allows devices around the world to communicate and exchange data. The early form of the Internet started with ARPANET in the late 1960s, and later the World Wide Web was created by Tim Berners-Lee in 1989. ([Medium][1])

## Identifying Devices on a Network

Devices on a network are identified using two main types of addresses:

* **IP Address (Internet Protocol)** – A logical address used to identify devices on a network.
* **MAC Address (Media Access Control)** – A unique physical address assigned to a network interface.

IP addresses can be public or private depending on whether the device is connected to the Internet or a local network. ([Medium][1])

## Networking Tool: Ping

The `ping` command is used to test the connection between two devices on a network. It uses the **ICMP (Internet Control Message Protocol)** to check whether a target system is reachable and to measure response time. ([Medium][1])

Example command:
ping 8.8.8.8

## Key Learnings

* Understanding the basic concept of networks
* Difference between Internet and local networks
* Importance of IP and MAC addresses
* Using the ping command to test connectivity

## Conclusion

This room provided a strong introduction to networking fundamentals. Understanding networking is crucial for cybersecurity because it helps security professionals analyze how systems communicate and identify potential vulnerabilities in network communication.

[1]: https://medium.com/%40hammaadm/network-fundamentals-thm-2016fd50024e?utm_source=chatgpt.com "TryHackMe, What Is Networking & Answers"
