---
title: Listen Local Bulgaria Technical Specifications
summary: Technical specifications of the Listen Local Bulgaria Databases.

tags:
  - Music information retrieval
date: "2022-12-23T00:00:00Z"

authors: ["daniel_antal"]

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/dataandlyrics
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Otherwise, set `slides = ""`.
slides: ""
---

# Technical Specifications

The `Listen Local Databases` collect, contrast, and if
necessary, correct information about musical artists, and music (work
 and their recordings). We only collect information about commercially released
music, because in this case, the artist and their representatives made
the music with information public and publicly retrievable. 

The data collection and the workflows follow reproducible research principles.

## Databases {#database}

- [x] The Write-In Database is a CC0, reusable database. 
- [x] The Opt-In Database contains highly sensitive personal information, and it is not released. 
- [x] With the consent of musical artists or their lawful representatives we overwrite information in the Write-In Database from more precise information in the Opt-In Database. We never release the Opt-In Database itself.

Both databases are created with the help of [RSQLite](https://rsqlite.r-dbi.org/), an extension package of the open-source R statistical environment that embeds the SQLite database engine in R, providing a DBI-compliant interface.

[SQLite](https://www.sqlite.org/index.html) is a public-domain, single-user, very light-weight database engine that implements a decent subset of the SQL 92 standard, including the core table creation, updating, insertion, and selection operations, plus transaction management.

The SQLite database is periodically updated and released.  You can import the entire database into MySQL, PostgreSQL, or any similar database engine of your choice.

## Authoritative copies {#zenodo}

We keep authoritative copies of periodic releases on [Zenodo](https://zenodo.org/), a European open science data repository. Zenodo was founded by CERN, and it is funded by the European Commission and its OpenAIRE project. Zenodo is completely independent from Musicautor, Reprex, or the Digital Music Observatory. The authoritative copies, once deposited on Zenodo, cannot be modified or deleted by the Listen Local partners.

The authoritative master copies of the Listen Local Write-In Databases, such as the Listen Local Bulgaria Write-In Database, have a permanent URL on Zenodo. You can reuse the database or its contents for any purpose with the only exception is that you cannot claim intellectual property on the database or its contents, and you must give credit to the database and its creators.

Under this permanent URL, you can find each periodic release under a different version number, date, and a globally unique Digital Object Identifier.  When re-using the database or its contents, pleasre refer to the citation information associated with this DOI number.

## Restful API {#api}

Our restful API is supported by [Datasette](https://datasette.io/), an open source multi-tool for exploring and publishing data.  Datasette helps to publish a SQLite database as an interactive website and accompanying API.

For an extended documentation visit [documentation.listen-local.net](https://documentation.listen-local.net/).
