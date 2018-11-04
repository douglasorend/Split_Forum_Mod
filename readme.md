------

# SPLIT FORUM MOD v2.0 BETA 3.1

[**By Dougiefresh**](http://www.simplemachines.org/community/index.php?action=profile;u=253913) -> [Link to Mod](https://custom.simplemachines.org/mods/index.php?mod=3730)

------

## Introduction
This modification allows you to divide your categories into subforums, a pseudo-forum located on a different directory, subdomain, or domain than the "primary forum".  The primary forum is any forum that has this modification installed.

## What It Does
[quote author=Terry at Moke link=topic=523055.msg3713355#msg3713355 date=1403833435]
It is a mod for the User side of things, but obviously it needs to be managed in the Admin pages to create the subforums, and this mod allows you to create Categories and Boards that appear to the end user as a separate Forum, either via the URL or even the domain name, and these separate Forums can have their own Themes as well. However it all shares the same database as your original forum so usernames, passwords, profiles etc are all the same so there is less for you and the end users to manage.

Without this mod if you wanted to limit access to particular Boards based you could set up a membergroup and just give them access to the Board(s) required and then they would see the extra Board(s) as part of the main Forum page, however they would still see the rest of the Forum as it is with the same theme etc. Yes you can change the theme for a Board but that would be a bit abrupt in most cases. 

With this mod you are essentially doing the same thing with the Membergroup and Board(s) regarding settng up the access but they get to see the Boards as a separate Forum, without all the other boards they might have access too and with a completely different theme if you wish. In the subForum they see the same stats, who is online, News, menu options etc. relative to the membergroup access they have, but with just the Boards you have chosen for them to see.
[/quote]

## Admin Alterations
There is a new area at ***Admin* -> *Forum* -> *SubForums***, which allows you to manage your subforums here.  Clicking on the board title on the left side will take you to the subforum itself.  Clicking on the **Boards** link on the right side will take you to the ***Admin* -> *Forum* -> *Boards*** area, restricted to that subforum.

On the primary subforum, creating a subforum is as easy as clicking on the **Create New SubForum** tab (and/or button) and filling out the information in order to create your new subforum.  This mod can create the folder and generate an "index.php" if required.  Subforum user registration agreements are mantained by the mod.

Clicking on **Modify** opens a page where you can change settings for that subforum, such as:

- Changing the title of the subforum
- Changing the server URL and/or path of the subforum
- Adding a favorites icon to the subforum
- Changing the default theme of the subforum
- Changing the default language of the subforum
- Changing the subforum ID on secondary subforums
- Changing the primary membergroup of new users registered to the subforum

Clicking on the **Delete** button will prompt what to do with categories within the board and will delete once the decision has been made by the user.

On the ***Admin* -> *Forum* -> *Boards*** page using the primary subforum, the categories and boards are seperated by which subforum they belong to.  On secondary subforums, only those categories and boards that belong to that subforum show up.

"Package Manager" and "Server Settings" settings are not available to Subforums, as these screens contain sensitive information that affects all subforums.

All recent posts, xml-based feeds, and other forum-related functionality works for each of the individual subforums.

## New Hook Added

- **integrate_subforum_subdomain** - Hook for creating/deleting subdomains and/or domains

## Special Credits

- [Greygal](http://www.simplemachines.org/community/index.php?action=profile;u=394494) made the mod compatible with [Event Registration for SMF2](https://custom.simplemachines.org/mods/index.php?mod=3238) in 3 posts starting [here](http://www.simplemachines.org/community/index.php?topic=523055.msg3767088#msg3767088)!  Thanks, greygal!!
- [KSRandom](https://www.simplemachines.org/community/index.php?action=profile;u=478373) added control over user membergroups per subforum!

## Compatibility Notes
This mod was tested on SMF 2.0.15, ~~ but should work on SMF 2.1 Beta 3~~, as well as SMF 2.0 and up.  SMF 2.1 Beta 1 and 2, as well as SMF 1.x, is not and will not be supported.

These optional mods should be installed (if desired) prior to this mod's installation:

- [Alias Boards v1.2+](https://custom.simplemachines.org/mods/index.php?mod=1024)
- [Pretty URLs](https://custom.simplemachines.org/mods/index.php?mod=636)
- [SimplePortal v2.3.6](https://custom.simplemachines.org/mods/index.php?mod=1104)
- [ezPortal](https://custom.simplemachines.org/mods/index.php?mod=1461)
- [Like Posts](https://custom.simplemachines.org/mods/index.php?mod=3708)
- [Event Registration for SMF2](https://custom.simplemachines.org/mods/index.php?mod=3238)

## Changelog
The changelog can be viewed at [XPtsp.com](http://www.xptsp.com/board/free-modifications/split-forum-mod/?tab=1).

## License
Copyright (c) 2013 - 2018, Douglas Orend, Kirk Sykora

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
