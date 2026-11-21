# Reflection from Part A: Concept Analysis

## i. What is Agentic Software Engineering?
Agentic Software Engineering (ASE) is the discipline of designing, building, testing, and maintaining software in which AI agents perceive their environment, reason about goals, and act with some autonomy, often by calling tools, APIs, or other agents. It also covers using AI agents as collaborators across the software lifecycle. ASE applies established engineering practices such as requirements, design, testing, and version control to systems whose behavior is probabilistic rather than fully scripted.

## ii. How does an AI agent differ from a traditional software application?
A traditional application executes deterministic, pre-programmed logic: the same input yields the same output, and every path was written by a developer. An AI agent, as defined by Russell and Norvig, perceives its environment through sensors and acts through actuators to achieve its goals. It chooses its own steps, adapts to context, and may produce different outputs for the same input. This makes agents more flexible, but also harder to specify, test, and predict.

## iii. Why are Agile methods appropriate for developing agentic systems?
Agentic systems have evolving requirements and uncertain behavior, so they need frequent feedback. Agile methods such as Scrum use short sprints, incremental delivery, and regular reviews and retrospectives. These let teams test agent behavior early, adjust prompts, tools, and guardrails, and respond quickly to surprises. Scrum's pillars of transparency, inspection, and adaptation match the need to continually monitor and refine agents. Version control with Git supports this by tracking changes, enabling collaboration, and allowing safe rollback.

## iv. What risks should developers consider when deploying autonomous AI agents?
Developers should consider incorrect or hallucinated outputs; unintended or irreversible actions; security threats such as prompt injection, excessive permissions, and data leakage; privacy violations from handling personal data; bias and unfair outcomes; lack of transparency and accountability; and over-reliance on automation. The NIST AI Risk Management Framework treats these as risks to be governed, mapped, measured, and managed throughout the system's lifecycle.

## v. Why is human oversight important in AI-enabled applications?
Humans provide judgment, context, and accountability that agents lack. Oversight lets people review high-impact decisions, approve sensitive actions, catch errors or bias, and stop or override the system when it misbehaves. It keeps responsibility with people rather than machines, supports user trust and legal compliance, and aligns with the Govern function of the NIST framework.
