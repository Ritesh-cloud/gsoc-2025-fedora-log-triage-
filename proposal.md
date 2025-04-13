# GSoC 2025 Proposal – Fedora Project

## Personal Information

- **Name**: Ritesh Murmu
- **Email**: [your_email@example.com]
- **GitHub/Portfolio**: [your_github_url]
- **University**: Birla Institute of Technology, Mesra
- **Program**: M.Sc. in Quantitative Economics and Data Science

---

## Project Title: AI-Powered Log Triage and Security Alert Aggregator for Fedora

### Abstract

The goal of this project is to develop an AI-powered tool to intelligently classify and aggregate security logs for Fedora systems. This tool will use machine learning techniques to classify log entries (normal, warning, critical) and group related alerts together to reduce noise, improve incident response, and enhance the security visibility of Fedora’s infrastructure.

---

## Benefits to the Community

- **Improved Efficiency**: Automating log triage will reduce manual efforts and allow administrators to focus on real incidents.
- **Enhanced Security**: Faster identification of critical security alerts using machine learning.
- **Scalability**: The tool can be extended to handle logs from various sources and provide a flexible solution.
- **Open Contribution**: This will help streamline contributions from other developers in the Fedora ecosystem.

---

## Deliverables

1. **Phase 1:**
   - Set up the log parsing pipeline.
   - Develop a machine learning model for log classification.
2. **Phase 2:**
   - Implement clustering for alert grouping.
   - Build a dashboard/CLI for visualizing categorized alerts.
3. **Final Phase:**
   - Real-time log ingestion.
   - Final documentation and deployment-ready release.

---

## Timeline

| Period | Goals |
|--------|-------|
| Community Bonding (May 20 – June 16) | Familiarize with Fedora Infra, finalize tech stack (e.g., Loguru, NLTK, etc.) |
| Week 1–2 | Set up dev environment, create log parsing pipeline |
| Week 3–4 | Develop and test the ML model for log classification |
| Week 5–6 | Implement alert grouping with clustering algorithms |
| Week 7–8 | Mid-term evaluation, finalize CLI/UI for monitoring alerts |
| Week 9–10 | Integrate with Fedora’s log system, start testing in real environments |
| Week 11–12 | Final testing and prepare for deployment |
| Week 13 | Submit final deliverables and documentation |

---

## Technical Approach

- **Log Preprocessing**: I’ll use NLP techniques to filter and tokenize log entries for easier classification.
- **Machine Learning**: Using supervised classification (SVM, Random Forest) and unsupervised clustering (K-Means/DBSCAN) to categorize and group logs.
- **Visualization**: A simple CLI or a web-based dashboard using Flask to display categorized alerts.

---

## Why Me?

- **Skills**: I have a solid background in Python, machine learning, and data analysis. I have also worked on similar projects involving text classification and real-time data processing.
- **Open Source Experience**: I have contributed to several open-source projects and I’m familiar with using Git and GitHub for collaboration.
- **Interest in Fedora**: I’ve been using Fedora for a while and am eager to contribute to its community through this project.

---

## Future Work

Post-GSoC, I aim to continue developing the tool by:
- Adding feedback mechanisms to improve machine learning models.
- Extending the system to other log sources across Fedora infrastructure.
- Improving real-time processing and scalability.

---

## Backup Plan

If the real-time ingestion integration is delayed, I’ll focus on improving the log classification and grouping features using sample logs, with real-time functionality being a future addition.

---

## Contact

- **Name**: Ritesh Murmu
- **Email**: riteshmurmu11@gmail.comm
- **GitHub**: https://github.com/Ritesh-cloud?tab=overview&from=2025-04-01&to=2025-04-13
