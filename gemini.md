---
# Gemini Context

This file provides context to Gemini about the project. By providing high-level information, you can help Gemini understand the project's goals, tech stack, and conventions, which will lead to more relevant and accurate responses.

## Project Overview

**Name:** Darvishvand.Ventures

**Description:** A Decentralized Autonomous Startup Accelerator.

**Goals:**
- Address limited transparency and stakeholder engagement in traditional startup accelerators.
- Propose an innovative DAO governance framework designed for early-stage ventures.
- Operate as a community-funded organization.

## Tech Stack

**Languages:**
- JavaScript, TypeScript

**Frameworks/Libraries:**
- Next.js

**Databases:**
- PostgreSQL

**Other Tools:**
- Cloudflare

## Project Conventions

**Coding Style:**
- Add the following copyright and license notice to the top of every source file:
  '''
  Darvishvand.Ventures Copyright (C) 2025 Mohammad Mohammadi Darvishvand

  This program is free software: you can redistribute it and/or modify
  it under the terms of the GNU General Public License as published by
  the Free Software Foundation, either version 3 of the License, or
  (at your option) any later version.

  This program is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  GNU General Public License for more details.

  You should have received a copy of the GNU General Public License
  along with this program.  If not, see <https://www.gnu.org/licenses/>.
  '''
- (e.g., "Follow PEP 8 for Python.")
- (e.g., "Use Prettier for code formatting.")

**Commit Messages:**
- (e.g., "Follow the Conventional Commits specification.")
- (e.g., "Start commit messages with a verb in the imperative mood.")

**Branching Strategy:**
- (e.g., "Use GitFlow (main, develop, feature branches).")
- (e.g., "Create a new branch for each feature or bug fix.")

**Logging:**
- Automatically log all significant actions, decisions, and executed steps in `ACTIONS.md`.
- Each log entry should be dated.

**Git Workflow:**
- After creating or modifying files, automatically stage the changes using `git add`.
- After staging, automatically commit the changes with a clear and descriptive commit message.

---

## How to Use This File

This file is read by Gemini at the beginning of a session to get context about your project. You can update it as your project evolves.

### Examples

**Example 1: Web Application**

```
---
# Gemini Context

## Project Overview

**Name:** My Awesome App

**Description:** A web application for managing tasks and projects.

**Goals:**
- Allow users to create, update, and delete tasks.
- Organize tasks into projects.
- Provide a dashboard for an overview of progress.

## Tech Stack

**Languages:**
- TypeScript
- JavaScript

**Frameworks/Libraries:**
- React
- Node.js
- Express

**Databases:**
- MongoDB

## Project Conventions

**Coding Style:**
- Use Prettier for code formatting.
- Follow the Airbnb JavaScript Style Guide.

**Commit Messages:**
- Follow the Conventional Commits specification.

**Branching Strategy:**
- Use GitFlow.
---
```

**Example 2: Python Library**

```
---
# Gemini Context

## Project Overview

**Name:** PyAnalyze

**Description:** A Python library for statistical analysis.

**Goals:**
- Provide a simple API for common statistical functions.
- High performance and easy to extend.

## Tech Stack

**Languages:**
- Python

**Frameworks/Libraries:**
- NumPy
- Pandas

## Project Conventions

**Coding Style:**
- Follow PEP 8.

**Commit Messages:**
- "feat: Add new feature"
- "fix: Fix a bug"

**Branching Strategy:**
- Create a branch for each new feature.
---
```
