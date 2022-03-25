# Towards an Event Perspective of CVE Descriptions for Vulnerability Analysis

## Data Description

The dataset was collected from the CVE vulnerability library and covers the period from 1999 to 2021. We screened out vulnerabilities with remediation links from all data and selected vulnerability reports for 16 commonly used CWE types. Finally, we eliminated some invalid or too little information bug reports, and finally got 4638 bug reports. Each entry includes 9 features in our dataset, which is published in comma-separated value (CSV) format. The 9 characteristics are the CVE-ID, description, cause (one or two may exist), location, version, attacker, operation, and consequence of the vulnerability. It should be noted that these features are extracted from vulnerability reports from an event perspective.
