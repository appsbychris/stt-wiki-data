Star Trek Timelines Recipe and Drop Data
========================================

This repository contains data extracted from the [Star Trek Timelines
Wiki](http://startrektimelineswiki.com/wiki/Main_Page) for item
recipes, drop rates, and character item requirements. The data are
stored in JSON format.

Out of respect to the maintainers of the wiki, the Wikimedia API is
used to extract the content using only about 120 queries. To avoid
strain on their servers, I haven't posted the scraping and parsing
code, but I'll update the data periodically as long as I'm playing the
game.

The wiki is a great community resource -- unofficial and player
run. Please be sure to update the drop rates as well as any new or
modified recipes.


Caveats
-------

These data are, at best, as good as the wiki. Due to various parsing
issues, they're probably worse.

Drop rates are not known for faction-only items, nor do I have a list
of faction-only items. These would show up as items used in recipes
that do not have drop rates. Unfortunately, typos appear the same
way. I haven't gone through the process of validating all the items
with missing recipes or drop rates.

For formatting reasons when expanding large chains of items, a few
common recipes have been entered in a way that's very difficult to
parse. For example, [Basic Civilian Engineer
Clothing](http://startrektimelineswiki.com/wiki/Template:ItemX/Civilian_Engineer_Clothing/0).
I'd probably need to maintain a list of exceptions where I can't rely
on the wiki.

Some items can come from different eras, but the era is not always
specified on the character or recipe page. For example, it is not
specified which era of communicator is equipped by [1701
Sisko](http://startrektimelineswiki.com/wiki/1701_Sisko).


Licensing
---------

As the data come from the STT wiki, this content is available under
Creative Commons Attribution Share Alike. Game content and materials
are trademarks and copyrights of their respective publisher and it's
licensors.
