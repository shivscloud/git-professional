# DOCKER: ZERO TO PROFESSIONAL — COMPLETE DEEP DIVE
## Professional PowerPoint Book — Slide Content Specification
**Target: 220 Slides | Dark Technical Theme | Production-Ready**

---

# PART 0 — DOCKER LEARNING ROADMAP
**Slides: 1-8**

---

## Slide 1 — Cover Slide

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║    ██████╗  ██████╗  ██████╗██╗  ██╗███████╗██████╗              ║
║    ██╔══██╗██╔═══██╗██╔════╝██║ ██╔╝██╔════╝██╔══██╗             ║
║    ██║  ██║██║   ██║██║     █████╔╝ █████╗  ██████╔╝             ║
║    ██║  ██║██║   ██║██║     ██╔═██╗ ██╔══╝  ██╔══██╗             ║
║    ██████╔╝╚██████╔╝╚██████╗██║  ██╗███████╗██║  ██║             ║
║    ╚═════╝  ╚═════╝  ╚═════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝             ║
║                                                                  ║
║           ZERO TO PROFESSIONAL — COMPLETE DEEP DIVE              ║
║                                                                  ║
║    From Beginner → Engineer → Production → Kubernetes Expert     ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

**Subtitle:** A Complete Technical Reference for DevOps, Platform, and Kubernetes Engineers

**Footer:** 220+ Slides | 50+ Labs | 150+ Interview Questions | Production Patterns

---

## Slide 2 — What This Course Teaches

```
┌─────────────────────────────────────────────────────────────────┐
│                    LEARNING OUTCOMES                             │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  LEVEL 1 — USER                                                  │
│  ├─ Execute any docker run command with full understanding      │
│  ├─ Understand every flag, option, and parameter                │
│  └─ Troubleshoot common container issues                        │
│                                                                  │
│  LEVEL 2 — ENGINEER                                              │
│  ├─ Explain Docker CLI → API → Daemon → Runtime architecture    │
│  ├─ Design production-grade Dockerfiles                         │
│  ├─ Implement secure networking and storage patterns            │
│  └─ Build CI/CD pipelines with image security                   │
│                                                                  │
│  LEVEL 3 — INTERNALS                                             │
│  ├─ Trace container startup: dockerd → containerd → runc        │
│  ├─ Explain namespaces, cgroups, OverlayFS internals            │
│  ├─ Understand OCI specifications and container runtimes        │
│  └─ Debug Kubernetes runtime issues from Docker knowledge       │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## Slide 3 — Docker Skill Progression

```
                    DOCKER SKILL PROGRESSION
    ┌─────────────────────────────────────────────────────────┐
    │                                                         │
    │  EXPERT    ████████████████████████████████████████ 100%│
    │            ├─ Architecture Design                       │
    │            ├─ Platform Engineering                      │
    │            ├─ Kubernetes Runtime Deep Dive              │
    │            └─ Security Architecture                     │
    │                                                         │
    │  SENIOR    ████████████████████████████████───────  80% │
    │            ├─ Production Operations                     │
    │            ├─ CI/CD Pipeline Design                     │
    │            ├─ Multi-Stage Builds                        │
    │            ├─ Security Hardening                        │
    │            └─ Performance Optimization                  │
    │                                                         │
    │  INTERMEDIATE ████████████████████████────────────  60% │
    │            ├─ Dockerfile Mastery                        │
    │            ├─ Networking & Storage                      │
    │            ├─ Compose Patterns                          │
    │            ├─ Registry Management                       │
    │            └─ BuildKit & Buildx                         │
    │                                                         │
    │  BEGINNER  ████████████──────────────────────────────── 30% │
    │            ├─ CLI Fundamentals                          │
    │            ├─ Container Lifecycle                       │
    │            ├─ Image Basics                              │
    │            ├─ Basic Dockerfile                          │
    │            └─ Simple Networking                         │
    │                                                         │
    └─────────────────────────────────────────────────────────┘
```

---

## Slide 4 — Beginner → Professional Roadmap

```
    ┌──────────────┬──────────────┬──────────────┬──────────────┐
    │   PHASE 1    │   PHASE 2    │   PHASE 3    │   PHASE 4    │
    │  FOUNDATION  │   DEEP DIVE  │   ADVANCED   │  PRODUCTION  │
    ├──────────────┼──────────────┼──────────────┼──────────────┤
    │              │              │              │              │
    │  • Install   │  • Dockerfile│  • BuildKit  │  • Security  │
    │  • CLI       │  • Layers    │  • Multi-arch│  • CI/CD     │
    │  • Run       │  • Networking│  • Compose   │  • Registry  │
    │  • Images    │  • Storage   │  • Internals │  • K8s       │
    │  • Lifecycle │  • Volumes   │  • Namespaces│  • Scaling   │
    │              │              │  • cgroups   │  • Observ.   │
    │              │              │              │              │
    │  2 Weeks     │  3 Weeks     │  3 Weeks     │  2 Weeks     │
    │              │              │              │              │
    └──────────────┴──────────────┴──────────────┴──────────────┘
                              ↓
                    ┌──────────────────┐
                    │  DAY 1-90 PLAN   │
                    │  • 30 Days: Core │
                    │  • 60 Days: Deep │
                    │  • 90 Days: Prod │
                    └──────────────────┘
```

---

## Slide 5 — Labs and Project Roadmap

```
    REAL-WORLD PROJECT PROGRESSION

    ┌─────────────────────────────────────────────────────────────┐
    │  WEEK 1-2: SINGLE CONTAINER                                 │
    │  ├─ Lab 1-5: Run, inspect, lifecycle, logs, exec           │
    │  └─ Deliverable: Running nginx + custom app                │
    │                                                             │
    │  WEEK 3-4: MULTI-CONTAINER                                  │
    │  ├─ Lab 6-10: Networks, DNS, volumes, Compose basics       │
    │  └─ Deliverable: Frontend + Backend + DB (local)           │
    │                                                             │
    │  WEEK 5-6: DOCKERFILE MASTERY                               │
    │  ├─ Lab 11-15: Multi-stage, cache, security, healthchecks  │
    │  └─ Deliverable: Optimized production Dockerfile           │
    │                                                             │
    │  WEEK 7-8: PRODUCTION PATTERNS                              │
    │  ├─ Lab 16-20: CI/CD, registry, security, monitoring       │
    │  └─ Deliverable: Complete pipeline + hardened containers   │
    │                                                             │
    │  WEEK 9-10: KUBERNETES BRIDGE                               │
    │  ├─ Lab 21-25: Image flow, troubleshooting, runtime        │
    │  └─ Deliverable: K8s deployment from Docker knowledge      │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 6 — How to Study This PowerPoint

