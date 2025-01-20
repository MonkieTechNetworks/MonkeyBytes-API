# Changelog

## [2.0.1] - 2024-10-08

### Table of Contents
- [Added](#added)
- [Changed](#changed)
- [Fixed](#fixed)
- [Documentation](#documentation)

---

### Added
- **Index.js Updates**:
  - Connected the root endpoint to WebSocket protocol for real-time server metrics and updates.
  - Added dynamic content loading for server analytics.
  - Implemented medieval theme toggle functionality.

- **Improved Discord Webhook Integration for Reddit Feeds**:
  - Enhanced the functionality for fetching top 5 posts from Reddit RSS feeds (`/r/all` and `/r/discordapp`) and posting them to different Discord channels using webhooks.
  - Each post is formatted correctly with titles, content, and images (if available).

- **Eighth Edict - Noble Welcome Update**:
  - The root (`/`) endpoint now includes a grand, medieval-themed welcome message, greeting users in the noble tongue of 1066 England.
  - Interactive toggle for "Latest Decrees" allows users to show or hide the updates dynamically, enhancing usability and engagement.

---

### Changed
- **Root Endpoint Improvements**:
  - The root (`/`) endpoint now serves detailed information, including:
    - API structure guide
    - Latest updates from `updates.json`
    - Server metrics and uptime with an automatic updating UK time

- **Refined Webhook Formatting**:
  - Adjusted the formatting of Discord webhooks for Reddit posts.
  - Posts are embedded with proper titles, content, author names, and post links.
  - Improved handling of posts with no images or content.

---

### Fixed
- **Webhook Stability**:
  - Resolved issues where webhooks failed to post multiple posts or posted incomplete data.
  - Now all posts are sent sequentially with proper error handling.

- **Testing Endpoint Stability**:
  - Fixed inconsistencies with the `/testing` endpoint, ensuring correct output of random bot names, cat images, and facts.

- **Removed Unnecessary Dependencies**:
  - Removed unused packages and streamlined the codebase, ensuring that no unnecessary dependencies are included.

---

### Documentation
- **Updated Changelog**:
  - Comprehensive changelog detailing all changes, including new features, fixes, and updates, ensuring full transparency and guidance for future developers.

- **Code Structure Explanation**:
  - Updated inline documentation within the code to clearly explain all new functionality, particularly around Discord webhooks, Reddit RSS feeds, and CatFact Ninja integration.

---  

_**End of Changelog**_  
