# ReVanced changelog

## 2023-12-04
- Updated to 18.45.43

## 2023-11-25
- Updated to 18.45.41
- Hide layout components: Hide video quality menu footer
- Add Disable fullscreen ambient mode patch
- Add Disable suggested video end screen patch
- Add Enable old seekbar thumbnails patch
- SponsorBlock: Rename "Preview/Recap" category to "Preview/Recap/Hook"
- Rename Restore old seekbar thumbnails and Restore old quality menu
- Add Enable slide to seek patch
- Add Remove tracking query parameter patch
- ReturnYouTubeDislike: Improve layout padding
- Add Disable rolling number animations patch
- Hide ads: Hide shopping links in video description
- Hide layout components: Hide "For You" shelf in channel page

## 2023-10-27
- ReturnYouTubeDislike: Fix dislikes not showing on Shorts
- Hide layout components: Hide new channel watermark component
- Theme: Disable gradient loading screen
- Add Announcements patch
- Add Spoof device dimensions patch

## 2023-10-10
- Updated to 18.38.44
- Hide info cards: Fix info cards not hiding for some users
- Hide layout components: Always hide redundant 'player audio track' button
- Hide layout components: Hide "Join", "Notify me", search result shelf header and timed reactions
- Hide shorts components: Fix hiding navigation bar
- Restore functionality of Old video quality menu and Custom speeds on tablets
- Add Bypass URL redirects patch
- Add Disable fine scrubbing gesture patch
- Other improvements to existing patches

## 2023-09-07
- Updated to 18.32.39
- Allow setting no background color
- Apply custom seekbar color to shorts
- Add a switch to enable/disable custom seekbar color
- Add switch to hide chips shelf
- Add Player Flyout Menu patch
- Add switch to hide individual action buttons 
- Add Alternative thumbnails patch 
- Add Custom player overlay opacity patch 
- Add Enable tablet layout patch
- Restored original app name and icon

## 2023-07-18
- Updated to 18.23.35
- Remove non-functional custom video buffer patch
- Update app icon

## 2023-07-07
- Option to hide mix playlists
- Don't re-enable signature spoof automatically
- Enable predictive back gesture

## 2023-06-07
- Updated to 18.19.35
- Fix default video quality/speed being applied when resuming app
- Fix temporarily frozen video after opening a short
- Add tap and hold functionality to copy video URL buttons
- Add option to import/export ReVanced settings
- Add hide-load-more-button, hide-filter-bar and hide-shorts-components patches
- Use dynamic background color for custom splash screen
- Other fixes and improvements

## 2023-05-10
- Update to 18.16.37
- Disable debugging by default
- Fix hide action buttons not working for some users
- Remove hide-my-mix patch (broken)
- Disable minimized playback for shorts
- Add hide-player-overlay and navigation-button patches
- Fix background play of kids videos
- Other fixes and improvements

## 2023-04-22
- Update to 18.08.37
- Allow to not remember playback speed
- Automatic signature spoofing to prevent playback issues
- Change 'Hide create, clip and thanks buttons' to default off
- Fix 'Hide share button'
- Hide more types of ads
- Disable preferences and add dialog messages to preferences
- Change default video speed and quality inside the settings menu
- Various fixes and improvements to Sponsorblock and other patches

## 2023-03-18
### Patches v2.163.0
- `disable-fullscreen-panels-auto-popup`: use proper descriptions
- `general-ads`: fix switch description wording
- `hide-time`: use correct integrations class
- `hide-watch-in-vr`: fix descriptions
- `open-links-directly`: reference correct integrations method
- `general-ads`: hide channel bar
- `general-ads`: hide horizontal video shelf
- `open-links-directly`: skip every redirect url
### Patches v2.164.0
- `general-ads`: hide quick actions in fullscreen
- `general-ads`: hide related videos in quick action
- `return-youtube-dislike`: support for shorts
- Remove patch `open-links-directly`
### Patches v2.165.0
- `spoof-signature-verification` patch
### Patches v2.165.1
- `spoof-signature-verification`: use correct fingerprint
### Patches v2.166.0
- `general-ads`: remove duplicate preference
- `return-youtube-dislike`: add missing strings
- `custom-video-buffer`: replace patch with removal notice
- `disable-player-popup-panels`: use better patch description
- `general-ads`: do not hide components in library tab
- `general-ads`: hide image shelf from search results
- `hide-autoplay-button`: do not disable autoplay button when hidden
- `hide-floating-microphone-button`
- Bump compatibility to 18.05.40

## 2023-02-15
- `custom-branding`: correct scaling, margin and images
- `hide-player-buttons` patch
- `general-ads`: hide pill to view products
- `minimized-playback`: disable when playing shorts
- `general-ads`: use better description for switch
- `general-ads`: hide web search results

## 2023-01-30
- `return-youtube-dislike`: do not fetch voting stats when watching shorts
- `sponsorblock`: replace missing strings
- `general-ads`: remove hiding video shelf
- `open-links-externally` patch
- Show toasts along exceptions

## 2023-01-19
- Disabled predictive back gesture
- Added `hide-breaking-news-shelf`, `copy-video-url`, `remember-playback-rate` and `spoof-app-version` patches
- Improvements to existing patches

## 2022-12-24
- Updated base to 17.49.37
- Improvements to existing patches

## 2022-12-11
- Enabled predictive back gesture on Android 13
- Fixed swipe down to refresh
- Improvements to existing patches
- Re-enabled `theme` patch

## 2022-11-30
- Updated base to 17.45.36
- Added `open-links-directly` and `remove-player-button-background` patch
- Improvements to existing patches

## 2022-11-03
- Updated base to 17.43.36
- Added `hide-watch-in-vr` patch
- Updated Return YouTube Dislike to support new UI
- Hide Shorts comments button when hide comments is enabled

## 2022-10-28
- Updated base to 17.41.37
- Added the following patches: `hide-crowdfunding-box`, `hide-artist-card`, `hide-album-cards` and `comment`
- Re-added `hide-create-button`
- Changed default app name to ReVanced
- Use proper scaled icons
- Fixes and improvements to other patches

## 2022-10-21
- Added two new patches: `hide-my-mix` (removes mix playlists from the feed) and `hide-captions-button` (hides the captions button on video player)
- Temporarily excluded `hide-create-button` patch (conflicts with `hide-shorts-button` and makes the app crash)
- Various fixes and improvements to other patches

## 2022-10-06
- Added `disable-startup-shorts-player` and `hide-video-buttons` patches

## 2022-09-25
- Added `disable-auto-player-popup-panels` and `hide-time-and-seekbar` patches
- `custom-playback-speed`: max, min, granularity option
- Option to disable sponsorblock on shorts

## 2022-09-19
- Updated base to 17.36.37

## 2022-09-17
- Completely removed `amoled` from patches

## 2022-09-15
- Removed `amoled` patch since it's been deprecated by `theme`
- Added `disable-auto-captions` patch

## 2022-09-03
- Fixed download button color

## 2022-08-30
- Updated base to 17.33.42

## 2022-08-27
- Added `client-spoof` patch