```
    STUDY METHODOLOGY

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  FOR EACH TOPIC:                                            │
    │  ┌─────────────────────────────────────────────────────┐   │
    │  │ 1. READ the concept slide                           │   │
    │  │ 2. STUDY the architecture diagram                   │   │
    │  │ 3. EXECUTE the command examples                     │   │
    │  │ 4. OBSERVE the internal behavior                    │   │
    │  │ 5. COMPLETE the hands-on lab                        │   │
    │  │ 6. ANSWER the interview questions                   │   │
    │  │ 7. REVIEW the production checklist                  │   │
    │  └─────────────────────────────────────────────────────┘   │
    │                                                             │
    │  RECOMMENDED PACE:                                          │
    │  • Self-study: 2-3 hours/day                               │
    │  • With labs: 4-5 hours/day                                │
    │  • Interview prep: Focus on Parts 53-54                    │
    │  • Production reference: Parts 48-49, 55                   │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 7 — Docker Command/Reference Strategy

```
    COMMAND GRAMMAR

    docker <OBJECT> <COMMAND> [OPTIONS]

    ┌─────────────┬──────────────────────────────────────────────┐
    │   OBJECT    │   COMMON COMMANDS                            │
    ├─────────────┼──────────────────────────────────────────────┤
    │ container   │ run, create, start, stop, restart, rm, exec  │
    │ image       │ build, pull, push, tag, inspect, history     │
    │ volume      │ create, ls, inspect, rm, prune               │
    │ network     │ create, ls, inspect, connect, disconnect     │
    │ compose     │ up, down, ps, logs, exec, build              │
    │ system      │ df, prune, info, events                      │
    │ buildx      │ build, ls, inspect, create, use              │
    └─────────────┴──────────────────────────────────────────────┘

    TIP: Every object has: create, ls, inspect, rm
```

---

## Slide 8 — Docker Interview Roadmap

```
    INTERVIEW PREPARATION TRACKS

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  TRACK A: BEGINNER (50 Questions)                           │
    │  Parts: 4, 5, 6, 7  →  CLI, Run, Lifecycle, Images          │
    │                                                             │
    │  TRACK B: INTERMEDIATE (50 Questions)                       │
    │  Parts: 10-17  →  Dockerfile, Networking, Storage, Compose  │
    │                                                             │
    │  TRACK C: ADVANCED (50 Questions)                           │
    │  Parts: 19-22, 31-36  →  Security, Internals, Namespaces    │
    │                                                             │
    │  TRACK D: SENIOR TROUBLESHOOTING (30 Questions)             │
    │  Part: 30, 44  →  Production failures, K8s bridge           │
    │                                                             │
    │  TRACK E: ARCHITECTURE (20 Questions)                       │
    │  Parts: 2, 41-43, 54  →  System design, OCI, K8s runtime    │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

# PART 1 — WHAT IS DOCKER?
**Slides: 9-20**

---

## Slide 9 — What is Docker?

```
    ┌─────────────────────────────────────────────────────────────┐
    │  DOCKER — THE DEFINITION                                     │
    ├─────────────────────────────────────────────────────────────┤
    │                                                             │
    │  Docker is a platform that enables developers to:           │
    │                                                             │
    │  1. PACKAGE applications with all dependencies              │
    │  2. DISTRIBUTE consistently across environments             │
    │  3. RUN isolated processes sharing the host kernel          │
    │  4. MANAGE the full application lifecycle                   │
    │                                                             │
    │  Key insight: Docker automates OS-level virtualization.     │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

**Speaker Notes:**
- Docker is NOT a virtual machine
- Docker leverages Linux kernel features (namespaces, cgroups)
- The "container" concept predates Docker (LXC, chroot, jails)
- Docker made containers accessible and standardized

---

## Slide 10 — What Docker is NOT

```
    COMMON MISCONCEPTIONS

    ┌─────────────────────────────────────────────────────────────┐
    │  ❌ Docker is NOT a VM                                       │
    │     • No guest OS, no hypervisor                             │
    │     • Containers share the host kernel                       │
    │                                                             │
    │  ❌ Docker is NOT just "lightweight VMs"                     │
    │     • Different isolation model entirely                     │
    │     • Different performance characteristics                  │
    │                                                             │
    │  ❌ Docker is NOT a programming language                     │
    │     • It's a runtime and tooling platform                    │
    │                                                             │
    │  ❌ Docker is NOT required for containers                    │
    │     • containerd, CRI-O, podman are alternatives             │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 11 — Containerization Concept

```
    CONTAINERIZATION — THE CORE IDEA

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │         ┌─────────────────────────────────────┐            │
    │         │         APPLICATION + DEPS          │            │
    │         │  ┌─────┐  ┌─────┐  ┌─────┐  ┌─────┐│            │
    │         │  │Code │  │ Libs│  │Conf │  │Tools││            │
    │         │  └─────┘  └─────┘  └─────┘  └─────┘│            │
    │         └─────────────────────────────────────┘            │
    │                              ↓                             │
    │                    ┌─────────────────┐                     │
    │                    │   CONTAINER     │                     │
    │                    │  (Isolated)     │                     │
    │                    └─────────────────┘                     │
    │                              ↓                             │
    │                    ┌─────────────────┐                     │
    │                    │   HOST KERNEL   │                     │
    │                    │  (Shared)       │                     │
    │                    └─────────────────┘                     │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 12 — Application Packaging Evolution

```
    EVOLUTION OF APPLICATION DEPLOYMENT

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  BARE METAL (2000s)                                         │
    │  ┌─────────────────────────────────────────────────────┐   │
    │  │  App runs directly on OS                            │   │
    │  │  Problem: "Works on my machine" syndrome            │   │
    │  └─────────────────────────────────────────────────────┘   │
    │                                                             │
    │  VIRTUAL MACHINES (2010s)                                   │
    │  ┌─────────────────────────────────────────────────────┐   │
    │  │  Full OS per application → Heavy, slow, wasteful    │   │
    │  └─────────────────────────────────────────────────────┘   │
    │                                                             │
    │  CONTAINERS (2013+)                                         │
    │  ┌─────────────────────────────────────────────────────┐   │
    │  │  Shared kernel → Lightweight, fast, dense           │   │
    │  │  Application + dependencies packaged together       │   │
    │  └─────────────────────────────────────────────────────┘   │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 13 — Process Isolation

