# Metasploit Resource Portal Data

This is the public repository for all the data that fuels the
[Metasploit Resource Portal][site], a community-driven effort
to collect and highlight especially useful resources for [Metasploit
Framework][framework] users and developers.

This Resource Portal is no mere link farm of out-of-date documentation.
Oh no. If you're looking for that, [let me Google that for you][lmgtfy]
-- there are nearly **900,000** such links for you to peruse.

Instead, the Resource Portal is a **curated** and **continuously
reviewed** collection of the most helpful videos, blog posts, podcasts,
and other helpful resources, produced mainly by community contributors.

While we do have some [Getting Started][getting-started] links, most of
the resources are heavy on more advanced developer and penetration-tester
[pro tips][pro-tips].

## Adding a Resource

If you have found or written something especially insightful involving
Metasploit, we'd love to hear about it! The procedure for review and
inclusion is easy:

1. [Fork] this repository.
1. Edit the appropriate category's corresponding [YAML][psych] file in the [data] subdirectory.
1. Create a pull request describing your resource addition.

All suggestions need to include at least a URL, a date, a title, and an
author. Follow the existing format, and you should be fine.

Once that's done, one of the kind collaborators will review it for
accuracy and relevency, and hopefully, include it on the [site] with a
heart-felt commit message of thanks.

## Other suggestions

If you have a more general bug or feature to report or suggest for the
site itself, feel free to [open an issue][issues].

  [site]: https://metasploit.github.io
  [framework]: https://github.com/rapid7/metasploit-framework
  [fork]: https://guides.github.com/activities/forking/
  [psych]: https://github.com/tenderlove/psych
  [lmgtfy]: http://lmgtfy.com/?q=metasploit
  [issues]: https://github.com/metasploit/resource-portal-data/issues
  [data]: https://github.com/metasploit/resource-portal-data/blob/master/data
  [getting-started]: https://github.com/metasploit/resource-portal-data/blob/master/data/getting_started.yml
  [pro-tips]: https://github.com/metasploit/resource-portal-data/blob/master/data/pro_tips.yml
