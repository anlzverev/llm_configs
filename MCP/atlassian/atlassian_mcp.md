# Atlassian MCP

[mcp-atlassian](https://github.com/sooperset/mcp-atlassian)
Provdies agent wiht integration to the Confluence and Jira. Uses token or Oauth for authorisation.

## Run
``` bash
docker run --rm -p 9000:9000 \
  --env-file ~/.claude/atlassian.env \
  ghcr.io/sooperset/mcp-atlassian:latest \
  --transport sse --port 9000 -vv
```
