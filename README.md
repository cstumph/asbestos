## Current direction:
To research:
A web based client would be infeasible, so pretty sure I'm going to try out atom-shell: https://github.com/atom/atom-shell although phonegap may be a better direction to move in.


##Features:
- Single column or multicolumn interface.
- themeable (sorry, I have to have this)
- Subscribable mute lists/shareable filters


## Filters:
- tweets from new accounts
- tweets containing specific user names
- hashtags


##General notes:
- Try to keep in mind a good plugin architecture so additional modules can be added/overridden at whim.
- A users timeline will need to be loaded in mem/disk for filtering through a big reduce operation and frequently appended to afterwards. Maybe not grab historical tweets on first startup and only retrieve since last (not first) startup.
- Consider ethical implications of allowing archiving stored tweets(see: deleted tweets) as this is a very double edged sword, but could be useful in cases of documenting harassment.
