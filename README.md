Directory is a collection of websites that offer their information in form of parsable feeds. The information is being used to populate feedreaders. Categorization is, at this stage in the project, out of scope. If categorizatoin is required, it can be added manually or automatically through other projects.

urls.md
---------

  The primary collection of news websites. It is meant as the directory of blogs and/or news sources. You are welcome to contribute to that collection.

sites.yaml
----------

  This file contains processed information, extraced from URLs listed above. Information contained therein covers, if available, the following:

    title: The title of the site.
    url: The url of the site, for reference.
    feeds:
      A list of feeds offered by this site.
    og:
      Open Graph Information.

Tools

  sites.py - Collects Websites Information and associated Feed URLs
  feeds.py - Collects Feed Details
  entries.py - Processes Individual Entries from Feeds