```
    HOW CONTAINERS ACHIEVE ISOLATION

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  WITHOUT CONTAINERS:                                        │
    │  ┌─────────────────────────────────────────────────────┐   │
    │  │  Host: PID 1, 2, 3, 4, 5...                         │   │
    │  │         ↑    ↑  ↑  ↑  ↑                              │   │
    │  │      System processes + App processes mixed         │   │
    │  └─────────────────────────────────────────────────────┘   │
    │                                                             │
    │  WITH CONTAINERS:                                           │
    │  ┌─────────────────────────────────────────────────────┐   │
    │  │  Host:    PID 100, 200, 300...                      │   │
    │  │             ↓      ↓      ↓                         │   │
    │  │  Container A: PID 1, 2, 3... (isolated view)        │   │
    │  │  Container B: PID 1, 2, 3... (isolated view)        │   │
    │  └─────────────────────────────────────────────────────┘   │
    │                                                             │
    │  Isolation achieved through: Namespaces + cgroups           │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 14 — Containers vs Virtual Machines

```
    ┌─────────────────────────────────────────────────────────────┐
    │           CONTAINERS vs VIRTUAL MACHINES                     │
    ├─────────────────────────────────────────────────────────────┤
    │                                                              │
    │  CHARACTERISTIC    │  CONTAINER      │  VIRTUAL MACHINE     │
    │  ──────────────────┼─────────────────┼──────────────────────│
    │  Guest OS          │  None (shared)  │  Full OS per VM      │
    │  Kernel            │  Host kernel    │  Guest kernel        │
    │  Hypervisor        │  Not required   │  Required            │
    │  Startup time      │  < 1 second     │  Minutes             │
    │  Resource overhead │  Low (MB)       │  High (GB)           │
    │  Density           │  Thousands/Host │  Dozens/Host         │
    │  Isolation         │  Process-level  │  Hardware-level      │
    │  Portability       │  High           │  Medium              │
    │  Security          │  Kernel shared  │  Stronger isolation  │
    │                                                              │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 15 — Bare Metal vs VM vs Container

```
                        COMPARISON VISUAL

    BARE METAL              VIRTUAL MACHINE           CONTAINER

    ┌─────────────┐        ┌─────────────┐          ┌─────────────┐
    │   App A     │        │  ┌─────────┐│          │  ┌─────────┐│
    │   App B     │        │  │ GuestOS ││          │  │ App +   ││
    │   App C     │        │  │  App A  ││          │  │ Deps    ││
    │             │        │  └─────────┘│          │  └─────────┘│
    │   Host OS   │        │  ┌─────────┐│          │  ┌─────────┐│
    │             │        │  │ GuestOS ││          │  │ App +   ││
    │             │        │  │  App B  ││          │  │ Deps    ││
    │             │        │  └─────────┘│          │  └─────────┘│
    │             │        │  Hypervisor │          │             │
    │             │        │             │          │             │
    └─────────────┘        └─────────────┘          │   Host OS   │
                                                    │             │
                                                    └─────────────┘

    Heavy coupling          Heavy isolation         Lightweight isolation
    No portability          Good portability        Excellent portability
```

---

## Slide 16 — Why Containers Became Important

```
    THE CONTAINER REVOLUTION — DRIVERS

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  1. MICROSERVICES                                           │
    │     • Many small services → Need consistent environments    │
    │     • Different tech stacks → Need isolation                │
    │                                                             │
    │  2. CLOUD NATIVE                                            │
    │     • Scale horizontally → Need density                     │
    │     • Ephemeral infrastructure → Need speed                 │
    │                                                             │
    │  3. DEVOPS CULTURE                                          │
    │     • "Works on my machine" → Eliminated                    │
    │     • CI/CD pipelines → Standardized builds                 │
    │                                                             │
    │  4. IMMUTABLE INFRASTRUCTURE                                │
    │     • Reproducible deployments                              │
    │     • Version-controlled environments                       │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 17 — Microservices and Containers

```
    CONTAINERS ENABLE MICROSERVICES

    BEFORE (Monolith):                    AFTER (Microservices):

    ┌─────────────────────┐              ┌─────┐  ┌─────┐  ┌─────┐
    │                     │              │User │  │Order│  │Pay  │
    │   MONOLITHIC        │              │Svc  │  │Svc  │  │Svc  │
    │   APPLICATION       │              └─────┘  └─────┘  └─────┘
    │                     │                 │        │        │
    │  ┌───────────────┐  │              ┌─────┐  ┌─────┐  ┌─────┐
    │  │   UI Layer    │  │              │Prod │  │Cart │  │Notif│
    │  ├───────────────┤  │              │Svc  │  │Svc  │  │Svc  │
    │  │  Business     │  │              └─────┘  └─────┘  └─────┘
    │  │   Logic       │  │
    │  ├───────────────┤  │              Each service:
    │  │   Data        │  │              • Independent deploy
    │  │   Access      │  │              • Own technology stack
    │  └───────────────┘  │              • Own scaling
    │                     │              • Isolated failures
    └─────────────────────┘

    Problem: Tight coupling,    Solution: Loose coupling,
             slow deployments            fast independent deploys
```

---

## Slide 18 — Portability

```
    DOCKER'S PORTABILITY PROMISE

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │         ┌─────────────┐                                     │
    │         │ Dockerfile  │                                     │
    │         │   / Image   │                                     │
    │         └──────┬──────┘                                     │
    │                │                                            │
    │     ┌──────────┼──────────┐                                 │
    │     │          │          │                                 │
    │     ▼          ▼          ▼                                 │
    │  ┌─────┐    ┌─────┐    ┌─────┐                              │
    │  │Local│    │  CI │    │ Prod│                              │
    │  │ Dev │    │Server│   │ K8s │                              │
    │  └─────┘    └─────┘    └─────┘                              │
    │                                                             │
    │  SAME IMAGE → SAME BEHAVIOR → EVERYWHERE                    │
    │                                                             │
    │  Eliminates: "It works on my machine"                       │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 19 — Immutable Infrastructure

