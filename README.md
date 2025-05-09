# -siem-integration-suit
SIEM Tool Integration with Security Data Sources

This project demonstrates how to integrate a custom SIEM (Security Information and Event Management) setup with various threat intelligence and monitoring tools to enhance real-time detection, log analysis, and incident response capabilities.

🔍 Project Description

This repository contains a collection of scripts, configurations, and documentation designed to:
	•	Integrate external threat intelligence sources into a SIEM pipeline
	•	Automate log enrichment using APIs (e.g., Shodan, AbuseIPDB)
	•	Analyze and correlate suspicious behavior across network events
	•	Improve alert fidelity and reduce false positives
	•	Provide a foundation for building a lightweight SOC monitoring tool

🛠️ Technologies Used
	•	SIEM: Elasticsearch, Kibana, or Splunk (configurable)
	•	Threat Intelligence APIs: AbuseIPDB, Shodan
	•	Scripting: Python
	•	Log Sources: Syslog, JSON-formatted event logs

🚀 Getting Started
	1.	Clone the repository
	2.	Configure API keys in .env
	3.	Run the script: python enrich_logs.py
	4.	View enriched logs in your SIEM platform

📄 License

This project is open-source and available under the MIT License.
