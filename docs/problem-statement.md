# 🧠 AI Agent for Cybersecurity Incident Response  
### Watsonx Orchestrate Hackathon 2025  

---

## Overview  

Cybersecurity incidents are increasing in both **volume** and **sophistication**, yet incident response processes remain **manual, inconsistent, and slow** across most organizations.  
Users often fail to report incidents accurately, and security teams struggle with incomplete information and delayed escalation, leading to **missed threats and prolonged recovery times**.  

To address this gap, we present **Agentic AI Cybersecurity Analyst** — an intelligent, reasoning-enabled AI agent built using **IBM Watsonx Orchestrate**.  
This agent autonomously collects incident details, reasons about severity and impact, guides users on containment steps, and orchestrates reporting workflows while ensuring compliance and human oversight.  

---

## Problem Statement  

- Incident response in most organizations remains heavily **manual and error-prone**.  
- Users lack awareness of **how to identify and report** potential threats (e.g., phishing, ransomware, data breaches).  
- Security teams face **delays, incomplete data, and unstructured reports**.  
- Traditional chatbots and ticketing tools **lack adaptive reasoning** and **contextual intelligence**.  

A new class of AI systems is needed — one that combines **reasoning, adaptability, and orchestration** to streamline cybersecurity response processes.  

---

## Solution: Agentic AI Cybersecurity Analyst  

The **Agentic AI Cybersecurity Analyst** is a **ReAct (Reason + Act)**-based autonomous agent that serves as the first line of defense during cybersecurity incidents.  
It can **converse intelligently**, **reason contextually**, and **guide users** through the process of identifying, containing, and reporting incidents.

### Key Capabilities  

1. **Interactive Data Collection**  
   - Gathers structured details (time, source, device, network, URLs, suspected data exposure).  
2. **Severity & Impact Analysis**  
   - Uses embedded threat intelligence and response frameworks (NIST, MITRE ATT&CK).  
3. **Guided Incident Response**  
   - Provides clear containment and recovery steps.  
4. **Dynamic Decision-Making**  
   - Adjusts actions based on threat type and severity level.  
5. **Integration with Enterprise Tools**  
   - Connects to Jira, ServiceNow, or SOC dashboards for reporting and escalation.  

---

## Key Features  

| Feature | Description |
|----------|-------------|
| **Agentic Reasoning** | Uses ReAct framework for multi-step reasoning and autonomous decision-making. |
| **Conversational Intelligence** | Natural language dialogues to gather and verify incident details. |
| **Severity Classification** | Evaluates potential impact based on attack type, scope, and exposure. |
| **Knowledge Integration** | Cyber threat intelligence and response playbooks embedded in agent. |
| **Guided Ticket Creation** | Automatically drafts Jira/ServiceNow tickets with pre-filled structured data. |
| **Human Oversight** | Escalates high-severity incidents to security teams for validation. |

---

## Understanding Agentic AI  

**Agentic AI** refers to autonomous systems capable of **goal-directed, context-aware reasoning and action**.  
Unlike static automation, it can **plan, adapt, and execute tasks** dynamically.  

In cybersecurity, Agentic AI enables:
- **Proactive detection** and **autonomous reasoning** for incident analysis  
- **Adaptive response orchestration** under uncertain conditions  
- **Operational resilience** in evolving threat landscapes  

---

### References

1. [IBM Watsonx Orchestrate Documentation](https://www.ibm.com/docs/en/watsonx/watson-orchestrate/base?topic=getting-started-watsonx-orchestrate)

3. Bibliography: 
- [Study paper-1](https://f1000research.com/articles/14-843/pdf)
- [Study paper-2](https://f1000research.com/articles/14-843/pdf)

4. See the [Architecture Diagram](/architecture.md) for details.

5. [Demo link](https://www.youtube.com/watch?v=HAF2NYPqK7E)