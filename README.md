# Network File Analysis with Wireshark: Decrypting DLL File & VirusTotal Attack Investigation #
This repository contains a detailed project on analyzing a network file using Wireshark, decrypting a DLL file, and investigating potential malicious activity through VirusTotal. The aim of this project is to showcase a systematic approach to identifying and mitigating cyber threats.

# Overview
Cybersecurity threats often hide in seemingly innocuous files or network traffic. In this project:
Wireshark was used to analyze network traffic and extract key insights.
A DLL file was decrypted to investigate its contents and behavior.
VirusTotal was leveraged to confirm the malicious nature of identified artifacts.

#Project Workflow
  Network File Analysis with Wireshark
  Imported the provided .pcap file into Wireshark.
  Applied filters to locate suspicious traffic, including encrypted traffic and unusual patterns.
  Identified the presence of a DLL file being transmitted.
  DLL File Extraction and Decryption
  Exported the suspected DLL file from the network stream.
  Decrypted the file using appropriate tools to reveal its contents.
  Observed behaviors such as code injection, system calls, or registry modifications.
  Attack Analysis Using VirusTotal
  Uploaded the decrypted DLL file to VirusTotal.
  Reviewed reports to confirm whether the file was flagged as malicious.
  Analyzed indicators of compromise (IOCs) such as hashes, domains, or IP addresses.


# Tools and Technologies Used
  Wireshark: For network traffic analysis and DLL extraction.
  VirusTotal: For analyzing the extracted DLL file for malicious signatures.
  Python/Bash Scripts: To assist in decryption and automate parts of the analysis.
  Virtual Environment: To ensure safe handling of potentially malicious files.



