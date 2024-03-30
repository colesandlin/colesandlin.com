---
title: "Pi-hole Implementation"
date: 2021-06-29
weight: 5
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
    image: "images/pi-hole-implementation.png" # image path/url
    # alt: "<alt text>" # alt text
    # caption: "<text>" # display caption under cover
    # relative: false # when using page bundles set this to true
    hidden: false # only hide on current single page
editPost:
    # URL: "https://github.com/<path_to_repo>/content"
    # Text: "Suggest Changes" # edit text
    # appendFilePath: true # to append file path to Edit link
---

[Pi-hole](https://pi-hole.net/) is an open-source software that acts as a DNS server which blocks advertisements and disables trackers on a network-wide level. I configured my instance to run on a headless Raspberry Pi Zero connected to my router through Ethernet. This device has improved my network’s privacy by preventing targeted advertising and security by stopping malicious advertisements from being served.
