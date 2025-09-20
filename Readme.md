# Java MCP server

A plain java MCP server using the MCP SDK that gives a list of presentations

- Transport provider is STDIO
- It has a "get_presentations" tool for seeing presentation details
## How To
Create a Jar file -
```bash
mvn clean package
```
Use MCP Inspector -
```bash
npx @modelcontextprotocol/inspector
```
This will install(node.js required) and launch the MCP inspector that you can use to test and debug an MCP Server.

Paste your jar file path in the "arguments" input in the inspector interface and connect.