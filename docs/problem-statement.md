# Problem Statement for Watsonx Orchestrate hackathon 2025

**Problem statement: AI Agent for Cybersecurity Incident Response**

- Cybersecurity incidents are growing in frequency and sophistication, yet incident response in most organizations remains heavily manual, inconsistent, and slow. When users encounter potential threats such as phishing emails, malicious downloads, or data leaks they often lack the technical knowledge to properly report or contain the issue. Security teams, in turn, struggle with incomplete information, delayed escalation, and unstructured incident reports. These gaps lead to inconsistent triage, missed indicators of compromise, data exposure, and extended recovery times.

- Traditional chatbots or helpdesk tools fails to address this challenge effectively. They rely on static workflows and predefined scripts, lacking the ability to reason, adapt, and respond dynamically to unique incident contexts. What is needed is an intelligent, autonomous system that can engage users conversationally, reason about threat patterns, guide containment, and orchestrate the incident management process. All while ensuring human oversight and adherence to cybersecurity protocols.


**Solution statement**

- We built an AI agent "Agentic AI Cybersecurity Analyst" a self-learning AI agent assistant that acts as the first line of response during cybersecurity incidents. It is built upon the ReAct (Reason + Act) agentic framework, this AI agent is capable of logical reasoning, contextual understanding, and dynamic decision-making beyond typical automation.

- How agent responds to the incident ?
When a user encounters a suspected security issue, the agent initiates an interactive dialogue to collect and verify all relevant incident details, such as:

Time, location, and nature of the event (e.g., phishing email, suspicious login, ransomware alert)

Data possibly compromised (credentials, financial data, personal or corporate information)

Device and network context

Malicious URLs, attachments, or installation attempts

The agent then analyzes the severity and potential impact using embedded cybersecurity knowledge (attack types, breach indicators, response standards) and provides step-by-step guidance on next actions — such as isolating a device, disconnecting from the network, preserving evidence, or alerting support teams.

This agent leverages uploaded cybersecurity knowledge, including incident types, response guidelines, and threat patterns, to provide contextual, evidence-based recommendations. Its agentic reasoning enables it to simulate professional cybersecurity decision-making, balancing accuracy, safety, and adaptability to new or evolving threats.

Instead of directly raising system tickets, the agent guides users through the process of reporting incidents correctly by outlining what details to include, how to prioritize the issue, and how to submit it through internal tools like Jira or ServiceNow. This ensures users take the right actions while maintaining security and procedural compliance.


- Uniqueness and Creativity
What makes this project unique is its fusion of agentic reasoning, contextual intelligence, and guided response enablement. Unlike traditional chatbots, this agent demonstrates situational awareness and adaptive reasoning, mirroring how a cybersecurity analyst thinks and reacts. It transforms incident response from a reactive ticketing process into a guided, intelligent, and proactive defense mechanism.

By combining natural dialogue, analytical reasoning, evidence extraction, and guided user action — all with human-in-the-loop oversight — this AI agent represents a new class of trustworthy, interactive, and operationally useful cybersecurity assistants.


# Statement on Agentic AI:

- Agentic Artificial Intelligence refers to autonomous systems capable of pursuing complex, goal-directed tasks with minimal human intervention, distinguished by adaptability, decision-making autonomy, and operational resilience in dynamic environments.1 Unlike traditional AI models that operate reactively, agentic AI proactively plans, adapts, and executes workflows, aligning with theories of autonomy and adaptivity central to intelligent agent design.2 In the context
of cybersecurity, this capability is increasingly valuable due to the sophistication, speed, and unpredictability of emerging threats. The scarcity of skilled cybersecurity professionals, combined with the growing complexity of attack surfaces, creates a pressing need for autonomous cyber-defense agents capable of sensing, reasoning, acting, and learning without constant oversight.

- Use of Watsonx Orchestrate in solution implementation:
We have built an AI agent in the Watsonx Orchestrate platform with model "llama-3-2-90vision-instruct" and tuning parameters knowledge, behaviour, guidelines and toolset. We have added cybersecurity threat dataset for agent's knowledge base. We tuned the model using the instructions for responding to cyber incident,  incident details to be checked like time, malicious links/ activities observed, affected device, network for deep analysis of the problem. We also instruct how the response should be given to the user based on the incident severity and impact. We have added the guidelines for specific action request like    account restoration where user request for account restoration guidance, raising ticket for an incident in ticket management tool like Jira. This guidelines can be replaced by respective tool agents.