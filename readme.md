# About
I wanted a way to parse Marvel Crisis Protocol data from BattleScribe and push it to a database so I could easily use it in other projects.

*   The raw BS xml schema is... awful.
*   This notebook parses the html output of a roster built in the BS app and normalizes it enough to work in a relational database.
*   I'm not providing the data, but it's freely available through the BS app.

## prereqs
You'll need to install BeautifulSoup (bs4) to run this notebook, but you should use whatever your preference is for env and database connection handling to suit your needs.

## Known issues
*   The tactics cards need a good regex cleaning
*   Need to bring in mission cards
*   Need to handle leadership
*   Need to account for magic space stones and their affect on threat levels
*   more distant -- handle powers, attacks, and healthy/injured stats