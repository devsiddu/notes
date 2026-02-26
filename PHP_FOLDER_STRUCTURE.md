# PHP Folder Structure Guide

## Standard PHP Project Structure

```
project-root/
├── src/
│   ├── Controllers/
│   ├── Models/
│   ├── Views/
│   └── Services/
├── public/
│   ├── index.php   <-- entry point
│   ├── css/
│   ├── js/
│   └── images/
├── config/
│   └── database.php
├── tests/
├── vendor/         <-- only if using composer
├── .env            <-- optional (manual load)
├── .gitignore
├── composer.json   <-- optional
└── README.md
```

## Directory Descriptions

| Directory | Purpose |
|-----------|---------|
| `src/` | Application source code |
| `public/` | Web-accessible files |
| `config/` | Configuration files |
| `tests/` | Unit and feature tests |
| `vendor/` | Composer dependencies |

## Getting Started

1. Create the folder structure above
2. Initialize Composer: `composer init`
3. Set up your `.env` for environment variables
4. Configure database connection in `config/database.php`
