# zimbra-unused-accounts
find Zimbra accounts which have not been used in some time

## Usage (as user root):
*  zimbra-unused-accounts 15
 finds all account older than 15 days days

## Files
* /etc/zimbra-unused-accounts.ignore - list of usernames to ignore (optional file)

## Environment variables
* DEFAULT_DOMAIN=zimbra.example.com - zpush sometimes does not specify  domain, add this domain on all acounts without one specified
* SKIP_NEVER=0 - also reports never used account (default is SKIP_NEVER=1, which ignores them)
* DEBUG=2 - for debug
