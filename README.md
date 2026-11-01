# Oryntra OS

**An independent desktop operating system built from scratch.**

Oryntra OS is an experimental operating system project with the ambition of creating an independent desktop computing platform.

The project aims to challenge some of the limitations of today's desktop operating systems by prioritizing user freedom, application compatibility.

This project is being developed incrementally, starting with fundamental computer architecture and operating system concepts, eventually progressing towards a fully functional desktop operating system.

> Building an operating system is a long journey. This repository documents the entire process — ideas, decisions, experiments, progress, failures, challenges, and achievements.

---

## Table of Contents

- [Project Motivation](#-project-motivation)
- [Core Goals](#-core-goals)
- [Project Philosophy](#-project-philosophy)
- [Current Stage](#-current-stage)
- [What I'm Currently Working On](#-what-im-currently-working-on)
- [Development Roadmap](#-development-roadmap)
- [Progress Log](#-progress-log)
- [Problems and Challenges](#-problems-and-challenges)
- [Next Goals](#-next-goals)
- [How to Start Developing](#-how-to-start-developing)
- [Development Guidelines](#-development-guidelines)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [Disclaimer](#-disclaimer)

---

## Why Oryntra OS? — Project Motivation

Modern desktop operating systems provide powerful computing environments, but users still face limitations in how they control their operating systems and access software.

Two particular problems inspired this project.

**1. Users should control their operating system versions.**

When a new operating system version is released, users should not be forced to accept it simply because it is the latest release.

If someone prefers an older version, they should have the freedom to return to it without reinstalling the entire operating system or losing their personal data.

**2. Applications should not be restricted by operating system boundaries.**

Software availability is often tied to the operating system for which an application was developed.

An application targeting Windows may not work natively on Linux, and a macOS application may not be available on Windows.

The goal is to reduce these boundaries and provide users with a unified desktop application experience.

Oryntra OS is an attempt to explore and address these problems through an independent operating system.

---

## Core Goals

These are the two primary goals that define the initial direction of Oryntra OS.

### 1. Version Freedom

Users should have complete control over which version of Oryntra OS they want to use.

Expected capabilities:

- Upgrade to newer operating system versions.
- Return to previously released versions.
- Maintain access to older versions.
- Recover from unsuccessful updates.
- Preserve personal data when changing operating system versions.
- Allow users to decide when to upgrade.

The operating system should not force users to adopt a newer release simply because it is available.

### 2. Universal Desktop Application Compatibility

Users should be able to install and run desktop applications regardless of whether they were originally developed for Windows, macOS, or Linux.

Expected compatibility targets:

- Windows desktop applications.
- Linux desktop applications.
- macOS desktop applications.
- Applications built using different programming languages and development frameworks.

The goal is not merely to launch applications, but to provide functional compatibility wherever technically and legally possible.

---

## Project Philosophy

Oryntra OS will follow these principles:

- **User freedom:** Users should control their computing environment.
- **Independence:** Develop an independent operating system rather than building another Linux distribution.
- **Compatibility:** Reduce application availability restrictions.
- **Transparency:** Document decisions, limitations, and development progress.
- **Reliability:** Prioritize a dependable computing experience.
- **Learning through development:** Understand and build the underlying operating system components rather than blindly relying on existing implementations.

---

## Current Stage

**Stage: Initial Planning and Research**

<details>
<summary>Current project status</summary>

| Area | Status |
|---|---|
| Project name | Decided — Oryntra OS |
| Project motivation | Defined |
| Core product goals | Defined |
| Product requirements | Initial |
| Operating system architecture | Not decided |
| Target hardware | Not finalized |
| Programming languages | Not finalized |
| Kernel development | Not started |
| Bootloader development | Not started |
| Prototype | Not started |

</details>

The project is currently in its planning stage. Technical architecture and implementation decisions will be made after the initial product requirements and development roadmap are established.

---

## What I'm Currently Working On

**Current focus: Defining the product and its direction.**

Activities:

- Establishing the purpose of Oryntra OS.
- Identifying problems the operating system should solve.
- Defining product requirements.
- Researching operating system fundamentals.
- Understanding how existing desktop operating systems work.
- Planning the initial prototype.

This section will be updated whenever the current focus changes.

---

## Development Roadmap

The following roadmap represents the intended development journey. It is not a fixed implementation plan.

### Phase 1 — Product Planning

- [x] Choose the project name.
- [x] Define the initial project motivation.
- [x] Establish the two primary product goals.
- [ ] Finalize product requirements.
- [ ] Define prototype scope.
- [ ] Establish measurable prototype success criteria.

### Phase 2 — Research and Architecture

- [ ] Study computer architecture.
- [ ] Study operating system fundamentals.
- [ ] Research existing operating system architectures.
- [ ] Define the target hardware architecture.
- [ ] Decide the kernel architecture.
- [ ] Define the boot process.
- [ ] Establish the initial technical stack.

### Phase 3 — Initial OS Prototype

- [ ] Establish the development environment.
- [ ] Create the initial bootable kernel.
- [ ] Achieve the first successful boot.
- [ ] Implement basic screen output.
- [ ] Implement fundamental memory management.
- [ ] Implement basic interrupt handling.

### Phase 4 — Core Operating System

- [ ] CPU and process management.
- [ ] Memory management.
- [ ] Device management.
- [ ] Basic device drivers.
- [ ] Filesystem support.
- [ ] System calls.
- [ ] User-space execution.

### Phase 5 — Desktop Environment

- [ ] Display and graphics support.
- [ ] Window management.
- [ ] Input handling.
- [ ] Desktop interface.
- [ ] Application management.
- [ ] System settings.

### Phase 6 — Product Goals

- [ ] Design the version management experience.
- [ ] Implement operating system version switching.
- [ ] Implement reliable rollback.
- [ ] Establish universal application compatibility goals.
- [ ] Develop and validate application compatibility.
- [ ] Test real-world desktop workflows.

### Phase 7 — Long-Term Development

- [ ] Improve hardware compatibility.
- [ ] Improve performance and reliability.
- [ ] Expand application compatibility.
- [ ] Establish an update and release system.
- [ ] Prepare for broader testing.

---

## Progress Log

This section records what happens during development.

Every meaningful milestone, experiment, discovery, failure, or architectural decision should be documented here.

### November 2026

**November 1, 2026 — Project Initiation**

- Selected the name Oryntra OS.
- Established the initial project motivation.
- Defined two primary goals:
  - Version freedom.
  - Universal desktop application compatibility.
- Started documenting the product requirements.
- Created the initial project repository.

### Progress Log Template

Use this template for future updates:

```markdown
### YYYY-MM-DD — Title

**What I worked on:**
- 

**What I learned:**
- 

**What I achieved:**
- 

**Problems encountered:**
- 

**Decisions made:**
- 

**Next steps:**
- 
```

---

## Problems and Challenges

This section tracks technical, architectural, research, and development challenges.

No problem should be hidden. Failed experiments and unresolved issues are part of the development process.

### Active Challenges

_No technical challenges recorded yet. Development has not started._

### Challenge Tracking Template

```markdown
### Problem: Problem title

**Date discovered:**

**Description:**
Explain the problem.

**Expected behaviour:**
What should happen?

**Actual behaviour:**
What happened instead?

**Investigation:**
What has been tried?

**Current status:**
- Open
- Investigating
- Resolved
- Blocked

**Resolution:**
Document the solution when available.
```

---

## Next Goals

The immediate objectives are:

1. Complete the initial product requirements.
2. Define exactly what the first prototype must demonstrate.
3. Establish the operating system's architectural direction.
4. Finalize the target hardware and technical stack.
5. Begin the first practical development milestone.

Only after the current objectives are completed should the next set of goals be introduced.

---

## How to Start Developing

Oryntra OS is currently in its planning stage. The actual development setup and build instructions will be documented once the architecture and technology choices are finalized.

### Prerequisites

The initial development environment is expected to require:

- A Linux-based development machine.
- A code editor.
- Version control using Git.
- A compiler and assembler.
- An operating system emulator.
- Debugging tools.
- Basic knowledge of computer architecture and low-level programming.

The exact tools and versions will be documented in a dedicated development guide.

### Getting the Repository

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/oryntra-os.git

cd oryntra-os
```

### Development Workflow

The intended development workflow:

1. Review the current project goals and roadmap.
2. Check the latest progress logs.
3. Review open problems and challenges.
4. Select an achievable development milestone.
5. Research and document the intended changes.
6. Implement and test the changes.
7. Document the results, including unsuccessful experiments.
8. Update the roadmap and progress log.

### Technical Development Guide

Detailed instructions will be added as the project progresses:

- [ ] Development environment setup.
- [ ] Required tools and dependencies.
- [ ] Source code organization.
- [ ] Build instructions.
- [ ] Running the OS in an emulator.
- [ ] Debugging instructions.
- [ ] Testing procedures.
- [ ] Release and versioning process.

---

## Development Guidelines

To keep the project organized:

1. Every major feature should have a documented objective.
2. Significant architectural decisions should be recorded.
3. Progress logs should reflect actual work completed.
4. Unresolved problems should remain visible.
5. Features should not be marked complete until tested.
6. Product requirements should guide technical decisions.
7. Development should proceed through small, verifiable milestones.

---

## Project Structure

The repository structure will evolve as development progresses.

The initial documentation layout is:

```text
oryntra-os/
│
├── README.md
│
├── docs/
│   ├── product-requirements.md
│   ├── architecture.md
│   ├── development-guide.md
│   └── decisions/
│
├── logs/
│   └── progress.md
│
├── challenges/
│   └── README.md
│
└── src/
    └── (Future source code)
```

This is a proposed documentation structure, not the finalized source code architecture.

---

## Contributing

Oryntra OS is an independent operating system development project.

Contributions, discussions, suggestions, research findings, and constructive feedback are welcome.

Before proposing major changes:

1. Understand the project's core goals.
2. Review existing documentation.
3. Explain the problem or improvement.
4. Describe the expected outcome.

Contributions should align with the project's long-term direction.

---

## Disclaimer

Oryntra OS is an experimental project under active planning and development.

It is not currently intended for production use.

The project aims to develop an independent desktop operating system and is not based on an existing Linux, Windows, or macOS kernel.

Application compatibility across operating systems is an ambitious long-term objective and is subject to technical, hardware, and licensing limitations.

---

## Final Note

An operating system is not built in a day.

This repository will serve as the public development journal of Oryntra OS — documenting the journey from initial ideas and research to a working operating system.

**One project. Independent development. Two initial goals. One milestone at a time.**

