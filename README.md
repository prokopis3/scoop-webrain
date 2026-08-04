# scoop-webrain

Scoop bucket for [webrain](https://github.com/prokopis3/webrain) — a portable,
LLM-driven browser-automation & web-scraping MCP server (one binary, three
engines: Chrome / Lightpanda / Obscura).

## Install

```powershell
scoop bucket add webrain https://github.com/prokopis3/scoop-webrain
scoop install webrain
```

Then start the MCP server:

```powershell
webrain mcp --http 9223
```

## Engine install

```powershell
webrain install            # Chrome for Testing
webrain install --engine obscura   # Obscura
webrain doctor             # diagnose the install
```
