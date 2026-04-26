- chat
```sh
- 너가 모르거나 학습되지 않은 기술이나 라이브러리, 프로젝트의 경우 아래의 순서대로 기술 검증해
 ㄴ context7 MCP 사용
 ㄴ SearchWeb 사용
 ㄴ FetchURL 사용
 ㄴ Playwright MCP 사용
```

- mcp.json
```sh
{
  "mcpServers": {
    "context7": {
      "command": "npx",
      "args": [
        "-y",
        "@upstash/context7-mcp@latest"
      ]
    },
    "sequential-thinking": {
      "command": "npx",
      "args": [
        "-y",
        "@modelcontextprotocol/server-sequential-thinking"
      ]
    },
    "playwright": {
      "command": "npx",
      "args": [
        "-y",
        "@executeautomation/playwright-mcp-server"
      ]
    }
  }
}
```
