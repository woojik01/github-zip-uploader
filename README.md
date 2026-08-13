# GitHub ZIP Uploader

Mobile-friendly PWA for uploading a ZIP archive to a GitHub repository through a secure Vercel serverless API.

## Planned flow

1. Enter GitHub repository settings.
2. Enter a fine-grained GitHub Personal Access Token with repository Contents read/write permission.
3. Select a ZIP file on mobile or desktop.
4. Preview files and upload them as a Git commit.

The GitHub token must never be exposed in client-side JavaScript or committed to the repository.