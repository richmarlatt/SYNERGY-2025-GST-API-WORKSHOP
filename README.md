# 🚀 Building API Automations with GoSystem Tax Workshop
**Thomson Reuters SYNERGY 2025**

Welcome to the repository for the **Building API Automations with GoSystem Tax Workshop**! This repository contains all the materials, examples, and resources you'll need for our hands-on session.

## 📋 Table of Contents
- [Workshop Overview](#workshop-overview)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Workshop Agenda](#workshop-agenda)
- [Resources](#resources)
- [Support](#support)
- [Contributors](#contributors)

## 🎯 Workshop Overview

### Description
This interactive workshop is designed for participants who want to get started with API automations, specifically using GoSystem Tax. We'll begin with a step-by-step demonstration of building a basic automation in real-time. Then, participants will have the opportunity to work through several scenarios with guidance and live feedback. By the end of the session, you'll leave with practical experience and a set of blueprints to kickstart your own automation projects.

### Learning Objectives
By the end of this workshop, you will:
- ✅ Navigate the Developer Portal and obtain your API credentials
- ✅ Implement authentication flows for GoSystem Tax API
- ✅ Create and manage Locators to identify tax returns
- ✅ Retrieve field data using Get Fields, XRefs, and Get Forms operations
- ✅ Write data to GoSystem Tax using Save Fields and Grouped Fields
- ✅ Take home ready-to-use Postman collections and templates for your automation projects

### Duration
⏱️ 75 minutes

### Target Audience
This workshop is ideal for:
- Tax professionals looking to automate their workflows
- IT professionals supporting tax departments
- Anyone interested in learning API automation with GoSystem Tax

## 🛠 Prerequisites

### Required Software
- [ ] **Postman** (Latest version) - [Download here](https://www.postman.com/downloads/)
- [ ] **GoSystem Tax** access credentials
- [ ] Modern web browser (Chrome, Firefox, or Edge recommended)
- [ ] Text editor (VS Code, Cursor, or similar)

### Knowledge Requirements
Participants should have a working knowledge of APIs and an understanding of how they can be applied in a tax environment. 
Participants should have familiarity with GoSystem Tax and have the following information on hand:
- GoSystem Tax API Keys
- Access to GoSystem Tax

### Pre-Workshop Setup
1. Install Postman Desktop application
2. Create a free Postman account
3. Import the workshop collection (see [Getting Started](#getting-started))
4. Verify your GoSystem Tax credentials

## 🚦 Getting Started

### 1. Clone or Download this Repository
```bash
git clone https://github.com/[your-username]/synergy-2025-gst-api-workshop.git
```
Or download as ZIP from the green "Code" button above.

### 2. Access the Developer Portal
1. Navigate to the GoSystem Tax Developer Portal
2. Log in with your credentials
3. Locate your API Key (we'll walk through this in Module 1)
4. Keep the portal open for reference

### 3. Import Postman Collections
1. Open Postman Desktop Application
2. Click "Import" button
3. Navigate to `/collections/` folder
4. Import folders in order:
   - `01-api-setup/`
   - `02-authentication/`
   - `03-locators/`
   - `04-get-operations/`
   - `05-save-operations/`

### 4. Configure Environment Variables
1. In Postman, go to Environments tab
2. Import `environments/workshop-environment.json`
3. Add your API Key from the Dev Portal
4. Set your GoSystem Tax instance URL
5. Save the environment

### 5. Verify Your Setup
Run the "Test Connection" request in the "01-api-setup" collection to ensure everything is configured correctly.

## 📁 Repository Structure

```
synergy-2025-gst-api-workshop/
│
├── 📂 collections/
│   ├── 01-api-setup/
│   │   ├── dev-portal-api-key.json
│   │   └── environment-setup.json
│   ├── 02-authentication/
│   │   ├── oauth-flow.json
│   │   └── token-management.json
│   ├── 03-locators/
│   │   ├── create-locator.json
│   │   └── locator-examples.json
│   ├── 04-get-operations/
│   │   ├── get-fields.json
│   │   ├── xref-examples.json
│   │   ├── get-forms.json
│   │   └── get-all-fields.json
│   └── 05-save-operations/
│       ├── save-fields.json
│       ├── grouped-fields.json
│       └── batch-updates.json
│
├── 📂 environments/
│   ├── workshop-environment.json
│   ├── dev-portal-template.json
│   └── sample-data.json
│
├── 📂 documentation/
│   ├── api-reference.md
│   ├── field-mapping-guide.md
│   ├── xref-documentation.md
│   ├── troubleshooting.md
│   └── best-practices.md
│
├── 📂 exercises/
│   ├── exercise-1-setup-auth/
│   ├── exercise-2-create-locator/
│   ├── exercise-3-read-fields/
│   ├── exercise-4-write-fields/
│   └── solutions/
│
├── 📂 templates/
│   ├── locator-templates.json
│   ├── field-mapping-template.json
│   ├── xref-lookup-template.json
│   └── grouped-field-template.json
│
├── 📂 resources/
│   ├── slides/
│   ├── dev-portal-guide.pdf
│   ├── field-reference.pdf
│   └── useful-links.md
│
└── README.md
```

## 📚 Resources

### Documentation
- [GoSystem Tax API Documentation](link-to-docs)
- [Postman Learning Center](https://learning.postman.com/)
- [Workshop Slides](./resources/slides/)

### Support Channels
- 💬 Workshop Slack Channel: #synergy2025-gst-api
- 📧 Email Support: [workshop-support@example.com]
- 🐛 Issues: Use the [GitHub Issues](https://github.com/[your-username]/synergy-2025-gst-api-workshop/issues) tab

### Additional Learning
- [API Automation Best Practices](./documentation/best-practices.md)
- [Troubleshooting Guide](./documentation/troubleshooting.md)
- [Advanced Scenarios](./templates/)

## 🤝 Support

During the workshop:
- Raise your hand for in-person help
- Use the chat for quick questions
- Check the troubleshooting guide for common issues

After the workshop:
- Slack channel for community support
- Email for specific questions

## 👥 Contributors

### Workshop Hosts
- **Rich Marlatt** - Co-Host 
- **Jaques Joseph** - Co-Host

### Special Thanks
- Thomson Reuters SYNERGY 2025 Team
- GoSystem Tax API Team
- All workshop participants!

## 📄 License

This workshop material is provided for educational purposes. Please refer to Thomson Reuters' terms of service for API usage guidelines.

## 🎉 Ready to Get Started?

We're excited to have you join us for this hands-on workshop! If you have any questions before the session, please don't hesitate to reach out through the support channels listed above.

**See you at SYNERGY 2025!** 🚀

---

*Last Updated: [Current Date]*
*Version: 1.0.0*
