# date-tool-mcp

**Name:** date-tool-mcp  
**Description:** A simple MCP server that returns the current date in YYYY-MM-DD format.  
**Author:** asdfffgggec  
**Repository:** https://github.com/asdfffgggec/date-tool-mcp  
**License:** MIT  
**Tags:** date-tool, kaneai  
**Transport:** stdio

## About

`date-tool-mcp` 是一个提供当前日期查询的 MCP Server，返回 `YYYY-MM-DD` 格式的日期。

## MCP Server config

```json
{
  "mcpServers": {
    "date-tool-mcp": {
      "command": "python",
      "args": ["mcp/server.py"]
    }
  }
}
```

## Installation

```bash
pip install -r mcp/requirements.txt
```

## Usage

```bash
python mcp/server.py
```

## Tools

### get_today

Returns the current date in `YYYY-MM-DD` format.
