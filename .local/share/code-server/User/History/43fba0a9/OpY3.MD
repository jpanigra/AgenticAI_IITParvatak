Agentic Design Record (ADR V1) 

1. Inputs 

Production support requests: Tickets, alerts, log queries, service restart requests. 

Knowledge base: Standard operating procedures, runbooks, FAQs. 

Monitoring data: System health metrics, error logs, performance dashboards. 

2. Tools 

Ticketing system integration (ServiceNow, Jira). 

Log analysis tools (Splunk, ELK). 

Automation scripts (Python, PowerShell). 

Agentic AI frameworks (LangChain, AutoGen, Semantic Kernel). 

3. Memory 

Short-term memory: Context of current request, recent actions taken. 

Long-term memory: Past resolutions, ticket history, patterns of recurring issues. 

Learning loop: Improve accuracy by storing successful fixes and feedback. 

4. Output 

Resolved tickets: Automated closure of routine requests. 

Reports: Logs, metrics, and resolution summaries. 

Escalations: Forward complex issues to human engineers with context. 

5. Autonomy Level 

Semi-autonomous agent: 

Handles routine tasks independently. 

Escalates complex or risky tasks to humans. 

Autonomy increases gradually as confidence grows. 

6. Decision Boundaries 

Safe zone: Restarting services, fetching logs, generating reports. 

Boundary zone: Applying patches, modifying configurations — requires human approval. 

Escalation zone: Critical outages, security incidents — always handed to humans. 

7. Success Metrics 

Reduction in manual requests: Target 40–60% fewer repetitive tickets. 

Resolution time: Faster closure of routine tasks. 

Accuracy: Minimal errors in automated actions. 

User satisfaction: Positive feedback from engineers and customers. 

🎯 How to Present 

You can say in class: "My ADR V1 defines the design of an Agentic AI system for production support. It takes inputs like tickets and logs, uses tools such as automation scripts and monitoring systems, and applies memory to learn from past fixes. The outputs are resolved tickets, reports, and escalations. The agent works at a semi-autonomous level, with clear decision boundaries to ensure safety. Success will be measured by reduced manual requests, faster resolution, and improved accuracy. This forms the foundation of my capstone project." 