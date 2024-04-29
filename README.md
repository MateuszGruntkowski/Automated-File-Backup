# Automatic Folder Backup Script

This Python script automatically creates a backup of a specified folder at a scheduled interval using the `schedule` library.

## How to Use
1. Set the source directory (`source_dir`) to the path of the folder you want to backup.
2. Set the destination directory (`destination_dir`) to the path where you want to save the backups.
3. (Optional) Set the desired backup time by modifying the `schedule.every().day.at()` line in the script.
4. Run the script.
5. The script will create a backup of the source folder in the destination folder at the specified time.
