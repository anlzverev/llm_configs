# LLM configs
Repository to keep up to date configs for various llm tools.

## MCPs
List of MCPs used in different configs

### [context7](https://github.com/upstash/context7)
MCP extracting up to date documentation for libraries.
No additional configuration required.

### [atlassian](MCP/atlassian/atlassian_mcp.md)
Confluence and Jira integration MCP. Requires docker setup to work.

### [github](https://github.com/github/github-mcp-server)
Github integration, using GH. [Requires setup](https://github.com/github/github-mcp-server/tree/main/docs/installation-guides).

### [sequential-thinking](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking)
Analytical thikning for LLM.

## Claude code
Terminal tool with impressive capabilities.

### Config
Copy `settings.local.json` and `.mcp.json` from the profile that you need to the `.claude/` folder of you project. Keep in mind that there might be additional configuration necessary for each of them to work.
Read more in [docs](https://docs.anthropic.com/en/docs/claude-code/settings).

#### Developer
1. Copy config
2. [Set up the Atlassian MCP](https://github.com/sooperset/mcp-atlassian?tab=readme-ov-file#-http-transport-configuration)
3. ???
4. PROFIT
