# Final Project Reflection

## Student Information

**Name:** Mark A. McKinney  
**Date:** August 15, 2026

---

# Project Title

Cyber Mini-Defense Toolkit

---

# 1. What I Built

For this project, I developed a Cyber Mini-Defense Toolkit that applies Python programming to practical cybersecurity activities. The project includes a log analyzer, a rule-based suspicious login detector, a password strength checker, a phishing detector, and data visualizations. These tools allowed me to examine cybersecurity data, identify potential threats, and demonstrate how relatively simple automation can support cybersecurity analysis and decision-making.

# 2. Dataset Used

I used the cybersecurity login dataset provided for the project. The dataset contains 600 login records and includes information that can be used to examine authentication behavior, including login attempts, failed login attempts, IP address activity, login times, and suspicious activity classifications. I used Python and pandas to load, examine, and analyze the dataset.

# 3. Suspicious Activity Found

My analysis identified several patterns associated with suspicious activity. Of the 600 login records, 367 were classified as suspicious and 233 as non-suspicious. The dataset contained 3,845 failed login attempts. Suspicious records averaged approximately 8.56 failed login attempts and 16.65 total login attempts, compared with approximately 3.02 failed attempts and 7.73 total attempts for non-suspicious records.

These findings demonstrated that repeated failed logins and unusually high login activity can provide useful indicators of potential security problems. However, I also learned that one indicator should not automatically determine whether activity is malicious. Security analysts must consider the broader context before making that determination.

# 4. What I Learned

One of the most important concepts I learned was how cybersecurity professionals can use data analysis to identify patterns that may indicate security threats. I strengthened my understanding of log analysis, authentication security, anomaly detection, phishing awareness, password security, and rule-based detection.

I also learned the importance of combining technical analysis with professional judgment. Automated tools can identify patterns quickly, but analysts still need to interpret the results and determine whether the activity represents an actual security threat.

# 5. Challenges Faced

One challenge involved developing rules that could identify suspicious behavior without assuming that every unusual event represented malicious activity. For example, a failed login can occur because a legitimate user entered an incorrect password. I therefore had to examine failed logins together with other indicators rather than relying on one factor.

Another challenge involved working through the code, validating the results, and making sure the visualizations accurately represented the underlying data. Working through these challenges strengthened my understanding of both Python and cybersecurity analysis.

# 6. AI in Cybersecurity

AI can help cybersecurity professionals analyze large amounts of security data, recognize patterns, prioritize alerts, and identify potentially suspicious activity more quickly. AI can also support security teams by automating repetitive analytical tasks and helping analysts focus their attention on higher-risk events.

However, AI systems can make mistakes. False positives may identify legitimate behavior as malicious, while false negatives may allow actual threats to go undetected. Organizations should therefore use AI as a decision-support capability rather than as a replacement for cybersecurity professionals. Human oversight remains important when automated findings could lead to significant security decisions.

# 7. Future Improvements

If I had additional time to expand the project, I would improve the suspicious activity detector by incorporating additional indicators and more advanced anomaly-detection techniques. I would also develop an interactive dashboard that would allow analysts to monitor login activity and investigate suspicious events more efficiently.

Additional improvements could include stronger phishing detection, expanded password analysis, automated alert prioritization, and machine-learning techniques that could compare rule-based detection with predictive models.

# 8. Final Reflection

The most important lesson I learned from this program is that effective cybersecurity requires more than technical tools. Technology provides valuable capabilities, but cybersecurity professionals must understand the data, evaluate context, communicate findings, and apply professional judgment when making decisions.

This project helped me connect Python programming, data analysis, cybersecurity, automation, and responsible AI within one practical environment. It also reinforced the importance of using technology to support human decision-making rather than replacing it. I came away from the project with a stronger understanding of how cybersecurity analysis can combine technical capabilities with responsible and informed decision-making.

# Responsible AI Statement

**Successful AI = Responsible AI**

AI systems should be secure, ethical, transparent, and human-centered.
