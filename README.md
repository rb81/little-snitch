# little-snitch
Little Snitch Rule Group for blocking ad networks, social media plugins, and other annoyances.

## How to Subscribe

1. Host the `Blockers.lsrules` file somewhere on the Internet,
2. Open up the Little Snitch Rules screen,
3. Click on the `+` on the right of Rule Groups (on the left),
4. Enter the URL of the hosted file.

## How to Add More Rules

Simply follow the format in the file, appending new entries to the bottom of the list:

    {
        "action" : "deny",
        "process" : "any",
        "remote-domains" : "facebook.com"
    }

## Configuration Options

Little Snitch has a number of useful configuration options -- such as the ability to limit blocking to certain apps or processes. This version blocks the domains from all processes. You can also combine URLs, but I've separated them to make it easier to find and modify them.

## More Information

https://help.obdev.at/littlesnitch4/lsc-rule-group-subscriptions

## You May Also Like

https://pgl.yoyo.org/adservers/serverlist.php?hostformat=littlesnitch-rule-group-subscriptions&mimetype=plaintext
