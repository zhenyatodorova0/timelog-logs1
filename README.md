# timelog-logs1

Storage for incident timelog files. Files are automatically deleted after **7 days** via a scheduled GitHub Actions workflow.

## How it works

- Drop timelog files into this repository
- A daily GitHub Action checks all files and removes any committed more than 7 days ago
- The workflow runs at 2:00 AM UTC every day and can also be triggered manually
