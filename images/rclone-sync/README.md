# rclone-sync

Inspired by [periodic-rclone-sync](https://github.com/matthiasmullie/periodic-rclone-sync), synchronises a directory periodically using [rclone](https://rclone.org/).

## Configuration

A valid `rclone.conf` must to available at `/config/rclone/rclone.conf`.

- `CRON`: cron expression of when the synchronisation should run.
- `SOURCE`: provider & path to get the data from
- `TARGET`: provider & path to sync the data to
- `OPTIONS` (optional): additional rclone [options](https://rclone.org/docs/#options) (e.g. `--checkers=2 --transfers=2 --check-first`)
