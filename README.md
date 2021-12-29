# Change Log for premium social network as of 12-2021
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
