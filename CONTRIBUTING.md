# Contributing to Awesome LangGraph Ecosystem

Contributions are welcome and encouraged! Whether you're fixing a typo, adding a new project, updating documentation, or suggesting improvements, your help is appreciated.

## How to Contribute

### Fork the repository
Click the "Fork" button in the top right corner of the GitHub page.

### Create a new branch
Create a new branch for your changes. This keeps your changes separate from the main project until they're ready to be merged. A good branch name describes the changes you're making, e.g., `add-new-project`, `fix-typo`, or `update-category`.

```bash
git checkout -b add-new-project
```

### Make your changes
Edit the `DRAFT-README.md` file with your additions or corrections. Please follow the existing format and style.

#### When adding a new project:
- **Project name**: Link to the repository using the format `[username/repository-name](https://github.com/username/repository-name)`
- **Description**: Provide a clear, concise description of the project's functionality and key features
- **GitHub Stars badge**: Include the GitHub stars badge using: `![GitHub stars](https://img.shields.io/github/stars/username/repository-name?style=social)`
- **Category**: Place the project in the appropriate category. If a new category is needed, please create one and maintain alphabetical order
- **Table format**: Follow the existing table structure with Project, Description, and GitHub Stars columns

#### Example entry:
```markdown
| [username/project-name](https://github.com/username/project-name) | Brief description of what the project does and its key features | ![GitHub stars](https://img.shields.io/github/stars/username/project-name?style=social) |
```

#### When adding official LangChain projects:
- Follow the dropdown format used in the "Official LangGraph Projects" section
- Include repository links, GitHub stars, and last commit badges
- Provide comprehensive descriptions with key features

### Commit your changes
Commit your changes with a clear and concise message explaining what you've done.

```bash
git commit -m "Add new XYZ project to Data Science category"
```

### Push your branch
Push your branch to your forked repository.

```bash
git push origin add-new-project
```

### Create a pull request
Go to the original repository and click the "New pull request" button. Select your forked repository and branch. Provide a clear title and description of your changes in the pull request.

### Review and merge
Your pull request will be reviewed by the maintainers. They may suggest changes or ask for clarification. Once the review is complete, your changes will be merged into the main project.

## Guidelines

### Keep it consistent
- Follow the existing format and style of the `DRAFT-README.md` file
- Use the same formatting, capitalization, and punctuation patterns
- Maintain the table structure for community projects
- Use dropdown format for official projects

### Categorization
- **Community Projects**: Place projects in the most appropriate category based on their primary use case
- **Official Projects**: Organize under the correct subsection (Specialized Agent Libraries, Apps & Agents, or Development Tools)
- If creating a new category, provide a clear description and maintain alphabetical order

### Accurate information
- Ensure all information is accurate and up-to-date
- Double-check repository links and verify they work
- Test that GitHub badges display correctly
- Verify project descriptions accurately reflect the project's capabilities

### Quality standards
- **Active projects**: Prefer projects that are actively maintained
- **LangChain ecosystem**: Ensure projects genuinely use LangChain, LangGraph, or related technologies
- **Clear descriptions**: Write concise and informative descriptions explaining what the project does and its key features
- **Avoid duplicates**: Check that the project isn't already listed

### Formatting requirements
- **One project per table row**: List each project on a separate line for better readability
- **Alphabetical order**: Maintain alphabetical order within each category (by repository name, not username)
- **Consistent linking**: Use the full GitHub URL format for all repository links
- **Badge consistency**: Use the social style for GitHub stars badges

### Description writing tips
- Start with what the project does (e.g., "AI-powered", "Multi-agent system for", "Automated tool for")
- Mention key technologies used (LangGraph, LangChain, specific LLM providers)
- Highlight unique features or capabilities
- Keep descriptions under 200 characters when possible
- Use active voice and clear, technical language

### Categories and scope
The repository covers projects in these main areas:
- **Core Frameworks**: LangChain, LangGraph, LangSmith, LangGraph Platform
- **Official Projects**: Projects maintained by the LangChain team
- **Community Projects**: Third-party projects organized by domain/use case
- **Integrations**: Third-party providers and tools that extend the ecosystem

## Types of Contributions

### Adding new projects
- Community-built applications using LangChain/LangGraph
- Official LangChain team projects and tools
- Integration packages and provider libraries

### Improving existing content
- Updating project descriptions for clarity
- Fixing broken links or badges
- Correcting categorization
- Adding missing projects

### Documentation improvements
- Enhancing category descriptions
- Improving the ecosystem overview
- Adding helpful tips or context
- Fixing typos and grammar

### Structural improvements
- Suggesting new categories
- Reorganizing content for better navigation
- Improving the table of contents
- Enhancing formatting

## Questions or Issues?

If you have questions about contributing or need help with the process, please:
- Open an issue on GitHub
- Check existing issues for similar questions
- Review the existing content for examples

Thank you for contributing to the Awesome LangGraph Ecosystem! 🦜🔗
