# radarr-upgrade-filter

## Description
radarr-upgrade-filter is a tool designed to help manage and filter movie downloads in a Radarr setup within a Docker environment. It ensures that only higher quality versions of movies are downloaded, even if the original files in your library are low quality.

## Features
- **Quality Filtering**: Ensures that only better quality versions of movies are downloaded.
- **Blacklist Management**: Manages blacklisted releases to avoid downloading unwanted content.
- **History Tracking**: Keeps track of download decisions and history for auditing.
- **Web Interface**: Provides a web interface to manage settings, view history, and monitor downloads.

## Installation

### Prerequisites
- Docker
- Docker Compose

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/radarr-upgrade-filter.git
   cd radarr-upgrade-filter
