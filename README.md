# date-tool-mcp

## 基本信息

- 名称：date-tool-mcp
- 描述：提供当前日期查询的 MCP Server，返回 `YYYY-MM-DD` 格式的日期。
- 作者：asdfffgggec
- 仓库：https://github.com/asdfffgggec/date-tool-mcp
- 许可证：MIT
- 标签：date-tool, kaneai
- 传输方式：stdio

## 功能

- `get_today`：返回当前年月日，格式为 `YYYY-MM-DD`。

## 服务配置

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

## 本地运行

```bash
pip install -r mcp/requirements.txt
python mcp/server.py
```

## Tools

### get_today

返回当前年月日，格式 `YYYY-MM-DD`。
