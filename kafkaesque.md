The k8e guide to creating agentic systems is largely influenced on event driven architecture, with my specific experience being with apache kafka

Key principles:
- small, focused tasks
- event-driven -> state-driven
- fresh context, clean working environment for each task
- tasks can be started manually, on a schedule, or as a response to some event

parallelization:
- use a centralized work tracking system (e.g., github issues, jira) to assign work to prevent duplicating effort
- log status updates in the form of pushed commits, opened PRs, comments, etc

what this creates is a system for agentic-driven development
