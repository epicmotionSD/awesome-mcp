# Contribution Guidelines

Thank you for considering contributing to Awesome MCP Servers! Please follow these guidelines to help maintain the quality of this list.

## Adding to this list

Please ensure your pull request adheres to the following guidelines:

### Quality Standards

- **Production Ready**: Only include MCP servers that are actively maintained and production-ready
- **Working Links**: All links must be functional and point to the correct resources
- **Clear Descriptions**: Each entry should have a concise, clear description
- **Proper Category**: Place items in the most appropriate category
- **No Duplicates**: Check that your addition isn't already listed

### MCP Server Requirements

For a server to be added, it must:

1. **Follow MCP Specification**: Implement the [Model Context Protocol](https://spec.modelcontextprotocol.io/) correctly
2. **Have Documentation**: Include a README with setup instructions
3. **Be Publicly Available**: Available via npm, GitHub, or other public package managers
4. **Be Maintained**: Active development or stable release within the last 6 months
5. **Add Value**: Provide unique functionality not covered by existing servers

### Submission Format

Use the following format for new entries:

```markdown
- [Server Name](https://github.com/username/repo) - Brief description of what it does
  - Installation: `npm install -g package-name` (if applicable)
  - Features: Key features (optional)
```

Example:
```markdown
- [GitHub MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - Official GitHub integration (repositories, issues, PRs, search)
```

### Pull Request Process

1. **Search existing issues and PRs** to avoid duplicates
2. **One item per PR** - Makes it easier to review
3. **Use meaningful titles** - "Add [Server Name]" or "Update [Server Name]"
4. **Test your links** - Ensure all URLs work
5. **Check spelling and grammar** - Use proper English
6. **Maintain alphabetical order** within categories (where applicable)

### Categories

Add new servers to existing categories when possible. If proposing a new category:

- Must have at least 3 quality entries
- Should not overlap with existing categories
- Must be a distinct use case

### What NOT to Include

- ❌ Servers in early alpha/beta without documentation
- ❌ Proprietary/closed-source tools (unless exceptional)
- ❌ Abandoned projects (>1 year without updates)
- ❌ Servers that don't follow MCP specification
- ❌ Promotional content or spam
- ❌ Servers with security vulnerabilities
- ❌ Duplicate functionality without significant improvement

## Updating Your Submission

If you need to update an existing entry:

1. Explain the reason for the change in your PR
2. Keep the same formatting style
3. Update the description if functionality changed
4. Add new features to existing items rather than creating duplicates

## Suggesting Resources

For learning resources, tutorials, or blog posts:

- Must be high quality and accurate
- Should be beginner-friendly OR clearly marked as advanced
- Video tutorials should be from reputable sources
- Blog posts should be from recognized authors or publications

## Reporting Issues

Found a broken link or outdated information?

1. Open an issue with the title "Broken Link: [Server Name]"
2. Include the section and item name
3. Suggest a fix if possible

## Questions?

Not sure if something belongs? Open an issue to discuss before submitting a PR.

## Code of Conduct

This project follows the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## License

By contributing, you agree that your contributions will be licensed under the CC0 License.

---

Thank you for helping make this the best resource for MCP servers! 🎉
