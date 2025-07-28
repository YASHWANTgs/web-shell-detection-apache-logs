# web-shell-detection-apache-logs

The project is a mastery of web shell detection with forensic analysis of an Apache access log on a Linux web server. Attack simulation consisted of sending malicious HTTP GET  requests (e.g., GET /shell.php?cmd=whoami)  intended for remote command executions using a PHP web shell. thoroughly analyzing access.log patterns, the project finds evidence of exploitation as suspicious URL params, repeated access of suspicious files, as well as command executions attempts—key indicators mapping to MITRE ATT&CK T1505.003 (Web Shell). Analysis includes a step-by-step of screenshots of simulation of an attack, Suspicious requests (<?php system($_GET['cmd']); ?>`), investigation of logs, as well as a handwritten detection process. This project exhibits key Blue Team skills of a threat huntig, an incident response specialist, as well as a log expert and is thus highly applicable to entry-level SOC analysts.


