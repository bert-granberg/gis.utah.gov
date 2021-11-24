---
title: 'Introducing the Official UGRC API Client'
author:
  display_name: Steve Gourley
  email: sgourley@utah.gov
date: 2021-11-23 20:18:45
categories:
  - Featured
  - Developer
tags:
  - geocoding
---

Assigning a geographic coordinate to an address, otherwise known as geocoding, is one of the simplest ways to enable data to be visualized on a map. This makes geocoding a gateway to a Geographic Information System (GIS). Because location matters to us, we make geocoding simple!

Since the creation of the [UGRC API](https://api.mapserv.utah.gov) over 10 years ago, UGRC has been building geocoding clients. A geocoding client is a piece of software that understands how to interact with the UGRC API, and hide the complexity, to make geocoding simple. The first [geocoding client](https://github.com/agrc/kitchen-sink/tree/main/packages/dartboard) enabled users in a [web application](https://atlas.utah.gov) to quickly find their house in aerial imagery and understand what is near them. An ArcGIS tool client brought the same functionality to desktop GIS. No user is going to be left out.

One-off address geocoding is very useful, but state agencies, local governments, private companies, etc., have large tabular datasets without locations. We built the ArcGIS [geocoding toolbox client]({% link data/address-geocoders-locators/index.html %}#GeocodingToolbox) to make the batch geocoding of hundreds of thousands of addresses simple. All of the clients that run within ArcGIS require an expensive software license. We think everyone should have free access to geocode Utah addresses --- and now they do.

The official [UGRC API client](https://github.com/agrc/api-client) is now available to everyone! This cross-platform desktop application carefully guides you through your geocoding tasks. We analyzed the data from our other clients and made great improvements to the user experience. We think this is the best API client we have ever created. Go [download](https://github.com/agrc/api-client/releases) the official UGRC API Client right now for [MacOS](https://github.com/agrc/api-client/releases/download/v1.5.0/UGRC.API.Client-1.5.0-x64.dmg) or [Windows](https://github.com/agrc/api-client/releases/download/v1.5.0/ugrc-api-client-1.5.0-win32-setup.exe) and start geocoding.

![first screen]({% link images/api-client/client.png %})
{: .flex .flex--center}

## A few highlights we are proud of

- No license is needed to use the client! It is download and go.
- The client is cross-platform. It works on [Mac](https://github.com/agrc/api-client/releases/download/v1.5.0/UGRC.API.Client-1.5.0-x64.dmg) and [Windows](https://github.com/agrc/api-client/releases/download/v1.5.0/ugrc-api-client-1.5.0-win32-setup.exe).
- The client is evergreen. The app will automatically download updates as soon as they are available. Every time the application restarts, it will be the best, most recent version.
- You only need to create one API key ever. Did your IP address change? No problem! Your access will not be interrupted.
- API keys are validated before the geocoding task starts. The create a key, try to geocode, fail, read the error message, create a new key, succeed loop is broken!

There are many improvements compared to our other desktop clients that you will need to download the app and see for yourself. We are not finished. We have many new features planned for this client that you will not want to miss.

![UGRC API Logo]({% link images/api-client/web_api_logo.png %})
{: .flex .flex--center }