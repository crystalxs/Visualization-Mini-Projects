# Network Traffic Anomly and Compromise Detection

The dataset comes from Dr. Chiara Sabatti at Stanford University. It is the summary of some real network traffic data from the past. The dataset has ~21K rows and covers 10 local workstation IPs over a three month period. Half of these local IPs were compromised at some point during this period and became members of various botnets.

This visualization aim to discover when a compromise has occurred by a change in the pattern of communication.

Dataset structure:

- `date`: `yyyy-mm-dd` (from 2006-07-01 through 2006-09-30)
- `l_ipn`: local IP (coded as an integer from 0-9)
- `r_asn`: remote ASN (an integer which identifies the remote ISP)
- `f`: flows (count of connnections for that day)

Files:

* jupyter notebook: data processing with `python`
* html: data visualization code & visualization