```
    IMMUTABLE INFRASTRUCTURE PRINCIPLE

    MUTABLE (Traditional):              IMMUTABLE (Docker):

    ┌─────────────────────┐            ┌─────────────────────┐
    │  Server v1.0        │            │  Image: app:v1.0    │
    │  ├─ Install pkg A   │            │  ├─ FROM base       │
    │  ├─ Configure X     │            │  ├─ COPY code       │
    │  ├─ Patch security  │            │  ├─ RUN build       │
    │  │                  │            │  └─ Result: v1.0    │
    │  Server v1.1        │            │                     │
    │  ├─ Update pkg B    │            │  Image: app:v1.1    │
    │  ├─ Change config   │            │  ├─ FROM base       │
    │  └─ Hope it works   │            │  ├─ COPY code       │
    │                     │            │  ├─ RUN build       │
    │  Problem: Drift     │            │  └─ Result: v1.1    │
    │                     │            │                     │
    │                     │            │  v1.0 and v1.1      │
    │                     │            │  are DISTINCT       │
    │                     │            │  No drift possible  │
    └─────────────────────┘            └─────────────────────┘
```

---

## Slide 20 — Reproducibility

```
    REPRODUCIBILITY — THE DOCKER ADVANTAGE

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  TRADITIONAL DEPLOYMENT:                                    │
    │  "Install these packages, run these commands..."            │
    │  → Different results on different machines                  │
    │  → Manual steps prone to error                              │
    │  → No version control of environment                        │
    │                                                             │
    │  DOCKER DEPLOYMENT:                                         │
    │  docker run myapp:1.2.3                                     │
    │  → Identical result everywhere                              │
    │  → Image is version-controlled                              │
    │  → Declarative, auditable                                   │
    │                                                             │
    │  Key: The image IS the deployment artifact                  │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

# PART 2 — DOCKER ARCHITECTURE
**Slides: 21-35**

---

## Slide 21 — Docker Architecture Overview

```
                    DOCKER ARCHITECTURE

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │   DEVELOPER                                                 │
    │       │                                                     │
    │       ▼                                                     │
    │   ┌─────────┐                                               │
    │   │Docker   │  ← CLI (Client)                               │
    │   │CLI      │                                               │
    │   └────┬────┘                                               │
    │        │  REST API                                          │
    │        ▼                                                     │
    │   ┌─────────┐    ┌──────────┐                               │
    │   │ dockerd │───→│containerd│                               │
    │   │(Daemon) │    │          │                               │
    │   └────┬────┘    └────┬─────┘                               │
    │        │              │                                     │
    │        │              ▼                                     │
    │        │         ┌─────────┐                                │
    │        │         │  runc   │  ← OCI Runtime                 │
    │        │         └────┬────┘                                │
    │        │              │                                     │
    │        │              ▼                                     │
    │        │         ┌─────────┐                                │
    │        │         │  Linux  │                                │
    │        │         │  Kernel │                                │
    │        │         └─────────┘                                │
    │        │              │                                     │
    │        └──────────────┘                                     │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 22 — Component Responsibilities

```
    ┌─────────────────────────────────────────────────────────────┐
    │  COMPONENT          │  RESPONSIBILITY                        │
    ├─────────────────────┼────────────────────────────────────────┤
    │  Docker CLI         │  User interface, command parsing       │
    │  Docker API         │  REST interface for daemon             │
    │  dockerd            │  Image management, API server          │
    │  containerd         │  Container lifecycle, image pull       │
    │  containerd-shim    │  Process supervision, signal handling  │
    │  runc               │  OCI runtime, create container process │
    │  Linux Kernel       │  Namespaces, cgroups, filesystems      │
    └─────────────────────┴────────────────────────────────────────┘
```

---

## Slide 23 — Client/Server Architecture

```
    DOCKER CLIENT/SERVER MODEL

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  LOCAL:                                                     │
    │  ┌──────────┐         Unix Socket          ┌──────────┐   │
    │  │  docker  │ ───────────────────────────→ │ dockerd  │   │
    │  │   CLI    │  ←────────────────────────── │ daemon   │   │
    │  └──────────┘         (Responses)          └──────────┘   │
    │                                                             │
    │  REMOTE:                                                    │
    │  ┌──────────┐         TCP/SSH              ┌──────────┐   │
    │  │  docker  │ ───────────────────────────→ │ dockerd  │   │
    │  │   CLI    │                              │  (Remote)│   │
    │  └──────────┘                              └──────────┘   │
    │                                                             │
    │  Default socket: /var/run/docker.sock                       │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 24 — Docker Daemon (dockerd)

```
    DOCKER DAEMON RESPONSIBILITIES

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  dockerd manages:                                           │
    │                                                             │
    │  ├─ Image operations                                        │
    │  │   • Pull, push, build, tag, remove                       │
    │  │   • Layer storage and caching                            │
    │  │                                                           │
    │  ├─ Container lifecycle                                     │
    │  │   • Create, start, stop, pause                           │
    │  │   • Resource allocation                                  │
    │  │                                                           │
    │  ├─ Network management                                      │
    │  │   • Bridge creation, NAT rules                           │
    │  │   • DNS, service discovery                               │
    │  │                                                           │
    │  ├─ Volume management                                       │
    │  │   • Volume creation, mounting                            │
    │  │                                                           │
    │  └─ Plugin system                                           │
    │      • Logging drivers, volume drivers, network drivers     │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 25 — containerd Deep Dive

```
    containerd — THE CONTAINER RUNTIME

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  containerd is the industry-standard container runtime.     │
    │                                                             │
    │  Key responsibilities:                                      │
    │  ├─ Image management (pull, unpack, snapshot)               │
    │  ├─ Container lifecycle (create, start, stop, delete)       │
    │  ├─ Snapshot management (layer storage)                     │
    │  ├─ Network namespace setup                                 │
    │  ├─ Mount namespace setup                                   │
    │  └─ Invocation of OCI runtime (runc)                        │
    │                                                             │
    │  containerd is used by:                                     │
    │  • Docker Engine                                            │
    │  • Kubernetes (via CRI)                                     │
    │  • containerd standalone                                    │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 26 — runc — The OCI Runtime

```
    runc — EXECUTING THE CONTAINER

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  runc is the reference implementation of the OCI Runtime    │
    │  Specification.                                             │
    │                                                             │
    │  What runc does:                                            │
    │  ├─ Create container process                                │
    │  ├─ Set up namespaces (PID, network, mount, etc.)           │
    │  ├─ Configure cgroups (CPU, memory, PIDs)                   │
    │  ├─ Apply security profiles (capabilities, seccomp)         │
    │  ├─ Execute the container's entrypoint                      │
    │  └─ Manage the container lifecycle                          │
    │                                                             │
    │  runc is NOT Docker-specific — any OCI-compliant runtime    │
    │  can use it.                                                │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 27 — OCI Specification

