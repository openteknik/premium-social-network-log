# Change Log for premium social network as of 12-2021
PREMIUM SOCIAL NETWORK 6.1-build-1646717283  08/03/2022
- Stories 2.1
    - Delete button missing due to BS5
    - Add a warning before delete
   
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
