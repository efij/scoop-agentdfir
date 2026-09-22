# scoop-agentdfir

Scoop bucket for [AgentDFIR](https://github.com/efij/AgentDFIR), open-source
digital forensics and incident response for AI coding agents. Windows x64 and ARM64.

```powershell
scoop bucket add agentdfir https://github.com/efij/scoop-agentdfir
scoop install agentdfir
agentdfir run
```

`scoop update agentdfir` follows new releases.

The manifest is rendered and pushed by the AgentDFIR release workflow
(`scripts/update-scoop.sh` in the main repository) from the release's
`SHA256SUMS.txt`. Do not edit `bucket/agentdfir.json` by hand.
