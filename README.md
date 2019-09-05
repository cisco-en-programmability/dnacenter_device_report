# Cisco DNA Center Device Report



This is a Python sample code to showcase how to create a Cisco DNA Center managed devices report.

**Cisco Products & Services:**

- Cisco DNA Center

**Tools & Frameworks:**

- Python environment

**Usage**

- $ python device_report.py

Executing this script will create a report with all the devices managed by Cisco DNA Center.
This report will include this information for each device:
  - hostname
  - device type
  - software version
  - management IP address
  - serial number

The report will be saved as a CSV file.

- Sample CSV file:
C9800-CL,Cisco Catalyst 9800-CL Wireless Controller for Cloud,16.10.1e,10.93.130.31,9L2L5LASF7
NYC-9300,Cisco Catalyst 9300 Switch,16.9.2,10.93.130.21,FCW2145L0N
PDX-9300,Cisco Catalyst 9300 Switch,16.9.2,10.93.130.43,FCW2169L0J

The code could be easily changed to add or remove information about devices, based on the user needs.


**License**

This project is licensed to you under the terms of the [Cisco Sample Code License](./LICENSE).
