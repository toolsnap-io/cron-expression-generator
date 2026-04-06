# Cron Expression Generator

A free online tool to build, test, and explain cron expressions visually.

## Features

- Visual cron expression builder with dropdowns
- Human-readable explanation of any cron expression
- Calculate next execution times
- Support for standard cron (5 fields) and extended cron (6-7 fields)
- Common preset expressions (every minute, hourly, daily, weekly, etc.)
- Syntax validation with error highlighting

## How to Use

1. Use the dropdowns to set minute, hour, day, month, and weekday
2. Or type a cron expression directly (e.g., `0 9 * * 1-5`)
3. See the human-readable description and next run times
4. Copy the cron expression to your configuration

## Common Examples

| Expression | Description |
|---|---|
| `* * * * *` | Every minute |
| `0 * * * *` | Every hour |
| `0 9 * * 1-5` | Weekdays at 9 AM |
| `0 0 1 * *` | First day of month |
| `0 0 * * 0` | Every Sunday midnight |

## Try It Online

👉 [risetop.top](https://risetop.top) — Free online tools for developers and everyone.

## License

MIT License — free to use, modify, and distribute.
