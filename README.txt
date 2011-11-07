MobileCube
Version 3.1.0 beta

MobileCube is a skin for the [RoundCube](http://roundcube.net/) PHP web mail app styled after Apple's MobileMe web mail client. It was developed by [PhireWare](http://phireware.com/) as a [SourceForge project](http://sourceforge.net/projects/mobilecube/).

The author has apparently given up development on this theme in favour of [CrystalMail](http://www.crystalmail.net/), which is itself now dormant. SourceForge isn't a good venue for a project with an absent maintainer, so I created this fork from the last version posted on there.

The orginal theme bundled the RoundCube calendar plugin, but that is now maintained separately as part of the [myroundcube plugin bundle](http://code.google.com/p/myroundcube/), so I have removed it from this repo and rearranged the folders to simplify it. The install instructions have not been updated to match.

The beta release this was forked from has some problems, some of which are described in [this post](http://www.roundcubeforum.net/8-themes-styling/28-theme-releases/6012-new-mobileme-mobilecube-17.html#post34907). I have applied those changes in this repo.

Please fork and request pulls so we can keep this lovely theme alive!

Original README follows
=======================

Installing:
Unarchive the MobileCube.zip file and place it in the /skins/ directory.


Config requirements:

Skin Folder MUST be called "MobileCube"



$rcmail_config['list_cols'] = array('flag', 'from', 'subject', 'date', 'size', 'attachment');

$rcmail_config['default_imap_folders'] = array('INBOX', 'Drafts', 'Sent', 'Trash', 'Junk');

$rcmail_config['skin_path'] = 'skins/MobileCube/';

$rcmail_config['preview_pane'] = TRUE;