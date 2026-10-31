# Dbro

A fast, lightweight desktop database manager for Windows, with a Navicat-style interface.

**Supported databases:** MySQL · MariaDB · PostgreSQL · SQL Server · SQLite

## Download

👉 **[Download the latest version](https://github.com/Ichione-Oriza/Dbro/releases/latest)**: get `Dbro-Setup-x.y.z.exe` from the **Assets** section.

### Installation

1. Run `Dbro-Setup-x.y.z.exe`. Dbro installs for the current user and does not need administrator rights.
2. Windows SmartScreen may show *"Windows protected your PC"* because the installer is not code-signed yet. Click **More info → Run anyway**.

### Updates

Dbro checks for new versions on startup and downloads them in the background. When an update is ready, choose **Restart Now** to install it right away, or **Later** to install it the next time you close the app. You can also check manually via **Help → Check for Updates…**.

Your connections, saved passwords, scripts and backups are kept when you update.

## Features

- **Connections**: MySQL, MariaDB, PostgreSQL, SQL Server and SQLite, with SSL and **SSH tunnel** support (password or private key). Saved passwords are encrypted with Windows DPAPI.
- **Connect by URI**: e.g. `mysql://user:pass@host:3306/db`.
- **SQL editor**: syntax highlighting, autocomplete, run multiple statements or just the selection, Explain, export results to CSV/JSON.
- **Table data**: inline editing, add/delete rows, Navicat-style filter & sort, grid/form view, cell editor, pagination.
- **Table designer** (MySQL/MariaDB, PostgreSQL): fields, indexes, foreign keys, checks, triggers, with SQL preview.
- **User management**: create and edit users, roles and logins; manage privileges.
- **Dump & restore**: pure JavaScript, works over SSH tunnels, no `mysqldump`/`pg_dump` needed.
- **Import/export**: CSV import wizard; export to CSV, JSON or SQL.
- **Script library**: save queries per connection and database.
- **Light and dark themes**.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| Ctrl+Enter / F9 | Run query |
| Ctrl+Shift+Enter | Run selection |
| Ctrl+S | Save query / apply table changes |
| Ctrl+Q | New query |
| F2 / Enter | Edit cell |
| F5 | Refresh |

## Where your data is stored

| What | Location |
| --- | --- |
| Connections & settings | `%APPDATA%\Dbro` |
| Scripts | `C:\Users\<you>\Dbro\Scripts` |
| Backups | `C:\Users\<you>\Dbro\Backups` |

## Reporting issues

Found a bug or have a suggestion? Please open an [issue](https://github.com/Ichione-Oriza/Dbro/issues).
