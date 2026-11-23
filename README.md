# BORCELLE Books — Bookstore Web Application

BORCELLE Books is a bookstore website project with separate frontend and backend directories. It is intended to demonstrate an online book-browsing and shopping experience.

## Repository structure

- `Frontend/` — user-facing website
- `Backend/` — server-side application and supporting code

## Getting started

The exact setup depends on the scripts and configuration files in each directory. Review the backend and frontend folders, install their respective dependencies, and configure the local database before running the application.

## Configuration and security

- Use local configuration for database credentials.
- Do not commit real passwords, private keys, production credentials, or personal customer data.
- Change any default development credentials before deploying.
- Use synthetic records when demonstrating the application.

## Development notes

Before deploying, document the database schema, required environment variables, installation commands, and any payment or authentication integrations that are actually implemented.


## Repository completeness notes

The current tracked backend files are not a complete runnable PHP application: `Backend/config.php` requires `Backend/classes/DBConnection.php` and `Backend/classes/SystemSettings.php`, but those class files are not present in the repository tree. A fresh clone will need the missing classes and a configured MySQL database before the backend can run. The current local database settings in `Backend/initialize.php` are development defaults; replace them with environment-based configuration before any deployment, and do not expose default developer accounts on a public server.
