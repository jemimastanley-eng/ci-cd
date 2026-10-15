## GitHub Actions (GHA) Syntax Cheat Sheet

| Syntax | Purpose |
| --- | --- |
| `on:` | Trigger events |
| `jobs:` | Define jobs |
| `runs-on:` | Choose a runner |
| `steps:` | List operations |
| `uses:` | Invoke an action |
| `with:` | Supply action inputs |
| `run:` | Execute shell commands |
| `needs:` | Set job dependencies |
| `if:` | Conditional execution |
| `env:` | Set environment variables |
| `${{ ... }}` | Evaluate expressions |
| `secrets.NAME` | Reference a secret |
| `strategy.matrix` | Run combinations of configurations |
| `permissions:` | Set `GITHUB_TOKEN` permissions |
| `workflow_dispatch:` | Enable manual triggering |
| `actions/upload-artifact@v4` | Preserve and share workflow outputs |