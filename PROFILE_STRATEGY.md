# GitHub Profile Architecture & Strategy Playbook
*Prepared for Vardaan Bazaz — Software Engineer & Applied Researcher*

---

## 1. Professional Bio Strategy

Your GitHub bio is the 160-character elevator pitch visible directly under your profile picture. It should be punchy, technically specific, and free of cliché greeting tags.

### Selected Bio Options
1. **Option A (Systems + AI Focus - Recommended)**:
   > Software Engineer & Applied ML Researcher. Building high-throughput systems, computer vision pipelines, and scalable SaaS backends.
2. **Option B (Minimalist / Architectural)**:
   > Designing deliberate engineering solutions at the intersection of systems, vision, and scale.
3. **Option C (Direct & Functional)**:
   > Software Engineer | Specializing in Applied ML, Computer Vision, and Full-Stack Systems.

---

## 2. Profile Presentation Strategy

To maintain the "engineering workshop" aesthetic, configure your GitHub profile with the following settings:
*   **Show Contribution Activity**: Keep the contribution graph visible. A consistent, quiet stream of commits shows active, deliberate build habits.
*   **Activity Overview**: Enable the activity overview chart (under profile settings) to give recruiters a quick visual breakdown of your commit, PR, and review distributions.
*   **Avoid Metric Badges**: Do not install external profile-readiness trackers, dynamic visitor counters, or skill badges. They dilute the minimalist aesthetic and feel amateur.

---

## 3. Pinned Repositories Strategy

Currently, you have one primary showcase. As you build, follow this pinning progression:

| Phase | Pinned Repositories | Strategy |
| :--- | :--- | :--- |
| **Current (1 Project)** | 1. `vardaanbazaz` (Profile Repo)<br>2. `Employee-Attrition-and-Churn-Analysis-main` | Pins are left-aligned. Pinned repos should strictly represent high-quality, production-ready work. |
| **Mid-Term (2-3 Projects)** | 1. `Employee-Attrition-and-Churn-Analysis-main`<br>2. `EduSync` (or next flagship)<br>3. `V-Surveillance` (or equivalent) | Unpin the profile repo once you have 3+ solid technical repos to show. Let your real repositories command the primary visual real estate. |
| **Target State (4-6 Projects)** | 6 carefully selected flagship projects spanning Systems, Applied ML, and Full-Stack SaaS. | Do not pin minor forks, coursework, or half-finished tutorials. Pin only repositories with rich READMEs and clean architectural structures. |

---

## 4. Public vs. Private Repository Rules

Organize your work clearly to signal high-end professional standards to recruiters and admissions committees.

### 🟢 Keep Public
*   **Flagship Projects & SaaS Builds**: Anything showcasing end-to-end design, modular testing, and clear architecture (e.g., `EduSync`).
*   **Applied Research Replications**: Well-documented PyTorch/TensorFlow implementations of academic papers with clean docstrings and model validation metrics.
*   **DevOps & Infrastructure Boilerplates**: Custom Docker Compose files, CI/CD runner workflows, or Terraform configurations. This shows production-level deployment capability.

### 🔴 Keep Private (or Archive)
*   **Academic / Coursework Assignments**: Simple homework tasks, basic coding exercise templates, and raw university labs. Having dozens of `CS101-lab3` repositories cluttering your public list screams "student".
*   **Incomplete Prototypes**: If you are hacking on a rough proof-of-concept, keep it private until it has a clean repository structure and a proper README.
*   **Forked Codebases**: If you fork an open-source project to submit a PR, delete the fork or make it private once the PR is merged (unless you actively maintain the fork).

---

## 5. Repository Naming Conventions

Consistency in naming signals discipline and systems thinking. Adopt a clean, standardized convention for all future projects.

### Convention: Kebab-Case
Use all-lowercase, hyphen-separated names. Avoid CamelCase or snake_case for repository names.

| Project Category | Recommended Repository Name | Description |
| :--- | :--- | :--- |
| **SaaS & Systems** | `edusync-platform` | Clean, lowercase kebab-case. |
| **Research / ML** | `v-surveillance-analysis` | Indicates research focus. |
| **BI / Analytics** | `employee-attrition-dashboard` | Refined from previous verbose name. |
| **Infrastructure** | `ml-pipeline-orchestrator` | Clear, functional naming. |
