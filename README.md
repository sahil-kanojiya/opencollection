# API Collections

A centralized, Git-versioned repository of API requests, environments, and automated test collections built with [Bruno](https://www.usebruno.com/).

## ðŸ“ Repository Structure

`	ext
api-collections/
â”œâ”€â”€ bruno.json                  # Collection definition
â”œâ”€â”€ environments/
â”‚   â”œâ”€â”€ Local.bru              # Default local variables (localhost:8080)
â”‚   â”œâ”€â”€ Dev.bru                # Dev environment variables
â”‚   â””â”€â”€ *.env                  # Secret variables (gitignored)
â”œâ”€â”€ job-portal/                 # Job Portal Microservices requests
â”‚   â”œâ”€â”€ folder.bru
â”‚   â””â”€â”€ health-check.bru
â”œâ”€â”€ hotel-booking/              # Hotel Booking Microservices requests
â”œâ”€â”€ book-management/           # Book Management API requests
â””â”€â”€ nexora/                     # Nexora communications platform requests
`

## ðŸš€ Getting Started with Bruno

1. Open **Bruno Desktop**.
2. Click **Open Collection**.
3. Select this folder: `D:\my-projects\api-collections`.
4. In the top-right environment dropdown, select **Local** or **Dev**.
5. Run your requests!

## ðŸ”’ Secret Management

- Non-sensitive variables are committed in `environments/<EnvName>.bru`.
- Secrets (tokens, API keys, passwords) should be marked as **Secret** in Bruno, which places them into `environments/<EnvName>.env` (automatically protected by `.gitignore`).
