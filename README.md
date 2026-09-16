# Stephan Loesevitz

**Linux Systems Engineer | Infrastructure Automation | Reliability Engineering**

I build tools and systems that make Linux infrastructure safer to operate.

My work focuses on production hosting environments, infrastructure automation, migrations, observability, security, and operational tooling. I enjoy turning repetitive or failure-prone administrator workflows into software that is easier to understand, review, recover, and trust.

Much of what I build comes directly from problems encountered while operating real Linux systems.

## What I work with

**Linux & Infrastructure**

* Red Hat Enterprise Linux
* AlmaLinux
* Debian
* Ubuntu
* systemd
* Docker
* Kubernetes
* Virtualization and VPS infrastructure

**Web & Hosting**

* Apache
* Nginx
* cPanel
* PHP-FPM
* DNS
* SSL/TLS
* Mail infrastructure

**Databases**

* MySQL
* MariaDB
* PostgreSQL
* Database migrations
* Performance troubleshooting
* Backup and recovery

**Automation & Development**

* Go
* Rust
* Python
* Bash
* Ansible
* Git
* Infrastructure as Code

**Operations & Reliability**

* Server migrations
* Incident troubleshooting
* Capacity planning
* Security hardening
* Fail2ban automation
* Monitoring and diagnostics
* Backup and recovery workflows
* Production safety guardrails

---

## Featured Projects

| Project                                                             | What it does                                                                                                                                                              |
| ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [**StePanel**](https://github.com/itchyitchy123/StePanel)           | Operator-focused Linux hosting control plane written in Go for server management, cPanel migrations, backups, database operations, auditing, and infrastructure workflows |
| [**FPM Lens**](https://github.com/itchyitchy123/FPM_Lens)           | Evidence-based PHP-FPM capacity planner that analyzes real memory usage and generates explainable, memory-bounded configuration recommendations                           |
| [**WayExpand**](https://github.com/itchyitchy123/wayexpand)         | Privacy-first Wayland text expander for Linux written in Rust, with GUI/CLI management, snippet automation, Espanso import, and multiple native Wayland backends          |
| [**MailSwiftSync**](https://github.com/itchyitchy123/MailSwiftSync) | Mail migration control plane designed to make large mailbox migrations observable, reviewable, recoverable, and verifiable                                                |

---

## Currently Building

### [StePanel](https://github.com/itchyitchy123/StePanel)

A safety-first control plane for Linux hosting infrastructure.

StePanel is designed around the idea that infrastructure tooling should make dangerous operations easier to understand and harder to perform accidentally.

Current areas of development include:

* Durable background job execution
* cPanel and hosting migrations
* Database administration
* Backup and restore workflows
* Server resource controls
* Operational auditing
* Failure recovery
* Reproducible releases
* Infrastructure health and diagnostics

The project is written primarily in **Go** and focuses on building reliable operator workflows rather than simply wrapping shell commands in a web interface.

---

### [FPM Lens](https://github.com/itchyitchy123/FPM_Lens)

A review-first PHP-FPM capacity planning and analysis tool.

Instead of guessing at `pm.max_children` or relying on generic tuning formulas, FPM Lens measures real workload behavior and memory consumption before generating recommendations.

The goal is to make PHP-FPM tuning:

* Evidence-based
* Explainable
* Repeatable
* Memory-aware
* Safe for production environments

Recommendations are presented for human review rather than automatically modifying production configuration.

---

### [WayExpand](https://github.com/itchyitchy123/wayexpand)

A privacy-first text expansion platform built specifically for modern Linux Wayland desktops.

WayExpand is written in **Rust** and explores a Wayland-native approach to reliable text expansion rather than relying entirely on legacy X11 behavior.

Features and development areas include:

* Native Wayland integration
* GUI and CLI snippet management
* Fast text expansion
* Espanso configuration import
* wlroots virtual keyboard support
* libei/EIS integration
* Wayland input-method support
* Local-first operation
* Privacy-conscious logging
* Backend diagnostics and environment detection

The long-term goal is simple:

> Make text expansion on Wayland boringly reliable.

---

### [MailSwiftSync](https://github.com/itchyitchy123/MailSwiftSync)

A migration control plane for large mailbox moves.

Mail migrations are easy to start and surprisingly difficult to prove correct. MailSwiftSync focuses on the operational side of migration: visibility, verification, retries, failure recovery, and auditability.

The project is being designed around:

* Pre-migration validation
* Controlled synchronization
* Progress visibility
* Failure tracking
* Retry-safe operations
* Migration verification
* Audit history
* Recovery workflows

The objective is not simply to move mail.

It is to make migrations **safe, reviewable, recoverable, and provable**.

---

## Engineering Approach

I tend to build infrastructure software around a few principles:

**Prefer evidence over assumptions.**
Measure the system before changing it.

**Make dangerous operations reviewable.**
Production automation should help operators understand what will happen before it happens.

**Design for failure.**
Retries, rollback paths, checkpoints, logs, and recoverability matter as much as the happy path.

**Automate repetition, not judgment.**
Automation should remove repetitive work while preserving human control over high-impact decisions.

**Operational tools should explain themselves.**
A recommendation is more useful when an operator can understand why it was made.

---

## Current Areas of Interest

I'm continuing to deepen my work in:

* Linux infrastructure engineering
* Site Reliability Engineering
* Platform engineering
* Infrastructure automation
* Kubernetes
* Infrastructure as Code
* Distributed systems
* Observability
* Database reliability
* Secure systems programming with Go and Rust

---

## Connect

* [LinkedIn](https://www.linkedin.com/in/stephan-loesevitz-85646b225/)
* [cyberducttape.com](https://cyberducttape.com)
* [GitHub Projects](https://github.com/itchyitchy123?tab=repositories)

Open to conversations around **Linux infrastructure, systems engineering, SRE, platform operations, hosting automation, and infrastructure tooling**.