```
    OPEN CONTAINER INITIATIVE (OCI)

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  OCI defines THREE specifications:                          │
    │                                                             │
    │  1. OCI IMAGE SPECIFICATION                                 │
    │     • How container images are structured                   │
    │     • Manifests, layers, configuration                      │
    │                                                             │
    │  2. OCI RUNTIME SPECIFICATION                               │
    │     • How to run a container                                │
    │     • Runtime lifecycle, state, hooks                       │
    │                                                             │
    │  3. OCI DISTRIBUTION SPECIFICATION                          │
    │     • How to distribute images                              │
    │     • Registry API, authentication                          │
    │                                                             │
    │  Docker contributed these specs to the Linux Foundation.    │
    │  They are now vendor-neutral standards.                     │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 28 — Linux Kernel Role

```
    LINUX KERNEL — THE FOUNDATION

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  Docker containers rely on these kernel features:           │
    │                                                             │
    │  ┌─────────────┬────────────────────────────────────────┐  │
    │  │  Namespaces │ Process, network, mount, UTS, IPC,     │  │
    │  │             │ user, cgroup isolation                 │  │
    │  ├─────────────┼────────────────────────────────────────┤  │
    │  │  cgroups    │ CPU, memory, PID, I/O resource control │  │
    │  ├─────────────┼────────────────────────────────────────┤  │
    │  │  OverlayFS  │ Union filesystem for layer storage     │  │
    │  ├─────────────┼────────────────────────────────────────┤  │
    │  │  Capabilities│ Fine-grained privilege control        │  │
    │  ├─────────────┼────────────────────────────────────────┤  │
    │  │  seccomp    │ System call filtering                  │  │
    │  └─────────────┴────────────────────────────────────────┘  │
    │                                                             │
    │  Without these kernel features, containers cannot exist.    │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 29 — Container Startup Flow

```
    WHAT HAPPENS WHEN YOU RUN: docker run nginx

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  1. CLI parses command, sends API request                   │
    │  2. dockerd receives request                                │
    │  3. Image resolution: check local, pull if needed           │
    │  4. Create container config (namespaces, mounts, etc.)      │
    │  5. containerd creates container snapshot                   │
    │  6. containerd prepares network namespace                   │
    │  7. containerd invokes runc with OCI spec                   │
    │  8. runc creates namespaces                                 │
    │  9. runc configures cgroups                                 │
    │  10. runc applies security profiles                         │
    │  11. runc executes entrypoint (nginx)                       │
    │  12. Container process running as PID 1                     │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 30 — Docker vs containerd vs Kubernetes

```
    ┌─────────────────────────────────────────────────────────────┐
    │  RUNTIME COMPARISON                                          │
    ├─────────────────────────────────────────────────────────────┤
    │                                                              │
    │  DOCKER ENGINE                                              │
    │  • Full-featured daemon with CLI, API, image management     │
    │  • Uses containerd internally                               │
    │  • Developer-friendly, feature-rich                         │
    │                                                              │
    │  containerd                                                 │
    │  • Lightweight runtime, no CLI                              │
    │  • Used by Docker and Kubernetes                            │
    │  • Focus: container lifecycle only                          │
    │                                                              │
    │  KUBERNETES                                                 │
    │  • Orchestration platform                                   │
    │  • Uses containerd (or CRI-O) as runtime                    │
    │  • Does NOT require Docker Engine                           │
    │  • Manages containers across many nodes                     │
    │                                                              │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 31 — Architecture Decision Points

```
    WHEN TO USE WHAT

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  USE DOCKER ENGINE WHEN:                                    │
    │  • Local development                                        │
    │  • Simple deployments                                       │
    │  • Need full CLI and tooling                                │
    │                                                             │
    │  USE containerd DIRECTLY WHEN:                              │
    │  • Building custom tooling                                  │
    │  • Minimal runtime needed                                   │
    │                                                             │
    │  USE KUBERNETES WHEN:                                       │
    │  • Multi-node orchestration                                 │
    │  • Complex deployments                                      │
    │  • Need auto-scaling, self-healing                          │
    │                                                             │
    │  NOTE: Kubernetes can use containerd WITHOUT Docker Engine  │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 32-35 — [Additional Architecture Deep Dives]

*Detailed slides on: socket communication, API endpoints, daemon configuration, runtime hooks, shim process, snapshotters, content stores*

---

# PART 3 — INSTALLATION AND ENVIRONMENT
**Slides: 36-45**

---

## Slide 36 — Installation Options

```
    DOCKER INSTALLATION PATHS

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  DOCKER DESKTOP (Recommended for dev)                       │
    │  ├─ Windows + WSL2 backend                                  │
    │  ├─ macOS + Linux VM backend                                │
    │  ├─ Includes Kubernetes option                              │
    │  └─ GUI + CLI                                               │
    │                                                             │
    │  DOCKER ENGINE (Linux servers)                              │
    │  ├─ Native Linux installation                               │
    │  ├─ Production deployments                                  │
    │  └─ Full control over configuration                         │
    │                                                             │
    │  DOCKER ROOTLESS (Advanced)                                 │
    │  ├─ Run without root privileges                             │
    │  ├─ Enhanced security                                       │
    │  └─ Some feature limitations                                │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 37 — Docker on Linux

```
    LINUX INSTALLATION

    # Official Docker repository (recommended)
    curl -fsSL https://get.docker.com | sh

    # Or manual steps:
    # 1. Add Docker's official GPG key
    # 2. Add repository to Apt sources
    # 3. apt update && apt install docker-ce

    # Verify installation
    sudo systemctl status docker
    sudo docker run hello-world

    # Post-install: Add user to docker group
    sudo usermod -aG docker $USER
    # Then logout and login
```

---

## Slide 38 — Docker Desktop on Windows/WSL2

