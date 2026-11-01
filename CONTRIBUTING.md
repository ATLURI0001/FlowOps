# Contributing to FlowOps

Thank you for your interest in contributing to **FlowOps**!

FlowOps is a collection of 280+ n8n automation workflow templates covering AI agents, DevOps, data processing, messaging, and third-party integrations.

Contributions are welcome to improve existing workflows, expand integrations, and maintain the collection.

## How to Contribute a Template

1. **Fork** the [FlowOps repository](https://github.com/ATLURI0001/FlowOps).
2. **Add your JSON template** to the appropriate category folder, such as `Gmail_and_Email_Automation/`, `Telegram/`, or `OpenAI_and_LLMs/`.
3. **Update `README.md`** by adding a new row to the appropriate category table using the existing four-column format:

   | Title | Description | Department | Link |
   |---|---|---|---|
   | Template Title | Brief description of the workflow | Engineering | [Link to Template](Category_Folder/Template%20Name.json) |

4. **Submit a Pull Request** with a clear title and description of the template and any required configuration.

## Template Requirements

- Must be a valid n8n workflow JSON file exported from n8n.
- Must include a meaningful name and description.
- Should be tested and functional on a recent version of n8n.
- Must not contain credentials, API keys, tokens, passwords, or sensitive information.
- File names should match their corresponding template titles.
- External services and required configuration should be documented.
- Existing template authors and applicable license notices must be credited.

## Suggesting a New Category

If your template does not fit into an existing category:

1. Open an [Issue](https://github.com/ATLURI0001/FlowOps/issues) with the title `New Category: Category Name`.
2. Explain the types of automation workflows the category will contain.
3. Include at least one relevant workflow template.

## Reporting Issues

- Report broken workflows using GitHub Issues.
- Include the workflow name, affected nodes, and relevant error messages.
- Describe the expected and actual behavior.
- Never include real API keys or credentials in issue reports.
- Report exposed credentials
