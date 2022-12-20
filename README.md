# Change Log for premium social network as of 12-2021
PREMIUM SCOIAL NETWORK 6.6 BUILD 1671544138 20-12-2022
- [U] RememberLogin 

PREMIUM SOCIAL NETWORK 6.5 build 1669820463 30-11-2022
- [U] SharePost now allows to share videos, polls, events, marketplace, files.
- [U] Updated videos component to 9.0
- [U] Updated MultiPurpose theme with some improvements.

PREMIUM SOCIAL NETWORK 6.4 build 1661510459 26-08.2022
- [R] Removed Hashtag 5.0 and replaced it with old version.
- [U] Sentiment component update
- [U] Censorship
- [U] Videos
- [U] LinkPreview

The update is for OSSN 6.4 release.

PREMIUM SOCIAL NETWORK 6.3-build 1657717409 13-07-2022
- [U] HashTag 5.0

PREMIUM SOCIAL NETWORK 6.3-build 1657216129 07-07-2022
- [U] Videos 8.3

PREMIUM SOCIAL NETWORK 6.3-build-1656752311 02-07-2022
- [U] Videos 8.2
- [B] Old videos and events images not showing after update.

PREMIUM SOCIAL NETWORK 6.1-build 1651253416 29/04/2022
- [U] Share post 3.1 

PREMIUM SOCIAL NETWORK 6.1-build 1650628405  22/04/2022
- [U] Updated Social Theme and Awesome theme.

PREMIUM SOCIAL NETWORK 6.1-build-1647196473  13/03/2022
- [U] Polls 2.2
    - [E] Added total people voted count in title of polls (right corner).

PREMIUM SOCIAL NETWORK 6.1-build-1646717283  08/03/2022
- [U] Stories 2.1
    - [B] Delete button missing due to BS5
    - [E] Add a warning before delete
   
PREMIUM SOCIAL NETWORK 6.1-build-1645803269  25/02/2022
- Remember Me Login 3.0 
    - [E] Update fingerprint to v3
    
PREMIUM SOCIAL NETWORK 6.1-build-1643890979  03/02/2022
- CUSTOM FIELDS 7.0
    - [B] Sorting of custom fields doesn't reflect singup form.
    - [B] data_args undefined variable because on custom fields 6.2
    
PREMIUM SOCIAL NETWORK 6.1-build-1642951734  02/02/2022
- [E] Updated to CustomFields 6.2

PREMIUM SOCIAL NETWORK 6.1-build-1642951734  01/23/2022
- [B] Old videos uploaded before Videos component 7.2 update didn't shows because the upgrade script was missing.
- [B] Some old updates didn't got registered in updated list (even after script execution). 1542564032, 1561645773, 1578946534
- [B] Link not visible for sent box , messages window. Updated to White theme 6.3
  
PREMIUM SOCIAL NETWORK 6.1-build-1642176255  01/14/2022
- EVENTS 4.2
     - [B] Event add date is not translated when different langauge in use.
- BUSINESS PAGES 2.2
    - [E] Add a search page type for business pages
- MULTI PURPOSE THEME 6.3
    - [B] Show date picker dark mode
    - [E] Show business page search icon.

PREMIUM SOCIAL NETWORK 6.1-build-1640876563  12/30/2021
 - USER VERIFIED 3.0 
    - [E] Show tick on user friends list
    - [B] Tick not showing on user/photo view comment list.
 
PREMIUM SOCIAL NETWORK 6.1-build-1640793001  12/29/2021
- VIDEOS  7.2.
  - [B] Videos cron.php was not able to run due to SAPI from cpanel cron job not returning cli rather cgi-fcgi. Improved the detection system.
 
PREMIUM SOCIAL NETWORK 6.1-build-1640155314  12-22-2021
- [B] Polls, videos, events As of OSSN 6.1 we need to set $vars['full_view'] = false; in entity view comments params to avoid showing all comments.
- [E] Videos component updated to 7.x.
    - Adds a cron job to do a video conversion in backend.
    - Adds a video pending conversion page only for admins and video owner. 
    - Adds a video delete option if video conversion failed.
    - Please see https://www.openteknik.com/wiki/view/21820/videos-component-configuration

PREMIUM SOCIAL NETWORK 6.1-build-1639928890  12-19-2021
- [B] Business page causing to show all comments in the newsfeed.

PREMIUM SOCIAL NETWORK 6.1-build-1639302274  12-12-2021
- [B] Family and realationship shows wrong realtionship type.