```
    WINDOWS + WSL2 ARCHITECTURE

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  Windows Host                                               │
    │  ├─ Docker Desktop GUI                                      │
    │  ├─ Docker CLI (optional)                                   │
    │  └─ WSL2 Integration                                        │
    │       │                                                     │
    │       ▼                                                     │
    │  WSL2 Linux VM                                              │
    │  ├─ dockerd                                                 │
    │  ├─ containerd                                              │
    │  ├─ runc                                                    │
    │  └─ Linux kernel (WSL2)                                     │
    │                                                             │
    │  Docker Desktop manages the WSL2 VM automatically.          │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 39 — Docker Version Command

```
    docker version

    Client: Docker Engine - Community
     Version:           24.0.5
     API version:       1.43
     Go version:        go1.20.6
     Git commit:        ced0996
     Built:             Wed Jul 19 19:58:50 2023
     OS/Arch:           linux/amd64
     Context:           default

    Server: Docker Desktop 4.21.1 (114176)
     Engine:
      Version:          24.0.5
      API version:      1.43 (minimum version 1.12)
      Go version:       go1.20.6
      Git commit:       ced0996
      Built:            Wed Jul 19 19:58:50 2023
      OS/Arch:          linux/amd64
      Experimental:     false
     containerd:
      Version:          1.6.21
      GitCommit:        3dce8eb
     runc:
      Version:          1.1.7
      GitCommit:        v1.1.7-0-g860f06b
```

---

## Slide 40 — Docker Info Command

```
    docker info — SYSTEM STATE

    ┌─────────────────────────────────────────────────────────────┐
    │  Server Version: 24.0.5                                     │
    │  Storage Driver: overlay2                                   │
    │    Backing Filesystem: extfs                                │
    │    Supports d_type: true                                    │
    │    Native Overlay Diff: true                                │
    │  Logging Driver: json-file                                  │
    │  Cgroup Driver: cgroupfs                                    │
    │  Cgroup Version: 2                                          │
    │  Kernel Version: 5.15.49-linuxkit                           │
    │  Operating System: Docker Desktop                           │
    │  CPUs: 8                                                    │
    │  Total Memory: 7.664GiB                                     │
    │  Docker Root Dir: /var/lib/docker                           │
    │  Registry: https://index.docker.io/v1/                      │
    │  Experimental: false                                        │
    │  Insecure Registries:                                       │
    │   127.0.0.0/8                                               │
    │  Live Restore Enabled: false                                │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 41-45 — [Troubleshooting Installation, Permissions, Socket Issues, WSL Problems, Disk Space]

---

# PART 4 — CORE DOCKER CLI
**Slides: 46-70**

---

## Slide 46 — Docker CLI Object Model

```
    DOCKER OBJECTS

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  docker container  →  Running processes                     │
    │  docker image      →  Read-only templates                   │
    │  docker volume     →  Persistent storage                    │
    │  docker network    →  Network connectivity                  │
    │  docker build      →  Image creation                        │
    │  docker context    →  Connection endpoints                  │
    │  docker plugin     →  Extensions                            │
    │                                                             │
    │  Every object supports: create, ls, inspect, rm             │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 47 — docker run — The Foundation

```
    docker run [OPTIONS] IMAGE [COMMAND] [ARG...]

    PURPOSE: Create AND start a new container from an image.

    ┌─────────────────────────────────────────────────────────────┐
    │  docker run nginx                                           │
    │    → Runs nginx in foreground (blocking)                    │
    │                                                             │
    │  docker run -d nginx                                        │
    │    → Runs nginx in background (detached)                    │
    │                                                             │
    │  docker run --name mynginx nginx                            │
    │    → Names the container "mynginx"                          │
    │                                                             │
    │  docker run -p 8080:80 nginx                                │
    │    → Maps host port 8080 to container port 80               │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 48 — docker run — Complete Flag Reference

```
    ┌─────────────────────────────────────────────────────────────┐
    │  FLAG              │  PURPOSE                               │
    ├────────────────────┼────────────────────────────────────────┤
    │  -d, --detach      │  Run in background                     │
    │  -it               │  Interactive + TTY                     │
    │  --rm              │  Remove on exit                        │
    │  -p, --publish     │  Publish ports                         │
    │  --name            │  Container name                        │
    │  -e, --env         │  Set environment variable              │
    │  -v, --volume      │  Mount volume                          │
    │  --network         │  Connect to network                    │
    │  --restart         │  Restart policy                        │
    │  --memory          │  Memory limit                          │
    │  --cpus            │  CPU limit                             │
    │  --user            │  Run as user                           │
    │  --read-only       │  Read-only filesystem                  │
    │  --cap-drop        │  Drop capabilities                     │
    │  --security-opt    │  Security options                      │
    │  --entrypoint      │  Override entrypoint                   │
    │  -w, --workdir     │  Working directory                     │
    └────────────────────┴────────────────────────────────────────┘
```

---

## Slide 49-55 — [Detailed flag explanations with examples, security implications, production recommendations]

---

## Slide 56 — docker create vs docker run

```
    docker create    →  Create container, do NOT start
    docker run       →  Create container AND start it

    USE CASE FOR docker create:
    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  # Create container with complex config                     │
    │  docker create --name myapp \                               │
    │    -p 8080:80 \                                             │
    │    -v /data:/app/data \                                     │
    │    -e ENV=prod \                                            │
    │    myimage                                                  │
    │                                                             │
    │  # Later, start when ready                                  │
    │  docker start myapp                                         │
    │                                                             │
    │  Useful for:                                                │
    │  • Pre-configuring containers                               │
    │  • Scheduled start times                                    │
    │  • Conditional startup                                      │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 57-70 — [Container lifecycle commands, image commands, monitoring commands, detailed explanations]

---

# PART 5 — docker run DEEP DIVE
**Slides: 71-90**

*Detailed breakdown of every flag with architecture, security, and production implications*

---

# PART 6 — CONTAINER LIFECYCLE
**Slides: 91-100**

---

## Slide 91 — Container States

```
                    CONTAINER LIFECYCLE

                          ┌─────────┐
                          │ created │
                          └────┬────┘
                               │ docker start
                               ▼
                          ┌─────────┐
                          │ running │◄────┐
                          └────┬────┘     │
                               │          │
                    ┌──────────┼──────────┤
                    │          │          │
                    ▼          ▼          │
              ┌─────────┐  ┌─────────┐   │ docker unpause
              │ paused  │  │ stopped │   │
              └────┬────┘  └────┬────┘   │
                   │            │        │
                   │ docker     │ docker │
                   │ pause      │ start  │
                   └────────────┘        │
                                         │
                               docker rm │
                               (if --rm) │
                               ◄─────────┘
```

---

## Slide 92 — Exit Codes and Restart Policies

```
    CONTAINER EXIT CODES

    ┌─────────────────────────────────────────────────────────────┐
    │  0    → Success / graceful shutdown                         │
    │  1    → Application error                                   │
    │  137  → SIGKILL (128 + 9)                                   │
    │  143  → SIGTERM (128 + 15)                                  │
    │  126  → Command cannot execute                              │
    │  127  → Command not found                                   │
    │                                                             │
    │  RESTART POLICIES:                                          │
    │  --restart no          → Never restart (default)            │
    │  --restart on-failure  → Restart on non-zero exit           │
    │  --restart always      → Always restart                     │
    │  --restart unless-stopped → Restart unless manually stopped │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 93-100 — [PID 1, signals, graceful shutdown, CMD vs ENTRYPOINT, shell vs exec form, practical experiments]

