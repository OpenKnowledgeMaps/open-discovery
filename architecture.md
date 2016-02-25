# Architecture

The following is an architectural proposal for the Blaze Open Knowledge Map application:

## Papers: Data Aggregation & Metadata

**desc:** A json rest api or graphql endpoint which wraps various data sources, such as sckott's [R ropensci fulltext library](https://github.com/ropensci/fulltext).

**url:** https://api.archivelab.org/scholar

**stack:** python, flask, postgres, sqlalchemy, R,

**github:** https://github.com/ArchiveLabs/scholar.archivelab.org

**spec:** pending approval


## OKM Backend + Database

**desc:** A REST API to a database of user accounts, preferences, and curated topic maps

**url:** https://api.openknowledgemaps.org

**stack:** php, mysql

**github:** https://github.com/pkraker/HeadstartServer (to be created)

**spec:** pending approval


## Front-end

**desc:** a standalone, serverless SPA (single page app)

**url:** https://openknowledgemap.org

**stack:** react, d3, jquery

**github:** https://github.com/pkraker/Headstart

**spec:** pending approval
