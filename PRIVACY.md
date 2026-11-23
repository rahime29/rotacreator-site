# Rota Creator – Privacy Policy

_Last updated: 22 November 2026_

Rota Creator is a personal automation that produces short travel videos ("Next Station is <City>") and uploads them **only to the Rota Creator YouTube channel** (https://www.youtube.com/@rotacreator), owned and operated by the author of this project. It has no end users and no sign-up.

## Use of YouTube API Services
Rota Creator uses the **YouTube API Services** (YouTube Data API v3) to upload videos to the owner's own channel.
By using YouTube features of this project you agree to be bound by the **YouTube Terms of Service**: https://www.youtube.com/t/terms

YouTube and Google data are handled according to the **Google Privacy Policy**: https://policies.google.com/privacy

## What data is accessed
With the owner's OAuth authorization, Rota Creator uses these scopes:
- `youtube.upload` – to upload the generated video and its title, description and tags.
- `youtube.readonly` – only to read the authorized channel's ID (`channels.list?mine=true`) and confirm that uploads go to the correct channel.

Rota Creator does **not** access, collect or store any information about viewers, other users or other channels, and does not read comments, analytics or private data.

## What data is stored
- The OAuth client ID, client secret and refresh token of the owner are stored only as encrypted GitHub Actions secrets and in a local `.env` file on the owner's computer. They are never committed to the repository or shared.
- After an upload, only the public YouTube video ID, upload time and privacy status are stored in a private project file.
- No personal data, cookies or tracking are used.

## Sharing
No data obtained through the YouTube API Services is shared with, sold to or disclosed to any third party.

## Deletion and revoking access
- Access can be revoked at any time at the Google security settings page: https://security.google.com/settings/security/permissions
- Revoking access immediately stops all uploads. Stored tokens are deleted by removing the GitHub secrets and the local `.env` file; stored video IDs can be deleted on request.
- Videos can be deleted directly in YouTube Studio.

## Contact
Questions or deletion requests: https://github.com/rahime29/rotacreator-site/issues
