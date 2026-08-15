# Cyber Mini-Defense Toolkit

**Mark A. McKinney**  
**Final Project – AI & Cybersecurity**

## Project Overview

The Cyber Mini-Defense Toolkit demonstrates how Python, cybersecurity analysis, data visualization, and automation can support practical security operations. I developed this project to analyze login activity, identify suspicious behavior, evaluate authentication risks, and demonstrate several defensive cybersecurity techniques within a single environment.

The project connects technical analysis with cybersecurity decision-making. Rather than relying on one indicator to identify suspicious activity, the toolkit evaluates multiple factors and emphasizes the importance of context and human judgment.

## Project Objectives

The project focuses on the following objectives:

- Analyze cybersecurity login data using Python
- Examine failed login activity and authentication patterns
- Identify potentially suspicious login behavior
- Develop a rule-based suspicious login detector
- Evaluate password strength
- Identify common phishing indicators
- Visualize cybersecurity data and findings
- Develop practical security recommendations
- Demonstrate responsible use of AI and automation

## Key Findings

The login dataset contained **600 records**. My analysis produced the following findings:

- **367 records** were classified as suspicious
- **233 records** were classified as non-suspicious
- The dataset contained **3,845 failed login attempts**
- Suspicious records averaged approximately **8.56 failed login attempts**
- Non-suspicious records averaged approximately **3.02 failed login attempts**
- Suspicious records averaged approximately **16.65 total login attempts**
- Non-suspicious records averaged approximately **7.73 total login attempts**
- The rule-based detector correctly classified **555 of 600 records**
- The detector achieved an overall accuracy of **92.5%**

These findings demonstrate the value of examining multiple security indicators instead of treating a single event as proof of malicious activity.

## Toolkit Components

The Cyber Mini-Defense Toolkit includes:

1. Cybersecurity login data analysis
2. Failed login analysis
3. Suspicious activity analysis
4. Rule-based suspicious login detector
5. Password strength checker
6. Phishing detector
7. Cybersecurity data visualizations
8. Security recommendations
9. Responsible AI and automation considerations

## Technologies Used

- Python
- Google Colab
- Jupyter Notebook
- Pandas
- Matplotlib
- GitHub

## Repository Structure

- **data/raw/** – Original cybersecurity dataset
- **notebooks/** – Final Cyber Mini-Defense Toolkit Jupyter Notebook
- **reports/figures/** – Project figures and visualizations
- **reflection/** – Project reflection and lessons learned
- **README.md** – Project overview and documentation

## Responsible Use of AI and Automation

AI and automation can help cybersecurity professionals process security data, identify patterns, and prioritize potential threats. However, automated systems should support professional judgment rather than replace it.

Security professionals should validate significant findings, review potential false positives, protect sensitive information, document important decisions, and evaluate automated detection methods as threats and organizational environments change.

## Conclusion

This project demonstrates how Python and automated analysis can support practical cybersecurity activities. The Cyber Mini-Defense Toolkit combines data analysis, threat detection, authentication security, phishing awareness, visualization, and responsible automation within one project.

The project reinforced an important cybersecurity principle: effective security analysis requires technical indicators, context, and human judgment. Automation can improve the speed and consistency of analysis, while cybersecurity professionals remain responsible for evaluating findings and determining the appropriate response.
