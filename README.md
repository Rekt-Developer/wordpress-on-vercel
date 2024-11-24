# WordPress on Vercel

Serverless WordPress deployment on Vercel platform.

## Setup Instructions

1. Fork this repository
2. Create a new project on Vercel
3. Connect your database (MySQL/MariaDB)
4. Configure environment variables

### Required Environment Variables

```
DB_NAME=your_database_name
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_HOST=your_database_host
WP_HOME=https://your-domain.com
WP_SITEURL=https://your-domain.com

# Generate these at https://api.wordpress.org/secret-key/1.1/salt/
WP_AUTH_KEY=
WP_SECURE_AUTH_KEY=
WP_LOGGED_IN_KEY=
WP_NONCE_KEY=
WP_AUTH_SALT=
WP_SECURE_AUTH_SALT=
WP_LOGGED_IN_SALT=
WP_NONCE_SALT=
```

## Features

- Optimized for Vercel serverless environment
- Security hardening
- CDN support
- Automated deployment

## Author

Isaac Likhon (isaac.likhon@yahoo.com)

## License

GPL-2.0-or-later
