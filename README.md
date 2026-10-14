# Luca's Loaves Assessment Website

Code-only handover branch for continued implementation and local testing. The student assessment guide, named evidence workbook, sitemap PDF, and personal assessment files were intentionally excluded because the destination repository is public.

## Local setup

Requirements: PHP 8+ with `mysqli` and `fileinfo`, and MySQL/MariaDB.

1. Import `database/schema.sql` into a local database. It creates `lucas_loaves_assessment` with sample bakery products and one sample job.
2. Configure `LL_DB_HOST`, `LL_DB_USER`, `LL_DB_PASSWORD`, and `LL_DB_NAME` in the PHP process environment. `settings.php` uses local XAMPP-style defaults and `lucas_loaves_assessment` if unset. Never commit real credentials.
3. Set the web server document root to the repository root and start PHP/MySQL.
4. Register a test account and verify authentication, logged-out order restriction, products, cart, checkout, classes, careers/job application, and contact form.
5. Complete the assessment evidence locally using genuine results and screenshots. Do not claim tests or HTTPS checks not performed.

This is an assessment project, not a production payment service. It does not collect or store card numbers or CVV. Enable HTTPS before asserting transport encryption.
