# CommunityScrapers
This is a public repository containing scrapers created by the Stash Community.

To download the scrapers you can clone the git repo or download directly any of the scrapers.

When downloading directly click at the scraper.yml you want and then make sure to click the ![raw](https://user-images.githubusercontent.com/48220860/82433600-59c5d580-9a9a-11ea-8f51-f7d80e3ce735.png) button and then save page as file from the browser to preserve the correct format for the yml file.

Any scraper file has to be stored in the `~/.stash/scrapers` ( ~/.stash is where the config and database file are located) directory. If the directory is not there it needs to be created.

After updating the scrapers directory contents or editing a scraper file a restart of stash is needed and a refresh of the edit scene/performer page.

## Scene Scrapers
You can find a list of sites currently supported for by community scene scraping in [SCENE-SCRAPERS.md](https://github.com/stashapp/CommunityScrapers/blob/master/SCENE-SCRAPABLE.md)

## Performer Scrapers
This list is meant to keep track of which sites are already supported by existing community scrapers. And which scrapers support them. When introducting a new scraper, add the sites your scraper supports to this list in your PR. Please keep the site list in alphabetical order to keep the list tidy.

Supported Site|Scraper
------------- | -------------
babepedia.com|Babepedia.yml
freeones.xxx|NewFreeones.yml
iafd.com|Iafd.yml

## Contributing
Contributions are always welcome! Use the [Scraping Configuration](https://github.com/stashapp/stash/wiki/Scraping-configuration) wiki entry to get started and stop by the [Discord](https://discord.gg/2TsNFKt) #the-scraping-initiative channel with any questions.
