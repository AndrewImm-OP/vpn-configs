# vpn-configs

[![Update VPN Configs](https://github.com/AndrewImm-OP/vpn-configs/actions/workflows/update-config.yml/badge.svg)](https://github.com/AndrewImm-OP/vpn-configs/actions/workflows/update-config.yml)

Public showcase repo: serves a single, hourly-refreshed VPN subscription file.

The aggregation logic itself is closed-source and runs as a private Docker image — only the **result** lives here.

## Subscription URL

```
https://raw.githubusercontent.com/AndrewImm-OP/vpn-configs/main/live_merged.txt
```

### v2rayNG / NekoBox / Hiddify

Add as a **subscription** (not a single server). Set update interval to 60 minutes.

## Files

- `sources.txt` — list of upstream subscription URLs.
- `live_merged.txt` — auto-generated, verified subscription. **Do not edit by hand.**
- `.github/workflows/update-config.yml` — hourly cron that pulls the aggregator image and rebuilds `live_merged.txt`.

