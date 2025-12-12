# Devu — The Open-Source Developer University

**No tutorials. No shortcuts. Build real projects, submit your work, and get peer-reviewed.**

---

## About Devu

Devu is an open-source, project-based learning platform designed to teach developers **real-world skills**. Unlike traditional tutorials or CS degrees that focus on theory, Devu focuses on **hands-on projects**, **peer feedback**, and **practical engineering experience**.  

Our mission is to build **real developers, not vibe coders**.

---

## How Devu Works

1. **Tracks**  
   Devu organizes learning into tracks (e.g., Backend Engineering, Frontend Engineering, Low-Level Systems). Each track contains multiple real-world projects.

2. **Projects**  
   Every project comes with:  
   - `README.md` — the assignment and goals  
   - `starter/` — starter code  
   - `tests/` — automated tests for validation  
   - `solutions/` — reference solution (optional)  
   - `devu.json` — metadata for the CLI

3. **CLI: Devu Student Portal**  
   The Devu CLI allows students to:  
   - Copy starter code into their workspace  
   - Run tests to validate their work  
   - Submit their project via a GitHub Pull Request  

4. **Peer Review**  
   Submissions are visible as PRs in the Devu repository. Contributors review and leave feedback, helping everyone improve.

---

## Getting Started

Follow these steps to start using Devu:

### 1. Clone the repository
```
git clone https://github.com/DEVU-ORG/DEVU.git
cd DEVU
```

### 2. Explore tracks and projects
All learning paths are organized under the `tracks/` directory. Each track contains one or more projects. For example:

```
tracks/
  backend-engineering/
    build-http-server/
    database-api/
  frontend-engineering/
    react-dashboard/
    ui-components/
```

Navigate the directories to see project assignments, starter code, tests, and solutions.

### 3. Run the CLI
The Devu CLI is your student portal for interacting with projects. For now, it will support the following commands:

```
# Initialize a project in your local workspace
devu init <project-name>

# Run tests for the current project
devu test

# Submit the project via a pull request
devu submit
```

Further installation and usage instructions will be added as the CLI develops.

