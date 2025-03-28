# 🧠 CNT 4713 – Project 2: TCP Analysis with Wireshark

In this project, Pamela Uriarte and I explored the Transmission Control Protocol (TCP) using Wireshark. We captured a live trace by uploading a file to a remote server, then analyzed both our trace and a provided one to answer detailed questions about TCP behavior.

## 👥 Group Members
- Nicholas
- Pamela Uriarte

## 🔍 What We Did
- Captured live TCP traffic during a file upload to `gaia.cs.umass.edu`
- Analyzed TCP sequence numbers, ACKs, and RTT using Wireshark
- Used Time-Sequence-Graph and Round-Trip-Time-Graph to examine congestion control
- Calculated throughput and reviewed retransmissions, window sizes, and slow start behavior

## 📁 Files Included
- `project2-report.pdf`: Our answers with annotated Wireshark screenshots
- `my-trace-file.pcap`: Our personal captured trace
- Supporting screenshots included in the report

## 🧰 Tools Used
- Wireshark (packet capture and analysis)
- Provided trace file from [Wireshark Labs](https://www-net.cs.umass.edu/wireshark-labs/wireshark-traces.zip)

## 🎯 Key Topics
- TCP connection setup (SYN, SYN-ACK)
- Sequence and acknowledgment numbers
- Flow and congestion control
- TCP throughput calculation
- Slow start and congestion avoidance
