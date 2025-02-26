---
title: "MMM-Streamflow Module"
date: 2023-11-21
author: "Cole Sandlin"
cover:
    image: "mmm-streamflow-module.png"
---

The Cambridge Dictionary defines mudlarking as “the activity of searching the mud near rivers trying to find valuable or interesting objects.” This happens to be a hobby of mine, so I decided to develop a [MagicMirror²](https://magicmirror.builders/) module using Node.js to help me decide when conditions are ideal for it. The module uses REST API calls to the U.S. Geological Survey’s [Instantaneous Values Service](https://waterservices.usgs.gov/docs/instantaneous-values/instantaneous-values-details/) to fetch and display real-time water data for the user’s location. Users can monitor measurements such as water level and flow rate for rivers, streams, and other bodies of water across the United States.
