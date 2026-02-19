# RLAD - Record Losses And Debt

```
 ██████╗  ██╗       █████╗  ██████╗
 ██╔══██╗ ██║      ██╔══██╗ ██╔══██╗
 ██████╔╝ ██║      ███████║ ██║  ██║
 ██╔══██╗ ██║      ██╔══██║ ██║  ██║
 ██║  ██║ ███████╗ ██║  ██║ ██████╔╝
 ╚═╝  ╚═╝ ╚══════╝ ╚═╝  ╚═╝ ╚═════╝
  Record   Losses   And   Debt
```

A minimalist CLI finance tracker for users who want to manage their spending without the overhead of
spreadsheets or bloated apps. Track income and expenses, sort and filter transactions, and get quick
summaries -- all from your terminal.

## Quick Start

1. Ensure you have **Java 17** or above installed.
2. Download the latest `RLAD.jar` from the [Releases](https://github.com/AY2526S2-CS2113-T06-4/tp/releases) page.
3. Run it:
   ```
   java -jar RLAD.jar
   ```

## Commands at a Glance

| Command | What it does | Status |
|---------|--------------|--------|
| `add` | Record a new transaction | Planned |
| `list` | View transactions (supports `--sort amount\|date`) | Working |
| `delete` | Remove a transaction by hash ID | Planned |
| `modify` | Edit an existing transaction | Planned |
| `summarize` | Get a financial breakdown | Planned |
| `help` | View available commands and usage | Working |
| `exit` | Exit the app | Working |

## Documentation

- **[User Guide](docs/UserGuide.md)** -- Full command reference with examples
- **[Developer Guide](docs/DeveloperGuide.md)** -- Architecture and design docs
- **[About Us](docs/AboutUs.md)** -- Team members

