# N8N Workflow Collection

This repository contains a collection of automated workflows created using n8n, a powerful workflow automation tool. Each workflow is stored as a JSON file and can be imported into your n8n instance.

## 🚀 Current Workflows

### AI Voice Agent (`ai-voice-agent.json`)
An intelligent voice agent workflow that:
- Handles webhook requests
- Integrates with OpenAI's GPT models
- Uses vector databases (Pinecone) for information retrieval
- Manages restaurant data and menu information
- Provides AI-powered responses through a webhook

## 📋 Repository Structure
```
.
├── README.md
├── ai-voice-agent.json
└── ... (more workflows to be added)
```

## 🔧 How to Use

### Prerequisites
- n8n instance (self-hosted or cloud)
- Required API credentials:
  - OpenAI API
  - Google Sheets API
  - Pinecone API

### Importing Workflows
1. Download the desired workflow JSON file
2. In your n8n instance, go to Workflows
3. Click on "Import from File"
4. Select the downloaded JSON file
5. Configure the required credentials
6. Activate the workflow

## 🔐 Credentials Required
Before using any workflow, ensure you have set up the necessary credentials in your n8n instance:

- OpenAI API credentials
- Google Sheets OAuth2 credentials
- Pinecone API credentials
- Any other workflow-specific credentials

## 📝 Workflow Documentation

Each workflow in this repository includes:
- A descriptive name
- JSON configuration file
- Required credentials
- Node configurations
- Connection details

## 🤝 Contributing

Feel free to contribute by:
1. Forking the repository
2. Creating a new branch for your workflow
3. Adding your workflow JSON file
4. Creating a pull request
5. Adding documentation for your workflow in this README

## 📜 Naming Convention

When adding new workflows, please follow this naming convention:
- Use lowercase letters
- Use hyphens to separate words
- Include a brief description of the workflow's purpose
- Example: `email-automation-workflow.json`

## ⚠️ Important Notes

- Always review and test workflows in a development environment before deploying to production
- Keep your API credentials secure and never commit them to the repository
- Regularly update your n8n instance to ensure compatibility
- Back up your workflows before making significant changes

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Note**: This repository is actively maintained and new workflows will be added regularly. Check back often for updates and new automation solutions. 