---

# PART 7-8 — IMAGES AND LAYERS
**Slides: 101-115**

---

## Slide 101 — Image Fundamentals

```
    WHAT IS A DOCKER IMAGE?

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  An image is a READ-ONLY template for creating containers.  │
    │                                                             │
    │  Contains:                                                  │
    │  ├─ Filesystem layers (stacked, immutable)                  │
    │  ├─ Configuration metadata                                  │
    │  ├─ Environment variables                                   │
    │  ├─ Exposed ports                                           │
    │  ├─ Entrypoint / CMD                                        │
    │  ├─ Working directory                                       │
    │  └─ User information                                        │
    │                                                             │
    │  Images are identified by:                                  │
    │  • Repository:Tag (nginx:latest)                            │
    │  • Digest (nginx@sha256:abc...)                             │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 102 — Image Layers

```
    IMAGE LAYER ARCHITECTURE

    nginx:latest

    ┌─────────────────────────────────────────────────────────────┐
    │  Layer 4:  nginx config + entrypoint      [~2KB]           │
    │  ─────────────────────────────────────────────────────      │
    │  Layer 3:  nginx binary + modules         [~50MB]          │
    │  ─────────────────────────────────────────────────────      │
    │  Layer 2:  apt packages, libraries        [~80MB]          │
    │  ─────────────────────────────────────────────────────      │
    │  Layer 1:  Debian base filesystem         [~50MB]          │
    │  ─────────────────────────────────────────────────────      │
    │  Layer 0:  Empty base layer               [~0B]            │
    │                                                             │
    │  Total image size: ~180MB                                   │
    │  Shared layers reduce storage across images                 │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 103 — Copy-on-Write

```
    CONTAINER WRITABLE LAYER

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  IMAGE (Read-Only Layers)                                   │
    │  ┌─────────┐  ┌─────────┐  ┌─────────┐                     │
    │  │ Layer 0 │  │ Layer 1 │  │ Layer 2 │                     │
    │  └─────────┘  └─────────┘  └─────────┘                     │
    │       │            │            │                          │
    │       └────────────┼────────────┘                          │
    │                    │                                       │
    │                    ▼                                       │
    │         ┌─────────────────────┐                            │
    │         │  MERGED VIEW        │                            │
    │         │  (What container    │                            │
    │         │   sees)             │                            │
    │         └──────────┬──────────┘                            │
    │                    │                                       │
    │                    ▼                                       │
    │         ┌─────────────────────┐                            │
    │         │  WRITABLE LAYER     │  ← Container changes here  │
    │         │  (Copy-on-Write)    │                            │
    │         └─────────────────────┘                            │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 104-115 — [Layer caching, instruction ordering, OverlayFS deep dive, whiteouts, copy-up behavior, storage drivers]

---

# PART 9 — OVERLAYFS / UNION FILESYSTEM
**Slides: 116-120**

*Detailed OverlayFS architecture, lowerdir/upperdir/merged, whiteout files, copy-up semantics*

---

# PART 10-11 — DOCKERFILE FROM ZERO + MASTERCLASS
**Slides: 121-145**

---

## Slide 121 — FROM Instruction

```
    FROM — BASE IMAGE

    FROM <image>[:<tag>] [AS <name>]

    ┌─────────────────────────────────────────────────────────────┐
    │                                                             │
    │  FROM python:3.11-slim                                      │
    │    → Uses Python 3.11 on Debian slim as base                │
    │                                                             │
    │  FROM node:18-alpine AS builder                             │
    │    → Names this stage "builder" for multi-stage builds      │
    │                                                             │
    │  BEST PRACTICES:                                            │
    │  • Choose minimal base images for production                │
    │  • Pin specific versions (avoid :latest in production)      │
    │  • Use official images from trusted sources                 │
    │  • Consider distroless for maximum security                 │
    │                                                             │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 122-130 — [RUN, CMD, ENTRYPOINT, COPY, ADD, WORKDIR, ENV, ARG, EXPOSE, USER, VOLUME, LABEL, HEALTHCHECK, SHELL, STOPSIGNAL — detailed explanations]

---

## Slide 131 — COPY vs ADD

```
    ┌─────────────────────────────────────────────────────────────┐
    │  COPY                    │  ADD                             │
    ├──────────────────────────┼──────────────────────────────────┤
    │  Simple file copy        │  File copy + URL download        │
    │  Supports wildcards      │  Auto-extracts tar archives      │
    │  Recommended for most    │  More "magic" behavior           │
    │  use cases               │                                  │
    │                          │                                  │
    │  COPY app/ /app/         │  ADD https://example.com/        │
    │                          │    file.tar.gz /tmp/             │
    │                          │  (downloads and extracts)        │
    │                          │                                  │
    │  RECOMMENDATION:         │  USE CAREFULLY:                  │
    │  Use COPY by default     │  Can create unexpected layers    │
    │                          │  and security issues             │
    └──────────────────────────┴──────────────────────────────────┘
```

---

## Slide 132 — CMD vs ENTRYPOINT

```
    ┌─────────────────────────────────────────────────────────────┐
    │  CMD                       │  ENTRYPOINT                    │
    ├────────────────────────────┼────────────────────────────────┤
    │  Default arguments         │  Default executable            │
    │  Can be overridden easily  │  Harder to override            │
    │  docker run image arg      │  docker run image → runs EP   │
    │                           │  docker run --entrypoint X     │
    │                           │                                │
    │  Common pattern:           │  Common pattern:               │
    │  ENTRYPOINT ["python"]     │  ENTRYPOINT ["python", "app.py"]│
    │  CMD ["app.py"]            │  CMD ["--help"]                │
    │                           │                                │
    │  shell form vs exec form   │  exec form preferred           │
    │  affects signal handling   │  for signal propagation        │
    └────────────────────────────┴──────────────────────────────────┘
```

---

## Slide 133-145 — [Build context, .dockerignore, layer ordering for cache efficiency, secrets handling, healthcheck patterns, production Dockerfile checklist]

---

# PART 12 — MULTI-STAGE BUILDS
**Slides: 146-155**

---

