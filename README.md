# OpenCollection API Suite

This repository stores API collections, requests, tests, and environments adhering to the **OpenCollection YAML specification**, natively supported by [Bruno](https://www.usebruno.com/).

## ðŸ“ Structure

`	ext
opencollection/
â”œâ”€â”€ opencollection.yml          # OpenCollection root specification
â”œâ”€â”€ bruno.json                  # Bruno configuration
â”œâ”€â”€ environments/
â”‚   â”œâ”€â”€ local.yml              # Local environment variables
â”‚   â”œâ”€â”€ dev.yml                # Dev environment variables
â”‚   â””â”€â”€ *.secret.yml           # Secret variables (gitignored)
â”œâ”€â”€ job-portal/                 # Job Portal requests (.yml)
â”œâ”€â”€ hotel-booking/              # Hotel Booking requests (.yml)
â”œâ”€â”€ book-management/           # Book Management requests (.yml)
â””â”€â”€ nexora/                     # Nexora communications platform requests (.yml)
`

## ðŸš€ Opening in Bruno

1. Open **Bruno Desktop**.
2. Click **Open Collection**.
3. Select `D:\my-projects\opencollection`.
4. Choose your environment (**Local** / **Dev**) and run your requests!
