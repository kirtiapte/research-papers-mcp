# Research Papers MCP server - credit - deeplearning.ai

MCP server uses arXiv, a free and open-access repository for scholarly articles, primarily in physics, mathematics, computer science, and related fields to find research papers based on the topic.  
It also provides following capabilities.
- search_papers - Search for papers on arXiv based on a topic
- extract_info - Get detailed information about a specific arXiv paper

## Configuration for Claude Desktop

You will need to supply a configuration for the server for your MCP Client. Here's what the configuration looks like for [claude_desktop_config.json](https://modelcontextprotocol.io/quickstart/user):

```
{
  "mcpServers": {
     "bitcoin-mcp-server": {
      "command": "java",
      "args": [
        "-jar",
        "/path/to/bitcoinn-mcp-server/target/bitcoinn-mcp-server-0.0.1-SNAPSHOT.jar"
      ]
    },
}
```