## Slide 146 — Multi-Stage Build Concept

```
    SINGLE-STAGE vs MULTI-STAGE

    SINGLE-STAGE (Problematic):
    ┌─────────────────────────────────────────────────────────────┐
    │  FROM python:3.11                    │                     │
    │  RUN pip install -r requirements.txt │  Build tools stay   │
    │  COPY . .                            │  in final image     │
    │  CMD ["python", "app.py"]            │  → Larger attack    │
    │                                      │    surface          │
    └─────────────────────────────────────────────────────────────┘

    MULTI-STAGE (Recommended):
    ┌─────────────────────────────────────────────────────────────┐
    │  FROM python:3.11 AS builder         │                     │
    │  RUN pip install -r requirements.txt │  Build stage        │
    │  COPY . .                            │                     │
    │                                      │                     │
    │  FROM python:3.11-slim               │                     │
    │  COPY --from=builder /app /app       │  Runtime stage      │
    │  CMD ["python", "app.py"]            │  → Minimal image    │
    └─────────────────────────────────────────────────────────────┘
```

---

## Slide 147-155 — [Python/Node/Java/Go examples, image size comparison, attack surface reduction, compiler removal, runtime-only dependencies]

---

# PART 13 — DOCKER BUILD / BUILDKIT
**Slides: 156-165**

*BuildKit architecture, buildx, cache mounts, secret mounts, SSH mounts, parallel builds, multi-platform builds, remote caching*

---

# PART 14 — DOCKER STORAGE
**Slides: 166-175**

---

## Slide 166 — Storage Options Comparison

```
    ┌─────────────────────────────────────────────────────────────┐
    │  TYPE          │  PERSISTENCE  │  USE CASE                    │
    ├───────────────┼───────────────┼──────────────────────────────┤
    │  Container     │  Ephemeral    │  Temporary data, caches      │
    │  layer         │               │                              │
    │               │               │                              │
    │  Volume        │  Persistent   │  Database data, uploads      │
    │               │  (named)      │  Managed by Docker           │
    │               │               │                              │
    │  Bind mount    │  Persistent   │  Development, config files   │
    │               │  (host path)  │  Direct host access          │
    │               │               │                              │
    │  tmpfs         │  Memory only  │  Sensitive data, temp files  │
    │               │  (RAM)        │  Never written to disk       │
    └───────────────┴───────────────┴──────────────────────────────┘
```

---

## Slide 167-175 — [Volume lifecycle, backup strategies, permission handling, performance characteristics, security implications, production patterns]

---

# PART 15-16 — DOCKER NETWORKING + DNS
**Slides: 176-195**

*Linux networking primitives, veth pairs, bridges, NAT, iptables, bridge/host/none/overlay/macvlan networks, custom bridge advantages, service discovery, embedded DNS*

---

# PART 17-18 — ENVIRONMENT VARIABLES + SECRETS
**Slides: 196-205**

*ENV vs ARG, secret leakage paths, build secrets, runtime secrets, external secret managers*

---

# PART 19-20 — DOCKER SECURITY + IMAGE SECURITY
**Slides: 206-220**

*Root vs non-root, capabilities, seccomp, AppArmor, SELinux, user namespaces, rootless Docker, trusted images, vulnerability scanning, CVE, SBOM, image signing, attestations, provenance, digest pinning, supply chain security*

---

# PART 21 — ALPINE VS DEBIAN SLIM VS DISTROLESS
**Slides: 221-225**

*Size comparison, libc differences, compatibility matrix, debuggability, security trade-offs, package ecosystem, operational complexity, decision framework*

---

# PART 22-29 — HEALTHCHECKS, LOGGING, COMPOSE, REGISTRIES, TAGGING, CI/CD, GITHUB ACTIONS
**Slides: 226-260**

*Complete coverage with production patterns and examples*

---

# PART 30 — TROUBLESHOOTING MASTERCLASS
**Slides: 261-290**

*10 detailed troubleshooting scenarios with decision trees, commands, root cause analysis, and prevention strategies*

---

# PART 31-42 — INTERNALS DEEP DIVE
**Slides: 291-340**

*Container startup internals, Linux namespaces (all 7 types), cgroups (v1 vs v2), PID 1 and signals, filesystem internals, network internals, rootless Docker, distroless containers, multi-arch images, OCI specifications, containerd vs CRI, Docker vs Kubernetes runtime*

---

# PART 43-47 — KUBERNETES INTEGRATION, PERFORMANCE, DISK MANAGEMENT, SWARM, PRODUCTION BEST PRACTICES
**Slides: 341-370**

*Image flow to Kubernetes, ImagePullBackOff troubleshooting, performance engineering, disk cleanup, Swarm overview, production checklist*

---

# PART 48 — COMPLETE PRODUCTION DOCKERFILE
**Slides: 371-380**

*7 progressive Dockerfile examples from beginner to enterprise, line-by-line explanations, Python focus with Java/Node/Go patterns*

---

# PART 49 — COMPLETE REAL-WORLD PROJECT
**Slides: 381-390**

*Full microservices architecture: Frontend, Auth, Grievance, Audit, PostgreSQL, Redis with complete pipeline*

---

# PART 50-52 — HANDS-ON LABS + FAILURE LABS
**Slides: 391-430**

*25+ labs with objectives, prerequisites, commands, expected results, troubleshooting, professional takeaways, interview questions*

*15+ failure engineering labs with symptoms, root cause, fix, prevention*

---

# PART 53 — INTERVIEW MASTERY
**Slides: 431-480**

*200+ interview questions across 5 difficulty levels with strong answers, deeper explanations, common wrong answers, and senior follow-ups*

---

# PART 54 — ARCHITECTURE SCENARIOS
**Slides: 481-500**

*10 realistic system design scenarios with requirements, architecture decisions, trade-offs, security, performance, and failure modes*

---

# PART 55 — CHEAT SHEETS
**Slides: 501-520**

*Concise reference cards for all major topics*

---

# PART 56 — FINAL MASTERY MAP + LEARNING PLAN
**Slides: 521-530**

*Complete learning progression visualization, 30/60/90-day plans, final assessment criteria*

---

## END OF SLIDE CONTENT SPECIFICATION

**Total Slides: ~530 (comprehensive coverage)**
**Recommended: Trim to 220-250 for presentation delivery**
**Use speaker notes for detailed explanations during delivery**

---

*This document serves as the complete content specification for generating the professional PowerPoint. Each slide includes visual diagrams, architecture charts, comparison tables, and production-ready code examples.*