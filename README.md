# Installation Steps

To install the `add_tool` MCP server, run the following command:
# replace uvx with fullpath in claude, if not found
```json
{
  "mcpServers": {
    "add_tool": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/kosminus/mcp-server-test.git",
        "mcp-server"
      ]
    }
  }
}
```

This will fetch and set up the `mcp-server` from the specified GitHub repository.