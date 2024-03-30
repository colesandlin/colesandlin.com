---
title: "MMM-Streamflow Module"
date: 2023-11-21
weight: 1
# aliases: ["/first"]
# tags: ["first"]
author: "Cole Sandlin"
# author: ["Me", "You"] # multiple authors
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: false
# description: "Desc Text."
# canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: true
searchHidden: true
ShowReadingTime: false
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: false
ShowRssButtonInSectionTermList: false
UseHugoToc: false
cover:
    image: "images/mmm-streamflow-module.png" # image path/url
    # alt: "<alt text>" # alt text
    # caption: "<text>" # display caption under cover
    # relative: false # when using page bundles set this to true
    hidden: false # only hide on current single page
editPost:
    # URL: "https://github.com/<path_to_repo>/content"
    # Text: "Suggest Changes" # edit text
    # appendFilePath: true # to append file path to Edit link
---

According to Cambridge Dictionary, mudlarking is defined as “the activity of searching the mud near rivers trying to find valuable or interesting objects.” This is a hobby of mine, so I decided to create a [MagicMirror²](https://magicmirror.builders/) module using Node.js to help me determine when to go out. This module utilizes REST API calls to the [United States Geological Survey](https://www.usgs.gov/tools/usgs-water-services) to fetch and display real-time water data for the user’s location. Users can monitor measurements such as water level and flow rate for rivers, streams, and other bodies of water across the United States.
