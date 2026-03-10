# Security Policy

## Forbidden Data
The following items must **NEVER** be committed to this repository:
- API keys
- .env files
- SSH private keys
- Database connection strings

## Repository Visibility
- **Public Repo:** Visible to the entire internet and actively searchable by bots.
- **Private Repo:** Restricted to specific collaborators only.

## Local Secret Management
`.env` files should be used locally to store secrets (like API keys or database strings). These secrets should be accessed as environment variables within your code instead of being hardcoded, ensuring they are never committed to version control.
