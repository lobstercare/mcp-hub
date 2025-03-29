# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![Français](https://img.shields.io/badge/Français-Cliquez-blue)](README.fr.md)

[![GitHub stars](https://img.shields.io/github/stars/lobstercare/mcp-hub?style=social)](https://github.com/lobstercare/mcp-hub)

A curated list of awesome Model Context Protocol (MCP) servers.

* [What is MCP?](#what-is-mcp)
* [Clients](#clients)
* [Tutorials](#tutorials)
* [Server Implementations](#server-implementations)
* [Frameworks](#frameworks)
* [Utilities](#utilities)
* [Community](#community)

## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on production-ready and experimental MCP servers that extend AI capabilities through file access, database connections, API integrations, and other contextual services.

## Clients

* [Claude Desktop](https://claude.ai/desktop) - Official Claude desktop app with MCP support
* [Cursor](https://cursor.sh/) - AI-native code editor with MCP support
* [Cline](https://github.com/cfortuner/cline) - Terminal-based Claude client with MCP support
* [Windsurf](https://www.windsurf.ai/) - AI-native IDE with MCP support
* [LibreChat](https://www.librechat.ai/) - Open-source AI Web UI supporting multiple providers including MCP
* [mcphub.nvim](https://github.com/ravitemer/mcphub.nvim) - A Neovim plugin for MCP server interaction

## Tutorials

* [Model Context Protocol (MCP) Quickstart](https://modelcontextprotocol.io/docs/quickstart)
* [Building Your First MCP Server](https://modelcontextprotocol.io/docs/tutorials/first-server)
* [MCP Server Development Guide](https://modelcontextprotocol.io/docs/server-development)


## MCP Server Legend

### Implementation Status

| Symbol | Meaning |
|--------|---------|
| ⭐ | Official reference implementation by the MCP team |

### Programming Languages

| Symbol | Language |
|--------|----------|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> | Python |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> | TypeScript/JavaScript |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> | Go |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-plain.svg" width="16" height="16"/> | Rust |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="16" height="16"/> | C# |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="16" height="16"/> | Java |

### Deployment Model

| Symbol | Type | Description |
|--------|------|-------------|
| 🏠 | Local | Runs on user's machine, interacts with local software |
| ☁️ | Cloud | Connects to remote APIs and services |

### Platform Compatibility

| Symbol | Platform |
|--------|----------|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="16" height="16"/> | macOS |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="16" height="16"/> | Windows |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="16" height="16"/> | Linux |

### Server Categories

| Symbol | Category |
|--------|----------|
| 📂 | [File Systems](#file-systems) |
| 🗄️ | [Databases](#databases) |
| 🌐 | [Web & Search](#web--search) |
| 🔄 | [Version Control](#version-control) |
| 💬 | [Communication](#communication) |
| 🖥️ | [Developer Tools](#developer-tools) |
| 📊 | [Monitoring](#monitoring) |
| 🧠 | [Knowledge & Memory](#knowledge--memory) |
| 🗺️ | [Location Services](#location-services) |
| 🎮 | [Gaming](#gaming) |
| 💰 | [Finance](#finance) |
| 🛠️ | [Utilities](#utilities) |

## Server Implementations

* 📂 - [File Systems](#file-systems)
* 🗄️ - [Databases](#databases)
* 🌐 - [Web & Search](#web--search)
* 🔄 - [Version Control](#version-control)
* 💬 - [Communication](#communication)
* 🖥️ - [Developer Tools](#developer-tools)
* 📊 - [Monitoring](#monitoring)
* 🧠 - [Knowledge & Memory](#knowledge--memory)
* 🗺️ - [Location Services](#location-services)
* 🎮 - [Gaming](#gaming)
* 💰 - [Finance](#finance)
* 🛠️ - [Utilities](#utilities)

### 📂 <a name="file-systems"></a>File Systems

- [modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/server-filesystem) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Direct local file system access with configurable permissions
- [modelcontextprotocol/server-google-drive](https://github.com/modelcontextprotocol/server-google-drive) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Google Drive integration for listing, reading, and searching files
- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> 🏠 - Golang implementation for local file system access
- [hmk/box-mcp-server](https://github.com/hmk/box-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Box integration for listing, reading and searching files
- [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" width="16" height="16"/> - Fast Windows file search using Everything SDK
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Share code context with LLMs via MCP or clipboard
- [quarkiverse/quarkus-mcp-servers/filesystem](https://github.com/quarkiverse/quarkus-mcp-servers/filesystem) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="16" height="16"/> 🏠 - A filesystem allowing for browsing and editing files implemented in Java using Quarkus
- [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 ☁️ - Access any storage with Apache OpenDAL

### 🗄️ <a name="databases"></a>Databases

- [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/server-postgres) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - PostgreSQL database integration with schema inspection and query capabilities
- [modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/server-sqlite) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - SQLite database operations with built-in analysis features
- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="16" height="16"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - MCP service for Tablestore with vector search capabilities
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - MCP Server for Elasticsearch interaction
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Airtable database integration with schema inspection and CRUD capabilities
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - BigQuery database integration with schema inspection and query capabilities
- [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Second (But with JS) BigQuery database integration with schema inspection and query capabilities
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - TiDB database integration with schema inspection and query capabilities
- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - ClickHouse database integration with schema inspection and query capabilities
- [get-convex/convex-backend](https://stack.convex.dev/convex-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Convex database integration for table introspection and queries
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> 🏠 - Multi-database MCP server supporting MySQL & PostgreSQL
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Full featured MCP Server for MongoDB Databases
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - MongoDB integration for LLM database interaction
- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Model Context Protocol with Neo4j
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - MCP server for Nile's Postgres platform
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Snowflake integration with read/write operations
- [sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Pinecone integration with vector search capabilities
- [bytebase/dbhub](https://github.com/bytebase/dbhub) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Universal database MCP server supporting mainstream databases
- [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Google Sheets integration for spreadsheet management
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> - Connects AI tools directly to Airtable, allowing natural language queries, record creation, updates, deletions, and data migration.
- [tradercjz/dolphindb-mcp-server](https://github.com/tradercjz/dolphindb-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> -  DolphinDB database integration with schema inspection and query capabilities.
- [felores/airtable-mcp](https://github.com/felores/airtable-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Another Airtable MCP implementation
- [ravenwits/mcp-server-arangodb](https://github.com/ravenwits/mcp-server-arangodb) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - MCP Server for ArangoDB database
- [calvernaz/alphavantage](https://github.com/calvernaz/alphavantage) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - AlphaVantage stock market data API

### 🌐 <a name="web--search"></a>Web & Search

- [modelcontextprotocol/server-brave-search](https://github.com/modelcontextprotocol/server-brave-search) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Web search capabilities using Brave's Search API
- [modelcontextprotocol/server-fetch](https://github.com/modelcontextprotocol/server-fetch) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Efficient web content fetching and processing
- [modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/server-puppeteer) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Browser automation for web scraping and interaction
- [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Kagi search API integration
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Exa AI Search API integration
- [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Browser automation and webscraping with Playwright
- [pskill9/web-search](https://github.com/pskill9/web-search) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Free web searching using Google search results
- [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Web search using DuckDuckGo
- [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server/) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Advanced retrieval and Private Deep Research
- [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Web searches, URL scraping, and Markdown content return
- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Search Airbnb and get listing details
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Interact with any OpenAI SDK Compatible Chat Completions API

### 🔄 <a name="version-control"></a>Version Control

- [modelcontextprotocol/server-github](https://github.com/modelcontextprotocol/server-github) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Repository management, file operations, and GitHub API integration
- [modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/server-gitlab) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - GitLab API, enabling project management
- [modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/server-git) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Tools to read, search, and manipulate Git repositories

### 💬 <a name="communication"></a>Communication

- [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - WhatsApp integration for searching messages, contacts, and sending messages via WhatsApp Web API
- [modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/server-slack) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Slack workspace integration for channel management and messaging
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="16" height="16"/> - Safe access to iMessage database
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="16" height="16"/> - iMessage interface with sending/receiving capabilities
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Integration with Gmail and Google Calendar
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Interact with Twitter search and timeline
- [elie222/inbox-zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Email management with follow-up detection
- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Nostr protocol integration for posting notes

### 🖥️ <a name="developer-tools"></a>Developer Tools

- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Figma data access for design implementation
- [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Kubernetes management and operations
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> 🏠 - Docker container management and operations
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="16" height="16"/> - Xcode integration for project management
- [snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> 🏠 - Connect any HTTP/REST API using OpenAPI specs
- [jetbrains/mcpProxy](https://github.com/JetBrains/mcpProxy) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Connect to JetBrains IDE
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Line-oriented text file editor optimized for LLMs
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="16" height="16"/> - iTerm terminal access and command execution
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Run any command with secure execution
- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Automatic debugging via breakpoints
- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Interact with Atlassian Cloud products (Confluence and Jira)
- [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Perform operations on AWS resources
- [Vortiago/mcp-azure-devops](https://github.com/Vortiago/mcp-azure-devops) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Bridge to Azure DevOps services

### 📊 <a name="monitoring"></a>Monitoring

- [modelcontextprotocol/server-sentry](https://github.com/modelcontextprotocol/server-sentry) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Sentry.io integration for error tracking
- [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Raygun API integration for crash reporting
- [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Search dashboards and query datasources in Grafana
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Access to OpenTelemetry traces and metrics
- [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original-wordmark.svg" width="16" height="16"/> 🏠 - System monitoring for CPU, memory, disk, and network

### 🧠 <a name="knowledge--memory"></a>Knowledge & Memory

- [modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/server-memory) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Knowledge graph-based persistent memory system
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Enhanced graph-based memory for AI role-play
- [topoteretes/cognee](https://github.com/topoteretes/cognee/tree/dev/cognee-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Memory manager with various graph and vector stores
- [hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Documentation retrieval through vector search
- [kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Zotero Cloud integration for research collections
- [graphlit/graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Knowledge retrieval from Slack, Discord, and more

### 🗺️ <a name="location-services"></a>Location Services

- [modelcontextprotocol/server-google-maps](https://github.com/modelcontextprotocol/server-google-maps) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Google Maps integration for location services
- [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Access time in any timezone
- [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Geocoding server for nominatim, ArcGIS, Bing
- [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - IP geolocation and network information
- [jjsantos01/qgis_mcp](https://github.com/jjsantos01/qgis_mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - QGIS Desktop integration for geospatial analysis

### 🎮 <a name="gaming"></a>Gaming

- [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Godot game engine interaction
- [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp/) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Fantasy Premier League data and analysis
- [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="16" height="16"/> 🏠 - Unity3D Game Engine integration
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - VRChat API interaction for friends, worlds, and avatars

### 💰 <a name="finance"></a>Finance

- [base/base-mcp](https://github.com/base/base-mcp) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Base Network and Coinbase API integration
- [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Cryptocurrency market data via CoinCap
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Coinmarket API for crypto listings
- [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Alpha Vantage API for stock and crypto data
- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Blockchain services for 30+ EVM networks
- [bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp/) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Bankless Onchain API for smart contracts
- [GoPlausible/algorand-mcp](https://github.com/GoPlausible/algorand-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Comprehensive tools for interacting with Algorand blockchain

### 🛠️ <a name="utilities"></a>Utilities

- [githejie/mcp-server-calculator](https://github.com/githejie/mcp-server-calculator) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Calculator for precise numerical calculations
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Generate visualizations from data
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> ☁️ - Fetch YouTube subtitles
- [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - TikTok integration for post details and subtitles
- [vivekVells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Document format conversion using Pandoc
- [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Prevents cascading errors with "Vibe-check" agent
- [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Human-in-the-loop workflow for AI tools
- [gotoolkits/mcp-difyworkflow-server](https://github.com/gotoolkits/mcp-difyworkflow-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> ☁️ - Query and execute Dify workflows
- [Omar-v2/mcp-ical](https://github.com/Omar-v2/mcp-ical) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="16" height="16"/> - Interact with MacOS Calendar through natural language
- [scorzeth/anki-mcp-server](https://github.com/scorzeth/anki-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> 🏠 - Interact with Anki decks and cards
- [Simon-Kansara/ableton-live-mcp-server](https://github.com/Simon-Kansara/ableton-live-mcp-server) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> 🏠 - Control Ableton Live

## Frameworks

- [hannesrudolph/fastmcp](https://github.com/hannesrudolph/fastmcp) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> - Python framework for building MCP servers with FastAPI
- [microsoft/mcp.net](https://github.com/microsoft/mcp.net) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="16" height="16"/> - .NET library for building MCP servers
- [modelcontextprotocol/mcpjs](https://github.com/modelcontextprotocol/mcpjs) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> - JavaScript/TypeScript framework for building MCP servers
- [quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="16" height="16"/> - Java framework for building MCP servers with Quarkus
- [modelcontextprotocol/mcpy](https://github.com/modelcontextprotocol/mcpy) <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="16" height="16"/> - Python library for building MCP servers

## Utilities

- [modelcontextprotocol/mcp-cli](https://github.com/modelcontextprotocol/mcp-cli) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> - Command-line tool for testing MCP servers
- [modelcontextprotocol/mcp-proxy](https://github.com/modelcontextprotocol/mcp-proxy) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> - Proxy for debugging MCP server interactions
- [modelcontextprotocol/mcp-playground](https://github.com/modelcontextprotocol/mcp-playground) ⭐ <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="16" height="16"/> - Web-based playground for testing MCP servers

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to add or update MCP servers in this list.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
