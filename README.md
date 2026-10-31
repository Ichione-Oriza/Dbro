# Dbro

A fast, lightweight desktop database manager for Windows.

**Supported databases:** MySQL · MariaDB · PostgreSQL · SQL Server · SQLite

## Download

👉 **[Download Dbro-Setup.exe](https://github.com/Ichione-Oriza/Dbro/releases/latest/download/Dbro-Setup.exe)** (latest version)

All versions and release notes: [Releases](https://github.com/Ichione-Oriza/Dbro/releases).

**Requirements:** Windows 10 or 11, 64-bit.

### Installation

1. Run `Dbro-Setup.exe` and choose where to install (default: `%LOCALAPPDATA%\Programs\Dbro`). Dbro installs for the current user and does not need administrator rights.
2. Windows SmartScreen may show *"Windows protected your PC"* because the installer is not code-signed yet. Click **More info → Run anyway**.

### Updates

Dbro checks for a new version when it starts, or via **Help → Check for Updates…**. If one is available, it shows what's new and asks **Download & Install** or **Later**. After the download, Dbro closes, installs the update and opens again.

Your connections, saved passwords, scripts and backups are kept when you update.

## Features

- **Connections**: MySQL, MariaDB, PostgreSQL, SQL Server and SQLite, with SSL and **SSH tunnel** support (password or private key). Saved passwords are encrypted with Windows DPAPI; SSH host keys are verified.
- **Connect by URI**: e.g. `mysql://user:pass@host:3306/db`.
- **SQL editor**: syntax highlighting, autocomplete, run multiple statements or just the selection, Explain, export results to CSV/JSON.
- **Table data**: inline editing, add/delete rows, filter & sort builder, grid/form view, cell editor, pagination.
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
| Connections, settings, known SSH hosts | `%APPDATA%\Dbro` |
| Scripts | `C:\Users\<you>\Dbro\Scripts` |
| Backups | `C:\Users\<you>\Dbro\Backups` |

## Reporting issues

Found a bug or have a suggestion? Please open an [issue](https://github.com/Ichione-Oriza/Dbro/issues).

## License

Dbro is released under the [MIT License](LICENSE). Licenses of bundled third-party software are in `THIRD_PARTY_NOTICES.txt` in the install folder.

MySQL, MariaDB, PostgreSQL, SQL Server and SQLite are trademarks of their respective owners. Dbro is an independent project and is not affiliated with them.
