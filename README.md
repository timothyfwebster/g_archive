# g_archive
Backup and removal tool for managing your gmail box

## Usage:

> python rm_old.py [number of days] [directory to which files will save]

The script will archive any emails older than the number of days you enter. Be sure to enter the full directory path.

## Wishlist

- [ ] Usage/argparser
- [ ] Better error handling
- [ ] Auto-zip your archive
- [ ] Password/credential handling


This script was based primarily off [Radek Wojcik](http://radtek.ca/blog/delete-old-email-messages-programatically-using-python-imaplib/) and a post written 3 years ago on this subject. I've updated this with an archive option and some PEP8 guidelines but Radek did most of the work so hats are off! 
