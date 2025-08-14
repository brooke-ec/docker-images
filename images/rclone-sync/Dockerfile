FROM rclone/rclone

CMD echo "${CRON:-* * * * *} rclone sync ${SOURCE} ${TARGET} ${OPTIONS}" >> /var/spool/cron/crontabs/root && crond -f -l 8 -L /dev/stdout

ENTRYPOINT []