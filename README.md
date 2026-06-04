.# IBM_NIDS
A NIDS is a security tool that monitors network traffic for suspicious activity, policy violations, and cyber threats.
This repository contains my official submission for the IBM University Engagement Project. This project introduces a robust, machine learning-based Network Intrusion Detection System (NIDS) built natively within the enterprise IBM Cloud ecosystem. By analyzing raw network traffic data, the application successfully identifies and classifies various types of cyber-attacks to provide an early warning of malicious activities and secure communication networks.

Domain: Cybersecurity / Network Security

Project Title: [NIDS] Network Intrusion Detection System

Submission Platform: IBM University Engagement

Author: Prathmesh Kadam

🧠 Threat Detection Architecture (Powered by IBM watsonx.ai)

Instead of relying on traditional, rigid signature-based firewall rules, the system uses Machine Learning to understand baseline network behavior and flag statistical anomalies across multiple attack vectors:

Data Preprocessing Pipeline: Ingests and cleans the NSL-KDD dataset, intelligently encoding categorical features (like TCP/UDP protocols) and scaling numerical data for optimal model performance.

Multiclass Classification Engine: Synthesizes historical packet data to distinguish normal network activity from four primary cyber-attack categories: DoS (Denial of Service), Probe, R2L (Remote to Local), and U2R (User to Root).

Real-Time Inference Endpoint: Deployed as a live API on IBM Cloud to evaluate incoming JSON network packet features instantly, returning precise threat classifications and confidence scores.

Proactive Defense Framework: Acts as an autonomous Level 1 SOC (Security Operations Center) analyst, reducing alert fatigue by filtering out benign traffic and identifying potential zero-day exploits.

🛠️ Native Tech Stack Configuration

Core Environment: IBM Cloud Lite Infrastructure & PaaS

ML & Governance Foundation: IBM watsonx.ai (End-to-end model lifecycle management)

Programming & Algorithms: Python, Scikit-Learn, Pandas, NumPy

Data Payload Format: JSON (JavaScript Object Notation) for REST API inferences

📸 Production Workspace Verification

To verify operational workflows and model deployment, live infrastructure verification assets and required submission documents are stored directly within the repository execution directory:

Submission Files: app.json, problemstatement.pdf, and presentation.pptx are included in the root directory.

Deployment Proof: See the included screenshots/visual confirmations of the active IBM watsonx deployment dashboard, JSON testing inputs, and real-time prediction results
