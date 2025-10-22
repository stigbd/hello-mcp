# hello-mcp

A simple example demonstrating how to use the MCP (Model Context Protocol).

## Architecture

This example consists of a server and a client communicating using the MCP protocol over the stdio transport mechanism.

In general the MCP architecture consists of the following key participants:
- **MCP Host**: The AI application that coordinates and manages one or multiple MCP clients
- **MCP Client**: A component that maintains a connection to an MCP server and obtains context from an MCP server for the MCP host to use
- **MCP Server**: A program that provides context to MCP clients

**Context**: In this example, the context is weather data and alerts provided by the MCP server to the MCP client.


## Reference
- <https://modelcontextprotocol.io/>
