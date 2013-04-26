# NoEyeRape - making the web more pleasant to look at, but still not broke.

This repo contains several files:

 - hosts: the contents of this file can be pasted into your computer's hosts file, thus preventing any of those sites from ever opening on your computer again. That way, you can be sure they'll never get a single ad-view or page visit from you ever again. This is only for the most critical offenders. Please note that you shouldn't do this if you rely on the information on those websites. I've typically found that I don't really need the sites I block this way, and I never miss them.

- blocklist: this is like the hosts file for Google's search results. The contents of this file can be imported into Google's Personal Blocklist extension, thus making sure the sites don't appear in your Google search results either. If you add this in addition to the hosts file, the website in question is effectively deleted from the web for you individually.

- adblockrule: contains a string which can be pasted into the advanced options of the AdBlock extension. This makes sure ads are not shown only on these specific domains. I use this for sites I use often and don't want to lose access to, but find their ads invasive, rude and distracting.

- adblockrule_violations: a file explaining each of the violators in the adblockrule file. This is because the adblock syntax won't allow comments, so it wasn't possible to explain the offenders in the adblockrule file itself.

# Contributing

If you would like to add your own contributions, please submit a pull request. Submit PR violations preferably in the form of a permanent post online with a screenshot. For examples, see the files related to the kind of block you want to do.
The best kind of contributing, though, is just sharing this with other people. The more people we get involved, the faster we can weed out bad user experiences on the web. This feedback alone should be enough for a positive change.

# Origin

Ads are not bad. Invasive, rude and distracting ads are bad. The origin post regarding this effort is here: http://goo.gl/3Px7n
