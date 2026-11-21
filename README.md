# muse-usage-widget

Muse subscription usage data for a widget, auto-updated every 30 minutes.

## Data

[`data/muse_usage.json`](data/muse_usage.json) — refreshed every 30 minutes by a scheduled job:

```json
{
  "updated_at": "2026-11-21T10:08:00+08:00",
  "plan": "Free",
  "percent_used": 18,
  "resets_at": "2026-11-27T20:42:00+08:00",
  "additional_tokens": { "percent_used": 3, "left_label": "5.8B tokens left" }
}
```

## Fields

- `plan` — subscription plan name
- `percent_used` — percent of the weekly allowance used
- `resets_at` — when the weekly allowance resets
- `additional_tokens` — extra (permanent) allowance: percent used and remaining amount as text
- `updated_at` — when this file was last updated

## Raw link

https://raw.githubusercontent.com/wutongshu123456/muse-usage-widget/main/data/muse_usage.json
