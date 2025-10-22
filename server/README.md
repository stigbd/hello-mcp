# server

A simple MCP server that provides weather data.

It uses the [stdio transport mechanism](https://modelcontextprotocol.io/docs/learn/architecture#transport-layer).

## Run it

```bash
uv sync
uv run weather.py
```

To stop the server, you need to kill it:

```bash
ps aux|grep "uv run weather.py # Get the process id (pid)
kill -s TERM <pid>
```

## Reference
- <https://modelcontextprotocol.io/docs/develop/build-server>
