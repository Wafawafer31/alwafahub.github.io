# Realtime Photo Download (RTPD)

This is a ready-to-deploy PHP project for photo galleries synced with Google Drive.

## Setup

1. Run `composer install`
2. Add your `credentials.json` to `/config`
3. Run `php google_drive/drive_client.php` to authenticate
4. Access `admin/index.php` via browser

## Notes
- `token.json` and actual Google Drive files are ignored for security.
