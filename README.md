# SWE 441 Project

A Software Engineering course project demonstrating Jira workflow management and version control integration for a heart disease prediction application.

**Project Lead**: falaqalwardy
**Course**: SWE_441
**GitHub Repository**: https://github.com/falaqalwardy/SWE_441
**Jira Workspace**: https://falaqalwardy-swe-441.atlassian.net/

---

## 🎯 Project Overview

This project demonstrates professional software maintenance practices by:

1. Implementing custom Jira workflows for issue tracking
2. Integrating version control with automated issue linking
3. Establishing metrics and reporting systems
4. Creating knowledge base documentation in Confluence

The application being maintained is a machine learning model for heart disease prediction.

---

## 🛠️ Software Maintenance Components

### Jira Workflow Management

- **Custom Issue Types**: Bug Report, Feature Request, Model Improvement, Documentation Update
- **Workflow Statuses**: Each type has 4+ statuses (To-Do, In Progress, In Review, Done)
- **Automated Transitions**: Defined workflow rules and validations

### Version Control Integration

- **Jira ↔ GitHub Integration**: Automatic commit linking
- **Branch Naming**: `SWE-XXX-feature-name` format
- **Commit Format**: `SWE-XXX: Description` for automatic tracking

### Metrics & Reporting

Key metrics tracked:
- Issue resolution time
- Sprint velocity
- Defect density
- Code quality improvements

### Knowledge Base (Confluence)

Documentation includes:
- Meeting notes
- Architecture decisions
- Troubleshooting guides
- Generated reports

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/falaqalwardy/SWE_441.git
cd SWE_441
```

### Development Workflow

1. **Create Jira Issue** - Select issue type and fill details
2. **Create Branch** - `git checkout -b SWE-XXX-feature-name`
3. **Make Changes** - Modify code as needed
4. **Commit** - `git commit -m "SWE-XXX: Description"`
5. **Push** - `git push origin SWE-XXX-feature-name`
6. **Update Status** - Move issue through workflow in Jira

---

## 📁 Project Structure

```
SWE_441/
├── heart-disease-prediction.ipynb  # ML model notebook
├── heart.csv                        # Dataset
├── README.md                        # This file
├── PROGRESS.md                      # Completion tracker
├── JIRA_SETUP_GUIDE.md             # Jira configuration
└── project.md                       # Requirements
```

---

## 📊 Progress Tracking

Check [PROGRESS.md](PROGRESS.md) for current status, next tasks, and submission checklist.

---

## 🎓 Course Requirements

✅ Custom Jira workflow with 3+ issue types
✅ Version control integration
✅ Metrics and reporting
✅ Confluence knowledge base

---

## 📧 Contact

**Project Lead**: falaqalwardy
**GitHub**: [@falaqalwardy](https://github.com/falaqalwardy)

---

## 📄 License

This project is for academic purposes as part of the SWE_441 course.
