# Github Actions for liferay-frontend

## Workflows
### [Sync liferay-portal fork](https://github.com/liferay-frontend/github-actions/blob/master/.github/workflows/sync-liferay-portal.yml)

This is a cron job that runs hourly to sync [liferay-frontend/liferay-portal](https://github.com/liferay-frontend/liferay-portal) to [liferay/liferay-portal](https://github.com/liferay/liferay-portal)

### [AUI Snapshot Release](https://github.com/liferay-frontend/github-actions/blob/master/.github/workflows/aui-snapshot-release.yml)

Manual task to kick off a snapshot release to maven. It takes the latest `master` branch from `liferay-frontend-projects`

### [AUI Official Release](https://github.com/liferay-frontend/github-actions/blob/master/.github/workflows/aui-official-release.yml)

Manual task to kick off an official release to maven. It takes the latest `master` branch from `liferay-frontend-projects`

### [Run Performance Report](https://github.com/liferay-frontend/github-actions/blob/master/.github/workflows/run-performance-report.yml)

This is a cron job that runs daily to publish performance reports to [https://liferay-frontend.github.io/github-actions/](https://liferay-frontend.github.io/github-actions/)
