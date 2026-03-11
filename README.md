# Digital Forensics Project – Kali Linux Investigation Environment

## Project Overview

This project establishes a Kali Linux forensic workstation used to investigate digital evidence recovered from a hard drive found in a lake known to have been used as a dumping site for evidence related to cold cases.

The goal of this project is to demonstrate how Kali Linux can be used as a forensic environment to safely acquire, preserve, and analyze digital evidence while maintaining forensic integrity and proper investigative procedures.

## Environment

The forensic analysis environment was deployed using:

- Kali Linux
- Microsoft Azure Virtual Machine
- Secure SSH access
- Linux command-line forensic tools

This environment provides a secure and scalable platform for digital forensic investigations.

## Project Scenario

In this scenario, investigators recovered a hard drive from a lake that has historically been used as a dumping location for evidence in unsolved criminal investigations.

The purpose of this project is to prepare a forensic analysis environment capable of examining the recovered drive and identifying potential digital evidence.

Because storage devices recovered from water may be damaged or partially corrupted, the investigation will focus on safe forensic imaging and data recovery techniques.

## Forensic Tools Identified

The following categories of forensic tools were identified for use in this project:

### Disk Imaging
- dd
- dc3dd

### Disk Analysis
- Autopsy
- Sleuth Kit

### File Recovery
- TestDisk
- PhotoRec

### Memory Analysis
- Volatility
- Rekall

### Network Analysis
- Wireshark
- tcpdump

### Steganography Detection
- Steghide
- Stegsolve

These tools were selected because they are widely used in digital forensic investigations and are compatible with Kali Linux.

## Evidence Handling Strategy

To preserve the integrity of the recovered evidence, the following forensic procedures will be followed:

- Create a forensic disk image before analysis
- Use write-blocking techniques when accessing storage devices
- Verify evidence integrity using cryptographic hashes
- Maintain proper chain of custody documentation
- Conduct analysis only on forensic copies of evidence

Following these best practices ensures that digital evidence remains reliable and legally admissible.

## Repository Contents

This repository contains:

- Initial_Proposal.docx
- README.md

## Author

Digital Forensics Project  
Kali Linux Investigation Environment
