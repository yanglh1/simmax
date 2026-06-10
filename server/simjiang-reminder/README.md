# SimJiang Cloud Reminder Service

Cloud reminder backend for SimJiang.

Features:
- Multi-user API keys (`/api/register`)
- Per-key isolated sync data (`/api/sync`)
- Telegram test/reminders (`/api/test-telegram`)
- SMTP email test/reminders (`/api/test-email`)
- Manual expiry check (`/api/check-now`)
- Periodic expiry scan every 30 minutes

Default production endpoint used by the app:

```text
https://ccs.ziranaa.top:16670
```

Systemd service name on VPS:

```text
simjiang-reminder
```
