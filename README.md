# mcp-server

```

uv venv
source .venv/Scripts/activate
  503  clear
  507  uv add "mcp[cli]"
  508  uv run mcp install main.py






===============================================

-- to add github mcp server in our env :
https://www.mcpappstore.com/apps/github-mcp-server

update the json config file :





{
  "mcpServers": {
    "LeaveManager": {
      "command": "C:\\Users\\HP\\.local\\bin\\uv.EXE",
      "args": [
        "run",
        "--with",
        "mcp[cli]",
        "mcp",
        "run",
        "C:\\Users\\HP\\Downloads\\mcp\\my-mcp\\main.py"
      ]
    },
    "github": {
      "command": "npx",
      "args": [
        "-y",
        "@modelcontextprotocol/server-github"
      ],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": " "
      }
    }
  }
}



```



```

NOTE : REMOVE CLAUDE FROM TASK MANAGER AND THAN START AGAIN TO SEE UPDATED CHANGES

```
