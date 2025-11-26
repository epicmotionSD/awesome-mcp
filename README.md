# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome MCP (Model Context Protocol) servers, tools, and resources for Claude Desktop and other AI assistants.

The Model Context Protocol (MCP) is an open protocol that standardizes how applications provide context to Large Language Models (LLMs). This list focuses on production-ready servers, tools, and resources.

## Contents

- [Official Resources](#official-resources)
- [Server Management](#server-management)
- [Development Tools](#development-tools)
- [Productivity](#productivity)
- [Data & Databases](#data--databases)
- [Cloud & Infrastructure](#cloud--infrastructure)
- [Communication](#communication)
- [AI & Machine Learning](#ai--machine-learning)
- [Security & Authentication](#security--authentication)
- [Finance & Business](#finance--business)
- [Content & Media](#content--media)
- [Utilities](#utilities)
- [Learning Resources](#learning-resources)
- [Communities](#communities)

## Official Resources

- [MCP Specification](https://spec.modelcontextprotocol.io/) - Official protocol specification
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - Official TypeScript/JavaScript SDK
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) - Official Python SDK
- [Claude Desktop](https://claude.ai/download) - Official Claude desktop app with MCP support

## Server Management

Tools for discovering, installing, and managing MCP servers.

- [OpenConductor](https://github.com/epicmotionSD/openconductor) - The npm for MCP servers. Install 220+ servers with one command, zero config.
  - `npm install -g @openconductor/cli`
  - Features: Stacks, registry, achievements, zero-config installation
- [MCP Get](https://github.com/michaellatman/mcp-get) - Package manager for MCP servers with Homebrew-like interface
- [MCP Manager](https://github.com/zueai/mcp-manager) - GUI application for managing Claude Desktop MCP servers
- [MCP CLI](https://github.com/wong2/mcp-cli) - Command-line interface for testing MCP servers

## Development Tools

### Version Control

- [GitHub MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - Official GitHub integration (repositories, issues, PRs, search)
- [GitLab MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - GitLab integration
- [Git MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Local Git repository operations

### IDEs & Editors

- [VSCode MCP](https://github.com/QuantGeekDev/code-mcp-server) - Visual Studio Code integration
- [Zed MCP](https://github.com/zed-industries/zed) - Zed editor with built-in MCP support

### Code Quality

- [Linear MCP](https://github.com/jerhadf/linear-mcp-server) - Linear issue tracking integration
- [Sentry MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - Error tracking and monitoring

### Documentation

- [Sequential Thinking MCP](https://github.com/sequentialread/mcp-server-sequential-thinking) - Enhanced reasoning and documentation

## Productivity

### Project Management

- [Jira MCP](https://github.com/QuantGeekDev/jira-mcp-server) - Atlassian Jira integration
- [Asana MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/asana) - Asana task management
- [Monday.com MCP](https://github.com/felores/monday-mcp) - Monday.com integration

### Note Taking & Knowledge

- [Obsidian MCP](https://github.com/MarkusPaulsen/obsidian-mcp) - Obsidian vault integration
- [Notion MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/notion) - Notion workspace integration
- [Apple Notes MCP](https://github.com/sirmews/apple-notes-mcp) - Apple Notes integration
- [Google Drive MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - Google Drive file access
- [Memory MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - Persistent memory across conversations

### Filesystem

- [Filesystem MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - Local file operations (read, write, search)
- [Directory Tree MCP](https://github.com/PrakharGupta36/directory-tree-mcp) - Visualize directory structures
- [File Insights MCP](https://github.com/PrakharGupta36/file-insights-mcp) - Analyze files and provide insights

### Time & Calendar

- [Google Calendar MCP](https://github.com/vrknetha/mcp-google-calendar) - Google Calendar integration
- [Time MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/time) - Current time and timezone utilities

## Data & Databases

### SQL Databases

- [PostgreSQL MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - PostgreSQL database operations
- [MySQL MCP](https://github.com/benborla/mcp-server-mysql) - MySQL database integration
- [SQLite MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - SQLite database access
- [Supabase MCP](https://github.com/QuantGeekDev/supabase-mcp-server) - Supabase platform integration
- [Neon MCP](https://github.com/neondatabase/mcp-server-neon) - Neon serverless Postgres

### NoSQL Databases

- [MongoDB MCP](https://github.com/kiliczsh/mcp-mongo-server) - MongoDB operations
- [Redis MCP](https://github.com/QuantGeekDev/redis-mcp-server) - Redis cache and data structures
- [Snowflake MCP](https://github.com/datawiz168/mcp-snowflake) - Snowflake data warehouse

### Data Analysis

- [Pandas MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/pandas) - Data analysis with pandas DataFrames
- [BigQuery MCP](https://github.com/LucasHild/mcp-server-bigquery) - Google BigQuery analytics

## Cloud & Infrastructure

### Cloud Platforms

- [AWS KB MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-kb-retrieval) - AWS Knowledge Base retrieval
- [Kubernetes MCP](https://github.com/Flux159/mcp-kubernetes) - Kubernetes cluster management
- [Docker MCP](https://github.com/QuantGeekDev/docker-mcp-server) - Docker container management
- [Railway MCP](https://github.com/railway-app/railway-mcp) - Railway platform deployment

### Monitoring & Analytics

- [Axiom MCP](https://github.com/axiomhq/mcp-server-axiom) - Axiom observability platform
- [Grafana MCP](https://github.com/grafana/mcp-grafana) - Grafana dashboards and metrics
- [Datadog MCP](https://github.com/DataDog/mcp-server-datadog) - Datadog monitoring

## Communication

- [Slack MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - Slack channel and message management
- [Discord MCP](https://github.com/QuantGeekDev/discord-mcp-server) - Discord server integration
- [Gmail MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/gmail) - Gmail email operations
- [Twilio MCP](https://github.com/QuantGeekDev/twilio-mcp-server) - SMS and voice communications

## AI & Machine Learning

- [Tavily MCP](https://github.com/RamXX/mcp-tavily) - AI-powered web search
- [LangChain MCP](https://github.com/rectalogic/langchain-mcp) - LangChain integration
- [OpenAI MCP](https://github.com/pierrebrunelle/mcp-server-openai) - OpenAI API integration
- [Anthropic MCP](https://github.com/kimtth/anthropic-mcp-server) - Anthropic API integration
- [Perplexity MCP](https://github.com/tanigami/mcp-server-perplexity) - Perplexity AI search

## Security & Authentication

- [1Password MCP](https://github.com/1Password/mcp-server-1password) - 1Password secrets management
- [Bitwarden MCP](https://github.com/QuantGeekDev/bitwarden-mcp-server) - Bitwarden password vault
- [OAuth2 MCP](https://github.com/QuantGeekDev/oauth2-mcp-server) - OAuth2 authentication flows

## Finance & Business

- [Stripe MCP](https://github.com/QuantGeekDev/stripe-mcp-server) - Stripe payment processing
- [QuickBooks MCP](https://github.com/QuantGeekDev/quickbooks-mcp-server) - QuickBooks accounting
- [E-commerce MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/ecommerce) - Shopping cart and product management

## Content & Media

### Web Scraping & Search

- [Brave Search MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - Brave search engine API
- [Puppeteer MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) - Web scraping and automation
- [Browserbase MCP](https://github.com/browserbase/mcp-server-browserbase) - Headless browser automation
- [Fetch MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Web content fetching

### Media Processing

- [YouTube Transcript MCP](https://github.com/kimtth/youtube-transcript-mcp-server) - Extract YouTube video transcripts
- [Cloudinary MCP](https://github.com/cloudinary-community/mcp-server-cloudinary) - Image and video management
- [ElevenLabs MCP](https://github.com/QuantGeekDev/elevenlabs-mcp-server) - Text-to-speech generation
- [Spotify MCP](https://github.com/QuantGeekDev/spotify-mcp-server) - Spotify music integration

### Social Media

- [Twitter MCP](https://github.com/QuantGeekDev/twitter-mcp-server) - Twitter/X API integration
- [LinkedIn MCP](https://github.com/QuantGeekDev/linkedin-mcp-server) - LinkedIn professional network
- [Instagram MCP](https://github.com/QuantGeekDev/instagram-mcp-server) - Instagram media and stories

## Utilities

### System Tools

- [Shell MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/shell) - Execute shell commands
- [Filesystem MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - File operations
- [Playwright MCP](https://github.com/executeautomation/mcp-playwright) - Browser automation testing

### Location & Maps

- [Google Maps MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) - Maps, geocoding, directions
- [Location MCP](https://github.com/QuantGeekDev/location-mcp-server) - Geolocation services

### Automation

- [Raycast MCP](https://github.com/raycast/mcp-simple-jetbrains) - Raycast launcher integration
- [Home Assistant MCP](https://github.com/tevonsb/homeassistant-mcp) - Smart home automation
- [IFTTT MCP](https://github.com/QuantGeekDev/ifttt-mcp-server) - IFTTT automation service

## Learning Resources

### Documentation

- [Official MCP Docs](https://modelcontextprotocol.io/docs) - Complete protocol documentation
- [OpenConductor Guides](https://openconductor.ai/docs) - Practical MCP guides and tutorials
- [MCP Quickstart](https://modelcontextprotocol.io/quickstart) - Get started in 5 minutes

### Tutorials

- [Building Your First MCP Server](https://modelcontextprotocol.io/tutorials/building-mcp-with-llm) - Step-by-step guide
- [MCP Server Examples](https://github.com/modelcontextprotocol/servers) - Official example servers
- [Creating Custom Tools](https://modelcontextprotocol.io/tutorials/custom-tools) - Advanced customization

### Videos

- [MCP Introduction by Anthropic](https://www.youtube.com/watch?v=example) - Official intro video
- [OpenConductor Demo](https://www.youtube.com/watch?v=example) - Installing your first servers

### Blog Posts

- [Introducing the Model Context Protocol](https://www.anthropic.com/news/model-context-protocol) - Anthropic's announcement
- [Why MCP Matters](https://openconductor.ai/blog/why-mcp-matters) - Understanding the ecosystem

## Communities

- [MCP Discord](https://discord.gg/mcp) - Official Discord community
- [r/ClaudeAI](https://reddit.com/r/ClaudeAI) - Reddit community
- [MCP GitHub Discussions](https://github.com/modelcontextprotocol/discussions) - Technical discussions
- [OpenConductor Discord](https://discord.gg/openconductor) - Server registry community

## Stacks (Pre-configured Server Collections)

Pre-built combinations of MCP servers for specific use cases:

- **Coder Stack** - GitHub + Git + Filesystem + PostgreSQL + Sequential Thinking
- **Writer Stack** - Obsidian + Google Drive + Brave Search + Memory + Time
- **DevOps Stack** - Kubernetes + Docker + AWS + Grafana + Sentry
- **Data Stack** - PostgreSQL + MongoDB + Pandas + BigQuery + Snowflake
- **Marketing Stack** - Twitter + LinkedIn + Instagram + Google Analytics + Stripe

Install stacks with [OpenConductor](https://openconductor.ai):
```bash
openconductor stack install coder
```

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
