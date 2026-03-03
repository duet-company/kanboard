# Duet Company - Kanboard

Task board and issue tracking for Duet Company development.

## 📋 Board Columns

### 🆕 To Do
- New tasks not started
- Backlog items
- Ideas for consideration

### 🚧 In Progress
- Tasks currently being worked on
- Active development
- In review

### ✅ Done
- Completed tasks
- Shipped features
- Resolved bugs

## 🏃 Sprint Management

### Current Sprint: Sprint 2 (Weeks 3-4)
**Goal:** Core Platform & AI Agent Development

#### Tasks (Week 3 - Core Platform Development)
- [ ] #9 Implement database models and migrations
- [ ] #10 Create API endpoints stubs for core functionality
- [ ] #11 Setup AI agent framework base
- [ ] #12 Connect to LLM providers (Claude, GPT-4, GLM-5)

#### Tasks (Week 4 - AI Agent Integration)
- [x] #13 Build Query Agent (NL → SQL) prototype
- [x] #14 Implement natural language interface
- [🔄] #15 Integrate agents with backend API (PR #4 - stubs created, awaiting merge)
- [ ] #16 Testing and validation

### Previous Sprint: Sprint 1 (Weeks 1-2)
**Goal:** Foundation and Infrastructure Setup

#### Tasks
- [ ] #1 Set up company registration
- [ ] #2 Acquire domain aidatalabs.ai
- [x] #3 Provision VPS infrastructure
- [x] #4 Setup Kubernetes cluster
- [x] #5 Deploy ClickHouse database
- [x] #6 Setup monitoring stack
- [x] #7 Create CI/CD pipelines
- [x] #8 Complete backend authentication

### Next Sprint: Sprint 3 (Weeks 5-6)
**Goal:** Platform Designer Agent & Query Agent Enhancements

## 🏷️ Labels

### Priority
- `critical` 🚨 - Must do immediately
- `high` 🔴 - Should do this sprint
- `medium` 🟡 - Nice to have
- `low` 🟢 - Future consideration

### Type
- `feature` ✨ - New functionality
- `bug` 🐛 - Fix broken functionality
- `refactor` ♻️ - Improve code structure
- `docs` 📝 - Documentation updates
- `design` 🎨 - Design changes
- `test` ✅ - Testing improvements

### Status
- `ready` ✅ - Ready to start
- `blocked` 🚫 - Waiting on something
- `in-progress` 🔄 - Currently working
- `in-review` 👀 - Awaiting review
- `done` ✅ - Completed

### Team
- `engineering` 👷 - Engineering work
- `product` 📊 - Product management
- `design` 🎨 - Design work
- `marketing` 📢 - Marketing tasks
- `ops` ⚙️ - Operations

## 📊 Metrics

- **Velocity:** Story points completed per sprint
- **Cycle Time:** Average time from start to completion
- **WIP Limits:** Limit work in progress (max 3 per column)
- **Throughput:** Number of tasks completed per sprint

## 🔗 Project Links

- **Company Monorepo:** https://github.com/duet-company/company
- **Vision:** https://github.com/duet-company/vision
- **Kanboard:** https://github.com/duet-company/kanboard

## 🚀 Workflow

### 1. Create Issue
- Use descriptive title
- Fill out issue template
- Add appropriate labels
- Set priority

### 2. Start Task
- Move from "To Do" to "In Progress"
- Assign to yourself
- Create branch from `main`

### 3. Work on Task
- Follow development process
- Commit frequently
- Update issue with progress

### 4. Submit PR
- Link PR to issue
- Request review
- Update labels to "in-review"

### 5. Complete
- Merge PR to main
- Close issue
- Move to "Done"

## 📋 Issue Templates

### 🐛 Bug Report

```markdown
**Description:**
Brief description of the bug

**Steps to Reproduce:**
1.
2.
3.

**Expected Behavior:**
What should happen

**Actual Behavior:**
What actually happens

**Environment:**
- Browser/OS:
- Version:

**Additional Context:**
Logs, screenshots, etc.
```

### ✨ Feature Request

```markdown
**Problem Statement:**
What problem are you trying to solve?

**Proposed Solution:**
How should it work?

**Alternatives Considered:**
What other options did you consider?

**Additional Context:**
Mockups, examples, etc.
```

### 📝 Task

```markdown
**Description:**
What needs to be done?

**Acceptance Criteria:**
- [ ] Criterion 1
- [ ] Criterion 2
- [ ] Criterion 3

**Dependencies:**
What needs to be done first?

**Timeline:**
When should this be completed?
```

## 📈 Progress Tracking

### Week 1 (Feb 17-23)
- Tasks started: 0/8
- Tasks completed: 4/8
- Blocked: 0

### Week 2 (Feb 24 - Mar 2) - INFRASTRUCTURE COMPLETE
- Tasks started: 0/8
- Tasks completed: 4/8
- Blocked: 0

### Week 3 (Mar 3-9) - SPRINT 2 STARTED
- Tasks started: 1/8 (Issue #15 - PR created)
- Tasks completed: 0/8
- Blocked: 0

---

**Maintainer:** Engineering Team
**Sprint Duration:** 2 weeks
**Next Planning:** Mar 17, 2026
