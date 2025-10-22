# client

A simple MCP client that requests weather data.

The client uses the [stdio transport mechanism](https://modelcontextprotocol.io/docs/learn/architecture#transport-layer).

## Run it

To run it, you need an [API key](https://modelcontextprotocol.io/docs/develop/build-client#setting-up-your-api-key) from the Anthropic Console.

In a .env file, set the `MCP_API_KEY` environment variable:

```bash
# .env
# Replace "your_api_key_here" with your actual API key
MCP_API_KEY="your_api_key_here"
```

Then run the client with the server script as an argument:

```bash
uv sync
uv run --env-file .env client.py ../server/weather.py
```

## Reference
- <https://modelcontextprotocol.io/docs/develop/build-client>
