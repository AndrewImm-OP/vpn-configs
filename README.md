# White-List bypass cfg's

[![Update VPN Configs](https://github.com/AndrewImm-OP/vpn-configs/actions/workflows/update-config.yml/badge.svg)](https://github.com/AndrewImm-OP/vpn-configs/actions/workflows/update-config.yml)

## Subscription URL

```
https://raw.githubusercontent.com/AndrewImm-OP/vpn-configs/main/live_merged.txt
```

### v2rayNG / NekoBox / Hiddify / Happ / etc.

Add as a **subscription** (not a single server). Set update interval to 60 minutes.

## Files

- `sources.txt` — list of upstream subscription URLs.
- `live_merged.txt` — auto-generated, verified subscription. **Do not edit by hand.**
- `.github/workflows/update-config.yml` — hourly cron that pulls the aggregator image and rebuilds `live_merged.txt`.

