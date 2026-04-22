---
layout: default
title: Proposal
---

# Proposal

AI vs. Human Penetration Testing Effectiveness

Brendan Ketelsen 

Information Technology

---

Background

This project aims to systematically evaluate the effectiveness of AI-based penetration
testing tools relative to experienced human penetration testers across various network
environments. I will compare performance metrics (vulnerabilities discovered, time, false
positives, cost, etc.) for AI versus human experts to determine the strengths and
weaknesses of each approach.

Cybersecurity breaches continue to grow in frequency and cost. At the same time, there
is a global shortage of qualified security professionals. One study reported a 3.4 million
worker gap in cybersecurity talent (Lake & Suarez, 2022). Recent advances (large
language models, machine learning, etc.) have enabled AI that can autonomously scan
networks and suggest exploits. AI excels at repetitive, large-scale tasks such as
vulnerability scanning and can operate 24/7, unlike humans. Therefore, organizations
using security AI typically report faster breach detection and lower costs.

However, experts caution that AI lacks human intuition and reasoning. AI can identify
known patterns, but struggles with complex business logic, novel exploits, or multi-step
attack chains (Thomas, 2025). A recent industry study observed that an AI testing tool
called XBOW submitted 1,060 potential issues but only around 10% were confirmed
valid, creating many false positives and requiring human review (Thomas, 2025).
Building on this context, my research will rigorously compare AI and human penetration
testing under realistic conditions to inform the best practices for blending both.

---

Methodology

Testbed Setup: Build one isolated lab environment that includes a Windows Server
virtual machine, an Ubuntu Linux Server virtual machine, and a deliberately vulnerable
web application. Seed a limited set of known vulnerabilities into the environment so
results can be checked.

AI Tools: Configure one AI tool to perform reconnaissance, vulnerability identification,
and exploit suggestions against the approved lab network. The tool will receive only the
authorized scope and credentials.

Human Testers: Recruit four experienced penetration testers or advanced cybersecurity
students with prior offensive-security experience. Each participant will test the same
environment for a fixed time using standard tools such as Nmap, Burp Suite, and
Metasploit. Participants will be compensated for their time.

Data Collection & Metrics: Record the number of unique vulnerabilities found, severity,
time to first valid finding, false positives, and total time. Findings will be checked against
the seeded vulnerability list and scored for validity. The comparison will be limited to one
environment and one testing window so the results are directly comparable.

Ethical and Security Controls: All testing will occur on isolated, on campus networks or
testbeds with no outside impact. Human participants will sign consent forms, and all
actions will comply with legal and ethical guidelines. No actual real-world systems will
be targeted.

---

Anticipated Outcomes

I expect the study to show that AI tools greatly accelerate vulnerability detection and
coverage, consistently finding many low-level flaws quickly. However, I also anticipate
identifying clear gaps where human expertise remains crucial, such as more creative
exploits, social engineering and validating the AI findings. Metrics will likely be similar to
prior findings: AI may achieve higher rates of identified issues per hour but at the
expense of higher false-positive rates. The expected outcome is a comprehensive
evaluation that actually measures these trade offs. The project will produce
recommendations for hybrid testing (i.e. use AI for broad scanning and let humans focus
on contextual analysis). Ultimately, I aim to develop guidelines on integrating AI into
penetration testing workflows and to propose new metrics for evaluating efficiency
across human and AI agents. The results will advance understanding of AI’s role in
cybersecurity and suggest future research directions in automated offensive security.

---

References

Lake, S., & Suarez, J. (2022, October 20). The cybersecurity industry is short 3.4 million workers-that’s good news for cyber wages. Fortune. https://fortune.com/education/articles/the-cybersecurity-industry-is-short-3-4-million-workers-thats-good-news-for-cyber-wages/

Thomas, M. (2025, October 19). Why AI won’t be replacing human penetration testers soon. PGI. https://www.pgitl.com/insights/ai-replacing-human-penetration-testing

---

Timeline

Dates and Tasks:

January 1, 2027- Feburary 14, 2027:
Finalize the project design, build the lab environment, and seed the test vulnerabilities.

February 14, 2027 – March 14, 2027
Configure the AI tools, finalize scoring rules, and recruit human participants.

March 14, 2027 – April 14, 2027 
Run the AI and human penetration tests on the same lab environment and collect the results.

April 14, 2027 – May 1, 2027 
Analyze the findings, compare performance metrics, and draft the final report and poster.

---

Budget

Item, Units and Cost, Total

Participant pay: $25/person for 4 people, $100

Digital resources: One Linux Ubuntu VM, one Windows Server VM, and about 20 hours of AWS EC2 computing resources for automated scanning, $350

Hardware: Campus computer lab room rental, 1 1TB external SSD, and 1 8-port switch, $300

Total: $750

---

Dissemination

Findings will be submitted as a student poster and report to the Annual Computer Security Applications Conference (ACSAC). 
