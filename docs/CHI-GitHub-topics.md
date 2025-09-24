# 📌 CHI Repository Topics Guide

This document defines how to use **GitHub Topics** in the CHI-CityTech organization.  
Topics classify repositories by **role**, **association**, and **state** so they are searchable and consistently organized.

---

## 🔹 Why Topics?
- **Topics** describe a whole repository.  
- They show up under the repo description in GitHub.  
- Clicking a topic displays *all repos with the same topic*.  
- This is different from:
  - **Labels** (used for Issues and Pull Requests)  
  - **Tags** (used for releases/versions)  

---

## 🔹 CHI Topic Taxonomy

Every repository should use topics from three categories:

### 1. Role (choose one)
Defines what kind of repository this is.

| Topic             | Meaning                                                                 | Example Repo                        |
|-------------------|-------------------------------------------------------------------------|-------------------------------------|
| `meta-project`    | Framework-level CHI initiative (BBS, BSP, BRPS, Collaborative-AI, etc.) | `Balanced-Blended-Space-META`       |
| `student-research`| Individual student-led project                                          | `Hammer` (Reginald Fairley)         |
| `admin`           | Administrative, branding, templates, docs                              | `CHI-Admin`, `CHI-Branding`         |
| `infrastructure`  | Technical scaffolding (templates, actions, CI/CD, .github)             | `CHI-Research-Template`, `.github`  |

---

### 2. Association (choose one or more)
Links the repo to the meta-project(s) it supports.

| Topic                | Meta-Project / Cluster                             | Example Repo                        |
|----------------------|----------------------------------------------------|-------------------------------------|
| `bbs`                | Balanced Blended Space (framework)                 | `BBS-Personal-LLM`                  |
| `bsp`                | Blended Shadow Puppet                              | `Blended-Shadow-Puppet-Theatre`     |
| `brps`               | Blended Reality Performance System                 | `Unity-BSP`, `AI-with-QLab-using-OSC`|
| `collaborative-ai`   | Collaborative AI (AI as partner, OER, curriculum)  | `AI_Curriculum`                     |
| `unescoworld`        | UNESCO-aligned worldbuilding                       | `Documentary`, `Blended_Music`      |
| `built-environment`  | Built Environment meta-project (architecture, infra)| `AVMI-GVSC-SoundSystem`             |
| `quantum-music`      | Quantum Music and Sounding Futures                 | `QuantumMusic`                      |
| `anti-hate`          | Anti-Hate Initiative                               | `Anti-Hate`                         |

---

### 3. State (choose one)
Shows where the project is in its lifecycle.

| Topic       | Meaning                                       | Example Repo                        |
|-------------|-----------------------------------------------|-------------------------------------|
| `active`    | Currently in development                      | `AI_Media_Control`                  |
| `prototype` | Early-stage, exploratory build                | `Unity-BSP`                         |
| `archive`   | No longer maintained, for reference only      | Old student repos, retired forks     |
| `planned`   | Repo placeholder, not yet active              | `Blended_Music` (before work begins)|

---

## 🔹 Example Usage

**Repo:** `BBS-Personal-LLM`  
- Role: `student-research`  
- Association(s): `bbs`, `collaborative-ai`  
- State: `active`

**Repo:** `Blended-Shadow-Puppet-Theatre`  
- Role: `meta-project`  
- Association: `bsp`  
- State: `active`

**Repo:** `CHI-Admin`  
- Role: `admin`  
- Association: *(none — purely admin)*  
- State: `active`

---

## 🔹 How to Add Topics

1. Go to the repo main page.  
2. In the right sidebar, find the **About** box.  
3. Click the ✏️ **edit icon** (visible if you have write/admin rights).  
4. In the pop-up, type topics (separate with Enter).  
5. Click **Save changes**.  

---

## 🔹 Best Practices
- Use **lowercase, hyphenated** topics (`meta-project`, not `MetaProject`).  
- Every repo must have **exactly one Role**.  
- Add **one or more Associations** if relevant.  
- Pick **exactly one State**.  
- Keep topics consistent with this guide for easy filtering and automation.

---

✅ By tagging repos consistently, we create a **living map of CHI** — making it easier to connect projects, track activity, and integrate research across disciplines.
