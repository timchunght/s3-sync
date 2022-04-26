Install RClone
```
vi ~/.config/rclone/rclone.conf
chmod 600 ~/.config/rclone/rclone.conf
```
Syncing
```
rclone lsd spaces:BUCKET_NAME
rclone sync spaces:source_bucket s3:dest_bucket -v
rclone check spaces:source_bucket s3:dest_bucket
```