# Assignment 3 — Building Your Command Center

Part of the DevOps Micro Internship (DMI) Cohort 3 with Agentic AI

---

## Purpose

In this assignment, you will build a local Claude Skills system by creating the `.claude/skills/` folder structure, adding predefined skill files, and executing a real agentic command (`/scaffold-terraform`) to generate infrastructure code. You will also observe how skills enforce tool restrictions and enable controlled automation.

---

# Task 1 — Create the Skill Folder Structure

## Goal

Create the required `.claude/skills/` directory structure for all skills.

### Evidence

#### Screenshot 1 — Skills folder structure in VS Code

![Skills folder structure](../week-02-agentic-ai/screenshots/AI3_1.png)

---

# Task 2 — Add the Skill Files

## Goal

Place all required skill files into their correct directories and verify their configuration.

### Evidence

#### Screenshot 2 — scaffold-terraform skill folder contents

![scaffold-terraform folder contents](../week-02-agentic-ai/screenshots/AI3_2.png)

---

#### Screenshot 3 — tf-plan/SKILL.md showing allowed-tools restrictions

![tf-plan SKILL.md frontmatter](../week-02-agentic-ai/screenshots/AI3_3.png)

---

# Task 3 — Run /scaffold-terraform

## Goal

Execute the `/scaffold-terraform` skill to generate a full Terraform infrastructure setup.

### Evidence

#### Screenshot 4 — Claude scaffold execution result

![Scaffold execution result part 1](../week-02-agentic-ai/screenshots/AI3_4a.png)

![Scaffold execution result part 2](../week-02-agentic-ai/screenshots/AI3_4b.png)

![Scaffold execution result part 3](../week-02-agentic-ai/screenshots/AI3_4c.png)

---

#### Screenshot 5 — Generated terraform/ folder with all files

![Generated terraform folder](../week-02-agentic-ai/screenshots/AI3_5.png)

---

# Task 4 — Run terraform init and /tf-plan

## Goal

Initialize Terraform and execute the `/tf-plan` skill to observe plan execution and output analysis.

### Evidence

#### Screenshot 6 — /tf-plan execution and Claude analysis output

![tf-plan execution and analysis part 1](../week-02-agentic-ai/screenshots/AI3_6a.png)

![tf-plan execution and analysis part 2](../week-02-agentic-ai/screenshots/AI3_6b.png)

---

# Submission Instructions

- Ensure `.claude/skills/` folder and all skill files are committed to your GitHub repository
- Run all commands successfully and capture required screenshots
- Push final changes to your forked repository

---

## GitHub Repository URL

https://github.com/agbaike/Ultimate-Agentic-DevOps-with-Claude-Code

`__________________________`

---

# Completion Checklist

- [x] `.claude/skills/` folder created with all 4 skill folders
- [x] All skill files placed correctly
- [x] `tf-plan/SKILL.md` shows correct `allowed-tools` restrictions
- [x] `/scaffold-terraform` executed successfully
- [x] Terraform files generated inside `terraform/` folder
- [x] `terraform init` executed successfully
- [x] `/tf-plan` executed and output analyzed by Claude
- [x] All required screenshots added
- [x] GitHub repository URL included

---

## 📌 About DMI & CloudAdvisory

DevOps Micro Internship (DMI) is a project-based DevOps program run by Pravin Mishra (The CloudAdvisory) focused on real-world execution, systems thinking, and career readiness.

It helps learners build strong DevOps foundations with hands-on experience.

---

## 📌 Resources

- 🌐 DMI Official Website: https://pravinmishra.com/dmi
- 🎓 DevOps for Beginners (Udemy): https://www.udemy.com/course/devops-for-beginners-docker-k8s-cloud-cicd-4-projects/
- 🎓 Agentic AI DevOps with Claude Code: https://www.udemy.com/course/ultimate-agentic-ai-devops-with-claude-code/
- 🎓 DevOps with Claude Code: Terraform, EKS, ArgoCD & Helm: https://www.udemy.com/course/devops-with-claude-code-terraform-eks-argocd-helm/
- ▶️ YouTube Playlist: https://www.youtube.com/playlist?list=PLFeSNDtI4Cho
- 🔗 Pravin Mishra (LinkedIn): https://www.linkedin.com/in/pravin-mishra-aws-trainer/
- 🏢 CloudAdvisory (LinkedIn): https://www.linkedin.com/company/thecloudadvisory/

---

_This submission is part of DevOps Micro Internship (DMI) Cohort 3 — Agentic AI Track._
