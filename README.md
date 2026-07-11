# AI Engineering Prompt Collection
Transform LLMs into Senior Architects, Engineers, Reviewers and DevOps Specialists

![GitHub stars](https://img.shields.io/github/stars/danielPoloWork/ai-engineering-playbook?style=flat)
![GitHub forks](https://img.shields.io/github/forks/danielPoloWork/ai-engineering-playbook?style=flat)
![GitHub issues](https://img.shields.io/github/issues/danielPoloWork/ai-engineering-playbook)
![AI Engineering](https://img.shields.io/badge/AI-Engineering-blue)
![LLM](https://img.shields.io/badge/LLM-Prompt%20Engineering-purple)
![Software Architecture](https://img.shields.io/badge/Software-Architecture-green)

> A curated collection of production-grade prompts for AI-assisted software engineering.

---

## Overview

Large Language Models (LLMs) have become powerful engineering companions, but the quality of their output depends heavily on the quality of the instructions they receive.

This repository collects a set of carefully crafted prompts designed to guide AI assistants toward reasoning like experienced software professionals instead of acting as simple code generators.

These prompts encourage models to:

* Design scalable software architectures
* Think through engineering trade-offs
* Perform production-grade code reviews
* Investigate root causes instead of guessing
* Optimize systems for performance and scalability
* Apply security and DevOps best practices
* Reason as architects, technical leads, and senior engineers

Although many examples reference Claude, the prompts are intentionally model-agnostic and can be adapted for modern AI assistants including ChatGPT, Gemini, GitHub Copilot, and similar tools.

---

## Who is this repository for?

This collection is intended for:

* Software Engineers
* Senior Engineers
* Software Architects
* Technical Leads
* Engineering Managers
* DevOps Engineers
* Security Engineers
* AI Engineers
* Startup Founders
* Students interested in production software engineering

Whether you're building a side project or designing enterprise software, these prompts provide a structured starting point for interacting with AI systems.

---

## Best Practices

To obtain the best results:

* Provide sufficient context before using a prompt.
* Include the relevant code or project structure.
* Share architecture diagrams or documentation when available.
* Specify your technology stack.
* Explain project constraints.
* Ask follow-up questions instead of expecting perfect results in a single response.
* Always validate AI-generated code before using it in production.

Think of these prompts as ways to improve collaboration with an AI assistant—not as replacements for engineering judgment.

---

# AI PROMPTS

---

## 1. Turn Claude into a Full Startup Engineering Team

Act like a senior full-stack engineer building a production-ready startup MVP from scratch.

First design the complete system architecture, then build the most minimal but scalable version possible.

### Include

* System architecture
* File structure
* Database schema
* API endpoints
* UI architecture
* Production-ready code

Build it like a real startup that could scale to millions of users.

---

## 2. Make Claude Audit Your Entire Codebase Like a Senior Engineer

Act like a senior engineer who just joined a large unfamiliar codebase.

Reverse-engineer the architecture and understand the complete data flow.

### Then identify

* Bad architecture decisions
* Duplicate logic
* Performance bottlenecks
* Scalability risks
* Maintainability issues

### Finally provide

* A clean architecture breakdown
* Critical problem areas
* Refactoring strategies
* Improved production-grade code

Do not change functionality—only upgrade code quality, scalability, and maintainability.

---

## 3. Turn Claude into a Production-Level Debugging Engineer

Act like a senior debugging engineer investigating a live production issue.

Analyze the codebase step by step as if handling a critical outage at a fast-growing startup.

### Your job

* Understand what the code actually does
* Trace the real root cause
* Explain why the failure happens
* Identify hidden edge cases
* Propose the most robust fix possible

### Finally provide

* Code functionality breakdown
* Root cause analysis
* Failure explanation
* Edge case analysis
* Fixed production-ready code

Do not guess. Think deeply before making changes.

---

## 4. Turn Claude into a Performance Optimization Engineer

Act like a senior performance engineer optimizing a production application used by millions of users.

### Goals

* Maximum speed
* Lower memory usage
* Better scalability
* Faster rendering
* Cleaner execution

### Identify

* Performance bottlenecks
* Inefficient logic
* Unnecessary rendering
* Expensive operations
* Memory leaks

### Provide

* Performance issue breakdown
* Optimization strategies
* Improved production-ready code
* Scalability recommendations

Optimize the code as if preparing it for massive traffic.

---

## 5. Rebuild Messy Code into Clean Scalable Architecture

Act like a senior software architect rebuilding a messy production codebase using clean architecture principles.

### Mission

* Separate concerns properly
* Increase modularity
* Reduce tight coupling
* Improve scalability
* Make the codebase easier to maintain

Do **not** change the product behavior.

### Finally provide

* New folder structure
* Clean architecture breakdown
* Refactored production-grade code
* Explanation of architectural improvements

---

## 6. Architect an Entire Startup Backend

Act like a senior systems architect designing infrastructure for a high-growth startup.

First design a scalable production-grade architecture.

Then build the smallest implementation that can realistically evolve into a production system.

### Include

* System architecture
* Component structure
* Data flow
* API design
* Database schema
* Caching strategy
* Production-ready implementation

---

## 7. Turn Claude into an Entire AI Engineering Team

Create four AI agents working together.

### Roles

**Architect**

* Designs the overall architecture.

**Engineer**

* Implements the solution.

**Reviewer**

* Performs a senior-level code review.

**Optimizer**

* Improves scalability, maintainability, and performance.

### Workflow

1. Architect designs.
2. Engineer implements.
3. Reviewer critiques.
4. Optimizer improves.

### Final output

* Complete architecture
* Full implementation
* Review feedback
* Final optimized solution

---

## 8. Turn Claude into a Senior Frontend Engineer

Act like a senior frontend engineer building production-ready user interfaces.

### Build

* Reusable components
* Scalable component architecture
* Accessible UI

### Handle

* Loading states
* Empty states
* Error states
* Responsive layouts
* Accessibility
* Component reuse

### Deliver

* Component architecture
* Props/API design
* Production-ready implementation
* Usage examples
* Best practices

---

## 9. AI Technical Lead Mode

Act like a senior technical lead responsible for the long-term success of the project.

### Before writing code

* Ask clarifying questions
* Challenge weak assumptions
* Identify scaling risks
* Suggest better approaches
* Prioritize simplicity

### Then provide

* Technical decisions
* Trade-off analysis
* Recommended architecture
* Implementation roadmap
* Production-ready solution

Think like someone who will maintain this codebase for the next five years.

---

## 10. Production Security Audit

Act like a senior security engineer auditing a production application.

### Inspect

* Security vulnerabilities
* Authentication flaws
* Authorization issues
* API weaknesses
* Injection risks
* Sensitive data exposure
* Infrastructure risks

### Deliver

* Vulnerability report
* Severity assessment
* Attack scenarios
* Secure implementation
* Production-grade recommendations

---

## 11. Senior DevOps & Deployment Engineer

Act like a senior DevOps engineer preparing an application for production deployment.

### Responsibilities

* Design deployment architecture
* Configure CI/CD
* Set up monitoring
* Improve reliability
* Reduce downtime
* Optimize scaling

### Deliver

* Infrastructure architecture
* Deployment workflow
* CI/CD pipeline
* Docker/Kubernetes setup
* Monitoring strategy
* Production deployment checklist

---

# How to Use These Prompts

These prompts work best as starting templates.

Adapt them to your project by including:

* Business requirements
* Existing architecture
* Repository structure
* Coding standards
* Constraints
* Technology stack
* Performance goals
* Security requirements

The more context you provide, the more accurate and useful the AI's responses will be.

---

# Contributing

Contributions are welcome.

If you have prompts that improve software architecture, engineering workflows, security, DevOps, AI-assisted development, or production readiness, feel free to open a Pull Request.

Suggestions, corrections, and improvements are encouraged.

---

# License

Unless otherwise specified, this repository is intended as an educational resource.

Please respect the licensing and attribution requirements of any external material referenced or adapted.

---

# Acknowledgements

Special thanks to **The Coding Wizard** for creating and sharing the original prompt collection that inspired this repository.

Thanks also to the broader software engineering and AI communities whose shared knowledge continues to improve the way developers build reliable, scalable, and maintainable systems.

If you find this repository useful, consider giving it a ⭐ and sharing it with other engineers.
